# preview-brasilcleaning

Preview site for **BrasilCleaning** — commercial & residential cleaning in Broward County, South Florida.
*Caring for Your Well-Being.*

## Structure
- `index.html` — single-page site (self-contained: inline CSS + JS)
- `quote.html` — multi-step "Get a Free Estimate" form (EmailJS, client-side)
- `assets/` — logo, favicons and images

## Deploy
Static site — deploy on **Vercel** by importing this repository. No build step required.

## Contact
- Rosangela Souza — (954) 274-2055

---
### Pending (`[PLACEHOLDER]` / `[CONFIGURAR]` / `[CONFIRMAR]` markers in code)
- EmailJS keys in `quote.html` (publicKey / serviceId / templateId) — form runs
  in "preview mode" until real keys are set
- Real email address (footer shows "Email — coming soon")
- Real client reviews
- `thankyou.html` (form currently shows an inline success state)
- `privacy.html` / `cookies.html` policy pages

### Done
- Real transparent logo (nav + light footer), no border/background
- Homepage "Get a Free Estimate" CTAs wired to `quote.html`
- Multi-step estimate form (`quote.html`) with validation + success state
