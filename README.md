# Lab Competence Portal Showcase

This repository contains a lightweight static showcase website for the Lab Competence Portal. It is designed for managers, consultants, and other non-technical stakeholders who need a clear overview of the product without running the full application stack.

## What the showcase covers

- purpose of the Lab Competence Portal
- main user groups and staff roles
- core laboratory and POCT workflows
- stakeholder-facing benefits
- current prototype status
- links to the source repository and live frontend login

## Stack

- HTML
- Bulma via CDN
- small amount of vanilla JavaScript
- custom CSS in `assets/css/site.css`

## Structure

```text
.
|-- index.html
|-- assets
|   |-- css
|   |   `-- site.css
|   `-- js
|       `-- site.js
`-- README.md
```

## Local preview

Because this is a static site, you can preview it with any simple static server. For example:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

This site is ready for GitHub Pages or any static hosting platform. No build step is required.

## Attribution

This page was designed and validated by Peter Chuk, and built with assistance from ChatGPT.

## Content sources

The showcase copy is based on:

- `README.md` from `pccork/labcompetence-portal`
- `apps/backend/APP_USER_GUIDE.md` from `pccork/labcompetence-portal`
- `PROJECT_PROPOSAL.md` from `pccork/labcompetence-portal`
- layout inspiration from `pccork/caremodelhub-showcase`
