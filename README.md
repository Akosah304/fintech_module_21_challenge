# fintech_module_21_challenge

## Background

 launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

## Technologies

This project uses the following packages:

* [Remix](https://remix.ethereum.org/) - Remix is an IDE and compiler that runs in the browser that lets users debug transactions and create Ethereum contracts using the Solidity programming language..

* Ganache is a tool used in blockchain development, particularly with Ethereum. It’s a personal blockchain for Ethereum development that you can use to deploy contracts, develop your applications, and run tests. Ganache simulates a local Ethereum network with a set of accounts you can use for testing and development purposes.

* Solidity - Solidity is a high-level, object-oriented language used to create smart contracts. Programs known as "smart contracts" control how accounts behave in the Ethereum state.

* Getamask



## Installation Guide

You can work on this project online. No packages need to be installed locally.


## Usage

Please download the project or clone the project using git clone

Please launch remix by typing the following on the browser:

```python
https://remix.ethereum.org/
```

---

## KaseiCoin

1. **SOLIDITY COMPILER**: This is the name or title of the interface/tool you're using. It indicates that it's a compiler specifically for the Solidity programming language, which is used for writing smart contracts on the Ethereum blockchain. 

2. **COMPILER + 요**: This might be a button or option related to the compiler. The "+ 요" part could indicate additional features or settings related to the compiler.

3. **0.5.5+ commit.47a71e8f**: This shows the version of the Solidity compiler being used, which is 0.5.5, along with a specific commit identifier (commit.47a71e8f). This version information helps ensure consistency in compiling Solidity code.

![Kaseicoin.sol](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/Kaseicoin.sol.png)

## KaseiCoinCrowdsale

![KaseiCoinCrowdsale.sol](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/KaseiCoinCrowdsale.sol.png)

## KaseiCoin_connected_metamask and Ganache

1. **Environment**: This section specifies the environment in which you're deploying and running transactions. In this case, it's using MetaMask as the injected provider, which is a browser extension for interacting with the Ethereum blockchain. It also shows the network you're connected to (Custom - network ID 5777), along with the account address and its balance (100 ether). 

2.**Gas Limit**: This indicates the maximum amount of gas (a unit used for executing transactions on the Ethereum blockchain) allowed for the transaction. In this case, it's set to 3,000,000 gas. 

3. **Value (Wei)**: This section allows you to specify the amount of cryptocurrency (Ether) to send along with the transaction. The value is denominated in Wei, the smallest unit of Ether. 

4. **Contract Details**: This section provides information about the smart contract you're deploying. It includes the contract's name (KaseiCoin), source file (KaseiCoin.sol), and the EVM (Ethereum Virtual Machine) version (petersburg).

![KaseiCoin_connected_metamask and ganache.](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/KaseiCoin_connected_metamask%20and%20ganache.png)


![Crowdsale_address](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/crowdsale_address.png)

## kaseicoin_deployed and confirmation

 1. **Contract Interactions**: This section provides a list of functions and methods available for interacting with the KaseiCoin smart contract. These functions include actions like adding a minter, minting tokens, transferring tokens, checking allowances, and more. 
 
 2. **Transaction History**: This area likely displays a history of transactions related to the contract, including details such as transaction hashes, block numbers, gas used, and inputs.

![kaseicoin_deployed and confirmation](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/kaseicoin_deployed%20and%20confirmation.png)

## Crowdsale_deploy

![crowdsale_deploy](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/crowdsale_deploye.png)

## Crowdsale_deployed_address
 KaseiCoinCrowdsaleDeployer contract was successfully deployed to the blockchain. The constructor likely initialized the contract with parameters, such as the addresses of the KaseiCoinCrowdsale contract and the KaseiCoin token contract. The gas used indicates the computational effort required for the deployment

![crowdsale_deployed_address](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/crowdsale_deployed_address.png)

## Crowdsale_deployer

![crowdsale_deployer](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/crowdsale_deployer.png)

## Crowdsale_deployed_metamask confirmation

![crowdsale_deployed_metamask confirmation](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/crowdsale_deployed_metamask%20confirmation.png)


## Crowdsale_details
![crowdsale_details](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/crowdsale.png)

## Buy 1000 wei confirmation

![buy 1000 wei confirmation](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/buy%201000%20wei%20confirmation.png)

## Buy 1000wei_metamask_confirmation

![buy 1000wei_metamask_confirmation](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/buy%201000wei_metamask_confirmation.png)

## Buy token with another account

![Buy token with another account](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/buy%20token%20with%20another%20account.png)

## Token with another account details

![token with another account details](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/Screenshot%20(99).png)

## Ganache 1
 Each transaction includes information such as the hash (a unique identifier for the transaction), sender address, recipient address (if applicable), gas used, and value transferred. Transaction 4 involves the creation of a new contract, with the resulting contract address provided. These details provide insights into the activities and interactions occurring on the blockchain network, allowing users to track and analyze transactions.

![Ganache 1](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/Ganache%201.png)


## Ganache 2
This information describes a transaction where a contract call was made to the address 0x8C51cd64eb7B389CbC8322eBa667F75501D99D6e from the sender address 0xA216e31B5D64Ee8E5BD8203D5AD69835c2906b0d. The transaction details include the amount of gas used, gas price, gas limit, and the block in which the transaction was mined. The transaction data likely contains information about the function call or interaction being made with the contract at the specified address. Overall, this information provides insights into the execution of smart contract interactions on the blockchain network.

![Ganache 2](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/Ganache%202.png)


## Ganache 3

![Ganache 3](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/Ganache%203.png)

## Confirmation_token amount

![Confirmation_token amount](https://github.com/Akosah304/fintech_module_21_challenge/blob/main/Starter_Code/Evaluation%20evidence/Confirmation_token%20amount.png)