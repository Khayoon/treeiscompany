# TreeIsCompany

A lightweight, mobile-friendly tree care and reclaimed wood marketplace preview. Plain HTML, CSS and JavaScript; no build dependencies.

## Run

Serve this folder with `python -m http.server 4173` and open http://localhost:4173. HTTPS or localhost is required for PWA installation and service workers.

## Included

Responsive woodshop, category filters, bag with quantities, local sample orders, downloadable tree project briefs, local merchant listings and data export. Installable web manifest and offline shell after the first online visit. All prices and products are samples in CAD. Original CSS illustrations require no external image service. Google Fonts is optional; system font fallbacks work offline.

## Scope

This is an early interactive preview, not an operating marketplace. Data is stored only in localStorage in the current browser. There is no authentication, shared database, real inventory, payment collection, shipping integration, email/SMS delivery, bidding or live support. Project briefs are downloaded rather than sent. No business certification, insurance or service availability is asserted. Do not put sensitive data into this preview.

The supplied 2017 project sheet describes a broader multi-merchant marketplace. This first version focuses on the user's later tree care / Memory Tree / reclaimed wood direction and request for a quick, light PWA instead of native Android/iOS apps. Business/legal tasks in the sheet were treated as planning material, not actions to execute.

## Next production step

Connect a backend with authenticated customer and merchant roles, server-enforced access controls and shared inventory. Add an approved merchant payment account, checkout webhooks, shipping policies and a real contact endpoint before accepting customers or payments. Do not store passwords or payment credentials in this static app.

## Deployment

GitHub Pages serves the repository root on the main branch. All asset paths are relative for project-page compatibility. Bump the service-worker cache version when changing the offline asset set.
