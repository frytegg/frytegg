# Alexandre Lemiere

Fintech engineering student at [ESILV](https://www.esilv.fr/) (Paris) — building trading systems, DeFi protocols, on-chain applications, and quantitative research on DeFi risk.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/alexandre-lemiere)

## Research

**[DeFi Peg Failure & Tracking Error — a research portfolio](https://frytegg.github.io/defi-depeg-research/)** ([repo](https://github.com/frytegg/defi-depeg-research))

16-week research internship (Derivalink, via Acensi) building an audited, from-scratch on-chain data pipeline across ~20 DeFi synthetic-asset protocols, then applying econometrics, machine learning, reinforcement learning and graph theory to how — and why — pegs fail. Twenty technical sub-reports plus one synthesis report, each backed by a full data audit and a pre-registered evaluation standard applied throughout — including a headline result that was internally audited and retracted, reported as plainly as the positive ones.

**Featured reports:**
- 📄 [Internship Report](https://raw.githubusercontent.com/frytegg/defi-depeg-research/main/reports/internship_report/Internship_Report_Alexandre_Lemiere.pdf) — the synthesis: methodology, 4 research questions, findings, design recommendations
- [MakerDAO — DAI](https://raw.githubusercontent.com/frytegg/defi-depeg-research/main/reports/maker/dai/main.pdf) — survived March 2020 *and* March 2023 SVB; a 697bp oracle-vs-market gap invisible to a single oracle
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

## Current project

**Polymarket BTC Binary Options Trading System** (private repos)

Hybrid algorithmic trading system for Polymarket's BTC Up/Down binary options, combining Black-Scholes pricing with real-time Binance/Chainlink oracle feeds. Two strategy implementations:
- **Taker mode** — exploits pricing lag between Binance and Polymarket via Fill-and-Kill orders
- **Market making** — Avellaneda-Stoikov model with adverse selection risk management

Next steps: migrate to new 5-minute BTC Up/Down markets, finalize market making with lateral perp hedging.

## Hackathon projects

| Project | Event | Result | Description |
|---------|-------|--------|-------------|
| [agentfi](https://github.com/BuzzBallz/agentfi) | **ETHDenver 2026** | **2nd place** — 0G Best DeFAI, **3rd place** - ADI Chain | Multi-chain marketplace for autonomous AI agents as iNFTs (ERC-7857), with payments on ADI Chain and orchestration via Hedera |
| [sui-shield](https://github.com/frytegg/sui-shield) | EPFL SUI 2025 | | Decentralized gas fee insurance marketplace on Sui |
| [spark-base](https://github.com/frytegg/spark-base) | Base Batches 2025 | | Competitive on-chain mini-games with ARK token rewards |
| [tokena](https://github.com/frytegg/tokena) | XRPL Rome 2025 | **4th place** | XRPL multi-party token issuance & management |

## Other projects

| Project | Description | Stack |
|---------|-------------|-------|
| [crypto-portfolio-management](https://github.com/frytegg/crypto-portfolio-management) | Multi-strategy crypto portfolio optimization dashboard — 7 allocation strategies, GJR-GARCH volatility, HMM regime detection, on-chain signals, walk-forward backtesting, real-time Binance prices | Python, Plotly Dash |
| [inflexion](https://github.com/frytegg/inflexion) | Trustless, fully-collateralized on-chain market for Uniswap v3 impermanent-loss risk | Solidity, Stylus (Rust), Arbitrum |
| [funding-engine](https://github.com/frytegg/funding-engine) | Delta-neutral funding rate arbitrage across CEX/DEX (Bybit, Hyperliquid) | TypeScript |
| [blackjack-strategy-studio](https://github.com/frytegg/blackjack-strategy-studio) | Optimal blackjack strategy table generator with rules-aware engine | Python, React |
| [ask-starknet-bot](https://github.com/frytegg/ask-starknet-bot) | Starknet Q&A bots for Telegram, Discord, and X using LangGraph + MCP | Python |
| [rust-port-scanner](https://github.com/frytegg/rust-port-scanner) | Multi-threaded TCP port scanner | Rust |
| [build-your-own-git](https://github.com/frytegg/build-your-own-git) | Minimal git implementation — init, hash-object, cat-file, ls-tree, write-tree, commit-tree (CodeCrafters challenge) | Rust |
