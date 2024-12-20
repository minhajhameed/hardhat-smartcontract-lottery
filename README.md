# Hardhat Smart Contract Lottery

This project demonstrates a decentralized lottery system using Solidity, Hardhat, and Chainlink services. The lottery allows users to participate by sending ETH, and a winner is randomly selected using Chainlink VRF. Chainlink Keepers automate the process of determining the winner.

## Features
- **Lottery Entry**: Users can enter the lottery with ETH.
- **Random Winner Selection**: Utilizes Chainlink VRF for fair randomness.
- **Automation**: Chainlink Keepers handle automated winner selection.

## Requirements
Before running the project, ensure you have the following installed:
- **Node.js**: v14.x or later
- **Hardhat**: Installed as a dev dependency
- **Metamask**: For interacting with the contract
- **Ethereum Testnet**: Such as Goerli or Sepolia

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/minhajhameed/hardhat-smartcontract-lottery.git
cd hardhat-smartcontract-lottery
npm install
