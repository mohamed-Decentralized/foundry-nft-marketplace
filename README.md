# Gas Bad Nft Marketplace

This repository contains the implementation of a gas-optimized NFT marketplace smart contract. The contract allows users to list, buy, update, and cancel NFTs on the marketplace. It uses inline assembly to optimize gas costs, ensuring minimal overhead for common actions such as emitting events and interacting with external contracts.

---

## Features

The `GasBadNftMarketplace` contract offers the following key features:

- **Listing NFTs**: Users can list their NFTs for sale, specifying the sale price.
- **Buying NFTs**: Users can purchase listed NFTs by sending the correct amount of Ether to the contract.
- **Canceling Listings**: Sellers can cancel their NFT listings.
- **Updating Listings**: Sellers can modify the price of their listed NFTs.
- **Withdrawing Proceeds**: Sellers can withdraw the proceeds of their sales.
- **Gas Optimizations**: The contract uses inline assembly to optimize event logging and reduce transaction costs.

## Installation

```bash
git clone https://github.com/mohamed-Decentralized/foundry-nft-marketplace.git
cd foundry-nft-marketplace
forge install 
forge build
```