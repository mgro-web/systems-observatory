
Systems Observatory — Research Commons (Static Site)
===================================================

How to use (GitHub → Netlify):
1) Create a GitHub repo (public), e.g., mgro-web/systems-observatory.
2) Upload all files from this folder to the repo (keep the structure).
3) In Netlify: Add new site → Import from Git → pick this repo.
   Build command: (leave blank)  |  Publish directory: /
4) In Netlify Domain management: add systemsobservatory.org and www.systemsobservatory.org, choose a primary.
5) If using Netlify DNS: ensure A @ → 75.2.60.5 and 99.83.190.102, CNAME www → <yoursite>.netlify.app
6) Enable HTTPS (Let's Encrypt) in Domain → HTTPS.

Edit content:
- index.html (homepage + NPSA block)
- repository.html (cards + search)
- about.html (two short paragraphs)
- style.css (colors/typography)

Email shown for NPSA: mgro@systemsobservatory.org

Generated: 2025-08-15T09:51:07.691367
