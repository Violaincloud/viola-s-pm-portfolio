# Viola S — Product Management Portfolio

**Product Manager · QA & Product Operations · Fintech & SaaS**

Lagos, Nigeria · 

---

## About Me

I'm a product manager with 6+ years of experience building and improving SaaS products starting from the customer side and working my way into full product ownership. My background spans fintech (wallet systems, payments, escrow), edtech, proptech, and marketplace products.

What makes my PM work different: I've been the person who takes the support ticket, escalates the bug, validates the fix, and writes the post-mortem. That context makes me a better PM — I write acceptance criteria engineers can actually build from, I spot edge cases early, and I design flows that account for what happens when things go wrong.

---

## Projects

| Project | Type | Domain | Status |
|---------|------|--------|--------|
| [Trovr Lite](#trovr-lite) | PRD · User Flows · Acceptance Criteria | Student Marketplace | Capstone — Submitted |
| [Campus Marketplace — Success Metrics](#campus-marketplace) | Metrics & Analytics Plan | Marketplace | Capstone — Submitted |
| [HouseIT](#houseit) | PRD · MVP Scope · User Stories | PropTech / Real Estate | Academic Project |
| [ISSOP](#issop) | PRD · Market Analysis · Personas | EdTech / SaaS | Academic Project |
| [Fintech UX Improvement](#fintech-improvement) | Product Analysis · Recommendations | Fintech / Payments | Original Case Study |

---

## Trovr Lite

**A trust-first student marketplace for Nigerian university campuses**

> *Trovr Lite is a focused platform that lets Nigerian university students list items they want to sell, discover what others are selling, and message each other to arrange a transaction — without leaving a chaotic WhatsApp group or trusting a stranger on the internet.*

**Role:** Lead Product Manager (Conclase Academy Capstone, Team 1)
**Version:** PRD v4.0 · May 2026

### The Problem
Nigerian university students buy and sell secondhand goods — textbooks, phones, furniture, laptops — through WhatsApp groups, Twitter/X, and paper flyers. Listings disappear into the scroll within hours. Scams are common. There is no way to verify a seller is a real student before agreeing to meet.

### The Solution
A campus-specific marketplace where:
- **Anyone can browse** without signing up (zero friction for discovery)
- **Sellers must verify** a school email address before posting
- **Buyers must verify** before messaging a seller (accountability before real-world meetings)
- **Trust signals** (verified badge, account age, items sold) are visible on every listing and profile

### Key PM Decisions
- **Open browsing vs. gated browsing:** Deliberately chose open browsing to solve the cold-start problem. Requiring sign-up just to look at listings kills discovery.
- **Guest-to-signup conversion as a core metric:** The moment a guest clicks "Message Seller" is the highest-conversion moment in the product. Designed the sign-up prompt to feel like a natural next step, not a wall.
- **Strict out-of-scope discipline:** Payments, delivery, ratings, and cross-campus features are all explicitly excluded from v1 with documented reasoning — not a backlog, a decision log.

### Figma Prototype
[View Designs →](https://www.figma.com/design/5Bznn0wYJDMzoHgXIpxZ9u/CapStone?node-id=0-1)

### Documents
- [Full PRD (v4.0)](projects/trovr-lite/PRD-v4.md) — 8 features, 40+ acceptance criteria, 7 user flows, risk assessment, rollout plan

### North Star Metric
**Conversations that lead to a marked-sold listing** — the intersection of discovery, trust, and outcome.

---

## Campus Marketplace — Success Metrics

**Analytics plan for the Trovr Lite capstone project**

**Role:** Lead PM — defined metrics framework for the full team
**Date:** 12 May 2026

### Philosophy
Metrics were defined before launch, not after. Every metric is tied to a specific user behaviour and a named owner.

### Key Decisions
- Explicitly identified **vanity metrics** the team agreed NOT to track (total signups, total messages sent, page views) — and documented why each one is noise
- Defined **analytics implementation plan** with specific event names, trigger conditions, and properties — not left to engineering to guess

### Core Metrics

| Metric | Target | Why |
|--------|--------|-----|
| Completed transaction rate | >15% within 2 weeks | Closest proxy to a real deal |
| Listing-to-conversation rate | >25% | Measures if listings are discoverable and compelling |
| Weekly active users | >30 WAU | Baseline health (paired with transaction rate) |
| Search-to-click rate | >40% | Measures search relevance |
| Verified seller rate | >80% | Trust signal health |
| Report rate | <5 per 100 listings | Fraud/spam early warning |

### Documents
- [Full Metrics & Analytics Plan](projects/campus-marketplace/success-metrics.md)

---

## HouseIT

**A VR/AR-powered real estate platform for Lagos renters**

> *People want an assurance that what they see is what they get. Potential renters are often disappointed when they arrive at apartments in Lagos because it looks different from what was advertised online.*

**Role:** Product Manager
**Domain:** PropTech · Real Estate · Lagos, Nigeria

### The Problem
- Landlords and agents deceive potential renters with misleading property photos
- Renters spend years searching for the right apartment
- Discrimination based on ethnicity, religion, and marital status is a widespread and largely unaddressed problem in the Lagos rental market

### The Solution
A property listing platform with:
- **VR/AR virtual tours** so renters can experience properties before visiting
- **Identity verification** of landlords, agents, and listings via VerifyMe/UVerify
- **Anti-discrimination policy** enforced through a binding contract at onboarding
- **Neighbourhood scouting** via Google Maps integration

### MVP Scope
Core: Authentication, property listings, search & filter, virtual tours, chat, ratings & reviews, geo-mapping, identity verification, discrimination prevention, save & share.

Post-MVP roadmap includes: AR interior design, live virtual tours, AI-powered personalised recommendations, financial calculators, property comparison tools.

### Revenue Model

| Market | Source | Mechanism |
|--------|--------|-----------|
| Landlords | Subscription | Listing fee per month |
| Renters | Premium | VR tour access, premium features |
| Advertisers | Ad revenue | Third-party promotions |
| Agents | Commission | % on successful rentals |

### Documents
- [PRD](projects/houseit/PRD.md)
- [MVP Feature Spec](projects/houseit/MVP.md)
- [User Flow (Miro)](https://miro.com/app/board/uXjVKTifZ9Y=/)

---

## ISSOP

**Integrated Smart School Operations Platform**

> *A cloud-based, mobile-first SaaS product for private K-12 schools in Nigeria and West Africa.*

**Role:** Product Manager (Conclase Academy Assignment)
**Version:** PRD v3.0 · May 2026

### The Problem
Private schools in Nigeria are running on paper. Administrators chase fee defaulters by phone. Attendance is taken in physical registers that no one reviews. Student pickups are verified by a security guard who recognises a face. Parent communication happens on WhatsApp groups that not everyone checks.

### The Solution — 4 Integrated Modules

| Module | Core Capability |
|--------|----------------|
| Smart Fee Management | Configurable installment plans, automated reminders, parent digital wallet, real-time financial dashboard |
| Student Safety & Pickup Authorization | QR-code entry/exit scanning, OTP-based pickup verification, emergency broadcast |
| Academic & Classroom Hub | Digital attendance, assignment distribution, deadline notifications, report generation |
| Unified Communication Suite | In-app messaging, school-wide broadcasts, push + SMS emergency alerts |

### Market Sizing
- **TAM:** ₦9 billion annual market (30,000+ private schools × ₦300K avg subscription)
- **SAM:** ₦2.4 billion (8,000 schools in Lagos, Abuja, Port Harcourt)
- **SOM Year 1:** ₦15 million ARR (50 schools)
- **SOM Year 2:** ₦100 million ARR (200 schools)

### Key Design Decisions
- **Android-first, iOS to follow:** Most school staff in Nigeria use Android. iOS would delay launch without meaningful user gain.
- **2-hour onboarding target:** Previous school management software failed because it required IT setup. ISSOP must be self-serve for a non-technical administrator.
- **NDPA compliance built in:** Nigeria Data Protection Act compliance is a requirement, not an afterthought.

### Documents
- [Full PRD v3.0](projects/issop/PRD-v3.md)

---

## Fintech Improvement — Original Case Study

**How to improve trust and UX in Nigerian fintech apps**

> An original product analysis identifying the most common UX and trust failures in Nigerian payment and wallet apps — with specific, actionable recommendations grounded in real user behaviour.

**Role:** Product Analyst / Author
**Type:** Original case study (not from a bootcamp)

[Read the full case study →](projects/fintech-improvement/README.md)

---

## Professional Experience

**Head of Support, Onboarding & QA — Clannit** *(2020–Present)*
- Contributed to product development of Clannit's in-app wallet system: Sterling Bank integration, wallet-to-wallet transfers, wallet-to-bank withdrawals, and escrow payment flows
- Led pre-deployment QA and release validation across payment features
- Reduced churn by 25%, onboarding friction by 35%, improved app store rating from 1★ to 4.0

**Customer Experience & Product Operations — PageFly** *(2024–Present)*
- Synthesised merchant feedback to inform the product roadmap
- Maintained 4.8/5 CSAT

---

## Tools
Jira · Notion · Figma · Miro · Trello · Google Analytics · Mixpanel · Zendesk · Intercom · Shopify · Slack
