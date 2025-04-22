# Solana gRPC Streaming Examples (GS Node)

Welcome to the official collection of **Solana gRPC examples powered by [GS Node](https://gsnode.io)** — the fastest, lowest-latency RPC infrastructure for bots, snipers, dashboards, and dev tooling.

Each example is in its own GitHub repository, focused on **one specific use case**, with plug-and-play code in TypeScript.

> 💬 Need help or want to talk RPC performance? [Join our Discord](https://discord.gg/M8778yHKcV)

---

## Available gRPC Examples

| Use Case | Description | Link |
|----------|-------------|------|
| Subscribe to Slots | Stream every new Solana slot in real time. | [solana-grpc-subscribe-slots](https://github.com/gsnode/solana-grpc-subscribe-slots) |
| Subscribe to Account | Get updates when a specific account changes. | [solana-grpc-subscribe-account](https://github.com/gsnode/solana-grpc-subscribe-account) |
| Account with Data Slice | Listen to a slice of account data (e.g. token balance). | [solana-grpc-subscribe-account-slice](https://github.com/gsnode/solana-grpc-subscribe-account-slice) |
| Program-owned Accounts | Subscribe to all accounts owned by a program (e.g. OpenBook). | [solana-grpc-subscribe-program](https://github.com/gsnode/solana-grpc-subscribe-program) |
| Transaction Signature | Track a specific transaction by its signature. | [solana-grpc-subscribe-transaction-signature](https://github.com/gsnode/solana-grpc-subscribe-transaction-signature) |
| Finalized Transactions | Listen to every finalized transaction on-chain. | [solana-grpc-subscribe-all-finalized-transactions](https://github.com/gsnode/solana-grpc-subscribe-all-finalized-transactions) |
| Filtered Transactions | Include/exclude accounts in transaction filters (e.g. Serum only). | [solana-grpc-subscribe-transaction-filtered](https://github.com/gsnode/solana-grpc-subscribe-transaction-filtered) |
| Block Events | Subscribe to block production (slot-level). | [solana-grpc-subscribe-blocks](https://github.com/gsnode/solana-grpc-subscribe-blocks) |
| Block Metadata | Lightweight block metadata stream (leader, slot, timestamp). | [solana-grpc-subscribe-blocks-meta](https://github.com/gsnode/solana-grpc-subscribe-blocks-meta) |
| Entry Stream | Raw low-level entry stream for validators or research. | [solana-grpc-subscribe-entry](https://github.com/gsnode/solana-grpc-subscribe-entry) |

---

## Requirements

Each repo uses:
- Node.js `v18+`
- TypeScript
- `@grpc/grpc-js` + `protobufjs`

Just clone any repo, run `npm install`, and launch with `ts-node`.

---

## 🔗 About GS Node

[GS Node](https://gsnode.io) provides Solana developers with ultra-fast RPC infrastructure optimized for real-time use cases:
- gRPC support
- MEV bots
- Sniping tools
- DEX dashboards
- Validator observability
