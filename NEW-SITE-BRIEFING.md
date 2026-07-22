# New Site Briefing — Paste This Into a Fresh Chat

Build me a multi-page static HTML website for a local SEO agency. Here are the full specs:

**Agency:** [YOUR AGENCY NAME] — a local SEO agency targeting [YOUR NICHE, e.g. plumbers / roofers / chiropractors]. Replace all placeholder business names and stats with ones appropriate for that niche.

---

## Pages to Build

All self-contained HTML files, no external CSS/JS dependencies:

1. `index.html` — Homepage with hero, social proof ticker, "what we do" section, how it works, results, pricing, FAQ, CTA
2. `services.html` — Services index with 4 card grid linking to detail pages
3. `service-maps.html` — Google Maps Dominance service detail
4. `service-reputation.html` — Reputation Engine service detail
5. `service-ai.html` — AI Recommendation Architecture service detail
6. `service-website.html` — Website Optimization (Core 30 Framework) service detail
7. `audit.html` — Free audit request page with left value prop + right Formspree AJAX form
8. `book-a-call.html` — Strategy call booking page with left "what to expect" + right Formspree AJAX form

---

## Design System

Use these exact CSS variables across all pages:

```css
--navy:#0B1F3A;
--blue:#1A6EFF;
--blue-light:#3B8BFF;
--coral:#F07248;
--coral-light:#F5895E;
--gray-100:#F4F7FC;
--gray-200:#E8EDF5;
--gray-500:#8494A9;
--gray-700:#3D4F63;
--green:#22C55E;
--radius:12px
```

Service accent colors:
- Maps = blue (`#1A6EFF`)
- Reputation = gold (`#F5A623`)
- AI = purple (`#7C3AED`)
- Website = teal (`#0F9B8E`)

---

## Shared Components (every page)

- **Fixed nav** (dark navy, blur backdrop): Logo left, nav links center, coral CTA button "Get Free Audit" → audit.html
- **Footer:** 4-column grid (brand + contact, Services, Company, Get Started)
- **Mobile breakpoints** at 900px and 560px

---

## Copy Framework

StoryBrand — the client is the hero, their problem is losing customers to competitors, the guide (agency) gives them a plan, the result is domination of local search. Adapt all copy to the niche.

---

## Forms

Formspree AJAX pattern with `action="https://formspree.io/f/YOUR_FORM_ID"`. On success, replace form HTML with a thank-you message inline. Do NOT redirect.

---

## Four Service Pillars

1. **Google Maps Dominance** — get into the local 3-pack
2. **Reputation Engine** — automated review generation
3. **AI Recommendation Architecture** — get recommended by ChatGPT, Perplexity, Claude, Google AI
4. **Core 30 Website Framework** — conversion-optimized website audit & rebuild

---

## Each Service Page Should Include

- Hero section with visual mockup built in HTML/CSS (no images needed)
- "What It Is" two-column section
- "How It Works" 3-step process
- "What's Included" grid (8 items)
- Results section with 3 fictional before/after case studies using niche-appropriate business names and cities

---

## Deployment

Static site — designed to deploy on Vercel (Framework: Other, blank build command, blank output directory). `index.html` at root serves as homepage.
