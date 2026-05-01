# Netlify-ready static site

## Deploy as ZIP
1. Download this repository as `.zip`.
2. Unzip locally and confirm files are in the root (`index.html`, `styles.css`, `netlify.toml`).
3. In Netlify, go to **Sites → Add new site → Deploy manually**.
4. Drag and drop the unzipped folder.
5. Replace `example.netlify.app` in `index.html`, `robots.txt`, and `sitemap.xml` with your final domain.

## Included optimizations
- SEO: title, meta description, canonical, Open Graph, Twitter tags, schema.org JSON-LD.
- Crawlability: `robots.txt` + `sitemap.xml`.
- Security/performance headers through `netlify.toml`.
- Lightweight CSS-only visual effects (no JS runtime dependencies).
