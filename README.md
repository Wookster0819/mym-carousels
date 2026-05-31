# mym-carousels

Carousel CDN for **Maximize Your Medicare** (2026–2027 edition).

Separate from `mxr-carousels` (Maximize Your Retirement) by design — different
book, different CTA (maximizeyourmedicare.com), different brand.

## URL pattern
```
https://mym-carousels.vercel.app/{persona}/p{N}_{NN}_card{i}.png
```
- persona = folder ("persona1", "persona2", ...)
- p{N}    = persona number (p1..p10)
- NN      = zero-padded carousel number (01..30)
- i       = card index (1..5):  1 hook · 2 fact · 3 answer · 4 bio · 5 cover

## Contents
- `public/persona1/` — The 64-Year-Old (Enrollment Clock): 30 carousels × 5 cards = 150 PNGs
