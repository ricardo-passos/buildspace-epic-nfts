[![Netlify Status](https://api.netlify.com/api/v1/badges/c717b8bf-9514-44fd-8b62-dda465ac3664/deploy-status)](https://app.netlify.com/sites/ricardo-passos-epic-nfts/deploys)
# buildspace-epic-nfts
App to mint random generated NFTs. Each generated NFT will contain three random words and a random background color. The generation process is done on-chain.

## Getting started

1 - Head over the `blockchain` folder, run `pnpm install`. 
  - Then you'll need to start the local blockchain node with `pnpm run node`.
  - Now it's a matter of deploy the smart contract with `pnpm run deploy`.

2 - Head over the `client` folder, run `pnpm install`.
  - All you need to now is run `pnpm run dev`.

You're good to go.
