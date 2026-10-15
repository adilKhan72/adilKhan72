### Adil Khan — Lead Software Architect · Backend & Applied AI

I've spent 10+ years designing and shipping backend systems for US and UK companies: lending and
underwriting platforms, workforce-management SaaS, and international e-commerce logistics. Today I lead
engineering on a US loan-underwriting platform and bring applied AI into how the team builds software:
LLM-assisted code review and testing, and Whisper speech pipelines.

- 🏗️ **Architecture & leadership:** system design, service boundaries, code-review culture, mentoring teams of 5–15 engineers
- ⚙️ **Backend:** PHP / Laravel / Zend, Node.js / Express, Python / FastAPI, REST & GraphQL, queues and workers
- 🤖 **Applied AI:** LLM integration (OpenAI, Claude), LangChain, speech-to-text (Whisper), AI-assisted testing (Playwright)
- ☁️ **Infra:** Docker, AWS (EC2, Lambda, RDS, S3), GitHub Actions, Nginx · MySQL, PostgreSQL, Redis, MongoDB

---

#### Featured work

| Project | What it shows |
|---|---|
| [**loan-underwriting-ai**](https://github.com/adilKhan72/loan-underwriting-ai) | *In progress, built in public.* Consumer-loan underwriting: a Laravel 13 API and a Python AI service with pluggable LLMs (Claude / OpenAI / local Ollama). LLMs extract and explain, a versioned rules engine decides, and PII is encrypted and redacted. ADRs, CI on PostgreSQL |
| [**ai-code-review-action**](https://github.com/adilKhan72/ai-code-review-action) | *In progress.* A GitHub Action that reviews pull requests with an LLM (Claude / OpenAI / Ollama). Inline comments only on real diff lines, the PR diff treated as untrusted input, repo rules read from the base branch, and de-duplicated comments across re-runs. TypeScript, 100+ tests |
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
