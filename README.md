# Uppsala University (uppsala)

Uppsala University (Uppsala universitet) is Sweden's oldest university, founded in 1477, and is ranked #103 in the QS World University Rankings 2025. This repository catalogs the university's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. Uppsala has no single central developer portal; its public APIs are research-infrastructure driven and decentralized across departments and library systems.

APIs.json: https://raw.githubusercontent.com/api-evangelist/uppsala/refs/heads/main/apis.yml

Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=uppsala-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Research
- Open Data
- Sweden

## APIs

- **UCDP API** — Uppsala Conflict Data Program RESTful API (JSON) for conflict datasets; free access token required. Docs: https://ucdp.uu.se/apidocs/ — base `https://ucdpapi.pcr.uu.se/api/`
- **Norse World REST-API** — Attestation and location records of foreign place names in medieval Nordic texts; JSON, GeoJSON, JSON-LD. Docs: https://www.uu.se/en/research/norseworld/infrastructure/rest-api — base `https://norseworld.nordiska.uu.se/shared/`
- **DiVA OAI-PMH** — Institutional repository OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://www.uu.se/en/library/publish/diva — base `https://uu.diva-portal.org/dice/oai`

## Plans / Rate Limits / FinOps

- Plans: [plans/uppsala-plans-pricing.yml](plans/uppsala-plans-pricing.yml)
- Rate Limits: [rate-limits/uppsala-rate-limits.yml](rate-limits/uppsala-rate-limits.yml)
- FinOps: [finops/uppsala-finops.yml](finops/uppsala-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uu.se/
- GitHub: https://github.com/uppsala-university
- LinkedIn: https://www.linkedin.com/school/uppsala-university/
- Review: [review.yml](review.yml)

## Notes

All cataloged APIs and properties were verified against live URLs on 2026-06-03. The UCDP API endpoint returns HTTP 401 without an access token (expected, token is free on request). The Norse World REST-API and DiVA OAI-PMH endpoints returned HTTP 200. No endpoints, sign-up flows, or properties were fabricated. The LinkedIn page returns HTTP 999 (standard LinkedIn bot block) but the page exists.

## Maintainers

- Kin Lane — kin@apievangelist.com
