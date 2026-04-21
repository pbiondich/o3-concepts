# OpenMRS 3 — Patient Chart Explorations

A static site with two design artifacts for the O3 patient chart:

- **`replica.html`** — faithful clickable recreation of the production chart
- **`redesign.html`** — three redesign variants on a side-by-side canvas
- **`index.html`** — landing page linking to both

All files are fully self-contained (React, styles, data, fonts inlined). No build step.

## Deploy to GitHub Pages

1. Create a new repo and drop these three files at the root (or inside `/docs`).
2. **Settings → Pages → Source:** Deploy from a branch → `main` / `/` (or `/docs`).
3. Wait a minute. The landing page lives at your Pages URL; the two chart views at `/replica.html` and `/redesign.html`.

## Local preview

Just open `index.html` in a browser. No server needed.

## Credits

Derived from [OpenMRS](https://openmrs.org) / [openmrs-esm-patient-chart](https://github.com/openmrs/openmrs-esm-patient-chart) — MPL 2.0. Design prototype, not a production build.
