# App Flow, Pages & Roles – First-Time 1031 Concierge

## 🧭 App Navigation Flow
1. **Homepage**
   - Intro to 1031 exchanges
   - Platform benefits
   - “Start Your 1031 Timeline” CTA

2. **Signup Flow**
   - Email/password signup
   - Form collects: property type, sale date, price
   - Route to dashboard on success

3. **Dashboard – 1031 Timeline Tracker**
   - Personalized step-by-step checklist
   - Status indicators (e.g., done, upcoming, urgent)
   - Email/SMS reminders auto-triggered

4. **Expert Marketplace**
   - Filterable directory (CPA, Attorney, Broker)
   - View expert cards with bio, location, language, price
   - Book consult (Stripe payment → Calendly link)

5. **NNN Property Listings**
   - Curated low-risk listings for beginners
   - Filters: lease length, tenant type, location
   - External broker contact link (no in-app messaging)

6. **Ask the 1031 Coach (optional AI)**
   - Chat UI for common FAQs
   - Friendly, plain-English answers
   - Suggests next steps and relevant links

---

## 📄 Page List
- `/` – Homepage
- `/signup` – Signup form
- `/dashboard` – 1031 Timeline view
- `/experts` – Browse experts
- `/properties` – View property listings
- `/consultation/complete` – Booking success screen
- `/chat` – (Optional) AI 1031 Coach
- `/admin` – Admin dashboard (V2)

---

## 👥 User Roles

### 1. **General User**
- Can sign up and manage their 1031 timeline
- Book consultations with experts
- View investment property listings

### 2. **Admin** (Internal Only)
- Can manage experts and approve property listings
- View all bookings and transactions
- Add FAQs and manage AI training data

### 3. **Expert** (Optional future role)
- If enabled later, experts could log in to view/manage their bookings
- Not needed for MVP

