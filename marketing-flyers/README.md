# Marketing flyers

Served by jsDelivr from `main`; the IFA web app reads `marketing-flyers.json`.

```
marketing-flyers/
  marketing-flyers.json  # the catalog: every flyer and its languages
  en/<flyer-id>.jpg      # one folder per language code
  hi/<flyer-id>.jpg
  ta/<flyer-id>.jpg
  thumbs/<flyer-id>.jpg  # small English copy for the app's grid
```

## Image format

Save every flyer as a progressive JPEG, 900px wide (quality ~82, about
100–180 KB). Thumbnails are 450px wide (quality ~75, about 30–50 KB). Never
commit full-size PNG exports: the app downloads every image, so a 1 MB file
makes the grid and the language switch slow.

```sh
# with Pillow installed
python3 -c "from PIL import Image; im=Image.open('in.png').convert('RGB'); \
im.thumbnail((900, 10000), Image.LANCZOS); \
im.save('en/<flyer-id>.jpg', quality=82, optimize=True, progressive=True)"
```

## marketing-flyers.json

```json
{
  "version": 2,
  "flyers": [
    {
      "id": "autopilot",
      "title": "Investments on Autopilot",
      "image_url": "https://cdn.jsdelivr.net/gh/Dhansaarthi/assets@main/marketing-flyers/en/autopilot.jpg",
      "thumb_url": "https://cdn.jsdelivr.net/gh/Dhansaarthi/assets@main/marketing-flyers/thumbs/autopilot.jpg",
      "tags": ["SIP"],
      "crop_top": 90,
      "languages": {
        "en": { "title": "Investments on Autopilot", "image": "en/autopilot.jpg" },
        "hi": { "title": "ऑटोपायलट पर निवेश", "image": "hi/autopilot.jpg" }
      }
    }
  ]
}
```

- `title` and `image_url` are the English version for the app version that is
  live now; remove them from every flyer once the multi-language app ships.
- Language keys are codes (`en`, `hi`, `ta`, `te`, `kn`, `ml`, `mr`, `gu`, `bn`);
  the app maps them to labels. The grid shows the English version, and the
  preview shows a language switcher only for flyers with more than one language.
- `thumb_url` is what the grid loads; without it the grid falls back to the
  full image.
- `image` is a full URL or a path relative to this folder. `crop_top` (pixels
  trimmed from the top of the personalised preview) can also be set per
  language to override the flyer's.
- **Add a translation:** drop the image in `<code>/` under the same flyer id and
  add an entry under that flyer's `languages`.
- **Add a flyer:** add an object to `flyers` with at least one language, and a
  thumbnail in `thumbs/`.
- Upload a changed image under a new file name; the workflow purges changed
  files from jsDelivr on every push to `main`.
