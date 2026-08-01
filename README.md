# jacobv25.github.io — portfolio

Personal portfolio site for Jacob Valenzuela: software engineering + agentic AI work.

- **Stack:** hand-written static HTML/CSS, no framework, no build step, no trackers.
- **Structure:** `index.html` (single page) · `css/style.css` · `assets/` (résumé PDF).
- **Deploy:** GitHub Pages, straight from `main` (no action needed beyond push).

## Local preview

```sh
open index.html          # or any static server, e.g.:
python3 -m http.server 8000
```

## Updating

- Résumé: replace `assets/Jacob_Valenzuela_Resume.pdf` (source of truth lives in `~/job-hunting/resume/`).
- Projects: edit the cards in `index.html` — each is a self-contained `<article class="card">`.
