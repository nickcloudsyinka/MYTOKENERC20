# OJODELE Token Smart Contract

## Overview
`OJODELE` is an ERC20-compliant token with minting and burning functionalities. It extends the standard ERC20 token by incorporating the ability to mint and burn tokens, controlled by the contract's owner. This contract also utilizes OpenZeppelin's `ERC20`, `ERC20Burnable`, and `Ownable` contracts to ensure robust and secure token management.

## Features
- **Minting**: The contract owner can mint new tokens to a specified address.
- **Burning**: The contract owner can burn tokens from a specified account.
- **Ownership Control**: The contract owner has exclusive rights to mint, burn, and transfer ownership.
- **Standard ERC20 Functionality**: Implements the standard ERC20 token functions such as `transfer`, `approve`, `allowance`, and `transferFrom`.

## Contract Details

- **Token Name**: ojodele
- **Token Symbol**: OJODELE
- **Solidity Version**: ^0.8.19
- **License**: MIT

## Installation and Deployment

### Prerequisites
- [Node.js](https://nodejs.org/)
- [Hardhat](https://hardhat.org/)
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts)

### Step 1: Clone the repository

```bash
git clone https://github.com/your-repository/ojodele-token
cd ojodele-token
