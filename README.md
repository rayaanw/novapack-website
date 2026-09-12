# Novapack Website

A single-file marketing website built for Novapack Group, a plastics
manufacturing / PE-recycling company — hero section, product catalog with
category filtering, a sustainability/certification section, a scrolling
customer-logo wall, animated stat counters, and a mobile-responsive nav, all
in one deployable `index.html` with no build step or framework.

> **Note:** this public copy has the client's real logos, product photos,
> and certificate image stripped out and replaced with neutral placeholders
> — the code/markup/styling is unchanged, but the real brand assets used in
> production aren't included here.

## What it includes

- Hero with primary CTAs (Explore Products / Sustainability / Nova Power)
- Animated stats band (production volume, recycling volume, solar capacity)
- About section
- Product catalog with category filtering and per-product quote links
- Industries-served section
- Scrolling customer-logo marquee
- Sustainability & Circular Economy section
- "Nova Power" battery/energy-storage section
- Mobile hamburger menu, scroll-triggered reveal animations

## Image system

Product and customer-logo images are looked up by filename
(`assets/images/products/<name>.jpg`, `assets/images/customers/<name>.png`);
if a specific file is missing, the page falls back to a branded SVG
illustration, then a plain placeholder — so a missing asset never renders as
a broken image. A handful of brand images (logo, hero/about backgrounds,
certificate) are inlined directly in the HTML as base64 data URIs rather
than separate files, for simpler single-file deployment.

## Stack

Plain HTML/CSS/JS — no framework, no build step, no dependencies. Deployed
as a single uploaded file plus an `assets/images/` folder.
