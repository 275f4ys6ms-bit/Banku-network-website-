# Banku Network Website

A polished landing page for Banku Network, designed for deployment on Vercel.

## Requirements

- Node.js 18.20.8+, 20.3+, or 22+
- npm

## Local development

Install the exact dependencies in `package-lock.json`. This includes the Astro CLI; no global Astro installation is needed.

```bash
npm ci
npm run dev
```

Open the local URL printed by Astro.

## Production build

```bash
npm run build
npm run preview
```

The production build is written to `dist/`.

## Deploy to Vercel

Import the repository into Vercel. The build command is `npm run build`; Astro generates the static site in `dist/`.
