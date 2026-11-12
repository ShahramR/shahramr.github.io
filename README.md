# shahramr.github.io

Personal academic website of **Shahram Rahimi, Ph.D.** — Professor and Head of the
Department of Computer Science, University of Alabama.

Built as a static site (plain HTML/CSS, no build step) and hosted on GitHub Pages.

## Structure

- `index.html` — main page (about, research, selected publications, lab, service, contact)
- `publications.html` — full publication list grouped by year
- `assets/style.css` — all styling
- `assets/photo.jpg` — *(optional)* add a portrait photo here, then in `index.html`
  replace the `<span class="monogram">SR</span>` line with
  `<img src="assets/photo.jpg" alt="Portrait of Shahram Rahimi">`

## Updating

Edit the HTML files directly and push to `main`; GitHub Pages redeploys automatically.

### Keeping Scholar data current

The citations / h-index / i10-index banner on `publications.html` and the
selected publications on `index.html` are plain HTML — refresh the numbers from
https://scholar.google.com/citations?user=cRqh6lwAAAAJ&hl=en and bump the
"as of" date. The "Chronological archive" in `publications.html` is also plain
HTML, generated from the Scholar profile — add new papers to the top year
section, or ask Claude to re-sync everything from the live profile.
