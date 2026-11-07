# CreatorDesk MVP (working name)

A clickable prototype of a creator platform for Indian micro-creators:

1. **Create profile:** onboarding form with live preview
2. **Portfolio page:** public `/username` page with stats, work, rate card and a "Work with me" button
3. **Rate calculator:** suggests a fair ₹ price per deliverable
4. **Deal desk:** brand inquiry → accept → contract → advance → content live → paid, with fee breakdown, invoice and contract preview
5. **Brand view:** brands search creators by niche, language and budget

## Status

Prototype only. Everything runs in the browser with sample data:
- no login or database (data is saved in the browser's localStorage)
- stats, payments, contracts and invoices are simulated
- all creators and brands are fictional

## Run it

Open `index.html` in any browser. No build step needed.

## Next steps (real version)

- Next.js + Supabase (Google login, Postgres, row-level security, storage)
- YouTube Data API for verified stats (Instagram Graph API later)
- Razorpay with split payments and webhooks for the deal desk
- Legal pages (Terms, Privacy, Refunds), lawyer-reviewed contract template
- Email/WhatsApp notifications, error tracking, analytics

## Business model being tested

- Creators: free portfolio; Pro ₹99/month (custom domain, analytics, no badge)
- Deals: 8% fee, charged only when the creator gets paid
- Brands: paid creator search later
