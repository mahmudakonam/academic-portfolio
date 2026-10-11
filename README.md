# Md Mahmud Akon — Academic Portfolio

A responsive academic portfolio featuring research interests, publications, engineering projects, experience, and research notes.

## Structure

- `dist/index.html` — main portfolio
- `dist/blog/` — research-note articles
- `dist/assets/` — CV and brand assets
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment

## Local preview

```bash
python3 -m http.server 4173 --directory dist
```

Then open `http://localhost:4173`.

Every push to `main` deploys the contents of `dist` to GitHub Pages.
