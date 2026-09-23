# No Frontier Travel Collective

Static site for **No Frontier Travel Collective** — tagline: Mountains · Oceans · And Beyond.

## Information architecture

| Path | Page |
|------|------|
| `/` (`index.html`) | Brand homepage — hero, story, featured trip teaser, About |
| `/trips/` (`trips/index.html`) | Trips index — live offerings (Niseko) + “more coming” placeholder |
| `/trips/niseko/` (`trips/niseko/index.html`) | Hilton Niseko Village trip detail — inclusions, prices, photos, book CTA |

## Live preview

GitHub Pages (from `main`):

- https://ficknargo.github.io/nofrontier-site/
- https://ficknargo.github.io/nofrontier-site/trips/
- https://ficknargo.github.io/nofrontier-site/trips/niseko/

## Open locally

```bash
# From this folder:
python3 -m http.server 8080
# then visit http://localhost:8080
```

Relative paths — nested pages use `../` / `../../` for CSS, assets, and photos.

## Brand / product notes

- Public name: **No Frontier Travel Collective**
- Tagline: Mountains · Oceans · And Beyond
- Niseko land: **$2,995**/person · with 6-day Niseko United: **$3,495**/person
- Book CTA (Niseko only): `mailto:booking@nofrontiertravel.com?subject=Hilton%20Niseko%20Village%20Jan%202027`
- Instagram: [@nofrontiertravelco](https://www.instagram.com/nofrontiertravelco/)

## Open items

- **GroupCollect book URL** — TBD. Mailto stays live until GC link is wired.

## Contents

- `index.html` — brand home
- `trips/index.html` — trips list
- `trips/niseko/index.html` — Niseko trip
- `styles.css` — shared styles
- `site.js` — mobile nav toggle
- `assets/` — logos (seal, header, watermark, logo)
- `photos/` — hero + grid images
