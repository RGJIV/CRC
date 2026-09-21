# Cow Rock Construction Website

A clean, professional static website for **Cow Rock Construction**, an ultra high-end custom home builder based in Cashiers, North Carolina.

## Project Overview

This repository contains the source code for the Cow Rock Construction website. It is a lightweight, fast-loading static site built with plain HTML, CSS, and a small amount of vanilla JavaScript.

### Key Features

- **Responsive Design** — Works well across desktop and mobile devices
- **Accessible Mobile Menu** — ARIA attributes for better screen reader support
- **Dynamic Gallery** — Images are loaded via JavaScript from a clean array (easy to maintain)
- **Image Modal Viewer** — Click any gallery photo for a clean enlarged view
- **Professional Aesthetic** — Minimal, elegant design appropriate for luxury custom homes
- **Privacy-Focused** — Gallery includes messaging that most clients prefer private viewings

## Pages

| Page          | Description |
|---------------|-------------|
| `index.html`  | Homepage with brand message and clear calls to action |
| `aboutus.html`| Professional biography of Richard Jennings and the company |
| `gallery.html`| Private project gallery (25 curated images) |
| `404.html`    | Branded not-found page |

## File Structure

```
.
├── index.html
├── aboutus.html
├── gallery.html
├── 404.html
├── styles.css
├── robots.txt
├── sitemap.xml
├── llms.txt
├── CNAME
├── README.md
├── *.png (logos)
├── ReasonForItAll.jpg (background fallback)
└── CRC001.jpg – CRC116.jpg (gallery images)
```

## Recent Improvements

- Cleaned up code and removed unnecessary scripts
- Improved mobile menu accessibility (ARIA)
- Made gallery dynamic and easier to maintain
- Added proper spacing and readability improvements
- Standardized year handling in footer
- Consistent structure across all pages
- September 2026: crawl files (`robots.txt`, `sitemap.xml`, `llms.txt`), JSON-LD on the homepage, canonical + Open Graph tags, page-specific visually hidden headings, branded 404, and WebP logo/hero via `image-set` / `<picture>` with original JPG/PNG fallbacks. No phone number on the site.

## Deployment

This site is designed to be deployed via **GitHub Pages**.

To deploy:
1. Push to the `main` branch
2. Enable GitHub Pages in repository settings (Source: Deploy from a branch → `main`)

A `CNAME` file is included for custom domain configuration.

## Images

- Gallery images follow the naming convention `CRCxxx.jpg`
- To add new images: Upload the file and add the filename to the `imageFiles` array in `gallery.html`
- Master logo: `COWROCK_PRIMARY_NAVY.png`. Master hero: `ReasonForItAll.jpg`. Optimized WebP copies are embedded so supporting browsers do not download the masters.

## License

Private project for Cow Rock Construction.

---

*Built for Cow Rock Construction • Cashiers, North Carolina*
