# BabylonHackathon_IPFS-FILECOIN_CultureGram
CultureGram <br><br>
Step 1: To build this application, we need first some dependencies.
1. Node JS: 	This will enable the installation of all the packages of the computer and also enable the execution of the client side application. Node JS (https://nodejs.org/en/download/).
2. Truffle framework: This will be used to create etherium smart contracts with the solidity programing language, write test against them and deploy the smart contracts to the blockchain. Install truffle from the command line using the following commands.
Npm install –g truffle@5.1.39
3. Ganache Personal Blockchain: It provides 10 accounts funded with 100 Eth that can be used for testing smart contracts. (https://www.trufflesuite.com/ganache)
4. MetaMask for Browsers.  This etherium wallet is installed as a browser extension that will enable the browser to connect to the blockchain easily.
Step 2: clone project from our directory, install all packages by following the following commands after starting, and ensure Ganache is running.
//clone the repository
git clone https://github.com/lcaei/BabylonHackathon_IPFS-FILECOIN_CultureGram.git
//install all packages with node package manager
npm install 
//start the server to host the side of the application
npm run start
// Run migrations to deploy contracts
Truffle migrate –reset
//Run test on the smart contract
Truffle console
Truffle test
