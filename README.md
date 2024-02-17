# Solidity Require Assert Revert
This Solidity contract, named RequireAssertRevert, showcases the usage of require(), assert(), and revert() statements. These statements are essential in smart contract development for input validation, critical condition checking, and handling exceptional cases.
## Description
The contract contains three functions, each demonstrating a different statement:

### requireStatement(uint256 amount):

Illustrates the use of require() statement.
Checks if the provided amount is greater than 0.
If the condition is not met, it reverts the transaction with the specified error message.

### assertStatement(uint256 amount):

Demonstrates the assert() statement.
Asserts that the provided amount is greater than 0.
If the assertion fails, indicating a critical error, the transaction is reverted.

### revertStatement():

Displays the use of the revert() statement.
Always reverts the transaction with the error message "Amount must be greater than 0."

## Getting Started
  ### Prerequisites
To run and interact with this contract, you need access to a Solidity development environment. You can use tools like Remix, Truffle, or Hardhat.

Usage
Compile the Contract:

Copy and paste the provided Solidity code into your development environment.
Compile the contract using the Solidity compiler.

Deploy the Contract:
Deploy the contract on your chosen development blockchain.
Interact with the Functions:

After deployment, interact with the contract by calling the three functions.
Provide appropriate parameters when calling requireStatement and assertStatement functions.
