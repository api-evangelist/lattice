# Lattice (lattice)

Lattice is a people management platform used by over 5,000 companies to run performance reviews, track OKRs and goals, collect employee engagement survey data, manage compensation, and handle core HR (HRIS) workflows. The platform exposes two public REST APIs: the Lattice Talent API (v1) for performance, goals, feedback, and review data, and the Lattice HRIS API (v2) for employee records and organizational data. Both APIs use API-key authentication and are documented on the Lattice Developer Hub at developers.lattice.com.

APIs.json: https://raw.githubusercontent.com/api-evangelist/lattice/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=lattice-api-evangelist&utm_content=repo

## Tags

- HR
- People Management
- Performance Management
- OKRs
- Goals
- Employee Engagement
- HRIS
- Compensation
- Feedback
- Surveys

## APIs

### Lattice Talent API

REST API for Lattice's Talent product suite covering users, goals, OKRs, performance review cycles, continuous feedback, competencies, tasks, and organizational departments. Uses cursor-based pagination and API key authentication.

- Documentation: https://developers.lattice.com/reference/introduction
- Base URL: https://api.latticehq.com/v1

### Lattice HRIS API

REST API (v2) for Lattice's HRIS product covering employee records, organizational hierarchy, and HR core data. Supports service account authentication and is designed for HR system integrations including Okta SCIM provisioning.

- Documentation: https://developers.lattice.com
- Base URL: https://api.latticehq.com/v2

## Plans / Rate Limits / FinOps

| Resource | File |
|---|---|
| Plans & Pricing | [plans/lattice-plans-pricing.yml](plans/lattice-plans-pricing.yml) |
| Rate Limits | [rate-limits/lattice-rate-limits.yml](rate-limits/lattice-rate-limits.yml) |
| FinOps | [finops/lattice-finops.yml](finops/lattice-finops.yml) |

Lattice uses a modular per-employee-per-month (PEPM) pricing model billed annually with a minimum contract of approximately $4,000. Performance Management starts around $11-14 PEPM; HRIS around $10-16 PEPM. API access is bundled with the corresponding product module — no separate API usage charges. Rate limits are enforced per API key (~100 RPM for Talent API, ~60 RPM for HRIS API); 429 responses include a Retry-After header.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|---|---|
| Website | https://lattice.com |
| Documentation | https://developers.lattice.com |
| LinkedIn | https://www.linkedin.com/company/lattice-hq |
| X | https://x.com/latticehq |
| Blog | https://lattice.com/blog |
| Pricing | https://lattice.com/pricing |
| Status Page | https://status.latticehq.com |

## Maintainers

- Kin Lane / kin@apievangelist.com
