# The Graph (the-graph)

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

The Graph is a decentralized blockchain data indexing protocol. It exposes Subgraphs (GraphQL APIs over indexed on-chain data), Substreams (parallel streaming dataflows), the Token API (REST/MCP for token data), and supports 80+ chains. Self-hosted Graph Node and Firehose are open-source.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/the-graph/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/the-graph/refs/heads/main/apis.yml)

## Tags

- Web3
- Indexing
- GraphQL
- Subgraphs
- Multi-chain

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### The Graph Subgraphs (GraphQL)

Per-subgraph GraphQL endpoints served by the decentralized network of Indexers. Each subgraph defines its own schema; queries are billed in GRT or via a hosted gateway in USD.

- **Human URL:** [https://thegraph.com/docs/en/subgraphs/querying/introduction/](https://thegraph.com/docs/en/subgraphs/querying/introduction/)
- **Base URL:** `https://gateway.thegraph.com/api/{apiKey}/subgraphs/id/{subgraphId}`

#### Tags

- GraphQL
- Subgraphs
- Decentralized

#### Properties

- [Documentation](https://thegraph.com/docs/en/subgraphs/querying/introduction/)
- [Postman Collection](collections/the-graph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-graph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### The Graph Token API

REST API for cross-chain token data (balances, holders, prices, transfers, metadata) with built-in MCP server for AI agents.

- **Human URL:** [https://thegraph.com/docs/en/token-api/quick-start/](https://thegraph.com/docs/en/token-api/quick-start/)
- **Base URL:** `https://token-api.thegraph.com`

#### Tags

- REST
- Tokens
- MCP

#### Properties

- [Documentation](https://thegraph.com/docs/en/token-api/quick-start/)
- [Postman Collection](collections/the-graph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-graph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### The Graph Substreams

gRPC streaming protocol for parallelized blockchain dataflows backed by Firehose. Substreams power high-throughput indexing pipelines.

- **Human URL:** [https://thegraph.com/docs/en/substreams/introduction/](https://thegraph.com/docs/en/substreams/introduction/)
- **Base URL:** `grpc://mainnet.eth.streamingfast.io:443`

#### Tags

- gRPC
- Streaming

#### Properties

- [Documentation](https://thegraph.com/docs/en/substreams/introduction/)
- [Postman Collection](collections/the-graph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-graph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Graph Node Admin JSON-RPC (self-hosted)

JSON-RPC admin interface to a self-hosted Graph Node for deploying, listing, and managing subgraphs. Public hosted-service is deprecated; this surface applies to self-managed indexers.

- **Human URL:** [https://github.com/graphprotocol/graph-node](https://github.com/graphprotocol/graph-node)
- **Base URL:** `http://{graph-node}:8020`

#### Tags

- JSON-RPC
- Admin

#### Properties

- [Documentation](https://github.com/graphprotocol/graph-node)
- [Postman Collection](collections/the-graph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-graph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Firehose

Open-source flat-file extraction layer that powers Substreams. Provides chain-specific gRPC streams of blocks and transactions.

- **Human URL:** [https://thegraph.com/docs/en/substreams/firehose/](https://thegraph.com/docs/en/substreams/firehose/)
- **Base URL:** `varies per chain`

#### Tags

- gRPC
- Streaming

#### Properties

- [Documentation](https://thegraph.com/docs/en/substreams/firehose/)
- [Postman Collection](collections/the-graph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-graph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/thegraph)
- [Website](https://thegraph.com/)
- [Plans](plans/the-graph-plans-pricing.yml)
- [Rate Limits](rate-limits/the-graph-rate-limits.yml)
- [Fin Ops](finops/the-graph-finops.yml)
- [L L Ms Txt](https://token-api.thegraph.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
