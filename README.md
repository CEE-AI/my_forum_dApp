# Decentralized Blog DApp

This is a decentralized blog application built on Next.js using blockchain technology. 

## Overview

The app allows users to:

- Connect their Ethereum wallet
- View all posts shared on the decentralized network
- Create new posts with title, content and image
- Upload post images to IPFS for decentralized storage 
- Interact with blockchain smart contracts to store post data 
- View post details and comments
- Add comments to existing posts

The frontend is built with:

- Next.js 
- TypeScript
- ethers.js to interact with the blockchain
- react-dropzone for image uploads

The backend consists of Solidity smart contracts deployed to the Ethereum blockchain, along with IPFS for decentralized storage.

## Smart Contracts

There are two main smart contracts:

- **PostManager** - Stores a list of all Post contracts and handles main post logic
- **Post** - Holds data for an individual post including title, content, author, etc.

New Post contracts are created when users create a post.

## Getting Started

1. Install dependencies:



npm install


2. Connect to the Ropsten test network

3. Update the PostManager contract address config variable to interact with deployed contracts

4. Run the dev server: 



npm run dev


5. Open the app at http://localhost:3000

6. Connect your Ethereum wallet to start interacting with the decentralized blog!

## Future Work

Some ideas for future improvements:

- Support mainnet deployment 
- Improve UI/UX for better mobile experience
- Add ability to tip post authors 
- Implement profiles for users
- Add notifications for new posts/comments
- Improve test coverage
