# Blockain Best Locations Survey ✈️
A simple Blockchain project developing ethereum smart contracts and tests for a survey website.<br>

## Pre-requirements 📋

To clone and run this project, you will need:

- [Node.js](https://nodejs.org/en/) (I've used version `v18.15.0` while writing this doc)
- npm (I've used version `9.5.0` while writing this doc)
- [Ganache*](https://archive.trufflesuite.com/ganache/) ( (I've used version `2.7.1` while writing this doc)

***Note:** Unfortunately, [Truffle Suite is being sunset](https://consensys.io/blog/consensys-announces-the-sunset-of-truffle-and-ganache-and-new-hardhat), but you can use this material more for learning.
<br>

## Installation 🏗️

1. Open Ganache app now and click on Quickstart ETHEREUM, this will generate a blockchain running locally on port 7545.

2. You also need to integrate Metamask in the ETH Network. <br>
[Check Truffle docummentation in a how-to tutorial](https://archive.trufflesuite.com/docs/truffle/how-to/truffle-with-metamask/)

<img src="https://github.com/rodrigomolter/blockchain-testing/assets/57466763/a951b6ec-627c-4bd5-aded-610fb89dc406" width=400>
<br><br>

3. Install the Truffle CLI globally by running the following command:
```bash
npm install -g truffle
```

4. Run to install the dev dependencies
```bash
npm install
```

5. Compile all the project <br>
Solidity is a compiled language, meaning we need to compile our Solidity to byte code for Ethereum Virtual Machine (EVM) to execute.
```bash
truffle compile
```

6. Migrate the contract <br>
Before we can migrate our contract to the blockchain, we need to have a blockchain running.
**So, make sure Ganache is running and go to your terminal and type truffle migrate.**
```bash
truffle migrate
```

## Starting the App </>
Start the application with the command
```bash
npm run dev
```

## Running the tests 🧪

In this project, you can run tests
```bash
truffle test
```

## Support this project 🙌

If you want to support this project, leave a ⭐.

This project is based on the [Pet Shop tutorial](https://archive.trufflesuite.com/boxes/pet-shop/) in the Truffle Box

___

Made with love 🧡 by [Rodrigo Molter](https://www.linkedin.com/in/rodrigo-molter/)
