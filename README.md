# FilmedByJaymes — Website

Live site: https://filmedbyjaymes.com (GitHub Pages, custom domain in `CNAME`)

Single-file site: everything is in `index.html`.

## Work thumbnails
Save a cover image for each Work card in `images/` as `work-1.jpg`, `work-2.jpg`, `work-3.jpg`, `work-4.jpg`
(16:10 works best, about 1280x800). Until they exist, the cards show a clean placeholder.
Card order: 1 = AMSC TikTok, 2-4 = Instagram Reels (links are in the Work section of `index.html`).

## Language toggle
EN is the text in the HTML. Spanish lives in the `ES` object near the bottom of `index.html`.
Each translatable element has a `data-i18n="key"` that matches a key in `ES`.

## Editing
- Colors / fonts: CSS variables in `:root`
- Results numbers: `.metric` blocks in the Results section
- Partners: `.partner` blocks in the Partners section
- Contact: email only (`filmedbyjaymes@gmail.com`)
