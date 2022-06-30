# Initial-Coin-Offering

![image](https://i.imgur.com/78uY3Mm_d.webp?maxwidth=1520&fidelity=grand)

This Dapp is for the DAO.
You want to launch a DAO for holders of your CryptoDevs NFTs. From the ETH that was gained through the ICO, you built up a DAO Treasury. The DAO now has a lot of ETH, but currently does nothing with it.

You want to allow your NFT holders to create and vote on proposals to use that ETH for purchasing other NFTs from an NFT marketplace, and speculate on price. Maybe in the future when you sell the NFT back, you split the profits among all members of the DAO.

Created as part of the [Learn Web3 DAO](https://www.learnweb3.io/) Sophmore Tack.

This code was written for Decentralized Autonomous Organization Tutorial

## Features

- Anyone with a CryptoDevs NFT can create a proposal to purchase a different NFT from an NFT marketplace
- Everyone with a CryptoDevs NFT can vote for or against the active proposals
- Each NFT counts as one vote for each proposal
- Voter cannot vote multiple times on the same proposal with the same NFT
- If majority of the voters vote for the proposal by the deadline, the NFT purchase is automatically executed
- To be able to purchase NFTs automatically when a proposal is passed, you need an on-chain NFT marketplace that you can call a purchase() function on. There exist a lot of NFT marketplaces out there, but to avoid overcomplicating things, we will create a simplified fake NFT marketplace for this tutorial as the focus is on the DAO.
- We will also make the actual DAO smart contract using Hardhat.
- We will make the website using Next.js to allow users to create and vote on proposals

Let's start building 🚀

## Frontend 

- This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).


## Overview Info

- Chain: Ethereum
- Network: Rinkeby
- Languages: Solidity, JavaScript
- Deployed to Rinkeby FakeNFTMarketplace Contract: `0x1200Bf5714934fa2f0f9bD26294b8635116bc0C5`
- Deployed to Rinkeby CryptoDevsDAO Contract: `0x94537461B3A951a9a1c07F223C7025fF6E6bA25c`
- Rinkeby Contract Link on Etherscan: https://rinkeby.etherscan.io/address/0x1200Bf5714934fa2f0f9bD26294b8635116bc0C5
- Rinkeby Contract Link on Etherscan: https://rinkeby.etherscan.io/address/0x94537461B3A951a9a1c07F223C7025fF6E6bA25c
- Live Website: [`https://ico-airdrop-mikexd-dev.vercel.app/`](https://ico-airdrop-mikexd-dev.vercel.app/)


## Technology/Websites used:

- [VS Code](https://code.visualstudio.com/)
- [Rinkeby](https://www.rinkeby.io/#stats)
- [Alchemy](https://www.alchemy.com/)
- [Hardhat](https://hardhat.org/)
- [OpenZeppelin](https://www.openzeppelin.com/)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
