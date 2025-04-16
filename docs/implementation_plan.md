# Implementation Plan – First-Time 1031 Concierge

## Phase 1 – MVP (Days 1–30)
**Goal**: Launch a usable platform with core 1031 functionality for first-time users.

### Week 1–2:
- ✅ Set up project repo (Next.js 14 + Supabase backend)
- ✅ Build mobile-first layout structure with Tailwind + shadcn/UI
- ✅ Implement signup/login flow with Supabase Auth
- ✅ Design onboarding form: property type, sale price, estimated sale date

### Week 3:
- ✅ Build personalized 1031 Timeline Tracker (based on sale date)
  - Checklist logic
  - Email/SMS deadline reminders (Twilio integration)
- ✅ Create CMS in Airtable for experts
- ✅ Build Expert Marketplace UI (filterable directory)

### Week 4:
- ✅ Stripe Checkout integration for $99–$199 expert consults
- ✅ Calendly embed for post-payment scheduling
- ✅ Test end-to-end user flow: Signup → Timeline → Book Consult
- ✅ Launch soft beta with ~10 users

---

## Phase 2 – V1 (Days 31–60)
**Goal**: Add property marketplace + improve automation

- ✅ Add curated NNN Property Listings (pull from Airtable CMS)
- ✅ Filters: lease length, tenant type, location
- ✅ Each listing links out to broker URL
- ✅ Enable email/SMS reminder settings UI
- ✅ Begin building content blog (for SEO + education)

---

## Phase 3 – V2 (Days 61–90)
**Goal**: Introduce smart AI features + internal tools

- ✅ Build “Ask the 1031 Coach” chatbot using custom-trained FAQ model
- ✅ Create basic admin panel for managing users, experts, and bookings
- ✅ Add simple CRM for Realtor referrals (optional)
- ✅ Monitor usage analytics (Supabase + Posthog or similar)

---

## Team Setup Recommendation
- **Solo Developer** (full-stack, MVP builder)
- **1 Designer** (UX/UI contractor or Figma kit)
- **1 Tax/1031 Advisor (part-time)** – to review FAQ/chatbot content + expert vetting

---

## Optional Tasks
- Add webhook to auto-send consult receipts to user inbox
- Explore Zapier integration for expert CRM
- Translate key pages into Spanish for accessibility
- Launch via Product Hunt + Substack feature

---

## Early Access + Validation Goals
- ✅ 50 signups in first month (from Reddit, REI forums, or agent referrals)
- ✅ 5+ paid consults through platform
- ✅ Collect 10 user interviews for feedback

