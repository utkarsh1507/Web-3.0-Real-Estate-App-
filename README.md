# NFT-Based Real Estate Marketplace

## Overview
This is a **full-stack Web3 application** that enables users to **buy and sell real estate properties as NFTs** on the Ethereum blockchain. The project ensures secure and transparent transactions using smart contracts.

## Tech Stack
- Blockchain & Smart Contracts: Solidity, Ethereum
- Development Framework: Hardhat
- Frontend: React, Web3.js
- Backend: Node.js, Express
- Storage: IPFS (for property metadata)

## Features
- **NFT Property Listings** – Each real estate property is tokenized as an NFT.
- **Secure Smart Contracts** – Ensuring secure transactions and ownership transfer.
- **Ethereum Payment Integration** – Users can buy properties using ETH.
- **Decentralized Storage** – Property details and metadata are stored on IPFS.
- **User-friendly Interface** – Built with React for seamless interaction.

## Installation & Setup
### Prerequisites
- Node.js (v16+ recommended)
- Hardhat
- MetaMask Wallet

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nft-real-estate.git
   cd nft-real-estate
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Deploy Smart Contracts:
   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network goerli
   ```
4. Run the frontend:
   ```bash
   cd frontend
   npm start
   ```

## Smart Contract Details
The core smart contract **RealEstateNFT.sol** includes:
- Minting properties as NFTs
- Handling secure property transfers
- Ensuring only verified owners can list properties

## Contributing
Feel free to open an issue or submit a pull request!

## License
This project is licensed under the MIT License.

## Contact
Connect with me on [LinkedIn] https://www.linkedin.com/in/utkarsh-srivastava-707aa61b0/ or reach out via email at utkarshzz007@gmail.com

