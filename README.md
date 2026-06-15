<div align="center">

# Anubhav Chauhan

**Full-Stack Engineer** · TypeScript · NestJS · Next.js 14 · MongoDB · Redis · Socket.io

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anubhavchauhan3367/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:anubhavchauhan3011@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Anubhav-Chauhan3367)
![Profile Views](https://komarev.com/ghpvc/?username=Anubhav-Chauhan3367&color=0A66C2&style=flat&label=Profile+Views)

</div>

---

## About me

Full-stack engineer with **2+ years** building production systems end-to-end. Primary engineer on **NexGen** — an enterprise project control & compliance platform for real estate developers — for **17 months**, owning the full stack across **474 REST endpoints** and **3 repositories**.

I specialize in real-time systems, multi-tier access control, event-driven architectures, and scalable backend design. Currently building distributed systems side projects and targeting senior full-stack / backend-leaning roles at product companies.

---

## Tech stack

| Layer | Technologies |
|---|---|
| **Languages** | TypeScript, JavaScript (ES6+), Java |
| **Frontend** | Next.js 14 (App Router), React.js, Tailwind CSS, shadcn/ui, Radix UI, Zustand, TanStack Query, Zod, React Hook Form |
| **Backend** | NestJS, Node.js, Express.js, MongoDB, Redis, Socket.io, Bull queues, PDFKit, ExcelJS, Docxtemplater |
| **Tools & Infra** | Docker, Git, GitHub Actions, AWS S3, SendGrid, NextAuth, CI/CD |

---

## What I've built

### NexGen — Enterprise Project Control & Compliance Platform
*FiftyFive Technologies · Sep 2024 – present*

- Designed a **WebSocket-based concurrent editing lock** using Socket.io + Redis pub/sub adapter — horizontally scalable across backend instances, eliminating silent split-brain conflicts across concurrent sessions
- Architected a **3-tier RBAC system** for external consultants (organisation → project → task/subtask) with time-bounded access, automated email triggers on grant/revoke, and cross-org invitation support — **1,783 lines of core business logic** across 17 async methods
- Eliminated per-document **N+1 joins** from notification queries using `.lean()` + `.select()` projection — cutting **~32% of fields** transferred per request
- Designed the **frontend architecture** across all platform modules — App Router, shadcn/ui, Zustand, TanStack Query with optimistic updates, Zod + React Hook Form — **adopted as the team standard**
- Built end-to-end: **notification engine** (12+ event types, per-user preferences) · **server-side document pipeline** (PDF / Excel / DOCX from live data) · **Google Drive–style file system** with granular RBAC and cross-org sharing

### Prospexs — Business & Event Management Platform
- Reduced bundle size by **40%** via code splitting — load time **4.5s → 2.8s**
- Raised user satisfaction from **3.5 → 4.6 / 5** through UX optimisation; shipped i18n for 2 languages

---

## Currently building

**[distributed-rate-limiter](https://github.com/Anubhav-Chauhan3367/distributed-rate-limiter)** — Redis-based sliding window + token bucket rate limiter; exploring distributed systems primitives, horizontal scalability, and failure modes.

---

## GitHub stats

<p align="center">
  <!-- <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Anubhav-Chauhan3367&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&hide_rank=true&hide=issues" alt="GitHub Stats" /> -->
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anubhav-Chauhan3367&layout=compact&hide_border=true&langs_count=5&hide=blade,php,css,html" alt="Top Languages" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Anubhav-Chauhan3367&bg_color=00000000&color=378ADD&line=185FA5&point=185FA5&area=true&area_color=B5D4F4&hide_border=true&custom_title=Contribution+Activity" alt="Contribution Graph" />
</p>

---

<p align="center">
  <sub>Delhi NCR, India · Open to remote roles</sub>
</p>
