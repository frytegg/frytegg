# Alexandre Lemiere

Fintech engineering student at [ESILV](https://www.esilv.fr/) (Paris) — building trading systems, DeFi protocols, on-chain applications, and quantitative research on DeFi risk.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/alexandre-lemiere)

## Research

**[DeFi Peg Failure & Tracking Error — a research portfolio](https://frytegg.github.io/defi-depeg-research/)** ([repo](https://github.com/frytegg/defi-depeg-research))

16-week research internship (Derivalink, via Acensi) building an audited, from-scratch on-chain data pipeline across ~20 DeFi synthetic-asset protocols, then applying econometrics, machine learning, reinforcement learning and graph theory to how — and why — pegs fail. Twenty technical sub-reports plus one synthesis report, each backed by a full data audit and a pre-registered evaluation standard applied throughout — including a headline result that was internally audited and retracted, reported as plainly as the positive ones.

**Featured reports:**
- 📄 [Internship Report](https://raw.githubusercontent.com/frytegg/defi-depeg-research/main/reports/internship_report/Internship_Report_Alexandre_Lemiere.pdf) — the synthesis: methodology, 4 research questions, findings, design recommendations
- [MakerDAO — DAI](https://raw.githubusercontent.com/frytegg/defi-depeg-research/main/reports/maker/dai/main.pdf) — survived March 2020 *and* March 2023 SVB; during SVB its oracle bottomed at $0.889 while DAI traded at $0.828 on Curve, a 600+ bp gap invisible to a single oracle
- [Iron Finance — IRON/TITAN](https://raw.githubusercontent.com/frytegg/defi-depeg-research/main/reports/iron_finance/iron/main.pdf) — full forensic reconstruction of the June 2021 collapse (supply inflated ~335,000× in ~24h)
- [Systemic-risk graph theory (S9)](https://raw.githubusercontent.com/frytegg/defi-depeg-research/main/reports/graphs/s9_closing_report/main.pdf) — a from-scratch DebtRank model validated against 3 real historical collapses
- [IV-smirk gate report (S8)](https://raw.githubusercontent.com/frytegg/defi-depeg-research/main/reports/s8_iv_smirk/main.pdf) — the report with the retracted result: an audit found the exciting claim didn't hold up, so it was withdrawn

→ [Full index of all 20 sub-reports](https://frytegg.github.io/defi-depeg-research/)

## Tech

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat&logo=solidity&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Move](https://img.shields.io/badge/-Move-4A90D9?style=flat)
![Foundry](https://img.shields.io/badge/-Foundry-1C1C1C?style=flat&logo=ethereum&logoColor=white)
![Tokio](https://img.shields.io/badge/-Tokio-000000?style=flat&logo=rust&logoColor=white)

## Current projects

**Cross-venue sports/prediction-market arbitrage bot** (private repo)

Arbitrage engine spanning Polymarket (CLOB, Polygon), Azuro V3 (LP-backed vAMM, Polygon/Gnosis) and Overtime V2 (AMM, Optimism/Arbitrum/Base) — detects opportunities where the net edge after every friction (venue fees, size-aware slippage, gas, staleness, basis risk) is positive across two venues quoting the same event.

## Featured projects

| Project | Event | Result | Description |
|---------|-------|--------|-------------|
| [orma](https://github.com/BuzzBallz/orma) | **XRPL Lending Protocol 2026** (De Vinci Blockchain, Paris) | **1st place** | Solvency oracle for closed-ended XRPL lending vaults. The first recognised loss is invisible to every indexer that diffs transaction metadata, so a vault can read 1.00 while it holds 0.80; Orma reads the objects instead, publishes the grade as a native XLS-47 oracle object a second publisher can contest, and lets an XLS-70 credential gate who may subscribe. Shipped with a protocol paper and a 40-finding developer-experience report filed during the build. Three of those findings were reported on the closed-ended vault specification and [merged into XLS-65/66](https://github.com/XRPLF/XRPL-Standards/pull/587) the next day: two protocol constants that did not match the server, and a transactor missing from the permission matrix. A fourth finding was [accepted by a Ripple maintainer](https://github.com/XRPLF/xrpl-dev-portal/issues/3926) and turned into a documentation task. |
| [agentfi](https://github.com/BuzzBallz/agentfi) | **ETHDenver 2026** | **2nd place** — 0G Best DeFAI, **3rd place** - ADI Chain | Multi-chain marketplace for autonomous AI agents as iNFTs (ERC-7857), with payments on ADI Chain and orchestration via Hedera |
| [inflexion](https://github.com/frytegg/inflexion) | **Arbitrum Open House 2026** | | Trustless, fully-collateralized on-chain market for Uniswap v3 impermanent-loss risk. Fair value priced on-chain via a closed-form Arbitrum Stylus (Rust) oracle; a cvAMM floor and competing market makers route to whichever is cheaper. Full stack: contracts, SDK, REST API, subgraph, frontend. My most-developed solo project — the one with the most real design work behind it. |
| [sui-shield](https://github.com/frytegg/sui-shield) | EPFL SUI 2025 | | Decentralized gas fee insurance marketplace on Sui |
| [tokena](https://github.com/frytegg/tokena) | XRPL Rome 2025 | **4th place** | XRPL multi-party token issuance & management |

## Other projects

| Project | Description | Stack |
|---------|-------------|-------|
| [crypto-portfolio-management](https://github.com/frytegg/crypto-portfolio-management) | Multi-strategy crypto portfolio optimization dashboard — 7 allocation strategies, GJR-GARCH volatility, HMM regime detection, on-chain signals, walk-forward backtesting, real-time Binance prices | Python, Plotly Dash |
| [funding-engine](https://github.com/frytegg/funding-engine) | Delta-neutral funding rate arbitrage across CEX/DEX (Bybit, Hyperliquid) | TypeScript |
| Polymarket BTC Up/Down trading system *(private)* | Hybrid algorithmic trading system for Polymarket's BTC Up/Down binary options — Black-Scholes fair value vs. Binance/Chainlink feeds; taker mode (Fill-and-Kill) and market making (Avellaneda-Stoikov) | TypeScript |
| [spark-base](https://github.com/frytegg/spark-base) | Competitive on-chain mini-games platform on Base — players earn ARK tokens, stakes escrowed on-chain (Base Batches 2025 Hackathon) | Solidity, Node.js, React |
| [blackjack-strategy-studio](https://github.com/frytegg/blackjack-strategy-studio) | Optimal blackjack strategy table generator with rules-aware engine | Python, React |
| [ask-starknet-bot](https://github.com/frytegg/ask-starknet-bot) | Starknet Q&A bots for Telegram, Discord, and X using LangGraph + MCP | Python |
| [rust-port-scanner](https://github.com/frytegg/rust-port-scanner) | Multi-threaded TCP port scanner | Rust |
| [build-your-own-git](https://github.com/frytegg/build-your-own-git) | Minimal git implementation — init, hash-object, cat-file, ls-tree, write-tree, commit-tree (CodeCrafters challenge) | Rust |
