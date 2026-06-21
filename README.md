# Hyperping (hyperping)

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
