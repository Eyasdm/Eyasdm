<div align="center">

# Eyas Mohammed

**Full-Stack Developer · iOS Learner · Electrical Engineering Student**

*Sukabumi, Indonesia · Originally from Sudan*

[![Portfolio](https://img.shields.io/badge/Portfolio-eyas.dev-000000?style=flat&logo=vercel&logoColor=white)](https://eyas-dev.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eyas-mohammed/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:eyasadamelfaki@gmail.com)

</div>

---

## About

I build technology for real problems — the kind where the user has unreliable internet, no tech background, or no existing tool that fits. Three deployed production apps, a desktop ERP running live in a client's business, and a top-5 finish in a national ML hackathon. Currently learning iOS because a real client needed push notifications that a desktop app can't deliver.

Electrical Engineering student at Nusa Putra University (GPA 3.95 / 4.00). The engineering background isn't separate from the software work — it's what pushes me toward problems that matter: agriculture, infrastructure, tools that work without connectivity.

---

## Open Source

Contributing to [**Headlamp**](https://github.com/headlamp-k8s/plugins), the CNCF/Kubernetes-SIG extensible web UI, focused on its Knative plugin — accessibility, internationalization, and Eventing resource support.

- [**#1066**](https://github.com/headlamp-k8s/plugins/pull/1066) — full i18n sweep of the Knative plugin: 260 translation keys across 36 files, following the established `flux` plugin convention.
- [**#1136**](https://github.com/headlamp-k8s/plugins/pull/1136) — split from #1066 for reviewability: `clusterdomainclaims` views plus a `domain.ts` fix threading `t` into a non-React helper.
- [**#1057**](https://github.com/headlamp-k8s/plugins/pull/1057) — accessibility fix for color-only status indicators in `PodsSection` (WCAG 2.1 SC 1.4.1).

Also active on the Knative Eventing design discussion ([#922](https://github.com/headlamp-k8s/plugins/issues/922), [cncf/mentoring#2001](https://github.com/cncf/mentoring/issues/2001)) — duck-typed source discovery, condition semantics, and Trigger filter behavior, verified against a local Knative Serving + Eventing cluster.

---

## Projects

### 🏆 IndabaX Sudan ML Hackathon — 4th / 132 teams
Agricultural dry spell prediction model for Sudan. Binary classification on 17 years of daily climate data — soil moisture, vapor pressure deficit, sea surface temperatures, atmospheric pressure. HistGradientBoosting with a 3-model rank ensemble and recency-weighted predictions for temporal drift.

→ [`indabax-dryspell-prediction`](https://github.com/Eyasdm/indabax-dryspell-prediction)

---

### BizCore Desktop — Client ERP
Desktop application built for a real client (Al-Khattaf boutique). Electron + React frontend, SQLite for local-first storage, bidirectional multi-device sync engine with conflict resolution via Supabase, cloud backup on Cloudflare R2. Handles invoicing, inventory, accounting ledgers, and role-based access. Full RTL/Arabic UI, including a character-level Arabic shaper for PDF invoice rendering. Running in a live business.

*Private repo — client work*

---

### BizCore Mobile — iOS Companion App
Lightweight iOS inventory companion for the BizCore desktop ERP. Built because the client specifically asked for low-stock alerts on their phone — something a desktop app physically can't push. SwiftUI, SwiftData, Supabase REST API, local push notifications. Reads from the same production database as the desktop app.

→ [`bizcore-mobile`](https://github.com/Eyasdm/bizcore-mobile)

---

### TechNest — Full-Stack E-Commerce
Solo end-to-end build: Next.js frontend, Express/Node backend, MongoDB, Stripe payments with idempotent verified webhooks, JWT auth, role-based access control, Gemini AI chatbot, automated email (Brevo), admin dashboard. Deployed on Vercel + Render.

→ [Live Demo](https://e-commerce-eyasdms-projects.vercel.app) · [`e-commerce`](https://github.com/Eyasdm/e-commerce)

---

### Brew-Bite — Cafe Ordering System
Two-part system: a customer-facing Next.js ordering app with QR-based cashier verification, cart management, and pickup/delivery flow — and a separate React/Vite admin dashboard (TypeScript) for order tracking, menu management, and analytics. Both connected to Supabase with real-time sync.

→ [Brew-Bite Website](https://brewbite.netlify.app) · [Dashboard](https://brew-bite-dashboard.netlify.app) · [`Brew-bite-website`](https://github.com/Eyasdm/Brew-bite-website) · [`brew-bite-dashboard`](https://github.com/Eyasdm/brew-bite-dashboard)

---

## Tech Stack

**Languages**
JavaScript (ES6+) · TypeScript · Python · Swift · SQL · HTML · CSS

**Frontend**
React · Next.js · SwiftUI · Tailwind CSS · Zustand · TanStack Query · shadcn/ui · Vite

**Backend**
Node.js · Express.js · REST APIs · Supabase · Electron

**Databases**
MongoDB · PostgreSQL · SQLite · SwiftData · Supabase (Postgres)

**ML / Data**
scikit-learn · pandas · numpy · scipy · Jupyter · Google Colab

**Tools**
Git · GitHub · Vercel · Render · Cloudflare R2 · Stripe · Google OAuth · Xcode · kind · kubectl

---

## Currently

- 🧩 Contributing to Headlamp (CNCF) — Knative plugin i18n, a11y, and Eventing support
- 📱 Building BizCore Mobile — iOS companion for a live client's desktop ERP
- 🌱 Deepening Swift and Apple HIG for real-world iOS development
- 📊 Active DSA practice → [`neetcode-submissions`](https://github.com/Eyasdm/neetcode-submissions)
- 🎓 3rd year Electrical Engineering, Nusa Putra University — GPA 3.95 / 4.00

---

## Background

- 🇸🇩 Sudanese · based in Indonesia since 2024
- 🗣️ English · Arabic · Indonesian (A2)
- 🏅 IndabaX Sudan ML Hackathon — 4th / 132 teams (Dec 2025)
- 📜 McKinsey & Company Forward Program — 10-week global leadership program

---

<div align="center">

*I use technology to solve real problems for people who need it.*

</div>
