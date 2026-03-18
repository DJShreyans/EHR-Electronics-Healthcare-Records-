# EHR 2.0

EHR 2.0 is an Electronics Healthcare Records project developed as a **final-year diploma/polytechnic project**.  
It is designed to improve the management of healthcare records by combining web technologies with blockchain concepts for better security, transparency, and reliability.

This project was built collaboratively by:

- **Shreyans Jain**
- **Durvesh Mhatre**
- **Dipak Shedge**
- **Harsh Jagtap**

---

## Features

- Secure Electronic Healthcare Records management
- Appointment handling
- PDF upload functionality
- Blockchain-based integration for record security
- User-friendly web interface
- MetaMask wallet support
- IPFS support for decentralized file storage

---

## Tech Stack

- **Frontend:** React.js / JavaScript
- **Backend:** Node.js
- **Blockchain:** Ethereum, Truffle, Ganache
- **Storage:** IPFS (Kubo)
- **Wallet Integration:** MetaMask
- **Hosting:** Firebase

---

## Project Background

The healthcare industry is rapidly moving towards digital transformation, yet many systems still rely on fragmented, centralized, and insecure methods of storing patient records. Traditional Electronic Health Record (EHR) systems often suffer from issues such as data breaches, lack of interoperability, limited patient control, and dependency on centralized authorities.

To address these challenges, **EHR 2.0** was developed as a next-generation healthcare record management system that integrates modern web technologies with blockchain and decentralized storage solutions.

The core idea behind this project is to enhance **data security, transparency, and accessibility** while ensuring that sensitive medical information remains tamper-proof and trustworthy. By leveraging **blockchain technology (Ethereum)**, the system ensures that once records are stored, they cannot be altered without proper authorization, thereby maintaining data integrity.

Additionally, the project utilizes **IPFS (InterPlanetary File System)** for decentralized file storage, allowing large medical files such as reports and PDFs to be stored securely and efficiently without relying on centralized servers. This reduces the risk of data loss and improves system scalability.

The integration of **MetaMask** enables secure user authentication and interaction with blockchain smart contracts, ensuring that only authorized users (patients, doctors, or administrators) can access or modify records.

This project was developed during the final year of our diploma/polytechnic as a team effort, with the objective of exploring real-world applications of blockchain in healthcare. It reflects our attempt to solve critical problems in medical data management by combining concepts from web development, distributed systems, and cybersecurity.

Overall, EHR 2.0 represents a step towards building a more **secure, decentralized, and patient-centric healthcare ecosystem**.
---

## Requirements

1.Install nodeJs

* [Node JS](https://nodejs.org/en/download/)

2.Install Ganache

* [Ganache Truffle](https://www.trufflesuite.com/ganache)

3. Download IPFS (kubo)

* [IPFS Kubo](https://dist.ipfs.tech/#go-ipfs)

4.Add Metamask Extension in Browser

* [Metamask Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en-US)

5. open cmd in project directory

```
npm install --force
```

5.open cmd/terminal as Administrator and type

```
npm install -g truffle
```

6.open Ganache
 
 *  New Workspace
 *  AddProject
 *  Select truffle-config.js in Project Directory
 *  Save Workspace

7.Compile and migrate Contracts
 ```
 truffle migrate
 ```
8. Run Server

```
npm start
```
