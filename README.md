# Morph Forge Exotics

This repository contains the recovered production site for Morph Forge Exotics, a genetics-focused ball python and western hognose breeding program in New Britain, Connecticut.

## Structure

- `index.html` — self-contained production page with inline styles and behavior
- `logo.png` — production logo asset recovered from the live deployment
- `.github/workflows/static-validation.yml` — lightweight HTML and reference validation

The site is intentionally dependency-free and deploys as a static site from the repository root. External social links remain `#` placeholders because the production deployment did not expose destination URLs.

## Local validation

Serve the repository root with any static HTTP server, then open `index.html` in a browser. The CI workflow validates markup, local asset references, internal anchors, required content, and the email link.
