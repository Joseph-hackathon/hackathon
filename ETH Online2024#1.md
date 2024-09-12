![image](https://github.com/user-attachments/assets/60da6a1f-ccf3-48ff-818d-e362ff12b915)

# ETH Online 2024

`Review of participation in the 18 hackathon.`

## Contents
- [Github repo](https://github.com/AeroDump/contracts) | [Demo Site](https://aerodump.vercel.app/)

### Overview:
Cutting-edge platform designed to simplify and automate the distribution of tokens for users and project owners across multiple blockchain networks.

✨If you want to see details, go to the [Showcase](https://ethglobal.com/showcase/aerodump-4z48m)

---
### Background:
We formed a team together by recruiting team members directly from the Discord channel and Telegram.
- Project Manager 1
- Smart Contract 2
- Software Engineer 2

---
### Track:

- *LayerZero*
- *Sign Protocol*
- *Chainlink*
- *Web3Auth*

---
### Project:
![image](https://github.com/user-attachments/assets/e9305949-4090-4ca0-87b8-1d2b3b73c27c)

> **AeroDump**

`AeroDump` is a cutting-edge platform designed to simplify and automate the distribution of tokens for users and project owners across multiple blockchain networks. Built to support airdrops, marketing event rewards, and large-scale token transfers, AeroDump leverages the power of automation, cross-chain interoperability, and secure vaults to provide an efficient, hands-free solution for bulk token distribution.

> **Architecture**

![image](https://github.com/user-attachments/assets/cf062c58-ea84-4724-aa71-c8107afda6ef)

> **User Journey**
```mermaid
graph TD;
    Sign-In/Sign-Up-->Register-Project;
    Register-Project-->Upload-CSV;
    Register-Project-->Fill-the-Text;
    Upload-CSV-->Deposit-Vault;
    Fill-the-Text-->Deposit-Vault;
    Deposit-Vault-->Auto-Distribution;
    Auto-Distribution-->Check-History;
```

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
1) Overall, AeroDump's service is a service that includes detailed development elements and functions. Therefore, we exchange opinions on the requirements for each sponsor track we will submit, what technology we will use and how we will do it, the current status of the project, how users use the platform, and how the platform should operate. I had to share my opinion with the development team members about this, but since I lack a bit of knowledge in the technical area, it was a bit difficult to talk about it, and there were situations where we couldn't understand each other, which was disappointing. (However, in this regard, I tried to understand what the developer and project manager was talking about by asking an experienced developer who was in the middle of me to understand what he was saying and what he wanted. Afterwards, we were able to further develop the platform's functions and operating principles by gaining sufficient understanding with the developer.)
2) In situations like the one above, I, as the project manager, should have played that role, but instead I asked for help from the development team members and received it, so I felt a little disappointed with myself and felt like I was still lacking.
3) English presentation required

---
### Positive aspects:
- Since the AI ​​engineer did not know much about blockchain, he had to study in parallel while developing the model. However, she developed a very good AI model by continuing to study until the end, understanding it on her own, and communicating with developers who knew smart contract code among our team members.
Therefore, during the local demo, an amazing project emerged, so it was great to think that the AI ​​model could be considered a model to the extent that it could be used not only for this hackathon but also for actual projects.
- Since there was no front end, the demo platform lacked quality and was unable to be fully functionally integrated, so the submission was closed. However, the rest of the team tried to integrate it until the end, and the front end was also briefly developed and uploaded to the server, so a demo link was created and an image was able to show what kind of platform it was.
- Since this hackathon was a Hedera hackathon, there was a lack of edge points on how to use Hedera, but the team members thought together and used a message in a place called Topic within the Hedera contract to provide the results of the analysis to our platform. The idea was to store the data in on-chain storage by putting it in a part. So, we were able to utilize this idea by linking it to a business model on our platform.

---
### Things I learned from the hackathon:
- I tried to provide a multi-chain service using Chainlink's CCIP, but a development team member did research and found that Layer Zero also provides CCIP, so since we are using the vault service at Layer Zero anyway, I suggested that we also utilize CCIP as well, so Layer Zero I found out that it also provides CCIP functionality. (After thinking about it, I thought that Layer Zero is also a bridge service and would provide sufficient CCIP functions.)
- I learned from the development team members that this logic is quite tricky and difficult when using Chainlink automation to automate the contract code so that the contract can be automatically executed in the Layer Zero vault and distributed to the wallets of desired users. It is done. Simply, since the function called Chainlink Automation is specialized for automation, I thought that it would be possible to just add the contract address to be automated within a few lines of code, but it was not true and was only shared that it was a little more complicated, so I first learned about it.

---
### What i did
👨🏼‍💻 Role: Product & Project Manager (PM)

- Ideation
- Planning
- Research about market, competitors, referrence
- Determine development priorities and organize strategic sponsor tracks
- Checek the Schedule
- Make the Architecture | User Flow
- Summary for the meeting reports & Submmit contents
