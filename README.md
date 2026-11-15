### Hi, I'm Ivan Petrovsky

Java Backend Developer based in Moscow. Previously owned backend development and architecture at an early-stage HR-tech startup (14 Java/Spring Boot microservices, Kafka, PostgreSQL, LLM pipelines). Also building tooling and structured workflows for AI coding agents.

---

### Core Stack

- **Backend:** Java, Spring Boot, Spring Security, JPA / Hibernate, REST API
- **Messaging & Data:** Apache Kafka, PostgreSQL, pgvector, Redis, Liquibase
- **AI & Tooling:** LangChain4j, structured LLM pipelines, AI coding-agent workflows (MCP, skills, hooks)
- **Infra & Observability:** Docker, GitHub Actions, Testcontainers, Grafana, Loki

---

### Experience & Key Projects

#### Vaiti — HR-tech Platform *(Oct 2025 – Jun 2026, commercial, private repo)*
Java Backend Developer responsible for backend architecture and core services across 14 microservices.
- **LLM Pipeline Optimization:** Moved taxonomy resolution out of prompts into `pgvector` semantic search and added fail-fast filtering, cutting per-vacancy processing cost by 70% and latency by 33%.
- **Quota & Billing Subsystem:** Built a hybrid credit model (Redis daily counters + PostgreSQL term credits) with idempotent compensating refund events over Kafka on AI operation failures.
- **Auto-Apply Recovery & Observability:** Migrated a stalled Python service into a colocated Java/Kafka consumer; built structured-log monitoring in Loki/Grafana and selective monorepo CI (`detect-impact.sh`) on GitHub Actions.

#### Public Projects
- **[Agent-Rig](https://github.com/impatient0/agent-rig)** *(add/verify link)* — A skill and workflow collection bringing engineering discipline to AI coding agents: isolated worktree dispatch, independent verification gates, ADR/backlog audits, and clean merges. *(Also publishing on [Agensi.io](https://agensi.io).)*
- **[Project A-Zero](https://github.com/impatient0/a-zero)** *(verify repo slug)* — Data-driven cryptocurrency trading and backtesting platform built with Java & Spring.
- **[1-Click Render Add-on](https://github.com/impatient0/render-pipeline-addon)** — Blender utility add-on for direct asset/render export.

---

### Links & Contact

- **Website:** [impatient0.com](https://impatient0.com)
- **Telegram:** [@LonkiSolomki](https://t.me/LonkiSolomki)
- **Email:** `ivanpetrovskiy98@gmail.com`
