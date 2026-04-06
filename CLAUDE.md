# MindKraft Farm Venture — Project Context

This file gives any Claude session full context on everything built for MindKraft Farm Venture.
Always read this before making any changes to the project.

---

## Business Overview

**Business name:** MindKraft Farm Venture
**Type:** Premium broiler chicken farm
**Location:** Owode, Osogbo, Osun State, Nigeria
**Launch date:** May 2026
**Owner:** Tobi (GitHub: Lorbar)
**WhatsApp:** +234 803 357 8281
**Email:** mindkraftfarm@gmail.com

**What they sell:**
- Live broiler chickens (2.2kg average, Arbor Acres & Cobb 500 breeds)
- Dressed chicken (slaughtered & cleaned)
- Bulk/wholesale orders (up to 2,000 birds per harvest)
- Event/owambe bulk supply (weddings, parties, naming ceremonies, church events)

**Farm capacity:** 2,000 birds per 6-week cycle
**Operating hours:** Monday–Saturday, 9:00 AM – 5:00 PM, Sunday Closed

**Primary market:** Osun State (Osogbo, Ede, Iwo, Ile-Ife, Ilesa, Ejigbo, Ikirun)
**Expanding to:** Oyo State (Ibadan, Ogbomosho, Oyo, Saki)
**Delivery:** Currently Osogbo and neighbouring towns, expanding state-wide

---

## Live URLs

| Product | URL |
|---|---|
| Main website | https://mindkraftfarmventure.netlify.app |
| Finance app | https://mindkraftapp.netlify.app |

---

## GitHub Repositories

| Repo | URL | Private? |
|---|---|---|
| Website | github.com/Lorbar/mindkraft-website | Public |
| Finance app | github.com/Lorbar/mindkraft-finance | Private |

**Git config:**
- Name: Tobi
- Email: ajao.daniel@gmail.com
- SSH key: set up at ~/.ssh/id_ed25519
- Remote: git@github.com:Lorbar/...

**Deploy workflow:**
1. Make changes to files in `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/`
2. `git add <files> && git commit -m "message" && git push`
3. Netlify auto-deploys within 60 seconds — no manual action needed

---

## File Locations

| File | Path |
|---|---|
| Website | `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/index.html` |
| Finance app | `/Users/tobi/Documents/AI/Farm_Claude/output/finance_app/` |
| Logo (navy/light bg) | `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/MindKraft_Logo_Navy.svg` |
| Logo (white/dark bg) | `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/MindKraft_Logo_White.svg` |
| Favicon | `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/favicon.svg` |
| Sitemap | `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/sitemap.xml` |
| Robots.txt | `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/robots.txt` |

---

## Tech Stack — Website

- **Single file static HTML** (`index.html`) — no framework, no build step
- **Tailwind CSS** via CDN (`https://cdn.tailwindcss.com`)
- **Google Fonts:** Cormorant Garamond (display/headings), Roboto (buttons), DM Sans (body)
- **Images:** Unsplash CDN (`images.unsplash.com/photo-[ID]?w=...&q=...`)
- **Form handling:** Web3Forms (free) → emails to mindkraftfarm@gmail.com
- **Hosting:** Netlify (free plan), auto-deploys from GitHub main branch

**Brand colours:**
- Navy: `#1E446A`
- Gold/brown: `#956E46`
- Light gold: `#D4A96A`
- Cream/background: `#FDF7EC`
- Dark navy: `#0E2130`
- Text: `#102539`

---

## Logo — The Luxury Stacked

Logo concept chosen by client: **Concept 04 — The Luxury Stacked**

Design elements:
- Triple rule top and bottom: thin (0.6px) · thick (2.2px) · thin (0.6px)
- "MINDKRAFT" in Roboto Black, letter-spacing 5, navy (#1E446A) on light / white on dark
- Diamond ornament (◆) flanked by gold rules as divider
- "FARM VENTURE" in Cormorant Garamond 500, letter-spacing 7, gold (#956E46)

Navbar SVG: `width="224" height="60" viewBox="0 0 224 60"`
Full SVG logo: `width="520" height="200" viewBox="0 0 520 200"`
Two colour variants saved as downloadable SVGs (see file locations above).

---

## Website Sections (in order)

1. **Navbar** — Fixed, white/95 bg, MK Luxury Stacked logo, nav links, "Place an Order" CTA
2. **Hero** — Full-screen, white broiler chickens image, headline + subtext + two CTAs
3. **Stats bar** — Fresh/Every Harvest · 6 Wk Cycle · 2.2kg · 2,000 Birds
4. **About/Vision** — Farm story, pills, white broilers image
5. **Offerings** — 3 product cards: Live Broilers, Dressed Chicken, Bulk & Wholesale
6. **Our Process** — 6-step numbered dark section
7. **Quality/Infrastructure** — Features + farm image
8. **Who We Serve** — 4 cards: Households, Restaurants & Hotels, Event Caterers, Wholesale Traders
9. **Delivery Areas strip** — Osun State towns + Oyo State towns listed
10. **Dark CTA** — Brand statement + two buttons
11. **FAQ** — Accordion
12. **Contact** — Info panel (phone, hours, map) + enquiry form
13. **Footer** — Logo, nav, products, contact, service areas, copyright

---

## Features Implemented

- ✅ Floating WhatsApp button (bottom-right, links to wa.me/2348033578281)
- ✅ MK diamond favicon
- ✅ Open Graph / Twitter Card meta tags (social sharing previews)
- ✅ Web3Forms contact form → emails to mindkraftfarm@gmail.com
- ✅ Google Maps embed (Owode, Osogbo)
- ✅ Scroll reveal animations (stat cards, offering cards, process steps)
- ✅ Mobile hamburger menu
- ✅ Netlify auto-deploy from GitHub
- ✅ Google Search Console verified (HTML file + HTML tag methods)
- ✅ Sitemap submitted to Google

---

## SEO Strategy

**Target keywords:** broiler chicken Osogbo, fresh chicken Osun State, buy chicken Oyo State,
chicken for owambe Nigeria, chicken for wedding Osun State, chicken delivery Osogbo,
event catering chicken Nigeria, chicken Ile-Ife, chicken Ibadan, poultry farm Osogbo

**What's been done:**
- Keyword-rich title tag and meta description
- Full JSON-LD LocalBusiness structured data (name, address, geo, hours, areaServed, products)
- Canonical URL tag
- Google Search Console verified + sitemap submitted
- robots.txt and sitemap.xml
- Keyword-rich image alt texts
- Oyo State + event keywords woven naturally into copy
- Delivery areas strip (visible on page + indexed by Google)
- Service areas in footer

**Google Search Console:** Verified at https://mindkraftfarmventure.netlify.app/
**Sitemap:** https://mindkraftfarmventure.netlify.app/sitemap.xml
**Verification files:** HTML file + meta tag both active (don't remove either)

---

## Third-Party Services

| Service | Purpose | Account | Notes |
|---|---|---|---|
| Netlify | Hosting + auto-deploy | mindkraftfarm@gmail.com | Free plan |
| GitHub | Code repository | Lorbar | SSH auth set up |
| Web3Forms | Contact form emails | mindkraftfarm@gmail.com | Free, access key in form hidden input |
| Google Search Console | SEO indexing | mindkraftfarm@gmail.com | Verified ✅ |
| Web3Forms access key | `eb006908-1dea-47d2-a39f-016db0572f92` | — | In index.html hidden input |

---

## Finance App

**Location:** `/Users/tobi/Documents/AI/Farm_Claude/output/finance_app/`
**Files:** index.html, app.js, style.css
**Live URL:** https://mindkraftapp.netlify.app
**GitHub:** github.com/Lorbar/mindkraft-finance (Private)
**Purpose:** Internal finance tracking — income, expenses, P&L reporting
**Deploy workflow:** Same as website — edit files, commit, push, Netlify auto-deploys

---

## How to Make Website Changes

1. Open Claude Code in `/Users/tobi/Documents/AI/Farm_Claude/Farm_Website/`
2. Tell Claude what to change
3. Claude edits `index.html` (and other files if needed)
4. Run: `cd /Users/tobi/Documents/AI/Farm_Claude/Farm_Website && git add <files> && git commit -m "description" && git push`
5. Wait ~60 seconds → change is live at mindkraftfarmventure.netlify.app

**Common change examples:**
- "Update phone number" → search for +234 803 357 8281 in index.html
- "Add a new FAQ" → find the `#faq` section
- "Change operating hours" → search for "Monday – Saturday" in index.html
- "Update capacity" → search for "2,000" in index.html

---

## Pending / Future Work

- [ ] Buy a custom domain (e.g. mindkraftfarm.com or mindkraftfarm.com.ng) and connect to Netlify
- [ ] Set up Google Business Profile (maps listing) for local SEO
- [ ] Add customer testimonials section once business launches
- [ ] Add product pricing once finalised
- [ ] Consider WhatsApp Business API for automated order responses
- [ ] Expand delivery areas copy as coverage grows to full Osun/Oyo State

---

## Key Decisions Made (and why)

- **Single HTML file:** Simplest possible setup — no build tools, easy to edit, fast to deploy
- **Netlify + GitHub:** Free hosting with auto-deploy — no manual uploads needed
- **Web3Forms over Netlify Forms:** Netlify email notifications cost $20/month; Web3Forms is free
- **Logo — The Luxury Stacked:** Client selected from 5 concepts; chosen for premium, no-icon look
- **Unsplash images:** Free CDN, no hosting costs, white broiler chickens only (important to client)
- **Web3Forms:** Free forever, unlimited submissions, no account needed beyond access key
