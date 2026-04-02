# cx

An Astro landing page inspired by Stitch-generated luxury furniture ecommerce concepts and refined toward a MOHD-style commercial homepage.

## Stack

- Astro 6
- Static output
- Plain Astro components and CSS

## Local development

```bash
npm install
npm run dev
```

Open `http://localhost:4321/`.

## Build

```bash
npm run build
npm run preview
```

## Project structure

- `src/pages/index.astro` — homepage implementation
- `src/layouts/MainLayout.astro` — shared layout and global styles
- `astro.config.mjs` — Astro config

## Notes

- The page uses remote image URLs from the design export.
- `dist/`, `.astro/`, and `node_modules/` are intentionally ignored.
- If `package-lock.json` is missing in GitHub, run `npm install` locally and commit it from a machine with GitHub git credentials.
