# Jessica Pante Salinas — Portfolio

Simple static portfolio site for freelancing as a Funnel Builder & Shopify E-commerce Specialist.

## Structure

- `index.html` — main page
- `styles.css` — styling
- `script.js` — small JS (footer year)
- `assets/funnel-samples/` — put funnel/store screenshots here later

## Adding funnel samples

1. Drop image files into `assets/funnel-samples/` (e.g. `funnel-1.png`).
2. In `index.html`, inside `<div id="funnel-gallery" class="gallery">`, replace the placeholder div with items like:

```html
<div class="gallery-item">
  <img src="assets/funnel-samples/funnel-1.png" alt="Funnel sample 1" />
  <div class="gallery-caption">Skincare brand opt-in funnel</div>
</div>
```

3. Add as many `.gallery-item` blocks as needed.

## Deploy to Vercel

1. Push this repo to GitHub (already done if you're reading this from the repo).
2. Go to [vercel.com](https://vercel.com) → New Project → import this repo.
3. Framework preset: **Other** (static site, no build step needed).
4. Deploy.
