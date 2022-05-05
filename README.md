# SubBridge Integration Repo

## How to integration your asset into SubBridge?

Bascially you should do the following steps to finish integration with SubBridge:

- Open an issue on this repo to provide assets registry information
- Test registration locally or on Rococo
- Register asset on Khala network
- Integrate SubBridge into your app[Optional]

More details can be found on Phala Wiki.

## Tips of runing our chain locally

- Build [khala-parachain](https://github.com/Phala-Network/khala-parachain) with command `cargo build --release --features=all-runtimes`
- Use [polkadot-launch] start a paracahin testnet, use config file `thala-karura.config.json` as reference. Please aware that the `chain` argument is `thala-dev-2004` which already contains paraid, you may need to disable `--parachain-id` in your polkadot-launch source code.
