<div align="center">

<a href="https://arielonoriaga.huggian.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=4000&pause=1500&color=58A6FF&center=true&vCenter=true&width=720&height=50&lines=Ariel+Onoriaga" alt="Ariel Onoriaga" />
</a>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3500&pause=1200&color=888888&center=true&vCenter=true&width=720&lines=Senior+AI+Engineer+%26+Production+Backend+Architect.;Agentic+systems+%C2%B7+MCP+%C2%B7+deterministic+guardrails.;Rust+%C2%B7+TypeScript+%C2%B7+Go+%C2%B7+AWS+%C2%B7+money-movement+systems." alt="Tagline" />

<br>

**Senior AI Engineer & Production Backend Architect**

<sub>7 years · Agentic Systems, MCP & Guardrails · TypeScript, Rust, Go, Python, AWS · Remote (UTC−3, US hours) · Full-time & contract</sub>

<br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

<br>

<table>
  <tr>
    <td align="center" width="240">
      <h3>🤖 AI Systems & MCP</h3>
      <sub>guardrails, multi-agent hubs, CI gates</sub>
    </td>
    <td align="center" width="240">
      <h3>🦀 30-crate Rust SaaS</h3>
      <sub>915 releases · 62k+ sales · AI assistant</sub>
    </td>
    <td align="center" width="240">
      <h3>🛡️ GLI-Certified AWS</h3>
      <sub>real-money multi-tenant platform</sub>
    </td>
  </tr>
</table>

<br>

[![Portfolio](https://img.shields.io/badge/portfolio-arielonoriaga.huggian.com-A8430F?style=for-the-badge&labelColor=0D1117)](https://arielonoriaga.huggian.com)
[![CV](https://img.shields.io/badge/CV_PDF-1466C4?style=for-the-badge&labelColor=0D1117)](https://arielonoriaga.huggian.com/ariel-onoriaga-cv.pdf)
[![LinkedIn](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/arielonoriaga/)
[![Email](https://img.shields.io/badge/email_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:onoriagaariel@gmail.com)
[![Followers](https://img.shields.io/github/followers/arielonoriaga?style=for-the-badge&logo=github&logoColor=white&color=58A6FF&labelColor=0D1117&label=followers)](https://github.com/arielonoriaga?tab=followers)

<br>

[ AI & Agent Open Source ](#-ai--agent-infrastructure-open-source) **·** [ Production Systems ](#-production-systems) **·** [ Regulated Cloud ](#-regulated-cloud-systems-aws) **·** [ Writing ](#-architecture-write-ups) **·** [ Contact ](#-lets-talk)

</div>

<br>

---

## 🤖 AI & Agent Infrastructure (Open Source)

> Most AI prototypes fail in production because the boundary between probabilistic LLM steps and deterministic state is weak. I build the guardrails, MCP memory layers, and CI verification gates that make agentic systems trustworthy.

<br>

| Repo | What it solves | Stack |
|:-----|:---------------|:------|
| **[iron-suite](https://github.com/arielonoriaga/iron-suite)** | Zero-cloud SQLite FTS5 + stdio **MCP memory hub** and multi-agent engineering skills across Claude Code, Codex, and Antigravity. | `Rust` `MCP` `SQLite FTS5` |
| **[claude-harness](https://github.com/arielonoriaga/claude-harness)** | Safety & self-improvement harness for AI coding agents — deterministic Rust tool-call guardrail, shared journal bus, test agent, review queue. | `Rust` `Shell` |
| **[claude-irondev](https://github.com/arielonoriaga/claude-irondev)** | Adversarial multi-lens code-review subagent and orchestrated dev cycle for Claude Code. Refuses to rubber-stamp. | `Claude Code` `Agents` |
| **[entropy-hunter](https://github.com/arielonoriaga/entropy-hunter)** | Deterministic code-health analyzer (complexity, coupling, churn, duplication) built as a CI regression gate to catch AI-generated code drift. | `TypeScript` `Rust` `Bun` |
| **[lazyfetch](https://github.com/arielonoriaga/lazyfetch)** | Terminal HTTP client published on [crates.io](https://crates.io/crates/lazyfetch) as a 7-crate hexagonal Rust workspace with an IO-free core enforced in CI (146 tests). | `Rust` `Tokio` `ratatui` |
| **[claude-statusline-bar](https://github.com/arielonoriaga/claude-statusline-bar)** | Information-dense status line for Claude Code — rate-limit countdowns, color ramps, git state. | `Shell` |

<br>

---

## 🏗️ Production Systems

### Ez-Commerce & Huggian Ecosystem — Multi-Tenant SaaS + AI Assistant

Built and operated solo using AI-augmented engineering with strict architecture, review, and test gates: **[arielonoriaga.huggian.com](https://arielonoriaga.huggian.com)** · **[huggian.com](https://huggian.com)**

<table>
<tr>
<td valign="top" width="50%">

**AI & Orchestration**
- In-app AI assistant inside Ez-Commerce for retail operations
- Multi-model LLM pipelines (Anthropic, OpenAI, Google, Groq) with tool access, cost caps, and human-in-the-loop checkpoints
- Consolidated three live services + a new AI module into a single Rust API & worker with dual-hash zero-reissue API key migration and cutover gates

</td>
<td valign="top" width="50%">

**Backend, Payments & Reliability**
- 30-crate Cargo workspace (split from 543k-line single crate: 5.0×–8.7× faster incremental builds), 44 bounded contexts, 481 migrations, 915 releases
- Payments that survive retries: idempotency keys, guarded state transitions, transactional outbox (`SKIP LOCKED` leased claims), offline POS sync
- Shared TypeScript billing, entitlement, and identity core (Bun, Hono, Drizzle, PostgreSQL; 27 bounded contexts)

</td>
</tr>
</table>

`Rust` `Axum` `Tokio` `SQLx` `TypeScript` `Hono` `Drizzle` `PostgreSQL` `SolidJS` `Docker`

<br>

### Regulated Cloud Systems (AWS)

Core engineer since Dec 2021 on a multi-tenant real-money gaming platform on AWS (Go / TypeScript monorepo; ~3,700 commits, ~38% of core repo).

- Architected and maintain 5 shared TypeScript libraries and a game template adopted across studio game teams (~1,850 commits).
- Co-developed RNG and game-math services with Monte Carlo simulation tooling (Go, Rust, Python); products passed **GLI (Gaming Laboratories International)** certification.
- Own Terraform IaC across Lambda, API Gateway, DynamoDB, Aurora, ECS, CloudFront, SQS/SNS, and IoT Core, plus internal Rust/Go developer tooling.

<br>

---

## ✍️ Architecture Write-Ups

- **[Payments that survive retries: idempotency keys, guarded transitions and an outbox in Rust](https://arielonoriaga.huggian.com/writing/payments-that-survive-retries/)**
- **[Three services, one Rust binary: a phased live migration](https://arielonoriaga.huggian.com/writing/three-services-one-rust-binary/)**

<br>

---

<details>
<summary><b>🧠 Full stack — click to expand</b></summary>

<br>

<table>
<tr>
<td valign="top" width="50%">

**AI & Agentic Systems**
LLM orchestration (Anthropic, OpenAI, Google, Groq) · MCP (Model Context Protocol) · tool-calling guardrails · multi-agent workflows · SQLite FTS5 retrieval · human-in-the-loop · CI quality/eval gates

**Backend & Data**
Rust (Axum, Tokio, SQLx) · TypeScript (Node, Bun, Hono, Drizzle) · Go · Python · PostgreSQL · DynamoDB · Redis · transactional outbox · idempotency

</td>
<td valign="top" width="50%">

**Cloud & Infrastructure**
AWS (Lambda, API Gateway, DynamoDB, Aurora, ECS, CloudFront, SQS/SNS, IoT Core) · Terraform · Docker · GitHub Actions · nginx · systemd

**Frontend & Architecture**
SolidJS · React · Vue · Astro · PWA / offline sync · DDD · Hexagonal architecture · property & mutation testing

</td>
</tr>
</table>

</details>

<br>

---

<div align="center">

## 💬 Let's talk

Open to **full-time remote (US/global)** and **senior contract** roles in **AI Engineering, Agentic Systems, and Production Backends**.

<br>

<a href="mailto:onoriagaariel@gmail.com"><img src="https://img.shields.io/badge/Email-onoriagaariel@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email" /></a>
<a href="https://arielonoriaga.huggian.com"><img src="https://img.shields.io/badge/Portfolio-arielonoriaga.huggian.com-A8430F?style=for-the-badge&logo=safari&logoColor=white&labelColor=0D1117" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/arielonoriaga/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn" /></a>

<br><br>

<sub>📍 Argentina · 🕒 UTC−3 (full US business-hours overlap) · 🌎 Remote full-time & contract</sub>

</div>
