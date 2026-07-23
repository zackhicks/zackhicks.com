# Zack Hicks Executive Website

This repository hosts the static website for zackhicks.com using GitHub Pages.

## Publish

1. Copy these files into the root of the cloned `zackhicks.com` repository.
2. Open GitHub Desktop.
3. Commit with the summary:
   `Replace site with clean production repository`
4. Push origin.
5. In GitHub repository settings, confirm Pages deploys from:
   - Branch: `main`
   - Folder: `/ (root)`
6. Keep the existing custom domain setting for `zackhicks.com`.

## Monthly perspective update

Edit `index.html` and search for:

`id="thinking"`

Update the title, date, body, and boardroom question.

Also update:
- the Boardroom Perspectives archive entry
- the Article structured-data block
- `sitemap.xml` last modified date

## Files

- `index.html` — complete self-contained website
- `404.html` — fallback page
- `.nojekyll` — tells GitHub Pages to serve files directly
- `robots.txt` — crawler instructions
- `sitemap.xml` — search-engine sitemap

The site is self-contained. It has no external CSS or local image dependencies.
