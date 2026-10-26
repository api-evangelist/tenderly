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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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
