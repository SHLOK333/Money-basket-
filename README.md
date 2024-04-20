# TokenTechies 

TokenTechies is a Web3 version of smallcase with token investment UX improvement in the DeFi space. Instead of micro-management of the portfolio, we provide a simple interface to create a bucket of tokens and invest in them in a single transaction. Consider it as mutual funds where the deposited amount will be invested in tokens with respective allocations. Later, it can be withdrawn according to the current market price. Choose better PNL doing buckets, invest, and grow with strategies!

### How are we using 1inch?
Using `1inch Fusion API`, we are swapping the investment into prospective token allocation on `Arbitrum One`, `Base`, and `Polygon Mainnet`. Later, it will be used to withdraw the funds from the bucket. 

## Prerequisites & Manual Setup

Every user must have a Metamask wallet to interact with this product. Check out how to create a Metamask wallet from [here](https://metamask.io). 

Follow the instructions for the local environment: The user must have Node.js and npm to run this platform. Just download Node.js from [here](https://nodejs.org/en/download/).

### Local Setup Instructions

**Clone the repo via CLI:**

```sh
git clone https://github.com/neel-ds/finn.git 
cd finn
```

**Install the required packages:**

```sh
npm install
yarn install   #or
pnpm install   #or
```

**Add required environment variables mentioned in `.env.example` file**

```sh
touch .env  #Paste env variables in this file and your values
```

**In the project directory, you can run:**

```sh
npm run dev
yarn dev   #or
pnpm dev   #or
```

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


  In other terminal for the same project...

# Verbwire Wallet Integration

Welcome to the Verbwire Wallet Integration project! This repository demonstrates a basic workflow for integrating the Verbwire wallet into your app, providing a seamless user onboarding experience and smoother interactions with your decentralized application (dApp). The wallet can be utilized like any other wallet, allowing you to perform tasks such as signing messages, conducting transactions, managing NFTs, handling ERC-20 Tokens, and interacting with smart contracts.

## Basic Functions Demonstrated

This project showcases the following three fundamental functions:

1. **Signing a Message**: Demonstrates how to sign a message using the Verbwire wallet.

2. **Sending Funds**: Illustrates the process of sending an amount to another wallet address using the Verbwire wallet.

3. **Minting NFT (or Contract Interaction)**: Provides an example of minting an NFT or interacting with a smart contract using the Verbwire wallet.

## Getting Started

### Installation

To get the project up and running, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory: `cd verbwire-wallet-integration`.
3. Install the required dependencies: `npm install`.

### Configuration

Before running the application, you need to make a few changes in the `credentials.js` file located in the root directory:

1. Add your public key with the necessary scope.
2. Add your application ID for the wallet integration.
3. Add your Alchemy API key.

## Running the application

Once you've configured the credentials, you can run the application using the following command:

```bash
npm run dev
```

This will start the development server, allowing you to access and test the Verbwire wallet integration in your app.


