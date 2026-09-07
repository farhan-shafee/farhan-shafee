# Farhan Shafee

Security Automation | Vulnerability Management | Application Security

I bring a professional background in software and test automation for financial technology systems. My cybersecurity engineering portfolio applies Python, CI/CD and automated testing to security workflows: evaluating findings, validating remediation and testing detections. I can demonstrate each flagship system live with a reproducible walkthrough.

## Featured Security Engineering

### [SecurePay — Application Security / DevSecOps](https://github.com/farhan-shafee/devsecops-pipeline)

A synthetic payments API with finding normalization, a deterministic security policy engine and fail-closed handling of missing or invalid scanner evidence. GitHub Actions integrates Semgrep, pip-audit, Gitleaks, Trivy, passive OWASP ZAP and a CycloneDX SBOM.

The fixture-based demo reproduces **RED/BLOCK → remediation → PASS**, plus a scanner-failure BLOCK. Current real scanner execution returns **[WARN/REVIEW](https://github.com/farhan-shafee/devsecops-pipeline/actions/runs/34161990375)**, requiring human review.

[141 automated tests in CI](https://github.com/farhan-shafee/devsecops-pipeline/actions/runs/34161990404) · [Recorded scanner evidence](https://github.com/farhan-shafee/devsecops-pipeline/blob/main/reports/real-ci/34161489096/README.md) · [Interview walkthrough](https://github.com/farhan-shafee/devsecops-pipeline/blob/main/docs/interview-demo.md)

### [Vulnerability Management](https://github.com/farhan-shafee/vulnerability-management-project)

A Python workflow normalizing Trivy JSON, Nessus XML exports and CSV into contextual risk priorities, SLAs and tracked remediation. Closure requires recorded remediation and later matching scan evidence. A real local Trivy dependency-manifest scan records **5 → 0 findings** after a dependency upgrade.

[212 automated tests in CI](https://github.com/farhan-shafee/vulnerability-management-project/actions/runs/34147859541) · [Remediation evidence](https://github.com/farhan-shafee/vulnerability-management-project/blob/main/lab/evidence/manifest.json) · [Interview walkthrough](https://github.com/farhan-shafee/vulnerability-management-project/blob/main/docs/interview-demo.md)

### [Detection Engineering](https://github.com/farhan-shafee/detection-engineering-lab)

**Five Windows detections** using Sigma rules and Python correlation, mapped to MITRE ATT&CK. Deterministic telemetry fixtures support positive and negative detection tests, simulated analyst investigations, dispositions and rule tuning. Optional Wazuh architecture is documented; live deployment is unverified and there are no live Wazuh captures.

[51 passing fixture assertions](https://github.com/farhan-shafee/detection-engineering-lab/blob/main/reports/demo.md) · [Tuning evidence](https://github.com/farhan-shafee/detection-engineering-lab/blob/main/evidence/tuning/README.md) · [Interview walkthrough](https://github.com/farhan-shafee/detection-engineering-lab/blob/main/docs/interview-demo.md)

## Additional Security Labs

- [Cloud Security](https://github.com/farhan-shafee/cloud-security-lab) — Python IAM policy checks, cloud-event analysis and remediation write-ups using sample data.
- [Incident Response](https://github.com/farhan-shafee/incident-response-playbooks) — Scenario-based response playbooks with evidence, escalation and post-incident review templates.
- [Threat Hunting](https://github.com/farhan-shafee/threat-hunting-playbooks) — Hypothesis-driven hunts, query examples and investigation summaries using synthetic telemetry.

## Core Capabilities

Demonstrated in the repositories above:

- **Security automation:** Python, API/data processing, deterministic policy engines and automated validation.
- **Application security / DevSecOps:** SAST, SCA, secret and container scanning, passive DAST, SBOMs and CI/CD security gates.
- **Vulnerability management:** Scanner export normalization, contextual prioritization, SLAs, remediation tracking and closure evidence.
- **Detection engineering:** Sigma, Windows telemetry analysis, MITRE ATT&CK mapping, detection tests, triage reasoning and tuning.
- **Engineering:** Git/GitHub, GitHub Actions, Docker, REST APIs and automated testing across Windows and Linux.

## Engineering Background

Years of professional software/test automation work in fintech underpin my approach to API and backend testing, CI/CD, debugging and release quality. These projects extend that experience into security automation through explicit controls, repeatable tests and evidence that can be inspected.

## Live Interview Walkthroughs

Every flagship repository includes a deterministic screen-share workflow and a documented interview walkthrough, linked above. I can run the workflows and explain the implementation, results and limitations live.

## Contact

[LinkedIn](https://www.linkedin.com/in/farhanshafee/) · [farhanshafee@outlook.com](mailto:farhanshafee@outlook.com)
