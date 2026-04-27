# SoT Portfolio Tracker — Marketing Site

Static landing page for [strategicoptionstrader.com](https://strategicoptionstrader.com).

## Stack

- Plain HTML + Tailwind CSS (CDN, no build step)
- Deployed on Cloudflare Pages
- Stripe Payment Links handle checkout

## Local preview

Open `index.html` directly in a browser — that's it. No build step, no `npm install`, no dev server required.

## Deploy

Cloudflare Pages auto-deploys on every push to `main`. Build settings:

- **Build command:** _(none)_
- **Build output directory:** `/`

## Links

- Production: https://strategicoptionstrader.com
- App: https://app.strategicoptionstrader.com
- Newsletter: https://optionsai.substack.com
- Stripe Payment Link (monthly + annual): https://buy.stripe.com/cNifZj1uFdgWeQSdtwdEs00

## Updating content

Edit `index.html` directly, commit, push. Cloudflare Pages rebuilds in ~30 seconds.

When swapping a real product screenshot in for the SVG mockup in the hero:
1. Save the screenshot as `hero-portfolio.png` in this folder
2. Replace the `<!-- Real-app-style screenshot mockup -->` block with `<img src="./hero-portfolio.png" alt="SoT Portfolio dashboard" class="rounded-t-lg shadow-2xl w-full" />`
