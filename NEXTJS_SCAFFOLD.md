# Next.js Production Scaffold — Samara Gym Luxury

## Project Structure
```
samara-gym-next/
├── app/
│   ├── layout.tsx          # Global layout, fonts, metadata
│   ├── page.tsx            # Homepage
│   ├── about/
│   │   └── page.tsx
│   ├── programs/
│   │   ├── page.tsx        # Programs listing
│   │   ├── [slug]/
│   │   │   └── page.tsx    # Individual program detail
│   ├── trainers/
│   │   ├── page.tsx
│   │   └── [slug]/page.tsx
│   ├── membership/
│   │   └── page.tsx
│   ├── gallery/
│   │   └── page.tsx
│   ├── blog/
│   │   ├── page.tsx
│   │   └── [slug]/page.tsx
│   ├── contact/
│   │   └── page.tsx
│   ├── faq/
│   │   └── page.tsx
│   └── api/
│       ├── contact/route.ts
│       ├── bmi/route.ts
│       └── booking/route.ts
├── components/
│   ├── ui/
│   │   ├── button.tsx      # shadcn/ui
│   │   ├── card.tsx
│   │   ├── input.tsx
│   │   └── ...
│   ├── layout/
│   │   ├── navbar.tsx
│   │   ├── footer.tsx
│   │   └── mobile-nav.tsx
│   ├── sections/
│   │   ├── hero.tsx
│   │   ├── stats.tsx
│   │   ├── programs-grid.tsx
│   │   ├── trainers-grid.tsx
│   │   ├── membership-toggle.tsx
│   │   └── ...
│   ├── shared/
│   │   ├── animation-wrapper.tsx
│   │   └── preloader.tsx
├── lib/
│   ├── animations.ts        # GSAP + Framer Motion helpers
│   ├── smooth-scroll.ts     # Lenis configuration
│   └── data/                # Content layer
│       ├── programs.ts
│       ├── trainers.ts
│       └── membership.ts
├── styles/
│   ├── globals.css          # Design tokens + typography + animations
│   └── components.css
├── public/
│   ├── images/
│   │   ├── hero/
│   │   ├── programs/
│   │   ├── trainers/
│   │   └── gallery/
│   └── fonts/
├── tailwind.config.ts
├── next.config.js
├── tsconfig.json
├── package.json
└── .env.local               # API keys, CMS URLs
```

## Tech Stack
- **Framework:** Next.js 14+ App Router
- **Language:** TypeScript
- **Styling:** Tailwind CSS v3 + shadcn/ui
- **Animations:** GSAP ScrollTrigger + Framer Motion
- **Smooth Scroll:** Lenis
- **Images:** next/image with Cloudinary or local public folder
- **CMS:** Sanity.io or Contentful for content management
- **Hosting:** Vercel

## Key Integrations
- **WhatsApp API** for booking inquiries
- **Supabase** for contact form + lead capture
- **Stripe** or Razorpay for online payments
- **Google Maps** embedded in contact page
- **YouTube API** for program videos

## Migration Path
1. Install Next.js + Tailwind + shadcn
2. Migrate HTML sections to React Server Components
3. Add client animations via `framer-motion` and `gsap`
4. Connect content layer to CMS
5. Deploy to Vercel with preview URLs

## Estimated Timeline
- Phase 1 (Weeks 1-2): Next.js scaffold + shadcn setup + all pages implemented
- Phase 2 (Weeks 3-4): Animations + CMS integration + contact/booking flows
- Phase 3 (Week 5): Photoshoot / asset collection + QA + deployment
