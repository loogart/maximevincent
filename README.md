# Maxime Vincent — Avocat | Lawyer

A responsive legal services website. French is the primary language on every page load. English is secondary and available using the EN language switch.

## Files

- `index.html` — page structure and bilingual copy
- `style.css` — responsive styling and brand palette
- `app.js` — language toggle and seven service cards
- `assets/` — supplied logo and photography

## Run locally

No installation or build step is required. From this folder, run:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the contents of this folder to its root.
2. In the repository, open Settings → Pages.
3. Select Deploy from a branch, choose `main` and `/ (root)`, and save.

The included `.nojekyll` file allows GitHub Pages to serve the files directly.

## Customize

Edit bilingual text in `index.html` and service descriptions in `app.js`.
Brand colors and layout are in `style.css`. The consultation link points to
https://calendly.com/mvincent-vincentavocats.

Fonts (DM Sans and Libre Caslon Display) load from Google Fonts with local fallback fonts.
All imagery is included. There is no backend, package manager, or build dependency.

Review professional copy and rights to supplied assets before making the repository public.
