# Uppsala University (uppsala)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
