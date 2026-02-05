# Aqua0

**A shared, non-custodial liquidity layer across chains.**  
Built on [1inch Aqua](https://1inch.com/aqua)'s virtual liquidity model—capital stays in your control while working across multiple chains and strategies.

---

## The problem

DeFi liquidity is fragmented across chains and pools. Even when TVL is high, **most LP capital is idle**: locked in one place, on one chain, in one strategy. Cross-chain volume is real ($300B+ in 2024), but infrastructure moves tokens—it doesn't make LP capital work more efficiently.

## The idea

Aqua0 brings **execution to liquidity** instead of moving liquidity into custodial pools:

- **Non-custodial** — Users keep control of their funds; the protocol tracks virtual balances.
- **Virtual liquidity** — The same capital can be allocated across multiple strategies and chains.
- **Cross-chain** — Execution is coordinated so liquidity serves demand wherever it happens (LayerZero, Stargate).
- **Intent-based** — Traders declare intents; LPs can choose which operations to back.

So: **one balance, multiple strategies, multiple chains, no custody.**

## What it enables

| Who             | Benefit                                                                                                                                             |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **LPs**         | One balance backs multiple strategies across chains; better capital efficiency and fee capture without traditional AMM custody or impermanent loss. |
| **Traders**     | Cross-chain swaps with less friction and slippage, from a single interface.                                                                         |
| **Integrators** | Quotes, swaps, and status via a small surface: quote → execute → status.                                                                            |

---

## Getting started

- **New to Aqua0?**  
  → [Product overview](https://docs.aqua0.xyz/docs/product/overview) · [How it works](https://docs.aqua0.xyz/docs/product/how-it-works) · [Landing page](https://aqua0.xyz) (when deployed)

- **Integrating (quotes, swaps, status)?**  
  → [Developer quickstart](https://docs.aqua0.xyz/docs/developers/quickstart) · [Integration guide](https://docs.aqua0.xyz/docs/developers/integration)

- **Security & trust**  
  → [Non-custodial design](https://docs.aqua0.xyz/docs/security/non-custodial) · [Risks & disclosures](https://docs.aqua0.xyz/docs/security/risks)

---

## Documentation

| Resource                | Link                                                                 |
| ----------------------- | -------------------------------------------------------------------- |
| **Docs site**           | [docs.aqua0.xyz](https://docs.aqua0.xyz)                             |
| **LLM-friendly export** | [docs.aqua0.xyz/llms-full.txt](https://docs.aqua0.xyz/llms-full.txt) |

Sections: **Product** (overview, how it works, economics, roadmap) · **Developers** (quickstart, integration, status & errors) · **Security** (non-custodial, risks, audits) · **Company** (mission, traction, team).

---

## Traction

- **ETHGlobal Buenos Aires** — Finalist; highlighted by 1inch and LayerZero.
- **Ecosystem** — Built on 1inch Aqua; in dialogue with 1inch, LayerZero, Arbitrum, Base.

---

## Tech at a glance

- **Contracts:** Solidity, Foundry, ERC-4337, 1inch Aqua, LayerZero/Stargate.
- **Backend:** TypeScript, Bun, Ponder (indexer), Supabase (Postgres), Redis.
- **Frontend:** Next.js 16, TypeScript, Tailwind, Radix/shadcn, wagmi, RainbowKit.
- **Docs:** Next.js, Fumadocs, MDX.

---

## License

Smart contracts and protocol code are intended for audit and public use under the terms specified in our documentation and releases.
