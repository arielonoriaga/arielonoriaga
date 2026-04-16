# Ariel Onoriaga 🚀
**Full-Stack Developer | Systems Engineer | Building Things That Ship**

I build production systems that move fast and stay lean. From static sites that obliterate WordPress to SaaS platforms with real billing pipelines — I care about ROI, not resume padding.

---

## 🔥 Live Projects

### **Huggian** — My Software Enterprise
**[huggian.com](https://huggian.com)**

Huggian is the company I'm building — a software enterprise focused on automation, SaaS infrastructure, and developer tooling. This is the technical backbone behind every product I ship.

- **Core API** (`api.huggian.com`) — Multi-tenant SaaS engine: product registry, subscription billing (Stripe + MercadoPago), customer management, webhook event delivery. DDD architecture with clean bounded contexts.
- **Admin Dashboard** (`admin.huggian.com`) — Internal SolidJS control panel
- **Landing** (`huggian.com`) — Astro 5 with custom GLSL shaders (aurora, particles, orbs, trails) rendered via WebGL
- **Products hosted:** Mudanzas Margarit, Ez-Stock, and more to come
- **Deploy pipeline** — GitHub Actions matrix builds → binary Docker images → VPS via SSH → Telegram notification on every deploy

**Tech:** Bun, Turbo monorepo, Hono (API), SolidJS (admin), Astro (landing), Drizzle ORM, PostgreSQL, Docker Compose, Nginx (wildcard SSL + subdomain routing), GitHub Actions

---

### **Mudanzas Margarit** — 90% Cost Cut Migration
**[mudanzasmargarit.com](https://mudanzasmargarit.com)** | Astro 5 + Bun + Nginx

Migrated a client from WordPress (600MB RAM, 3.5s load) to a static Astro site (30MB RAM, 0.8s load).

| Metric | Before | After | Gain |
|--------|--------|-------|------|
| Load Time | 3.5s | 0.8s | **4.4x faster** |
| RAM Usage | 600 MB | 30 MB | **20x less** |
| Annual Cost | $2,700 | $300 | **90% savings** |
| Lighthouse | 52/100 | 98/100 | **+46 points** |

**Tech:** Astro, TypeScript, Bun, Nginx, Let's Encrypt, GitHub Actions, Tailwind CSS

---

### **Ez-Stock** — Inventory & Invoicing SaaS (Validation Phase)
**[ez-stock.huggian.com](https://ez-stock.huggian.com)**

Multi-point inventory management with AFIP/ARCA electronic invoicing for small businesses in Argentina (kioscos, carnicerias, comercios). Landing live, validating with user interviews before scaling the full app.

- **Backend** — Rust (Axum) REST API, system-of-record, DDD with bounded contexts, auto-migrating PostgreSQL
- **Frontend** — SolidJS + Vite + Tailwind v4, component testing with Vitest + Playwright E2E
- **AFIP integration** — Go microservice handling Argentine electronic invoicing
- **Landing** — Astro 4 + Tailwind
- **Infrastructure** — Docker Compose (dev + prod configs), Taskfile automation, hot-reload dev environment
- **Practices** — DDD, clean architecture, E2E + unit testing, cargo clippy/fmt enforced in CI

**Tech:** Rust (Axum), Go, SolidJS, Astro, TypeScript, Bun, PostgreSQL, Docker, Vitest, Playwright

---

## 💪 Core Skills

### Full-Stack
- **Frontend:** Astro, SolidJS, React, Vue.js, TypeScript, Tailwind CSS
- **Backend:** Hono, Node.js, NestJS, Express, Bun
- **Databases:** PostgreSQL, Drizzle ORM, MySQL, MongoDB
- **Patterns:** DDD, event-driven, clean architecture, reactive systems (RxJS, Preact Signals)

### DevOps & Infrastructure
- **CI/CD:** GitHub Actions pipelines (multi-service matrix builds, zero-downtime deploys)
- **Containers:** Docker, Docker Compose, optimized images with `bun build --compile` (binary-only final stage)
- **Servers:** Nginx (reverse proxy, wildcard SSL, subdomain routing), systemd
- **Cloud:** VPS (Hostinger), AWS

### Game Development
- **Engine:** Phaser 4 (5+ shipped projects)
- **Graphics:** WebGL/GLSL shaders, canvas optimization, high-frame-rate rendering
- **Animation:** Spine professional tools
- **Systems:** Physics, collision detection, i18n, asset pipelines

### Performance & Optimization
- Lighthouse 95+ as a baseline, not a goal
- Bundle analysis, asset compression, static-first architecture
- Cost reduction engineering (proven 90% cuts through smart architecture)
- FFmpeg video processing, Sharp image optimization

---

## 🛠️ Current Stack

**Languages:** TypeScript (primary), JavaScript, Golang, Python, PHP

**Frontend:** Astro, SolidJS, React, Vue.js, Tailwind CSS

**Backend:** Hono, Bun, Node.js, Drizzle ORM

**DevOps:** GitHub Actions, Docker, Nginx, Linux (Arch)

**Tools:** Bun (package manager), Turbo, Zod, Vitest, Playwright

---

## 📈 Philosophy

> Every manual process is a profit leak. Every second of load time is a user lost.

1. **Ship real things** — not toy projects
2. **Automate early** — CI/CD from commit one
3. **Scale cheap** — architecture beats hardware
4. **Binary over bloat** — compile to a single file, drop the runtime

---

## 💬 Let's Connect

- **Company:** [huggian.com](https://huggian.com)
- **LinkedIn:** [arielonoriaga](https://www.linkedin.com/in/arielonoriaga/)
- **Email:** onoriagaariel@gmail.com

---

<a href="https://app.daily.dev/aonoriaga"><img src="https://api.daily.dev/devcards/v2/dDsB9Ksa0pT0bOa7aaWkO.png?type=default&r=hcg" width="356" alt="Ariel Onoriaga's Dev Card"/></a>
