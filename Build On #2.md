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
1) In terms of retrieving on-chain data using the Quicknode API, I was disappointed because I thought it was insufficient to retrieve various types of data and more detailed meaningful data.
2) It would have been nice to have content that imports various data, filters and preprocesses the data on its own, and provides it in a new data format, but it was unfortunate that there was not enough time to develop the content.
3) English presentation required.

### Positive aspects
- The data itself from the act of receiving surveys from users is the most meaningful feedback for companies and data that can be used for UX and marketing, so I am proud to have developed a platform where such survey data can be easily obtained, and I am proud to provide it to my team members. thank you
- Survey data contains user information, so we were thinking about how to secure this. A team member suggested the idea of ​​encrypting data using zk in Avail and uploading it to the on-chain, so we could develop and complete it and show it as a demo. It was really nice to have it.

### Things I learned from the hackathon
- Through this hackathon, I learned that Quicknode provides its own marketplace that seems to provide API applications to various data services, such as the Chrome Web Store, so that you can utilize the data collected by various services as well as APIs.
