# Launch readiness — My First Arabic Words

Updated 13 October 2026. This continues the existing product and launch; it is not a restart.

## Existing assets and live paths
- Repository: https://github.com/deetox1/my-first-arabic-words-site
- Live site: https://deetox1.github.io/my-first-arabic-words-site/
- Product details: https://deetox1.github.io/my-first-arabic-words-site/product.html
- Free sample: https://deetox1.github.io/my-first-arabic-words-site/sample.html
- Seller-provided Ko-fi listing: https://ko-fi.com/s/19b1223756
- Prior product QA found the customer ZIP contains a 32-page workbook PDF, a 7-page flashcards PDF with 28 cards, and printing notes; the free sample is a separate 3-page PDF. ZIP integrity passed. Keep the paid ZIP out of the public repository.

## Verified in this round
- Latest GitHub Pages workflow 38421363291 succeeded for commit 83764582e34fd2261d18b6913b7a81f9befc2a5f: https://github.com/deetox1/my-first-arabic-words-site/actions/runs/38421363291
- Remote live HTTP checks returned 200 for homepage, product.html, sample.html and store-config.js. Homepage and product page link to the seller's Ko-fi listing; the free sample route remains separate. Responsive CSS breakpoints and product detail copy are present. Automated Ko-fi fetch returned HTTP 403 anti-bot challenge, not evidence of a listing defect. Browser-rendered mobile screenshot/tap testing was not available.
- Pinterest Business @simad9063, profile ID 1149684748533737244, is connected. Pinterest's profile resources reported the website claim verified at 2026-10-13T15:09:56Z.
- Public board Arabic Learning at Home | Printables belongs to simad9063, ID 1149684679816462776, privacy PUBLIC. Latest API reads confirm zero Pins. Do not publish to @forsaform.
- Six existing authentic Pinterest creatives were visually reviewed: 1000×1500 portrait PNGs, roughly 110–157 KB, readable and using genuine workbook/flashcard previews. Pin 3 is inside My_First_Arabic_Words_Launch_Kit_Updated_2026-10-13.zip; the other five variants are in the Library. Preserve these assets.
- Seller confirmed the current Ko-fi price is correct, the paid ZIP was attached when creating the product, and checkout offers credit-card and PayPal options that appear to work. No real purchase was made. Post-payment download delivery and seller payout/withdrawal remain untested. Do not ask the seller to repeat these checks or make a charge just to test.

## Remaining blocker: Pinterest production publishing
The connected Pinterest API application has Trial access. The previous production create-Pin attempt was rejected and the storefront SVG was also rejected as a broken image. Do not retry production publishing until Standard access is approved. The authorized integration exposes no control to change this access tier.

Manual action: sign in at https://developers.pinterest.com/ → My apps → select the existing app → request Standard access. Provide a demo video showing the OAuth authorization flow and live Pinterest integration, submit the request, and wait for Pinterest's decision. Official guide: https://developers.pinterest.com/docs/key-concepts/access-tiers/ . After approval, use existing PNG bytes or a public PNG URL, not the rejected SVG; publish one Pin at a time and verify its ID, public URL, board placement and destination.

## Commercial payment receipt and withdrawal in Algeria
- Ko-fi is a direct-payment service: funds go to connected PayPal or Stripe, not a Ko-fi balance. Official guidance: https://help.ko-fi.com/hc/en-us/articles/115003980093-How-do-I-get-paid
- Algeria is not listed among Stripe's supported business countries: https://stripe.com/global. Do not plan on a standard Stripe account based in Algeria.
- PayPal Algeria's official receiving help says the account must confirm its email and a Visa credit card or US bank account; it describes transfers to an eligible Visa card or US bank account. The actual eligible withdrawal destinations are account-specific; check the seller's own PayPal Wallet. Official page: https://www.paypal.com/dz/cshelp/article/comment-recevoir-de-largent-avec-paypal%C2%A0-help667?locale.x=fr_DZ
- Do not rely on a card/account owned by another person unless PayPal and the issuer explicitly confirm the arrangement is allowed. No financial account was connected and no incoming commercial payment or withdrawal has been tested.

## Next actions
1. Request Standard access for the existing Pinterest app with the required compliant demo video; wait for approval.
2. Publish the six existing creatives gradually (about 3–4 distinct Pins weekly), using direct Ko-fi links for purchase-intent traffic. Verify every Pin before continuing.
3. In the seller's own PayPal account, verify commercial receiving status, limitations, any required identity/business verification, and eligible withdrawal destinations.
4. Review real saves/outbound clicks after 2–4 weeks. The milestone is a confirmed purchase, not impressions alone.

No Pin has been published; no sale, payment, payout or withdrawal is claimed. No ads were bought and no metrics were fabricated.

## Independent readiness check — 2026-10-14

- Rechecked the deployed GitHub Pages URLs from a remote HTTP client: homepage, `product.html`, `privacy.html`, `terms.html`, `support.html`, `sample.html`, `store-config.js`, `assets/store-product-image.svg`, `assets/pinterest-app-icon.svg`, and the free-sample release PDF all returned HTTP 200. This confirms URL reachability and that the privacy URL is publicly accessible; it does not replace a visual browser test.
- The Ko-fi listing `https://ko-fi.com/s/19b1223756` returned HTTP 403 to the independent checker. Its live price, preview gallery, paid attachment, checkout methods, and post-purchase download behavior therefore remain **unverified**. Do not infer payment eligibility or delivery from the listing URL alone.
- The existing site had no canonical URL metadata or favicon links. Added canonical URLs to the existing static pages, reused the existing brand SVG as the favicon, and added Open Graph URL/image and Twitter card metadata to the homepage and product page. Existing responsive layout and brand artwork were preserved.
- Corrected stale copy on `sample.html` and `support.html` that said checkout was not active / the store would open later, despite the existing Ko-fi listing being configured. The wording now directs visitors to check the live listing without claiming checkout or automatic delivery is verified.
- Narrowed the privacy policy to the actual owner-account board/Pin workflow and removed conditional analytics language; the app is not represented as reading general users' content or retrieving analytics.
- Reconciled the 14-day calendar to the current business board `Arabic Learning at Home | Printables` on `@simad9063` (board ID `1149684679816462776`) and the canonical Ko-fi URL. Added `marketing/pinterest-six-pin-publishing-pack.csv` for the six prepared PNG creatives. Each draft remains unpublished and clearly flags the owner-only storefront check and the API Standard-access blocker.
- Payment readiness still requires the owner to confirm that their actual Algeria-based payment account can receive international commercial payments and withdraw funds through a provider-permitted method. No payment or withdrawal was tested.
