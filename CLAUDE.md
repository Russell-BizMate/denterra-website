# Denterra marketing site (hiredenterra.com)

Plain HTML/CSS site hosted on GitHub Pages at https://www.hiredenterra.com (CNAME is in the repo root). No build step. Pushing to `main` republishes the live site within a couple of minutes.

## Pages
- `index.html` home
- `dental-practices.html`, `professionals.html`, `pricing.html`, `claims-cloud.html`, `stories.html`, `our-stories.html`
- `styles.css` shared styles; images live in the root and `assets/`

## Rules for changes
- Keep existing URL paths unchanged so search rankings aren't affected. Never rename or delete a published page without a redirect plan.
- Update `sitemap.xml` when pages are added or removed (create it if it doesn't exist yet).
- Forms run through GoHighLevel embeds. Don't rewrite the embed snippets.
- Domain DNS is at Namecheap. Don't touch CNAME unless the domain changes.
- Commit directly to `main` and push. After pushing, confirm https://www.hiredenterra.com loads (HTTP 200) and the change is visible.
