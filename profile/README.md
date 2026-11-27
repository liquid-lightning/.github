# liquid-lightning

This project aims to build a Visa for web3: a fully trustless payment network that connects chains over a common layer 2, built on Lightning.

- **Multi-asset:** BTC, L-BTC, Liquid assets, ETH and ERC-20 tokens.
- **Swaps:** pay in one asset, receive another.
- **Instant:** payments settle off-chain in seconds.

> [!WARNING]
> **Proof of concept only.** Not audited, not production ready. Use it on test networks only, never with real funds.

## Repositories

| Repository | What it is |
|---|---|
| [lightning](https://github.com/liquid-lightning/lightning) | Core Lightning fork with asset channels |
| [liquid-plugin](https://github.com/liquid-lightning/liquid-plugin) | Asset channels on Liquid |
| [utxo-contract](https://github.com/liquid-lightning/utxo-contract) | Contract that lets Lightning run on EVM chains |
| [swap-plugin](https://github.com/liquid-lightning/swap-plugin) | Cross-asset payments |
| [pricer-plugin](https://github.com/liquid-lightning/pricer-plugin) | Prices for swaps |
| [ember](https://github.com/liquid-lightning/ember) | Hosted Lightning nodes |
| [ember-client](https://github.com/liquid-lightning/ember-client) | Rust client for ember |
| [light-app](https://github.com/liquid-lightning/light-app) | Android wallet |
| [dashboard](https://github.com/liquid-lightning/dashboard) | Web page for managing nodes |

Each repository has its own README with setup steps.

## Licence

Each repository has its own licence. Copyright (c) 2026 The liquid-lightning developers.
