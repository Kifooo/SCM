# Smart Contract Management

The Assessment contract is a simple smart contract written in Solidity that allows for depositing, withdrawing, and redeeming items using Ethereum. It also implements custom error handling and emits events for important contract actions.

## Features

- Deposit: The contract owner can deposit Ethereum into the contract.
- Withdraw: The contract owner can withdraw Ethereum from the contract.
- Redeem: Users can redeem predefined NFT (Non-Fungible Token) items by paying with the deposited Ethereum balance.

## Getting Started

To interact with the Assessment contract, you'll need an Ethereum wallet or development environment that supports Solidity smart contracts. You can deploy the contract to the Ethereum blockchain and interact with it using tools like Remix, Truffle, or Hardhat.

## Prerequisites

- An Ethereum wallet or development environment
- Knowledge of interacting with Ethereum smart contracts using tools like Remix, Truffle, or web3.js

## Deployment

Deploy the contract to the Ethereum blockchain using tools like Remix, Truffle, or Hardhat. Make sure to specify the appropriate compiler version (Solidity ^0.8.9) and include the SPDX license identifier.

## Usage

- Deposit: Call the `deposit` function to deposit Ethereum into the contract. Only the contract owner can deposit funds.
- Withdraw: Call the `withdraw` function to withdraw Ethereum from the contract. Only the contract owner can withdraw funds. Make sure to provide a valid withdrawal amount.
- Redeem: Call the `redeem` function with the ID of the NFT item you want to redeem. Ensure you have sufficient balance in the contract to cover the redemption cost.

## Custom Error Handling

The contract implements custom error handling for cases where the withdrawal amount exceeds the contract balance. This ensures that transactions revert gracefully with informative error messages.

## Events

The contract emits events for important actions such as depositing, withdrawing, and redeeming items. You can listen to these events to track contract activity.

## License

This project is not licensed. Feel free to use and modify the code as per your requirements.

