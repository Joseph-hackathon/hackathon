![image](https://github.com/user-attachments/assets/609cd100-79a5-47d0-b3c5-77065d2ca798)

# [REDACTED] Hackathon
`Review of participation in the 21 hackathon.`

[Demo](https://web3-gaming-redacted.vercel.app/) | [Github](https://github.com/SUNIDHI-JAIN125/Redacted-Hackathon) | [Video](https://youtu.be/AAP3yWIKdlE)

## Overview
A visualization dashboard for Web3 games that goes beyond just displaying game information is very compelling.

> ✨If you want to see details, go to the [Devpost](https://devpost.com/software/not-yet-lhnw4d)

### Team
We formed a team together by recruiting team members directly from the Discord channel.
- Product Manager 1
- Backend & Smart contract 1
- Frontend developer 1

### What i did
👨🏼‍💻 Role: Product & Project Manager (PM)
- Planning
- Ideation
- Research about market | competitors | referrence
- Checek the Schedule
- Make the Architecture | Github repo readme file | Diagram
- Summary for the meeting reports & Submmit contents

### Track
- *Native Track*
  - Best of Chain Abstraction
  - Best tech
  - Honorable Mentions
- *Chain Agnostic Track*
  - Proximity Chain Abstraction Bounty
  - Bounty Winners

## Project
![image](https://github.com/user-attachments/assets/3ef5c537-cf0d-496f-84a2-290458b642df)
<br></br>

**io.Side** is a Web3 analytics platform, built with NEAR Protocol, designed for users to gain in-depth insights into decentralized apps, particularly in Web3 gaming. 
It aggregates cross-chain data, using NEAR’s chain abstraction to provide a seamless experience for managing assets across networks. 
Features include real-time game data, a Dapp explorer, and a caching system for efficient data retrieval. 
With a strong focus on security and privacy through NEAR’s Chain Signatures, io.Side enables gamers, developers, and investors to easily track performance, assets, and trends within the Web3 ecosystem.

### Key Points

**Comprehensive Web3 Game Dashboard:**
- Our platform goes beyond simply providing game overviews. It offers an in-depth analysis of both on-chain (NFTs, tokens, TVL) and off-chain (rankings, player performance) data, delivering a holistic view of the game ecosystem.

**Real-Time On-Chain Data Visualization:**
- We provide users with real-time tracking and visualization of token and NFT prices, marketplace activity, and on-chain transactions related to Web3 games. This makes the complex Web3 game economy more accessible and transparent.

**Gamified Analytics:**
- The platform transforms data analysis into a fun, interactive experience, allowing users to explore game statistics in a way that mimics the competitive and engaging nature of gaming itself.

**Cross-Game Comparison:**
- For users playing multiple Web3 games, the platform aggregates performance, token holdings, and NFT portfolio data across different games, allowing for seamless comparison and asset management in one place.

**Future Expansion into NFT Marketplaces:**
- Our platform aims to integrate with NFT marketplaces and expand asset management features, enabling users to efficiently manage all their in-game and out-of-game assets from a single, unified platform.

### Diagram
``` mermaid
sequenceDiagram
    participant User
    participant AI_Agent as AI Agent
    participant Game_API as Web3 Game API
    participant Blockchain as Blockchain Explorer
    participant Dashboard as Visualization Dashboard

    User->>Dashboard: Access dashboard
    Dashboard->>AI_Agent: Request game data
    AI_Agent->>Game_API: Fetch game metadata (rankings, levels, etc...)
    Game_API-->>AI_Agent: Return game metadata
    AI_Agent->>Blockchain: Fetch on-chain data (NFT prices, tokens, etc...)
    Blockchain-->>AI_Agent: Return on-chain transaction data
    AI_Agent->>Dashboard: Send analyzed data (rankings, NFTs, tokens, etc...)
    Dashboard-->>User: Display visualized game data
```

### Result
- Not yet

### Reason for falling (Feedback from NEAR Protocol judges)
- Not yet

### Areas for improvement
1) We attempted to collect on-chain data for Near ecosystem games, but there were not many sponsored tracks providing game data. We tried to use Zetta Block, but we could not retrieve data due to API issues. We tried to use public AI, but we had to use an AI agent and it was difficult to implement, so we used the **`DAppRadar API`** to transfer game data to Near protocol as well as other networks from the API. It was disappointing that I couldn't take advantage of the various sponsor tracks because I had to bring them.
2) English presentation required.

### Positive aspects
- We haven't used many sponsor tracks, and there aren't many places that provide on-chain game data to Near Protocol, so it was difficult, but fortunately, I was able to retrieve on-chain game data for web3 games through Subgraph on **`DAppRadar`** and **`The Graph`**. It was great to be able to complete a web3 game explorer that fits the purpose of our io.Side project.

### Things I learned from the hackathon
- [See that link](https://github.com/Joseph-hackathon/hackathon/blob/main/%5BREDACTED%5D%20Hackathon%20%231.md#things-i-learned-from-the-hackathon)
