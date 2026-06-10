# Hi, I'm Anubhav Chauhan 👋

**Full-Stack Engineer** · TypeScript · NestJS · Next.js 14 · MongoDB · Redis · Socket.io

Based in Delhi NCR, India · Open to remote roles

---

## About me

Full-stack engineer with 2+ years building production systems end-to-end. Primary engineer on **NexGen** — an enterprise project control & compliance platform for real estate developers — for 17 months. I own the full stack: real-time collaborative locking, multi-tier access control, event-driven notifications, and server-side document generation pipelines across **474 REST endpoints** and **3 repositories**.

Currently deepening my distributed systems knowledge through hands-on side projects.

---

## Tech stack

**Languages**
`TypeScript` `JavaScript (ES6+)` `Java`

**Frontend**
`Next.js 14 (App Router)` `React.js` `Tailwind CSS` `shadcn/ui` `Radix UI` `Zustand` `TanStack Query` `Zod` `React Hook Form` `DnD Kit`

**Backend**
`NestJS` `Node.js` `Express.js` `MongoDB` `Redis` `Socket.io` `Bull queues` `REST APIs` `PDFKit` `ExcelJS` `Docxtemplater`

**Tools & Infra**
`Docker` `Git` `GitHub Actions` `AWS S3` `SendGrid` `NextAuth` `CI/CD` `Figma`

---

## What I've built at FiftyFive Technologies

**NexGen — Enterprise Project Control & Compliance Platform**

- Designed a **WebSocket-based concurrent editing lock** using Socket.io + Redis pub/sub — horizontally scalable across backend instances, eliminating split-brain conflicts across concurrent sessions
- Architected a **3-tier RBAC system** for external consultants (organisation → project → task/subtask) with time-bounded access, automated email triggers on grant/revoke, and cross-org invitation support — 1,783 lines of core business logic across 17 async methods
- Refactored a monolithic endpoint into a **3-tier lazy-load architecture** — eliminating all optional column data from page load
- Eliminated per-document **N+1 joins** from notification queries using `.lean()` and `.select()` projection — cutting ~32% of fields transferred per request
- Designed the **frontend architecture** across all platform modules — App Router, shadcn/ui on Radix primitives, Zustand for cross-module state, TanStack Query with optimistic updates, Zod + React Hook Form for end-to-end type safety — adopted as the team standard
- Built end-to-end: **notification engine** (12+ event types, per-user preferences) · **server-side document pipeline** (PDF/Excel/DOCX from live data) · **Google Drive–style file system** with granular RBAC and cross-org sharing

---

## Currently working on

- **Distributed rate-limiter** — Redis-based sliding window + token bucket implementation; deep-dive into distributed systems primitives
- **NeetCode 150** — daily DSA practice (Easy/Medium)
- **System design** — building structured revision notes on CAP theorem, consistent hashing, Kafka, sharding, and the 7-step interview framework

---

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anubhavchauhan3367/)
[![Email](https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white)](mailto:anubhavchauhan3011@gmail.com)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Anubhav-Chauhan3367&show_icons=true&hide_border=true&count_private=true&theme=default" alt="GitHub stats" />
</p>
