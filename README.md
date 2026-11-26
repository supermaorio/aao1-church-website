# AAO1 Church Website

A new, independent website project for AAO1, built separately from the current WordPress website.

> **Safety boundary:** This repository is for development only. It does not connect to or modify the live AAO1.org WordPress installation. Do not change the live domain's DNS or WordPress hosting during development.

## Planned stack

- [Astro](https://astro.build/) for the website framework
- [Pages CMS](https://pagescms.org/) for Git-backed content editing
- GitHub Actions for build and deployment automation
- GitHub Pages for a preview deployment, once explicitly configured

## Project status

**Scaffolding stage.** The repository is intentionally kept separate from the production website. Hosting and custom-domain deployment are not enabled by this initial commit.

## Planned content

- Home
- About AAO1
- Ministries
- Sermons and resources
- Events and announcements
- Connect and contact

## Local development

The Astro application will be added in the next implementation step. Once the project files are in place:

```bash
npm install
npm run dev
```

## Content and privacy

- Only publish content and media that AAO1 has approved for public use.
- Do not commit confidential prayer requests, personal data, credentials, API keys, or private pastoral communications.
- Keep form submissions in a secure service with access controls, not in public Git history.
- Preserve existing WordPress URLs and content until a migration is reviewed and approved.
