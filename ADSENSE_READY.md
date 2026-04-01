# ADSENSE_READY.md — Dependability Holdings LLC Website

## What Was Created

A complete professional informational website for **Dependability Holdings LLC** at `dependability.us`.

### Project Location
`~/openclaw/workspace-bacottibot/Website/dependability-us/`

### Pages (6 HTML files)
| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Hero, stats, features, CTA |
| About | `about.html` | Company overview, mission, differentiators |
| Investment Philosophy | `investment-philosophy.html` | 6 core principles, FAQ, portfolio construction |
| Educational Resources | `educational-resources.html` | Investment basics, portfolio, wealth building articles |
| Contact | `contact.html` | Contact info + functional form with validation |
| Privacy Policy | `privacy.html` | GDPR-compliant privacy disclosure |
| Terms of Use | `terms.html` | Investment risk disclaimers, liability limitations |

### Assets
- `css/style.css` — Complete responsive stylesheet (dark green/navy theme, mobile-first)
- `js/main.js` — Mobile menu, form validation, scroll animations
- `assets/logo.svg` — SVG logo

### Design
- **Theme**: Dark professional (navy/dark green tones with green accent `#3ecf8e`)
- **Font**: Inter (Google Fonts)
- **Mobile**: Fully responsive, hamburger menu on mobile
- **No frameworks**: Pure HTML/CSS/JS, fast loading

### AdSense-Ready Features
- `ca-pub-XXXXXXXXX` placeholder in all pages (replace with your actual AdSense ID)
- GA_MEASUREMENT_ID placeholder for Google Analytics
- Proper `<meta name="google-adsense-account">` tags
- Ad placeholders ready for Google AdSense integration
- Schema.org JSON-LD markup on all pages (Organization, FAQPage, ContactPage, CollectionPage)
- Proper meta tags, Open Graph tags, and robots directives

### Schema.org Markup
- `index.html` — Organization schema
- `about.html` — AboutPage + Organization schema
- `investment-philosophy.html` — FAQPage schema with 2 Q&A pairs
- `educational-resources.html` — CollectionPage schema
- `contact.html` — ContactPage + Organization schema

## What's NOT Included (Privacy/Discretion)
- NO personal information of any kind
- NO mention of Bacotti Inc, Bacotti family, or any individual names
- NO identifying details about ownership
- About section is intentionally vague ("investment holding company")
- Contact uses generic `info@dependability.us`
- Location listed only as "United States"

## GitHub Deployment — ACTION REQUIRED

**IMPORTANT**: GitHub CLI (`gh`) is NOT authenticated on this machine. Mike needs to:

1. **Authenticate gh**:
   ```bash
   gh auth login
   ```

2. **Create the GitHub repo**:
   ```bash
   gh repo create dependability-us --public --source=. --push
   ```
   (Run from the `Website/dependability-us/` directory)

3. **Enable GitHub Pages**:
   - Go to: https://github.com/[username]/dependability-us → Settings → Pages
   - Set Source: Deploy from a branch → `main` → `/ (root)`
   - Save

4. **Set Custom Domain**:
   - In same GitHub Pages settings, add `dependability.us` as custom domain
   - At GoDaddy: Add DNS A record pointing to GitHub Pages IP (185.199.108.153)
   - Add CNAME record: `www` → `[username].github.io`

## Before Going Live — Replace These Placeholders

| Placeholder | Replace With |
|-------------|--------------|
| `ca-pub-XXXXXXXXX` | Your Google AdSense publisher ID |
| `GA_MEASUREMENT_ID` | Your Google Analytics measurement ID |
| `info@dependability.us` | Your actual contact email |
| `https://dependability.us/assets/og-image.png` | Upload an OG image (1200x630px) to assets/ |

## Notes
- The contact form currently shows a success message client-side only (no backend). For production, connect to a form service (Formspree, Netlify Forms, etc.) or a backend endpoint.
- All investment content includes appropriate disclaimers
- The site is fast (no frameworks, minimal JS, optimized CSS)
- Fully keyboard accessible and WCAG-aware
