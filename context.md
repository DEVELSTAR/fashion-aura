# Fashion Aurah — Project Context

## Business Overview

A manufacturer-direct branded clothing store operating out of HSR Layout, Bengaluru.
They stock branded clothes (Tommy Hilfiger, Nike, Zara, Adidas, Dior, Gucci, H&M, Uniqlo, etc.)
for Men, Women, and Kids — sold at up to **60% off MRP**.

Currently runs with no physical shop signage — selling from home, growing via WhatsApp groups.
Goal: build online presence so people can find them on Google and walk in.

---

## Store Details

| Field       | Value |
|-------------|-------|
| **Name**    | Fashion Aurah |
| **Tagline** | An Aura of Timeless Style |
| **Address** | 218, 9th Main Rd, near Lawrence High School ICSE, Sector 6, HSR Layout, Bengaluru, Karnataka 560102 |
| **Phone**   | +91 99447 25450 |
| **WhatsApp**| https://wa.me/919944725450 |
| **Google Maps** | https://maps.google.com/?q=Fashion+Aurah+HSR+Layout+Bangalore |

**Brand description (from WhatsApp group):**
> "More than just clothes, we offer confidence in a closet. Explore our collection of must-have staples and unique finds, each piece chosen to elevate your look and empower your everyday."

---

## Website — Current State

**Stack:** Vanilla HTML + CSS + JavaScript (no frameworks, no build tools)
**Files:**
- `index.html` — full single-page website
- `style.css` — all styles
- `images/` — 10 product photos + favicon + category images
- `robots.txt`, `sitemap.xml` — SEO basics

**Sections (in order):**
1. Fixed header — logo, nav (About / Gallery / Contact), WhatsApp CTA
2. Hero — fullscreen image slider (4 images), headline + CTA buttons
3. Trust strip — 4 key selling points (Branded / 60% Off / All Categories / Manufacturer)
4. About — store story, brand chip pills, photo, "Find Our Store" CTA
5. Gallery — masonry-style 3-col image grid (9 photos)
6. Contact — address + phone + WhatsApp rows, embedded Google Maps, 3 action buttons
7. Floating WhatsApp button — always visible
8. Footer — logo, address, copyright

**Lead-gen CTAs placed at:**
- Header (WhatsApp button)
- Hero (Chat on WhatsApp + View Collection)
- Gallery (Join WhatsApp for Updates)
- Contact (Call Now / WhatsApp / Get Directions)
- Floating button (persistent)

**Design system:**
- Colors: `#c0392b` red (accent), `#111111` black, `#25d366` WhatsApp green
- Fonts: Playfair Display (headings) + Inter (body)
- Scroll-reveal animations on all sections
- Fully responsive (desktop → tablet → mobile)

---

## Future Improvements

### High Priority
- [ ] Add Google Business Profile (critical for local search visibility)
- [ ] Add WhatsApp group join link (they currently manage arrivals there)
- [ ] Real product photos sorted by category (Men / Women / Kids)
- [ ] Add opening hours to contact section

### Nice to Have
- [ ] Instagram / social media links in footer
- [ ] "New Arrivals" badge or announcement banner
- [ ] WhatsApp catalog integration
- [ ] Simple enquiry form (name + phone + message → WhatsApp redirect)
- [ ] Category filter on gallery (Men / Women / Kids tabs)
- [ ] Add `favicon.png` fallback alongside `favicon.webp`

### SEO
- [ ] Submit sitemap.xml to Google Search Console
- [ ] Add structured data (LocalBusiness schema) to `<head>`
- [ ] Get reviews on Google Maps
- [ ] Add Open Graph / Twitter card meta tags for social sharing

---

## Notes

- Images are all `.webp` format (good for performance)
- No backend needed currently — pure static site
- Deployment: currently on cPanel (see `.cpanel.yml`)
- The store sells branded surplus / manufacturer stock — this is the key differentiator (premium brands, very low price)
