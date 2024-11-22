# NFT Marketplace dApp

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🌐 [Live Demo](#live-demo)

## <a name="introduction">🤖 Introduction</a>

The NFT Marketplace dApp is a decentralized application that allows users to create, buy, and sell NFTs (Non-Fungible Tokens) on a local blockchain. Built using Hardhat, OpenZeppelin, Ethers, Chai, Vite and Firebase, this project showcases the capabilities of blockchain technology in the realm of digital asset management.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Hardhat
- OpenZeppelin
- Ethers.js
- Chai
- Vite
- Firebase

## <a name="features">🔋 Features</a>

👉 **Create NFTs**: Users can mint new NFTs on the local blockchain.

👉 **Buy and Sell NFTs**: Facilitates secure transactions of NFTs between users.

👉 **Metamask Integration**: Users can connect their Metamask wallets to interact with the dApp.

👉 **Local Blockchain**: Utilizes Hardhat for a local blockchain environment, enabling development and testing.

👉 **Smart Contract Deployment**: Deploy smart contracts using Hardhat and OpenZeppelin.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the NFT Marketplace dApp locally on your machine.

**Prerequisites**

Ensure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [Metamask Wallet](https://metamask.io/) (Chrome Extension)

**Cloning the Repository**

```bash
git clone https://github.com/ssachin520280/nft-marketplace-dapp.git
cd nft-marketplace-dapp
```

### Compile the Smart Contracts

Compile the contracts using Hardhat:

```bash  
npx hardhat compile  
```

### Run a Local Blockchain Node

Run the following command to start a local blockchain node in the background:

```bash  
npx hardhat node  
```

### Deploy the Smart Contracts

Deploy the contracts to the local blockchain:

```bash  
npx hardhat run backend/scripts/deploy.js --network localhost  
```

### Frontend Setup

Navigate to the `frontend` directory and install the required dependencies:

```bash  
cd frontend  
npm install  
```

### Run the Frontend

Start the development server:

```bash  
npm run dev  
```

### Metamask Wallet Configuration

Configure your Metamask wallet to connect to the local Hardhat blockchain:

- **Network Name**: Hardhat Node  
- **RPC URL**: http://127.0.0.1:8545  
- **Chain ID**: 31337  
- **Currency Symbol**: ETH  

Add a new account to the Metamask wallet using one of the private keys output by the npx hardhat node command.

### Connect Wallet

1. Open http://localhost:5173 in your browser.  
2. Click on the **Connect Wallet** button to link your Metamask wallet to the dApp.

## 🌐 Live Demo

Check out the live demo of the NFT Marketplace dApp here: [NFT Marketplace Live](https://google.com)

---

Feel free to customize this README file to better suit the specific needs and details of your project. Happy coding! 🚀

