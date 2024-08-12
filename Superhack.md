# Superhack 2024
![스크린샷_12-8-2024_141419_](https://github.com/user-attachments/assets/4a4c5e85-f675-4f96-b267-58cab8cfbedc)

## Review of participation in the 13 hackathon.

## Contents
- [Github repo](https://github.com/alexsrebernic/mintory)
- [Demo Site](https://mintory.vercel.app/)
- [Twitter](https://x.com/mintorydotfun)

### Overview:
Mintory.fun prioritizes the Optimism ecosystem while also leveraging various ecosystems using the OP Stack, and it also supports the Base ecosystem with a focus on ERC-721 NFTs. We aim to recognize NFTs as assets with ownership value, creating a vibrant and liquid NFT ecosystem. Therefore, our services are designed to enhance NFT engagement and liquidity, allowing general users to explore and become familiar with web3 through fun, interest, and creativity, thereby gaining extensive experience.

✨If you want to see details, go to the [Showcase](https://ethglobal.com/showcase/mintory-fwd6i)

---
### Background:
We formed a team together by recruiting team members directly from the Discord channel and Telegram.
- Project Manager 1
- Front-end developer 1
- Full-stack Developer 1
- UX/UI Desginer 1

---
### Track:

- *Optimism*
- *Worldcoin*
- *Base*
- *Pyth*
- *Blockscout*

---
### Project:
> **Mintory**

![New Cover](https://github.com/user-attachments/assets/7de9eb02-de2e-49d6-bb0e-842c1435f0a3)

### Easy NFT Creation and Trading:
- Users can easily create and trade ERC-721 NFTs, learning about NFT creation and trading processes.

### Liquidity Pools with Stablecoins:
- We provide liquidity pools pairing NFTs with USDT or USDC (e.g., NFT 1 : USDT 1), allowing users to buy and sell NFTs at measured prices.

### Automatic NFT DEX Listing:
- NFTs are automatically listed on NFT DEX (e.g., Uniswap) when trading volume reaches a certain level, benefiting NFT creators with better experience and earnings.

### User Verification Benefits:
- Verified users receive special benefits, such as their NFTs being displayed prominently at the top of listings. Unverified users can still use the platform but without these benefits.

> **Architecture**

![image](https://github.com/user-attachments/assets/84e47de7-c004-468f-87c4-000079aa9aa8)

### User flow:
1. Web3 Login
   - Users log in to web3 by connecting their wallet (MetaMask, Coinbase, etc.).
2. NFT Creation
   - Creators use the "Create" feature to generate their own NFTs.
3. Authentication and Exposure
   - If creators want their NFTs displayed at the top of the main screen, they authenticate their credibility using World ID.
4. NFT Purchase
   - General users select and purchase the created NFTs.
5. NFT Resale
   - If they wish to sell the NFTs, they can list them for resale on the platform.
6. Automatic Listing
   - When the generated NFTs reach the set trading threshold within the platform, they are automatically listed on an NFT DEX like Uniswap for trading.

---
### Build Tools
<img src="https://img.shields.io/badge/Typescript-3178C6?style=flat&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=white"/> <img src="https://img.shields.io/badge/Next.js-ffffff?style=flat&logo=nextdotjs&logoColor=black"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/Solidity-363636?style=flat&logo=solidity&logoColor=white"/> <img src="https://img.shields.io/badge/Web3.js-F16822?style=flat&logo=web3dotjs&logoColor=white"/>

---
### Result:
- Not yet

---
### Reason for falling (Feedback from ETHGlobal judges):
- Not yet

---
### Areas for improvement:
1) Among the game metadata values included in the contract, if the value that can be used as "Feature" had been specifically set, the developers could have proceeded with the development more conveniently, but it was a pity that I could not set the value specifically.
2) There was a lack of information and study on the mechanisms for Sui smart contracts and the metadata values included.
3) English presentation required

---
### Positive aspects:
- Before participating in the Sui Hackathon, I participated in the Celestia Hackathon. So, I participated in the Sui Hackathon just 2 days after it ended, so the team members were all exhausted, but they still did their best until the end and finished with a good result, so it was nice to be able to get such a good result.
- There was no professional front-end developer, but the contract developer wanted to try the front-end, so this was my first time working properly on the front-end. He shared "Gam3.gg" as a reference with very good quality, and it was very similar to the platform. I think there were good results because the front-end was developed well.
- Even though this was the first time using an API called Zettablock, the backend developer stayed up all night developing it, analyzing the contract, selecting “Features” related to game metadata within the contract, and providing only those parts to Zettablock as an API. I think we got good results by using it to display only the desired data values ​​after data filtering.

---
### Things I learned from the hackathon:
- Since I only knew the Sui ecosystem as a concept as a network specialized for games, I was thinking of an idea as a game-related project, so while doing research with the development team members, I was checking the smart contract for transactions that occurred in Sui Explorer. I was very surprised to see that it contained methods (or functions) related to game metadata, and this was the first time I learned about it.
- The function called “Package ID” within the contract allows us to know that the game contains various metadata for various rankings, levels, characters, etc. and is related to game-related data, so we can filter data based on “Package ID” to filter the game. Metadata values ​​are displayed on the front.

---
### What i did
👨🏼‍💻 Role: Product Manager (PM)

- Ideation
- Planning
- Research about referrence
- Determine development priorities and organize strategic sponsor tracks
- Checek the Schedule
- Create the social account and post
- Make the Architecture
- Summary for the meeting reports & ETHGlobal contents
