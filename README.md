# rafay. — Portfolio (Muhammad Rafay Uddin)

Single-page portfolio: `index.html` (inline CSS + JS) + `/media`. No build step — deploy on Vercel as a static site.

## Edit your content
All content lives in the `<script>` at the bottom of `index.html`:
`PROJECTS`, `BRANDS`, `TOOLS`, `SKILLS`, `JOBS`, `FEED`, `INSTAGRAM`. Look for `REPLACE`.

## Files to add (missing media shows a gradient placeholder until you add it)
- `media/rafay.webp` — yellow-background portrait (4:5, ~880×1100)
- `media/<folder>/<slug>/cover.webp` — one cover per project
- `media/<folder>/<slug>/01.webp, 02.webp…` — viewer images (edit `media:` in PROJECTS for more/fewer)
- `media/animations/<slug>/*.mp4` and `media/social-media-reels/<slug>/reel.mp4` — videos (H.264 MP4, 9:16)
- `media/feed/01.webp … 06.webp` — latest Behance/Instagram post thumbnails
- Folders: logo-and-guidelines · packaging-design · print-media-designs · illustrations · animations · amazon-a-plus-content · social-media-post · social-media-reels
- `media/og.jpg` (share image) and `media/apple-touch-icon.png` are already included.
