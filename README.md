# Soilable website deployment

Static website prepared for GitHub and Cloudflare Pages.

- `index.html` is the English homepage; `/zh-hant/` is the Traditional Chinese homepage.
- English SEO URLs retain the legacy path names (e.g. `/about-us/`, `/contact-us/`). Chinese pages use `/zh-hant/` equivalents.
- The `_redirects` file permanently redirects the interim `soilable-*.html` URLs to the canonical paths.
- `sitemap.xml` and `robots.txt` support search discovery. Verify the domain in Google Search Console and submit the sitemap after deploying.
- No framework or build command is required. Set the Cloudflare Pages output directory to the repository root.
