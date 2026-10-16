# El Mirage Epoxy

Website for El Mirage Epoxy (elmirageepoxy.com), an epoxy flooring contractor in El Mirage, AZ.

Static HTML, no build step. Preview locally with `python3 -m http.server` from this folder and open http://localhost:8000 (opening the files directly won't resolve the root paths).

## Pages
- `index.html` (home)
- Nine service pages, each in its own folder so URLs have no `.html` (e.g. `garage-floor-coatings/index.html` is served at `/garage-floor-coatings/`), linked from the Services dropdown
- Links and assets use root paths (`/assets/...`), so serve the site from the domain root (custom domain on GitHub Pages, Netlify, Cloudflare Pages, etc.)

## To update later
- Phone and email are placeholders: (623) 555-0148 and info@elmirageepoxy.com
- Photos in `assets/photos` are licensed from Envato Elements (Lifetime Commercial License, account: Danny)
- The estimate form is front-end only; connect it to a form service before launch

## SEO
- Photos are keyword-named, served as WebP with JPG fallback at 800px and 1600px (`srcset`), with descriptive alt text, width/height, and lazy loading
- Each page has Open Graph image tags and JSON-LD (ImageGallery, plus LocalBusiness on home and Service on service pages)
- `sitemap.xml` (with image entries) and `robots.txt` are at the root
