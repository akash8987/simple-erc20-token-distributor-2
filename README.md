# Simple ERC-20 Token Distributor

This repository contains a streamlined, single-directory implementation of a custom ERC-20 Ethereum token and a Batch Distributor contract. It is designed for developers looking to understand how to mint tokens and send them to multiple addresses in a single transaction to save on gas.

## Features
* **ERC-20 Compliant**: Standard OpenZeppelin-based token logic.
* **Batch Transfers**: Send tokens to up to 100+ addresses at once.
* **Web3 Integration**: Includes a simple JavaScript snippet to interact with the contract using Ethers.js.

## Quick Start
1. Deploy `Token.sol` to a testnet (like Sepolia).
2. Deploy `Distributor.sol`.
3. Use `app.js` to connect your wallet and trigger the batch distribution.

## License
MIT
