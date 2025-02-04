# AITUSE2327 Token

This project aims to creates an ERC-20 token based on Ethereum. The token was created for the AituSE2327 group. Its initial supply consists of 2000 tokens.

## Features

- **ERC-20 Standard**: This token follows the ERC-20 standard, which is the most widely used standard for tokens on the Ethereum blockchain.
- **Initial Supply**: 2000 tokens.
- **Functions**:
  - Functions to retrieve and display transaction information.
  - Function to return the block timestamp of the latest transaction in a human-readable format.
  - Function to retrieve the address of the transaction sender.
  - Function to retrieve the address of the transaction receiver.
  
## Functionalities

1. **ERC-20 Token**:
   - The token is called `AITUSE2327`, and its symbol is `AITUSE`.
   - The initial token supply is 2000 AITUSE, which are initially owned by the contract creator.

2. **Functions**:
   - `getLastTransactionTimestamp`: Returns the timestamp of the latest transaction in a human-readable format.
   - `getLastTransactionSender`: Returns the address of the sender of the latest transaction.
   - `getLastTransactionReceiver`: Returns the address of the receiver of the latest transaction.
   - All transactions are logged through the `TransactionInfo` event.

## Installation and Setup

To run the project, open remix.

Then, create a new file, copy and paste the contract into it.
Compile it.

Then go to Deploy and Run, use metamask as environment and deploy the contract.
