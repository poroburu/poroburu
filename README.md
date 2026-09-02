# poroburu

Systems and protocol-adjacent engineering. Production validator ops, funded protocol work to beta, a hackathon custody prototype, and a public packet pipeline.

Looking for systems / infra work with visible ownership.

## Status (honest)

**Validator ops, 2022–2025.** Production Cosmos validators: Akash, Jackal, Juno (Neta DAO); Passage, Nomic (direct). The job was chain upgrades and emergency maintenance.

**ic-cosmos — DFINITY grant, 2025, beta.** Port of ic-solana toward Cosmos: RPC canister, threshold ECDSA, Cosmos Hub sign/send. Tagged `v0.1.0-beta`. Not production-ready; the production milestone was not finished. No public URL until the repo is public.

**[kparser2](https://github.com/poroburu/kparser2) — public RC (`v0.1.0-rc.2`).** Packet-native FFXI telemetry: C++ capture → ZMQ → F# decoders → .NET 8 CLI/WPF. Fixture-tested. Best two-minute read on this account. Not a general product release.

**openKMS — Colosseum prototype.** YubiHSM2-backed signer for Cosmos and Solana, deny-by-default policy, Raspberry Pi, pay.sh integration. Prototype; supporting repos are private.

**Currently.** Solo Hummingbot lab (validation, not a team product). Public code when it exists: [txline-strategies](https://github.com/poroburu/txline-strategies), [txline-gateway](https://github.com/poroburu/txline-gateway). Do not link empty demo repos.

## Pin

Start at **kparser2**. Add ic-cosmos to pins only when it is public. Unpin kparser (v1), pumpdotfunosmo, and kpacket from the profile UI — they are pre-grant.
