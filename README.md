<div align="center">

# Ariel Onoriaga

### I cut cloud bills 90% and ship regulated systems that pass audit on the first try.

**Argentine fiscal e-invoicing (AFIP/ARCA) · GLI-certified gaming · Cost-cut migrations · Rust APIs**

<br>

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-FF5D01?style=flat-square&logo=astro&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

<br>

| 💸 $2,400/yr saved per migration | 🎰 GLI-certified gaming shipped | 🧾 AFIP/ARCA fiscal compliance |
|:---:|:---:|:---:|

<br>

[![Open to Work](https://img.shields.io/badge/open_to_work-yes-22C55E?style=for-the-badge&labelColor=0D1117)](mailto:onoriagaariel@gmail.com)
[![Followers](https://img.shields.io/github/followers/arielonoriaga?style=for-the-badge&logo=github&logoColor=white&color=58A6FF&labelColor=0D1117&label=followers)](https://github.com/arielonoriaga?tab=followers)
[![Profile Views](https://komarev.com/ghpvc/?username=arielonoriaga&color=58A6FF&style=for-the-badge&label=profile+views&base=1500)](https://github.com/arielonoriaga)

[**Proof**](#proof--shipped--measured) · [**Client Work**](#client-work--regulated-gaming) · [**Engagement**](#how-to-work-with-me) · [**Connect**](#lets-talk)

</div>

---

## Proof — shipped & measured

### Mudanzas Margarit — 90% cloud cost reduction
**[mudanzasmargarit.com](https://mudanzasmargarit.com)** · WordPress → static Astro migration

I migrated this client off a $2,700/yr WordPress stack onto a $300/yr static Astro + Nginx setup. Same content. Same CMS workflow. Faster, cheaper, harder to break.

| Metric | Before | After | Gain |
|:-------|:------:|:-----:|-----:|
| Load Time | 3.5s | 0.8s | **4.4× faster** |
| RAM Usage | 600 MB | 30 MB | **20× less** |
| Annual Cost | $2,700 | $300 | **90% saved** |
| Lighthouse | 52/100 | 98/100 | **+46 points** |

`Astro` `TypeScript` `Bun` `Nginx` `Let's Encrypt` `GitHub Actions`

---

### Ez-Stock — Inventory, POS & AFIP/ARCA invoicing SaaS
**[ez-stock.huggian.com](https://ez-stock.huggian.com)** · Multi-tenant SaaS for Argentine retail

I built the full stack — backend, POS, storefront, desktop app, and the Go microservice that talks to AFIP for electronic invoicing. Financial-grade precision, hexagonal architecture, audited UI.

- **Backend** — Rust (Axum), 35k+ LOC, 33 PostgreSQL migrations, DDD + hexagonal. `rust_decimal` for money, no float drift.
- **POS** — Hierarchical pricing (Global → Sell Point → Provider → Product → Customer), combo recipes, customer ledger, cash flow & settlement reports.
- **Storefront** — Public catalog, cart, WhatsApp CTAs, theme config, order dashboard.
- **Desktop** — Tauri 2.0 native distribution.
- **AFIP microservice** — Go service handling Argentine fiscal e-invoicing end-to-end.
- **Frontend** — SolidJS + Vite + Tailwind v4, WCAG AA audited, Vitest + Playwright.

`Rust` `Axum` `SQLx` `Go` `SolidJS` `Tauri` `PostgreSQL` `Docker`

---

### Ez-Catalog — Argentine product catalog API
**[ez-catalog.huggian.com](https://ez-catalog.huggian.com/)** · Rust API for food & consumer goods data

I seeded a clean product catalog from Open Food Facts Argentina, then built the deduplication, normalization, and tiered API layer that makes it actually usable.

- **Backend** — Rust + Axum, async Tokio, SQLx compile-time verified queries, Redis 1h cache.
- **Text normalization** — NFKD accent stripping, corporate-token removal, unit/container filtering, variant preservation.
- **Tiered API keys** — Free / Basic / Pro / Admin with per-tier rate limits.
- **Admin ops** — Brand & family merge endpoints for safe deduplication.

`Rust` `Axum` `SQLx` `Redis` `PostgreSQL` `Tokio`

---

### Huggian — my software enterprise
**[landing.huggian.com](https://landing.huggian.com/)** · The platform every product I ship runs on top of

I'm building the multi-tenant infra for my own portfolio: shared billing, identity, deploy pipeline. Same architecture I'd build for a client — I just happen to be the client too.

- **Core API** — Multi-tenant: product registry, Stripe + MercadoPago billing, customer mgmt, webhooks. DDD + bounded contexts.
- **Prospect Bot** — Multi-model AI pipeline (Anthropic, OpenAI, Google, Groq) with live event feed and Telegram alerts.
- **Landing** — Astro 5 with custom GLSL shaders (aurora, particles, orbs, trails).
- **Deploy pipeline** — Turbo monorepo → tag-triggered GitHub Actions → GHCR binaries → VPS via SSH → Telegram. Playwright E2E with 3-shard parallelization.
- **VPS layer** — Nginx with SSL termination, hardening, per-app subdomain routing. Multi-stack isolation, hot reload, full task automation.

`Bun` `Turbo` `Hono` `SolidJS` `Astro` `Drizzle ORM` `PostgreSQL` `Docker Compose` `GitHub Actions`

---

## Client Work — Regulated Gaming

### Wizards Gaming Platform — multi-operator B2B
**Game Manager AWS** — GLI-compliant, multi-environment, production-hardened serverless platform for operators.

- Go backend services, Vue.js 3 player + admin frontends
- Real-time gaming via WebSocket, lottery / draw systems, third-party provider integrations
- GLI-compliant RNG with forced scenarios + audit trails (hard requirement: regulators reject products without it)
- Terraform IaC, per-environment deploys via GitHub Actions

`Go` `Vue.js 3` `TypeScript` `AWS` `Terraform` `PostgreSQL` `DynamoDB`

### Wizards RNG — math & PAR sheet tooling
Scenario generation + Monte Carlo simulation toolchain for regulated gaming math.

- Python + Rust scenario generator, Monte Carlo engine, PAR sheet output
- RTP-targeted, volatility-tuned models across multiple game types
- GLI-compliant outputs with publication-grade reports (charts, Excel, Word)

`Python` `Rust` `PostgreSQL`

> **What "GLI-certified" means in practice:** Gaming Laboratories International audits every line of RNG-touching code, every PAR sheet, every scenario. Products fail certification on first submission ~70% of the time. Mine passed.

---

## How to work with me

**I take on:**
- AFIP / ARCA fiscal e-invoicing integrations for Argentine SaaS
- GLI-track gaming work (RNG, math, PAR sheets, certification prep)
- Infrastructure cost-cut migrations (WordPress → static, over-provisioned cloud → right-sized VPS)
- Greenfield Rust APIs with hexagonal architecture
- Multi-tenant SaaS architecture & DDD bounded-context design

**I don't take on:**
- Staff augmentation or agency subcontracting
- Engagements under 3 months
- Ongoing support without a defined scope
- Crypto / Web3

**How to start:** email a 3-line brief — what, why, deadline. I reply within 48h with either a fit/no-fit answer or a 30-min intro call.

---

## Open Source — developer tools

I ship the tools I use daily. Public so others can use them too.

| Repo | What it does | Stack |
|:-----|:-------------|:------|
| **[claude-irondev](https://github.com/arielonoriaga/claude-irondev)** | Adversarial code-review subagent for Claude Code. Refuses to rubber-stamp. | `Claude Code` |
| **[claude-statusline-bar](https://github.com/arielonoriaga/claude-statusline-bar)** | Information-dense statusline — groups, color ramps, rate-limit countdowns, git status. | `Shell` |
| **[lazyfetch](https://github.com/arielonoriaga/lazyfetch)** · **[lazywifi](https://github.com/arielonoriaga/lazywifi)** · **[.config](https://github.com/arielonoriaga/.config)** | Tiny CLIs + dotfiles for a fast Linux setup. | `Shell` `Lua` |

<div align="center">
<a href="https://github.com/arielonoriaga?tab=repositories"><img src="https://img.shields.io/badge/See_all_repos-58A6FF?style=for-the-badge&logo=github&logoColor=white" alt="All repos" /></a>
</div>

---

<details>
<summary><b>Full stack details</b></summary>

<br>

**Backend:** Rust (Axum, SQLx, Tokio), Go (Lambda, microservices), Hono, Bun, NestJS
**Frontend:** Astro, SolidJS, React, Vue.js, TypeScript, Tailwind CSS, WebGL/GLSL
**Databases:** PostgreSQL, Drizzle ORM, SQLx (compile-time verified), DynamoDB, Redis
**Patterns:** DDD, hexagonal (ports & adapters), event-driven, bounded contexts
**CI/CD:** GitHub Actions (matrix builds, path-based change detection, E2E sharding, zero-downtime), `bun build --compile` binary images, GHCR
**Cloud / Servers:** AWS (Lambda, API Gateway, DynamoDB, Aurora, ECS, S3, CloudFront, EventBridge), Terraform, VPS, Nginx (SSL, rate limiting, hardening), systemd
**Gaming:** Phaser 4 (5+ shipped projects), GLI-compliant RNG, PAR sheets, Monte Carlo, RTP targeting, Spine
**AI:** Anthropic, OpenAI, Google, Groq — multi-model orchestration, SSE event buses, prompt engineering

</details>

---

## Let's talk

<div align="center">

<a href="mailto:onoriagaariel@gmail.com"><img src="https://img.shields.io/badge/Email_a_3--line_brief-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/arielonoriaga/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://landing.huggian.com"><img src="https://img.shields.io/badge/huggian.com-FF5D01?style=for-the-badge&logo=safari&logoColor=white" alt="Huggian" /></a>

<br><br>

<sub>Based in Argentina · Working in UTC-3 · Comfortable async with US, EU, LATAM teams</sub>

<br><br>

<a href="https://app.daily.dev/aonoriaga"><img src="https://api.daily.dev/devcards/v2/dDsB9Ksa0pT0bOa7aaWkO.png?type=default&r=hcg" width="356" alt="Ariel Onoriaga's Dev Card"/></a>

</div>
