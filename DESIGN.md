<!-- SEED: re-run $impeccable document once there's code to capture the actual tokens and components. -->
---
name: Northline Concrete Pros
description: Local-SEO marketing site for a Quad Cities concrete contractor — built to convert, not to look like a template.
---

# Design System: Northline Concrete Pros

## Overview

**Creative North Star: "The Steel-Blue Foreman"**

A foreman doesn't oversell. He shows up, states what the job needs, and lets the finished slab speak for itself. That's the register this system commits to: one confident steel-blue carrying real visual weight (hero bands, CTA blocks, footer — not a timid accent tucked into a link color), paired with a single robust sans-serif that reads like a work order, not a pitch deck. The seed hue (~200-205° OKLCH) reads as work-truck blue, overcast Midwest sky before a pour — deliberately industrial-trustworthy rather than tech-startup-cool.

This system explicitly rejects the interchangeable-contractor-site look named in PRODUCT.md: stock photography, cookie-cutter WordPress/lead-gen layouts, and city pages that differ only by find-and-replace. Every visual decision should read as "a specific company did this job," never "a template generated this page."

**Key Characteristics:**
- One committed brand color (steel-blue), not a diluted multi-accent palette
- Single sans-serif family carried across multiple weights — no decorative pairing
- Flat-by-default surfaces; elevation appears only as a response to interaction
- Motion is responsive (state feedback, section entrances) — never choreographed spectacle
- Real specificity over generic reassurance: names, years, license numbers, actual project photos

## Colors

**The Steel Commitment Rule.** The primary steel-blue is not a decorative accent — it carries 30-60% of any given page (hero band, trust strip, CTA blocks, footer). This is a *Committed* color strategy: one saturated color anchors brand recognition, not a restrained neutral palette with a token accent.

### Primary
- **Steel Blue** (deep, work-truck blue — hue family ~200-205° OKLCH; anchor: overcast Midwest sky, poured concrete at dawn) — [exact OKLCH value to be resolved during implementation via `$impeccable document`]. Used for hero bands, primary CTAs, header/footer, section dividers that need to declare "this is Northline."

### Secondary / Accent
- **Signal Amber** (a warm, saturated complement distinct from steel-blue in both hue and lightness — safety-equipment amber/orange family) — [exact value TBD]. Reserved for the single highest-priority action per screen: "Get a Free Quote," the phone CTA. Its rarity is what makes it work — if everything is amber, nothing is.

### Neutral
- **Background**: pure or near-pure white — the mood lives in the brand colors and typography, not in a tinted surface. Avoid the cream/sand/beige "AI default" entirely; this brand's warmth comes from steel-blue + amber + real photography, not from a warm-tinted bg.
- **Ink** (body text): near-black with a whisper of the steel hue, ≥7:1 contrast against bg — non-negotiable given the older-homeowner, outdoor-mobile-reading audience named in PRODUCT.md.
- **Muted** (secondary text, captions): ink pulled ~40% toward bg, same hue family, ≥3.5:1 contrast against bg. Never the pale "elegant" gray that fails at arm's length in sunlight.

### Named Rules
**The No-Cream Rule.** Body background stays pure white or a true off-white at near-zero chroma. Warm-tinted near-white "paper/sand/linen" backgrounds are the saturated 2026 AI tell and are explicitly banned for this project.

## Typography

**Display Font:** single robust sans-serif, humanist-industrial character (exact family to be chosen at implementation — think a grotesque with real personality, not a generic system-UI sans)
**Body Font:** the same family, lighter weight
**Character:** direct and unfussy — a work order, not a pitch deck. No decorative serif, no script, no font pairing across contrast axes; the discipline is entirely in weight variation within one family.

### Hierarchy
- **Display** (bold/black weight, clamp up to ~6rem, tight but not touching — letter-spacing ≥ -0.04em): hero headline only, one per page.
- **Headline** (semibold, large): section headers ("Our Services," "Proudly Serving the Quad Cities").
- **Title** (medium-semibold): card/service titles, city-page H1s.
- **Body** (regular, 65-75ch max line length): all prose — service descriptions, FAQ answers, testimonials.
- **Label** (medium, small, minimal tracking): form labels, nav items, badges ("Licensed & Insured").

### Named Rules
**The One-Family Rule.** Every weight on the page comes from a single sans-serif family. If a second face ever appears, it earns its place on a genuine contrast axis (e.g., serif for a printed-quote-style callout) — never a second similar sans "for variety."

## Elevation

Flat by default. Surfaces sit at rest with no shadow; elevation appears only as a direct response to interaction (button hover/focus, card hover on service grids). This matches the *Responsive* motion energy — feedback, not choreography — and keeps the page feeling built rather than decorated.

### Named Rules
**The Flat-By-Default Rule.** No ambient drop shadows on cards or sections at rest. Shadows exist only as hover/focus state, kept shallow (≤8px blur) — never paired with a heavy border (no "ghost card" 1px-border-plus-wide-shadow combo).

## Do's and Don'ts

### Do:
- **Do** commit steel-blue to real surface area (hero, footer, CTA blocks) — a token accent link color is not enough for a Committed strategy.
- **Do** keep body text at ≥7:1 contrast against white; this audience reads on phones outdoors.
- **Do** put the phone number and a CTA on every page, unmissable, per PRODUCT.md.
- **Do** write genuinely different content per city page — no find-and-replace duplication.
- **Do** use real project photos and named specifics (years in business, license numbers, project counts) instead of generic trust copy.
- **Do** build responsive, purposeful motion: section-entrance feedback and interactive-state transitions, each reduced-motion-safe.

### Don't:
- **Don't** use a cream/sand/beige tinted body background — the saturated AI default this project explicitly rejects.
- **Don't** ship stock-photo hero imagery or cookie-cutter WordPress-contractor layouts (PRODUCT.md anti-reference, verbatim).
- **Don't** use gradient text, side-stripe borders (`border-left`/`border-right` as a colored accent), or glassmorphism as decoration.
- **Don't** default to the hero-metric template (big number + small label + gradient accent) — this is a lead-gen site, not a SaaS dashboard.
- **Don't** add a tiny uppercase tracked "eyebrow" above every section, or numbered 01/02/03 markers unless a section is genuinely a sequence.
- **Don't** over-round cards or CTAs (border-radius 32px+); keep radii modest (12-16px, full-pill only for tags/buttons).
- **Don't** choreograph scroll animations for this audience — mobile-first, older homeowners, responsive feedback only.
