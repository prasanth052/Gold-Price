# Tamil Nadu Gold Rate Live Dashboard & Estimator

A modern, responsive, real-time gold market price dashboard and retail jewelry billing estimator for Tamil Nadu (Chennai / MJDMA benchmark).

## Features
- **Live USD/INR Hourly Sync:** Fetches exchange rates from [ExchangeRate-API](https://open.er-api.com/v6/latest/USD) with a smart 1-hour `localStorage` cache.
- **Dynamic International Spot Input:** Enter any Spot Gold price ($/oz) to instantly update Tamil Nadu prices.
- **Tamil Nadu Benchmark Rates:**
  - 22K Gold 1 Sovereign (8 Grams / பவுன்) [Hero card]
  - 22K Gold 1 Gram
  - 24K Pure Gold (1 Gram & 8 Grams)
- **Mode Toggle:** Switch between **Board Rate** (daily shop display) and **Retail Price** (inclusive of 3% GST).
- **Interactive Jewelry Bill Estimator:** Calculate real-time final store bills with weight, Wastage/VA %, 3% GST, and BIS HUID Hallmarking fee.
- **Tariff Audit:** Transparent breakdown of import duties (5% BCD + 1% AIDC), landed costs, and MJDMA physical margins.

---

## How to Deploy to Netlify (1-Minute Setup)

### Option A: Drag & Drop (No Git Required)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `gold-dashboard` folder directly into the browser.
3. Your site is live immediately with a free HTTPS URL!

### Option B: Netlify CLI
```bash
cd gold-dashboard
npx netlify-cli deploy --prod
```

---

## How to Deploy to Vercel

```bash
cd gold-dashboard
npx vercel --prod
```

---

## How to Preview Locally

Double click `index.html` in your file explorer, or run:
```bash
npx serve gold-dashboard
```
