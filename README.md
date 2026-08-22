# Nationwide Building Society (nationwide-building-society)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Nationwide Building Society is the world's largest building society and one of the UK's biggest retail financial services providers, headquartered in Swindon, England. As a mutual it is owned by and run for the benefit of its members. As one of the CMA9, Nationwide operates a public developer portal publishing UK Open Banking APIs conformant to the Open Banking Implementation Entity (OBIE) standards - public Open Data APIs plus FAPI-secured Read/Write APIs for account information, payments, confirmation of funds, and variable recurring payments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nationwide-building-society/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nationwide-building-society/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Building Society
- Open Banking
- PSD2
- OBIE
- CMA9
- United Kingdom
- Payments
- Account Information

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Nationwide ATM Locator API

Public, unauthenticated OBIE Open Data API listing Nationwide ATM locations, accessibility, supported currencies, and services. Confirmed live (HTTP 200, application/json) at v2.2.

- **Human URL:** [https://developer.nationwide.co.uk/open-banking/open-data-apis](https://developer.nationwide.co.uk/open-banking/open-data-apis)
- **Base URL:** `https://openapi.nationwide.co.uk/open-banking/v2.2`

#### Tags

- Open Data
- ATMs

#### Properties

- [OpenAPI](openapi/obie-open-data-atm-locator-openapi.json) — shared OBIE Open Data standard (ATM Locator v2.3.0)
- [Documentation](https://developer.nationwide.co.uk/open-banking/open-data-apis)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

### Nationwide Branch Locator API

Public, unauthenticated OBIE Open Data API listing Nationwide branch locations, opening hours, accessibility, and services.

- **Human URL:** [https://developer.nationwide.co.uk/open-banking/open-data-apis](https://developer.nationwide.co.uk/open-banking/open-data-apis)
- **Base URL:** `https://openapi.nationwide.co.uk/open-banking/v2.2`

#### Tags

- Open Data
- Branches

#### Properties

- [OpenAPI](openapi/obie-open-data-branch-locator-openapi.json) — shared OBIE Open Data standard (Branch Locator v2.3.0)
- [Documentation](https://developer.nationwide.co.uk/open-banking/open-data-apis)

### Nationwide Personal Current Accounts API

Public, unauthenticated OBIE Open Data API publishing reference data for Nationwide personal current account products, features, and fees. Confirmed live (HTTP 200, application/json) at v2.2.

- **Human URL:** [https://developer.nationwide.co.uk/open-banking/open-data-apis](https://developer.nationwide.co.uk/open-banking/open-data-apis)
- **Base URL:** `https://openapi.nationwide.co.uk/open-banking/v2.2`

#### Tags

- Open Data
- Personal Current Accounts

#### Properties

- [OpenAPI](openapi/obie-open-data-personal-current-accounts-openapi.json) — shared OBIE Open Data standard (PCA v2.4.0)
- [Documentation](https://developer.nationwide.co.uk/open-banking/open-data-apis)

### Nationwide Account and Transaction Information API (AIS)

OBIE Read/Write Account and Transaction Information (AIS) API providing consented access to Nationwide account, balance, and transaction data. FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA).

- **Human URL:** [https://developer.nationwide.co.uk/open-banking/account-information-apis](https://developer.nationwide.co.uk/open-banking/account-information-apis)
- **Base URL:** `https://api.nationwide.co.uk/open-banking/v3.1/aisp`

#### Tags

- Account Information
- AIS
- Read/Write

### Nationwide Payment Initiation API (PIS)

OBIE Read/Write Payment Initiation (PIS) API for initiating payments from Nationwide accounts with customer consent. FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA).

- **Human URL:** [https://developer.nationwide.co.uk/open-banking/payment-initiation-apis](https://developer.nationwide.co.uk/open-banking/payment-initiation-apis)
- **Base URL:** `https://api.nationwide.co.uk/open-banking/v3.1/pisp`

#### Tags

- Payment Initiation
- PIS
- Read/Write

### Nationwide Confirmation of Funds API (CBPII)

OBIE Read/Write Confirmation of Funds (CBPII) utility API for checking fund availability on a Nationwide account. FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA).

- **Human URL:** [https://developer.nationwide.co.uk/open-banking/utility-apis](https://developer.nationwide.co.uk/open-banking/utility-apis)
- **Base URL:** `https://api.nationwide.co.uk/open-banking/v3.1/cbpii`

#### Tags

- Confirmation of Funds
- CBPII
- Read/Write

### Nationwide Variable Recurring Payments API (VRP)

OBIE Read/Write Variable Recurring Payments (VRP) API for consented sweeping and recurring payment mandates. FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA).

- **Human URL:** [https://developer.nationwide.co.uk/open-banking/payment-initiation-apis](https://developer.nationwide.co.uk/open-banking/payment-initiation-apis)
- **Base URL:** `https://api.nationwide.co.uk/open-banking/v3.1/pisp`

#### Tags

- Variable Recurring Payments
- VRP
- Read/Write

## Common Properties

- [Website](https://www.nationwide.co.uk/)
- [Developer Portal](https://developer.nationwide.co.uk/)
- [Documentation](https://developer.nationwide.co.uk/open-banking)
- [Getting Started](https://developer.nationwide.co.uk/open-banking/open-data-apis)
- [Support](https://developer.nationwide.co.uk/open-banking/support/faq)
- [Status Page](https://developer.nationwide.co.uk/open-banking/support/known-issues)
- [LinkedIn](https://www.linkedin.com/company/nationwide-building-society)
- [About](https://www.nationwide.co.uk/about-us)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
