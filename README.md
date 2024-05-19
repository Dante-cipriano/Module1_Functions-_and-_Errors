# AppleInventory Smart Contract

# Overview:

This repository contains a Solidity smart contract named `AppleInventory` which helps manage apple inventory. It provides functions to restock apples, sell them, and update the total inventory.


# Functionalities:

- Restock Apples:
Function: `restock(uint256 _quantity)`
Description: Adds a specified quantity of apples to the inventory.
Requirement: Restock quantity must be greater than 50.

- Sell Apples:
Function: `soldApple(uint256 _quantity)`
Description: Sells a specified quantity of apples, reducing the inventory.
Requirement: Quantity to be sold must be greater than 20 and should be available in the inventory.

- Update Total Apples:
Function: `TotalAppleInBasket(uint256 newTotal)`
Description: Allows the contract owner to update the total number of apples in inventory.

- Get Total Apples:
Function: `getTotalApples()`
Description: Retrieves the total number of apples in inventory.

- Get Owner:
Function: `getOwner()`
Description: Retrieves the address of the contract owner.



# Usage:

- Deploy the Contract:
   - Deploy the `AppleInventory` contract on an Ethereum-compatible blockchain network.

- Interact with the Contract:
Use a web3 provider or an Ethereum wallet to interact with the deployed contract.
Call functions `restock`, `soldApple`, and `TotalAppleInBasket` to manage the inventory.
Call functions `getTotalApples` and `getOwner` to retrieve information from the contract.


# Note:
Manage Ether transactions carefully when using contract functions.
Ensure proper access control, especially for critical functions like updating the total apples in inventory.


# License:
This smart contract is licensed under the MIT License.
