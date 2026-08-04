# Leeds Building Society (leeds-building-society)

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
