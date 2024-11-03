![image](https://github.com/user-attachments/assets/609cd100-79a5-47d0-b3c5-77065d2ca798)

# [REDACTED] Hackathon
`Review of participation in the 21 hackathon.`

[Demo](https://reception-seven.vercel.app/) | [Pitchdeck](https://drive.google.com/file/d/1gn9eo1JHbGmijGPWTwsq1gkfCLY_8rKp/view?usp=sharing) | [Github](https://github.com/Julius-Ky/reCeption) | [Video](https://youtu.be/puJjyTeLRjY)

## Overview
**reCEPTION** is an AI-powered security platform that offers functionality similar to reCAPTCHA, providing automated verification solutions for both Web2 and Web3 environments. The project aims to enhance the security and quality of smart contracts and provide automated validation solutions for users and developers.

> ✨If you want to see details, go to the [Devpost](https://devpost.com/software/not-yet-ud294o)

### Team
We formed a team together by recruiting team members directly from the Discord channel.
- Product Manager 1
- AI Engineer 1
- Software Engineer 1
- Smart contract 1
- Frontend developer 1

### What i did
👨🏼‍💻 Role: Product & Project Manager (PM)
- Planning
- Ideation
- Research about market | competitors | referrence
- Checek the Schedule
- Make the Architecture | Demo video flow | Pitchdeck | Github repo readme file | Diagram
- Presentation
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
- *Bitte Wallet*

## Project
![image](https://github.com/user-attachments/assets/53dc68d9-378a-493c-bfe9-79c28cc9a673)
<br></br>

1. **AI-Based Smart Contract Analysis**:
    - Users upload their smart contract code for analysis, where AI identifies security vulnerabilities, code flaws, and potential scams.
2. **Automated Security Checks and Corrections**:
    - Based on the analysis, the AI suggests and implements modifications, including security patches and performance optimizations.
    - Provides a feature to automatically deploy the modified code within the platform.
3. **Detailed Reporting**:
    - Generates comprehensive reports detailing the issues found, modifications made, and explanations to help users understand improvements.
    - Reports are available for download in CSV and PDF formats.
4. **Admin Console**:
    - An admin console allows administrators to set up and manage reCeption features on their own websites.
    - Supports reCAPTCHA-like functionality for security validation on web pages.
5. **API Provision**:
    - Offers API access to analysis results and data, enabling e-commerce platforms or Web3 applications to use these as security solutions.

### Diagram
``` mermaid
sequenceDiagram
participant User
participant E-Commerce as E-Commerce (Platform)
participant reCeption
participant NEAR

User ->> E-Commerce: 1. Login
E-Commerce -->> E-Commerce: Response the user info
User ->> E-Commerce: 2. Product Purchase (Cryptocurrency)
E-Commerce ->> reCeption: 3. Send Smart Contract (Payment)
reCeption ->> NEAR: 4. Smart Contract Analysis (NEAR AI)
NEAR -->> NEAR: Handles verification & fee charges for interactions
NEAR ->> reCeption: 5. Return Analysis result
reCeption ->> User: 6. Return Safety Judgment
User ->> E-Commerce: 7. Share whether to run (Check Box or Payment Approve)
E-Commerce -->> E-Commerce: Response payment
E-Commerce ->> NEAR: 8. Save contract data (Normal/Abnormal Classification)
```

### Result
- Not yet

### Reason for falling (Feedback from Aptos judges)
- Not yet

### Areas for improvement
1) We completed all of the smart contracts and AI models for each part, but in the process of integrating with the front end, there was a problem with the integration of the AI ​​model due to the high usage environment on PCs such as GPUs, so it was unfortunate that it could not be completed as a perfect platform.
2) This Near Protocol Hackathon had many sponsored tracks that focused on AI technology, which was the core of this hackathon, but among the sponsored tracks, we used **ZettaBlock** and **Public AI**'s API to import on-chain data and train it in our AI model to model it. We tried to improve and collect and pre-process a lot of data, but there was not enough data related to the vulnerabilities we wanted, and there was a problem integrating the API, so it was disappointing that we could not utilize the sponsor tracks.
3) Our MVP was to complete all of the API docs page, file upload page, and admin console page, but this MVP was not in a phase that could be completed within the period and had many overloaded functions, so it was difficult to manage these schedules. As a product manager, I was a bit lacking and was disappointed.
4) English presentation required.

### Positive aspects
- 

### Things I learned from the hackathon
- 
