<div align="center">

# Hey, I'm Khaled Ben Abderrahmen 👋

<a href="https://khaledxab.com"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&pause=1200&color=1F5FAF&center=true&vCenter=true&width=640&lines=Senior+Full-Stack+Developer;Co-Founder+%26+CTO+%40+Dar+Dev;Next.js+%C2%B7+NestJS+%C2%B7+Go+%C2%B7+Python+%C2%B7+Flutter;Open+to+remote+roles+and+freelance+missions" alt="Senior Full-Stack Developer · Co-Founder & CTO @ Dar Dev" /></a>

📍 Tunis, Tunisia 🇹🇳 · UTC+1, European working hours · **Open to remote roles and freelance missions**

[![Website](https://img.shields.io/badge/🌐_khaledxab.com-000000?style=for-the-badge)](https://khaledxab.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-khaledxab-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khaledxab)
[![Medium](https://img.shields.io/badge/Medium-@khaledxab-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@khaledxab)
[![Email](https://img.shields.io/badge/Email-khaled@khaledxab.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khaled@khaledxab.com)

</div>

---

## 👨‍💻 About me

I take SaaS products from an empty repository to live users: architecture, code, deployment and maintenance.
In 5+ years I've shipped a live ERP with AI features, a 15-service compliance platform, real-time marketplaces
and App Store mobile apps.

Give me a whole feature or product and I'll own it end to end, from design to production. I build Next.js and
NestJS apps in TypeScript, backend services and command-line tools in Go, Python services and Flutter apps, and I run
production infrastructure end to end: Docker and Kubernetes, Terraform, monitoring and zero-downtime deploys.
Native Arabic, fluent English and French, so building RTL and multilingual products comes naturally.

- 🏢 **Co-Founder & CTO @ Dar Dev** (2023 - present): architecture, stack, code review and infrastructure for all of the company's products
- 🌾 **Freelance**: Ifarming (Flutter AgriTech app, App Store) · Minduos (Python microservices, CI/CD, 99.5%+ uptime)
- 🎓 Software Engineering Program, **Holberton School** Tunis (2020 - 2022)
- 📜 **Anthropic Academy certifications (2026):** AI Fluency: Framework & Foundations · Model Context Protocol · MCP: Advanced Topics · Claude on Google Cloud · Claude with Amazon Bedrock

---

## 🏗️ Featured work

> 🔒 Most of my best work lives in **private repositories** (company and client code).
> I'm happy to walk through the architecture and code of any of these in a call: just [email me](mailto:khaled@khaledxab.com).

### 🌟 [Hesabi](https://hesabi.tn) · multi-tenant ERP SaaS · *live*
ERP for Tunisian businesses and accounting firms: invoicing, POS, stock, purchasing, payroll and accounting, plus an
accountant portal managing many client companies. Installable PWA, desktop client, full Arabic/French/English RTL.
`Next.js 16` `TypeScript` `PostgreSQL 16` `Prisma` `Docker` `PWA`

Built around it:
| Service | What it does | Stack |
|---|---|---|
| **AI assistant** | A chat assistant that looks up and acts on business data through tool calls, with streamed replies and a full audit log. It reaches data only through Hesabi's authenticated internal API, never the main database. | TypeScript · Node · PostgreSQL · Docker |
| **AI document import** | Reads invoices, purchase orders and bank statements (PDF or image) with a vision model and returns validated JSON. A validation layer cross-checks Tunisian tax rules and line totals. Includes a review dashboard. | Python · FastAPI · pytest · Docker |
| **Operations agent (Discord)** | Internal multi-agent bot: sign-up alerts, customer lookup, and human-in-the-loop email drafting (the model drafts, a person confirms). Each conversation runs in its own thread and expires automatically. | TypeScript · Cloudflare Workers, Queues, Workflows, Workers AI |
| **Connect** | The system that sends all of hesabi.tn's email: scheduled and bulk sends, delivery tracking via webhooks, live client sync. | Python · FastAPI · Resend |

### More projects
| Project | Description | Stack |
|---|---|---|
| 🛡️ **Veritas** | On-premise anti-money-laundering platform: 15 microservices behind a Kong gateway, with real-time transaction monitoring, sanctions screening, a rules engine and compliance reporting | Python · Kong · PostgreSQL · Docker |
| 🌾 **Falleh** | Live agricultural auction marketplace: real-time bidding over WebSockets, escrow wallet and ledger, KYC onboarding, chat, admin moderation | NestJS · Next.js 16 · React 19 · Redis · Socket.IO |
| 🔍 **NEXTGEN-SIEM** | Security monitoring platform (XDR): central manager and dashboard, plus an endpoint agent for Linux and Windows that installs and enrolls with a single command | Python · TypeScript |
| 📄 **Smart Import** | Rule-based extraction engine (no LLM): PDFs (digital and scanned), images, Excel, CSV and XML to clean JSON, with document-type and language detection (FR/AR/EN) | Python · FastAPI · OCR |
| 🧠 **kh.ai** | Terminal tool that routes tasks across several LLM providers and local models, with multi-step pipelines, side-by-side comparison and persistent memory | TypeScript · Bun |
| 🖨️ **Entete Studio** | Visual A4 letterhead and document-template builder with presets, token fields and PDF export, in AR/FR/EN | Next.js · pdfme · Prisma |
| 📡 **[sitewatch](https://github.com/Khaledxab/sitewatch)** | Open source website monitor: probes sites and exports uptime, latency and TLS certificate expiry to Prometheus. Single static binary, Helm chart and Grafana dashboard included | Go · Docker · Kubernetes · Prometheus · Grafana |
| 🏫 **TunisiaEdu** | White-label multi-tenant school platform: timetables, grades, attendance, finance | Next.js · NestJS · PostgreSQL · Redis · MinIO |
| 📱 **Mobile** | Legalease, Medify, Cleanch, Ifarming: Flutter apps with clean architecture and offline support | Flutter · Dart |

### Public
- [**sellbox**](https://github.com/Khaledxab/sellbox): all-in-one commerce platform for online sellers (storefront, orders, stock, delivery)
- Hesabi connectors for [Shopify](https://github.com/Dar-Dev-inc/hesabi-shopify), [WooCommerce](https://github.com/Dar-Dev-inc/hesabi-wordpress) and [PrestaShop](https://github.com/Dar-Dev-inc/hesabi-prestashop) (Dar Dev)

---

## 🚀 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,go,nodejs,nestjs,python,fastapi,django,flutter,dart&perline=11" alt="Languages and frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,prisma,redis,kafka,mongodb,mysql,docker,kubernetes,terraform,aws,cloudflare,prometheus,grafana,sentry,nginx,githubactions,linux&perline=10" alt="Data and infrastructure" />
</p>

| | |
|---|---|
| **Front-end** | Next.js 15/16, React 19, TypeScript, Tailwind CSS, TanStack Query, Zustand, PWA, RTL & i18n |
| **Back-end** | Go, NestJS, Node.js, Express, Python, FastAPI, Django REST, REST APIs, WebSockets, microservices |
| **Mobile** | Flutter, Dart, offline-first, push notifications |
| **Data** | PostgreSQL (replication, backups), Prisma, Redis (clustering), Kafka, MongoDB, MySQL, Firebase |
| **DevOps** | Docker, Kubernetes (k3s, EKS), Terraform, Docker Compose, Nginx, load balancing, GitHub Actions, Linux, SSL/TLS, zero-downtime deploys |
| **Cloud / Ops** | AWS (storage, queues), Cloudflare (Workers, Queues, Workflows, Workers AI), MinIO, Prometheus, Grafana, Sentry |
| **Security** | JWT, RBAC, multi-tenant isolation, mTLS, Kong API gateway, XDR endpoint agents, on-premise hardening |
| **AI** | LLM tool calling and orchestration, agents, human-in-the-loop workflows, MCP, vision and OCR document extraction |

<p align="center">🇹🇳 Arabic · Native &nbsp;·&nbsp; 🇬🇧 English · Fluent &nbsp;·&nbsp; 🇫🇷 French · Professional</p>

---

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=Khaledxab&theme=tokyonight&hide_border=true)](https://github.com/khaledxab)

*"Building things that matter, one commit at a time."*

</div>
