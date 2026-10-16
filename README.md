### Adil Khan — Lead Software Architect · Backend & Applied AI

I've spent 10+ years designing and shipping backend systems for US and UK companies: lending and
underwriting platforms, workforce-management SaaS, and international e-commerce logistics. Today I lead
engineering on a US loan-underwriting platform and bring applied AI into how the team builds software:
LLM-assisted code review and testing, and Whisper speech pipelines.

- 🏗️ **Architecture & leadership:** system design, service boundaries, code-review culture, mentoring teams of 5–15 engineers
- ⚙️ **Backend:** PHP / Laravel / Zend, Node.js / TypeScript, Python / FastAPI, REST & GraphQL, queues, event streams (Redis Streams)
- 🤖 **Applied AI:** LLM integration (Claude, OpenAI, Ollama), RAG with hybrid search, evals that gate CI, MCP servers, LangChain, Whisper, AI-assisted code review and testing
- ☁️ **Infra & data:** Docker, Kubernetes (kustomize, KEDA), AWS (EC2, Lambda, RDS, S3), GitHub Actions · PostgreSQL (RLS, pgvector, TimescaleDB), MySQL, Redis, MongoDB · Airflow, pandas

---

#### Featured work

| Project | What it shows |
|---|---|
| [**loan-underwriting-ai**](https://github.com/adilKhan72/loan-underwriting-ai) | Consumer-loan underwriting, end to end: a Laravel 13 API, a Python AI service with pluggable LLMs (Claude / OpenAI / Ollama) and a Vue dashboard. LLMs extract and explain, a **versioned rules engine decides**, PII is redacted before any model call, and a hash-chained audit trail records everything. 7 ADR-backed milestones, CI on PostgreSQL, runnable demo |
| [**ai-code-review-action**](https://github.com/adilKhan72/ai-code-review-action) | **v1.0.0.** A GitHub Action that reviews pull requests with an LLM (Claude / OpenAI / Ollama). Inline comments only on real diff lines, the diff treated as untrusted input, repo rules read from the base branch, de-duplicated re-runs, and opt-in test suggestions (unit + Playwright). TypeScript, 229 tests |
| [**rag-docs-assistant**](https://github.com/adilKhan72/rag-docs-assistant) | Retrieval-augmented Q&A: hybrid pgvector + Postgres full-text search with reciprocal rank fusion, **citations verified** before an answer is returned, an abstain threshold calibrated on data, retrieval evals **gating CI**, an LLM-judged answer eval, and an **MCP server**. Python, FastAPI, LangChain |
| [**lead-routing-engine**](https://github.com/adilKhan72/lead-routing-engine) | Event-driven lead distribution (ping-post) in TypeScript: Redis Streams consumer groups, atomic buyer caps, idempotency, leases with fencing tokens, a dead-letter queue, and a k6 load test that found and fixed a real throughput bug. Concurrency proven by integration tests |
| [**system-design-notes**](https://github.com/adilKhan72/system-design-notes) | Architecture write-ups with capacity maths, mermaid diagrams and ADRs: loan underwriting, ping-post lead distribution, multi-tenant workforce scheduling, international package forwarding, LLM features in production |
| [**workforce-scheduler-saas**](https://github.com/adilKhan72/workforce-scheduler-saas) | Multi-tenant shift scheduling: Laravel 13 + **Lighthouse GraphQL** + Vue 3. Tenant isolation enforced twice (app scope **and PostgreSQL row-level security**, proven by bypass tests), DST-correct shift times, versioned labour-rule packs, N+1-free week queries |
| [**meterflow**](https://github.com/adilKhan72/meterflow) | Data pipeline: **Airflow 3** DAGs over pandas + pandera validation, idempotent backfills into **TimescaleDB** hypertables with continuous aggregates, compression and retention, plus a data-quality gate that fails bad runs. A real `dag.test()` runs end to end in CI |
| [**laravel-pii-redactor**](https://github.com/adilKhan72/laravel-pii-redactor) | **v0.1.0** Laravel package: redact PII before text reaches LLMs, logs or third parties. Typed placeholders, counts-only results, a log-channel tap and an Eloquent cast. CI matrix PHP 8.3/8.4 × Laravel 12/13 |
| [**speech-to-text-pipeline**](https://github.com/adilKhan72/speech-to-text-pipeline) | FastAPI + faster-whisper service: async Redis/RQ jobs with permanent vs. transient retry handling, VAD-aligned chunking for long audio, **Urdu → English translation**, CI-tested |
| [**swatorganics-bagisto**](https://github.com/adilKhan72/swatorganics-bagisto) | A live store ([swatorganics.com](https://swatorganics.com)) on Laravel 11 / Bagisto: market-specific shipping and checkout, Meta Pixel and catalogue feed, SEO, scripted production deploys |
| [**urban_solution**](https://github.com/adilKhan72/urban_solution) | Role-based project-management system for an architecture firm: a ~40-table domain model with configurable intake fields and task workflows |

#### Professional highlights

- **Dependibot (US clients), Team Lead Software Engineer, AI** · 2023–present: lead development on Origin-8,
  a lead-management and loan-underwriting platform. Built borrower flows (e-signature, income/pay-date verification,
  secure SSN capture), SMS and SFTP integrations, fraud alerting, and introduced AI-assisted engineering.
- **ShopWorks (UK), Lead Full Stack Developer / Technical Architect** · 2022–2023: architecture for a retail
  workforce-management platform serving 100+ enterprise clients, with a 15+ engineer team.
- **GlobalShopaholics (US), Team Lead** · 2019–2020: high-volume international package-forwarding system with
  real-time shipping, tracking and payment integrations.

*Client and employer code is private. The repos here are my own work.*

---

📫 [LinkedIn](https://www.linkedin.com/in/adil-khan-60055112b/) · [adilkhanengineer72@gmail.com](mailto:adilkhanengineer72@gmail.com) · Islamabad, Pakistan · open to remote roles and relocation
