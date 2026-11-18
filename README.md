# nshinjiPortfolio

Personal portfolio of nshinjii.

## Pages
- `index.html` – main site (websites, pricing, contact)
- `thumbnails.html` – separate thumbnails page (`/thumbnails.html`)
- `privacy.html`, `terms.html`, `404.html`

## Updating thumbnails
1. Put the image in `/thumbnails` (.jpg or .webp, ~1280px wide, under 300KB).
2. In `thumbnails.html`, add it to the `THUMBS` list near the top of the script:
   `{src:'/thumbnails/my-thumb.jpg', alt:'What the thumbnail shows', platform:'youtube'},`
   (platform: `youtube`, `tiktok` or `instagram`)

Thumbnail prices live in the `PACKS` list in the same script (US dollars; £ is worked out automatically).
