# WalterEscobar.org — 2026 refresh

This is a dependency-free static site intended for GitHub Pages.

## Files
- `index.html` — entire site
- `styles.css` — layout and visual design
- `script.js` — mobile menu + current footer year
- `CNAME` — custom domain
- `robots.txt`
- `sitemap.xml`

## Safest manual GitHub update

1. Open the GitHub repository that currently publishes WalterEscobar.org.
2. Before changing anything, download the current repository ZIP or create a backup branch.
3. Confirm which branch GitHub Pages deploys from:
   **Settings → Pages → Build and deployment**.
4. Confirm whether the site publishes from `/ (root)` or `/docs`.
5. If it publishes from the repository root, upload these files to the root.
6. Keep the repository's existing `CNAME` if it already contains the working domain. The included file uses `walterescobar.org`.
7. Replace the old `index.html`, `styles.css`, and `script.js` only after you have a backup.
8. Commit with a message such as:
   `Refresh WalterEscobar.org public profile`
9. Wait for the Pages deployment to complete under **Actions** or **Settings → Pages**.
10. Test:
   - `https://walterescobar.org`
   - mobile navigation
   - `Walter@WalterEscobar.org` email link
   - Housing Accountability Archive link
   - LAHSA source link

## Important
Do not delete DNS records at your registrar. A content update in GitHub normally does not require DNS changes if the custom domain is already working.

## Positioning
This version intentionally does **not** discuss active complaints, agencies, case numbers, investigations, disputes, or ongoing oversight submissions. It presents a durable personal mission around housing, dignity, accountability, and Los Angeles.
