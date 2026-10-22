# Hank – Guangzhou China Sourcing Site

Static site, no build step. Live URL: https://hanzaiheng-cpu.github.io/hank/  (all internal links are relative).

## Files
- `index.html` – landing page: services, Services & pricing (Fiverr $40/$100/$180 + custom), how it works, categories, Guides cards, Watch (YouTube) box, FAQ, contact, **free quote form**
- `style.css` – shared styles (incl. print CSS)
- `checklist.html` – printable Canton Fair & Guangzhou Sourcing Checklist (lead magnet)
- `guides/canton-fair-phase-2.html` – Canton Fair Phase 2 (Oct 23–27, 2026) guide
- `guides/1688-buying-guide.html` – buying from 1688 via an agent
- `sitemap.xml`, `robots.txt` – SEO
- `README.md`

## ⚠️ Replace CONTACT_EMAIL
The quote form opens the visitor's email app via `mailto:`. Set your address in ONE place: `index.html`, near the bottom:
```js
const CONTACT_EMAIL = "CONTACT_EMAIL";   // -> "you@example.com"
```
Until replaced, the form will not reach you.

## To do
- Swap the "Watch on YouTube" link (index.html `#watch`) for the channel URL once it exists.
- Fiverr is the source of truth for prices; update the pricing block if gig prices change.
- Submit `sitemap.xml` in Google Search Console after deploy.
- Content rules: no testimonials, stats, client logos or ages unless real. No hashtags.

## Preview
`python3 -m http.server` here, then http://localhost:8000
