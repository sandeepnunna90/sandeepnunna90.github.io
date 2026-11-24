# sandeepnunna90.github.io

Personal site. Plain HTML and CSS, no build step, served by GitHub Pages from `main` (root folder).

- `index.html` — the page
- `assets/styles.css` — all styles
- `assets/og.png` — link-preview image (1200x630), generated from `assets/og.html` (command inside that file)
- `assets/favicon.svg` — tab icon

Preview locally:

```bash
python3 -m http.server 8000
```

`resume.pdf` is a web copy of the main resume with the phone number removed. To refresh it, export the
current resume without the phone line and replace the file.
