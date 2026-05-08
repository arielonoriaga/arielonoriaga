<div align="center">

# Ariel Onoriaga

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=3500&pause=1200&color=58A6FF&center=true&vCenter=true&width=620&lines=From+schema+migrations+to+GLSL+shaders.;GLI-certified+%C2%B7+AFIP-compliant+%C2%B7+Lighthouse+98.;90%25+infra+cost+cut.+Zero+feature+compromises.;Rust+APIs.+Go+microservices.+WebGL+shaders." alt="Typing SVG" />

**Complete systems — schema to CDN, compliance to deployment.**
Multi-tenant SaaS · GLI-certified gaming · Fiscal e-invoicing · Performance APIs

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

| 💸 90% infra cost reduction | ⚡ Lighthouse 98/100 | 🎰 GLI-certified gaming | 🦀 35k+ LOC Rust |
|:---:|:---:|:---:|:---:|

<br>

[**Live Projects**](#-live-projects) · [**Client Work**](#-client-work--wizards-gaming-platform) · [**Open Source**](#%EF%B8%8F-open-source) · [**Skills**](#-core-skills) · [**Connect**](#-lets-connect)

<br>

[![Followers](https://img.shields.io/github/followers/arielonoriaga?style=for-the-badge&logo=github&logoColor=white&color=58A6FF&labelColor=0D1117&label=followers)](https://github.com/arielonoriaga?tab=followers)
[![Profile Views](https://komarev.com/ghpvc/?username=arielonoriaga&color=58A6FF&style=for-the-badge&label=profile+views&base=1500)](https://github.com/arielonoriaga)
[![Open to Work](https://img.shields.io/badge/open_to_work-yes-22C55E?style=for-the-badge&labelColor=0D1117)](mailto:onoriagaariel@gmail.com)

</div>

---

## 🚧 Currently Building

**Huggian SaaS portfolio** — multi-tenant infra, AI prospect bot, billing engine. Shipping product on top of my own platform, not a hosted starter kit.

---

## 🔥 Live Projects

### Huggian — My Software Enterprise
**[landing.huggian.com](https://landing.huggian.com/)**

The company behind every product I ship. Multi-tenant SaaS infrastructure powering a growing portfolio of B2B tools.

- **Core API** (`api.huggian.com`) — Multi-tenant engine: product registry, subscription billing (Stripe + MercadoPago), customer management, webhook event delivery. DDD + bounded contexts.
- **Prospect Bot** — Multi-model AI pipeline (Anthropic, OpenAI, Google, Groq) with live event feed, source stats, and Telegram notifications.
- **Landing** (`landing.huggian.com`) — Astro 5 with custom GLSL shaders (aurora, particles, orbs, trails) via WebGL.
- **Deploy pipeline** — Turbo monorepo → tag-triggered GitHub Actions → GHCR binary images → VPS via SSH → Telegram notification. Playwright E2E with 3-shard parallelization + path-based change detection.

`Bun` `Turbo` `Hono` `SolidJS` `Astro` `Drizzle ORM` `PostgreSQL` `Docker Compose` `GitHub Actions` `Anthropic SDK`

---

### Mudanzas Margarit — 90% Cost Cut Migration
**[mudanzasmargarit.com](https://mudanzasmargarit.com)**

Migrated a client from WordPress (600MB RAM, 3.5s load) to a static Astro site. Same content, a fraction of the cost.

| Metric | Before | After | Gain |
|:-------|:------:|:-----:|-----:|
| Load Time | 3.5s | 0.8s | **4.4× faster** |
| RAM Usage | 600 MB | 30 MB | **20× less** |
| Annual Cost | $2,700 | $300 | **90% savings** |
| Lighthouse | 52/100 | 98/100 | **+46 points** |

`Astro` `TypeScript` `Bun` `Nginx` `Let's Encrypt` `GitHub Actions` `Tailwind CSS`

---

### Ez-Stock — Inventory, POS & Invoicing SaaS
**[ez-stock.huggian.com](https://ez-stock.huggian.com)**

Multi-sell-point stock management with AFIP/ARCA electronic invoicing for Argentine retail businesses. Full POS, storefront, and reporting suite.

- **Backend** — Rust (Axum) REST API, 35k+ LOC, 33 PostgreSQL migrations, DDD + hexagonal architecture. Financial-grade precision via `rust_decimal`.
- **Frontend** — SolidJS + Vite + Tailwind v4, WCAG AA audited, Vitest unit tests + Playwright E2E.
- **Storefront** — Public product listing, cart, WhatsApp CTAs, order management dashboard, store theme config.
- **POS** — Hierarchical pricing (Global → Sell Point → Provider → Product → Customer), combo recipes, customer ledger, cash flow reporting, settlement generation.
- **Desktop** — Tauri 2.0 (Rust bridge) for native distribution.
- **AFIP** — Go microservice handling Argentine electronic invoicing.

`Rust` `Axum` `SQLx` `Go` `SolidJS` `Tauri` `PostgreSQL` `Docker` `Vitest` `Playwright`

---

### Ez-Catalog — Argentine Product Catalog API
**[ez-catalog.huggian.com](https://ez-catalog.huggian.com/)**

Product catalog REST API for Argentine food/consumer goods — seeded from Open Food Facts Argentina with brand deduplication, family resolution, and text normalization.

- **Backend** — Rust (Axum), async Tokio, SQLx compile-time query verification, Redis caching (1h TTL).
- **Text normalization** — Accent stripping (NFKD), corporate token removal, unit/container filtering, variant preservation.
- **Tiered API keys** — Free, Basic, Pro, Admin with per-tier rate limiting.
- **Admin ops** — Brand/family merge endpoints for bulk deduplication without breaking referential integrity.

`Rust` `Axum` `SQLx` `Redis` `PostgreSQL` `Tokio` `Serde` `Tracing`

---

## 🏗️ Production Infrastructure

### VPS Orchestration Layer

The operational backbone running every hosted product. Versioned, CI-validated, zero-downtime.

- Nginx reverse proxy with SSL termination, security hardening, and per-app subdomain routing
- Multi-stack isolation — independent deploys per service, no coupling
- Tag-triggered CI/CD with config validation, hot reload, and Telegram notifications
- Full task automation: stack lifecycle, dev hot-reload, DB ops, secrets, health checks

`Nginx` `Docker Compose` `GitHub Actions` `Taskfile` `Let's Encrypt` `PostgreSQL`

---

## 🎰 Client Work — Wizards Gaming Platform

### Game Manager AWS — Serverless Gaming Platform

Multi-operator B2B gaming platform. GLI-compliant, multi-environment, production-hardened.

- Backend services in Go, player-facing and admin frontends in Vue.js 3
- Real-time gaming via WebSocket, lottery/draw systems, third-party provider integrations
- GLI-compliant RNG with forced scenario support and audit trails
- Infrastructure as Code (Terraform), automated per-environment deploys via GitHub Actions

`Go` `Vue.js 3` `TypeScript` `AWS` `Terraform` `GitHub Actions` `Docker` `PostgreSQL` `DynamoDB`

---

### Wizards RNG — Gaming Math & RNG Tooling

Scenario generation and mathematical validation toolchain for regulated gaming products.

- Python + Rust: scenario generator, Monte Carlo simulation engine, PAR sheet output
- Multiple game types with precise RTP targeting and volatility-tuned math models
- GLI-compliant outputs with professional reporting (charts, Excel, Word)

`Python` `Rust` `PostgreSQL`

---

## 🛠️ Open Source

Tools I use daily, shipped publicly. The `lazy-*` line is minimal CLIs that replace bloated alternatives.

| Repo | What it does | Stack |
|:-----|:-------------|:------|
| **[lazyfetch](https://github.com/arielonoriaga/lazyfetch)** | Tiny, fast neofetch alternative. System info without the bloat. | `Shell` |
| **[lazywifi](https://github.com/arielonoriaga/lazywifi)** | Wi-Fi management CLI — connect, scan, manage networks fast. | `Shell` |
| **[claude-irondev](https://github.com/arielonoriaga/claude-irondev)** | Adversarial code-review subagent for Claude Code. Refuses to rubber-stamp. | `Markdown` `Claude Code` |
| **[claude-statusline-bar](https://github.com/arielonoriaga/claude-statusline-bar)** | Information-dense statusline for Claude Code — groups, color ramps, rate-limit countdowns, git status. | `Shell` |
| **[.config](https://github.com/arielonoriaga/.config)** | Full dotfiles: Neovim, Hyprland, Kitty, Zsh, Tmux. Reproducible Linux setup. | `Lua` `Shell` |

<div align="center">

<a href="https://github.com/arielonoriaga?tab=repositories"><img src="https://img.shields.io/badge/See_all_repos-58A6FF?style=for-the-badge&logo=github&logoColor=white" alt="All repos" /></a>

</div>

---

## 💪 Core Skills

<details>
<summary><b>Expand the full stack</b></summary>

<br>

**Full-Stack**
- Frontend: Astro, SolidJS, React, Vue.js, TypeScript, Tailwind CSS, WebGL/GLSL shaders
- Backend: Rust (Axum, SQLx, Tokio), Go (Lambda, microservices), Hono, Bun, NestJS
- Databases: PostgreSQL, Drizzle ORM, SQLx (compile-time verified), DynamoDB, Redis, MySQL
- Patterns: DDD, hexagonal (ports & adapters), event-driven, bounded contexts, reactive systems

**DevOps & Infrastructure**
- CI/CD: GitHub Actions (matrix builds, path-based change detection, E2E sharding, zero-downtime)
- Containers: Docker, Docker Compose, multi-stage builds, `bun build --compile` binary images, GHCR
- Cloud: AWS (Lambda, API Gateway, DynamoDB, Aurora, ECS, S3, CloudFront, EventBridge), Terraform, VPS
- Servers: Nginx (reverse proxy, SSL termination, rate limiting, security hardening), systemd

**Game Development**
- Engine: Phaser 4 (5+ shipped projects)
- Graphics: WebGL/GLSL shaders, canvas optimization, high-frame-rate rendering
- RNG/Math: GLI-compliant RNG, PAR sheet generation, Monte Carlo simulation, RTP targeting
- Animation: Spine professional tools

**AI & LLM Integration**
- Providers: Anthropic (Claude), OpenAI, Google Gemini, Groq — multi-model orchestration pipelines
- Patterns: SSE event buses, real-time monitoring, prompt engineering, webhook delivery

**Performance & Optimization**
- Lighthouse 95+ as a baseline, not a goal
- Cost reduction engineering (proven 90% infra cuts via smart architecture)
- Bundle analysis, static-first, ARM64 optimization
- FFmpeg video processing, Sharp image optimization

</details>

---

## 📈 Philosophy

> Every manual process is a profit leak. Every second of load time is a user lost. Every dollar of cloud spend needs a justification.

- **Ship real things.** Toy projects don't pay rent — production systems do.
- **Automate from commit one.** If you'll run it twice, script it.
- **Architecture beats hardware.** Proven: $2,700/yr → $300/yr without losing a feature.
- **Binary over bloat.** Compile to a single file. Drop the runtime. Drop the surprise.
- **Compliance by design.** GLI, AFIP, WCAG AA — built in, not bolted on.
- **Root cause or nothing.** Five leaf patches < one source-of-truth fix.

---

## 💬 Let's Connect

<div align="center">

<a href="https://landing.huggian.com"><img src="https://img.shields.io/badge/huggian.com-FF5D01?style=for-the-badge&logo=safari&logoColor=white" alt="Huggian" /></a>
<a href="https://www.linkedin.com/in/arielonoriaga/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:onoriagaariel@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br><br>

<a href="https://app.daily.dev/aonoriaga"><img src="https://api.daily.dev/devcards/v2/dDsB9Ksa0pT0bOa7aaWkO.png?type=default&r=hcg" width="356" alt="Ariel Onoriaga's Dev Card"/></a>

</div>
