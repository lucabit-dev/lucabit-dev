<div align="center">

# Luca Longoni

**Full-Stack Engineer · Buenos Aires, Argentina**

*Developing more than just needs.*

</div>

---

I build products that handle **real data in real time** — trading platforms, SaaS workspaces, collaborative tools, AI workflows.
5+ years shipping across fintech, internal tooling, and SaaS.
I own things end-to-end: architecture, infrastructure, frontend, deployment.

---

### What I'm building

**[Prize — SaaS / Competitive Pricing Intelligence]**
• Co-founded Prize, a competitive-pricing intelligence platform for Argentine retailers. Built the full stack from scratch: Next.js 15
+ React 19 frontend (Vercel) and NestJS 10 + Prisma 6 + PostgreSQL backend (Railway), connected via a Next.js rewrite proxy.
• Designed and shipped a custom JWT auth system (HS256, httpOnly cookies with Bearer fallback) including bcrypt hashing,
account lockout, email verification, password reset, two-step email change, and FOUNDER-issued 15-minute impersonation
tokens for support.
• Built a multi-tenant company model with row-level isolation across 15 Prisma models, three roles (OWNER, EXECUTIVE,
ANALYST) enforced server-side via NestJS guards, and a token-based invite flow with 7-day expiry.
• Implemented an async email pipeline on pg-boss (PostgreSQL queues) with exponential-backoff retries, dead-letter table, and
a privacy trade-off storing sha256-truncated recipient hashes. 7 React Email templates delivered via Resend.
• Built a SaaS pricing engine modeling 10 Argentine competitor sources with tiered catalog pricing, annual discounts, and promo
codes. Config stored as a versioned JSON singleton, validated on every write.
• Shipped a 1900-line interactive price matrix UI (band states, configurable thresholds, URL-driven filters, shift+click range
selection, SVG price-history charts) and a 1500-line matching review queue with keyboard shortcuts. Instrumented Sentry on
both services with CI source-map upload, structured pino/JSON logging, and GitHub Actions CI on each repo.

---

**[TAPP-V2 — Trading Analytics Platform](https://github.com/lucabit-dev/TAPP-V2)**
• Built and led TAPP-V2, a production trading analytics platform in Node.js, TypeScript and React 19, used by traders for real
decisions on live markets.
• Designed a custom technical indicator engine (EMA, MACD, VWAP, LOD/HOD) matching TradingView at 99%+ accuracy,
processing 3,000+ candles per calculation across multiple timeframes.
• Integrated real broker APIs over WebSocket: Polygon.io for market data, ChartsWatcher for alert streams, and a P&L proxy for
live position tracking. Sustained sub-200ms latency on 500+ concurrent feeds and 10K+ events/day.
• Designed alert evaluation and asset ranking algorithms surfacing opportunities by momentum, improving signal detection
speed ~40%.
• Owned full deployment pipeline: AWS EC2 + Railway + Vercel, nginx reverse proxy, PM2 process management, GitHub
Actions CI/CD for zero-downtime pushes. 266 commits, all production.
• Built most of the codeb

`Node.js` `React 19` `TypeScript` `WebSockets` `MongoDB` `AWS` `PM2` `nginx`

---

**[Syncboard — Real-Time Multiplayer Whiteboard](https://github.com/lucabit-dev/whiteboard)**
pnpm monorepo with `@syncboard/shared` — typed Socket.IO payloads & API DTOs end-to-end. Public/unlisted/private rooms with JWT access control on both REST and Socket.IO. Debounced autosave to PostgreSQL. Optional Clerk auth with graceful degradation. Vitest integration tests. Docker.

`Socket.IO` `React 18` `Zustand` `Prisma` `PostgreSQL` `Vitest` `Docker`

---

**[Bunzi — Multi-Tenant SaaS Workspace & CRM](https://github.com/lucabit-dev/bunzi)**
• Founded and shipped Bunzi, a multi-tenant SaaS workspace and CRM platform, solo from architecture to production across
two complete rebuilds.
• Final version built on Next.js App Router, TypeScript, PostgreSQL with Prisma, Clerk auth (with graceful degradation), pnpm
and Vercel. Supported up to 3 isolated workspaces per user with full tenant isolation.
• Earlier version shipped on Node.js, React, MongoDB and Railway, demonstrating end-to-end ownership across two complete
codebases.
• Owned the full product lifecycle: system design, UX flows, onboarding, CI/CD via GitHub Actions, and iterative feedback cycles.

`Next.js` `TypeScript` `PostgreSQL` `Prisma` `Clerk` `pnpm` `Vercel` `GitHub Actions`

---

**[TARG — AI-Powered Action Planning](https://github.com/lucabit-dev/targ)** *(in progress)*
Turns a user's problem, prompt, and evidence into a structured action plan. LLM integration, agentic workflows, structured output systems.

`LLM APIs` `Agentic Workflows` `TypeScript`

---

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47a248?style=flat-square&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2d3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232f3e?style=flat-square&logo=amazonaws&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-c21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6e9f18?style=flat-square&logo=vitest&logoColor=white)

---

📍 Buenos Aires &nbsp;·&nbsp; 🌐 [lucalongoni.site](https://lucalongoni.site) &nbsp;·&nbsp; 💼 [linkedin](https://linkedin.com/in/luca-longoni) &nbsp;·&nbsp; 📬 lucalong54@gmail.com
