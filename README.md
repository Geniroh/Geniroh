<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Senior+Full-Stack+%2F+Backend+Engineer;NestJS+%E2%80%A2+Next.js+%E2%80%A2+PostgreSQL+%E2%80%A2+GCP;I+ship+products%2C+not+just+code." alt="Typing intro" />

# Hi, I'm Chibuzor Irobuisi 👋

**Senior Full-Stack Engineer** with 5+ years building production SaaS — multi-tenant architectures, identity systems, event-driven workflows, and real-time features. Google-certified **Professional Cloud Architect** & **Professional Cloud Developer**.

[![Portfolio](https://img.shields.io/badge/Portfolio-irochibuzor.vercel.app-2F81F7?style=for-the-badge&logo=vercel&logoColor=white)](https://irochibuzor.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chibuzor-irobuisi-8984a3334/)
[![Email](https://img.shields.io/badge/Email-irochibuzor%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:irochibuzor@gmail.com)

</div>

---

## 🚀 What I'm Building

| Product | What it is | Status |
|---|---|---|
| **[Zorpill](https://zorpill.com)** 💊 | Pharmacy management SaaS — smart inventory with expiry tracking, e-prescriptions, patient refill reminders, procurement & analytics. Built end-to-end by me (I'm also a licensed pharmacist — I built the tool I wished my industry had). | 🟢 Live |
| **[Vecta Studio](https://avs-landing-page-937508501188.us-central1.run.app/)** 🎬 | Unified AI creative studio — scripts, voiceovers, image & video generation, and smart aspect-ratio export in one workflow. Orchestrates multiple generative AI APIs on GCP Cloud Run. | 🟡 Beta — 2,000+ videos created |

> 🔒 Most of my commercial work lives in private company repositories. The case studies below describe what I've built — and I'm always happy to do a live code walkthrough.

---

## 🏗️ Selected Work — Case Studies

<details>
<summary><b>🔐 Unified SSO & Multi-Database Account Migration</b> — one identity system for a multi-product ecosystem</summary>
<br>

**The problem:** A product suite (Parentyn) had grown into multiple products, each with its own user database. Users had fragmented identities, and every new product meant another signup flow.

**What I built:**
- A centralized authentication service (SSO) acting as the single identity provider for all products
- A migration pipeline that consolidated user accounts from multiple legacy databases into the unified system — deduplicating identities and preserving credentials with **zero data loss**
- Token-based session flow (JWT) so every product delegates auth to one service

**What it taught me:** identity is a data-modeling problem before it's a security problem. The migration design — matching, merging, and verifying accounts across schemas — was 80% of the work.

`NestJS` `PostgreSQL` `JWT / OAuth patterns` `Data migration`
</details>

<details>
<summary><b>🏦 Fault-Tolerant Loan Request Workflow</b> — retries, TTLs, and event-driven bank coordination</summary>
<br>

**The problem:** Loan requests on an HR platform failed silently when the partner bank's side had issues — requiring manual follow-up and eroding user trust.

**What I built:**
- A request lifecycle where every loan request stays active for **24 hours** with up to **4 automated processing attempts**
- On each failed attempt, an event is published that notifies the partner bank with the error context, giving them a window to fix the issue **before the next retry**
- Requests expire cleanly after the TTL, so nothing lingers in an unknown state

**The result:** no more silent failures, no more manual reconciliation — the system coordinates its own recovery.

`NestJS` `BullMQ` `Redis` `Event-driven architecture` `Webhooks`
</details>

<details>
<summary><b>🏫 Multi-Tenant School Management Platform</b> — killing bottlenecks with caching & queues</summary>
<br>

**The problem:** A multi-tenant school management system was hitting performance walls as tenant count grew — slow reads, blocking heavy operations.

**What I built (as backend lead):**
- Redis caching layer for hot read paths
- BullMQ queue processing to move heavy operations off the request cycle and improve throughput
- Structured audit logging across tenant actions for compliance and traceability

`NestJS` `PostgreSQL` `Redis` `BullMQ` `Multi-tenancy`
</details>

<details>
<summary><b>💼 Full HR Suite</b> — payroll, invoicing, expenses & dual portals, architected from scratch</summary>
<br>

Owned system design end-to-end: backend architecture, API design, database modeling, and both the **admin** and **employee** frontend portals. Modules include payroll, employee management, invoicing, expense workflows, and department structuring.

`NestJS` `Next.js` `PostgreSQL` `REST APIs`
</details>

---

## 🛠️ Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

## ☁️ Certifications

- 🏅 **Google Professional Cloud Architect**
- 🏅 **Google Professional Cloud Developer**
- 🏅 Google Associate Cloud Engineer
- 🏅 Google Associate Workspace Administrator

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Geniroh&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Geniroh&layout=compact&theme=github_dark&hide_border=true" alt="Top languages" height="165" />

</div>

---

<div align="center">

💬 **Open to interesting problems** — especially SaaS architecture, identity/auth, and event-driven systems.

*The best way to reach me is [email](mailto:irochibuzor@gmail.com) or [LinkedIn](https://www.linkedin.com/in/chibuzor-irobuisi-8984a3334/).*

</div>
