# AAO1 Church Website

An independent redesign and rebuild of the AAO1 church website. This project is being developed separately from the existing WordPress installation.

> **Production safety:** This repository does not connect to or modify the live AAO1.org website. Do not change AAO1.org DNS, hosting, WordPress files, or its database as part of this development project.

## Technology

- **Astro** — fast, static-first website framework
- **Pages CMS** — Git-backed editing dashboard for site content
- **GitHub Actions** — automated build validation
- **GitHub Pages** — planned preview hosting, to be enabled after build validation

## Current project structure

- Home
- About AAO1
- Ministries
- Sermons
- Events and announcements
- Connect and visit information

## Content editing

The Pages CMS configuration is in `.pages.yml`. It provides editing sections for site content, sermons, events, and announcements.

Only entries with `published: true` appear in the public website build. Example entries are deliberately unpublished.

Before publishing:
1. Replace draft and placeholder copy with church-approved information.
2. Confirm ministry names, mission, vision, service times, address, and contact details.
3. Upload only media AAO1 has permission to publish.
4. Review all content before switching its publish toggle on.

## Local development

Requires Node.js compatible with the installed Astro release.

```bash
npm install
npm run dev
```

Create a production build:

```bash
npm run build
npm run preview
```

## Preview deployment

The Astro configuration currently targets this repository preview path:

`https://supermaorio.github.io/aao1-church-website/`

GitHub Pages deployment is intentionally not enabled yet. A build-validation workflow runs separately; enabling publication will be a deliberate next step after reviewing the build.

## Privacy and security

- Never commit passwords, API keys, access tokens, private pastoral messages, or confidential prayer requests.
- Do not collect sensitive prayer requests in static files or public GitHub issues.
- Use an approved secure form provider for submissions that require restricted access.
- Keep the WordPress website and its backups intact until a separately approved migration and launch.
- Keep the GitHub repository access protected with two-factor authentication.
