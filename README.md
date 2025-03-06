# Virtual Assets Locked Savings Platform

![Image](https://github.com/user-attachments/assets/401154ff-2157-48b1-ba00-b31717a689e6)

## Overview
FVKRY PRVNTA is a blockchain-based virtual assets and crypto locking platform that aims to enhance financial discipline and promote long-term saving among cryptocurrency and virtual asset owners. It allows users to check their impulsive spending and trading habits by allowing them to lock their ETH and ERC-20 tokens in secure vaults that can only be accessed after a predefined lock period ranging from days, weeks, months and upto years.

## Features
- Asset Locking:  
  Lock ETH and ERC-20 tokens in a secure smart contract vault.  
- Flexible Lock Periods:
  Users can set lock durations for days, weeks, months or years.   
- Add-on Deposits:
  Add more assets to your vault without resetting the lock period.  
- Secure and Transparent:
  Built on Ethereum, leveraging smart contracts for transparency and trust.

## User Flow
1. Connect Wallet:  
   Connect a crypto wallet to access the platform.  
2. Dashboard Access:  
   Manage vaults, view balances, and track lock periods.  
3. Vault Creation:  
   Specify lock duration, type and assets to lock.  
4. Deposit Management:  
   Add more funds to an existing vault.  
5. Adjust Lock Period:  
   Extend the lock period after every three months if needed.  
  


## Technology Stack
- Blockchain: Ethereum  
- Smart Contracts: Solidity (ERC-20 and ETH support)  
- Frontend: ReactJS
- Backend: Node.js with Supabase for authentication and database management  
- Tools: Hardhat, OpenZeppelin, and ethers.js  


## How It Works
1. Lock ETH:  
   Use the platform to deposit ETH securely into a vault with a lock period.  

2. Lock ERC-20 Tokens:  
   Select supported tokens, approve the contract, and lock them in your vault.  

3. Smart Contract Logic:  
   - Locks assets for the specified duration.  
   - Only allows adding assets until the lock period ends.  
   - Extend lock period if it expires.  

4. Releases Funds:  
   After the lock duration, users can withdraw assets directly to their wallets.

## Technology Stack
- Blockchain: Ethereum  
- Smart Contracts: Solidity (ERC-20 and ETH support)  
- Frontend: ReactJS with Vite
- Backend: Node.js and ExpressJS 
- Tools and Libraries: Hardhat, OpenZeppelin, WalletConnect, Wagmi and viem. 

## More
For detailed documentation on the smart contract, frontend and backend, view each individual repo readme file.