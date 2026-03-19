# 🇺🇸 US Elections 2028 — Static HTML Version

Pure HTML + CSS + JS. No framework, no build step, no Node.js required.

## Files

```
us-elections-2028-html/
├── index.html     ← Entire site (HTML + CSS + JS in one file)
├── robots.txt     ← SEO crawl instructions
├── sitemap.xml    ← Google sitemap with News schema
└── README.md
```

## Deploy Options

### Vercel (Recommended)
1. Push folder to GitHub
2. Import at app.netlify.com → just drag-and-drop the folder
3. Deploy → set domain to `uselection2028.netlify.app`

### Netlify
1. Drag & drop the folder onto netlify.com/drop
2. Set custom domain in Site Settings

### GitHub Pages
1. Push to repo → Settings → Pages → Deploy from `main` branch `/root`

### Any web host
Upload `index.html`, `robots.txt`, `sitemap.xml` to your public directory. Done.

## To Update Data

All placeholder data is in the `<script>` block near the bottom of `index.html`.
Look for the `/* ─── DATA ───` comment. Edit the arrays:

- `POLLS` — National poll percentages
- `SWING_STATES` — State-by-state numbers
- `POLLSTERS` — Pollster table rows
- `CANDIDATES` — Candidate bios and issues
- `KEY_DATES` — Election calendar
- `NEWS_ITEMS` — News headlines
- `TRENDING` — Keyword search volumes
- `TOPICS` — Topic card content

## SEO Included
- All meta tags, OG tags, Twitter Card
- 4× JSON-LD schemas (Event, NewsArticle, WebSite, BreadcrumbList)
- Canonical URL, robots meta, geo tags
- Sitemap + robots.txt
- Semantic HTML5 with ARIA labels
- Alt text on all images
- SEO footer paragraph with target keywords
