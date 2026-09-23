# Farhan Shafee

**Security Engineering × AI Automation × Fintech Systems**

My professional background is in fintech software and test automation. I build security and automation systems with the same focus on backend/API behavior, reproducible validation, and evidence that can be inspected.

[Portfolio](https://farhan-shafee.com) · [GitHub](https://github.com/farhan-shafee) · [LinkedIn](https://www.linkedin.com/in/farhanshafee/) · [Technical writing](https://farhan-shafee.com/writing)

## Flagship work

### AegisGraph V2 — Security Investigation Engineering

A security investigation platform for synthetic fintech telemetry, connecting scenario replay, deterministic detection and correlation, hypothesis tracking, and evidence-grounded AI.

[Live demo](https://aegisgraph.farhan-shafee.com) · [Case study](https://farhan-shafee.com/work/aegisgraph) · [Source](https://github.com/farhan-shafee/aegisgraph) · [Engineering article](https://farhan-shafee.com/writing/building-an-evidence-grounded-ai-security-investigation-system) · [CI](https://github.com/farhan-shafee/aegisgraph/actions/runs/35893999624)

- **Scenario replay:** Eight versioned synthetic scenarios exercise telemetry replay, normalization, deterministic detection, and correlation.
- **Hypotheses:** Supporting evidence, counterevidence, and missing observations stay separate from an analyst's acceptance.
- **Bounded AI:** Structured claims pass server-side schema, exact-context citation, and rule-based support checks. Tested unsupported premises return insufficient evidence; the model cannot change case state.
- **Detection tuning:** Versioned local rule proposals and full-corpus regression with human review; public comparisons use fixed presets.
- **Evidence export:** SHA-256 verification checks content against an unsigned, replaceable manifest. Hash agreement does not establish authenticity.

[Recorded V2 validation — September 23, 2026](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/V2_VALIDATION.md): **670 backend tests · 121 frontend tests · 26 browser tests**. Deterministic suites: **28 original evaluation cases · 145 V2 benchmark cases**. All three CI jobs passed. These evaluation suites use deterministic fixtures; [historical live OpenAI validation](https://github.com/farhan-shafee/aegisgraph/blob/main/docs/evaluations/LIVE_VALIDATION.md) is separate.

Public mode is read-only and deterministic; optional OpenAI analysis and persistent analyst workflows remain local/interview capabilities. Production authentication, tenant isolation, and real telemetry ingestion remain future work.

### CyberBit Solutions — Security Product Engineering

A cybersecurity business and product system connecting public security checks with assessment, reporting, and operations. Human-reviewed Snapshots remain distinct from automated paid Instant Signal Briefs. I built the admin/report tooling, Stripe checkout and webhook handling, paid-report access, and transactional email workflows.

[Product](https://cyberbitsolutions.com) · [Case study](https://farhan-shafee.com/work/cyberbit-solutions)

## Selected security engineering

| Project                                                                                       | Engineering evidence                                                                                                     |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [SecurePay / DevSecOps](https://github.com/farhan-shafee/devsecops-pipeline)                  | Synthetic payments API, deterministic security gates, scanner evidence validation, and repeatable remediation workflows. |
| [Vulnerability Management](https://github.com/farhan-shafee/vulnerability-management-project) | Scanner-export normalization, contextual prioritization, and remediation closure backed by matching rescan evidence.     |
| [Detection Engineering](https://github.com/farhan-shafee/detection-engineering-lab)           | Sigma rules, Python correlation, deterministic Windows telemetry fixtures, and simulated analyst investigations.         |

Additional labs: [Cloud Security](https://github.com/farhan-shafee/cloud-security-lab) · [Incident Response](https://github.com/farhan-shafee/incident-response-playbooks) · [Threat Hunting](https://github.com/farhan-shafee/threat-hunting-playbooks)

## Engineering focus

- **Security:** Detection, investigation, vulnerability workflows, and application-security controls with inspectable evidence.
- **AI systems:** Bounded context, structured output, deterministic validation, evaluation, and human-controlled state changes.
- **Backend and delivery:** Python/FastAPI, TypeScript/Next.js, PostgreSQL, REST APIs, Docker, CI/CD, and automated testing.
- **Fintech:** Backend financial systems, trading workflows, API/test automation, debugging, and release quality.

## Technical writing

**[Building an Evidence-Grounded AI Security Investigation System](https://farhan-shafee.com/writing/building-an-evidence-grounded-ai-security-investigation-system)**

An engineering account of AegisGraph's original architecture: separating detection from correlation, bounding model context, validating citations outside the model, and preserving human control.

## Contact

[LinkedIn](https://www.linkedin.com/in/farhanshafee/) · [Portfolio contact](https://farhan-shafee.com/contact)
