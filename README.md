# BENERAX — Corporate Website

Static marketing site for BENERAX LLC (AI-driven software company).
Hand-built HTML/CSS/JS — no framework. Deployed on Cloudflare Pages.

## Structure
- `index.html` — home
- `pages/` — shopify-app, core, platform, software-development, about, privacy, terms
- `assets/` — styles.css, site.js, logo.png
- `_headers` — Cloudflare Pages security + cache headers

## Deploy
Cloudflare Pages, connected to this repo. Every push to `main` auto-deploys.
Build command: none (static). Output directory: `/` (root).

## Domain
benerax.com (registrar: GoDaddy; DNS via Cloudflare).
