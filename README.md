# Aayush Portfolio

Next.js 16, React 19, TypeScript, Tailwind v4, Framer Motion, Lenis, optional Spline hero.

## Run
    npm install
    npm run dev      # http://localhost:3000

## Customize
- Edit `src/data/profile.ts` (name, bio, skills, projects, email, links).
- Spline: copy `.env.example` to `.env.local` and set `NEXT_PUBLIC_SPLINE_SCENE` to your scene URL. Without it, a lightweight CSS shape is shown.
- Colors and fonts: `src/app/globals.css` and `src/app/layout.tsx`.

## Deploy
Push to GitHub, import in Vercel, and set `NEXT_PUBLIC_SITE_URL` to your domain.
