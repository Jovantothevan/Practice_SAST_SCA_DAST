# Security Scanning

## Overview
This repository uses 3 types of security scanning:

---

## SAST — CodeQL
- Static code analysis
- Runs on: push + PR
- Detects code vulnerabilities

---

## SCA — OWASP Dependency Check
- Identifies vulnerable libraries
- Generates XML, HTML, JSON reports
- Artifacts: sca-reports/

---

## DAST — OWASP ZAP (Baseline + Full Scan)
- Tests running application
- Finds runtime vulnerabilities
- Artifacts:
  - zap-baseline-reports/
  - zap-fullscan-reports/

---

## Understanding Results
See `SCAN_ANALYSIS.md`

## Reporting Vulnerabilities
Email: security@example.com
