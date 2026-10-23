# Automed Website

<p align="center">
  <strong>Arabic-first business automation, presented clearly.</strong><br />
  A responsive portfolio website for Automed's AI-powered automation services and selected work.
</p>

<p align="center">
  <a href="https://automed-info.vercel.app/">Live website</a>
  ·
  <a href="https://github.com/ahmed-abdlhamid/Automed-Website">Source code</a>
</p>

---

## Overview

This repository contains the public Automed website. It introduces the services, showcases example projects, explains the delivery process, and gives prospective clients ways to get in touch.

Automed builds practical automation systems for businesses across different sectors. Depending on the use case, these may help organize customer conversations, orders, bookings, follow-ups, and internal workflows.

## Website highlights

- Arabic-first content with Arabic RTL and English LTR layouts.
- Responsive layouts for mobile, tablet, and desktop.
- Light and dark themes with a saved visitor preference.
- Service pages and an interactive portfolio with project details.
- Delivery-process information, FAQ accordion, and contact options.
- Search and social-sharing metadata, favicons, and a web app manifest.
- Vercel Web Analytics and Speed Insights on the deployed site.
- Keyboard focus styles and reduced-motion support.

## Technology

The current site is a static front end; it does not require a framework or build step.

- HTML
- CSS
- Vanilla JavaScript
- IBM Plex Sans Arabic and Readex Pro, loaded from Google Fonts
- Font Awesome icons
- Vercel hosting

## Run locally

From the repository root, start a local static server:

```bash
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

Opening `index.html` directly may work for a basic preview, but an HTTP server provides a more representative local environment. Vercel Analytics and Speed Insights are available on the deployed site; requests to their Vercel endpoints may return 404 when using a basic local server.

## Project structure

```text
.
├── index.html             # Main page, styles, and client-side behavior
├── assets/                # Brand assets, images, favicons, and portfolio media
├── manifest.webmanifest   # Web app manifest
├── vercel.json            # Vercel routing configuration
└── README.md
```

## Deployment

The site is deployed on Vercel at [automed-info.vercel.app](https://automed-info.vercel.app/). The repository is configured as a static site. Deployments are handled through the repository's existing GitHub–Vercel integration and project settings.

## Contact

For service inquiries, use the contact options on the [Automed website](https://automed-info.vercel.app/).

---

<p align="center"><sub>Automed — وفر وقتك</sub></p>
