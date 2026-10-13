# My First Arabic Words — landing page

A responsive international landing page for the existing Arabic–French printable learning bundle.

## Pages
- `index.html` — international home page, audience, product overview and FAQs.
- `product.html` — full product listing with real bundle contents and current checkout status.
- `sample.html` — sample information page.
- `privacy.html`, `terms.html`, `support.html` — existing policy and support pages.
- `assets/store-product-image.webp` — existing product artwork.
- `store-config.js` — safe public switch for the verified external checkout URL.

## Checkout activation
Paid checkout is intentionally inactive until the seller has an eligible payment account, uploads the customer bundle to a storefront that delivers digital files after payment, confirms its payout method, and tests that storefront's buyer journey. Then put the exact published product URL in `store-config.js` and set `provider` to its actual name. This file contains no payment credentials.

The planned one-time price is US$5.99. This is not a promise that sales or withdrawals are active.

## Sample asset
The 3-page sample is served from the existing GitHub Release; it is distinct from the paid 32-page workbook and 28-card flashcard bundle. Never upload the paid customer ZIP into this public repository.

## International positioning
The page targets families, homeschoolers and educators worldwide who want beginner Arabic resources, including households that benefit from French translations. Digital files are formatted for A4 printing.