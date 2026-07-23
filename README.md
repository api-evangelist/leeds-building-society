# Leeds Building Society (leeds-building-society)

Leeds Building Society is the fifth-largest building society in the United Kingdom, a mutual owned by and run for the benefit of its members rather than shareholders. Founded in 1875 and headquartered in Leeds, West Yorkshire, it holds over GBP 31 billion in assets and serves more than 991,000 members, focusing on savings and residential mortgages rather than current accounts. It is authorised by the Prudential Regulation Authority (PRA) and regulated by the Financial Conduct Authority (FCA) and the PRA.

Because Leeds Building Society does not provide payment or current accounts, it is **not** one of the CMA9 mandated banks and is **not** an Account Servicing Payment Service Provider (ASPSP) under PSD2 / UK Open Banking. It participates in Open Banking as a **data consumer** — for example using Experian Boost and Account Information data to speed mortgage affordability decisions — rather than as an API provider. As of this profile it publishes no public developer portal, no OBIE Open Data endpoint, and no OBIE Read/Write APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/leeds-building-society/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/leeds-building-society/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Building Society
- Mutual
- Savings
- Mortgages
- Open Banking
- PSD2
- OBIE
- United Kingdom

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

The entries below represent the **shared UK Open Banking (OBIE) standard specifications** that an FCA-authorised ASPSP would conform to. They are captured as standard references, **not** as Leeds Building Society API contracts — Leeds Building Society does not currently publish any of these APIs, and no live base URL was confirmed for this bank.

### OBIE Open Data API (shared standard)

The UK Open Banking Open Data API standard for public, unauthenticated reference data — ATM and branch locations, personal and business current accounts, unsecured SME loans, and commercial credit cards. Shared OBIE standard, not a Leeds Building Society contract; no live Open Data endpoint was confirmed for this bank.

- **Human URL:** [https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

#### Tags

- Open Data
- OBIE
- Reference Data

#### Properties

- [OpenAPI](openapi/obie-opendata-standard-swagger.json) — [OpenAPI/Swagger 2.0](https://spec.openapis.org/oas/latest.html) (shared OBIE Open Data standard, v1.3)
- [Documentation](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)
- [API Reference](https://github.com/OpenBankingUK/opendata-api-specs)

### OBIE Account and Transaction Information API (AIS, shared standard)

The OBIE Read/Write Account and Transaction Information (AIS) standard for retrieving account, balance, transaction, and beneficiary data with customer consent, secured with FAPI-grade OAuth2/OIDC, mutual-TLS, and PSD2 strong customer authentication. Shared standard reference; Leeds Building Society does not offer current accounts and does not publish this API.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Account Information
- AIS
- OBIE
- FAPI

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### OBIE Payment Initiation API (PIS, shared standard)

The OBIE Read/Write Payment Initiation (PIS) standard for initiating domestic, scheduled, standing-order, international, and file payments with customer consent, secured with FAPI OAuth2/OIDC, mutual-TLS, and PSD2 SCA. Shared standard reference; Leeds Building Society is not a payment account provider and does not publish this API.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Payment Initiation
- PIS
- OBIE
- FAPI

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### OBIE Confirmation of Funds API (CBPII, shared standard)

The OBIE Read/Write Confirmation of Funds (CBPII) standard for confirming whether funds are available on a payment account, secured with FAPI OAuth2/OIDC, mutual-TLS, and PSD2 SCA. Shared standard reference; Leeds Building Society does not operate payment accounts and does not publish this API.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Confirmation of Funds
- CBPII
- OBIE
- FAPI

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

## Common Properties

- [Website](https://www.leedsbuildingsociety.co.uk/)
- [Support](https://www.leedsbuildingsociety.co.uk/help-and-contact/)
- [Blog / Newsroom](https://www.leedsbuildingsociety.co.uk/newsroom/)
- [Terms of Service](https://www.leedsbuildingsociety.co.uk/legal-notice-and-website-terms-of-use/)
- [Privacy Policy](https://www.leedsbuildingsociety.co.uk/security/use-of-personal-information/)
- [Security](https://www.leedsbuildingsociety.co.uk/security/)
- [LinkedIn](https://www.linkedin.com/company/leeds-building-society)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
