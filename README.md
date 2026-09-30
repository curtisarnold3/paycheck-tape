# The Paycheck Tape

How the money system ate the American income, 1913–2026. A chart-first companion site to the book: one screen per chapter, navigable from one URL, no infinite scroll.

## Deploy on GitHub Pages
1. Create a repo (e.g. `paycheck-tape`) and push these files to the `main` branch.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. The site appears at `https://<user>.github.io/paycheck-tape/` within a minute or two.

Everything is static: `index.html` plus `charts/*.png`. No build step.

## Regenerating charts
Charts come from the FRED CSVs in the book project via `make_charts.py` / `make_charts2.py` (dark palette in `dark.py`). Drop new PNGs into `charts/` keeping the same filenames.
