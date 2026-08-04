# Tenderly

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
