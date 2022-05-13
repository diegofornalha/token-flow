# Cadence Fungible Token Tutorial

## Description
Explains how a basic fungible token is implemented in Cadence

## Readme
This tutorial takes you through the minimum requirements for using resources to build a simple Fungible Token smart contract in Cadence, as well as an introduction to Capabilities.

See the full tutorial here: https://docs.onflow.org/cadence/tutorial/03-fungible-tokens/

## About Playground Export
This project was generated from Playground living here:
[https://play.onflow.org/136057e3-1b88-425e-bbe9-724ca890dd19](https://play.onflow.org/136057e3-1b88-425e-bbe9-724ca890dd19)

We have added some basics tests, which you can run using Node, Flow Emulator and Flow JS Testing Framework.

## Installation
### Node *(optional if you have it installed already)*
Please follow instructions on NodeJS download page and install latest version of NodeJS software:
https://nodejs.org/en/download/

### Flow Emulator *(optional if you have it installed already)*
Flow Emulator is bundled with Flow CLI. You can find instructions on how to install it on Flow Docs site:
https://docs.onflow.org/flow-cli/

### Flow JS Testing Framework
All the necessary files will be installed if you run `npm install` inside `test` folder. For documentations on how to use
the framework you can consult package repository [https://github.com/onflow/flow-js-testing](https://github.com/onflow/flow-js-testing)

### Next Step
When all the above tools would be installed you will need to init Flow Emulator with `flow init` command from within
`test` folder. This will create `flow.json` file in the folder, which is necessary for emulator to operate properly.

Then you can proceed running the tests. We encourage you to run "Create Accounts" suit first, followed by "Deployment" and then
transactions and scripts.

### Afterword
Good luck and happy hacking! :)