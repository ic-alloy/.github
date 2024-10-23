![ic-alloy](./hero.png)

Alloy implements high-performance, well-tested & documented libraries for interacting with Ethereum and other EVM-based chains. This fork of Alloy adds support for the [Internet Computer](https://internetcomputer.org) (ICP) both as a transport layer and as a signer.

`ic-alloy` abstracts away a lot of complexities involved with interacting with an EVM RPC from inside an ICP canister.

## Library

### [ic-alloy](https://github.com/ic-alloy/ic-alloy)

The `ic-alloy` library is the Rust crate that you add to you project dependencies. Instead of interacting directly with the ICP EVM RPC canister, you interact with `ic-alloy`.

## Examples

### [ic-alloy-toolkit](https://github.com/ic-alloy/ic-alloy-toolkit)

A collection of examples on how to perform common EVM operations. Rust backend and React/Vite frontend.

Live demo: <https://u4yi6-xiaaa-aaaap-aib2q-cai.icp0.io>

### [ic-alloy-basic-wallet](https://github.com/ic-alloy/ic-alloy-basic-wallet)

A basic Ethereum multi-user wallet. Rust backend and React/Vite frontend.

Live demo: <https://7vics-6yaaa-aaaai-ap7lq-cai.icp0.io>