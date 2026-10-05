# Hi, I'm Rami 👋

AI engineer building reliable LLM agents and RAG systems. MSc in Computer Communication Engineering (2026), based in Lebanon.

## Featured projects

**[Multi-Agent Supervisor](https://github.com/rm12000356/multi-agent-supervisor-langgraph)** — a LangGraph assistant where a supervisor routes requests to SQL, RAG, web-research, visualization and conversation agents.
- Deterministic, bounded execution with per-turn step budgets and graceful handling of LLM outages and rate limits
- 100% routing accuracy on a 137-prompt evaluation, with a 90% acceptance threshold enforced by automated tests
- Role-based access, read-only database sessions, SSRF-protected web access
- 200+ unit tests, 72% coverage, and a randomized planner that detects loops and dead ends

**[Churn Survival](https://github.com/rm12000356/churn_survival)** — an end-to-end time-to-churn pipeline that uses survival analysis (penalized Cox PH with a Kaplan–Meier fallback) instead of binary classification, giving 30/90/180-day risk horizons and per-customer explanations.
- Five-stage modular pipeline with strict, versioned contracts between stages; onboarded 7+ real datasets (91k+ rows) with config-driven mapping, human-confirmed LLM-assisted column mapping, and quarantine of invalid rows
- Deterministic and auditable: bit-identical re-runs, with LLMs used only at the edges and never allowed to change a score, rank or risk level
- FastAPI service and web UI; 1,400+ tests, 94%+ coverage, ruff and mypy clean

**[Healthtrack](https://github.com/MoustafaWehbe/onramp-fp-medical-app)** — a full-stack medical platform I built with two teammates (hosted on a teammate's repository). React, Express, PostgreSQL, Redis, BullMQ and Docker.
- Health profiles, clinic and doctor management, dashboards and daily health logging, with authentication and ownership controls
- 372 backend tests with 97.19% service coverage

**[BPSK perceptron](https://github.com/rm12000356/BPSK-perceptron-ml)** — an adaptive perceptron classifier that detects BPSK signal transitions from I/Q data, from my telecom and 5G research background.

## Tools
Python · TypeScript/JavaScript · LangGraph · LangChain · RAG (pgvector, Qdrant) · Node.js · React · PostgreSQL · Docker · n8n · Ollama · Playwright

## Languages
English (fluent) · Spanish (native) · Arabic (conversational)

## Contact
[LinkedIn](https://linkedin.com/in/rami-noueihed)
