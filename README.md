# Girl's House — Girl Fashion Landing Page

An elegant, fully responsive storefront for a women's fashion brand, built as static HTML/CSS (no build step, no dependencies beyond Google Fonts).

## Pages
- **`index.html`** — Landing page: announcement bar, header + nav, editorial hero, "La Collection" product grid, brand-promise banner, story section, reassurance features, newsletter, footer.
- **`product.html`** — Product detail page for *Manteau long avec ceinture*: image gallery with selectable views, size selector, colour, quantity stepper, and a **cash-on-delivery order popup** where the customer enters their details (nom, téléphone, ville, adresse) and confirms. Live order total updates with size/quantity.

## Features
- Responsive (desktop → mobile) with a single-column order form on small screens.
- Minimalist fashion aesthetic: cream palette, Cormorant Garamond display, Jost UI, Pinyon Script wordmark.
- Original line-art illustrations and placeholder brand (*Girl's House*) — swap in your own name and product photos.
- French UI, tuned for the Moroccan market (livraison partout au Maroc, paiement à la livraison).

## Notes
- The order form is front-end only. To receive real orders, connect the form's submit handler to a backend (Google Sheet, WhatsApp, or an order API).
- Replace the beige illustration panels with real product photography when available.

## Deploy
Served as static files via GitHub Pages. Any static host (Netlify, Vercel, Cloudflare Pages) also works — just point it at the repo root.
