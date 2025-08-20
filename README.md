# Peak Portfolio (Next.js + Tailwind + Sanity CMS)
Built for **Subhan Shahid** — update content anytime with a CMS (no coding).
## Setup
1) Create GitHub repo and push this folder.
2) Deploy on Vercel (import repo).
3) Create a Sanity project at https://sanity.io/manage and add Vercel env vars:
```
NEXT_PUBLIC_SANITY_PROJECT_ID=xxxx
NEXT_PUBLIC_SANITY_DATASET=production
NEXT_PUBLIC_SANITY_API_VERSION=2024-08-01
# Optional: NEXT_PUBLIC_FORMSPREE_ID=yourFormId
```
4) Open `/studio` on your site, add Site Settings / Projects / Testimonials, publish.
