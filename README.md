# SolaFan

## Bring the Future Of Media to Web3

All-in-1 Artist Web3 Media Platform on Solana

- Easily Publish & Sell Content NFT embedded Anywhere (decentralize Spotify/Patreon)
- NFT purchase -> custody > Permissioned content stream (decentralized AWS/CloudFlare)
- Realtime Fan Insights > Manage Event Access (decentralize ticketmasters/eventbrite)

## Tech Stack

### [Cere Media SDK](https://cerebellum-network.github.io/cere-media-sdk-js/)

The Media SDK is a development kit that can be used to upload and retrieve encrypted content for NFTs.
- [Added Solana signature scheme support](https://github.com/Cerebellum-Network/cere-media-sdk-js/pull/40)

### [Cere Wallet](https://github.com/cere-io/cere-wallet-client)

Non-custodial walled with social auth.

- Added Solana network support to [API](https://github.com/cere-io/cere-wallet-api/pull/35/files) and [Client](https://github.com/cere-io/cere-wallet-client/pull/197/files)

### [Cere DDC](https://github.com/Cerebellum-Network/cere-ddc-sdk-js)

Decentralised data cloud cluster for storing assets and metadata.

## Quick start

1. Install dependencies:

```bash
nvm exec npm i
```

1. Copy ENV file:

```bash
cp env/.env.dev .env
```

1. Run the app:

```bash
nvm exec npm start
```
