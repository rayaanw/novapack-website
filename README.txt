NOVAPACK FINAL WEBSITE UPLOAD PACKAGE
Prepared: 2026-06-03 | Last updated: 2026-07-12

WHAT TO UPLOAD (required)
=========================
- index.html                  (the entire website - single file)
- assets/images/products/     (11 product photos + SVG fallbacks)
- assets/images/customers/    (24 customer logos)

Everything else in the package is reference/backup material and does
NOT need to be uploaded (docs/, assets/images/*-original files).

WHAT THE SITE INCLUDES
======================
- Hero with Explore Products / Sustainability / Nova Power buttons
- Stats band: 8,000 MT production, 20,000 MT PE Recycling,
  300 kW solar (Phase II 300 kW in pipeline), GRS/RCS/Halal certified
- About (Novapack Group, 50 years experience, 6 strengths)
- 11 products with category filter and per-product quote links
  (all quote/email links go to contact@novapack.com.pk)
- 8 industries served
- 25-customer logo wall (scrolling marquee)
- Sustainability & Circular Economy with GRS/RCS certificate
- Nova Power - Battery & Energy Storage section
- Mobile hamburger menu, animated counters, scroll effects

IMAGE SYSTEM
============
Product cards look for assets/images/products/<name>.jpg first, then
fall back to a branded SVG illustration, then a placeholder - nothing
can appear broken. To replace a photo later, overwrite the .jpg and
bump the version query in index.html (search "?v=2", change to "?v=3").

Customer logos work the same way via assets/images/customers/ - a
missing logo shows the company name as styled text. Only Murree Glass
currently has no logo file.

Original full-quality product photos are archived in
docs/original-product-photos/ (do not upload - reference only).

See docs/UPLOAD_INSTRUCTIONS.md for step-by-step hosting instructions
and docs/IMAGE_CREDITS.txt for image licensing/sources.
