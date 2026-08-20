# Twenty

**Live site: [twentysite.com](https://twentysite.com)**

Marketplace for production-ready SaaS kits. Buy source once, download the zip, follow setup docs, and ship. Auth, Stripe billing, full Next.js boilerplates, landing pages, admin dashboards, and AI product shells.

Twenty is checkout and the catalog. You keep the code, the Stripe account, and the deploy.

> Build SaaS products in days, not weeks.

## Product

- Browse kits: [Market](https://twentysite.com/market)
- [Auth kits](https://twentysite.com/auth-kits)
- [Stripe billing kits](https://twentysite.com/stripe-billing-kits)
- [Next.js SaaS boilerplates](https://twentysite.com/nextjs-saas-boilerplate)
- [AI SaaS kits](https://twentysite.com/ai-saas-kits)
- Free tools: [twentysite.com/tools](https://twentysite.com/tools)
- Guides and blog: [twentysite.com/guides](https://twentysite.com/guides) · [twentysite.com/blog](https://twentysite.com/blog)

## What you get

- Buy-once source (zip in your library after Stripe Checkout)
- Required setup instructions on every listing
- Custom cookie JWT auth on the platform (not Clerk, not Supabase Auth)
- Stack deals: pair a complementary kit at checkout when it qualifies
- Seller listings and admin review when creators are enabled

## Stack (this app)

| Piece | Choice |
|---|---|
| App | Next.js App Router |
| UI | Tailwind CSS + shadcn/ui |
| Database | PostgreSQL (Neon) via Prisma |
| Auth | bcrypt + JWT in httpOnly cookies |
| Payments | Stripe Checkout + `/api/stripe/webhook` |
| Files | S3 or Cloudflare R2 |
| Host | Vercel |

## Local development

```bash
npm install
npx prisma generate
npm run db:sync
npm run dev
