# Token Generator DApp

A simple Web3 DApp that lets users generate and receive ERC-20 tokens directly into their MetaMask wallet by clicking a button.

---

## Features

- Connect MetaMask wallet
- Mint ERC-20 tokens to the connected wallet
- Smart contract deployed to testnet
- React + Ethers.js frontend

---

## Tech Stack

- **Frontend:** React.js + Tailwind CSS  
- **Smart Contract:** Solidity (ERC-20)  
- **Blockchain Tools:** Hardhat, Ethers.js  
- **Wallet Integration:** MetaMask  
- **Network:** (e.g., Sepolia or Mumbai Testnet)

---


## How to Run Locally

### Prerequisites

- Node.js & npm
- MetaMask browser extension
- Hardhat installed globally:  
  ```bash
  npm install --save-dev hardhat
  ```
  #### Clone the repo
  ```
  git clone https://github.com/yourusername/token-generator-dapp.git
  cd token-generator-dapp
  ```

  #### Install dependencies
  ```
  npm install

  ```
  #### Compile the contract
  ```
  npx hardhat compile
  
  ```
  #### Deploy to testnet
  Update .env with your private key and Alchemy key.
  ```
  npx hardhat run scripts/deploy.js --network sepolia

  ```
 #### Start the Frontend
 ```
 npm run dev
 ```
 
