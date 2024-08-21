# Arauco Chain - Parachain

Arauco Chain use [Cumulus](https://github.com/paritytech/polkadot-sdk/tree/master/cumulus)-based Substrate node, configured with [Frontier](https://github.com/polkadot-evm/frontier), enabling compatibility with the Ethereum Virtual Machine (EVM).

## Implementation
**Arauco Chain** (parachain) is built using [Pop CLI](https://onpop.io/) and [Substrate SDK](https://substrate.io/).

### Devnet
To use the devnet in your environment, you can use Pop:

1. Download and install Pop.
2. Clone this repo.
3. Build this project with Pop:
``
pop build
``


4. Run this network, specifying the network file:
``
pop up parachain -f network.toml
``
