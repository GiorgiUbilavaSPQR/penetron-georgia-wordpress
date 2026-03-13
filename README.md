# Penetron Georgia — WordPress Full-Stack Rebuild

**Client:** Penetron Georgia (penetron.ge)
**Platform:** WordPress + Kadence (Free)
**Date:** 2025
**Role:** Full-Stack Developer / SEO / System Administrator

---

## Project Background

The original website had been untouched since 2016. It had no SSL certificate (HTTP only),
no branding, catastrophic design, and a Lighthouse score of ~25 on both desktop and mobile.
The site was hosted on a local Georgian provider (Magticom) with no performance optimization.

> Note: Before screenshots were not captured at the time of the initial audit —
> this was an early-career project before systematic documentation habits were established.

---

## What I Built

Complete rebuild from scratch using Local by Flywheel for staging,
then migrated to Hostinger Business (Germany server).

- Rebuilt entire site from 0 on local environment (Local by Flywheel)
- Migrated to Hostinger Business — Germany server
- Configured LiteSpeed Cache (Guest Mode + custom rules)
- Installed and configured SSL certificate (HTTP → HTTPS)
- Full branding, design, copywriting, product photography
- Configured Google Search Console + sitemap indexing
- Created and optimized Google Business Profile (photos, info, categories)

---

## Results

| Metric | Before | After |
|---|---|---|
| Desktop Score | ~25 / 100 | 100 / 100 |
| Mobile Score | ~25 / 100 | 99 / 100 |
| SEO Score | Poor | 100 / 100 |
| Best Practices | Poor | 100 / 100 |
| SSL Certificate | ❌ None | ✅ Valid |

---

## Plugins Configured

| Plugin | Purpose |
|---|---|
| Kadence Theme (Free) | Design system, layout |
| Kadence Gutenberg Blocks (Free) | Custom block components |
| Rank Math | SEO (replaced Yoast) |
| LiteSpeed Cache | Performance + Guest Mode |
| Wordfence (Free) | Security scanning + firewall |
| Duplicator Pro | Staging → Live migration |
| PixelYourSite | Facebook Pixel + GA4 |
| Ninja Forms | Contact forms |
| Join.chat | WhatsApp floating button |
| Sassy Social Share | Social sharing |
| Read Meter | Article read time |

---

## Custom CSS

All styling below was written manually to compensate for Kadence Free limitations:

- Equal-height Info Box card grid with bottom-aligned buttons
- Elite card hover effect (translateY lift + shadow)
- Sassy Social Share title typography fix
- Button color override (brand orange #F37A20)
- Footer social links grid layout
- Mobile drawer navigation font sizing
- Testimonial image grayscale treatment

---

## Technical Stack

WordPress · Kadence · Gutenberg · LiteSpeed · Hostinger · Rank Math ·
Wordfence · Google Search Console · Google Business Profile · GA4 · Facebook Pixel

---

## Lessons Learned

- Always capture before/after screenshots from day one
- Local by Flywheel is ideal for safe WordPress staging
- LiteSpeed Cache Guest Mode dramatically improves mobile scores on shared hosting
- Kadence Free requires significant CSS overrides for advanced layout control