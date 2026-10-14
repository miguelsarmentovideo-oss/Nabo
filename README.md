# Nabo Gastro Bar — nabobergen.no

One-page website for Nabo Gastro Bar, Strandgaten 87, Bergen. Plain HTML, CSS and a few lines of JavaScript. No build step.

Built on the **Nabo Gastro Bar Design System** (Claude Design): colours (copper, night, cream, glow), type (Big Shoulders Display, Instrument Serif, Hanken Grotesk via Google Fonts), pill buttons with hard "stamp" shadows. All copy is in English, British spelling.

## Files

- `index.html` — the whole page: hero, hours strip, about, menu, photos, visit, Instagram, footer
- `styles.css` — design tokens at the top, then sections
- `script.js` — mobile menu toggle
- `assets/logo/` — `nabo-logo-on-dark.png` (cream shadow, for dark backgrounds) and `nabo-logo.png` (original)
- `assets/venue/` — venue photos (`*.webp` full size, `*-sm.webp` for smaller slots)
- `assets/gallery/` — older food photos, not used on the page right now

## Updating

- **Menu / prices:** edit the `<article class="dish">` blocks in the Menu section of `index.html`.
- **Opening hours:** change both the hours strip near the top and the Visit section, plus the `openingHoursSpecification` block in `<head>`.
- **Booking link:** search for `booking.gastroplanner.no`.
