# AGENTS.md

## Project

- Astro 6.x static site, single page (`src/pages/index.astro`)
- Node >= 22.12.0 (enforced in `package.json`)
- TypeScript strict mode via `astro/tsconfigs/strict`
- No integrations, no SSR, no frameworks — pure Astro

## Styling

- **Tailwind CSS v4** — configured via `@theme` in `src/styles/global.css`, NOT `tailwind.config.js`
- PostCSS plugin: `@tailwindcss/postcss` (see `postcss.config.mjs`)
- Custom theme tokens (colors, fonts) defined in `src/styles/global.css` — use these, don't invent new ones
- Design system spec: `DESIGN.md` (colors, typography, components, light effects, spacing scale)
- Pencil design file: `assets/design.pen`

## Commands

| Command | Purpose |
|---|---|
| `npm run dev` | Dev server at `localhost:4321` |
| `npm run build` | Production build → `dist/` |
| `npm run preview` | Preview build locally |
| `npm run astro <cmd>` | Astro CLI (e.g. `astro add`, `astro check`) |

## Structure

- `src/pages/` — file-based routing, currently one "Coming Soon" page
- `src/styles/global.css` — Tailwind v4 `@theme` + base styles
- `public/` — static assets (favicons)
- `assets/design.pen` — Pencil design file for UI mockups
- `DESIGN.md` — full design system spec (palette, typography, components)
- `.astro/` — generated types (gitignored)
- `.agent/` — agent memory/plan files (gitignored)

## Conventions

- No test runner, linter, or formatter configured — add them before writing tests/lint rules
- `.env` files are gitignored and loaded automatically by Astro
- Dark beige palette (`#141210` background, `#D4B99B` primary accent) — don't introduce cool grays or pure blacks
- Typography: Playfair Display for headlines, Inter for body — don't add more typefaces
- Refer to `DESIGN.md` for component patterns (cards with light effects, badges, buttons, tab bar)
