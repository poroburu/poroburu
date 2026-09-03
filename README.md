# Marlin Lachance

Systems and protocol-adjacent engineering. Production Cosmos validator operations, a DFINITY-funded ICP↔Cosmos gateway, an HSM-signing prototype for on-chain agents, and a public MMO analytics packet pipeline.

Open to systems and infrastructure roles.

## Selected work

**Validator ops, 2022–2025.** Production Cosmos validators: Akash, Jackal, Juno, AtomOne (Neta DAO); Passage, Nomic (direct). Signing keys off-host (TMKMS + YubiHSM2). Homelab as a production datacenter: bonded WAN across multiple ISPs (OpenMPTCProuter on a mini PC) and UPS. On-call with the validator community and core teams.

**[ic-cosmos](https://github.com/poroburu/ic-cosmos)** — DFINITY grant, 2025. Rust port of ic-solana toward Cosmos: RPC canister, threshold ECDSA, Cosmos Hub sign and send. Tagged [`v0.1.0-beta`](https://github.com/poroburu/ic-cosmos/releases/tag/v0.1.0-beta).

**[kparser2](https://github.com/poroburu/kparser2)** — MMO analytics: C++ capture → ZMQ → F# decoders → .NET 8 CLI/WPF.

**openKMS — Colosseum.** YubiHSM2-backed signer for on-chain agents on Cosmos and Solana, the same remote-HSM pattern as the validators; deny-by-default policy engine on a Raspberry Pi; pay.sh intercepts x402 requests from an agent to the signing provider.

**Hummingbot lab.** Solo experiments this school year: [txline-strategies](https://github.com/poroburu/txline-strategies), [txline-gateway](https://github.com/poroburu/txline-gateway).
