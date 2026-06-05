# Capital.com Public API (capital-com-public-api)

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
