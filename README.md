# Blockchain Voting System

A decentralized voting application built using Ethereum blockchain technology. This project provides a secure, transparent, and tamper-proof online voting system using smart contracts.

## Overview

Traditional voting systems often face issues such as fraud, lack of transparency, centralized control, and manual vote counting. This project solves these problems by using blockchain technology and smart contracts.

The system allows an administrator to manage candidates and authorize voters. Only authorized users can vote, and each wallet address can vote only once. Votes are stored on the blockchain and results are displayed in real time.

## Features

- Wallet connection using MetaMask
- Admin-controlled candidate management
- Add candidates
- Remove candidates
- Authorize voters by wallet address
- One vote per user
- Real-time vote counting
- Automatic winner detection
- Transparent and secure blockchain records

## Technology Stack

- Frontend: React.js
- Blockchain: Ethereum
- Smart Contracts: Solidity
- Web3 Integration: Web3.js
- Wallet: MetaMask
- Deployment: GitHub, Vercel / Netlify

## Project Structure

```text
src/
 ├── components/
 │   ├── Navbar.jsx
 │   ├── Home.jsx
 │   ├── AdminPanel.jsx
 │   ├── Vote.jsx
 │   └── Results.jsx
 │
 ├── App.jsx
 └── contract.js
