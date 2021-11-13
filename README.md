# BabylonHackathon_IPFS-FILECOIN_CultureGram
CultureGram <br><br>
Step 1: To build this application, we need first some dependencies.<br><br>
1. Node JS: 	This will enable the installation of all the packages of the computer and also enable the execution of the client side application. Node JS<br><br> (https://nodejs.org/en/download/).<br><br>
2. Truffle framework: This will be used to create etherium smart contracts with the solidity programing language, write test against them and deploy the smart contracts to the<br><br> blockchain. Install truffle from the command line using the following commands.<br><br>
Npm install –g truffle@5.1.39<br><br>
3. Ganache Personal Blockchain: It provides 10 accounts funded with 100 Eth that can be used for testing smart contracts. (https://www.trufflesuite.com/ganache)<br><br>
4. MetaMask for Browsers.  This etherium wallet is installed as a browser extension that will enable the browser to connect to the blockchain easily.<br><br>
Step 2: clone project from our directory, install all packages by following the following commands after starting, and ensure Ganache is running.<br><br>
//clone the repository<br><br>
git clone https://github.com/lcaei/BabylonHackathon_IPFS-FILECOIN_CultureGram.git<br><br>
//install all packages with node package manager<br><br>
npm install <br><br>
//start the server to host the side of the application<br><br>
npm run start<br><br>
// Run migrations to deploy contracts<br><br>
Truffle migrate –reset<br><br>
//Run test on the smart contract<br><br>
Truffle console<br><br>
Truffle test<br><br>

STEPS OF EXECUTION
Once you start the server, the application launches on localhost:3000, asking the user to sign in with the blockchain wallet. In this case met mask<br><br>
 ![image](https://user-images.githubusercontent.com/20139432/141600732-c1394ec5-daff-4de3-93da-7103bbeb7660.png)

Clicking the choose file button opens a dialogue box which gives the user the chance to choose and upload to IPFS an image.<br><br>
 ![image](https://user-images.githubusercontent.com/20139432/141600743-b30d347c-f388-44f1-b68a-1196d7d71f24.png)

The image is uploaded and the description entered. The description and the image CID are stored in the blockchain in a persistent manner.<br><br>

