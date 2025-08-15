![Project Banner](public/readme/hero.png)

# 🧠 Converso – AI-Powered SaaS Learning Platform

**Converso** is a modern, AI-driven SaaS platform for real-time, voice-activated learning experiences.  
Built with Next.js, Supabase, Clerk, Stripe, Vapi, TypeScript, and TailwindCSS, Converso enables developers to launch and monetize SaaS products rapidly, with a focus on scalability, interactivity, and user experience.

---

## 🚀 Features

- **Secure Authentication:**  
  - Intuitive sign-up and login with Clerk
  - Customizable user profiles

- **Voice-Activated AI Lessons:**  
  - Real-time, interactive learning sessions powered by Vapi
  - Personalized experiences for any topic

- **Modern, Responsive UI:**  
  - Built with TailwindCSS and Shadcn UI for a seamless experience on all devices

- **Search & Discovery:**  
  - Powerful search and filtering to find companions and sessions

- **Scalable Database:**  
  - Supabase (Postgres) for real-time data, session history, and bookmarks

- **Session History & Bookmarks:**  
  - Track progress and revisit previous lessons

- **Flexible Subscription System:**  
  - Multiple plans (Basic, Core, Pro) with feature gating based on plan
  - Instant payments and billing via Clerk Billing and Stripe

- **Payments & Monetization:**  
  - Easy integration of pricing tables and checkout flows
  - Stripe for secure, instant transactions

- **Error Tracking & Monitoring:**  
  - Sentry for real-time error tracking, performance monitoring, and session replays

---

## 🛠️ Tech Stack

- **Frontend:** Next.js (App Router, SSR, server actions), TypeScript, TailwindCSS, Shadcn UI
- **Backend:** Supabase (Postgres, RLS, instant APIs), Vapi (voice AI), Clerk (auth & billing)
- **Payments:** Clerk Billing, Stripe
- **Monitoring:** Sentry
- **Forms:** React Hook Form, Zod
- **Other:** GitHub (version control), Juny (AI code assistant), Lottie (animations)

---

## ⚡ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-user/converso.git
   cd converso
Install dependencies:

Bash

npm install
Configure environment variables:
Create a .env.local file with:

Supabase keys and URLs
Clerk keys
Stripe keys
Vapi API keys
Sentry DSN
Run the development server:

Bash

npm run dev
Access the app:
Open http://localhost:3000 in your browser.

🧩 Application Structure
/ – Homepage, sign-in, recent sessions
/companions – Companion library and builder
/sessions – Real-time AI learning sessions
/profile – User profile, session history, and bookmarks
/pricing – Subscription plans and checkout
🖼️ Screenshots
Home	AI Session	Pricing
Home	Session	Pricing
💡 Best Practices & Highlights
Rapid MVP-to-monetization workflow (launch in under 7 days)
Reusable UI components with Shadcn UI
Server actions for secure, scalable backend logic
Real-time voice AI with Vapi
Plan-based feature gating with Clerk
Continuous deployment and versioning with GitHub
Mobile-first, accessible design


Thank you for visiting! If you like this project, please star the repo and follow me on GitHub.
Happy coding! 🚀
