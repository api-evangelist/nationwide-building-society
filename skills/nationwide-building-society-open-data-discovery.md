---
name: Nationwide Open Data discovery
description: >-
  Find Nationwide ATMs, branches, and personal current account products using the
  public, unauthenticated OBIE Open Data APIs. No credentials required.
api: openapi/obie-open-data-atm-locator-openapi.json
tier: open-data
auth: none
base_url: https://openapi.nationwide.co.uk/open-banking/v2.2
operations:
- GET /atms
- GET /branches
- GET /personal-current-accounts
---

# Nationwide Open Data discovery

Nationwide's OBIE Open Data APIs are fully public — no OAuth, key, or certificate.
Base URL: `https://openapi.nationwide.co.uk/open-banking/v2.2`.

## Steps

1. **List ATMs** — `GET /atms`. Returns OBIE Open Data ATM records (identification,
   location, accessibility, supported currencies, services). Confirmed live
   (HTTP 200, application/json). Supports conditional GET via `If-None-Match` /
   `If-Modified-Since` (304 Not Modified).
2. **List branches** — `GET /branches`. Returns branch locations, opening times,
   accessibility, and services.
3. **List personal current accounts** — `GET /personal-current-accounts`. Returns
   product reference data: fees, eligibility, overdraft, features and benefits.

## Conventions

- Response envelope carries the OBIE `Meta` block with the Open Licence and
  TermsOfUse references; collection items sit under `data`.
- Handle `429 Too Many Requests` with backoff; `503` indicates the service is
  temporarily unavailable.
- Errors follow the OBIE `OBErrorResponse1` envelope — see
  `errors/nationwide-building-society-problem-types.yml`.

## Notes

- This flow uses only the Open Data tier. Account, payment, and funds-confirmation
  data require the FAPI-secured Read/Write APIs (mTLS + OAuth2 + PSD2 SCA) and TPP
  onboarding — see `authentication/nationwide-building-society-authentication.yml`.
