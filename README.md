# Candle Signal Pro — Starter Product Package

## What it does
- Mobile-friendly installable web app (PWA) for Android browsers.
- Imports user-provided OHLC CSV data.
- Displays educational CALL / PUT / WAIT analysis for selected 1m or 5m datasets.
- Provides a basic historical price-movement backtest.
- Keeps uploaded CSV processing in the browser.
- No Quotex login, scraping, account connection, or automatic trading.

## Files
- `index.html` — app UI and analysis logic
- `manifest.webmanifest` — installable web app metadata
- `sw.js` — basic offline cache for hosted use
- `icon.svg` — simple app icon

## CSV format
Headers required: `time,open,high,low,close`
Use completed candles, in chronological order. Prepare separate CSV files for 1-minute and 5-minute data.

## Test locally
Open `index.html` in a modern browser and upload a CSV. Some PWA/offline features only work when served via HTTPS or localhost.

## Host free (example: GitHub Pages)
1. Create a GitHub account and a new public repository.
2. Upload all package files to the repository root.
3. In repository Settings → Pages, choose deploy from branch and select the main branch/root.
4. Open the published HTTPS URL on Android Chrome.
5. Use Chrome menu → Add to Home screen / Install app (wording may vary).

## Selling / publishing checklist
- Change name, colors, copy and support contact to your own brand.
- Do not imply affiliation with Quotex or guarantee earnings.
- Review the platform, broker, advertising and app-store rules before publishing.
- If selling access, add a lawful payment and licensing system; this starter has no user accounts, payments, subscription checks, or server-side entitlement system.
- Test with independent historical data and demo use before marketing any performance claims.
- Keep the app analysis-only. It does not execute trades.

## Strategy and risk limitations
The included EMA/RSI rule is an educational example, not a proven profitable strategy. Backtest results do not model binary-option payout rates, OTC pricing, spread, slippage, platform execution, or all costs. No financial result is promised.
