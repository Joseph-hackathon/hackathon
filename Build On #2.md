![image](https://github.com/user-attachments/assets/eebb9e9c-314a-4009-8d05-29b48ce07126)

# Build On
`Review of participation in the 22 hackathon.`

[Github](https://github.com/Quicktics/code) | [Video](https://vimeo.com/1025118457)

## Overview
**Quicktics** is a user-friendly platform that enables easy blockchain data analysis and visualization without the need for SQL queries.

> ✨If you want to see details, go to the [Devfolio](https://devfolio.co/projects/quickchat-80d6)

### Team
We formed a team together by recruiting team members directly from the Discord channel.
- Product Manager 1
- Full stack Dev 1

### What i did
👨🏼‍💻 Role: Product & Project Manager (PM)
- Planning
- Ideation
- Research about market | competitors | referrence
- Checek the Schedule
- Make the Architecture | Demo video flow | Github repo readme file
- Summary for the meeting reports & Submmit contents

### Track
- *QuickNode*
  - Functions
  - Streams
  - Best over-rall

## Project
Quicktics aims to democratize blockchain data analysis by making it simple, accessible, and customizable for users of all backgrounds. 
By removing the technical barriers that currently prevent many users from accessing on-chain insights, Quicktics empowers users to fully explore, analyze, and understand the Web3 ecosystem. 
With decentralized storage, customizable dashboards, and seamless integration with the QuickNode API, Quicktics is set to transform how users interact with blockchain data.

- **No Coding Required:** Users can query blockchain data and create custom dashboards without needing SQL or other programming skills.
- **Real-Time and Historical Data:** Utilize QuickNode Funtions and Streams to access real-time and historical on-chain data.
- **Cross-Platform Access:** Accessible via web, mobile app, and future integrations like Telegram mini-apps.

### Architecture
``` mermaid
sequenceDiagram
    participant User
    participant Quicktics
    participant QuickNode Functions and Streams API

    User->>Quicktics: Enters query or selects template
    Quicktics->>QuickNode Functions and Streams API: Sends request for on-chain data
    QuickNode Functions and Streams API-->>Quicktics: Returns relevant on-chain data
    Quicktics->>Quicktics: Processes data (e.g., token transfers, wallet activity)
    Quicktics->>User: Displays data in dashboard (graphs, charts, tables)
    
    alt Data storage needed
        User->>Quicktics: Requests to store data
        Quicktics->>Avail: Stores processed data
        Avail-->>Quicktics: Confirms data storage
        Quicktics-->>User: Confirms data storage in Avail
    end
```
<br></br>
1. User Input: The user enters a query or selects a pre-built template in the Quicktics dashboard.
2. QuickNode API Interaction: Quicktics connects to the QuickNode Functions and Streams API to retrieve the relevant on-chain data.
3. Data Processing: The data is processed based on the user’s query (e.g., token transfers, wallet activity).
4. Visualization: The data is displayed in the user’s custom dashboard with graphs, charts, or tables as specified.
5. Avail Storage (Future): Users can store the analyzed data in Avail for future reference or sharing.

### Result
- False

### Reason for falling (Feedback from QuickNode judges)
- Not yet

### Areas for improvement
1) Since there was only one developer, it was a little disappointing that he could not complete everything, including the backend, frontend, and smart contract, perfectly within the period.
Therefore, since we were unable to develop the front-end, we simply presented our project in the form of a CLI interface. So it was disappointing that there was no separate demo site.
2) It was disappointing that we could not utilize various on-chain API data.
The purpose of this hackathon was how to use API data, and we aimed to use such data to allow users to create their own dashboards in a custom format and easily create them using AI, but unfortunately, various API data and It was disappointing that we couldn't develop the front end.
3) We tried to use Avail DA to safely store dashboards and various data created by users in a custom format, but we were disappointed that we could not complete this within the period.
4) Overall, it was judged that it was not a feature in the MVP version that could be completed within the period, and it was disappointing because I felt that it could have been completed if more developers had been recruited if necessary.
5) English presentation required.

### Positive aspects
- We were fortunate and thankful that one developer was able to import Quicknode's on-chain data through CLI and complete development at least a little in line with our goals and desired direction.

### Things I learned from the hackathon
- I learned that the MVP function initially planned must be actively changed and modified depending on the team members or personnel, so that there is a high possibility of a high-quality project as a result.
