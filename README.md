# Ariel Onoriaga 🚀
**Full-Stack Developer | Systems Engineer | Building Things That Ship**

I build production systems that move fast and stay lean. From static sites that obliterate WordPress to SaaS platforms with real billing pipelines — I care about ROI, not resume padding.

---

## 🔥 Live Projects

### **Huggian** — SaaS Management Platform
**[huggian.com](https://huggian.com)** | Bun + Turbo monorepo + Hono + SolidJS + Astro + PostgreSQL

A full SaaS backend + landing + admin dashboard running on a single VPS with Docker Compose.

- **Core API** (`api.huggian.com`) — Hono DDD architecture with product registry, subscription billing (Stripe + MercadoPago), customer management, webhook event delivery
- **Admin Dashboard** (`admin.huggian.com`) — SolidJS admin panel
- **Landing** (`huggian.com`) — Astro 5 + custom WebGL GLSL shaders (aurora, particles, orbs, trails)
- **Deploy notifications** — GitHub Actions → Telegram bot on every deploy
- **Infrastructure** — Wildcard SSL, Nginx reverse proxy, binary Docker images via `bun build --compile`

**Tech:** Bun, Turbo, Hono, SolidJS, Astro, Drizzle ORM, PostgreSQL, Docker, GitHub Actions, Nginx

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

### **Ez-Stock** — Inventory SaaS (Validation Phase)
**[ez-stock.huggian.com](https://ez-stock.huggian.com)** | SolidJS + Vite + Tailwind

Inventory management for kioscos, carnicerias, and small businesses in Argentina. Landing page live, validating with user interviews before building the full app.

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

<a href="https://app.daily.dev/aonoriaga"><img src="https://api.daily.dev/devcards/v2/dDsB9Ksa0pT0bOa7aaWkO.png?type=default&r=16y" width="356" alt="Ariel Onoriaga's Dev Card"/></a>
