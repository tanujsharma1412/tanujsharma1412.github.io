# Tanuj Sharma — Portfolio

Personal portfolio website for **Tanuj Sharma**, a Senior Software Engineer (Backend) focused on credit cards, Credit Line on UPI, and payments infrastructure.

**Live site:** [tanujsharma1412.github.io](https://tanujsharma1412.github.io/)

**LinkedIn:** [tanuj-sharma1412](https://www.linkedin.com/in/tanuj-sharma1412/)

**GitHub:** [tanujsharma1412](https://github.com/tanujsharma1412)
**Resume:** [Tanuj_Sharma_Senior_Backend_Engineer.pdf](Tanuj_Sharma_Senior_Backend_Engineer.pdf)

## Overview

This is a fast, responsive, single-page static portfolio designed to give recruiters, hiring managers, and engineering leaders a concise view of Tanuj’s backend and fintech expertise.

It highlights:

- 5+ years of backend engineering experience
- 1M+ transactions/day at 99.99% availability, INR 1,344 Cr+ lifetime volume
- Joined Vegapay as the 11th employee; company now 135+
- Experience in credit infrastructure, card issuance, payment processing, banking integrations, and distributed systems
- Professional experience at Vegapay, BharatPe, and Grab
- Selected projects in DeepFake media detection and backend API development

## Technology

The site intentionally has no framework, build system, or custom JavaScript. It is fully compatible with GitHub Pages.

- HTML5
- CSS3
- Google Fonts
- Static assets stored in `images/`

## Project structure

```text
.
├── index.html       # Page content, SEO metadata, and external links
├── main.css         # Responsive layout, typography, and visual design
├── images/          # Profile photo and legacy project assets
└── README.md
```

## Local preview

Because this is a static website, it can be opened directly in a browser:

```bash
open index.html
```

Or serve it locally for a browser-like deployment environment:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deployment

This repository is configured for GitHub Pages. Push changes to the publishing branch configured in the repository’s **Settings → Pages** section; GitHub Pages will serve `index.html` as the site entry point.

## Updating content

- Update professional details, role descriptions, projects, and contact links in `index.html`.
- Update typography, colors, responsive behavior, and layout in `main.css`.
- Add or replace image files in `images/`, then update their paths in `index.html`.
- Keep the resume link in the `resume-note` section of `index.html` current.

## Contact

For professional opportunities or engineering discussions, contact Tanuj at [tanujsharma1412@gmail.com](mailto:tanujsharma1412@gmail.com) or via [LinkedIn](https://www.linkedin.com/in/tanuj-sharma1412/).
