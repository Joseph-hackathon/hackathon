# Superhack 2024
![스크린샷_12-8-2024_141419_](https://github.com/user-attachments/assets/4a4c5e85-f675-4f96-b267-58cab8cfbedc)

## Review of participation in the 15 hackathon.

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
- Worldcoin - Pool Prize

---
### Reason for falling (Feedback from ETHGlobal judges):
- Not yet

---
### Areas for improvement:
1) I was unable to complete the demo video until 5 minutes before the submission deadline, so the quality of the demo video was a bit lacking at the end.
2) Development continued until 10 minutes before the submission deadline, and the same situation as above occurred. It was unfortunate that I did not manage the schedule properly.
3) 2-3 days before submission, an issue occurred due to the version of the AMM code, which is automatically listed on Uniswap, one of the core functions of our platform, and integration and testing were not possible. So, it was unfortunate that this part was only expressed in roadmap format and could not be shown in this demo. (We should have checked and monitored our core functional areas with some priority, but I think this situation occurred because we failed to check them in advance.)
4) English presentation required

---
### Positive aspects:
- The submission time passed, but fortunately, the video was uploaded and the submission was completed successfully. Also, because the organizer gave us a little more time, we were able to edit the video and re-upload it as a demo video with slightly better quality.
- Even while all of our team members were doing their own work and taking exams, we were able to come up with a platform called Mintory because they developed the platform, followed me closely, and did their best to develop it in the direction I wanted.
- Although we were not able to integrate many sponsor tracks, our development team members were able to lead the way by researching things that fit the sponsor track and directly making suggestions, while also providing new ideas, such as using World ID and Pyth oracle to fetch prices. It was really nice to be able to develop our platform into a more diverse and highly reliable platform.

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
