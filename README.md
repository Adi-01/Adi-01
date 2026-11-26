# Hi, I'm Aditya Pushpam

<h3 align="center">
Full-Stack Developer | TypeScript · React · Next.js · Node.js · Express.js · PostgreSQL · Redis
</h3>

<p align="center">
I build and ship full-stack web applications with Next.js, Express.js, PostgreSQL, and Redis — focusing on clean APIs, authentication, caching, and real-time updates.
</p>

<p align="center">
  <a href="https://aditya-portfolio-nine-delta.vercel.app/">🌐 <b>Portfolio</b></a> &nbsp;|&nbsp;
  <a href="https://drive.google.com/file/d/1odJ6RlBWbndJLdeSx0Cf3fFxE3SKLqvP/view">📄 <b>Resume</b></a> &nbsp;|&nbsp;
  <a href="https://linkedin.com/in/aditya-pushpam-22d03m">💼 <b>LinkedIn</b></a> &nbsp;|&nbsp;
  <a href="mailto:pushpamaditya@gmail.com">📫 <b>Email</b></a>
</p>

---

## 🛠️ Skills

<p align="center">
  <!-- Languages & Frameworks -->
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
</p>
<p align="center">
  <!-- Architecture & Systems -->
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zod-3068B7?style=for-the-badge&logo=zod&logoColor=white"/>
</p>
<p align="center">
  <!-- DevOps & Tools -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Playwright-45BA4B?style=for-the-badge&logo=playwright&logoColor=white"/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/Stripe_API-635BFF?style=for-the-badge&logo=stripe&logoColor=white"/>
</p>

---

## 📌 About Me

- **Education:** Bachelor of Computer Applications (Artificial Intelligence), Parul University (Aug 2022 – Apr 2025)
- **Work Experience:**
  - **Independent Contractor (Freelance Full-Stack Developer)** *(Jul 2025 – Jul 2026)*: Replaced legacy Google Sheets/Forms/AppsScript workflows for 15–20 employees with a production Next.js, TypeScript, Express, and PostgreSQL application, reducing manual data-entry errors by 70–80%. Engineered bulker/godown inventory tracking with TanStack Query pre-fetching, cutting gate check-in time by ~60–70% across 50+ bulkers/day. Architected 3-tier RBAC with API-key gating.
  - **Web Development Intern at Arth Consultancy Services** *(Dec 2024 – Mar 2025)*: Built full-stack features with React (Vite), Bootstrap, and Django REST Framework. Implemented secure JWT authentication with automated silent token rotation via Axios response interceptors.

---

## 🚀 Featured Projects

### [Blogology](https://blogology-v2-frontend.vercel.app/) — Full-Stack Editorial & AI Publishing Platform
*Next.js · Express · TypeScript · Prisma · PostgreSQL · Redis · Stripe*
- Architected Next.js Cache Components architecture using Server Components with `"use cache"`, `cacheTag()`, and Server Actions with `updateTag()` for instant read-your-own-writes invalidation; built BlockNote editor with Gemini AI SSE token streaming.
- Sub-millisecond session authentication via Redis cache-aside (`session:<tokenHash>`), atomic sliding-window rate limiting, Stripe billing webhooks, and an on-write weighted feed ranking algorithm recomputed on engagement events.

---

### [FinFlow](https://fin-flow-frontend-zeta.vercel.app) — Real-Time Budgeting & Expense Engine
*Next.js · React · Express · PostgreSQL · Redis · Prisma · TanStack Query*
- Monthly budgeting platform designed around a Starting Allowance baseline model; real-time multi-device sync via Express SSE and Redis Pub/Sub with entity-scoped cache invalidation and `originClientId` deduplication.
- Gemini AI companion synthesizing non-judgmental spender archetypes with multi-model fallback chaining; demand-driven Redis proxy with 60s idle disconnect enabling serverless scale-to-zero container deployment.

---

### [ByteBox](https://bytebox-appwrite.vercel.app) — Cloud Storage Platform
*Next.js · TypeScript · Appwrite · TanStack Query · Tailwind CSS · Zod*
- Cloud storage platform built with Next.js Server Actions and Appwrite (Auth, Database, Storage) featuring a 2GB workspace, file-type validation, and quota enforcement ([GitHub](https://github.com/Adi-01/bytebox-appwrite)).
- Implemented email-based sharing, soft-delete Trash recovery (bulk restore/delete), Appwrite Full-Text Search, and optimistic UI updates with TanStack Query.

---

## 🧪 Currently Exploring

### [Webhook Delivery Engine](https://github.com/Adi-01/webhook-engine) *(Learning Project)*
*Apache Kafka · TypeScript · PostgreSQL · Prisma · SSE*
- Built to learn **Apache Kafka** fundamentals (topics, partitions, producers/consumers, and retry flows) alongside **HMAC-SHA256** payload signing and **SSE** delivery status streaming.

---

## 📫 Connect

<p align="center">
  <a href="https://linkedin.com/in/aditya-pushpam-22d03m">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://aditya-portfolio-nine-delta.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:pushpamaditya@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>
