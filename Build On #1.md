![image](https://github.com/user-attachments/assets/eebb9e9c-314a-4009-8d05-29b48ce07126)

# Build On
`Review of participation in the 22 hackathon.`

[Demo](https://reception-seven.vercel.app/) | [Pitchdeck](https://drive.google.com/file/d/1gn9eo1JHbGmijGPWTwsq1gkfCLY_8rKp/view?usp=sharing) | [Github](https://github.com/Julius-Ky/reCeption) | [Video](https://youtu.be/puJjyTeLRjY)

## Overview
**DataDiscovery** is a data asset management platform that collects, visualizes, and manages survey and on-chain data, allowing companies to purchase and utilize it.

> ✨If you want to see details, go to the [Devfolio](https://devfolio.co/projects/discovey-5c68)

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
- Make the Architecture | Demo video flow | Pitchdeck | Github repo readme file | Diagram | Prototype
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

### Prototype
> Before

#### API Docs page
<img src="https://github.com/user-attachments/assets/2070dcb3-71e8-4f1c-8100-b0717b442b96" width="500" height="900">
<br></br>

#### Admin console page
<img src="https://github.com/user-attachments/assets/51b6df3b-7009-432e-be1e-14d39f65386b" width="500" height="700">
<br></br>

> After

#### API Docs page
- In this hackathon, we simplified the API documentation page and created a page with only the key generation function.

![image](https://github.com/user-attachments/assets/7222bc89-70c9-4ccc-b6a8-7c6800ad1117)

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
- Through this Near Hackathon, I learned that Near Protocol wants projects on how to utilize current AI and blockchain technology more effectively and is trying to actively utilize AI technology. And currently, Near AI has not yet developed a model, but I am looking forward to creating Near's own AI model by collecting data with various sponsors who participated this time.
