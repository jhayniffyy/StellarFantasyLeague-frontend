# StellarFantasyLeague-frontend

A modern Web3 fantasy sports application built on Stellar, powered by Soroban smart contracts.
This repository contains the React-based frontend for the Stellar Fantasy League (SFL) platform.

Overview
The frontend enables users to:
Connect Stellar wallets
Create and join leagues
Build fantasy teams (NFT-based)
Track leaderboard rankings
Claim on-chain rewards
View NFT trophies and assets
All interactions are executed directly with Soroban smart contracts.

Tech Stack
React (Vite or Next.js)
TypeScript
Tailwind CSS
Stellar Wallet Kit
Freighter Wallet integration
Axios
Zustand / Redux (state management)



Project Structure
src/
 ├── components/
 ├── pages/
 ├── hooks/
 ├── services/
 ├── contracts/
 ├── store/
 ├── utils/
 └── assets/

Environment Variables
Create a .env file:
VITE_STELLAR_NETWORK=testnet
VITE_SOROBAN_RPC_URL=https://soroban-testnet.stellar.org
VITE_BACKEND_API_URL=http://localhost:3000
VITE_CONTRACT_LEAGUE_ID=
VITE_CONTRACT_TEAM_ID=
VITE_CONTRACT_REWARD_ID=

Installation
git clone repo URL 
cd project folder 
npm install
npm run dev
Wallet Integration
Supported wallets:
Freighter
WalletConnect-compatible wallets

Future:
Social login + auto wallet creation
Testing
npm run test
Includes:
Component tests
Contract interaction mocks
UI state tests

Contributing
Fork repo
Create feature branch
Submit PR
Follow coding standards
Include tests
