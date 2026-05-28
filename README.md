# Perdata.ai — Static Website

Six-page static site. No build step. Drop the folder onto Netlify, Vercel, Cloudflare Pages, or any static host.

## Pages

- `index.html` — Home
- `products.html` — The four-product ecosystem in detail
- `vision.html` — The manifesto: six principles
- `book.html` — Dying for Friendship and Community
- `team.html` — Founders and advisory bench
- `contact.html` — Investors, partners, press

## Files

```
perdata-website/
├── index.html
├── products.html
├── vision.html
├── book.html
├── team.html
├── contact.html
├── styles.css
└── README.md
```

## Design

Monochrome. Black ink, white paper, gray for mute. One typographic accent — italic serif for emphasis. Generous spacing. Nothing competes with the copy.

- Type pair: Fraunces (headings), Inter (body) — both loaded from Google Fonts
- No JavaScript dependencies beyond a 3-line mobile-nav toggle
- All links work cross-page

## To preview locally

```
cd perdata-website
python3 -m http.server 8000
# Open http://localhost:8000
```

## To ship

Drag the `perdata-website` folder onto Netlify or Vercel. Set the apex domain to `perdata.ai`. Done.
