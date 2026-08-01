### Hi, I'm Ramses Medina 👋

Full-stack / backend-leaning software engineer. I build event-driven and microservices systems, ship smart contracts, and I'm comfortable owning a product from the database schema up to the cloud infrastructure it runs on.

---

### 🧰 Tech I work with

**Backend**
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![Fastify](https://img.shields.io/badge/-Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java%208-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**Frontend**
![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Blockchain**
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Hardhat](https://img.shields.io/badge/-Hardhat-FFF100?style=flat-square&logo=ethereum&logoColor=black)
![Remix IDE](https://img.shields.io/badge/-Remix%20IDE-000000?style=flat-square&logo=ethereum&logoColor=white)
![IPFS](https://img.shields.io/badge/-IPFS-65C2CB?style=flat-square&logo=ipfs&logoColor=white)

**Databases**
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/-AWS%20(EC2%20|%20S3%20|%20KMS)-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/-Google%20Cloud%20Platform-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloud Functions](https://img.shields.io/badge/-Cloud%20Functions-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Messaging & Real-Time**
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Socket.io](https://img.shields.io/badge/-Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Tools**
![Jira](https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/-Notion-000000?style=flat-square&logo=notion&logoColor=white)
![Slack](https://img.shields.io/badge/-Slack-4A154B?style=flat-square&logo=slack&logoColor=white)

---

### 🚀 Featured projects

#### [Reps.io](https://github.com/R4ms3s13/Reps.io)
Strength training tracker built as an event-driven microservices system. Angular frontend, two NestJS services (workouts on MongoDB, users/auth on PostgreSQL) communicating over RabbitMQ pub/sub with a stateless Python analytics worker (1RM, Wilks score, plateau detection, AI coaching tips). Redis caching, JWT auth, hexagonal architecture on every backend service, fully dockerized.
`Angular` `NestJS` `Python/Flask` `MongoDB` `PostgreSQL` `Redis` `RabbitMQ` `Docker`

---

### 💼 Real-world experience

| Project | What it is | Stack |
|---|---|---|
| **WeGo** | Mobility app backend — Cloud Functions handling notifications and transactional messaging (SendGrid, Twilio) on top of Firestore/Realtime Database. | `Firebase` `Cloud Functions` `TypeScript` `Firestore` |
| **Domoblock** | Fintech/tokenized real-estate investment platform. Nx monorepo, Angular frontend, NestJS microservices (auth, KYC, payments, investments, blockchain, notifications) in hexagonal/DDD architecture over RabbitMQ, deployed on Google Cloud Run. | `NestJS` `Angular` `RabbitMQ` `PostgreSQL` `Firebase` `Google Cloud Run` `Docker` |
| **MitSoftware — Main website** | Headless CMS backend for the company's main website. | `Strapi` `Node.js` `Docker` |
| **Notrack** | Secure file-tracking platform. Fastify + MongoDB main backend with wallet-based auth verified on-chain against a BSC access-control smart contract (Ethers.js), AWS KMS encryption, S3 file storage, OnlyOffice document editing/preview, and Socket.io real-time events; a NestJS service handles admin/chat/auth, plus separate Fastify microservices for file processing. Runs on AWS EC2 behind Nginx. I built the access-control smart contracts myself with Hardhat and Remix IDE. | `NestJS` `Fastify` `MongoDB` `Solidity` `Hardhat` `Remix IDE` `Ethers.js` `AWS EC2` `AWS S3` `AWS KMS` `OnlyOffice` `Nginx` `Socket.io` |
| **Axinfy** (formerly Defily) | DeFi protocol on Polygon — membership, NFT accounts, staking, treasury and liquidity vaults behind UUPS upgradeable proxies, with automated deployment/verification tooling. Includes a standalone Express/MongoDB microservice that pins NFT metadata to IPFS via Pinata for marketplace visualization. | `Solidity` `Hardhat` `OpenZeppelin` `Polygon` `Express` `MongoDB` `IPFS/Pinata` |
| **LVLX** | NFT platform on BNB Smart Chain — ERC-1155 NFT contracts with a referral system and token staking. | `Solidity` `ERC-1155` `Hardhat` |
| **Dgallery** | UUPS-upgradeable NFT marketplace with on-chain dividends distribution, deployed and verified on BNB Smart Chain. | `Solidity` `Hardhat` `OpenZeppelin` `NFT Marketplace` |

---

### 📫 Reach me

[GitHub](https://github.com/R4ms3s13) · [LinkedIn](https://www.linkedin.com/in/ramses-medina-85421a22a/)
