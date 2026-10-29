# BloFin

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

BloFin is a cryptocurrency exchange offering spot, perpetual futures and copy trading. Its public Open API (base https://openapi.blofin.com, demo https://demo-trading-openapi.blofin.com) exposes REST endpoints for public market data, account, trading, asset management, affiliate and copy trading, plus public and private WebSocket channels, authenticated with ACCESS-KEY / ACCESS-SIGN HMAC-signed headers; a separate OAuth broker API runs at oauth.blofin.com. BloFin also publishes an official MCP server (blofin-mcp), an agent-first CLI (blofin-cli), a Python SDK and an agent skills hub on GitHub. Surfaced via the API Evangelist harvest backlog (source: market-gap:crypto-exchanges).

**Areas:** Company · Cryptocurrency · Cryptocurrency Exchange · Trading · Futures · Spot Trading · Copy Trading · WebSocket

## BloFin on APIs.io

Everything profiled for BloFin is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/blofin/](https://apis.io/providers/blofin/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [BloFin Broker API](https://apis.io/apis/blofin/blofin-broker-api/) — OAuth-based broker API at oauth.blofin.com for brokers to obtain tokens and user info, create API keys on a user's behalf and query deposit addresses and…
- [BloFin WebSocket API](https://apis.io/apis/blofin/blofin-websocket-api/) — Public and private WebSocket channels for futures (wss://openapi.blofin.com/ws/public, /ws/private), spot (/ws/spot/public, /ws/spot/private) and copy…
- [BloFin Account API](https://apis.io/apis/blofin/blofin-account-api/) — The Account API from BloFin — 12 operation(s) for account.
- [BloFin Affiliate API](https://apis.io/apis/blofin/blofin-affiliate-api/) — The Affiliate API from BloFin — 6 operation(s) for affiliate.
- [BloFin Asset API](https://apis.io/apis/blofin/blofin-asset-api/) — The Asset API from BloFin — 9 operation(s) for asset.
- [BloFin Copytrading API](https://apis.io/apis/blofin/blofin-copytrading-api/) — The Copytrading API from BloFin — 23 operation(s) for copytrading.
- [BloFin Market API](https://apis.io/apis/blofin/blofin-market-api/) — The Market API from BloFin — 12 operation(s) for market.
- [BloFin OAuth API](https://apis.io/apis/blofin/blofin-oauth-api/) — The Oauth API from BloFin — 6 operation(s) for oauth.
- [BloFin Spot API](https://apis.io/apis/blofin/blofin-spot-api/) — The Spot API from BloFin — 18 operation(s) for spot.
- [BloFin Trade API](https://apis.io/apis/blofin/blofin-trade-api/) — The Trade API from BloFin — 23 operation(s) for trade.
- [BloFin User API](https://apis.io/apis/blofin/blofin-user-api/) — The User API from BloFin — 1 operation(s) for user.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [BloFin MCP Server](https://apis.io/servers/blofin/blofin-mcp-server/)

#### JSON Schema (6)

The data models the API reads and writes.

- [GetApiV1AffiliateInviteesResponse](https://apis.io/schemas/blofin/blofin-get-api-v1-affiliate-invitees-response/)
- [GetApiV1CopytradingTradeOrdersPendingResponse](https://apis.io/schemas/blofin/blofin-get-api-v1-copytrading-trade-orders-pending-response/)
- [GetApiV1TradeOrdersHistoryResponse](https://apis.io/schemas/blofin/blofin-get-api-v1-trade-orders-history-response/)
- [PostApiV1TradeBatchOrdersRequest](https://apis.io/schemas/blofin/blofin-post-api-v1-trade-batch-orders-request/)
- [PostApiV1TradeOrderRequest](https://apis.io/schemas/blofin/blofin-post-api-v1-trade-order-request/)
- [PostApiV1TradeOrderTpslRequest](https://apis.io/schemas/blofin/blofin-post-api-v1-trade-order-tpsl-request/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Blofin Context](https://apis.io/jsonld/blofin/blofin-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [BloFin API Rules](https://apis.io/rules/blofin/blofin-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Blofin Authentication](https://apis.io/security/blofin/blofin-authentication/)
- [Blofin Domain Security](https://apis.io/security/blofin/blofin-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Blofin Plans Pricing](https://apis.io/plans/blofin/blofin-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Blofin Rate Limits](https://apis.io/rate-limits/blofin/blofin-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://blofin.com)
- [Documentation](https://docs.blofin.com/index.html)
- [API reference](https://docs.blofin.com/index.html)
- [Support](https://support.blofin.com/hc/en-us)
- [Changelog](https://docs.blofin.com/changelog.html)
- [GitHub](https://github.com/blofin)

## API Evangelist rating

**Kin Score 34.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 25.9 |
| Contract governance | 22.0 |
| Operational transparency | 52.6 |
| Developer ergonomics | 54.8 |
| Access clarity | 0.0 |

**Agent readiness 34.7** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | verified |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/blofin/](https://apis.io/providers/blofin/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for BloFin: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/blofin/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
