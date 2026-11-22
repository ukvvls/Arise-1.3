# ARISE 1.3 — Evolution

A new, independent mobile-first financial dashboard built as a static website. It is not a rename of ARISE 1.2.

## Features
- Dark obsidian workspace with translucent glass panels and accent-only glow.
- Arabic RTL and English LTR interface toggle.
- Independent page designs for markets, commodities, currency, news, company radar, and intelligence.
- Reference FX conversion via Frankfurter API (ECB reference rates). Values are shown with a date and are not live trading quotes.
- GDELT news feed links open the original publisher.
- Company directory is a static reference list; no stock values are fabricated.
- Markets and commodities explicitly indicate that their price feeds are not connected.
- Local text helper for simple summaries; no AI service/API is implied.
- Mobile bottom navigation.

## Deploy on GitHub Pages
1. Upload the contents of this folder to the repository root.
2. Open **Settings → Pages** and choose **GitHub Actions** as the source (if not already selected).
3. The included workflow deploys the root directory on pushes to `main`.

## Data notes
- Currency: `https://api.frankfurter.app` — ECB-based reference rates, not intraday trading data.
- News: GDELT open document API. Availability may vary; news links point to publishers.
- Markets, gold, silver, and oil intentionally remain blank until a reliable source is selected.

## Project files
`index.html`, `style.css`, `app.js`, `manifest.webmanifest`, `favicon.svg`, `.github/workflows/deploy.yml`
