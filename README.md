# Zeller (zeller)

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

Zeller is a Melbourne-founded Australian payments and business banking company (founded 2020 by former Square Australia executives Ben Pfisterer and Dominic Yap) that gives SMEs an integrated stack of card payment acceptance, a transaction account, a Mastercard debit card, and financial management tools in one place. As a merchant acquirer it processes in-person and online card payments (Visa, Mastercard, eftpos, American Express, JCB, Apple Pay, Google Wallet) across its Zeller Terminal hardware, Tap to Pay on mobile, and online checkout, positioning itself against Square and fellow Australian acquirer Tyro.

Zeller runs a genuine first-party developer program — the **Zeller Developer Suite** — but its reference documentation and API artifacts are gated behind a free developer account. The developer portal authenticates through an Auth0 (OAuth2 / OpenID Connect) tenant, and no OpenAPI specification is published for anonymous download.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zeller/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zeller/refs/heads/main/apis.yml)

## Tags

- Payments
- Australia
- Payment Gateway
- Payment Processing
- Acquiring
- Merchant Services
- Point of Sale
- In-Person Payments
- Tap to Pay
- SME

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Zeller Terminal API

Connect point-of-sale software directly to Zeller Terminal hardware to initiate and manage in-person card payments. Delivered through the Zeller Payments SDK (React, React Native, Windows .NET, Android, iOS).

- **Human URL:** [https://www.myzeller.com/au/developer-suite](https://www.myzeller.com/au/developer-suite)

#### Properties

- [Documentation](https://www.myzeller.com/au/developer-suite)
- [API Reference](https://developer.myzeller.com/) — gated behind a free developer account
- [Sign Up](https://developer.myzeller.com/)

### Zeller Online Payments API

Accept payments inside web and mobile apps via Zeller's Online integration. Part of the Zeller Developer Suite; full API documentation is available by request behind a free developer account.

- **Human URL:** [https://www.myzeller.com/au/developer-suite](https://www.myzeller.com/au/developer-suite)

#### Properties

- [Documentation](https://www.myzeller.com/au/developer-suite)
- [API Reference](https://developer.myzeller.com/) — gated behind a free developer account
- [Sign Up](https://developer.myzeller.com/)

### Zeller Tap to Pay API

Accept contactless card and mobile-wallet payments on a phone with no separate terminal, integrated through the Zeller Payments SDK.

- **Human URL:** [https://www.myzeller.com/au/developer-suite](https://www.myzeller.com/au/developer-suite)

#### Properties

- [Documentation](https://www.myzeller.com/au/developer-suite)
- [API Reference](https://developer.myzeller.com/) — gated behind a free developer account
- [Sign Up](https://developer.myzeller.com/)

## Developer Program Notes

- **Developer portal:** [https://developer.myzeller.com/](https://developer.myzeller.com/) — live but gated (Auth0 login).
- **Auth model:** OAuth2 / OpenID Connect via Auth0 (`auth.developer.myzeller.com`); authorization_code, client_credentials, and device_code grants advertised, with PKCE (S256).
- **SDKs:** Zeller Payments SDK for React, React Native, Windows .NET, Android, iOS.
- **Downloadable specs:** none published anonymously (OpenAPI/GraphQL/Postman not retrievable without a developer account).
- **eCommerce** payment gateway is marked "Coming soon" on the developer-suite page and is not yet listed as a live API here.

## Common Properties

- [Website](https://www.myzeller.com/au)
- [Developer Portal](https://developer.myzeller.com/)
- [Documentation](https://www.myzeller.com/au/developer-suite)
- [Sign Up](https://developer.myzeller.com/)
- [Pricing](https://www.myzeller.com/au/pricing)
- [Blog](https://www.myzeller.com/au/blog)
- [Support](https://www.myzeller.com/au/support)
- [Terms of Service](https://www.myzeller.com/au/terms)
- [Privacy Policy](https://www.myzeller.com/au/privacy)
- [GitHub Organization](https://github.com/myzeller)
- [LinkedIn](https://au.linkedin.com/company/zeller)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
