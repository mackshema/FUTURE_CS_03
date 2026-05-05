#  API Security Risk Analysis Report
### Cybersecurity Task 3 (2026)

![Type](https://img.shields.io/badge/Type-API%20Security%20Audit-blue)
![Target](https://img.shields.io/badge/Target-JSONPlaceholder-teal)
![Findings](https://img.shields.io/badge/Findings-9%20Issues-orange)
![Risk](https://img.shields.io/badge/Overall%20Risk-HIGH-red)
![Status](https://img.shields.io/badge/Status-Completed-green)

##  Target API
| Field | Detail |
|-------|--------|
| API | https://jsonplaceholder.typicode.com |
| Type | Public REST API — JSON |
| Tool | Postman (Future Interns — API Security Task 3) |
| Date | 2 May 2026 |
| Scope | Read-only — no exploitation |

##  Findings Summary
| ID | Finding | Severity | OWASP |
|----|---------|----------|-------|
| API-01 | Unauthenticated Access to All Users | HIGH | API2:2023 |
| API-02 | Excessive PII & Geo Data Exposure | HIGH | API3:2023 |
| API-03 | No Pagination / Mass Data Dump | MEDIUM | API4:2023 |
| API-04 | IDOR / BOLA — Any User by ID | HIGH | API1:2023 |
| API-05 | Unauthenticated POST Write Access | HIGH | API2:2023 |
| API-06 | Unauthenticated DELETE — 200 OK | CRITICAL | API5:2023 |
| API-07 | Missing Security Headers | MEDIUM | API8:2023 |
| API-08 | Weak Rate Limiting (1000 req) | MEDIUM | API4:2023 |
| API-09 | Technology Stack Disclosure | LOW | API8:2023 |


##  Ethical Disclaimer
> Read-only passive testing only on a public test API.
> No exploitation attempted. Educational use only.

##  Analyst
** Siva Sanjay Muthu T ** — 2026
