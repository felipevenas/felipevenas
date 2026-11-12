# Felipe Venas

**Fullstack Developer** · Salvador, Brazil

Fullstack developer moving into AI engineering. I build production backends and ship LLM-powered features on top of them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/felipevenas)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dev.felipevenas@gmail.com)

---

### About

- **2+ years** shipping production software end to end. Delivered **10+ products and sites** — client platforms, institutional sites and my own products.
- Backend-first with **Java 25 + Spring Boot 4** and **Python + FastAPI**: PostgreSQL with Flyway, JWT with rotating refresh tokens, idempotent webhooks, rate limiting and integration tests against real databases with Testcontainers. Frontend with **React, TypeScript and Astro**.
- Shipping **LLM features in production**: rubric-based essay correction, question explanations, study-plan generation and video hook analysis — with model calls isolated in Edge Functions, quotas and cost controls.
- Security and privacy by default: **row-level security**, LGPD-aware export and deletion flows, audit trails and encrypted secrets.

### Building with AI

| Project | What it does | AI in it |
|---|---|---|
| [**Aprendify**](https://github.com/felipevenas/aprendify) · [Live](https://aprendify.cloud) | ENEM prep platform: past-exam question bank, mock exams, TRI estimates, study schedule and Stripe billing. | Essay correction against the five official ENEM competencies, question explanations and study-plan generation with Groq (Llama 3.3 70B, GPT-OSS) inside Deno Edge Functions with quotas and rate limits. |
| **eufelipedesign Omnichannel** *(private)* | CRM and content operations for eufelipedesign, a design studio: prospecting, WhatsApp outreach, client portfolio, finance and Kanban. | Gemini for video hook and retention analysis, plus an AI creative assistant with model and cost guardrails. |
| **Agent-assisted delivery** *(private)* | My day-to-day setup for shipping with agents: specs, architecture review, QA and security passes, and PR/merge automation. | Claude Code and OpenCode with custom skills, subagents, MCP servers and persistent project memory. |

### Products in production

- [**DevRats**](https://github.com/felipevenas/api-dev-rats) ([web](https://github.com/felipevenas/webapp-dev-rats)): private consistency challenges for developers, with automatic GitHub commit verification, groups, rankings, streaks and real-time chat. Java 25, Spring Boot 4, PostgreSQL 17 and React 19. [Live](https://devrats.app)
- **Monteiro Veloso Platform** *(private)*: authenticated legal-operations platform for a law firm — contract intake, client records, documents, roles and audit history. React 19, Supabase/PostgreSQL with RLS and a single Edge Function write gateway. [Live](https://app.monteiroveloso.com)
- **Radar** *(private)*: multi-tenant outbound prospecting — Google Places discovery, lead enrichment and WhatsApp outreach through Evolution API, on an idempotent `pg_cron` pipeline with per-workspace quotas.

### Public repositories

- [**Price Tracker**](https://github.com/felipevenas/api-price-tracker) ([web](https://github.com/felipevenas/webapp-price-tracker)): price monitoring with target prices and history charts. FastAPI with Clean Architecture/DDD, Celery + Redis, Selenium Grid, PostgreSQL and JWT.
- [**Rate Limit Validator**](https://github.com/felipevenas/rate-limit-validator): desktop tool for concurrency testing and rate-limit policy validation, built with Python and PySide6 and shipped as a standalone Windows executable.

### Tech Stack

**AI**

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![OpenCode](https://img.shields.io/badge/OpenCode-0B0B0B?style=for-the-badge&logo=opencode&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Cloud & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white)

### Currently

- On the **Software Development & Innovation** team at **Alcance Contabilidade**, building APIs, integrations and workflow automations for accounting operations.
- Building [**DevRats**](https://devrats.app): consistency challenges for developers with automatic GitHub commit verification, rankings and real-time chat.
- Shipping client products end to end — internal operations platforms, institutional sites and AI features — on React, Supabase and Java/Spring Boot.
- Going deeper into AI engineering: prompt design, guardrails, cost and quota control, and agent-assisted development.
