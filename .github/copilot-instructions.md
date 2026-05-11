# GitHub Copilot Instructions

## Project overview
- This repository is a small Astro v5 app called **Mona Mayhem**.
- It uses Astro server output with `@astrojs/node` in standalone mode.
- Main app files:
  - `src/pages/index.astro` — landing page
  - `src/pages/api/contributions/[username].ts` — API endpoint for GitHub contribution data
- The `workshop/` folder contains tutorial content and should be ignored unless the task is specifically about the workshop.

## Build and run
- `npm install`
- `npm run dev`
- `npm run build`
- `npm run preview`
- `npm run astro`

## Astro guidance
- Keep routes and pages in `src/pages`.
- Use `.astro` pages and TypeScript for server route files.
- Static assets belong in `public/`.
- Prefer simple server-rendered UI; minimize client-side JS unless needed.

## What to ignore by default
- `workshop/` documentation and tutorial files
- localized README files (`README.es.md`, `README.pt_BR.md`)

## Key config
- `astro.config.mjs` — runtime/output configuration
- `package.json` — scripts, dependencies, Astro version
