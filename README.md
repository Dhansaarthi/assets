# Dhansaarthi assets

Static files for Dhansaarthi apps, served by jsDelivr from `main`:

```
https://cdn.jsdelivr.net/gh/Dhansaarthi/assets@main/<path>
```

| Folder | What it holds | Docs |
| --- | --- | --- |
| `marketing-flyers/` | Flyer catalog and images, per language, for the IFA web app | [marketing-flyers/README.md](marketing-flyers/README.md) |

## CDN cache

`.github/workflows/purge-cdn.yml` purges every file changed in a push to `main`
from jsDelivr. To purge specific files by hand, run the workflow from the
Actions tab with space-separated paths, e.g.
`marketing-flyers/marketing-flyers.json`.
