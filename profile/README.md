> # Deterministic State Machine

Deterministic, post-quantum peer-to-peer state progression without validators, consensus, sequencers, or a public global ledger.

## DSM

DSM is a relationship-local state machine architecture where correctness is enforced by cryptographic proof, forward-only adjacency, and deterministic verification.

## Building

- DSM core protocol
- SDK and wallet infrastructure
- Storage nodes
- Offline bilateral transfers
- Bitcoin Tap for Bitcoin ingress and egress
- dBTC bridge architecture
- Deterministic liquidity systems

## Bitcoin Tap

Bitcoin Tap is the DSM Bitcoin bridge path for moving value between Bitcoin and DSM. It is designed to enable Bitcoin-backed entry into DSM and Bitcoin redemption back out, while letting value move inside DSM under deterministic local state progression rather than global consensus.

We are currently using [Signet](https://en.bitcoin.it/wiki/Signet) for Bitcoin-side testing and integration.

Bitcoin: [bitcoin.org](https://bitcoin.org/)

## Principles

- No validators
- No consensus
- No global bottleneck for unrelated activity
- No gas for local DSM transfers
- No trusted operators
- No reliance on institutional authorization

## Status

Active development.
