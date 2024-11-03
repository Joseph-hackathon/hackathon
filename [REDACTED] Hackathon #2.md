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
  - Best of AI
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
1) We completed all of the smart contracts and AI models for each part, but in the process of integrating with the front end, there was a problem with the integration of the AI ​​model due to the high usage environment on PCs such as GPUs, so it was unfortunate that it could not be completed as a perfect platform.
2) This Near Protocol Hackathon had many sponsored tracks that focused on AI technology, which was the core of this hackathon, but among the sponsored tracks, we used **ZettaBlock** and **Public AI**'s API to import on-chain data and train it in our AI model to model it. We tried to improve and collect and pre-process a lot of data, but there was not enough data related to the vulnerabilities we wanted, and there was a problem integrating the API, so it was disappointing that we could not utilize the sponsor tracks.
3) Our MVP was to complete all of the API docs page, file upload page, and admin console page, but this MVP was not in a phase that could be completed within the period and had many overloaded functions, so it was difficult to manage these schedules. As a product manager, I was a bit lacking and was disappointed.
4) English presentation required.

### Positive aspects
- With only a few hours left until the submission deadline, there were issues with our platform not being able to integrate with the front end and AI model, but we did not give up and created a pitch deck to explain what our project was and a fully developed AI model. I was fortunate and glad that I was able to record a demo with the flow because I was able to show the code and that it was working properly.
- Although it was not integrated with the front end, we had developed all of the code for the NEAR smart contract and the AI ​​model that analyzes vulnerabilities, so we had a GitHub repo where we could demonstrate our performance as much as possible within the hackathon period, and our The project was 90% complete, so I was really grateful and happy because there were team members who worked hard and worked hard to develop it.

### Things I learned from the hackathon
- Even in a little over a month, we realized and learned that it is important to minimize the MVP features we want to create as much as possible. 
- It may be easy as a planner, but in terms of development, I knew that it takes a long time to analyze various aspects such as the integration process and the API linking process, create the architecture, and ensure that the flow operates properly, so I decided to spend a little more time on MVP. I learned that it is also necessary to prepare an MVP only for edge points that can reduce the project to a minimum and maximize the quality and performance of the project.
