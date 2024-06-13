# MyToken Contract

This Solidity contract implements a basic token system with functionalities to mint and burn tokens.

## Requirements

1. **Public Token Details**: The contract stores public variables for the token's name, abbreviation, and total supply.
2. **Address to Balance Mapping**: It includes a mapping that tracks the token balances of different addresses.
3. **Mint Function**: A `mint` function that increases the total supply by a specified amount and updates the balance of a given address accordingly.
4. **Burn Function**: A `burn` function that decreases the total supply and the balance of a specified address by a given amount, with checks to ensure sufficient balance is available for burning.
5. **Balance Checks in Burn**: The `burn` function includes conditionals to verify that the sender's balance is sufficient for the burn operation.

## Usage

1. **Deployment**: Deploy the contract to a compatible Ethereum Virtual Machine (EVM) environment.
2. **Interaction**: Interact with the contract through transactions to mint or burn tokens.
3. **Management**: Use the provided functions to manage token supply and balances.

## Solidity Version

This contract is written in Solidity version 0.8.18.

## SPDX-License-Identifier

This contract is licensed under the MIT License. The SPDX-License-Identifier can be found at the top of the Solidity file for more details.

## Contract Address

Once deployed, the contract will have a unique address on the Ethereum blockchain, allowing users to interact with its functions.