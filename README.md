# nft
A simple JavaScript library for working with NFTs.

## What it does
This library provides a set of tools for creating, managing, and interacting with NFTs on various blockchain platforms. It handles tasks such as metadata generation, image processing, and smart contract deployment.

## Installation
To get started, install the library using npm:
```bash
npm install
```
Then, import it into your JavaScript project:
```javascript
const NFT = require('./nft');
```
## Running the example
There's a simple example in the `example` directory that demonstrates how to use the library to create and deploy an NFT:
```javascript
const NFT = require('../nft');

// Create a new NFT
const myNFT = new NFT({
  name: 'My NFT',
  description: 'This is my NFT',
  image: 'path/to/image.png'
});

// Deploy the NFT to the blockchain
myNFT.deploy().then(() => {
  console.log('NFT deployed successfully');
});
```
Run the example using node:
```bash
node example/index.js
```
This will create and deploy a new NFT to the blockchain. Check out the `example` directory for more information.