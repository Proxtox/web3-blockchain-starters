# Deployment Guide

General guidance for deploying the starters.

## EVM Chains (Base, Arc, Ethereum, BSC)
1. Install dependencies: `npm install`
2. Configure your `.env` with RPC URL and private key
3. Run the deployment script: `npx hardhat run scripts/deploy.js --network <network>`
4. Verify the contract on the block explorer

## Solana
1. Install Anchor and Solana CLI
2. Run `anchor build`
3. Deploy with `anchor deploy`

## Sui
1. Install Sui CLI
2. Run `sui move build`
3. Publish with `sui client publish`

Most repos include a `scripts/deploy.js` or equivalent. Check the individual README for network-specific instructions.