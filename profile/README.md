# Aqua0

**Liquidity infrastructure for stablecoin issuers.**
One deposit, liquidity everywhere.

A stablecoin is only as strong as its liquidity. Aqua0 puts a single deposit to work across
multiple pools and chains at once, about 9x more capital-efficient than a traditional AMM position,
without giving up custody.

---

## The problem

DeFi liquidity is fragmented across chains and pools. Even when total value locked is high, most LP
capital sits idle: parked in one place, on one chain, in one strategy. For a stablecoin issuer, thin
or scattered liquidity is an existential risk. A peg only holds where there is depth to defend it.

## The idea

Aqua0 brings execution to liquidity instead of moving liquidity into custodial pools.

- **Non-custodial.** Your capital stays in your control inside the protocol's on-chain vaults. LPs
  keep control of their funds while Aqua0 coordinates execution to where liquidity is needed, under
  rules anyone can verify on-chain.
- **A shared pool, per asset.** Deposits flow into a fleet of per-asset vaults that are run together
  as one shared pool, so a single deposit can back liquidity across many venues and chains at the
  same time.
- **Cross-chain.** Liquidity serves demand wherever it happens. Positions and settlement are
  coordinated across chains over Across as the primary bridge.
- **Intent-based.** Traders declare intents, and LPs choose which strategies to back, from
  concentrated and stable curves to custom strategies written as Uniswap V4 hooks.

The result: one deposit, backing liquidity across pools and chains, with no loss of custody.

## What it enables

| Who                      | Benefit                                                                                                                                        |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Stablecoin issuers**   | Deep, defensible liquidity for your token across chains from a single deposit, so the peg is backed everywhere your users are.                  |
| **Liquidity providers**  | One deposit backs many strategies and chains at once: stronger capital efficiency and fee capture, without traditional AMM custody.             |
| **Integrators**          | Quotes, execution, and status over a small surface: quote, execute, status.                                                                     |

## Where it runs

Aqua0's mainnet beta spans five chains: **Base, Avalanche, Arbitrum, Celo, and Monad.** The beta is
private and deposit-capped as it opens, and a testnet is available to try today.

---

## Getting started

- **New to Aqua0?**
  Product overview and how it works at [docs.aqua0.xyz](https://docs.aqua0.xyz), or see the
  [landing page](https://aqua0.xyz).

- **Want in?**
  Join the private mainnet beta at [aqua0.xyz/mainnet-beta](https://aqua0.xyz/mainnet-beta), or try
  the [testnet](https://app.aqua0.xyz).

- **Integrating (quotes, execution, status)?**
  Developer quickstart and integration guide at [docs.aqua0.xyz](https://docs.aqua0.xyz).

## Documentation

| Resource                | Link                                                                 |
| ----------------------- | -------------------------------------------------------------------- |
| **Docs site**           | [docs.aqua0.xyz](https://docs.aqua0.xyz)                             |
| **LLM-friendly export** | [docs.aqua0.xyz/llms-full.txt](https://docs.aqua0.xyz/llms-full.txt) |

---

## Backed by

- **1inch.** Selected for the 1inch Aqua Incubator with a $50K grant to build cross-chain shared
  liquidity infrastructure.
- **Uniswap (2x).** Incubated in the Uniswap Foundation Hook Incubator, where we built our V4 hook,
  then accelerated by the Uniswap Foundation with a Uniswap X API integration.
- **ETHGlobal (2x).** Finalists at ETHGlobal Buenos Aires, where Aqua0 was born, then selected as
  one of four teams worldwide for ETHGlobal Spotlight NYC.
- **Angels.** Backed by angels from top protocols, including Sergej Kunz (co-founder of 1inch) and
  team members from Altitude.

## Team

- **Tomas Mazzitello.** CEO. Six years in DeFi; ex-Rather Labs (PM for NEAR Protocol and Solv).
- **Rithik Kumar.** CPO / COO. Creator of Dira, a Dirham-pegged stablecoin.
- **Yudhishthra Sugumaran.** CTO. Ex-Nethermind and Etherscan.

---

## Tech at a glance

- **Contracts:** Solidity, Foundry, Uniswap V4 hooks, 1inch Aqua, ERC-4337 account abstraction,
  ERC-7540 async redeem, Across for cross-chain settlement.
- **Backend:** TypeScript, Bun, Ponder (indexer), Postgres, Redis.
- **Frontend:** Next.js, TypeScript, Tailwind, wagmi.
- **Docs:** Next.js, Fumadocs, MDX.

## Community

- **X:** [@AquaZero0](https://x.com/AquaZero0)
- **Telegram:** [Join the community](https://t.me/+eDStwZjBW6gyMjdh)

## License

Protocol and application code is released under the terms specified in our documentation and
releases.
