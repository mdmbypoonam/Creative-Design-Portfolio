# Poonam Kashide — Creative Design Portfolio

A clean, high-converting static portfolio showcasing social ad campaigns, square feed posts, Instagram carousels, and modern landing page / website designs for real estate and corporate clients.

Live demo: https://designwithpoonam.vercel.app

## Built with
- Plain HTML (single page)
- Tailwind CSS (via CDN)
- Google Fonts (Plus Jakarta Sans)
- Static image assets (img/)

## Features
- Responsive single-page portfolio layout
- Sections for Social Ads, Feed Posts, Carousels, and Web Design
- Fast setup with no build step — open index.html or serve statically
- Web manifest and favicons included for PWA-like install support

## Files & structure
Top-level files
- index.html — main portfolio page (uses Tailwind CDN and Google Fonts)
- site.webmanifest — app manifest (icons: web-app-manifest-192x192.png, web-app-manifest-512x512.png)
- favicon.svg, favicon-96x96.png, favicon.ico, apple-touch-icon.png — site icons
- img/ — high-resolution portfolio images used across the site

Representative structure:
img/
  1.png ... 18.png   Portfolio images (high-resolution PNGs)

## Run locally
Quickest options:

- Open in browser
  - Double-click index.html or open it in your browser.

- Using Python built-in server
  - Python 3:
    python -m http.server 8000
  - Then open http://localhost:8000

- Using npx serve (Node.js)
  npx serve .

- VS Code
  - Use the Live Server extension and click "Go Live".

Notes:
- Images are high-resolution PNGs — consider optimizing (compressing or using JPEG/WebP) before deploying for faster load times.

## Deployment
This is a static site and can be deployed to any static host:
- Vercel, Netlify, GitHub Pages, or an S3 + CloudFront setup.
The repo already links to a live site at: https://adswithpoonam.vercel.app

## Contributing
This repository contains a static portfolio. For changes:
1. Fork or branch.
2. Edit index.html or replace images in img/.
3. Submit a pull request describing changes.

If you want to update styles, consider extracting Tailwind config and adding a build step (Tailwind CLI/postCSS) to enable custom utilities and smaller CSS bundles.

## Notes & next steps I recommend
- Add a LICENSE file (e.g., MIT) if you want to clarify reuse permissions.
- Optimize images (lossy compression or WebP) to reduce page load.
- Consider adding small accessibility checks (alt text is present for images; confirm for all).
- If you want to support smaller bundles and production Tailwind, I can add a simple build setup (npm, Tailwind CLI).

## Contact
Poonam Kashide — poonamkashide7@gmail.com
Website / live demo: https://designwithpoonam.vercel.app
