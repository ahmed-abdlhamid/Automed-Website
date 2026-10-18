# Automed — Smart Business Automation

**Automed designs and builds AI-powered automation systems that help businesses reduce repetitive work, organize operations, and serve customers more efficiently.**

🌐 **Live website:** https://automed-info.vercel.app/

This repository contains the source code for the Automed website. It presents the services, selected automation projects, delivery process, and contact options for businesses exploring practical AI agents and workflow automation.

## About Automed

Automed works with businesses across different sectors—not just healthcare. Depending on the business need, solutions can support restaurants, shops, clinics, and companies with customer communication, order intake, booking and follow-up, internal workflows, and document review.

The goal is to fit automation into the tools and processes a team already uses, rather than adding complexity for its own sake.

## Website Features

- **Arabic-first, bilingual experience** with Arabic RTL and English LTR layouts.
- **Light and dark themes** with saved theme preference.
- **Responsive design** for desktop, tablet, and mobile.
- **Service overview** covering customer service and order automation, booking and follow-up, internal processes, and AI-assisted document review.
- **Interactive portfolio** with project details and supporting media.
- **Delivery journey** explaining the stages from discovery through implementation and support.
- **FAQ accordion** and contact form that prepares a message for the visitor's selected contact channel.
- **SEO and sharing metadata**, favicons, and a web app manifest.
- **Vercel Web Analytics and Speed Insights** integrations for the deployed site.
- **Accessibility considerations**, including keyboard focus styles and reduced-motion support.

## Featured Work

The portfolio includes examples of automation concepts and systems such as:

- **Krokett** — customer conversations and restaurant order workflows.
- **HR Ninja** — internal HR processes.
- **Nexus Health** and **Elite Dental** — booking and follow-up scenarios.
- **PreAuth Mind** — AI-assisted document review.

These are portfolio examples of different use cases; the exact scope and integrations depend on each implementation.

## Technology

The website is intentionally lightweight and uses a static front-end:

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts: IBM Plex Sans Arabic and Readex Pro
- Font Awesome icons
- Vercel for hosting and deployment

There is no framework or build step required for the current static website.

## Run Locally

You can preview the site using any static HTTP server.

### Python

From the repository root, run:

```bash
python -m http.server 8000
```

Then open http://127.0.0.1:8000/ in your browser.

You can also open `index.html` directly, but using a local HTTP server is recommended for a more realistic preview.

**Note:** Vercel Analytics and Speed Insights endpoints are provided by the deployed Vercel environment. Their `/_vercel/...` requests may return 404 when running through a basic local static server; that alone does not indicate that the website's main page or assets have failed.

## Project Structure

```text
.
├── index.html             # Main page, styles, content, and client-side behavior
├── assets/                # Logos, favicons, images, and portfolio media
├── manifest.webmanifest   # Web app manifest
├── vercel.json            # Vercel routing configuration
└── README.md
```

The exact contents of `assets/` may evolve as portfolio media and brand assets are updated.

## Deployment

The site is configured for Vercel and is available at:

https://automed-info.vercel.app/

The current implementation is a static site. Changes to the repository's configured deployment branch can be deployed through the existing GitHub–Vercel integration, depending on the project's deployment settings.

## Contact

- **Website:** https://automed-info.vercel.app/
- **GitHub:** https://github.com/ahmed-abdlhamid

For service inquiries, use the contact options on the website.

---

*Automed — practical AI agents and automation systems for everyday business operations.*
