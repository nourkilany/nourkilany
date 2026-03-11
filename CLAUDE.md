# Nour Kilany - Profile Website

## Tech Stack
- **Astro** (static site generator)
- **TailwindCSS v4** (via `@tailwindcss/vite` plugin)
- Inline SVGs for social icons (X, LinkedIn, GitHub)

## Commands
- `npm run dev` — start dev server at localhost:4321
- `npm run build` — build static site to `dist/`
- `npm run preview` — preview built site locally

## Serve & Expose
- Build: `npm run build`
- Serve: `npx serve dist -l 4321`
- Expose: `sudo tailscale funnel 4321`

## Project Structure
- `src/layouts/Layout.astro` — base HTML layout (dark theme, meta tags)
- `src/pages/index.astro` — profile card page
- `src/styles/global.css` — Tailwind import
- `public/profile.jpg` — profile picture

## Conventions
- Dark theme: bg `#0a0a0a`, card `zinc-900`, border `zinc-800`
- Text: `zinc-100` for headings, `zinc-400` for muted text
- All external links use `target="_blank"` and `rel="noopener noreferrer"`
