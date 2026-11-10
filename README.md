# VSPR website

This is an editable static rebuild of the reference website, rebranded for VSPR while preserving the original layout, responsive navigation, product selectors, FAQ, policies page and checkout-link mechanism.

## Preview locally

Open `index.html` directly, or serve this folder with any static web server. For example:

```powershell
python -m http.server 4173
```

Then visit `http://localhost:4173`.

## Deploy

The folder can be deployed without a build step to GitHub Pages, Netlify, Cloudflare Pages, Vercel static hosting or any conventional web host. Upload the contents of this folder so `index.html` is at the site root. Point the intended VSPR domain to the selected host only after legal copy, email and checkout links are confirmed.

## Required launch confirmations

1. **Registered operator:** the reference site identifies `RINGO WEARABLES LIMITED` as the operating and contracting company. That legal entity has been retained wherever it states a contractual fact. Confirm the company name, registered number, registered office, VAT status and whether additional statutory disclosures are required before public launch.
2. **Customer-service email:** `davidr@paywithringo.com` is retained only because it is the current published operator contact. Replace it only with a confirmed VSPR mailbox that is actively monitored.
3. **Effective dates and policies:** confirm the June 2026 effective date, 30-day returns, complimentary size exchange, UK delivery times and governing-law wording with the operator or legal adviser.
4. **VSPR checkout:** the old payment links were deliberately removed because they may display the former branding or product descriptions. Add VSPR-specific Stripe Payment Links in `script.js` after checking product names, price, tax, shipping, customer emails, cancellation wording and statement descriptor.
5. **Product claims:** independently confirm IP68, material composition, card/service compatibility, territories and PCI-DSS-related wording against the final supplier and payment partner documentation.
6. **Partner links:** confirm the Manage-Mii and Curve links, affiliate parameters and regional availability remain approved for VSPR.
7. **Quote permission:** confirm the Elmer Funke Kupper quotation may be used for VSPR and is accurately attributed.

## Brand assets

- `vspr-lockup.png` uses the approved champagne-gold S/R, ivory V/P, contactless mark in the tagline and no final full stop.
- `vspr-collection.png` is the supplied four-finish render.
- The four product-card images are crops of that supplied render, so every ring shows `VSPR` on its outside face.
- `vspr-packaging.png` is a VSPR packaging visual derived from the live site's composition; obtain production artwork before manufacture.
