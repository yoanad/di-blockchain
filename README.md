# di-blockchain
PoC based on this tutorial https://www.dappuniversity.com/articles/blockchain-tutorial. 

# Requirements
- Node
- Ganache
- Truffle 

## Ganache Blockchain
A personal blockchain for Ethereum development you can use to deploy contracts, develop your applications, and run tests. It is available as both a desktop application as well as a command-line tool (formerly known as the TestRPC). Ganache is available for Windows, Mac, and Linux.

## Truffle
A world class development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM), aiming to make life as a developer easier.

``npm install -g truffle@5.0.2``

## Smart contract
It will be in charge of reading/writing to and from the blockchain. It will allow users to create new posts so that they can be shared in the newsfeed and tipped by other users.

- deploy smart contract on the blockchain
``truffle migrate``
  

## Things to remember
- Any time we store data on the Ethereum blockchain, we must pay a gas fee with Ether (Ethereum's cryptocurrency). This is used to pay the miners who maintain the network.
- While storing data on the blockchain costs money, fetching does not. In summary, reads are free, but writes cost gas.