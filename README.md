# Florida Boy LLC x BU-Bass Studios (GitHub Pages)

This repo powers the official partnership microsite.

Public branding: **Florida Boy Music x BU-Bass Studios**

## Folder structure
- `index.html` – Home
- `partnership/index.html`
- `artists/index.html`
- `visuals/index.html`
- `studio/index.html`
- `partners/index.html`
- `assets/css/styles.css`
- `assets/images/` – logo, placeholders, hero/OG image
- `.github/workflows/pages.yml` – GitHub Actions deployment

## How to update
### Copy + headlines
Edit the relevant HTML file. Search for the section headings and update text.

### Artists
In `artists/index.html`, each artist is a card with:
- name
- category/role
- country/city
- a one-line descriptor
- image path (use SVG placeholders while building)

### Images
Replace files in `assets/images/` as you approve artwork:
- `logo-mark.svg` – logo mark (header/footer)
- `hero.svg` – hero background
- `og-image.svg` – social share preview
- `artist-placeholder.svg` / `visual-placeholder.svg`

Keep images lightweight. Prefer SVG or compressed JPG/WebP stored here.

### Contact
Partners/brands: update the `mailto:` and WhatsApp link in `partners/index.html` and the footer in `index.html`.

## Deployment
Any push to the `main` branch deploys automatically via GitHub Actions.

## Custom domain (future)
1. Buy a domain
2. In repo Settings → Pages, set the custom domain
3. Create a `CNAME` record in DNS pointing to `username.github.io`
4. Add a `CNAME` file at the repo root matching the domain
5. Wait for DNS and enable HTTPS
