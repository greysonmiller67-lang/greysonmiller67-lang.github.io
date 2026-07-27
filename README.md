# greybits studio website

Static one-page site for the greybits studio — no build step, no dependencies beyond Google Fonts.

## Contents

- `index.html` — the whole site (hero, Games & Puzzles, Kids Corner, Everyday & Calm, About, footer)
- `styles.css` — all styling (Fraunces + Inter, candy-gradient light theme, responsive, reduced-motion safe)
- `assets/icons/` — the 12 live app icons, resized to 256px for the web

## Deploy to GitHub Pages

The site is a drop-in replacement for https://greysonmiller67-lang.github.io/:

1. Copy `index.html`, `styles.css`, and the `assets/` folder into the root of the `greysonmiller67-lang.github.io` repository (replacing the old `index.html`).
2. Commit and push — GitHub Pages redeploys automatically in a minute or two.

To preview locally, just open `index.html` in a browser.

## Updating later

- **New app goes live:** drop its 256px icon into `assets/icons/`, copy one `<a class="card">` block in the matching section of `index.html`, and edit the name / tagline / Play link. Bump the "12 apps live" stat in the hero.
- All Play links point at the real store pages; the "Follow the studio" teaser and nav/footer buttons point at the developer page (`dev?id=8067309061059365942`).
- Contact email in the footer: `greysonmiller67@gmail.com`.
