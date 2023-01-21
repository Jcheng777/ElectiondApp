# Election dApp

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Clone the project
`git clone https://github.com/Jcheng777/ElectiondApp.git`

## Install dependencies
```
$ cd election
$ npm install
```
## Start Ganache
Open the Ganache GUI client that you downloaded and installed. 

## Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

## Purpose
Voter fraud is real and it’s not going away anytime soon. In one New York Election, 184,455,000 votes were recorded even though there were only 41,000 eligible voters. The big idea is that corruption is happening and we can’t do anything to stop it. We can use these smart contracts to make sure that elections are fair.
