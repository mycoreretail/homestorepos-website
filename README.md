# homestorepos-website

HomeStore POS marketing site.

Static site for homestorepos.com. No build step: plain HTML plus an `images/` folder.

## Pages
- `index.html` — home
- `newsroom.html` — announcements
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service

## Images
- `images/logo-light.png`, `images/logo-dark.png`, `images/favicon.png` — HomeStore POS brand
- `images/dealer-*.png` — dealer logos shown in the scrolling strip on the home page

## Publishing with GitHub Pages
1. Push this folder to a repository.
2. Settings -> Pages -> Source: Deploy from a branch -> `main` / root.
3. Settings -> Pages -> Custom domain: homestorepos.com, tick Enforce HTTPS.
4. In GoDaddy DNS, add GitHub's A records for the apex domain and a CNAME for `www`.

`CNAME` in this folder already holds the custom domain.

## Contact details used on the site
info@HomeStorePOS.com · 404-587-9031

## Brand
Charcoal #222E38 · Teal #37A598 · Soft mint #A7CECA · Light mint #D9E8E7 · Gray #525B66
Headings: Plus Jakarta Sans. Body: Source Sans 3. Both loaded from Google Fonts.
