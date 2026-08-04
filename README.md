# Capital.com Public API (capital-com-public-api)

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

Capital.com is a European trading platform offering CFDs across shares, indices, commodities, forex, and cryptocurrencies. The Capital.com Public API provides direct access to the trading engine for automated strategies, giving programmatic control of positions, working orders, account preferences, and historical and streaming market data. A companion WebSocket API streams real-time prices and OHLC candles for up to 40 concurrent instruments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/capital-com-public-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/capital-com-public-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CFD
- Commodities
- Cryptocurrency
- Financial
- Forex
- Indices
- Market Data
- Shares
- Streaming
- Trading
- WebSocket

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-29

## APIs

### Capital.com REST API

The Capital.com REST API provides programmatic access to positions, working orders, deal confirmations, account information, account switching, transaction history, preferences (leverage, hedging mode), market navigation, instrument details, historical prices, watchlists, and client sentiment data. Authentication uses an API key plus login credentials to create a session that returns CST and X-SECURITY-TOKEN headers, which expire after 10 minutes of inactivity.

- **Human URL:** [https://open-api.capital.com](https://open-api.capital.com)

#### Tags

- CFD
- Financial
- Market Data
- Trading

#### Properties

- [Documentation](https://open-api.capital.com)
- [Base  U R L](https://api-capital.backend-capital.com/)
- [Sandbox](https://demo-api-capital.backend-capital.com/)
- [Authentication](https://open-api.capital.com)
- [OpenAPI](openapi/capital-com-public-api-capital-com-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/capital-com-public-api-capital-com-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/capital-com-public-api-capital-com-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Capital.com WebSocket API

The Capital.com WebSocket API streams real-time market data, supporting up to 40 concurrent instruments and OHLC candlestick subscriptions for low-latency trading applications.

- **Human URL:** [https://open-api.capital.com](https://open-api.capital.com)

#### Tags

- Market Data
- Streaming
- Trading
- WebSocket

#### Properties

- [Documentation](https://open-api.capital.com)
- [AsyncAPI](asyncapi/capital-com-public-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/capital-com-public-api-capital-com-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/capital-com-public-api-capital-com-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/capital-com-sv)
- [LinkedIn](https://www.linkedin.com/company/capitalcom)
- [Website](https://capital.com/)
- [Documentation](https://open-api.capital.com)
- [Sandbox](https://demo-api-capital.backend-capital.com/)
- [Privacy Policy](https://capital.com/privacy-policy)
- [Terms of Service](https://capital.com/terms-and-conditions)
- [Support](https://capital.com/help)
- [Blog](https://capital.com/news-and-analysis)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
