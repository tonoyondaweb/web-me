# AGENTS.md

## Project

- Astro 6.x static site, single page (`src/pages/index.astro`)
- Node >= 22.12.0 (enforced in `package.json`)
- TypeScript strict mode via `astro/tsconfigs/strict`
- No integrations, no SSR, no frameworks — pure Astro

## Commands

| Command | Purpose |
|---|---|
| `npm run dev` | Dev server at `localhost:4321` |
| `npm run build` | Production build → `dist/` |
| `npm run preview` | Preview build locally |
| `npm run astro <cmd>` | Astro CLI (e.g. `astro add`, `astro check`) |

## Structure

- `src/pages/` — file-based routing, one page currently
- `public/` — static assets (favicons)
- `assets/design.pen` — Pencil design file for UI mockups

## Conventions

- No test runner, linter, or formatter configured — add them before writing tests/lint rules
- `.env` files are gitignored and loaded automatically by Astro
- Generated types live in `.astro/` (gitignored)
