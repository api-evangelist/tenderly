# Tenderly

Tenderly is a Web3 development platform providing smart contract debugging, transaction simulation, virtual test environments, production-grade node RPC infrastructure, real-time alerting, serverless Web3 Actions, and gas profiling across 80+ EVM-compatible blockchain networks.

## APIs

| API | Description | Docs |
|-----|-------------|------|
| Tenderly REST API | Core REST API for projects, simulations, alerts, contracts, wallets, and Web3 Actions | [Docs](https://docs.tenderly.co/reference/api) |
| Simulation API | Dry-run transactions before execution with decoded traces, gas estimates, and balance changes | [Docs](https://docs.tenderly.co/simulations) |
| Virtual TestNets REST API | Create and manage production-mirroring virtual blockchain environments | [Docs](https://docs.tenderly.co/virtual-testnets/develop/rest-api) |
| Node RPC | Production JSON-RPC across 80+ EVM networks with debug/trace support | [Docs](https://docs.tenderly.co/node) |
| Alerts API | On-chain event monitoring with routing to Slack, webhooks, PagerDuty, and more | [Docs](https://docs.tenderly.co/alerts) |
| Web3 Actions API | Deploy serverless JS/TS functions triggered by on-chain events | [Docs](https://docs.tenderly.co/web3-actions) |

## Authentication

All REST API requests require an `X-Access-Key` header. Generate an access token from the Tenderly dashboard under Organization Settings > Access Tokens.

Base URL: `https://api.tenderly.co/api/v2`

## Pricing

Tenderly uses a consumption-based model measured in Tenderly Units (TU). The Free plan provides dashboard access and UI-only simulation. Paid Console plans include full API access and are custom-priced per contract based on networks, capacity, support, and history retention.

- [Pricing](https://tenderly.co/pricing)
- [Node RPC pricing details](https://docs.tenderly.co/node/pricing)

## Links

- [Website](https://tenderly.co)
- [Documentation](https://docs.tenderly.co)
- [GitHub](https://github.com/tenderly)
- [CLI](https://github.com/Tenderly/tenderly-cli)
- [Status](https://status.tenderly.co)
- [Blog](https://blog.tenderly.co)
- [Discord](https://discord.gg/fBvDJYR)

## Contact

- [Support](https://tenderly.co/contact)
- [Sales](https://tenderly.co/contact)
