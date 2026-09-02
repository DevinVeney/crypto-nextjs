# Crypto

A responsive marketing site for a cryptocurrency product, built with the Next.js App Router.

**Live:** https://crypto-nextjs-sigma.vercel.app

## Stack

Next.js · TypeScript · Tailwind CSS · Headless UI · Heroicons · React Slick

## Structure

Each page section is its own component under `app/components/` — banner, features,
pricing, FAQ, testimonials, footer — composed in `app/page.tsx`. Carousels use React
Slick; interactive disclosure and modal behaviour comes from Headless UI.

```bash
npm install && npm run dev
```

## Status

A front-end build from 2023, focused on responsive layout and section composition.
Static throughout — there is no backend, form handling or data layer.
