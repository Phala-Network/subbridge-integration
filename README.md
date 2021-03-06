# SubBridge Integration Repo

## How to integrate your asset into SubBridge?

Bascially you should do the following steps to finish integration with SubBridge:

- Open an issue on this repo to provide assets registry information
- Test registration locally or on Rococo
- Register asset on Khala network
- Integrate SubBridge into your app[Optional]

More details can be found on Phala Wiki.

## Tips of runing our chain locally

- Build [khala-parachain](https://github.com/Phala-Network/khala-parachain) with command `cargo build --release --features=all-runtimes`
- Use [polkadot-launch](https://github.com/paritytech/polkadot-launch) to start a paracahin testnet. We have provided a config file [thala-karura.config.json](https://github.com/Phala-Network/subbridge-integration/blob/main/thala_karura.config.json) to your as a reference. Please aware that the `chain` argument is `thala-dev-2004` which already contains paraid, you may need to disable `--parachain-id` in your polkadot-launch source code.
