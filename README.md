# RateRight

RateRight is a calm, premium, 100% client-side rate calculator for freelancers and consultants: enter your discipline, experience, client market and leverage signals, and it dials in a defensible **Floor / Recommended / Premium** rate range — complete with a citable justification and three copy-paste quote scripts so you can charge what you're actually worth without flinching. The hero is a live, animated "value dial" that settles on your recommended number as you tune the inputs.

**Live → (set on deploy)**

## How it works

- **Free tier (keyless, private):** All the math runs in your browser. A market baseline for your discipline is adjusted by experience band, client region, pricing model (hourly / day / project), and the leverage signals you select. You get an instant rate range, an equivalent day rate + annual figure, a transparent justification, a current-rate reality check, and three quote scripts you can copy and send. No backend, no signup, no tracking — nothing ever leaves the page.
- **Pro tier (bring your own key):** Paste your own GLM (z.ai) API key and a sentence about a specific client. RateRight sends the computed numbers to the official z.ai endpoint (client-side, from your browser only) and returns a custom justification + a ready-to-send quote message in a sharp, human voice. Your key stays in the tab and is sent nowhere except z.ai.

## Tech

Single self-contained `index.html` — inline CSS/JS, Google Fonts via CDN (Bricolage Grotesque / Plus Jakarta Sans / Space Mono), an animated `<canvas>` rate dial, `prefers-reduced-motion` and visible-focus support, responsive to mobile, plus SEO (title, meta description, OpenGraph, JSON-LD FAQPage). No build step, no dependencies — deploy the file as-is to any static host (e.g. GitHub Pages).

## Affiliate disclosure

The optional "Get a GLM key" button links to z.ai via a referral link (`https://z.ai/subscribe?ic=BWTG6TRYYQ`, 5% off). It's a referral — it helps keep RateRight free and costs you nothing extra. The tool is fully functional without ever clicking it; the AI features are entirely optional and only use **your** key, client-side.
