# PEHRAN — Authentic Kashmiri Craftsmanship

A static export of the PEHRAN storefront for handcrafted Kashmiri pherans and shawls.

## Live site

- **Live sandbox deployment:** Pehranbyperhan.com
- **Original preview source:** https://4173-i63lnxgfezklrgp9kic63-1ca3be9c.us1.manus.computer/#collections
- **GitHub repository:** https://github.com/nightframe01/uza

The live sandbox deployment serves the same committed files from this repository. It is available while the current Manus environment remains running.

## Included

- `index.html` — application shell and metadata
- `404.html` — fallback document for static hosting
- `assets/` — compiled JavaScript, CSS, and product imagery
- `favicon.webp` — site icon
- `.nojekyll` — disables Jekyll processing for compiled assets
- `export-manifest.json` — source and asset manifest
- `robots.txt` — crawler access rules and sitemap location
- `sitemap.xml` — public homepage and collection URLs

This is a static export of the currently deployed site. The compiled app includes a catalog fallback so the product collection can render without the original preview API.

## Optional GitHub Pages setup

The files are ready for GitHub Pages from the `main` branch and repository root. The current GitHub CLI credential can push code but does not have permission to activate Pages automatically. A repository administrator can enable it at **Settings → Pages → Deploy from a branch → `main` → `/ (root)`**.

## Google indexing

The site now includes a canonical URL, crawler-visible title and description, Open Graph metadata, schema.org store data, a `robots.txt`, and a sitemap. After GitHub Pages is enabled, submit `https://nightframe01.github.io/uza/sitemap.xml` in [Google Search Console](https://search.google.com/search-console). Google controls when a new site appears in search results; indexing is not immediate or guaranteed.
