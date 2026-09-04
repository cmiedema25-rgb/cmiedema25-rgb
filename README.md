# Charles Miedema

### AI Automation • Python • LLM Evaluation • Document AI • Agent Safety

I build and evaluate practical AI and automation systems with a focus on reliability, clear architecture, and real-world implementation. My work includes Python automation, tool-using AI agents, API integrations, workflow orchestration, document extraction, model-response evaluation, prompt testing, and adversarial evaluation.

I am especially interested in systems that connect language models to useful tools and business processes while remaining testable, observable, and safe to rerun.

## Technical Focus

- **AI & LLM Systems:** tool/function calling, agent orchestration, prompt and response evaluation, pairwise preference labeling, adversarial testing
- **Automation Engineering:** resumable workflows, retries, checkpoints, idempotency, CLI tooling
- **Document AI:** OCR-aware normalization, field extraction, provenance, validation
- **Agent Safety:** prompt-injection defenses, capability allowlists, tamper-evident audit trails
- **Python Development:** typed application code, modular architecture, testing, packaging
- **API & Integration Engineering:** REST-style integrations, JSON, webhooks, HMAC signing, environment-based configuration
- **Software Quality:** pytest, Ruff, GitHub Actions, CI, secure secret handling

## Featured Projects

### [LoadWatch](https://github.com/cmiedema25-rgb/loadwatch-shipment-exceptions)

Resumable shipment-exception triage for TMS exports: policy-based routing, auditable decision reports, checkpointed workflow stages, and signed webhook alerts.

**Highlights:** deterministic exception policy, atomic run state, HMAC-signed alerts, pytest, Ruff, and GitHub Actions CI on Python 3.11+.

[![LoadWatch CI](https://github.com/cmiedema25-rgb/loadwatch-shipment-exceptions/actions/workflows/ci.yml/badge.svg)](https://github.com/cmiedema25-rgb/loadwatch-shipment-exceptions/actions/workflows/ci.yml)

### [LLM Evaluation & Alignment Lab](https://github.com/cmiedema25-rgb/llm-evaluation-alignment-lab)

Deterministic LLM scoring, prompt-regression testing, pairwise preference annotation, alignment-data export, and an optional LoRA fine-tuning entry point.

**Highlights:** retained benchmark evidence, preference export, reviewer-disagreement analysis, pytest, Ruff, GitHub Actions.

[![LLM Evaluation Lab CI](https://github.com/cmiedema25-rgb/llm-evaluation-alignment-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/cmiedema25-rgb/llm-evaluation-alignment-lab/actions/workflows/ci.yml)

### [Document Intelligence Pipeline](https://github.com/cmiedema25-rgb/document-intelligence-pipeline)

OCR-aware document classification and field extraction with provenance, arithmetic validation, CLI/HTTP API, and a strict TypeScript SDK.

**Highlights:** layout-aware fixtures, retained benchmark report, Python + TypeScript CI, measurable precision/recall evidence.

[![Document Intelligence CI](https://github.com/cmiedema25-rgb/document-intelligence-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/cmiedema25-rgb/document-intelligence-pipeline/actions/workflows/ci.yml)

### [Secure Agent Runtime](https://github.com/cmiedema25-rgb/secure-agent-runtime)

A zero-dependency security gateway for tool-using AI agents: injection detection, policy decisions, capability limits, and tamper-evident audit evidence.

**Highlights:** 34-case red-team corpus, offline deterministic provider, HMAC audit chain, CodeQL + CI matrix.

[![Secure Agent Runtime CI](https://github.com/cmiedema25-rgb/secure-agent-runtime/actions/workflows/ci.yml/badge.svg)](https://github.com/cmiedema25-rgb/secure-agent-runtime/actions/workflows/ci.yml)

## Technologies

`Python` · `TypeScript` · `OpenAI-compatible APIs` · `REST APIs` · `JSON` · `Webhooks` · `OCR/Document AI` · `pytest` · `Ruff` · `GitHub Actions` · `Git` · `CI/CD` · `Transformers` · `PEFT/LoRA`

## Engineering Approach

I prefer systems designed to survive failures rather than just succeed once. That means predictable retries, persistent state, explicit interfaces, reproducible tests, secure configuration, measurable evaluation criteria, and documentation that makes a system understandable to the next person who works on it.

## Current Direction

I am continuing to develop portfolio projects around AI automation, agent workflows, API integrations, document intelligence, LLM evaluation, and practical agent-safety controls — with retained evidence a reviewer can re-run.

---

**GitHub:** [cmiedema25-rgb](https://github.com/cmiedema25-rgb)  
**Featured repositories:** [LoadWatch](https://github.com/cmiedema25-rgb/loadwatch-shipment-exceptions) · [LLM Evaluation Lab](https://github.com/cmiedema25-rgb/llm-evaluation-alignment-lab) · [Document Intelligence](https://github.com/cmiedema25-rgb/document-intelligence-pipeline) · [Secure Agent Runtime](https://github.com/cmiedema25-rgb/secure-agent-runtime)
