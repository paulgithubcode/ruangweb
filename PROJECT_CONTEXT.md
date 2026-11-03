# RuangWeb Project Context

## Project Overview

RuangWeb is an Indonesian website development service catalog.

The website presents web development services to potential clients in Indonesia.

## Main Objectives

- Build a professional website development service catalog.
- Present service descriptions and detailed service pages.
- Build a portfolio of demo websites over time.
- Generate potential client inquiries.
- Keep infrastructure and operating costs at Rp0 whenever possible.

## Technology Stack

- Astro 7
- Node.js 24
- npm
- TypeScript for shared service data
- Static website generation
- Git and GitHub
- Cloudflare Pages Free for deployment

Do not introduce paid services or require credit card registration.

## Development Environment

- OS: Linux Mint 22.3 Xfce
- Project directory: /mnt/DriveD/projects/ruangweb
- Local development server: http://localhost:4321
- Build output directory: dist

## Project Structure

- src/data/services.ts: shared service data
- src/layouts/BaseLayout.astro: shared page layout
- src/pages/index.astro: homepage and service catalog
- src/pages/layanan/[slug].astro: service detail pages
- public/: static assets

## Available Services

1. Company Profile
2. Personal Portfolio
3. Blog & Portal Berita
4. Product Catalog
5. Online Store
6. Business Information System
7. Marketplace
8. Custom Web Application

## Design Direction

- Modern, clean, professional and comfortable.
- White background with soft blue and purple accents.
- Rounded cards.
- Generous whitespace.
- Responsive layout.
- Mobile-friendly.
- Minimal animation.
- Good UX and SEO.

## Language Convention

- Public website content: Indonesian.
- Source code, filenames, variables, functions and technical documentation: English.
- Developer communication: Indonesian.

## Current Progress

- Astro project created successfully.
- Homepage and service catalog implemented.
- Shared service data created.
- BaseLayout implemented.
- Dynamic service detail pages implemented.
- All eight service detail routes successfully generated.
- Navigation from Company Profile catalog card to its detail page works.
- Detail page container alignment has been improved.

## Current Task

Continue improving the service detail page:

1. Review the complete detail page layout.
2. Improve the content section and two-column layout.
3. Review the contact card.
4. Review benefits, features and FAQ sections.
5. Ensure responsive behavior on mobile.
6. Keep the existing homepage design intact.

## Important Development Rules

- Inspect existing files before editing.
- Avoid unnecessarily rewriting working components.
- Reuse shared service data instead of duplicating service definitions.
- Preserve existing functionality.
- Keep changes incremental.
- Run npm run build after significant changes.
- Fix build errors before continuing.
- Do not deploy without explicit approval.

## Initial Commands

```bash
npm install
npm run dev
```

Build:

```bash
npm run build
```

## Instructions for Codex

First inspect the project structure and read this document.

Then inspect the existing implementation, identify inconsistencies and propose the next implementation steps.

Do not make large changes before explaining the plan.

Work incrementally and report:
- Files inspected
- Files changed
- Changes made
- Build and test results
- Remaining tasks
