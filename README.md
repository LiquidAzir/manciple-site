# Manciple landing site

Static, dependency-free landing page for `manciple.org`.

- `index.html`, `styles.css`, `app.js` — page source and interactions.
- `assets/` — brand art, narrated video, poster, and demo product screenshots.
- Product status is intentionally explicit: Gmail works today; other channels are roadmap concepts.
- The original 28-second watch page remains at `https://liquidazir.github.io/manciple-watch/`.

To preview locally, run `python3 -m http.server 8877 --directory marketing/manciple-site` from the repository root and open `http://127.0.0.1:8877/`.

The public site source is deployed via Vercel from `LiquidAzir/manciple-site`; this private repository keeps the working source alongside the product and pitch materials.
