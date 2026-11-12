# Bonds videos

The "Bonds Educational Videos" playlist. Apps read `bonds-videos.json` from
jsDelivr; the videos themselves are in Supabase Storage.

```
Bonds/
  bonds-videos.json      # the catalog: every video, in display order
  thumbs/<video-id>.jpg  # 16:9 poster for the list and the player (1280x720 progressive JPEG, ~70–150 KB)
```

| What | Where |
| --- | --- |
| Catalog + thumbnails | This folder, served by jsDelivr from `main` |
| Videos (`<video-id>.mp4`) | Supabase public bucket `bond-videos`, served by Supabase's CDN: `https://izkualqyrhgozeydabjj.supabase.co/storage/v1/object/public/bond-videos/<video-id>.mp4` |

Videos are not kept here: jsDelivr does not serve GitHub files over 20 MB, and
the videos are uploaded at full quality.

## bonds-videos.json

| Field | Meaning |
| --- | --- |
| `id` | Kebab-case id; also the file name of the video and its thumbnail |
| `title` | Full video title |
| `tag` | Short label for a chip or card heading |
| `description` | One line under the title |
| `video_url` | Supabase public URL of the `.mp4` |
| `thumb_url` | jsDelivr URL of the thumbnail, used as the list image and `<video poster>` |
| `duration_seconds` | Length, rounded to whole seconds |

The array order is the display order.

## Adding a video

1. Name the file `<video-id>.mp4`. Make it start fast before uploading (moves
   the index to the front; no re-encode, no quality change):
   `ffmpeg -i in.mp4 -map 0 -c copy -movflags +faststart <video-id>.mp4`
2. Upload it with Webapp-backend's `backend/scripts/upload_bond_videos.py <folder>`
   (public, `video/mp4`, cached for a year). It skips files already in the bucket.
3. Add `thumbs/<video-id>.jpg`, add an object to `videos`, bump `count`, push.

The CDN and browsers cache each video for a year, so upload a changed video
under a new file name and update `video_url`, instead of overwriting it.

## Playlists

`../video-playlists.json` lists every playlist the apps show (Resources → Videos),
in display order. Each entry:

| Field | Meaning |
| --- | --- |
| `id` | Kebab-case id; used in links (`?playlist=<id>`) |
| `title` | Playlist name, e.g. "Bonds Educational Videos" |
| `description` | One or two lines for the playlist card |
| `catalog_url` | Path of the playlist's catalog, relative to the repo root |
| `cover_url` | Optional cover image path; the first video's thumbnail when missing |

To add a playlist: make a folder like this one (catalog + `thumbs/`), upload its
videos, then add an entry to `video-playlists.json` and push. No app deploy is needed.
