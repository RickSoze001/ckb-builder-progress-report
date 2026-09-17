# Week 28 Progress Report

## Topics Covered

#### Decentralized Kickstarter

- **Fund-routing fixes found by an exact balance accounting test**
  - **4 exploits closed before testnet: fake pledge amounts, release double-count, merge amount rewrite, unpaid campaign destruction**
  - **Backers now get their storage deposits back, only the pledge and fees are spent**
  - **100 CKB minimum pledge so every released pledge can pay out**

- **v1.2 live on testnet**
  - **Contracts redeployed, frontend and indexer updated**
  - **Verified end to end with a JoyID wallet: pledge retry on conflicts, bot release, deposit reclaim**
  - **Review requested from Officeyutong**

- **Frontend**
  - **Pledge form shows the real cost and which deposits come back**
  - **Receipt deposit reclaim button once a campaign ends**
