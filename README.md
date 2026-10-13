# Egypt GDP Dashboard

Responsive, interactive prototype of the **Egypt's GDP Landscape: Trends & Insights** dashboard (desktop, tablet, mobile).

## Features
- 5 KPI cards + 6 charts built from the GDP data sheet
- Hover tooltips on all charts
- Range sliders on the quarterly charts (drag handles, drag the selected range, or use arrow keys)
- Two-tier quarter / fiscal-year axis
- Scale animation on all cards (load + hover)
- Pure HTML / CSS / JavaScript — no build step, no dependencies

## Structure
```
index.html      # page, styles, data and chart code
assets/         # KPI icons (SVG, exported from Figma)
```

## Run locally
Open `index.html` in a browser, or serve the folder:
```bash
npx serve .
```

## Deploy on GitHub Pages
1. Push this folder to a GitHub repository.
2. Repository **Settings → Pages**.
3. Source: **Deploy from a branch** → branch `main`, folder `/ (root)` → Save.
4. The site will be live at `https://<username>.github.io/<repo-name>/`.

## Updating the data
All numbers are at the top of the `<script>` in `index.html`
(`GDP_ANNUAL`, `GDP_GROWTH`, `Q_GDP`, `Q_GR`, `SECTORS`, `TREEMAP`).
