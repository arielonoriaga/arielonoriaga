<div align="center">

<a href="https://landing.huggian.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=4000&pause=1500&color=58A6FF&center=true&vCenter=true&width=720&height=50&lines=Ariel+Onoriaga" alt="Ariel Onoriaga" />
</a>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3500&pause=1200&color=888888&center=true&vCenter=true&width=720&lines=I+cut+cloud+bills+90%25.;I+ship+regulated+systems+that+pass+audit+first+try.;AFIP+%C2%B7+ARCA+%C2%B7+GLI+%C2%B7+Lighthouse+98%2F100." alt="Tagline" />

<br>

**Argentine fiscal e-invoicing · GLI-certified gaming · Cost-cut migrations · Rust APIs**

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

<table>
  <tr>
    <td align="center" width="240">
      <h3>💸 $2,400/yr</h3>
      <sub>saved per cost-cut migration</sub>
    </td>
    <td align="center" width="240">
      <h3>🎰 GLI-certified</h3>
      <sub>gaming products shipped</sub>
    </td>
    <td align="center" width="240">
      <h3>🧾 AFIP / ARCA</h3>
      <sub>fiscal compliance integrated</sub>
    </td>
  </tr>
</table>

<br>

[![Open to Work](https://img.shields.io/badge/open_to_work-yes-22C55E?style=for-the-badge&labelColor=0D1117)](mailto:onoriagaariel@gmail.com)
[![Email](https://img.shields.io/badge/email_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:onoriagaariel@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/arielonoriaga/)
[![Followers](https://img.shields.io/github/followers/arielonoriaga?style=for-the-badge&logo=github&logoColor=white&color=58A6FF&labelColor=0D1117&label=followers)](https://github.com/arielonoriaga?tab=followers)
[![Profile Views](https://komarev.com/ghpvc/?username=arielonoriaga&color=58A6FF&style=for-the-badge&label=views&labelColor=0D1117&base=1500)](https://github.com/arielonoriaga)

<br>

[ Proof ](#-proof--shipped--measured) **·** [ Client Work ](#-client-work--regulated-gaming) **·** [ How to Work With Me ](#-how-to-work-with-me) **·** [ Open Source ](#%EF%B8%8F-open-source) **·** [ Contact ](#-lets-talk)

</div>

<br>

---

## 💸 Proof — shipped & measured

> The strongest signal I can give you is a paying client whose bill went down.

<br>

<table>
<tr>
<td width="40%" valign="top">

### Mudanzas Margarit

**[mudanzasmargarit.com](https://mudanzasmargarit.com)**

WordPress → static Astro migration.
Same content. Same CMS workflow.
Cheaper, faster, harder to break.

`Astro` `TypeScript` `Bun` `Nginx` `GitHub Actions`

</td>
<td valign="top">

| Metric | Before | After | Gain |
|:-------|:------:|:-----:|-----:|
| Load Time | 3.5s | 0.8s | **4.4× faster** |
| RAM Usage | 600 MB | 30 MB | **20× less** |
| Annual Cost | $2,700 | $300 | **90% saved** |
| Lighthouse | 52/100 | 98/100 | **+46 points** |

</td>
</tr>
</table>

<br>

### 🦀 Ez-Stock — Inventory, POS & AFIP/ARCA invoicing SaaS

**[ez-stock.huggian.com](https://ez-stock.huggian.com)** — Multi-tenant SaaS for Argentine retail.

I built the full stack: backend, POS, storefront, desktop app, and the Go microservice that talks to AFIP for electronic invoicing. Financial-grade precision, hexagonal architecture, audited UI.

<table>
<tr>
<td valign="top" width="50%">

**Backend & data**
- Rust (Axum), 35k+ LOC, 33 PostgreSQL migrations
- DDD + hexagonal architecture
- `rust_decimal` for money — no float drift
- AFIP fiscal e-invoicing via Go microservice

**Frontend & native**
- SolidJS + Vite + Tailwind v4, WCAG AA
- Vitest unit tests + Playwright E2E
- Tauri 2.0 desktop distribution

</td>
<td valign="top" width="50%">

**POS**
- Hierarchical pricing (Global → Sell Point → Provider → Product → Customer)
- Combo recipes, customer ledger
- Cash flow + settlement reports

**Storefront**
- Public catalog, cart, WhatsApp CTAs
- Theme config, order dashboard

</td>
</tr>
</table>

`Rust` `Axum` `SQLx` `Go` `SolidJS` `Tauri` `PostgreSQL` `Docker`

<br>

### 🛒 Ez-Catalog — Argentine product catalog API

**[ez-catalog.huggian.com](https://ez-catalog.huggian.com/)** — Rust API for food & consumer goods data.

Seeded a clean catalog from Open Food Facts Argentina, then built the deduplication, normalization, and tiered API layer that makes it usable.

- **Backend** — Rust + Axum, async Tokio, SQLx compile-time verified queries, Redis 1h cache
- **Text normalization** — NFKD accent stripping, corporate-token removal, unit/container filtering
- **Tiered API keys** — Free / Basic / Pro / Admin with per-tier rate limits
- **Admin ops** — Brand & family merge endpoints for safe deduplication

`Rust` `Axum` `SQLx` `Redis` `PostgreSQL` `Tokio`

<br>

### 🏢 Huggian — my software enterprise

**[landing.huggian.com](https://landing.huggian.com/)** — The platform every product I ship runs on.

Multi-tenant infra for my own portfolio: shared billing, identity, deploy pipeline. Same architecture I'd build for a client — I just happen to be the client too.

<table>
<tr>
<td valign="top" width="50%">

**Core API**
Multi-tenant: product registry, Stripe + MercadoPago billing, customer mgmt, webhooks. DDD + bounded contexts.

**Prospect Bot**
Multi-model AI pipeline (Anthropic, OpenAI, Google, Groq) with live event feed and Telegram alerts.

</td>
<td valign="top" width="50%">

**Deploy pipeline**
Turbo monorepo → tag-triggered GitHub Actions → GHCR binaries → VPS via SSH → Telegram. Playwright E2E with 3-shard parallelization.

**VPS layer**
Nginx with SSL termination, hardening, per-app subdomain routing. Multi-stack isolation, hot reload, full task automation.

</td>
</tr>
</table>

`Bun` `Turbo` `Hono` `SolidJS` `Astro` `Drizzle ORM` `PostgreSQL` `Docker Compose`

<br>

---

## 🎰 Client Work — Regulated Gaming

> **What "GLI-certified" means in practice:** Gaming Laboratories International audits every line of RNG-touching code, every PAR sheet, every scenario. Products fail certification on first submission ~70% of the time. Mine passed.

<br>

<table>
<tr>
<td valign="top" width="50%">

### Game Manager AWS

Multi-operator B2B serverless platform. GLI-compliant, multi-environment, production-hardened.

- Go backend, Vue.js 3 player + admin frontends
- Real-time gaming via WebSocket
- Lottery / draw systems, third-party providers
- GLI-compliant RNG with forced scenarios + audit trails
- Terraform IaC, per-env deploys

`Go` `Vue.js 3` `TypeScript` `AWS` `Terraform` `PostgreSQL` `DynamoDB`

</td>
<td valign="top" width="50%">

### Wizards RNG — math & PAR sheet tooling

Scenario generation + Monte Carlo simulation toolchain for regulated gaming math.

- Python + Rust scenario generator
- Monte Carlo engine, PAR sheet output
- RTP-targeted, volatility-tuned models
- Multiple game types
- Publication-grade reports (Excel, Word)

`Python` `Rust` `PostgreSQL`

</td>
</tr>
</table>

<br>

---

## 🤝 How to work with me

<table>
<tr>
<td valign="top" width="50%">

#### ✅ I take on

- AFIP / ARCA fiscal e-invoicing for Argentine SaaS
- GLI-track gaming (RNG, math, PAR sheets, certification prep)
- Infrastructure cost-cut migrations
- Greenfield Rust APIs with hexagonal architecture
- Multi-tenant SaaS architecture & DDD design

</td>
<td valign="top" width="50%">

#### ❌ I don't take on

- Staff augmentation or agency subcontracting
- Engagements under 3 months
- Ongoing support without defined scope
- Crypto / Web3
- Tech I haven't shipped to production

</td>
</tr>
</table>

<div align="center">

**How to start →** Email a 3-line brief: *what, why, deadline.* I reply within 48h with either a fit/no-fit answer or a 30-min intro call.

<br>

<a href="mailto:onoriagaariel@gmail.com"><img src="https://img.shields.io/badge/📩_Send_3--line_brief-58A6FF?style=for-the-badge&labelColor=0D1117" alt="Send brief" /></a>

</div>

<br>

---

## 🛠️ Open Source

<sub>Tools I use daily, shipped publicly so others can use them too.</sub>

<br>

| Repo | What it does | Stack |
|:-----|:-------------|:------|
| **[claude-irondev](https://github.com/arielonoriaga/claude-irondev)** | Adversarial code-review subagent for Claude Code. Refuses to rubber-stamp. | `Claude Code` |
| **[claude-statusline-bar](https://github.com/arielonoriaga/claude-statusline-bar)** | Information-dense statusline — groups, color ramps, rate-limit countdowns, git status. | `Shell` |
| **[lazyfetch](https://github.com/arielonoriaga/lazyfetch)** · **[lazywifi](https://github.com/arielonoriaga/lazywifi)** · **[.config](https://github.com/arielonoriaga/.config)** | Tiny CLIs + dotfiles for a fast Linux setup. | `Shell` `Lua` |

<div align="center">
<a href="https://github.com/arielonoriaga?tab=repositories"><img src="https://img.shields.io/badge/Browse_all_repos-181717?style=for-the-badge&logo=github&logoColor=white" alt="All repos" /></a>
</div>

<br>

---

<details>
<summary><b>🧠 Full stack — click to expand</b></summary>

<br>

<table>
<tr>
<td valign="top" width="50%">

**Backend**
Rust (Axum, SQLx, Tokio) · Go (Lambda, microservices) · Hono · Bun · NestJS

**Frontend**
Astro · SolidJS · React · Vue.js · TypeScript · Tailwind CSS · WebGL/GLSL

**Databases**
PostgreSQL · Drizzle ORM · SQLx (compile-time verified) · DynamoDB · Redis

**Patterns**
DDD · Hexagonal (ports & adapters) · Event-driven · Bounded contexts

</td>
<td valign="top" width="50%">

**CI/CD & Containers**
GitHub Actions (matrix, path-based detection, E2E sharding) · `bun build --compile` · GHCR · Docker · Docker Compose

**Cloud & Servers**
AWS (Lambda, API Gateway, DynamoDB, Aurora, ECS, S3, CloudFront, EventBridge) · Terraform · Nginx (SSL, rate limiting, hardening) · systemd

**Gaming & AI**
Phaser 4 (5+ shipped) · GLI RNG · PAR sheets · Monte Carlo · RTP · Spine · Anthropic / OpenAI / Google / Groq orchestration

</td>
</tr>
</table>

</details>

<br>

---

<div align="center">

## 💬 Let's talk

<a href="mailto:onoriagaariel@gmail.com"><img src="https://img.shields.io/badge/Email_a_3--line_brief-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/arielonoriaga/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://landing.huggian.com"><img src="https://img.shields.io/badge/huggian.com-FF5D01?style=for-the-badge&logo=safari&logoColor=white" alt="Huggian" /></a>

<br><br>

<sub>📍 Based in Argentina · 🕒 UTC-3 · 🌎 Async-comfortable with US, EU, LATAM teams</sub>

<br><br>

<a href="https://app.daily.dev/aonoriaga"><img src="https://api.daily.dev/devcards/v2/dDsB9Ksa0pT0bOa7aaWkO.png?type=default&r=hcg" width="356" alt="Ariel Onoriaga's Dev Card"/></a>

</div>
