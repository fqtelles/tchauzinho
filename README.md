# Tchauzinho

![screenshot](https://raw.githubusercontent.com/fqtelles/tchauzinho/main/front-end/Portal%20do%20Tchauzinho.png)

## Try it out
### [Link](https://projeto-tchauzinho.fqtelles.repl.co/)


### Smart Contract on Goerli
##### [Etherscan](https://goerli.etherscan.io/address/0x388705156d1926f69e5867075f2cfbbfb3c77350)

### Instructions

``` bash
# install dependencies
$ npm install

# start hardhat node
$ npx hardhat node

# run scripts
$ npx hardhat run scripts/run.js --network localhost

# deploy smart contract
$ npx hardhat run scripts/deploy.js --network localhost

# start server
$ npm run dev
```

## Tech


* [Hardhat](https://hardhat.org/) - Ethereum development environment
* [Solidity](https://hardhat.org/) - Object-oriented, high-level language for implementing smart contracts on Ethereum
* [Ethers](https://github.com/ethers-io/ethers.js) - Ethereum wallet implementation and utilities in JS
* [Alchemy](https://www.alchemy.com/) - Broadcasts contract creation transaction to miners to add to the blockchain

This app was built as part of a [buildspace](https://buildspace.so/) project
