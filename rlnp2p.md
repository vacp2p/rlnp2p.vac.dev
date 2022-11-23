---
title: Main
---

# RLNP2P

**NOTE: This page is a very early work in progress.**

## About RLNP2P

RLNP2P gives p2p protocols and applications economic, anonymous spam protection using RLN.

RLN stands for Rate Limiting Nullifier and uses Zero Knowledge Proofs to enforce a certain message rate, without linking a publisher to a message. When a message rate is exceeded, a user's financial or social stake gets slashed.

In a p2p setting, this means that each node keeps the necessary state required and validates messages before passing them on.

This means that we get a decentralized, sybil-resistant and privacy-preserving communication channel in a p2p network.

## Examples

[Waku RLN Relay](https://rfc.vac.dev/spec/17/) is an example of using RLNP2P applied to Waku in a GossipSub network.

The same technique can trivally be used on top of stock libp2p GossipSub as well.

With some modifications, it can also likely be used in other topologies such as [Dandellion++](https://github.com/vacp2p/research/issues/119) and [Tor/onion routing](https://github.com/vacp2p/research/issues/149).

p2p applications that use use RLN on the social layer, as opposed to on the networking layer, can also likely use RLNP2p. For example, [zkchat](https://github.com/kayleegeorge/zk-chat).

We are also currently working on a variant that combines [RLN+Interrep](https://github.com/vacp2p/research/issues/147), using social stake instead of financial stake. This paves the way for users who do not currently have crypto assets to use RLNP2P.

### Contribute

Check out links below and join the #rln channel in our [Vac Discord](https://discord.gg/PQFdubGt6d)

## Links

### RLN

- [Rate Limiting Nullifier (PSE)](https://rate-limiting-nullifier.github.io/rln-docs/)
- [RLN spec (PSE/Vac)](https://rfc.vac.dev/spec/32/)
- [RLN GH org (PSE)](https://github.com/Rate-Limiting-Nullifier)
- [Zerokit RLN library (Vac)](https://github.com/vacp2p/zerokit/)

### RLN Relay

- [RLN Relay write-up (Vac)](https://vac.dev/rln-relay)
- [RLN Relay spec (Vac)](https://rfc.vac.dev/spec/17/)
- [RLN Relay testnet (Vac)](https://github.com/status-im/nwaku/blob/master/docs/tutorial/rln-chat-cross-client.md)

### Work in progress

- [RLN+Interrep](https://github.com/vacp2p/research/issues/147)
- [Waku v2 anonymity roadmap](https://github.com/vacp2p/research/issues/107)
- [RLNP2P positioning doc](https://github.com/vacp2p/research/issues/146)

### Misc

- [Privacy & Scaling Explorations](https://appliedzkp.org/)
- [Vac Research](https://vac.dev)