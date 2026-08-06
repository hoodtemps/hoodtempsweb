# hoodtemps.ca

The Hoodtemps website — a single static page, bilingual (FR/EN), zero build step, zero dependencies.

- Everything lives in `index.html` (content, styles, and the little language-toggle script).
- French is the default; the toggle remembers the visitor's choice and first-time visitors with an English browser get English.
- `.nojekyll` tells GitHub Pages to serve the files as-is. In the repo's **Settings → Pages**, the source should be **Deploy from a branch**.
- `CNAME` points the site at hoodtemps.ca.
- `assets/images/` holds the logo files for print/social use; the page itself uses an inline SVG and needs no assets.

To edit the site, edit `index.html` and push. That's it.
