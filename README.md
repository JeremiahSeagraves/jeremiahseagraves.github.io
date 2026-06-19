# Jeremiah Seagraves — Portfolio

Single-file, zero-build personal portfolio + interactive backend demo for a Senior Java
Backend Engineer. Everything lives inline (HTML + CSS + JS) — no frameworks, no build step.
GitHub and LinkedIn links are already filled in.

## Files
- `index.html` — **the live site** (flagship): interactive distributed-system simulator,
  AI "Ask about me" panel, ⌘K command palette, Recruiter view, architecture story, one-page
  summary, JSON-LD/SEO, accessibility.
- `resume.html` — matching, ATS-safe résumé. Open it and **Print → Save as PDF**.
- `Jeremiah-Seagraves-Resume-2026.pdf` — the résumé PDF the site's download buttons link to.
- `robots.txt`, `sitemap.xml`, `.nojekyll` — for search engines / GitHub Pages.
- Alternate designs (optional, not required to deploy): `index-dark.html`,
  `index-light.html`, `index-terminal.html`.

## Deploy free on GitHub Pages  →  https://jeremiahseagraves.github.io

1. Create a new **public** repo named exactly **`jeremiahseagraves.github.io`**.
2. Upload these to the repo root: `index.html`, `resume.html`,
   `Jeremiah-Seagraves-Resume-2026.pdf`, `robots.txt`, `sitemap.xml`, `.nojekyll`
   (the alternate `index-*.html` files are optional).
3. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`, **Save**.
4. Live in ~1 minute at **https://jeremiahseagraves.github.io**.

> Tip: you can drag-and-drop all the files into the repo via the GitHub web UI
> ("Add file → Upload files") — no Git commands needed.

### Quick local preview
Double-click `index.html`, or run:
```
python3 -m http.server 8000
```
then open http://localhost:8000

## Updating your résumé
Edit `resume.html`, open it, **Print → Save as PDF**, and save over
`Jeremiah-Seagraves-Resume-2026.pdf` (keep the same filename so the site's links keep working).

## Other free hosts (drag-and-drop, no Git)
- **Netlify Drop** — netlify.com/drop, drag the folder in.
- **Cloudflare Pages** / **Vercel** — connect the repo, deploy.

## Custom domain (optional)
Add a `CNAME` file containing your domain, then point a CNAME DNS record at
`jeremiahseagraves.github.io`.
