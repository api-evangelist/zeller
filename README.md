# Zeller (zeller)

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
