# Farhan Shafee

**Security Engineering × AI Automation × Fintech Systems**

My professional background is in fintech software and test automation. I build security and automation systems with the same focus on backend/API behavior, reproducible validation, and evidence that can be inspected.

[Portfolio](https://farhan-shafee.com) · [LinkedIn](https://www.linkedin.com/in/farhanshafee/) · [Technical writing](https://farhan-shafee.com/writing) · [Contact](https://farhan-shafee.com/contact)

## Start here

| Explore | Project | Open |
| --- | --- | --- |
| Security investigation & AI | **AegisGraph** | [Live demo](https://aegisgraph.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/aegisgraph) |
| Trading support & MCP | **CreditOps AI** | [Live showcase](https://creditops.farhan-shafee.com) · Source private |
| SDET & trading-workflow testing | **TradeFlow** | [Live demo](https://tradeflow.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/institutional-trading-sdet-lab) · [Demo guide](https://github.com/farhan-shafee/institutional-trading-sdet-lab/blob/main/docs/INTERVIEW_DEMO.md) |
| Banking and API quality engineering | **CreditFlow QE** | [Live demo](https://creditflow.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/creditflow-qe) |

## Selected work

### AegisGraph — Security investigation engineering

Replay synthetic fintech telemetry, inspect detections and competing hypotheses, compare detection-rule changes, and review evidence-grounded findings. **Python/FastAPI, TypeScript/Next.js, PostgreSQL.**

Public analysis is read-only and deterministic; optional live AI and saved analyst workflows are separate local/interview capabilities. Real telemetry ingestion and production identity/tenant controls remain outside the demo.

[Architecture](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/architecture/SYSTEM.md) · [Threat model](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/threat-model/THREAT_MODEL.md) · [Validation](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/VALIDATION.md)

### CreditOps AI — Trading incident investigation

Explore pricing/Kafka backlog, FIX session instability, and database-pool exhaustion through RFQ/order impact, linked evidence, original-versus-validated assessments, and technical/stakeholder handoffs. **Python/FastAPI, read-only MCP tools, Next.js, PostgreSQL.**

The public showcase plays recorded model-assisted investigations using synthetic data, with no new model or MCP diagnostic calls during playback. Fresh MCP diagnostics are a separate mode. The recordings do not demonstrate model-directed follow-ups; initiating causes remain unconfirmed and human review is required. Source remains private.

### TradeFlow — Institutional-trading SDET lab

Inspect synthetic order workflows and their **Playwright/TypeScript UI, API, contract, and integration tests**. Test-scoped fixtures, server-side authorization, runtime/OpenAPI validation, failure traces, and Chromium/Firefox/WebKit coverage make the test strategy visible.

This is a locally run interview and learning project—not a brokerage, matching engine, or live trading platform.

[Live demo](https://tradeflow.farhan-shafee.com) · [Test strategy](https://github.com/farhan-shafee/institutional-trading-sdet-lab/blob/main/docs/TEST_STRATEGY.md) · [Fixtures](https://github.com/farhan-shafee/institutional-trading-sdet-lab/blob/main/docs/FIXTURES.md) · [CI](https://github.com/farhan-shafee/institutional-trading-sdet-lab/actions/workflows/quality.yml)

### CreditFlow QE — Synthetic banking and test engineering

A credit-card ledger simulator built with **Java 21, Spring Boot, PostgreSQL, and Flyway**. Independent Cucumber/REST Assured, TestNG, Selenium/Playwright, and GitHub Actions checks exercise transaction correctness, account ownership, idempotency, concurrency, and browser/API workflows.

The demo uses synthetic accounts and may take time to wake from idle. It does not move real funds or establish regulated banking operation. The October 15, 2026 main CI at 631948a passed its core and browser jobs; earlier hosted-release and isolated Jenkins results are separate dated evidence.

[Live demo](https://creditflow.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/creditflow-qe) · [Case study](https://farhan-shafee.com/work/creditflow-qe) · [CI](https://github.com/farhan-shafee/creditflow-qe/actions/runs/38820309474)

## Supporting security work

| Project | Focus |
| --- | --- |
| [SecurePay / DevSecOps](https://github.com/farhan-shafee/devsecops-pipeline) | Synthetic payments API, security gates, scanner evidence, and repeatable remediation. |
| [Detection Engineering](https://github.com/farhan-shafee/detection-engineering-lab) | Sigma rules, Python correlation, Windows telemetry fixtures, and simulated triage. |
| [Cloud Security](https://github.com/farhan-shafee/cloud-security-lab) | Synthetic cloud-posture checks, audit-event detection, and reassessment. |
| [Vulnerability Management](https://github.com/farhan-shafee/vulnerability-management-project) | Scanner normalization, contextual prioritization, and rescan-backed remediation closure. |

Additional labs: [Incident Response](https://github.com/farhan-shafee/incident-response-playbooks) · [Threat Hunting](https://github.com/farhan-shafee/threat-hunting-playbooks)

## Engineering focus

Python/FastAPI · TypeScript/Next.js · Node.js · PostgreSQL · REST APIs · Playwright · Docker · CI/CD · Security validation · Human-reviewed AI tooling

## Technical writing

[**Building an Evidence-Grounded AI Security Investigation System**](https://farhan-shafee.com/writing/building-an-evidence-grounded-ai-security-investigation-system) — detection versus correlation, bounded model context, citation validation, and human-controlled decisions.
