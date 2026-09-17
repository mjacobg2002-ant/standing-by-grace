# I'm Still Standing By Grace — Homepage Redesign Concept

A modern, editorial, **homepage-only redesign concept** for I'm Still Standing By Grace, Inc.
(Baltimore, MD) — a behavioral-health, substance-use treatment and recovery organization.

> **Presentation concept only.** This is an unaffiliated design demonstration. It does not modify
> or replace the live website at standingbygrace.org.

## What's here
- `index.html` — the complete, self-contained homepage (HTML + CSS + a little vanilla JS).
- `public/images/standing-by-grace/` — locally downloaded photography, the authentic logo/dove
  mark, and `IMAGE-MANIFEST.md` documenting every image's source, photographer, and alt text.

## Design
- **Framework:** hand-built single-file static page — no build step, deploys anywhere.
- **Palette:** deep forest green, muted sage, restrained plum/violet, warm ivory, soft stone, charcoal.
- **Type:** Fraunces (editorial serif headlines) + Inter (body).
- **Approach:** oversized editorial headlines, generous white space, alternating image/copy program
  blocks, numbered sections, thin dividers, subtle scroll reveals, refined button transitions.

## Accessibility & performance
- Responsive from 320px → 1440px+; accessible mobile menu (Esc / scrim / focus states).
- Semantic landmarks, skip link, keyboard navigable, WCAG-minded contrast.
- Respects `prefers-reduced-motion`; lazy-loaded imagery; optimized JPEGs.

## Photography
All photos are sourced from [Pexels](https://www.pexels.com), downloaded locally (not hotlinked),
and documented in `public/images/standing-by-grace/IMAGE-MANIFEST.md`. People pictured are stock
models — **not** clients, staff, or program participants — and alt text is written accordingly.

## Content notes
Copy avoids inventing staff, testimonials, success rates, awards, insurance coverage, accreditation,
or guaranteed admission. Crisis guidance (911 / 988) and a "not monitored for emergencies" notice are
included. The two distinct organizations (I'm Still Standing By Grace, Inc. and By Grace Counseling
Services) and their separate phone numbers are clearly differentiated.

## Local preview
Open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
