# Samara Gym | Luxury Redesign — Deployment Guide

## Live Preview
- Local server: `http://localhost:5678/`
- File path: `C:\Users\SUJJAD\Desktop\SAMARA_LUXURY\index.html`

## Tech Stack
- HTML5 + CSS3 + Vanilla JavaScript (production-ready single-page experience)
- Fonts: Inter (Google Fonts CDN)
- Images: Unsplash royalty-free assets

## Design System
- Background: #050505
- Secondary: #0A0A0A
- Accent: #C8FF00 (Electric Lime)
- Typography: Inter 300-900
- Layout: Dark cinematic, glassmorphism cards, minimal spacing

## Key Sections
1. Hero — Full-screen cinematic bg, animated headline FORGE YOUR LEGACY, CTAs
2. Stats — 15+ Programs, 40+ Coaches, 5000+ Members, 7+ Years
3. About — Split layout philosophy + lifestyle image
4. Programs — 8 luxury cards (Strength, CrossFit, HIIT, Yoga, Spinning, PT, Kids, Nutrition)
5. Equipment — 3 cinematic cards
6. Trainers — 4 premium cards with certifications
7. Transformations — 3 metric cards (18KG lost, 8KG muscle, 30 days)
8. Testimonials — Carousel with 3 real reviews
9. Membership — 3 pricing cards Starter/Performance/Elite with monthly/yearly toggle
10. Gallery — Masonry grid
11. Blog — 3 article cards
12. FAQ — 6 accordion items
13. BMI Calculator — Interactive tool
14. Contact — Form + location/call/email/hours
15. Footer — Brand + links + social

## Animations
- Preloader with progress bar
- Scroll-triggered reveal animations
- Stats counter animation
- Hero parallax
- Card 3D tilt effect
- Magnetic buttons
- Auto-advancing testimonial carousel
- Membership pricing toggle
- BMI calculator with color-coded results

## SEO
- Semantic HTML5
- OpenGraph tags
- Meta description
- Alt text on all images
- Lazy loading images

## Accessibility
- Skip to main content link
- ARIA labels and roles
- Keyboard-navigable FAQ and pricing toggle
- Focus states

## Performance
- No build step required for the single HTML version
- All assets loaded from CDN or lazy-loaded
- CSS animations use GPU-accelerated transforms
- Minimal JS footprint ~3KB

## Next Steps
1. Replace Unsplash placeholder URLs with actual gym photography
2. Update phone number and contact details to real values
3. Connect form to backend API or email service
4. Integrate BMI calculator with InBody API if available
5. Add real trainer data and transformation photos
6. Implement online payment gateway for membership signups
