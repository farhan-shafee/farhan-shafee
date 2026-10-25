# Farhan Shafee

**Security Engineering × AI Automation × Fintech Systems**

My professional background is in fintech software and test automation. I build security and automation systems with the same focus on backend/API behavior, reproducible validation, and evidence that can be inspected.

[Portfolio](https://farhan-shafee.com) · [LinkedIn](https://www.linkedin.com/in/farhanshafee/) · [Technical writing](https://farhan-shafee.com/writing) · [Contact](https://farhan-shafee.com/contact)

## Start here

| Explore                             | Project           | Open                                                                                                                                                                                                                                          |
| ----------------------------------- | ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Security investigation & AI         | **AegisGraph**    | [Live demo](https://aegisgraph.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/aegisgraph)                                                                                                                                     |
| Trading support & MCP               | **CreditOps AI**  | [Live showcase](https://creditops.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/creditops-ai)                                                                                                                                |
| SDET & trading-workflow testing     | **TradeFlow**     | [Live demo](https://tradeflow.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/institutional-trading-sdet-lab) · [Demo guide](https://github.com/farhan-shafee/institutional-trading-sdet-lab/blob/main/docs/INTERVIEW_DEMO.md) |
| Banking and API quality engineering | **CreditFlow QE** | [Live demo](https://creditflow.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/creditflow-qe)                                                                                                                                  |

## Selected work

### AegisGraph — Security investigation engineering

Replay synthetic fintech telemetry, inspect detections and competing hypotheses, compare detection-rule changes, and review evidence-grounded findings. **Python/FastAPI, TypeScript/Next.js, PostgreSQL.**

Public analysis is read-only and deterministic; optional live AI and saved analyst workflows are separate local/interview capabilities. Real telemetry ingestion and production identity/tenant controls remain outside the demo.

[Architecture](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/architecture/SYSTEM.md) · [Threat model](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/threat-model/THREAT_MODEL.md) · [Validation](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/VALIDATION.md)

### CreditOps AI — Trading incident investigation

Explore pricing/Kafka backlog, FIX session instability, and database-pool exhaustion through RFQ/order impact, linked evidence, original-versus-validated assessments, and technical/stakeholder handoffs. **Python/FastAPI, read-only MCP tools, Next.js, PostgreSQL.**

The public showcase plays recorded model-assisted investigations using synthetic data, with no new model or MCP diagnostic calls during playback. Fresh MCP diagnostics are a separate mode. The recordings do not demonstrate model-directed follow-ups; initiating causes remain unconfirmed and human review is required. The source is public. Railway hosts the Next.js console, FastAPI API and PostgreSQL, with TLS, a restricted application role and tested off-volume backup recovery.

### TradeFlow — Institutional-trading SDET lab

Inspect synthetic order workflows and their **Playwright/TypeScript UI, API, contract, and integration tests**. Test-scoped fixtures, server-side authorization, runtime/OpenAPI validation, failure traces, and Chromium/Firefox/WebKit coverage make the test strategy visible.

TradeFlow runs locally for development and is independently hosted on Railway behind Cloudflare Tunnel. It has no database; synthetic sessions and orders reset on app restart. It is an interview and learning project—not a brokerage, matching engine, or live trading platform.

October 25, 2026 [dependency maintenance](https://github.com/farhan-shafee/institutional-trading-sdet-lab/blob/main/docs/SECURITY_MAINTENANCE_2026-10-25.md) updates Zod, Undici and fast-uri within compatible ranges and adds blocking full/production npm audits. The reviewed patch 265c9e0 was released on Railway after [successful CI](https://github.com/farhan-shafee/institutional-trading-sdet-lab/actions/runs/40214510996), followed by 20 public acceptance checks. Both audits reported zero known findings at validation time; that dated result is not a security guarantee.

[Live demo](https://tradeflow.farhan-shafee.com) · [Test strategy](https://github.com/farhan-shafee/institutional-trading-sdet-lab/blob/main/docs/TEST_STRATEGY.md) · [Fixtures](https://github.com/farhan-shafee/institutional-trading-sdet-lab/blob/main/docs/FIXTURES.md) · [CI](https://github.com/farhan-shafee/institutional-trading-sdet-lab/actions/workflows/quality.yml)

### CreditFlow QE — Synthetic banking and test engineering

A credit-card ledger simulator built with **Java 21, Spring Boot, PostgreSQL, and Flyway**. Independent Cucumber/REST Assured, TestNG, Selenium/Playwright, and GitHub Actions checks exercise transaction correctness, account ownership, idempotency, concurrency, and browser/API workflows.

The demo uses synthetic accounts. Railway hosts its Next.js frontend, Java API and PostgreSQL with private verify-full TLS; the web/API remain pinned to reviewed releases. API sleep is disabled, while the frontend may wake from idle. First scheduled daily-backup closeout and retained-resource cleanup remain pending as of October 25, 2026. It does not move real funds or establish regulated banking operation. The October 15, 2026 main CI at 631948a passed its core and browser jobs; earlier hosted-release and isolated Jenkins results are separate dated evidence.

[Live demo](https://creditflow.farhan-shafee.com) · [Source](https://github.com/farhan-shafee/creditflow-qe) · [Case study](https://farhan-shafee.com/work/creditflow-qe) · [CI](https://github.com/farhan-shafee/creditflow-qe/actions/runs/38820309474)

## Hosting and operating evidence

The portfolio and all four flagship demos run on Railway; Cloudflare supplies DNS and TradeFlow's tunnel ingress. The portfolio's GitHub main → successful CI → automatic production release was exercised at an exact commit. Release pins and CI-trigger behavior differ by project; [the current deployment matrix](https://github.com/farhan-shafee/farhanshafee.com/blob/main/docs/PROJECT_DEPLOYMENTS.md) records those boundaries.

AegisGraph uses a restricted SELECT-only API database account and required TLS. CreditOps and AegisGraph production-backup restores were tested; CreditFlow has isolated WAL recovery evidence and pending first scheduled daily-backup closeout. These finite checks do not establish availability, generalized security, RPO/RTO or real banking/trading operation. Retained old-provider resources await separate cleanup.

## Supporting security work

| Project                                                                                       | Focus                                                                                    |
| --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| [SecurePay / DevSecOps](https://github.com/farhan-shafee/devsecops-pipeline)                  | Synthetic payments API, security gates, scanner evidence, and repeatable remediation.    |
| [Detection Engineering](https://github.com/farhan-shafee/detection-engineering-lab)           | Sigma rules, Python correlation, Windows telemetry fixtures, and simulated triage.       |
| [Cloud Security](https://github.com/farhan-shafee/cloud-security-lab)                         | Synthetic cloud-posture checks, audit-event detection, and reassessment.                 |
| [Vulnerability Management](https://github.com/farhan-shafee/vulnerability-management-project) | Scanner normalization, contextual prioritization, and rescan-backed remediation closure. |

Additional labs: [Incident Response](https://github.com/farhan-shafee/incident-response-playbooks) · [Threat Hunting](https://github.com/farhan-shafee/threat-hunting-playbooks)

## Engineering focus

Python/FastAPI · TypeScript/Next.js · Node.js · PostgreSQL · REST APIs · Playwright · Docker · CI/CD · Security validation · Human-reviewed AI tooling

## Technical writing

[**Building an Evidence-Grounded AI Security Investigation System**](https://farhan-shafee.com/writing/building-an-evidence-grounded-ai-security-investigation-system) — detection versus correlation, bounded model context, citation validation, and human-controlled decisions.
