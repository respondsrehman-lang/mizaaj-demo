# Mizaaj Restaurant — Redesign Concept (Demo)

Unofficial one-page redesign concept for **Mizaaj Restaurant** ([mizaajrestaurant.com](https://mizaajrestaurant.com)) — fine dining, multi-cuisine restaurant in SMCHS, Shahrah-e-Faisal, Karachi.

**Live demo:** https://respondsrehman-lang.github.io/mizaaj-demo/

## What's different from the current site

- **Ivory & gold bright theme** — warm cream base with gold/terracotta accents, matching the restaurant's dark-gold logo, its printed menu design (ivory, terracotta headers, deep-green text) and the warm glow of its interiors.
- **Glassmorphic cards everywhere** — frosted-white glass (`backdrop-filter: blur + saturate`) layered over real food/interior photography so the imagery softly blurs through the cards. An `@supports` fallback keeps things readable where blur isn't supported.
- **Interactive menu with real data** — the current site shows menu scans as images; this concept rebuilds 12 categories / ~120 dishes (with actual prices) as a tappable, searchable-feeling category browser. Data transcribed from the restaurant's own menu book.
- Real photos hotlinked from the restaurant's site (aerial night hero, courtyard entrance, scale-wall dining room, tassel-chandelier atrium, open-air mocktail bar, giraffe room, signature dishes).
- Real business content: hours, weekday-only reservations, WhatsApp booking deep link (`wa.link/hna3yi`), events (birthday/corporate/Nikkah/Iftar), Google reviews, bank card discounts, map embed.

## Stack

Single self-contained `index.html` — no build step, no dependencies. Google Fonts (Cormorant Garamond + Jost), inline SVG icons, vanilla JS (menu tabs, scroll reveal, mobile nav). Reduced-motion and keyboard-accessible.

## Deploy (GitHub Pages)

```bash
git init
git add index.html README.md
git commit -m "Mizaaj redesign concept"
git remote add origin https://github.com/respondsrehman-lang/mizaaj-demo.git
git push -u origin main
```

Pages is enabled from the repo `Settings → Pages` (branch: `main`, root). Site appears at the URL above in a minute or two.

## Note

This is an unofficial concept demo. Images and menu content belong to Mizaaj Restaurant; all business details (phone 0301-9025777, address Plot 6-A SMCHS Karachi) were sourced from their live site. Verify pricing directly with the restaurant before relying on it.
