# QR-Integrated Supply Chain Verification

A blockchain-powered system for tracking and verifying product authenticity using smart contracts and QR codes. Built with Solidity, React, Web3.js, and MetaMask.

---

## Installation & Dependencies

### Backend (Smart Contracts)

To develop and deploy the smart contracts, install:

- **Node.js** (v14+)
- **npm**
- **Truffle**
- **Ganache GUI** or **Ganache CLI**

Install Truffle globally:
npm install -g truffle


### Frontend

Frontend is built using React and Web3.js.

Install dependencies with:

    npm install

### Setup and compilation

Open Ganache and ensure it’s running on:
    RPC Server: http://127.0.0.1:7545
    Chain ID: 1337 (or 5777)

Compile and Deploy Contracts using the commands:
    truffle compile
    truffle migrate

### Metamask setup

Add a Custom Network in MetaMask:
	- Network Name: Ganache Local
	- RPC URL: http://127.0.0.1:7545
	- Chain ID: 1337 or 5777

Import a Ganache account using its private key.

Connect your browser wallet to the DApp.


### Running the application

Enter the following commands in the terminal:
    truffle compile
    truffle migrate
    npm run dev


After the above steps, the UI will open on - http://localhost:3000. 

### QR Code Integration

Each product’s serial number can be converted to a QR code. Scanning the code triggers a blockchain verification call to check if the product is valid and traceable to a real manufacturer.

### License
    MIT © 2025 – QR-Integrated Supply Chain Verification
    Built for secure, transparent supply chains using Ethereum smart contracts.

