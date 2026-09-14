# Sundries Lite — free one-page template for homeware and gift shops

A single-file HTML template for a small shop selling online the honest way:
a product shelf, live open/closed status, and Buy buttons wired for Stripe
Payment Links. No basket, no build step, no frameworks — open `index.html`
and edit.

**Live demo:** https://sundries-lite.vercel.app

## Quick start

1. Edit the text directly in `index.html` — shop name, story, product cards, address.
2. Replace the photos in `img/` with your own (keep the filenames, or update the `src` paths).
3. Set your opening hours in the `HOURS` table near the bottom of the file
   (day 0 = Sunday; `null` = closed all day; `[10,17]` = 10am to 5pm).
4. Paste a Stripe Payment Link into each card's `data-payment-link` attribute
   to take real orders. Leave it empty and the Buy button explains itself
   with a toast instead of faking a checkout.
5. Upload anywhere — it's static files. Vercel, Netlify and GitHub Pages host it free.

## License

Free for personal and commercial use. Attribution appreciated but not
required. Don't resell or redistribute the template itself as a template.

Demo photos are Unsplash placeholders for preview only — replace them with
your own product photography before going live.

## Want more?

The full Sundries theme adds a multipage site (Shop, Our story, Visit), a
static page per product with its own gallery and story, category filters
and sorting on the shelf, a lightbox, four colour packs, a live map, and
JSON-driven content (rebrand the whole site from one data folder) — built
as an Astro 7 project.

→ https://mikesmithdesign.gumroad.com/l/sundries-astro-theme (£20)
