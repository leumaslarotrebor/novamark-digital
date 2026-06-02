# NovaMark — Digital Marketing Services Platform
### Aprisity Technologies — Web & Product Development Internship Assignment
**Candidate:** Samuel Oral Robert V | **ID:** WPD046 | **College:** Sathyabama Institute of Science and Technology

---

## Live Demo
🔗 https://leumaslarotrebor.github.io/novamark-digital/
---

## What I Built

A conversion-focused digital marketing services web platform — not just a landing page. Designed and developed as a real business product with measurable UX outcomes.

The brief asked for a digital marketing services webpage. I approached it the way a product engineer at a startup would: starting from business goals, not just visual requirements.

**Business goal of the page:** Convert visitors into audit requests (leads).
**Every design decision was made to serve that goal.**

---

## Sections & Why Each Exists

### 1. Hero Section
**Why:** First impression. Visitor decides in 3 seconds whether to stay.
- Animated word-by-word title reveal creates energy without being gimmicky
- Live dashboard mockup shows "proof before proof" — signals credibility immediately
- 4 KPIs (₹24Cr revenue, 380% ROAS, 200+ brands, 94% retention) establish authority in the first scroll
- Two CTAs: primary (Free Audit) and secondary (Explore Services) — captures both ready and curious visitors

### 2. Ticker / Marquee Strip
**Why:** Communicates breadth of services without taking up space. Used by Stripe, Linear, Vercel. Creates motion that keeps the eye engaged.

### 3. Pain Points Section
**Why:** Conversion science — people buy when they feel understood. Before showing solutions, show that you understand the problem. This section makes the visitor think "that's exactly my problem."

### 4. Services Slider (Tab Interface)
**Why:** 5 services would overwhelm as a grid. Tab interface = one focused message at a time. Each panel has:
- A specific benefit list
- A service-specific CTA
- Real metrics to back up the claim

### 5. Pricing Section (4 Plans)
**Why:** Transparent pricing builds trust. The "Most Popular" badge on Growth Engine anchors buyer psychology toward the mid-tier plan. Custom pricing for Enterprise removes price as an objection for large buyers.

### 6. ROI Calculator (Key Differentiator)
**Why:** Interactive tools = 3x longer time on page + 2x more leads (industry data). Most agencies don't show ROI upfront — this one does. The calculator:
- Takes real inputs (budget, revenue, industry, visitors, conversion rate)
- Applies industry-specific multipliers
- Returns projected revenue, ROAS, traffic, leads
- Delivers a personalized verdict that pushes toward the CTA

This is the feature that separates this submission from a standard landing page.

### 7. Testimonials + Results Band + Client Logos
**Why:** Social proof is the #1 conversion driver. Placed after pricing so a skeptical visitor who questioned the price sees validation immediately after.

### 8. FAQ Section
**Why:** Removes final objections before the CTA. Each question addresses a real sales objection: "How long for results?", "Can I cancel?", "What makes you different?" Answered honestly = builds trust.

### 9. Contact / Lead Capture Form
**Why:** The entire page exists for this moment. Form includes budget qualification, business type, and challenge statement — so the sales team knows exactly who they're talking to before the call.

### 10. Sticky CTA Bar
**Why:** Persistent conversion opportunity without being intrusive. Appears after 600px scroll. 15–20% of conversions on agency pages come from sticky CTAs.

---

## Technical Decisions

| Decision | Reason |
|----------|--------|
| Single HTML file | Zero dependencies, instant load, works offline, easy to host |
| CSS custom properties | Consistent design tokens, easy to retheme |
| No framework | Faster load time, simpler deployment, demonstrates raw frontend skill |
| Custom cursor | Premium feel, signals attention to detail — interviewers notice |
| Scroll reveal animations | Keeps the page feeling alive without slowing performance |
| Google Fonts (Syne + DM Sans) | Syne = strong, editorial, memorable. DM Sans = clean, readable. Distinctive pairing that doesn't feel generic |
| Dark theme | Aligns with premium digital agency aesthetic; reduces eye strain; makes accent colors pop |
| Mobile-first responsive | 60%+ of Indian users browse on mobile |

---

## Design System

**Colors:**
- Background: `#07070f` — near-black with blue undertone (not pure black — softer)
- Surface: `#0d0d1c` — card background
- Accent Red: `#ff4427` — CTAs, highlights, active states
- Accent Yellow: `#ffbe0b` — metrics, hover states, results
- Muted: `#7a788a` — body text, labels

**Typography:**
- Display / Headings: Syne 800 — editorial, strong, memorable
- Body: DM Sans 400/500 — clean, readable at small sizes

**Motion:**
- Hero words: staggered translateY reveal (cubic-bezier ease-out)
- Cards: scroll-triggered fadeUp via IntersectionObserver
- Bars: scaleX grow animation with delay
- Cursor ring: lerp-based follow (smooth, not snappy)

---

## ROI Calculator Logic

```
projectedRevenue = currentRevenue × (1 + (ROAS_multiplier - 1) × growthFactor × 0.4) + adBudget × ROAS_multiplier
projectedROAS = projectedRevenue / adBudget
projectedTraffic = currentVisitors × trafficMultiplier × growthFactor
projectedLeads = projectedTraffic × (conversionRate × convMultiplier / 100)
growthFactor = 1 + (months / 12) × 0.6
```

Industry multipliers sourced from aggregated digital marketing benchmarks (WordStream, HubSpot, Statista).

---

## AI Tools Used

- **Claude (Anthropic):** Architecture planning, copywriting, component structure
- **ChatGPT:** Pricing benchmark research, FAQ content ideation
- **Reasoning:** AI was used for acceleration, not replacement. Every design decision, layout choice, and business rationale was thought through independently and I can explain each one.

---

## What I Would Add With More Time

1. **Dark/Light mode toggle** — CSS variable swap, 20 lines of JS
2. **Animated counter numbers** — count up from 0 on scroll reveal
3. **Video testimonials section** — higher trust than text
4. **Blog/case studies section** — SEO value + content marketing
5. **WhatsApp chat widget** — high conversion in Indian market
6. **Google Analytics integration** — conversion tracking

---

## Submission Details

- **Candidate:** Samuel Oral Robert V
- **Candidate ID:** WPD046
- **College:** Sathyabama Institute of Science and Technology
- **Role Applied:** Web & Product Development Internship
- **Submission Date:** June 2026
- **Live Link:** [novamark-digital.netlify.app](https://novamark-digital.netlify.app)
- **Source File:** `NovaMark_Aprisity_Assignment.html`
