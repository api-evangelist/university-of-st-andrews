# University of St Andrews (university-of-st-andrews)

Scotland's first university (founded 1413) and ranked #90 in the QS World University Rankings 2025. This repository catalogs the University of St Andrews' public developer and API footprint as an [APIs.json](http://apisjson.org) provider profile. St Andrews has no centralized developer portal; its confirmed public, machine-readable surface is oriented toward research-data interoperability and operational transparency.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-st-andrews/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-st-andrews-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, OAI-PMH, Scotland, United Kingdom

## APIs

- **Service Status API** — JSON status API (Sorry platform), 10 req/sec, components and notices. Docs: https://status.st-andrews.ac.uk/api
- **Pure Research Portal OAI-PMH** — Metadata harvesting for the Pure research information system behind the St Andrews Research Portal. Base: https://risweb.st-andrews.ac.uk/ws/oai — Docs: https://www.st-andrews.ac.uk/research/support/pure/
- **St Andrews Research Repository OAI-PMH** — DSpace open-access repository metadata harvesting. Base: https://research-repository.st-andrews.ac.uk/dspace-oai/request — Docs: https://research-repository.st-andrews.ac.uk/

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/university-of-st-andrews-plans-pricing.yml](plans/university-of-st-andrews-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-st-andrews-rate-limits.yml](rate-limits/university-of-st-andrews-rate-limits.yml)
- FinOps: [finops/university-of-st-andrews-finops.yml](finops/university-of-st-andrews-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.st-andrews.ac.uk/
- GitHub (Research Computing): https://github.com/StAResComp
- LinkedIn: https://www.linkedin.com/school/university-of-st-andrews/
- Status: https://status.st-andrews.ac.uk/
- Review: [review.yml](review.yml)

## Notes

All entries were verified against live or cached public sources on 2026-06-03. The Pure OAI-PMH endpoint and Research Portal returned HTTP 200. The status API base path returns HTTP 406 to non-browser User-Agents but is documented and live. The DSpace Research Repository returned HTTP 503 to automated probes at review time (throttling); its OAI-PMH endpoint is confirmed via search indexing. The LinkedIn school page returns HTTP 999 (LinkedIn's bot/login gate) but exists. No endpoints were fabricated; St Andrews does not publish a unified developer portal.

## Maintainers

- Kin Lane — kin@apievangelist.com
