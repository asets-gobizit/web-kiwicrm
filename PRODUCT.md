# Product

## Register

brand

## Users

**Primary:** New Zealand SME owners (10–50 staff). Hands-on owner-operators across Auckland, Wellington, and the regions — typically the founder, MD, or operations lead who personally signs purchase orders. They Google "Zoho NZ" or "CRM consultant New Zealand", click a result, and land on KiwiCRM. They are the decision-maker. They don't have an internal IT team to evaluate vendors for them.

**Context when reading the site:** Frustrated with their current state — spreadsheet sprawl, half-implemented HubSpot, an offshore Zoho consultant who doesn't return calls in NZ business hours, or a free Zoho trial they couldn't get past day three. They're skeptical of CRM consultants in general (most have been burned). They want proof this firm is local, real, and competent — fast.

**Job to be done:** Decide within 60 seconds whether KiwiCRM is the kind of NZ Zoho partner worth emailing or calling. If yes, get the contact details with zero friction.

## Product Purpose

KiwiCRM is a Zoho product support and consulting company serving New Zealand SMEs. The business sells Zoho CRM (and the wider Zoho stack) implementation, consulting, training, and ongoing support — positioned as the local NZ-time-zone alternative to global Zoho partners and offshore implementers.

**Site purpose:** Convert qualified inbound traffic into direct contact (email or phone) with the consulting team. The site is a credibility instrument, not a self-service product surface. Success = the visitor emails or calls within their first session.

**Why it exists:** NZ SMEs evaluating Zoho consistently bounce between (a) overseas implementers with cost-but-no-context advantages and (b) local accountants pretending to do CRM. KiwiCRM exists to be the obvious third choice: NZ-based, Zoho-deep, available in NZ business hours.

## Brand Personality

**Three words:** Modern, energetic, upbeat.

**Voice:** Conversational and confident. Plain English over jargon. NZ vernacular is allowed when it lands ("we're not your offshore call centre", "Zoho done right, in NZ time"). No corporate weasel words ("solutions", "leverage", "synergies"). Authority comes from specificity (named integrations, real timelines, real prices) — not from buzzwords.

**Emotional goal:** The reader should feel relief. *"Finally — someone in NZ who actually does this and isn't going to ghost me at 6pm."*

**Reference (feel only, do NOT clone):** [a1crm.co.nz](https://a1crm.co.nz/) — the closest NZ Zoho-partner reference. We borrow their **local-trust signaling** and **customer-first sequencing** (testimonials and named clients before feature lists, transparent price ranges in FAQ). We do NOT borrow their visual restraint — KiwiCRM lands in a more modern, energetic visual register.

## Anti-references

What this site must explicitly NOT look or feel like:

1. **Generic SaaS hero + 4-card benefit grid.** Big gradient headline, four cards with emoji icons and "Easy / Fast / Secure / Reliable" labels, faux-3D dashboard mockup. The 2024 AI-template look. (The current KiwiCRM site has shades of this — that is what we are leaving behind.)
2. **Heavy corporate / Salesforce energy.** Stock photos of teams in suits, multi-tier pricing tables, 8-item navigation, foreign-feeling formality.
3. **Cute illustration-driven SaaS.** Hand-drawn characters, isometric people, pastel gradients (Mailchimp/Notion marketing style). Wrong tone for kiwi SME owners.
4. **Crypto / AI-startup neon.** Black backgrounds, glitchy fonts, gradient text, neon accents. Wrong audience entirely.
5. ~~The category cliché palette.~~ **Overruled by Danny 2026-04-29.** The kiwi-green + navy palette stays — Danny judged it lands better for the NZ CRM market than the more distinctive coral alternative. The "AI-cliché" callout was a generic design heuristic; Danny knows his market. Green is now the load-bearing brand color (`#2eaa4a` ≈ `oklch(64% 0.18 144)`), paired with `#1a1a2e` deep navy ink. Avoid only the *generic* execution of green+navy (gradient overlays, glassmorphism, hero-metric template) — those bans still hold.

## Design Principles

1. **Local-first credibility.** Every section should make it impossible to mistake KiwiCRM for an overseas firm. Named NZ cities, NZ-formatted phone numbers, NZ-side integrations (Xero, MYOB) called out by name, time-zone language ("we answer in NZ business hours"). Specificity is the trust mechanism.

2. **Customer-first sequencing.** Testimonials, named clients, and real outcomes appear *before* feature lists or service taxonomies. The visitor sees who has been helped before they read what we sell. (Borrowed from a1crm — strongest move on their site.)

3. **Energy without slop.** Modern and upbeat is delivered through typography weight, color confidence, and purposeful motion — NOT through trendy gradients, glassmorphism, gradient text, or hero-metric templates. If a design choice would pass the "AI made that" test, it stays out.

4. **Frictionless contact.** The primary CTA mechanism is `mailto:` — kiwi owner-operators will just email. No gating forms, no calendar dance, no qualification questionnaires. Email and phone visible above the fold. Every CTA in the site reduces to one click.

5. **Show, don't list.** No stock-photo people, no emoji feature icons, no identical card grids. Abstract illustrations, bold typography, and confident whitespace do the visual work. Each section earns its place — restated headings and intros that repeat the title get cut.

## Accessibility & Inclusion

**Target:** WCAG 2.1 AA across the site.

**Specific commitments:**
- Color contrast ≥4.5:1 for body text, ≥3:1 for large text and non-text UI.
- Full keyboard navigability (visible focus rings, logical tab order, no keyboard traps).
- Semantic HTML (proper landmark roles, heading hierarchy, descriptive `alt` on every image).
- `prefers-reduced-motion` honored — animations gracefully degrade.
- Forms (none planned beyond `mailto:` for now) would have proper labels and error messages.
- Phone numbers as `tel:` links so mobile users get one-tap calling.
- Email addresses as `mailto:` links with the canonical address `info@kiwicrm.co.nz` (single source of truth — the previous `info@gobizit.co.nz` mismatch is being corrected).
