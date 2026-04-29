# Kiwi CRM Website

## Project Overview
Marketing website for **Kiwi CRM** — a New Zealand Zoho consulting and product-support firm serving NZ SMEs (10–50 staff). Operated by GoBizIT NZ.

## Tech Stack
- Vanilla HTML + CSS (single `index.html`, no build step)
- Inline `<style>` block (no separate CSS bundle yet — refactor candidate)
- Static images in `images/`

## Repository
- GitHub: `asets-gobizit/web-kiwicrm`
- Default branch: master
- Deployed via GitHub Pages

## Domain & DNS
- Live URL: https://www.kiwicrm.co.nz
- Apex DNS managed on Cloudflare (account: Asets@gobizit.com)
- `CNAME` file in repo root sets the GitHub Pages custom domain

## Canonical Contact
- **Email:** `info@kiwicrm.co.nz` (do NOT use `info@gobizit.co.nz` on this site — domain mismatch)
- **Phone:** Removed from site per Danny 2026-04-29. Do not reintroduce `tel:` links or a published number unless Danny explicitly asks.

## Design Context
- **Register:** brand (marketing site)
- **PRODUCT.md** at repo root captures users, brand personality, anti-references, accessibility, and 5 strategic design principles. Read it before any design change.
- **DESIGN.md** to be generated post-rebuild via `/impeccable document` once the redesigned `index.html` ships.

## Current State (2026-04-29)
A redesign is in flight under `/impeccable craft`. The legacy `index.html` has known issues (broken `Get Started Free` CTA, generic SaaS hero, placeholder imagery, trend-reflex glassmorphism, category-cliché navy+green palette). All being addressed in the rebuild — see PRODUCT.md anti-references list.

## Key Rules
- Single source of truth for contact email is `info@kiwicrm.co.nz`.
- All CTAs are `mailto:` or `tel:` links — no gated contact forms (per PRODUCT.md design principle #4).
- No people-photos. Abstract illustration / bold typography only (per Imagery decision).
- Trend reflexes (gradient text, glassmorphism, hero-metric template, 4-card emoji grid) are explicit anti-patterns. Do not reintroduce.
- Color palette must avoid the navy + bright green CRM-category cliché.
