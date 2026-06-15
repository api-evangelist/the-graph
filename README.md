# The Graph (the-graph)

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
