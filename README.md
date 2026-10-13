# Project page: Spatial Stiffness Tuning for Soft Crawling Robots

Static project page for Meitani & Nisar, *IEEE Access* 14 (2026), doi:10.1109/ACCESS.2026.3697215.

## Adding your media
Drop files at these exact paths and they appear automatically. Until then a "coming soon" placeholder is shown.

| Slot | Path | Status |
|---|---|---|
| Main project video (hero) | `static/videos/teaser.mp4` | **missing** |
| Untethered demo video | `static/videos/untethered.mp4` | **missing** |
| Figs. 1–9 | `static/images/fig1_principle.png` … `fig9_untethered_turn.webp` | in place |

Videos: H.264 MP4, ideally under ~10 MB each (GitHub's file limit is 100 MB).
To embed a YouTube video instead, replace the `teaser` figure in `index.html` with a YouTube `<iframe>`.

## Publishing on GitHub Pages
1. Create a repo (e.g. `soft-crawler`) and push the contents of this folder to it.
2. Go to Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. The site goes live at `https://<username>.github.io/soft-crawler/`.

## Local preview
```bash
python3 -m http.server 8000
```
