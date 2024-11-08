# Token Contract

The `Token` smart contract is an ERC20-compliant token with added functionalities, such as minting and burning, and is fully owned and controlled by a specified owner. It is based on OpenZeppelin’s secure library, providing a solid foundation for ERC20 tokens with additional features.

## Contract Overview

- **Token Name**: MarySpidy
- **Token Symbol**: MARYSPIDY
- **Compiler Version**: `^0.8.19`
- **License**: MIT

## Features

This contract inherits from OpenZeppelin’s libraries and provides several key features:

- **ERC20**: Standard ERC20 token functionality.
- **ERC20Burnable**: Allows token burning, reducing the total supply.
- **Ownable**: Restricts certain functions to the contract owner.

## Constructor

The contract constructor initializes the token with a name, symbol, and owner.

```solidity
constructor(address initialOwner) ERC20("MarySpidy", "MARYSPIDY") Ownable(initialOwner) {}
