# Element 44 Consulting — Website

Static website for Element 44 Consulting. Hosted on Vercel.

## Project Structure

```
element44-site/
├── index.html        ← Main website (single page)
├── 404.html          ← Custom 404 error page
├── vercel.json       ← Vercel deployment config
├── package.json      ← Project manifest
├── robots.txt        ← Search engine directives
├── sitemap.xml       ← SEO sitemap
└── README.md         ← This file
```

## Deployment

This site is deployed on Vercel as a static project. See the deployment guide below.

## Custom Domain

After deploying, connect `element44.ca` via Vercel dashboard → Settings → Domains.

DNS records to add at your domain registrar:
- **A Record**: `@` → `76.76.21.21`
- **CNAME**: `www` → `cname.vercel-dns.com`
