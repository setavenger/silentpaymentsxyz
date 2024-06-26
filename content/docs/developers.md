---
title: Silent Payments For Developers
summary: For the developers among you, this page is a simple page to point you in the right direction for where to look into for integration on both the wallet and scanning side.
weight: 3
prev: /docs/wallets
next: /docs/bounties
---

For the developers among you, this page is a simple page to point you in the right direction for where to look into for integration on both the wallet and scanning side.

{{< callout type="info" >}}
  Please note that *sending* support is the most important right now, and that silent payments was designed to make sending trivial!
{{< /callout >}}

## Wallet libraries

- [cygnet3/rust-silentpayments](https://github.com/cygnet3/rust-silentpayments)
  - A Rust library for Silent Payments.
  - Warning: both this crate and BIP352 are still quite new. Review this library carefully before using it with mainnet funds.
- [BlueWallet/SilentPayments](https://github.com/BlueWallet/SilentPayments)
  - A TypeScript library for Silent Payments, built for Blue Wallet.
- [cake-tech/bitcoin_base](https://github.com/cake-tech/bitcoin_base/tree/cake-update-v3)
  - Dart library for flutter applications with full support for silent payments and tests included, built for Cake Wallet.
- [cake-tech/sp_scanner](https://github.com/cake-tech/sp_scanner/tree/sp_v1.0.0)
  - Dart package which calls rust FFI for faster ECDH scanning, built for Cake Wallet.
- [setavenger/go-bip352](https://github.com/setavenger/go-bip352)
  - A go package that handles the core computations surrounding Silent Payments.

## Scanning back-ends

- BlindBit
  - [blindbit-oracle](https://github.com/setavenger/blindbit-oracle)
  - [blindbitd](https://github.com/setavenger/blindbitd)
  - [WIP light client specification](https://github.com/setavenger/BIP0352-light-client-specification)
- [louisinger/silentiumd](https://github.com/louisinger/silentiumd)
- [cake-tech/electrs](https://github.com/cake-tech/electrs/tree/cake-update-v1)
  - Note that this is a WIP fork of `electrs` with optimized support for Silent Payment scanning added.
