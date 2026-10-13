# El Mirage Epoxy

Website for El Mirage Epoxy (elmirageepoxy.com), an epoxy flooring contractor in El Mirage, AZ.

Static HTML, no build step. Open `index.html` in a browser.

## Pages
- `index.html` (home)
- Nine service pages, one per service, named after their SEO slugs (e.g. `garage-floor-coatings-el-mirage-az.html`), linked from the Services dropdown

## To update later
- Phone and email are placeholders: (623) 555-0148 and info@elmirageepoxy.com
- Photos in `assets/photos` are licensed from Envato Elements (Lifetime Commercial License, account: Danny)
- The estimate form is front-end only; connect it to a form service before launch

## SEO
- Photos are keyword-named, served as WebP with JPG fallback at 800px and 1600px (`srcset`), with descriptive alt text, width/height, and lazy loading
- Each page has Open Graph image tags and JSON-LD (ImageGallery, plus LocalBusiness on home and Service on service pages)
- `sitemap.xml` (with image entries) and `robots.txt` are at the root
