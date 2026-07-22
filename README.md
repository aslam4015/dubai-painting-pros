# Dubai Painting Pros

Next.js 14 App Router + TypeScript website for Dubai Painting Pros. Data is in `data/settings.json`, `data/services.json`, and `data/areas.json`.

## Run locally
`npm install` then `npm run dev` and open http://localhost:3000.

## Build/deploy
Run `npm run build`. Import the repository into Vercel; framework preset is Next.js and no required environment variables are currently needed. Replace temporary contact data before launch. Add a custom domain in Vercel Domains, then update DNS at Cloudflare using the records shown by Vercel.

## Generated routes
All 45 services and 30 areas are statically parameterized, producing 1,350 area/service landing routes plus service and area pages. Content is generated from JSON and route parameters; customize per-record descriptions and SEO fields before production.
