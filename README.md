# Hyperping (hyperping)

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

Hyperping is an uptime monitoring and status page platform. Its REST API lets teams programmatically manage HTTP, ping, port, keyword, DNS, and browser monitors, run scheduled-task healthchecks, operate public status pages through incidents and maintenance windows, manage on-call outages, and pull uptime and SLA reporting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hyperping/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hyperping/refs/heads/main/apis.yml)

## Tags

- Uptime Monitoring
- Status Pages
- Incident Management
- Observability
- On-Call

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Hyperping Monitors API

Programmatically create, list, retrieve, update, and delete HTTP, ping, port, keyword, DNS, and browser monitors, plus cron-style healthchecks for scheduled tasks and background jobs, and pull uptime / SLA / MTTR reporting.

- **Human URL:** [https://hyperping.com/docs/api/monitors](https://hyperping.com/docs/api/monitors)
- **Base URL:** `https://api.hyperping.io/v1`

#### Tags

- Monitors
- Uptime Monitoring
- Healthchecks

#### Properties

- [Documentation](https://hyperping.com/docs/api/monitors)
- [API Reference](https://hyperping.com/docs/api/monitors)
- [OpenAPI](openapi/hyperping-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperping.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperping.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperping Status Pages API

Public machine-readable status feed exposing a status page's overall status indicator plus per-service operational state and uptime via the /{subdomain}/status.json endpoint for dashboards and internal tooling.

- **Human URL:** [https://hyperping.com/docs/status-page/status-page-json](https://hyperping.com/docs/status-page/status-page-json)
- **Base URL:** `https://api.hyperping.io/v1`

#### Tags

- Status Pages
- Public Status
- JSON

#### Properties

- [Documentation](https://hyperping.com/docs/status-page/status-page-json)
- [OpenAPI](openapi/hyperping-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperping.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperping.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperping Incidents API

Manage the full incident lifecycle on status pages (investigating, identified, monitoring, resolved) with threaded updates, schedule and complete maintenance windows, and acknowledge, resolve, or escalate on-call outages.

- **Human URL:** [https://hyperping.com/docs/api/incidents](https://hyperping.com/docs/api/incidents)
- **Base URL:** `https://api.hyperping.io/v1`

#### Tags

- Incidents
- Maintenance
- Outages

#### Properties

- [Documentation](https://hyperping.com/docs/api/incidents)
- [API Reference](https://hyperping.com/docs/api/incidents)
- [OpenAPI](openapi/hyperping-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperping.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperping.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperping Webhooks

Outbound event notifications delivering check.down and check.up payloads — including monitor UUID, status code, downtime duration, and multi-region ping results — to a configured webhook URL for incident automation.

- **Human URL:** [https://hyperping.com/docs/integrations/webhooks](https://hyperping.com/docs/integrations/webhooks)
- **Base URL:** `https://api.hyperping.io/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://hyperping.com/docs/integrations/webhooks)
- [OpenAPI](openapi/hyperping-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/hyperping)
- [LinkedIn](https://www.linkedin.com/company/hyperping)
- [Website](https://hyperping.com/)
- [Documentation](https://hyperping.com/docs)
- [Plans](plans/hyperping-plans-pricing.yml)
- [Rate Limits](rate-limits/hyperping-rate-limits.yml)
- [Fin Ops](finops/hyperping-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
