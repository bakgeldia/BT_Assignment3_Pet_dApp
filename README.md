# BT_Assignment3_Pet_dApp

## Blockchain Technologies - Assignment #3 Student: Bakgeldi Alkhabay | Group: CS-2008
## Source: https://web3.hashnode.com/solidity-tutorial-creating-an-ethereum-dapp-with-ethersjs#heading-step-2-building-the-pet-form

## Demo
Here is my demo of the app.
[![Watch the video](https://t4.ftcdn.net/jpg/03/89/44/35/360_F_389443581_rXSMqtVtA1wiMxWgvLxYDFj22I8tFxRx.jpg)](https://youtu.be/YBf0-ngnhr8)

# App creation process

## Solidity IDE(REMIX)

### Creation of Smart Contract
Сreate a new file called Pet_Contract.sol in the contracts folder, and paste the code from source.
<br><img src="images/2.png">

### Compiling the Smart Contract
Navigate to the "Solidity Compiler" section. Select the compiler version that matches the one specified in our smart contract. Then click on the "Compile" button.
<br><img src="images/1.png">

### Getting Goerli Testnet Token
Navigate to <a href='faucets.chain.link'>Faucets</a>. Connect with your Metamask wallet. Ensure to switch to the Goerli Test network on your Metamask. Solve the captcha, and click on the "Send 0.1 test ETH" button. Check your Metamask for the new balance.
<br><img src="images/3.png">
<br><img src="images/4.png">
<br><img src="images/5.png">
<br><img src="images/6.png">

### Deploying the Smart Contract
Navigate to the "Deploy and Run Transactions" section. Select "Injected Web3" as the environment. Click on the "Deploy" button to deploy our smart contract on the Goerli Testnet. We'll be prompted to confirm the contract deployment gas fee. We see our smart contract name under the "Deployed Contracts" section, as shown below:
<br><img src="images/7.png">
<br><img src="images/8.png">
<br><img src="images/9.png">

### Testing the Smart Contract
Click on the dropdown arrow in the setPet function to expand the input boxes. Fill the input boxes with your pet's details and click on the "Transact" button. Confirm the transaction gas fee. Check each funtion by clicking on the buttons.
<br><img src="images/10.png">
<br><img src="images/11.png">

## Building the Front End

### Installing Ethers.js
<br><img src="images/12.png">
<br><img src="images/13.png">
<br><img src="images/14.png">

### Building the Pet Form
<br><img src="images/15.png">
<br><img src="images/16.png">

### Building the Pet Details Section
<br><img src="images/17.png">
<br><img src="images/18.png">

### Creating the Signer Logic
<br><img src="images/19.png">
<br><img src="images/20.png">
<br><img src="images/21.png">
<br><img src="images/22.png">
<br><img src="images/23.png">

### Creating the SetNewPet Function
<br><img src="images/24.png">

### Creating the getCurrentPet Function
<br><img src="images/25.png">
<br><img src="images/26.png">

# Testing the dApp
<br><img src="images/27.png">
<br><img src="images/28.png">
<br><img src="images/29.png">
<br><img src="images/30.png">
