# The Sassy Lamb Studio — Affiliate‑Ready Site (Next.js + Tailwind)

## Local quickstart
```bash
npm i
npm run dev
# open http://localhost:3000
```

## Deploy to Vercel (easiest)
1. Create a new **Vercel** project: "Import → New Git repository".
2. Push this folder to GitHub (or upload via Vercel if offered).
3. Vercel auto-builds and gives you a live URL.

## Customize
- Edit `app/page.tsx`:
  - Change the site name/logo initials in the header.
  - Duplicate `<ArticleCard />` and `<GuideCard />` to add content.
  - Replace `href="#"` with your affiliate links (keep `rel="sponsored noopener"`).
- Disclosure and Privacy modal are already included (compliance basics).

## Self-tests
On the live site, click **“Show self tests”** (top). It verifies categories, filters, and card rendering.