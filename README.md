<!-- HEADER -->
<div align="center">

```
███████╗ █████╗ ██████╗ ███████╗███████╗██████╗
██╔════╝██╔══██╗██╔══██╗██╔════╝██╔════╝██╔══██╗
█████╗  ███████║██████╔╝█████╗  █████╗  ██║  ██║
██╔══╝  ██╔══██║██╔══██╗██╔════╝██╔══╝  ██║  ██║
██║     ██║  ██║██║  ██║███████╗███████╗██████╔╝
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚══════╝╚═════╝
```

### **Fareed Tijani** | Full-Stack Software Engineer
#### `Backend · AI Systems · Frontend · Mobile · Product Engineering`

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://fareedtijani.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fareed-tijani-b693492b9/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fareedtijani2810@gmail.com)
[![HireJourney](https://img.shields.io/badge/HireJourney-5795c2?style=for-the-badge&logoColor=white)](https://hirejourney.xyz)

</div>

---

## ⚡ The short version

I build and ship production software across **backend, frontend, mobile, and AI**.

I'm the founder and sole engineer behind **[HireJourney](https://hirejourney.xyz)**, an AI career platform I built from scratch and continue to operate in production. It includes 40+ REST APIs, a React frontend, personalized AI career guidance, a Chrome extension, dual payment infrastructure, and production deployment across multiple services. The platform has processed **1,000+ resumes and generated 1,500+ ATS reports**.

I've also built AI agents, Flutter mobile applications, e-commerce platforms, logistics systems, and backend APIs for real products and clients across fintech, healthcare, e-commerce, and logistics.

I work comfortably in existing codebases and from a blank repository. I learn quickly, ship fast, and use AI throughout my development workflow to research, implement, debug, and iterate faster while still understanding, testing, and taking ownership of what I ship.

---

## 🚀 Flagship: HireJourney *(Live in Production)*

<div align="center">

**[→ hirejourney.xyz ←](https://hirejourney.xyz)**

</div>

> An AI career platform helping job seekers analyze opportunities, improve resumes, practice interviews, track applications, and get personalized career guidance. **Designed, engineered, and shipped solo.**

### What's under the hood

```
✦ 40+ production REST APIs                  ✦ 1,000+ resumes processed
✦ 1,500+ ATS reports generated              ✦ Personalized AI career agent (Aria)
✦ Async LLM workflows + multi-model routing  ✦ React frontend + Chrome Extension
✦ JWT auth + Redis token blacklisting        ✦ 5+ job boards supported
✦ Paystack + Lemon Squeezy payments          ✦ IP-based local/global payment routing
✦ Webhooks + rate limiting                   ✦ Docker · Fly.io · Vercel · Cloudflare
✦ Automated CI/CD                            ✦ PostgreSQL + Redis
```

### Aria — Personalized AI Career Agent

Aria isn't just a chatbot sitting beside the application.

It uses a user's **resume, job-fit analyses, interview history, applications, and ongoing career activity** as persistent context to provide more relevant guidance over time.

New activity and analysis results are incorporated into Aria's context, allowing it to build a better understanding of a user's **skills, gaps, interview performance, applications, and career goals**.

### Stack

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-FF6B35?style=flat-square&logoColor=white)
![Paystack](https://img.shields.io/badge/Paystack-00C3F7?style=flat-square&logoColor=white)
![Lemon Squeezy](https://img.shields.io/badge/Lemon%20Squeezy-7C3AED?style=flat-square&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-7C3AED?style=flat-square&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

## 🛠 Full-Stack Arsenal

```python
stack = {
    "backend": [
        "Python · FastAPI · Django · Flask",
        "Java · Spring Boot",
        "Node.js · REST APIs"
    ],

    "frontend": [
        "React · Next.js · TypeScript",
        "Vite · TailwindCSS · Responsive UI"
    ],

    "mobile": [
        "Flutter · Dart · Riverpod · Dio"
    ],

    "ai": [
        "AI Agents · LLM Orchestration",
        "Multi-Model Routing · Prompt Engineering",
        "Claude · GPT · Gemini · DeepSeek · OpenRouter"
    ],

    "databases": [
        "PostgreSQL · MySQL · MongoDB",
        "Redis · Supabase · Neon"
    ],

    "orm": [
        "SQLAlchemy · Alembic · Drizzle ORM"
    ],

    "payments_integrations": [
        "Paystack · Lemon Squeezy",
        "KYC · Webhooks · API Integrations"
    ],

    "cloud_infrastructure": [
        "Docker · Fly.io · Vercel",
        "Firebase · Cloudflare · CI/CD"
    ],

    "testing_tooling": [
        "Pytest · Jest · JUnit",
        "Postman · Swagger/OpenAPI · Git · pnpm"
    ]
}
```

---

## 📂 Notable Projects

### 📈 Crypto Signal Agent — Adaptive AI Market Analysis

> An AI-driven trading-analysis agent that combines live market data, financial news, technical indicators, funding data, and the outcomes of previous signals to generate, evaluate, and refine subsequent trading analyses.

The system collects market data and news from multiple sources, runs technical and fundamental analysis, and uses Claude through OpenRouter to reason over the combined information.

Historical signal outcomes are fed back into subsequent analyses, allowing the system to incorporate what happened previously rather than treating every signal as an isolated prediction.

Signals are delivered in real time through Telegram.

`Python · FastAPI · Pandas · OpenRouter · Claude · Redis · NeonDB · CoinGecko · Binance API · Docker · Fly.io`

---

### 👟 Shoe Store E-Commerce Platform

> A full-stack e-commerce platform for a footwear retailer with a customer storefront and separate admin dashboard for managing products, inventory, and orders.

Built the customer-facing shopping experience alongside the management workflows, with Cloudinary handling product imagery and Paystack powering online payments.

[`Live Demo →`](https://lamore-shoes.vercel.app/)

`Next.js · TypeScript · PostgreSQL · Drizzle ORM · Cloudinary · Paystack`

---

### 🦻 CommsBridge — AI Assistive Mobile App

> An assistive mobile application designed to help hearing-impaired users follow conversations and identify potential hazards in their environment.

Built the Flutter mobile application alongside backend AI services for speech-to-text transcription, multilingual translation, AI-powered conversation summarization, and environmental sound detection.

The audio-processing pipeline was optimized to reduce processing time by approximately **40%**, with TensorFlow's YAMNet used for sound-event detection such as alarms and sirens.

`Flutter · Dart · Java · Spring Boot · Python · FastAPI · TensorFlow · YAMNet · Gemini · AssemblyAI · Cloudinary · MySQL`

---

### 💄 Fabhands — Client Acquisition Platform

> A client acquisition platform built for a UK-based freelance makeup artist, replacing repetitive pricing and availability conversations across DMs and WhatsApp with a single shareable experience.

Built a link-in-bio style digital brochure with service information, pricing, and appointment booking designed around turning visitors into direct enquiries and bookings.

[`Live Demo →`](https://fabhands-link.vercel.app/)

`React · Vite · TailwindCSS · Vercel`

---

### 📦 Consumer Data Ingestion System

> A backend system designed to ingest, store, and query large consumer datasets with reliable filtering and pagination.

The API supports multi-field filtering and offset-based pagination, with ingestion and retrieval separated so the data pipeline can evolve independently from query logic.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Tijanifareed/aktos-assignment)
[![Postman Docs](https://img.shields.io/badge/Postman_Docs-FF6C37?style=flat-square&logo=postman&logoColor=white)](https://fareed-team-7973.postman.co/workspace/c6250aa7-94a0-49bf-8031-508196beb84e/collection/44846809-153e881b-cb50-4d91-a430-176933ea161e?action=share&source=copy-link&creator=44846809)

`Python · Django · PostgreSQL · Railway · Render · Postman`

---

### 📓 Trading Journal

> A personal trading journal built to track trades and performance over time and answer a simple question: **am I actually improving, or does it just feel that way?**

[`Live Demo →`](https://my-trading-journal-hazel.vercel.app/)

`TypeScript · Drizzle ORM · Supabase`

---

## 💼 Experience

### Semicolon Labs — Software Engineer
**August 2026 – Present**

Working across 3 production products in a shared pnpm monorepo, building responsive Next.js interfaces, translating Figma designs into production-ready components, integrating REST APIs, and contributing through GitHub pull requests and code reviews.

### HireJourney — Founder & Solo Engineer
**October 2025 – Present**

Built and operate the platform end to end across frontend, backend, AI systems, payments, browser extension, and infrastructure.

### Meerge Africa — Backend Developer
**May 2025 – June 2025**

Built and maintained 25+ REST APIs supporting logistics, orders, payments, and KYC workflows, including Paystack integrations, Redis caching, OTP authentication, testing, and CI/CD.

### 3ribe — Mobile Developer
**February 2025 – April 2025**

Worked on a Flutter-based mobile application, improving responsive interfaces and the overall user experience.

### Semicolon Africa — Software Engineering Fellow
**February 2024 – February 2025**

Built backend systems and REST APIs for web and mobile applications while contributing to sprint planning, code reviews, testing, and mentoring.

---

## 📌 About the Repositories

A significant portion of my production work, **including the full HireJourney codebase**, lives in private repositories.

Some client projects are also protected by NDA, including fintech and healthcare applications involving KYC, payments, and mobile development.

Earlier work also includes contributions to internal products that don't have a public commit trail.

**What's public here is only a fraction of what I've built and shipped.**

I'm gradually building more in public through open-source projects, technical write-ups, and case studies.

---

## 🤖 How I Build

I use AI as part of my normal engineering workflow — not as a replacement for understanding the code.

I use it to:

- Research unfamiliar technologies and codebases
- Explore implementation approaches
- Prototype and iterate on features
- Debug and investigate issues
- Review alternative solutions
- Move faster through repetitive engineering work

I still **read the code, test the implementation, debug what breaks, and take responsibility for what ships.**

---

## 📬 Let's Talk

If you're building something ambitious and need an engineer who can **take a problem from idea to production**, I'm open to remote opportunities and relocation.

📧 **fareedtijani2810@gmail.com**

[Portfolio](https://fareedtijani.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/fareed-tijani-b693492b9/) · [HireJourney](https://hirejourney.xyz)

---

<div align="center">

<sub>Build it. Ship it. Learn from it. Build the next thing better.</sub>

</div>
