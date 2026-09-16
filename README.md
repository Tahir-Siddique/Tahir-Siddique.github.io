# Tahir Siddique — Python developer, London

Live site: [https://tahirsiddique.dev](https://tahirsiddique.dev/)  
GitHub Pages also redirects from [tahir-siddique.github.io](https://tahir-siddique.github.io/).

## SEO / Google Search Console

Use the **custom domain** as the property Google indexes (the `.github.io` URL 301s to it).

1. Open [Google Search Console](https://search.google.com/search-console)
2. Add property → **URL prefix** → `https://tahirsiddique.dev`
3. Verify (easiest: HTML tag in this site’s `<head>`, or DNS TXT on `tahirsiddique.dev`)
4. Sitemaps → submit `https://tahirsiddique.dev/sitemap.xml`
5. URL inspection → inspect `https://tahirsiddique.dev/` → Request indexing
6. Optional: also add the Domain property `tahirsiddique.dev` so `www` / http variants are covered

After a week or two, search **Tahir Siddique Python** and check the Images tab.

If Search Console gives you a `google-site-verification` meta tag, paste it into `index.html` `<head>` and push.

## Files

- `index.html` / `styles.css` — site
- `robots.txt` / `sitemap.xml` — crawl
- `assets/tahir-siddique-python-developer.jpg` — portrait
- `assets/tahir-siddique-python-developer-og.jpg` — 1200×630 share image
- `CNAME` — `tahirsiddique.dev`

## Local preview

```bash
python -m http.server 8000
```
