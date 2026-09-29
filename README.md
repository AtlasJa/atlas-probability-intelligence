# Atlas Probability Intelligence

Machine-readable **Bitcoin (BTC) 60-minute probability intelligence** for autonomous agents, developers, and x402 workflows.
👉 [Quickstart: test and integrate the live Atlas x402 endpoint](QUICKSTART.md)
## Live Product

**Price:** $0.01 per request  
**Payment:** x402 V2 on Base / USDC  
**Production endpoint:**  
https://atlas-probability-api-production.up.railway.app/v1/x402/probability/BTC

Unpaid requests return HTTP `402 Payment Required` with machine-readable payment instructions. After valid payment, the endpoint returns the protected probability response.

## What Atlas Returns

Atlas provides machine-readable BTC probability intelligence including:

- Probability BTC finishes **above** the current price
- Probability BTC finishes **below** the current price
- Supported upside/downside threshold probabilities
- Terminal price distribution information
- Expected terminal return
- Forecast timestamp and freshness
- Model metadata

Atlas is designed as a probabilistic input for an existing agent, dashboard, market-data workflow, alerting system, or research process.

## Intended Integrations

Atlas can complement:

- Autonomous agents
- x402 payment clients
- Crypto dashboards
- BTC alerting systems
- Market-data APIs
- MCP tools
- Quantitative and research workflows
- Signal aggregation and consensus systems

## Current Validated Commercial Scope

- Asset: **BTC**
- Forecast horizon: **60 minutes / 1 hour**
- Price: **$0.01/request**
- Network: **Base**
- Payment asset: **USDC**
- Access: **x402 V2**

Additional assets, shorter horizons, seasonal intelligence, regime/downside intelligence, and other products remain research or future expansion unless separately documented as production-ready.

## Important

Atlas outputs probabilistic model estimates, not investment advice, trading commands, or guaranteed outcomes. Users and autonomous systems decide how to use the information.

## Contact

GitHub: **@AtlasJa**

For integration questions, open an issue in this repository.
