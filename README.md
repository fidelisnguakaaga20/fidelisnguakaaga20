````markdown
# Single Brand Store

High-impact **single-brand fashion e-commerce** demo built with **Next.js 16 (App Router), TypeScript, Tailwind, Prisma, PostgreSQL (Neon), and Stripe**.

Built by **Nguakaaga Mvendaga — Full-Stack SaaS Engineer (Next.js · TypeScript · Stripe · Prisma)**

---

## 🚀 Live Demo

- **Live demo: https://single-brand-store.vercel.app

- **Admin login page:** https://single-brand-store.vercel.app/login  

> 🔐 **Demo admin credentials (TEST only)**  
> Email: `admin@example.com`  
> Password: `Admin123!`  

---

## 🧱 Tech Stack

- **Framework:** Next.js 16 (App Router) + React  
- **Language:** TypeScript  
- **Styling:** Tailwind CSS  
- **Animations:** Framer Motion  
- **Database:** PostgreSQL (Neon) via Prisma ORM  
- **Auth:** Custom JWT-based auth (`CUSTOMER` & `ADMIN` roles)  
- **Payments:** Stripe Checkout (TEST mode, no real charges)  
- **Hosting:** Vercel (app + API routes), Neon (database)  

---

## ✨ Core Features

### Public Storefront

- Hero section with **“Shop now”** and collection CTAs  
- Home highlights:
  - **New Arrivals**
  - **Best Sellers**
  - **Limited Editions**
- Product grid with:
  - Price, badges (New / Best Seller / Limited)
  - Responsive Tailwind layout + Framer Motion animations
- Product detail page:
  - Variants (size, color, price, stock)
  - Add to cart

### Catalog & Filters

- `/shop` page with:
  - Full catalog grid
  - Search by name, description, or tagline
  - Filter by **collection**, **price range**, and **tags**
  - Sort by newest, price (low → high / high → low), best sellers
- `/collections/[slug]` pages for:
  - New Arrivals, Best Sellers, Men, Women, Accessories, Limited Editions
  - Collection hero banners (AI-generated images) + filtered products

### Cart & Checkout (TEST Mode)

- Global cart using React context  
- Add/remove items, update quantity, view totals  
- Stripe Checkout using TEST keys  
- **No real payments** — demo flow only  

### Auth & Admin

- Email/password login with JWT  
- Roles:
  - `CUSTOMER` – browse, add to cart, start checkout
  - `ADMIN` – access `/admin` dashboard
- Admin dashboard includes:
  - Products list & basic catalog management
  - Promotions list
  - Orders list & order details

> ⚠️ Admin changes (price, stock, promotions, etc.) affect what **all users** see — same behavior as a real store back office.

---

## 🛠 Local Development

> The app is live on Vercel, but you can also run it locally.

```bash
git clone https://github.com/fidelisnguakaaga20/single-brand-store.git
cd single-brand-store
npm install
npm run dev
````

Then open `http://localhost:3000`.

---

## 🧪 Related Production-Grade SaaS Projects

For recruiters: these are other live projects that show my focus on **SaaS, billing, and real-world dashboards**.

### 1. Multi-Tenant AI SaaS (Featured)

* **Live:** [https://multi-tenant-ai-saas.vercel.app](https://multi-tenant-ai-saas.vercel.app)
* **Code:** [https://github.com/fidelisnguakaaga20/multi-tenant-ai-saas](https://github.com/fidelisnguakaaga20/multi-tenant-ai-saas)
* **Highlights:** Multi-tenant orgs, roles (OWNER / ADMIN / MEMBER), usage metering, Stripe upgrades (FREE → PRO), webhooks, and secure dashboard.

---

### 2. Stripe Revenue Copilot

* **Live:** [https://stripe-revenue-copilot.vercel.app](https://stripe-revenue-copilot.vercel.app)
* **Code:** [https://github.com/fidelisnguakaaga20/stripe-revenue-copilot](https://github.com/fidelisnguakaaga20/stripe-revenue-copilot)
* **Highlights:** Subscription analytics, Stripe Checkout upgrades, webhook-driven DB sync, reconcile jobs, and per-org billing dashboard.

---

### 3. Meal Plan SaaS

* **Live:** [https://meal-plan-saas.vercel.app](https://meal-plan-saas.vercel.app)
* **Stack:** Next.js 15 · Stripe · Clerk · Prisma · Neon DB
* **Highlights:** Subscription-based meal planning with auth, protected dashboard, and Pro tier via Stripe Checkout.

---

### 4. Job Board Platform

* **Live:** [https://job-board-next15-clean.vercel.app](https://job-board-next15-clean.vercel.app)
* **Stack:** Next.js 15 · WorkOS SSO · AWS S3 · MongoDB
* **Highlights:** Enterprise SSO login, job posting, S3 media uploads, and company admin dashboard.

---

### 5. Realtime Chat App

* **Live:** [https://chat-app-mocha-six-38.vercel.app](https://chat-app-mocha-six-38.vercel.app)
* **Stack:** MERN · Socket.io · JWT · MongoDB
* **Highlights:** Realtime messaging, presence, protected APIs, and token-based auth.

---

### 6. NGU-TOP E-Commerce

* **Live:** [https://ngu-top-e-commerce.vercel.app](https://ngu-top-e-commerce.vercel.app)
* **Stack:** MERN · Redux Toolkit · JWT
* **Highlights:** Full e-commerce flow with catalog, cart, checkout, and admin/customer separation.

---

## 👤 About Me

**Full-Stack SaaS Engineer · Next.js · TypeScript · Stripe · Prisma**

I build production-ready SaaS and e-commerce apps with:

* Real billing (Stripe Checkout + webhooks)
* Role-based dashboards
* Usage limits & paywalls connected to plans
* Secure server-side data fetching and clean codebases

---

## 📫 Contact

* **Email:** [fidelisnguakaaga20@gmail.com](mailto:fidelisnguakaaga20@gmail.com)
* **Phone:** 07031128081 / 07011507142
* **LinkedIn:** [https://www.linkedin.com/in/nguakaaga-mvendaga](https://www.linkedin.com/in/nguakaaga-mvendaga)
* **GitHub:** [https://github.com/fidelisnguakaaga20](https://github.com/fidelisnguakaaga20)

```
```
