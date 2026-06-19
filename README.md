# Jeremiah Seagraves — Portfolio

Live at **https://jeremiahseagraves.github.io**

Single-file, zero-build personal portfolio + interactive backend demo for a Senior Java
Backend Engineer. Everything lives inline (HTML + CSS + JS) — no frameworks, no build step.
GitHub and LinkedIn links are already filled in.

## Files

**Required for the site:**
- `index.html` — **the live site** (flagship): interactive distributed-system simulator,
  AI "Ask about me" panel, ⌘K command palette, Recruiter view, architecture story, one-page
  summary, JSON-LD/SEO, accessibility.
- `resume.html` — matching, ATS-safe résumé. Open it and **Print → Save as PDF**.
- `Jeremiah-Seagraves-Resume-2026.pdf` — the résumé PDF the site's download buttons link to.
- `og-image.png` — social-share preview card (LinkedIn, Slack, iMessage, X, etc.).
- `favicon.ico`, `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png` — browser-tab
  and home-screen icons. (`favicon-48/192/512.png` are optional extra sizes.)
- `robots.txt`, `sitemap.xml`, `.nojekyll` — for search engines / GitHub Pages.

**Optional alternate designs** (not needed to deploy):
- `index-dark.html`, `index-light.html`, `index-terminal.html`

## Deploy free on GitHub Pages  →  https://jeremiahseagraves.github.io

1. Create a new **public** repo named exactly **`jeremiahseagraves.github.io`**.
2. Upload the required files above to the repo root (the alternate `index-*.html` files are optional).
3. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`, **Save**.
4. Live in ~1 minute at **https://jeremiahseagraves.github.io**.

> Tip: drag-and-drop all the files into the repo via the GitHub web UI
> ("Add file → Upload files") — no Git commands needed.

## Updating the site

Edit the file in this folder, then on the repo do **Add file → Upload files**, drag the changed
file in, and **Commit**. GitHub Pages redeploys automatically in ~1 minute. Hard-refresh
(⌘+Shift+R) to bypass the browser cache.

- **Résumé:** edit `resume.html`, **Print → Save as PDF**, and save over
  `Jeremiah-Seagraves-Resume-2026.pdf` (keep the same filename so the links keep working).
- **Social preview / favicon:** replace `og-image.png` or the `favicon*` files (same names).
  After changing the social card, re-scrape it at the
  **LinkedIn Post Inspector** (https://www.linkedin.com/post-inspector/) so LinkedIn drops its cache.

## Quick local preview
Double-click `index.html`, or run:
```
python3 -m http.server 8000
```
then open http://localhost:8000

## Other free hosts (drag-and-drop, no Git)
- **Netlify Drop** — netlify.com/drop, drag the folder in.
- **Cloudflare Pages** / **Vercel** — connect the repo, deploy.

## Custom domain (optional)
Add a `CNAME` file containing your domain, then point a CNAME DNS record at
`jeremiahseagraves.github.io`.
