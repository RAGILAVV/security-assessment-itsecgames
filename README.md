# security-assessment-itsecgames
## Problem Statement
Evaluate the security posture of a publicly hosted endpoint.

## Tools Used
- Nmap
- Nikto
- Gobuster
- SSLyze / TestSSL
- cURL

## Deliverables
- `accunkex_report.pdf` → Detailed vulnerability report
- `screenshots/` → Proof of tool outputs
- `scans/` → Raw scan results

## Key Findings
- Outdated Apache version (2.4.29) with known CVEs
- TLS certificate mismatch (`mmebv.be` instead of `itsecgames.com`)
- Missing security headers (HSTS, CSP, etc.)
