# First-Time 1031 Concierge

## App Overview and Objectives
First-Time 1031 Concierge is a mobile-first web platform designed to guide first-time property sellers through the 1031 exchange process without mistakes. The platform combines educational content, personalized timeline tracking, vetted expert services, and curated investment opportunities—all within a trustworthy and professional user experience.

### Key Objectives:
- Educate users on 1031 exchanges in simple terms
- Help users stay on track with their 1031 timeline
- Connect users with vetted experts for professional support
- Offer beginner-friendly investment properties

## Target Audience
- Homeowners selling their first rental or commercial property
- Small-scale real estate investors (e.g., duplexes, 4-plexes)
- Realtors looking to refer clients needing 1031 exchange help

## Core Features and Functionality
- **Homepage**: Plain-English intro to 1031 exchanges, platform benefits, CTA to start
- **Signup Flow**: Email/password auth with basic property sale info collection
- **1031 Timeline Tracker**: Personalized checklist + deadline reminders via email/SMS
- **Expert Marketplace**: Vetted CPAs, attorneys, brokers with filters + Stripe payments
- **NNN Properties Marketplace**: Curated low-risk listings, filterable by investor needs
- **Consultation Booking**: Calendly integration for post-payment scheduling
- **Optional AI Coach**: Simple chatbot trained on 1031 FAQs

## High-Level Technical Stack
- **Frontend**: Next.js 14, Tailwind CSS, shadcn/UI
- **Backend**: Supabase (database, auth, email)
- **CMS**: Airtable (experts, property listings, FAQs)
- **Authentication**: Supabase email/password
- **Payments**: Stripe Checkout for expert consultations
- **Scheduling**: Calendly links per expert profile
- **Notifications**: Supabase + third-party SMS (e.g., Twilio)

## Conceptual Data Model
- **Users**: id, name, email, role, timeline_start_date, property_type
- **Timeline Items**: id, user_id, title, description, due_date, completed
- **Experts**: id, name, service_type, location, languages, calendly_link, stripe_price_id
- **Properties**: id, title, price, lease_length, tenant_type, location, external_broker_url
- **Bookings**: id, user_id, expert_id, time_slot, payment_status

## User Interface Design Principles
- Mobile-first, card-based layouts
- Font: Inter for a modern, clean look
- Color palette:
  - Primary: #1746A2 (deep blue - trust)
  - Accent: #00A6FB (light blue - freshness)
  - Background: White and soft grays (#F5F7FA)
- Clear CTAs, minimal jargon, and high readability

## Security Considerations
- Secure user authentication with Supabase Auth
- Stripe Checkout for PCI-compliant payments
- Role-based access control (e.g., admin, user)
- Data privacy for financial and contact information

## Development Phases / Milestones
**Phase 1 – MVP (30 Days):**
- Signup, Timeline Tracker, Expert Marketplace with payment + booking

**Phase 2 – V1 (60 Days):**
- NNN Property Listings, Email/SMS reminders

**Phase 3 – V2 (90 Days+):**
- AI Coach, CRM for Realtors, Admin dashboard

## Potential Challenges and Solutions
- **Complex tax/legal content** → Use expert-written FAQs + optional AI Coach
- **Calendar sync and booking reliability** → Leverage Calendly API for robustness
- **Maintaining trust** → Strong visual design + curated expert/properties only

## Future Expansion Possibilities
- Realtor referral dashboard & tracking
- Investor profiles and deal tracking
- In-app messaging with experts
- Real-time alerts on new listings
- Partner with brokerages for referral revenue

