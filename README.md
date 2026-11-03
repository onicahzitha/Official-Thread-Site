# THREAD Clothing Store

A fictional streetwear store website (Part 3: functionality and SEO). Author: **onicahzitha**.

**Live site:** https://onicahzitha.github.io/thread-clothing-store/ (GitHub Pages; update if your repository name differs)
**Repository:** https://github.com/onicahzitha/thread-clothing-store

## How to view the site
1. Online: open the live link above.
2. Locally: download or clone the repository and open `index.html` in a browser (no build step or server needed).

## Project structure
`index.html, shop.html, gallery.html, about.html, enquiry.html, contact.html, cart.html` | `css/style.css` | `js/main.js, js/products.js` | `images/` | `robots.txt` | `sitemap.xml`

## Implemented features
- Seven linked pages with a shared header, footer and mobile menu; visible keyboard-focus styles and a skip link
- External stylesheet (`css/style.css`) linked from every page; images stored in `images/`
- Working cart (add, change quantity, remove, clear, total, checkout confirmation) saved in `localStorage`
- Products loaded dynamically from `js/products.js`, with search, gender/category filters and sorting
- Accordion (home), tabs (about), modal (checkout), gallery with lightbox, CSS/JS animations
- Interactive Leaflet map on the contact page
- Enquiry form (validated, returns an instant quote and availability) and contact form (validated, compiles an email to info@threadstore.com; optional AJAX endpoint in `js/main.js`)
- SEO: unique titles and meta descriptions, keywords, heading structure, alt text, canonical links, Open Graph, JSON-LD, `robots.txt`, `sitemap.xml`
- Security: Content-Security-Policy meta tag, referrer policy, no `innerHTML` for user input, cart prices always read from `products.js`

## Planned / not implemented
- Real payment processing and a server-side order database (checkout is a demo)
- Off-page SEO (backlinks, social media promotion) and a real Formspree endpoint for AJAX contact sending
- Server-level security headers (not possible on GitHub Pages)

## Feedback received (Part 2) and response
| Feedback | Change made |
|---|---|
| Separate pages | Split into 7 HTML pages joined by navigation |
| External stylesheet | Moved all CSS to `css/style.css`, linked from each page |
| Images folder | Images moved to `images/`; file names unchanged, paths updated |
| Cart did not work | Wrote the cart, clear and checkout logic in `js/main.js` |
| Small-screen navigation | Compact toggle menu plus focus styles |
| Page structure | Closed the hero `div`; styled About and Contact; consistent names, alt text and prices |
| README accuracy | Separated implemented and planned features, added viewing steps |
| Git evidence / references | Commit history below; references in one format |

## Changelog
- **Part 3 / Feedback:** Created `css/style.css`; removed the `<style>` block.
- Created `index.html`, `shop.html`, `gallery.html`, `about.html`, `enquiry.html`, `contact.html`, `cart.html`; fixed the unclosed hero `div` and replaced the `|` separators in the nav with a styled nav.
- Price mismatches fixed: the displayed price is now the single price (THREAD shirts R450, THREAD jackets R500, THREAD Women'shirts R250). Categories corrected (Cargo Pants = Pants; jackets/shirts were stored as shoes/dresses).
- Merged "Our Clothing Collection" and "More Products" into one shop grid, driven by `js/products.js`.
- Added the missing alt text for `men's jacket 3.jpeg`; names, prices and Add to Cart labels now come from the same data.
- Added cart, search/filter/sort, accordion, tabs, modal, lightbox gallery, Leaflet map, animations.
- Added enquiry and contact forms with JavaScript validation and error messages.
- Added SEO tags, `robots.txt`, `sitemap.xml`, CSP and security notes.

## Suggested commit messages
`Move CSS to css/style.css` | `Split site into separate pages` | `Move images to images/ folder` | `Add working cart with localStorage` | `Add search, filter and sort` | `Add gallery lightbox and Leaflet map` | `Add enquiry and contact forms with validation` | `Add SEO tags, robots.txt and sitemap.xml` | `Update README and changelog`

## References
- Leaflet (2023) *Leaflet: an open-source JavaScript library for interactive maps*, version 1.9.4. Available at: https://leafletjs.com (Accessed: 3 November 2026).
- Mozilla (2026) *MDN Web Docs: Content Security Policy (CSP)*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP (Accessed: 3 November 2026).
- Mozilla (2026) *MDN Web Docs: Window.localStorage*. Available at: https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage (Accessed: 3 November 2026).
- Google (2026) *Google Search Central: SEO Starter Guide*. Available at: https://developers.google.com/search/docs/fundamentals/seo-starter-guide (Accessed: 3 November 2026).
- GitHub (2026) *GitHub Pages documentation*. Available at: https://docs.github.com/en/pages (Accessed: 3 November 2026).
- OpenStreetMap Foundation (2026) *OpenStreetMap*. Available at: https://www.openstreetmap.org (Accessed: 3 November 2026).
- W3C (2023) *Web Content Accessibility Guidelines (WCAG) 2.2*. Available at: https://www.w3.org/TR/WCAG22/ (Accessed: 3 November 2026).# Official-Thread-Site
