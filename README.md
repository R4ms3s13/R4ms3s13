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

**QA**
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white)

---

### 🚀 Featured projects

#### [Reps.io](https://github.com/R4ms3s13/Reps.io)
Strength training tracker built as an event-driven microservices system. Angular frontend, two NestJS services (workouts on MongoDB, users/auth on PostgreSQL) communicating over RabbitMQ pub/sub with a stateless Python analytics worker (1RM, Wilks score, plateau detection, AI coaching tips). Redis caching, JWT auth, hexagonal architecture on every backend service, fully dockerized.
`Angular` `NestJS` `Python/Flask` `MongoDB` `PostgreSQL` `Redis` `RabbitMQ` `Docker`

---

### 💼 Real-world experience

| Project | What it is | Stack |
|---|---|---|
| **WeGo** | Mobility app backend — designed and developed the backend's business logic in clean, scalable Cloud Functions built to handle a high volume of users, with push notifications and transactional messaging (SendGrid, Twilio) on top of Firestore/Realtime Database. | `Firebase` `Cloud Functions` `TypeScript` `Firestore` |
| **Domoblock** | Fintech/tokenized real-estate investment platform. Designed and developed the entire backend — NestJS microservices (auth, KYC, payments, investments, blockchain, notifications) in hexagonal/DDD architecture over RabbitMQ, in an Nx monorepo — and led a team of 4 building it. Automated the end-to-end purchase flow — MangoPay eWallet integration, automated withdrawals, token purchases, and top-ups. On-chain token minting on Polygon. Deployed on Google Cloud Run. The platform has accumulated over €58 million invested by users across its projects to date, several already distributing dividends. | `NestJS` `Angular` `RabbitMQ` `PostgreSQL` `Firebase` `Google Cloud Run` `Docker` |
| **MitSoftware — Main website** | Modernized the company's main website, migrating it from WordPress to a headless stack: a static Astro frontend and a Strapi CMS backend. Automated content publishing: a Strapi webhook redeploys and regenerates the site (SSG) on every content change, serving auto-generated bilingual (ES/EN) content. | `Astro` `Strapi` `Node.js` `Docker` |
| **Notrack** | Secure file-tracking platform with version history. Designed and developed the entire backend (Fastify + MongoDB) and collaborated on the Next.js/React frontend, with wallet-based auth verified on-chain against a BSC access-control smart contract (Ethers.js) I designed, built, and deployed with Hardhat and Remix IDE. AWS KMS encryption, S3 file storage, OnlyOffice document editing/preview, and Socket.io real-time events; a NestJS service handles admin/chat/auth. Runs on AWS EC2 behind Nginx. Commissioned a DragonJar S.A.S. security audit (ethical hacking): of 19 vulnerabilities found (none critical), 18 were resolved — [see the audit report](https://notrack.io/ACTA-notrack.pdf). | `Next.js` `React` `NestJS` `Fastify` `MongoDB` `Solidity` `Hardhat` `Remix IDE` `Ethers.js` `AWS EC2` `AWS S3` `AWS KMS` `OnlyOffice` `Nginx` `Socket.io` |
| **Axinfy** (formerly Defily) | DeFi protocol on Polygon — smart contracts that decentrally manage user finances: membership, NFT accounts, staking, treasury and liquidity vaults behind UUPS upgradeable proxies, with automated deployment/verification tooling. A standalone Express/MongoDB microservice automates unique NFT generation and pins metadata to IPFS via Pinata. Next.js/React dapp frontend for wallet connection and vault management. The protocol reached a TVL of ~$219,065 USDC as Defily, and holds around ~$106,500 USDC in its Axinfy relaunch; the platform surpassed 1,000 NFTs generated and purchased by users. | `Next.js` `React` `Solidity` `Hardhat` `OpenZeppelin` `Polygon` `Express` `MongoDB` `IPFS/Pinata` |
| **LVLX** | NFT platform on BNB Smart Chain — ERC-1155 NFT contracts with a referral system and token staking. | `Solidity` `ERC-1155` `Hardhat` |
| **Dgallery** | UUPS-upgradeable NFT marketplace with on-chain dividends distribution, deployed and verified on BNB Smart Chain. | `Solidity` `Hardhat` `OpenZeppelin` `NFT Marketplace` |

---

### 📫 Reach me

[Portfolio](https://ramses-medina.vercel.app/) · [GitHub](https://github.com/R4ms3s13) · [LinkedIn](https://www.linkedin.com/in/ramses-medina-85421a22a/)
