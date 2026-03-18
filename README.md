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

This project was completed during the **final year of our Polytechnic/Diploma** as a team project.  
The main goal was to create a healthcare platform where records can be stored and accessed in a more secure and transparent way using blockchain technology.

---

## Requirements

1.Install nodeJs

* [Node JS](https://nodejs.org/en/download/)

2.Install Ganache

* [Ganache Truffle](https://www.trufflesuite.com/ganache)

3. Download IPFS (kubo)

* [IPFS Kubo](https://dist.ipfs.tech/#go-ipfs)

  - configure ipfs refer: https://github.com/shamil-t/ehr-blockchain/issues/15#issuecomment-1333342345

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
