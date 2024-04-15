# Flower NFT Contract

This smart contract implements the creation and evolution of NFTs (Non-Fungible Tokens) representing different stages of flower growth. It utilizes the Chainlink library for automation and OpenZeppelin for ERC721 token standards implementation.

## Contract

The `Flower.sol` contract contains all the logic for creating, evolving, and maintaining flower NFTs.

### Dependencies

This contract depends on the following Solidity libraries:

- Chainlink (for automation)
- OpenZeppelin (for ERC721 and utilities)

### Installation and Usage Steps

1. Clone this repository to your local machine.

2. Make sure you have Node.js and npm installed.

3. Install project dependencies by running `npm install`.

4. Deploy the contract on an Ethereum network of your choice.

5. Interact with the contract to create and evolve flower NFTs.

### Interacting with the Contract

Once the contract is deployed on an Ethereum network, you can interact with it using a block explorer or a command-line interface like Truffle.

## Post-Deployment Steps to View the NFT

After deploying and using the contract, you can follow these steps to view the created NFTs:

1. Log in with MetaMask on your browser.

2. Click on your profile to access your NFT collection.

3. Select the latest collection to view the created NFTs.

4. To properly display an NFT on OpenSea, follow these steps:

   - Open the NFT on OpenSea.
   - Click on the three dots in the top right corner.
   - Select "Update Metadata".
   - Refresh the page multiple times to ensure the changes are reflected.

## Automation with Chainlink

To automate flower growth, you can use the Chainlink platform by following these steps:

1. Visit [https://automation.chain.link/](https://automation.chain.link/) and connect your wallet.

2. Register a new Upkeep.

3. Customize the automation logic according to your needs.

4. Add the Flower contract address to be used.

5. Register the automation with the name "FlorAuto" and a balance of 3 LINK.

## Note

This README provides basic instructions for deploying and using the Flower contract, as well as for automating its maintenance with Chainlink. Make sure to thoroughly read and understand the code and instructions before interacting with the contract on a real Ethereum network.
