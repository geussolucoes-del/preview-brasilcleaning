# preview-brasilcleaning

Preview site for **BrasilCleaning** — commercial & residential cleaning in Broward County, South Florida.
*Caring for Your Well-Being.*

## Structure
- `index.html` — single-page site (self-contained: inline CSS + JS)
- `quote.html` — multi-step "Get a Free Estimate" form with validation, privacy consent and EmailJS-ready delivery
- `privacy.html` — privacy policy page
- `cookies.html` — cookie policy page with reset preference control
- `assets/` — logo, favicons and images

## Deploy
Static site — deploy on **Vercel** by importing this repository. No build step required.

## Contact
- Rosangela Souza — (954) 274-2055

### Done
- Real transparent logo (nav + light footer), no border/background
- Homepage "Get a Free Estimate" CTAs wired to `quote.html`
- Multi-step estimate form (`quote.html`) with validation + success state
- Privacy consent added before form submission
- Cookie consent banner added to the main site and quote page
- Privacy Policy and Cookie Policy pages added
- Unverified testimonial placeholders replaced with a service-standard section
- Contact phone kept minimal in footers and promoted only after form submission
- Thank-you call/text CTA pushes `click_text_or_call` to `dataLayer`
- SEO metadata, canonical URLs and social sharing previews on every page
- `WebSite` and `LocalBusiness` JSON-LD with Broward County service coverage
- Search crawler discovery through `robots.txt` and `sitemap.xml`

### Operational note
- Add the real EmailJS `publicKey`, `serviceId` and `templateId` in `quote.html` before production form emails should be sent. Until then, the form works in preview mode and shows the success state without sending an email.
- After the Google Business Profile is verified, keep its business name, phone, website and service area consistent with the site. Add only confirmed address, hours and profile links to the structured data.
- Add the site to Google Search Console and submit `https://brasilcleaning.com/sitemap.xml` after the production domain points to this deployment.
