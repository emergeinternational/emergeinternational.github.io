# Florida Boy LLC x BU-Bass Studios (GitHub Pages)

This repository powers a static, sponsor-friendly partnership site for:
- **Florida Boy LLC** (public-facing name: **Florida Boy Music**)
- **BU-Bass Studios**

Positioning: compact, premium Ethiopia + America creative partnership presence.

## Site map
- `index.html` — homepage and top-level pitch
- `partnership/index.html` — alliance model and sponsor rationale
- `artists/index.html` — artist development approach and inquiry flow
- `visuals/index.html` — visuals/releases template grid (images + video slot)
- `studio/index.html` — studio/services overview
- `partners/index.html` — partner/sponsor contact and inquiry format

## Contact details (approved)

### Florida Boy LLC (primary international)
- Email: `partnerships@emergeglobally.com`
- WhatsApp: `+16465435666` (`https://wa.me/16465435666`)
- Telegram: `@EmergeHelpDesk` (`https://t.me/EmergeHelpDesk`)

### BU-Bass Studios Ethiopia (parallel local)
- WhatsApp: `+251942250718` (`https://wa.me/251942250718`)
- Telegram: `@BuBassStudios` (`https://t.me/BuBassStudios`)

### Exact files/sections where contact is currently placed
- Footer contact blocks on all pages:
  - `index.html`
  - `partnership/index.html`
  - `artists/index.html`
  - `visuals/index.html`
  - `studio/index.html`
  - `partners/index.html`
- Primary contact section for outreach split by entity:
  - `partners/index.html` → section **"Approved contact channels"**
- Artist inquiry split by entity:
  - `artists/index.html` → section **"Artist inquiry details"**
- Structured data contact references:
  - `index.html` → JSON-LD `Organization.contactPoint` and `Organization.email`

## Artist card replacement guide

File: `artists/index.html` (section **"Artist card templates"**)

For each card, replace in this order:
1. `h3` (stage name)
2. role + city/country line (`.meta`)
3. one-line positioning note (`.line`)
4. optional profile route hint line
5. image path (`img src`) with approved portrait asset

Shared image template currently used:
- `assets/images/artist-placeholder.svg`

## Visual/release asset replacement guide

Files:
- `visuals/index.html` (section **"Asset template grid"**)
- `index.html` homepage visuals section

Template assets currently used:
- `assets/images/visual-release-cover.svg` (Slot A)
- `assets/images/visual-ethiopia-america-still.svg` (Slot B)
- `assets/images/visual-sponsor-campaign.svg` (Slot C)
- `assets/images/video-teaser-placeholder.svg` (Slot D, video slot)

For each visual tile, replace:
1. image file path
2. title text
3. credit/link metadata text
4. destination link (when available)

## Brand asset swap guide (safe replacement)

You can replace these without changing layout structure:
- Hero art: `assets/images/hero.svg`
- Logo mark: `assets/images/logo-mark.svg`
- Social share image: `assets/images/og-image.svg`

Keep dimensions and file names (or update all references site-wide) to avoid broken previews.

## Placeholder items still remaining
- Artist slot names and bios in `index.html` and `artists/index.html`
- Artist portraits (`assets/images/artist-placeholder.svg` still in use)
- Visual template tiles in `index.html` and `visuals/index.html`
- Optional future per-artist profile pages are not yet created

## Recommended pre-launch replacement order
1. Final contact QA (send test email/WhatsApp/Telegram links)
2. Replace artist names, roles, bios, portraits
3. Replace visuals/release tiles and add live links + credits
4. Replace OG image + final hero/logo package (if updated)
5. Final pass: metadata, nav links, and mobile rendering

## Technical notes
- Static HTML/CSS only (GitHub Pages friendly)
- Keep media lightweight (SVG/WebP/compressed JPEG)
- Avoid adding build tooling unless absolutely required
