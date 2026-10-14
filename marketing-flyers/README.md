# Marketing flyers

Served by jsDelivr from `main`; the IFA web app reads `marketing-flyers.json`.

```
marketing-flyers/
  marketing-flyers.json  # the catalog: every flyer and its languages
  en/<flyer-id>.jpeg   # one folder per language code
  hi/<flyer-id>.jpeg
  ta/<flyer-id>.jpeg
```

## marketing-flyers.json

```json
{
  "version": 2,
  "flyers": [
    {
      "id": "autopilot",
      "title": "Investments on Autopilot",
      "image_url": "https://cdn.jsdelivr.net/gh/Dhansaarthi/assets@main/marketing-flyers/en/autopilot.jpeg",
      "tags": ["SIP"],
      "crop_top": 90,
      "languages": {
        "en": { "title": "Investments on Autopilot", "image": "en/autopilot.jpeg" },
        "hi": { "title": "ऑटोपायलट पर निवेश", "image": "hi/autopilot.jpeg" }
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
- `image` is relative to this folder. `crop_top` (pixels trimmed from the top of
  the personalised preview) can also be set per language to override the flyer's.
- **Add a translation:** drop the image in `<code>/` under the same flyer id and
  add an entry under that flyer's `languages`.
- **Add a flyer:** add an object to `flyers` with at least one language.
- Upload a changed image under a new file name; the workflow purges changed
  files from jsDelivr on every push to `main`.
