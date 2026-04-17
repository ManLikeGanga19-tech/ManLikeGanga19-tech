<div align="center">

```
 ██████╗  █████╗ ███╗   ██╗ ██████╗  █████╗ 
██╔════╝ ██╔══██╗████╗  ██║██╔════╝ ██╔══██╗
██║  ███╗███████║██╔██╗ ██║██║  ███╗███████║
██║   ██║██╔══██║██║╚██╗██║██║   ██║██╔══██║
╚██████╔╝██║  ██║██║ ╚████║╚██████╔╝██║  ██║
 ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝  ╚═╝
```

**Senior Fullstack Engineer · DevOps · SaaS Architect**  
📍 Mombasa, Kenya 🇰🇪 &nbsp;|&nbsp; Building production-grade platforms for Africa

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Multi-tenant+SaaS+%7C+End-to-end+ownership;Next.js+%7C+FastAPI+%7C+ASP.NET+Core+%7C+Go;M-Pesa+Daraja+%7C+KRA+eTIMS+%7C+Kubernetes;From+architecture+to+production+%E2%80%94+I+own+the+whole+stack.)](https://git.io/typing-svg)

</div>

---

## 👨🏾‍💻 About Me

I'm a **Senior Fullstack Developer & DevOps Engineer** who designs, builds, and ships enterprise-grade SaaS products end-to-end — from schema design to containerized cloud deployment.

My focus is solving **real operational problems** for African businesses: school administration, e-learning, retail POS, and sustainable housing. I've shipped systems live in production, integrated **M-Pesa Daraja** for subscription billing and STK Push payments, and navigated **KRA eTIMS** compliance from scratch.

```yaml
name:         ManLikeGanga19-tech
location:     Mombasa, Kenya 🇰🇪
role:         Senior Fullstack Engineer & DevOps
speciality:   Multi-tenant SaaS · Payment Integrations · African Fintech
available:    Open to senior roles, consulting & SaaS co-founding
languages:    English · Swahili
```

---

## 🏗️ Flagship Projects

---

### 📚 ShuleHQ — School Management System

> *Multi-tenant SaaS digitizing school administration for Kenyan institutions*

ShuleHQ replaces fragmented spreadsheets and manual processes with a unified cloud platform covering admissions, finance, academics, HR, and compliance — all in one place.

**Stack:** `Next.js 16` `React 19` `TypeScript 5` `Tailwind CSS 4` `Framer Motion` `FastAPI (Python 3.12)` `SQLAlchemy 2.0` `PostgreSQL 16.4` `Redis 7.4` `Docker` `GitHub Actions` `M-Pesa Daraja`

| Area | What's Built |
|------|-------------|
| 🏢 **Multi-Tenancy** | Complete data isolation per school; RBAC across SaaS Admin, Director, and Secretary portals |
| 🎓 **Curriculum** | 8-4-4 (marks, exam timetables, report cards), CBC (strand/sub-strand, progress reports), IGCSE (A*–G grading) |
| 💰 **Finance v2** | Per-class fee structures, smart invoice generation, partial payment rules, scholarships, M-Pesa STK Push |
| 👤 **SIS** | Bio-data, guardians, emergency contacts, document uploads, discipline history |
| 📋 **Attendance** | Session lifecycle (DRAFT → SUBMITTED → FINALIZED), bulk mark, corrections, PDF reports |
| 🔐 **Audit Logging** | Full action trail, 90-day auto-retention, searchable log for compliance |
| 📄 **PDF Engine** | Pure-Python invoices, receipts & report cards — zero external dependencies |

**Performance:** `381+ pytest tests` · `2,000 req/min rate limiting per tenant` · `Async task handling` · `DB connection pooling` · `Redis-backed token blacklist`

> ✅ **Live in production** — serving multiple Kenyan schools

---

### 🎯 Tusome — CBC E-Learning Platform

> *Subscription-based learning platform for Kenyan students (Grades 4–12)*

Tusome delivers CBC-aligned structured lessons, interactive quizzes, and a gamified experience designed for accessibility and engagement in the Kenyan education market.

**Stack:** `Turborepo + pnpm workspaces` `Next.js 15` `React 19` `TypeScript` `Tailwind CSS 4` `Shadcn/UI` `FastAPI (Python 3.12)` `SQLAlchemy (async)` `PostgreSQL` `Redis` `M-Pesa Daraja`

**Student Experience:**
- 📖 Grade-filtered lesson browser with Markdown rendering and completion tracking
- ✅ Auto-graded quizzes locked until parent lesson is complete
- 🏆 Gamification — XP, levels, daily streaks (server-tracked), achievement badges, grade leaderboard
- 💳 M-Pesa subscriptions: *Primary KSh 499 · Junior KSh 899 · Senior KSh 1,499/mo*
- 🆓 7-day free trial on signup with full subscription lifecycle management

**Admin Panel (Role-Based):**

| Role | Capabilities |
|------|-------------|
| `super_admin` | Platform stats, revenue breakdown, subscription analytics, admin management |
| `content_editor` | Subject/lesson/quiz CRUD, blog posts, FAQs, announcements |
| `support_agent` | User management, payment tracking, expiring trials, failed payments |

**Anti-Cheat System:** Randomized question/choice order · Minimum submission time (3s/question) · Daily attempt caps · Answer reveal controls · Lesson completion gates

**Coverage:** `65+ tests` across `auth · content · admin · progress · payments`

---

### 🏠 Wooden Houses Kenya — Marketing Site + Admin Dashboard

> *B2B web platform for a sustainable housing company in Kenya*

A dual-application system — a polished public marketing site and a private admin dashboard — served from a single Next.js build with domain-based routing.

**Stack:** `Next.js 16` `React 19` `TypeScript 5` `Tailwind CSS` `Shadcn/UI` `Zustand` `ASP.NET Core 8 (C#)` `Entity Framework Core 8` `PostgreSQL` `Apache` `SMTP` · Testing: `Jest` `MSW` `xUnit`

**Public Site:** Hero · Portfolio/Gallery · Pricing tiers · Lead capture · Newsletter signup · Testimonials · FAQs · Mobile-first responsive

**Admin Dashboard:**
- 📇 **Contact CRM** — Pipeline tracking (new → contacted → qualified → closed), internal notes, follow-up reminders
- 📝 **Quote Builder** — Line-item editor, discount logic (server-side only), A4 PDF output, SMTP email delivery
- 📰 **Newsletter** — Subscriber list, bulk actions, segmentation
- 🔐 **Auth** — JWT with HttpOnly Secure cookies, session management

**Architecture highlight:** Single Next.js build routes `woodenhouseskenya.com` (marketing) and `admin.woodenhouseskenya.com` (dashboard) via middleware-based auth — zero duplication, clean separation.

---

## 🛠️ Tech Stack

### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Shadcn/UI](https://img.shields.io/badge/Shadcn_UI-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433e38?style=flat-square&logo=react&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)

### Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Go](https://img.shields.io/badge/Go_Services-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=python&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-009688?style=flat-square&logo=python&logoColor=white)

### Data & Messaging
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Redpanda](https://img.shields.io/badge/Redpanda-E84040?style=flat-square&logo=apachekafka&logoColor=white)

### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### Payments & Compliance
![M-Pesa](https://img.shields.io/badge/M--Pesa_Daraja-00A651?style=flat-square&logo=safaricom&logoColor=white)
![KRA eTIMS](https://img.shields.io/badge/KRA_eTIMS-1a1a2e?style=flat-square&logoColor=white)
![Pesapal](https://img.shields.io/badge/Pesapal-FF6B00?style=flat-square&logoColor=white)
![Binance](https://img.shields.io/badge/Binance_API-F0B90B?style=flat-square&logo=binance&logoColor=black)

---

## 🧠 Engineering Philosophy

```
> Ship real systems, not demos.
> Own the stack end-to-end — schema to CI/CD pipeline.
> Build for the market you actually serve.
> Test what matters. Document what's complex.
> Iterate fast. Refactor deliberately.
```

I don't over-engineer early. I make pragmatic architectural choices that let systems **grow without collapsing** — proper multi-tenancy from day one, test coverage on business-critical paths, and deployments that don't need babysitting at 2am.

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ManLikeGanga19-tech&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00D9FF&icon_color=00D9FF&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ManLikeGanga19-tech&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00D9FF&text_color=c9d1d9&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com/?user=ManLikeGanga19-tech&theme=tokyonight&hide_border=true&background=0d1117&stroke=00D9FF&ring=00D9FF&fire=FF6B6B&currStreakLabel=00D9FF)

</div>

---

## 🤝 Let's Build Something

I'm open to:

- 🏢 **Senior engineering roles** at product companies building for Africa
- 🤝 **Technical consulting** — architecture reviews, SaaS buildouts, M-Pesa integrations, KRA eTIMS
- 🚀 **Co-founding** — if you have a strong problem and need a technical co-founder

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-ManLikeGanga19--tech-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ManLikeGanga19-tech)

</div>

---

<div align="center">
<sub>Engineered with precision. Deployed with confidence. Made in Kenya 🇰🇪</sub>
</div>
