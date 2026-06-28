# Reborn Beauty Ladies Salon — Website PRD

## Problem Statement
Modern, elegant, mobile-first marketing website for Reborn Beauty Ladies Salon, a premium women-only salon in BTM Layout, Bengaluru (10+ yrs, 4.5★, 1,500+ reviews). Pure HTML/CSS/vanilla JS, frontend-only, no backend.

## Architecture
- Single static page in `/app/frontend/public/index.html` (inline CSS + minimal vanilla JS).
- React root renders nothing (`App.js` returns null); static markup is the page so it serves via the dev server on port 3000.
- Google Fonts: Playfair Display (headings) + Inter (body). Palette: deep rose (#C2185B), gold (#D4AF37), cream (#FFF9F4).

## Implemented (2026-06-28)
- Fixed header w/ scroll state, smooth-scroll nav, sticky Book CTA.
- Hero with tagline, rating pill, bridal image, trust row.
- About (Hema story + stats), Services grid (6 categories w/ images).
- Bridal highlight section (glass card, WhatsApp enquiry deep link).
- Reviews (4 five-star testimonials), Hours & Location (Google Maps embed + directions).
- CTA band, footer, floating WhatsApp button, scroll-reveal animations.
- CTAs: tel:+918041119254, https://wa.me/919008878199, maps link, IG @hemareborn.

## Backlog / Next
- P1: Add a real appointment booking form (date/time + WhatsApp prefill).
- P2: Service pricing table in INR; image gallery/before-after; testimonials carousel.
