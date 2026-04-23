# Capital.com Public API (capital-com-public-api)
Capital.com is a European trading platform offering CFDs across shares, indices, commodities, forex, and cryptocurrencies. The Capital.com Public API provides direct access to the trading engine for automated strategies, giving programmatic control of positions, working orders, account preferences, and historical and streaming market data. A companion WebSocket API streams real-time prices and OHLC candles for up to 40 concurrent instruments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/capital-com-public-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
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

## APIs

### Capital.com REST API
The Capital.com REST API provides programmatic access to positions, working orders, deal confirmations, account information, account switching, transaction history, preferences, market navigation, instrument details, historical prices, watchlists, and client sentiment data. Authentication uses an API key plus login credentials to create a session that returns CST and X-SECURITY-TOKEN headers, which expire after 10 minutes of inactivity.

**Human URL:** [https://open-api.capital.com](https://open-api.capital.com)

#### Features

- Session-based authentication with CST and X-SECURITY-TOKEN
- Position management (open, update, close)
- Working orders (limit and stop)
- Deal confirmations and execution tracking
- Account switching across multiple accounts
- Transaction and activity history
- Leverage and hedging-mode preferences
- Demo account balance adjustment for testing
- Market navigation hierarchy
- Historical price data (OHLC)
- Client sentiment data
- Watchlist management

#### Use Cases

- Building automated CFD trading strategies
- Algorithmic execution across shares, forex, commodities, indices, and crypto
- Copy-trading and signal-provider applications
- Portfolio and risk dashboards
- Backtesting against historical price data
- Sentiment-driven trading signals

### Capital.com WebSocket API
The Capital.com WebSocket API streams real-time market data, supporting up to 40 concurrent instruments and OHLC candlestick subscriptions for low-latency trading applications.

**Human URL:** [https://open-api.capital.com](https://open-api.capital.com)

#### Features

- Real-time price streaming via WebSocket
- Up to 40 concurrent instrument subscriptions
- OHLC candlestick streaming
- Low-latency market data for trading systems

## Common Properties

- [Website](https://capital.com/)
- [Documentation](https://open-api.capital.com)
- [Sandbox](https://demo-api-capital.backend-capital.com/)
- [Privacy Policy](https://capital.com/privacy-policy)
- [Terms of Service](https://capital.com/terms-and-conditions)

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
