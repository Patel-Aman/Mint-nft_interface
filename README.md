# NFT Mint Interface

# Installation
To use this minter, do the following:

1. Run `npm install` to download the `node_modules` folder.
2. Download the [dotenv package](https://www.npmjs.com/package/dotenv) in project directory by running `npm install dotenv --save` in terminal
3. Create a `.env` file in the root directory. and then add your [Alchemy API Key](https://docs.alchemyapi.io/alchemy/tutorials/nft-minter#create-your-alchemy-api-key) and [Pinata Key and Secret](https://pinata.cloud/keys). `.env` file should look like this:

```
REACT_APP_PINATA_KEY = <pinata-key>
REACT_APP_PINATA_SECRET = <pinata-secret>
REACT_APP_ALCHEMY_KEY = https://eth-ropsten.alchemyapi.io/v2/<alchemy-key>
```
4. Run `npm start` in terminal to open the minter in browser.

# Use
1. Connect [metamask](https://metamask.io/download/) wallet using `Connect Wallet` button.

2. For minting NFT you will require gas. You can get it from [Faucet](https://goerlifaucet.com/).

3. Go to [Pinata](https://app.pinata.cloud/pinmanager) and upload image for NFT to get IPFS link.

4. Fill Name and Description for your NFT and click on `Mint NFT` to mint your NFT. Makee sure you are on goerli network before minting. wait for few minutes for success of transaction.

5. Go to [opensea](https://testnets.opensea.io/login?referrer=%2Faccount%3Ftab%3Dcollected) and connect your wallet you can see minted NFT in your collection.
