# Lab 10 — Submission

## Task 1: DefectDojo Setup + Import

### DefectDojo version
- Version installed: 3.1.101

### Product + Engagement
- Product ID: 1
- Product name: OWASP Juice Shop
- Engagement ID: 1
- Engagement status: In Progress

### Imports completed
| Lab | Scan type | File | Findings imported |
|-----|-----------|------|------------------:|
| 4 | Anchore Grype | grype-from-sbom.json | 110 |
| 4 | Trivy Scan | trivy.json | 115 |
| 6 | Checkov Scan | results_json.json | 80 |
| 7 | Trivy Scan (image) | trivy-image.json | 51 |
| **Total raw imports** | | | 356 |
| **After dedup** | | | 152 |

### Dedup example (Lecture 10 slide 11)
- CVE/ID: CVE-2010-4756 (GHSA-35jh-r3h4-6jhm)
- Number of source tools: 2 (Anchore Grype + Trivy Scan)
- DefectDojo's single finding ID: 93