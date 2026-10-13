# Sisi Zheng 郑思思 — academic homepage
Static site: `index.html` + `style.css` (+ `publications.json`). No build step needed; data is embedded in index.html.
## Deploy (GitHub Pages)
1. Create a public repo named **sisi-wiciel.github.io** on GitHub.
2. Upload index.html, style.css, publications.json (and photo.jpg if used) to the `main` branch root.
3. Settings → Pages → Deploy from branch `main` / root. Site: https://sisi-wiciel.github.io
## Photo
`photo.jpg` is used in the hero circle (falls back to "SZ" if missing). Replace it with a higher-resolution square photo for best quality.
## Updating publications
Source files live outside this folder (academic-homepage-src: pubs.tsv, cv.md, template.html, build.py). Edit them and run `python3 build.py`.
