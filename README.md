##Owner Smart Contract Assignment
📌 Overview

This repository contains a Solidity smart contract named Owner.sol, developed using both:

- Hardhat

- Foundry

Both frameworks are organized in separate directories inside a single parent project folder.
The contract was deployed to:

-Lisk Sepolia Testnet

-Arc Testnet

📂 Project Structure
.
├── OwnerHardhat/
│   ├── contracts/
│   │   └── Owner.sol
│   ├── scripts/
│   ├── test/
│   ├── hardhat.config.js
│   └── package.json
│
├── OwnerFoundry/
│   ├── src/
│   │   └── Owner.sol
│   ├── script/
│   ├── test/
│   └── foundry.toml
│
└── README.md

This project demonstrates the ability to work with multiple Ethereum development frameworks and deploy across multiple test networks.

##Deployment Details

##Lisk Sepolia Testnet with Hardhat

Contract Name: Owner

Network: Lisk Sepolia

Contract Address: 0x0c2ff1B1A520b6408152daf59bD2569519304AD3

Explorer: https://sepolia-blockscout.lisk.com/

##Arc Testnet with Hardhat

Contract Name: Owner

Network: Arc Testnet

Contract Address: 0x0c2ff1B1A520b6408152daf59bD2569519304AD3

Explorer: https://testnet.arcscan.app/

##Lisk Sepolia Testnet with Foundry

Contract Name: Owner

Network: Lisk Sepolia

Contract Address: 0xC27901c16B289Ea2ff70070E8fa0187369204dca

Explorer: https://sepolia-blockscout.lisk.com/

##Arc Testnet with Foundry

Contract Name: Owner

Network: Arc Testnet

Contract Address: 0xC27901c16B289Ea2ff70070E8fa0187369204dca

Explorer: https://testnet.arcscan.app/

🔐 Environment Variables

Each framework uses environment variables for deployment.

Example .env:

PRIVATE_KEY=your_private_key
RPC_URL=your_rpc_url


⚠️ Never commit your private key.

Learning Outcomes

This assignment demonstrates:

Smart contract development using Solidity

Using both Hardhat and Foundry in one project

Deploying to multiple EVM-compatible testnets

Managing multi-framework project structure


Addresses for hardhat :
Arc testnet :0x0c2ff1B1A520b6408152daf59bD2569519304AD3

Lisk sepolia:0x0c2ff1B1A520b6408152daf59bD2569519304AD3

Addresses for Foundry:
Arc testnet:0xC27901c16B289Ea2ff70070E8fa0187369204dca

Lisk sepolia:0xC27901c16B289Ea2ff70070E8fa0187369204dca
