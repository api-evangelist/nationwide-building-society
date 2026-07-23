# Nationwide Building Society (nationwide-building-society)

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
