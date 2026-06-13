# Early Bird Coffee — Kihei, Maui

Single-page marketing site for Early Bird Coffee, a locally owned coffee truck on
South Kihei Road serving premium Vietnamese coffee, ceremonial matcha, island
cold foams, croffles, and paninis.

**Live:** https://earlybirdcoffeesample.netlify.app/

## Stack
- One file, no frameworks: `index.html` (inline CSS + vanilla JS)
- Fonts: Fraunces + Hanken Grotesk (Google Fonts, non-render-blocking)
- Accessibility: semantic HTML, WCAG AA contrast, keyboard focus, reduced-motion support
- Imagery: CSS-generated (sun, rays, grain) — real photos go where marked with `PHOTO PLACEHOLDER` comments

## Deploy
Static site, no build step. Netlify serves the repo root (`publish = "."` in
`netlify.toml`). Push to the `main` branch and Netlify auto-deploys.

```bash
git add -A
git commit -m "Update site"
git push
```

## To finish before launch
- Replace the `PHOTO PLACEHOLDER` / `IMAGE` blocks in `index.html` with real photos
  (hero truck shot, story polaroid, Open Graph image at `assets/early-bird-og.jpg`).
- Confirm hours, phone `(808) 795-3141`, and address `1455 S Kihei Rd` are current.
