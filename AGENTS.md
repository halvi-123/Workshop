# AI Agent Instructions

## Project overview
- This is a small Astro v5 app called **Mona Mayhem**.
- The site is built in `src/pages` with a server output and Node adapter.
- Key app files:
  - `src/pages/index.astro` — main landing page
  - `src/pages/api/contributions/[username].ts` — GitHub contributions API route
- The `workshop/` folder contains tutorial content and should generally be ignored for application development unless the task explicitly involves the workshop.

## Build / development commands
- `npm install` — install dependencies
- `npm run dev` — run Astro in development mode
- `npm run build` — build the site for production
- `npm run preview` — preview built output
- `npm run astro` — run Astro CLI directly

## Astro-specific guidance
- The app uses an Astro server build: `output: 'server'` and `@astrojs/node` with `standalone` mode.
- Keep page routes under `src/pages`; add new endpoints there for API behavior.
- Use `.astro` for page templates and TypeScript in server routes.
- Prefer minimal client-side JavaScript and keep UI logic in Astro templates unless a component library is needed.
- Static assets should go in `public/`.

## What to focus on
- `src/pages` for app routes and page behavior
- `public/` for assets
- `astro.config.mjs` for deployment/runtime configuration

## What to ignore by default
- `workshop/` content — this is tutorial material, not production app code
- localized docs (`README.es.md`, `README.pt_BR.md`) unless translation work is requested

## References
- `README.md` — project description and workshop context
- `package.json` — scripts and dependencies
- `astro.config.mjs` — Astro build/runtime config
