Changes made for TalentKonnect Launch Race landing

Files added:
- index.html — Complete, semantic landing page with hero, how-it-works, rewards, countdown, testimonials, and a checkout placeholder.
- styles.css — Lightweight, responsive CSS using a single accent color (#00BFA6), rounded corners, soft shadows, and responsive breakpoints.

What was changed / implemented
- Full hero section with headline “Launch Your Project. Compete. Win Bali.”, sub-headline, CTAs, and a visual placeholder.
- How the Skill Race Works section implemented as a 3-column responsive grid.
- Rewards banner with three reward cards and a primary CTA to checkout.
- Countdown timer (client-side JS) set to 7 days from current load for demo purposes.
- Smooth scroll behavior for internal links.
- Mobile sticky CTA that appears when scrolling on small screens.
- Simple intersection animations for cards and hero visual.
- SEO meta tags, Google Inter font link, and favicon placeholder reference.
- Accessibility: semantic elements, focus outlines, and button keyboard support.

Design decisions / rationale
- Tech: Chosen plain HTML/CSS/vanilla JS for zero-setup preview; could be ported to React+Tailwind if desired.
- Visuals: White background with teal accent to keep look minimal and premium. Soft shadows and rounded corners make CTAs feel tangible.
- Copy: Realistic short content used (no lorem ipsum). Clear benefit statements and immediacy around "Next batch".
- UX: Sticky mobile CTA, smooth scroll, and subtle animations to increase conversion trust and perceived polish.

What I'd add next for production readiness
1. Replace placeholder checkout link with real payment flow and server-side validation.
2. Add analytics (Segment/GA4) and conversion tracking on CTA clicks.
3. Add A/B testing variants for hero copy and CTA text.
4. Optimize assets: include an SVG logo, compressed images, and critical CSS inlined for first paint.
5. Add unit/E2E tests for interactive behaviors and accessibility checks (axe).
6. Add OpenGraph tags for social sharing and richer link previews.
7. Add structured data (schema.org) for product/offers and event start time.

Notes / How to preview
- Open `index.html` in a browser (double-click or serve with a static host). It's front-end only and needs no build.
- For production deployment, push these files to a Vercel or Netlify site and configure the checkout endpoint.

End of changes.md