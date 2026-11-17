# Matheus Maia

**Senior Full-Stack, Mobile & Applied AI Engineer**  
Belém, Brazil · Remote Worldwide · [LinkedIn](https://www.linkedin.com/in/matheusmaiadev) · [7matheus.maia@gmail.com](mailto:7matheus.maia@gmail.com)

---

Software Engineer (Computer Engineering, UFPA · Postgrad in Software Engineering, PUC Minas) focused on **production AI systems**, **offline-first mobile applications**, and **distributed backend architectures**.

### Engineering Focus

- **Applied AI, Agents & RAG:** Multi-agent orchestration (`LangGraph`, `Semantic Kernel`, custom `MCP` servers & deterministic tool harnesses), hybrid RAG pipelines (`PostgreSQL pgvector` + `BM25` + `RRF`), and production guardrails (tenant isolation, PII/LGPD redaction, prompt-injection defense).
- **Distributed Backends & Domain Modeling:** High-availability services in **TypeScript (`NestJS`, `Node.js`, `Bun`)**, **C# (`.NET 9`)**, and **Rust (`Axum`, `Tokio`)**, applying **DDD**, **Hexagonal Architecture (Ports & Adapters)**, **CQRS**, and event-driven contracts (`CloudEvents`, `AWS SNS/SQS`, `Redis`, `SignalR`).
- **Offline-First & Native Mobile:** Mission-critical apps in **React Native**, **Kotlin (`Jetpack Compose`)**, and **Swift (`SwiftUI`)** engineered for zero data loss in disconnected environments (`RealmDB`, `Room`, `SwiftData`, background sync) and backed by automated E2E pipelines (`Playwright`, `Maestro`).

---

### Public Repositories & Technical Guides

- **[`manage-sound-app`](https://github.com/matheusmaiadev/manage-sound-app)** — **100% On-Device Native Android Automation** built with `Kotlin 2.3`, `Jetpack Compose M3 Expressive`, `Glance`, `Navigation 3`, passive geofencing, Wi-Fi triggers, and a hardened Google Play CI/CD pipeline.
- **[`guia-arquitetura-ia`](https://github.com/matheusmaiadev/guia-arquitetura-ia)** — **AI Architecture & Production Engineering Guide** covering LLM fundamentals, Multi-Agent Orchestration, Hybrid RAG, AWS Bedrock & Serverless GPU inference, Governance, and FinOps *(PT-BR)*.

### Selected Production & SaaS Architectures *(Private)*

- **Kipo Platform** — Multi-platform SaaS ecosystem combining a `.NET 9` core backend (Vertical Slices + SignalR + APNs/FCM), a headless `Rust` (`Axum` + `pgvector` + `RRF`) AI subscription router & HMAC-authenticated tool harness, a `React 19` AI Control Plane, and twin native `Kotlin/Compose` & `SwiftUI` apps.
- **STRATA** — Living context and multi-layer SaaS specification engine keeping product discovery, domain rules, architecture decisions, and multi-repo workflows synchronized.
- **Better Retro Board** — Real-time, structurally anonymous, phase-guided retrospective platform built with `React 19`, `TypeScript`, `Convex` WebSockets, `Tailwind CSS v4`, `Tauri v2` (Web, Desktop & Mobile), `Vitest`, and `Playwright` E2E.

---

### Core Stack

- **Languages:** TypeScript, C#, Kotlin, Swift, Rust, Python, SQL
- **Backend & AI:** NestJS, .NET 9, Axum, Hono, LangChain / LangGraph, MCP, PostgreSQL (`pgvector`), Redis, MongoDB
- **Frontend & Mobile:** React 19, Next.js, Astro, Tailwind CSS, React Native, Jetpack Compose, SwiftUI, Tauri v2, RealmDB
- **Cloud, Quality & DevOps:** AWS, Docker, Terraform, GitHub Actions, GitLab CI/CD, Playwright, Vitest, Maestro, OpenTelemetry / Sentry
