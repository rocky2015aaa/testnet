# Konstellation Testnets

This repo collects the genesis and configuration files for the various Konstellation
testnets. It exists so the [Konstellation](https://github.com/konstellation/konstellation)
repo does not get bogged down with large genesis files and status updates.

## Getting Started

To get started with the latest testnet, see the
[docs](https://github.com/Konstellation/konstellation#to-join-testnet-follow-this-steps).

## Testnet Status

⚠️ Latest testnet: [knstlhub-1](./knstlhub-1) ⚠️

Download the genesis here: [genesis](https://raw.githubusercontent.com/Konstellation/testnet/master/knstlhub-1/genesis.json)
Download the config here: [config](https://raw.githubusercontent.com/Konstellation/testnet/master/knstlhub-1/config.toml)

```bash
$ shasum -a 256 genesis.json
726e0c03ad96afd012af7161af8ed753348e157464951a76830733e7eb49879e  -
```

Seed nodes:

```
709dd4c6d8677df533cbe56c41cbf78a4b03ab1c@node1.konstellation.tech:26656
63077c418b50b67453043f3cd9124f3445d99b92@node2.konstellation.tech:26656
3528e0f60b31165f9d9befd33025821aeb20a64f@node3.konstellation.tech:26656
```

```
CHAIN_ID=knstlhub-1
RELEASE=v0.1.30
KONSTELLATION_VERSION=v0.1.30
```