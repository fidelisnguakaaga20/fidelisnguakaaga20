# 👋 Hi, I'm Nguakaaga Mvendaga

🚀 Full-Stack SaaS Engineer  
I build production-grade web apps with authentication, subscriptions, usage limits, and secure dashboards — not just UI demos.

I work mainly with:
- **Next.js / React / TypeScript**
- **Prisma + Postgres (Neon) / MongoDB**
- **Clerk / JWT auth**
- **Stripe subscriptions & webhooks**
- **Vercel / Render for deployment**

---

## 🔹 Featured Projects (Live SaaS)

### 1. Multi-Tenant AI SaaS  
**Status:** Live on Vercel (Production)  
**Live URL:** https://multi-tenant-ai-saas.vercel.app  
**Code:** https://github.com/fidelisnguakaaga20/multi-tenant-ai-saas

**What it is:**
A production-ready AI workspace for teams. Each user gets an organization (tenant) with:
- Auth & onboarding using Clerk
- Workspace / organization auto-created on first sign-in
- Role-based access (OWNER / ADMIN / MEMBER)
- Invite teammates to your org
- Usage metering per org (free plan = 10 AI generations / month)
- Paid upgrade to PRO with Stripe Checkout
- Stripe webhook promotes org to PRO → unlocks unlimited usage
- Billing status and usage shown inside dashboard
- Legal pages (Terms / Privacy) exposed in UI for compliance
- Hosted on Vercel, Postgres on Neon, AI calls via OpenAI API

**Stack:**  
Next.js 16 (App Router) · TypeScript · Clerk Auth · Stripe Billing · Prisma ORM · Neon Postgres · OpenAI API · Server Actions / Route Handlers · Vercel

**Why this matters to employers:**  
This is not a toy UI. It shows:
- Multi-tenant architecture
- Real billing lifecycle
- Secure server-side logic with role checks
- Webhooks in production
- CI/CD to Vercel
- Handling rate limiting and usage quotas

---

### 2. Meal Plan SaaS  
**Live URL:** https://meal-plan-saas.vercel.app  
**Stack:** Next.js 15 · Stripe · Clerk · Prisma · Neon DB  
**Summary:**  
Subscription-based meal planning app. Includes auth, protected dashboard, dynamic content per user, and paid Pro tier using Stripe Checkout.

**What it shows:**  
- Paid SaaS flow with upgrade wall  
- Persistent data in Postgres via Prisma  
- Deployed & usable publicly

---

### 3. Job Board Platform  
**Live URL:** https://job-board-next15-clean.vercel.app  
**Stack:** Next.js 15 · WorkOS SSO · AWS S3 · MongoDB  
**Summary:**  
Job marketplace with company login (WorkOS SSO), job posting, and media upload to S3.

**What it shows:**  
- Enterprise auth (SSO)  
- File storage in S3  
- Admin-style dashboard for companies

---

### 4. Realtime Chat App  
**Live URL:** https://chat-app-mocha-six-38.vercel.app  
**Stack:** MERN · Socket.io · JWT · MongoDB  
**Summary:**  
Full realtime messaging with authentication, live presence, and protected API routes.

**What it shows:**  
- WebSockets / Socket.io  
- Token-based auth with refresh flow  
- Realtime UI (typing indicators / seen states, etc.)

---

### 5. NGU-TOP E-Commerce  
**Live URL:** https://ngu-top-e-commerce.vercel.app  
**Stack:** MERN · Redux Toolkit · JWT  
**Summary:**  
Full e-commerce stack with product catalog, cart state, checkout flow, and admin management.

**What it shows:**  
- State management at scale (Redux Toolkit)  
- Authenticated cart / orders  
- Admin vs customer flows

---

## 🧠 Core Skills

**Frontend**
- Next.js (App Router, RSC)
- React + TypeScript
- Tailwind / utility-first UI

**Backend**
- Next.js API Routes & Route Handlers
- Node.js / Express.js REST APIs
- Role-based access control
- Webhooks (Stripe / custom)
- Rate limiting & usage metering logic

**Auth**
- Clerk (passwordless / social)
- WorkOS SSO (enterprise login)
- JWT sessions

**Billing**
- Stripe Checkout sessions
- Subscription plans (FREE vs PRO)
- Post-payment webhooks that update DB state
- Enforcing paywall rules in app logic

**Data**
- Prisma ORM
- Postgres (Neon)
- MongoDB / Mongoose
- Usage tracking per tenant / per month

**Infra / DevOps**
- Vercel (full-stack Next.js)
- Render / AWS S3
- CI/CD with GitHub → Vercel
- Environment variable management
- Production debugging / logs

---

## 🏆 What I actually deliver

- SaaS with real billing, not fake buttons  
- Multi-tenant architecture (orgs, roles, invite teammates)  
- Usage limits & paywalls that connect to Stripe plans  
- Secure dashboards with server-side data fetching  
- Realtime features where needed (chat, presence, activity)  
- Clean handoff docs so teams can maintain it

---

## 📫 Contact

- Email: fidelisnguakaaga20@gmail.com  
- Phone: 07031128081 / 07011507142  
- LinkedIn: https://www.linkedin.com/in/nguakaaga-mvendaga  
- GitHub: https://github.com/fidelisnguakaaga20
