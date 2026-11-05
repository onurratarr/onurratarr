# Hi, I'm Onur Atar 👋

**Applied AI / Forward Deployed Engineer — AI agents, automation workflows, RAG, and LLM evaluation.** Based in New Jersey, USA.

**Open to US roles** in AI agents, automation, forward-deployed, and applied AI engineering. US green card holder; no sponsorship needed.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

I turn ambiguous business problems into working AI systems: scoping agent solutions directly with business clients, building retrieval, tool-calling, and automation workflows, and designing the evaluation and human-review loops that keep them trustworthy.

- 🛰️ **AI Specialist, STEM & Data Intelligence @ SpaceX** (Apr 2024 – present) — LLM reasoning frameworks for STEM / advanced-math data, large-scale data curation and auditing, quality benchmarks for model outputs.
- 🧠 Previously **AI Data Scientist & STEM Expert @ Outlier** and **Data Scientist @ Shiptory**.
- 🎓 M.S. Information Technology (Data Management & Analytics) · B.S. Mathematics.
- 📚 Before tech: eight years leading a mathematics department and authoring calculus & geometry textbooks — I like explaining complex things clearly.

## What I build

- **Tool-calling agents** over CRM and ticketing APIs, WhatsApp, voice, and SQL warehouses
- **Integration and automation:** OAuth2 (client credentials, authorization code + PKCE), HMAC-signed idempotent webhooks, retries with backoff and jitter, audit logs
- **RAG** with citation-grounded answers and structured JSON intake
- **Evaluation:** rubric and reference scoring, LLM-as-judge, pairwise preferences, Cohen's kappa, CI regression gates
- **Human-in-the-loop** review queues, column-mapping review, and escalation / warm handoff

## Featured projects

Ordered by relevance to forward-deployed and automation work. These are **reference implementations on synthetic data only** — no client code or client data. Three of them (retail-whatsapp-llm-agent, turkish-legal-rag-intake, llm-eval-harness) are inspired by client projects I delivered.

| Project | What it shows |
|---|---|
| [enterprise-integration-agent](https://github.com/onurratarr/enterprise-integration-agent) | LLM agent over a Salesforce/Zendesk-style mock CRM and ticketing API: OAuth2 (client credentials, auth code + PKCE, refresh rotation), HMAC-signed idempotent webhooks, retries with backoff and jitter, PII-redacted audit log. |
| [customer-data-onboarding-pipeline](https://github.com/onurratarr/customer-data-onboarding-pipeline) | Messy CSV drops and a paginated REST API into DuckDB or Postgres: data contracts, quarantine, LLM-assisted column mapping with human review and a held-out eval, dbt-style models, data-quality checks, idempotent re-runs, audit trail. |
| [retail-whatsapp-llm-agent](https://github.com/onurratarr/retail-whatsapp-llm-agent) | WhatsApp retail agent: tool-calling over a synthetic SQLite product DB (price, promotion, stock), staff escalation, mock WhatsApp Cloud API webhook, SQL reports. |
| [voice-contact-center-agent](https://github.com/onurratarr/voice-contact-center-agent) | Contact-center voice agent: explicit flow spec, barge-in and silence handling, tool calls, warm handoff with a context summary, pluggable ASR/TTS, transcript evaluation. |
| [turkish-legal-rag-intake](https://github.com/onurratarr/turkish-legal-rag-intake) | Turkish legal RAG with citation-grounded answers, structured JSON client-intake agent, attorney review queue, rubric eval. |
| [text-to-sql-analytics-agent](https://github.com/onurratarr/text-to-sql-analytics-agent) | Schema-aware text-to-SQL over a synthetic dbt-style DuckDB warehouse: read-only SQL guard (allowlist, PII, LIMIT), validation and self-correction, execution-accuracy eval. |
| [llm-eval-harness](https://github.com/onurratarr/llm-eval-harness) | LLM evaluation harness: rubric and reference scoring, LLM-as-judge, RLHF-style pairwise preferences, Cohen's kappa, CI regression gate. |

**More:** [ofi-cross-impact-analysis](https://github.com/onurratarr/ofi-cross-impact-analysis) (Order Flow Imbalance cross-impact analysis).

## Skills

- **AI / LLM:** AI agents and tool calling, RAG, LLM evaluation and quality benchmarking, RLHF data, prompt engineering, LLM reasoning frameworks, data curation and annotation workflow design
- **Programming & data:** Python, SQL, FastAPI, DuckDB, Postgres, SQLite, Pydantic, dbt-style modeling, webhooks, OAuth2, statistical analysis, predictive modeling, data visualization
- **Working with clients:** requirements gathering, technical writing, explaining complex concepts to mixed audiences

## Contact

[LinkedIn — in/onur-atardsm](https://www.linkedin.com/in/onur-atardsm)
