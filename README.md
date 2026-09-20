# SAP SD Portfolio — Parupalli Venu Sai Nadh

A single-page personal portfolio for an SAP SD / Order-to-Cash professional transitioning into SAP HDI & HANA Cloud Modeling. Built as one self-contained HTML file — no build tools, no dependencies to install.

**Live site:** https://venusainadh.github.io/sap-sd-portfolio/ _(enable via Settings → Pages → deploy from `main`)_

---

## About this portfolio

This isn't a generic template — every design decision maps back to the actual career story it's telling:

- **The hero pipeline animation** (Order → Cash → Cloud) mirrors the real SAP Order-to-Cash process, using the same transaction codes (VA01, VA02, VF01, VF03, VF05, ZSDREBATS) used day-to-day on the job.
- **A consistent "honesty grammar" runs through the whole site:** solid amber borders mark skills, certifications, and experience that are real and held today. Dashed teal borders mark anything still in progress or planned — a certification being prepared for, or a project not yet built. Nothing on the page overstates where the candidate actually is.
- **Color palette:** a ledger-paper green background with navy ink text, nodding to the "reconciliation and cash" theme at the center of Order-to-Cash work — paired with amber (real, today) and teal (in progress, next) as the two functional accent colors.
- **Typography:** Fraunces (serif, for headlines) + IBM Plex Sans (body) + IBM Plex Mono (transaction codes, dates, certification IDs) — chosen to feel enterprise-appropriate without defaulting to generic SaaS styling.

## Sections

| Section | What it covers |
|---|---|
| Hero | Headline, one-line pitch, and the animated Order → Cash → Cloud pipeline |
| About | Background, education, and current role at a glance |
| O2C Flow | The five-step Order-to-Cash pipeline, with the transaction code behind each step |
| Skills | Split into "Hands-on today" (SAP SD/O2C) vs. "Building toward" (SAP HDI/HANA Cloud) |
| Experience | Current role at Cognizant Technology Solutions (CTS) |
| Certifications | Held certifications vs. certifications in progress, visually distinguished |
| Roadmap Projects | Planned self-study projects, clearly labeled as not yet built |
| Education | Degree, institution, and graduation details |
| Contact | Email and LinkedIn |

## Tech stack

- Plain HTML5 + CSS3 (no framework)
- Vanilla JavaScript (a few lines, no dependencies)
- Google Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces), [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans), [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono)
- Fully responsive (mobile, tablet, desktop)
- Respects `prefers-color-scheme` (light/dark) and `prefers-reduced-motion`

## Running locally

No build step required.

```bash
git clone https://github.com/Venusainadh/sap-sd-portfolio.git
cd sap-sd-portfolio
open index.html   # or just double-click the file
```

## Deploying

Works as-is on any static host:

- **GitHub Pages:** Settings → Pages → deploy from the `main` branch
- **Netlify / Vercel:** drag-and-drop the folder, or connect the repo

## Updating content

All content lives directly in `index.html` — experience, skills, certifications, and projects are plain HTML in clearly labeled `<section>` blocks. No CMS or data file to edit separately.

## Author

**Parupalli Venu Sai Nadh**
B.Tech, Computer Science and Information Technology — Koneru Lakshmaiah Education Foundation (KL University)
SAP SD / Order-to-Cash · Cognizant Technology Solutions

- Email: parupallivenusainadh@gmail.com
- LinkedIn: [linkedin.com/in/venusainadh](https://www.linkedin.com/in/venusainadh/)

## License

Personal portfolio — feel free to fork for inspiration, but please don't reuse the content as your own.
