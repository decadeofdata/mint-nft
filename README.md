# mint-nft
Minting NFT on polygon testnet. Code taken from Polygon documentation. Using Solidity and Hard-Hat.

## Installation

Using scripts in Git-Bash.
```
npm install hardhat @openzeppelin/contracts nft.storage dotenv @nomiclabs/hardhat-ethers
```
```
npx hardhat
```

When asked:  Select.
```
What do you want to do? · Create an empty hardhat.config.js
```

Create folders.
```
mkdir contracts assets scripts
```

Create file .env and entrer private key and NFT storage api.

Run.
```
node scripts/store-asset.mjs
```
```
npx hardhat run scripts/deploy-contract.mjs --network PolygonMumbai
```

Add info to mint-nft.mjs.

```
const CONTRACT_ADDRESS = ""
const META_DATA_URL = ""
```

Finally run.
```
npx hardhat run scripts/mint-nft.mjs --network PolygonMumbai
```
