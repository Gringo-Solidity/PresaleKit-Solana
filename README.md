#  PresaleKit-Solana

**Universal smart contract for token presales on Solana**, built with [Anchor](https://book.anchor-lang.com/).  
Highly configurable via YAML or CLI. Designed for startups, educational use, and production deployments.

---

##  Features

-  Configurable token presales with SOL or SPL tokens (e.g. USDC)
-  Hardcap / softcap / per-wallet limits
-  Vesting schedule (TGE %, cliff, linear unlock)
-  Optional allowlist (Merkle root)
-  Refunds if softcap is not reached
-  CLI + YAML support for non-devs
-  Built for reuse: multiple presales under one program

---

##  Project structure

presale-kit/
├── programs/
│ └── presale/ # Anchor smart contract
├── configs/ # YAML examples (school, startup, public)
├── cli/ # CLI to deploy and interact
├── tests/ # Unit and integration tests
├── README.md
├── ARCHITECTURE.md # Detailed program structure
└── LICENSE

## ⚙ Technologies

- Rust / Anchor
- Solana
- SPL Token / Token-2022
- YAML-based configuration
- Optional TypeScript (frontend or scripts)

---

##  Use cases

- Web3 startups raising via token presale
- Final project for [School of Solana](https://schoolofsolana.com/)
- Devs looking to reuse or extend a safe presale contract

---

##  Author

**Andrei "Gringo" Shapkin**  
GitHub: [@Gringo-Solidity](https://github.com/Gringo-Solidity)

This project is part of my School of Solana journey and Web3 portfolio.  
Use with attribution. Commercial use requires permission.
