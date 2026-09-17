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

## Photography & logo
All imagery is the organization's **own** — their real Baltimore facility, community rooms,
sessions, and building, plus their logo — pulled from standingbygrace.org, downloaded locally
(not hotlinked), and documented in `public/images/standing-by-grace/IMAGE-MANIFEST.md`. The logo
is used on a transparent background (its faint speckle wash was cleaned off); no background is
added behind it. Alt text is descriptive and does not assert anyone's identity.

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
