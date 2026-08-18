# ryoichirosatake.github.io

Ryoichiro Satake's personal site. Plain HTML/CSS, no build step, no framework.

## Structure

- `index.html` — Home
- `research/index.html` — Research (`/research/`)
- `ja/index.html` — Japanese page (`/ja/`)
- `css/style.css` — shared stylesheet
- `uploads/` — static files (e.g. CV)

## Development

Open `index.html` directly in a browser, or serve locally:

```bash
python3 -m http.server
```

## Deploy

Pushes to `main` are deployed to GitHub Pages via `.github/workflows/deploy.yml`.
