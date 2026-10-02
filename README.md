<div align="center">

# Hey, I'm Khaled Ben Abderrahmen 👋

<a href="https://khaledxab.com"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&pause=1200&color=1F5FAF&center=true&vCenter=true&width=640&lines=Senior+Full-Stack+Engineer;Co-Founder+%26+CTO+%40+Dar+Dev;Next.js+%C2%B7+NestJS+%C2%B7+Python+%C2%B7+Flutter;Open+to+remote+roles+and+freelance+missions" alt="Senior Full-Stack Engineer · Co-Founder & CTO @ Dar Dev" /></a>

📍 Tunis, Tunisia 🇹🇳 · UTC+1 · **Open to remote roles and freelance missions**

[![Website](https://img.shields.io/badge/🌐_khaledxab.com-000000?style=for-the-badge)](https://khaledxab.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-khaledxab-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khaledxab)
[![Medium](https://img.shields.io/badge/Medium-@khaledxab-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@khaledxab)
[![Email](https://img.shields.io/badge/Email-khaled@khaledxab.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khaled@khaledxab.com)

</div>

---

## 👨‍💻 About me

I take SaaS products from an empty repository to live users: architecture, code, deployment and maintenance.
Over 5+ years I've shipped a production ERP, a 15-service compliance platform, real-time marketplaces and
App Store mobile apps.

I work best as the engineer a small team can hand a whole feature or product to. I write typed Next.js and
NestJS code, build Python services and Flutter apps, and run my own Docker, Nginx and CI/CD infrastructure.
Native Arabic, fluent English and French, so RTL and multilingual products are home ground.

- 🏢 **Co-Founder & CTO @ Dar Dev** (2023 – present): architecture, stack, code review and infrastructure for the whole product portfolio
- 🌾 **Freelance**: Ifarming (Flutter AgriTech app, App Store) · Minduos (Python microservices, CI/CD, 99.5%+ uptime)
- 🎓 Software Engineering Program, **Holberton School** Tunis · Anthropic Academy certifications in MCP (2026)

---

## 🏗️ Featured work

> 🔒 Most of my best work lives in **private repositories** (company and client code).
> I'm happy to walk through the architecture and code of any of these in a call: just [email me](mailto:khaled@khaledxab.com).

### 🌟 [Hesabi](https://hesabi.tn) — multi-tenant ERP SaaS · *live*
ERP for Tunisian businesses and accounting firms: invoicing, POS, stock, purchasing, payroll and accounting, plus an
accountant portal managing many client companies. Installable PWA, desktop client, full Arabic/French/English RTL.
`Next.js 16` `TypeScript` `PostgreSQL 16` `Prisma` `Docker` `PWA`

Built around it:
| Service | What it does | Stack |
|---|---|---|
| **AI assistant service** | Standalone tool-calling chat orchestrator with SSE streaming. Owns its own conversation, action-draft and audit-log store, and acts on business data only through Hesabi's authenticated internal API. | TypeScript · Node · PostgreSQL · Docker |
| **AI document import** | Turns invoices, purchase orders and bank statements (PDF/image) into schema-validated JSON, with a validation layer that cross-checks Tunisian tax rules and line-item arithmetic. Includes a review dashboard. | Python · FastAPI · pytest · Docker |
| **Operations agent (Discord)** | Internal multi-agent bot: sign-up alerts, customer lookup, and human-in-the-loop email drafting (the model drafts, a person confirms). Step-driven sessions, threads, auto-expiry. | TypeScript · Cloudflare Workers |
| **Connect** | Company console and the production mail backbone of hesabi.tn: scheduled and bulk sends, delivery tracking via webhooks, live client sync. | Python · FastAPI · Resend |

### More projects
| Project | Description | Stack |
|---|---|---|
| 🛡️ **Veritas** | On-premise anti-money-laundering platform: 15 microservices behind a Kong gateway, with real-time transaction monitoring, sanctions screening, a rules engine and compliance reporting | Python · Kong · PostgreSQL · Docker |
| 🌾 **Falleh** | Live agricultural auction marketplace: real-time bidding over WebSockets, escrow wallet and ledger, KYC onboarding, chat, admin moderation | NestJS · Next.js 16 · React 19 · Redis · Socket.IO |
| 🔍 **NEXTGEN-SIEM** | XDR platform (manager + dashboard) with a cross-platform endpoint agent for Linux and Windows and one-line enrollment | Python · TypeScript |
| 📄 **Smart Import** | Deterministic extraction engine: PDFs (digital and scanned), images, Excel, CSV and XML to clean JSON, with document-type and language detection (FR/AR/EN) | Python · FastAPI · OCR |
| 🧠 **kh.ai** | Terminal tool that routes tasks across several LLM providers and local models, with multi-step pipelines, side-by-side comparison and persistent memory | TypeScript · Bun |
| 🖨️ **Entete Studio** | Visual A4 letterhead and document-template builder with presets, token fields and PDF export, in AR/FR/EN | Next.js · pdfme · Prisma |
| 🏫 **TunisiaEdu** | White-label multi-tenant school platform: timetables, grades, attendance, finance | Next.js · NestJS · PostgreSQL · Redis · MinIO |
| 📱 **Mobile** | Legalease, Medify, Cleanch, Ifarming: Flutter apps with clean architecture and offline support | Flutter · Dart |

### Public
- [**sellbox**](https://github.com/Khaledxab/sellbox): all-in-one commerce platform for online sellers (storefront, orders, stock, delivery)
- Hesabi connectors for [Shopify](https://github.com/Dar-Dev-inc/hesabi-shopify), [WooCommerce](https://github.com/Dar-Dev-inc/hesabi-wordpress) and [PrestaShop](https://github.com/Dar-Dev-inc/hesabi-prestashop) (Dar Dev)

---

## 🚀 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,nodejs,nestjs,python,fastapi,django,flutter,dart&perline=10" alt="Languages and frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,prisma,redis,mongodb,mysql,firebase,docker,nginx,githubactions,linux&perline=10" alt="Data and infrastructure" />
</p>

| | |
|---|---|
| **Front-end** | Next.js 15/16, React 19, TypeScript, Tailwind CSS, TanStack Query, Zustand, PWA, RTL & i18n |
| **Back-end** | NestJS, Node.js, Express, Python, FastAPI, Django REST, REST APIs, WebSockets, microservices |
| **Mobile** | Flutter, Dart, offline-first, push notifications |
| **Data** | PostgreSQL, Prisma, Redis, MongoDB, MySQL, Firebase |
| **DevOps** | Docker, Docker Compose, Nginx, GitHub Actions, Linux, SSL/TLS, MinIO, monitoring |
| **Security** | JWT, RBAC, multi-tenant isolation, mTLS, Kong API gateway, on-premise hardening |
| **AI** | LLM orchestration, tool calling, agents, MCP, document extraction |

<p align="center">🇹🇳 Arabic — Native &nbsp;·&nbsp; 🇬🇧 English — Fluent &nbsp;·&nbsp; 🇫🇷 French — Professional</p>


---

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=Khaledxab&theme=tokyonight&hide_border=true)](https://github.com/khaledxab)

*"Building things that matter, one commit at a time."*

</div>
