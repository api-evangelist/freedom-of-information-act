# Freedom of Information Act (freedom-of-information-act)
The Freedom of Information Act (FOIA) APIs published by FOIA.gov provide access to FOIA agency components (Drupal JSON:API), agency annual report XML, and the agency submission specification used by participating federal agencies.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/freedom-of-information-act/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Federal Government, FOIA, Transparency

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Freedom of Information Act (FOIA) API
The FOIA API exposes agency components (`/api/agency_components`, `/api/agency_components/{id}`, `/api/agency_components/{id}/request_form`) and annual report XML (`/api/annual-report-xml/{agency}/{year}`) at `https://api.foia.gov`. Public APIs require an `X-API-Key` header. The portal-to-agency submission API uses a `FOIA-API-SECRET` shared-secret header and is implemented at each participating agency (recommended host: `foia-api.agency.gov`).

**Human URL:** [https://www.foia.gov/developer/](https://www.foia.gov/developer/)

**Base URL:** `https://api.foia.gov`

#### Properties

- [Documentation](https://www.foia.gov/developer/)
- [OpenAPI](openapi/freedom-of-information-act-openapi.yml)

## Common Properties

- [Portal](https://www.foia.gov/developer/)
- [Website](https://www.foia.gov/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
