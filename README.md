# 👋 Hi, I'm Nguakaaga Mvendaga

## Full-Stack SaaS Engineer

I ship production apps with auth, subscriptions, usage limits, secure dashboards, and webhooks—not toy UIs.

**Tooling:** Next.js 16 · React · TypeScript · Prisma · Postgres (Neon) · MongoDB · Clerk · JWT · Stripe (Checkout + Webhooks) · Vercel/Render

---

## 🔹 Featured Project — Multi-Tenant AI SaaS (Live)

**Live URL:** https://multi-tenant-ai-saas.vercel.app  
**Code:** https://github.com/fidelisnguakaaga20/multi-tenant-ai-saas

**What it does**

* Org (tenant) auto-provision on first sign-in
* Roles: OWNER / ADMIN / MEMBER; invite teammates
* Usage metering per org (FREE = 10 generations/month)
* Upgrade to **PRO** via Stripe Checkout → webhook promotes org to PRO (unlimited)
* Plan badge + usage in dashboard; legal pages (Terms/Privacy) visible
* AI demo route with safe fallback when OpenAI quota is missing

**Production notes**

* Edge auth via `proxy.ts` (Clerk) protecting `/dashboard(.*)`
* Per-org rate limiting; idempotent, retry-safe webhooks
* Single-source layout (no duplicate navbar/footer); mobile shows **Sign out**
* OpenAI 429 handled gracefully with user messaging
* CI/CD: push to `main` → Vercel deploy; tagged releases (e.g., `v0.2.0`)

**Stack**
Next.js 16 (App Router) · TypeScript · Clerk · Stripe · Prisma · Neon Postgres · OpenAI API · Route Handlers · Server Actions · Vercel

**How to try**

1. Sign in → org auto-created
2. **AI Demo** → generate text (uses quota)
3. **Pricing** → upgrade; webhook flips plan to **PRO**; dashboard updates

**Security & Ops**

* Server-side role checks for org resources
* `.env.local` kept out of repo; structured server logging

**Roadmap**

* Audit log UI, billing history, per-org API keys
* E2E tests (Playwright) + error tracking (Sentry)



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
