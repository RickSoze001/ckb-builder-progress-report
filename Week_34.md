# Week 34 Progress Report

## Topics Covered

#### Decentralized Kickstarter

- **Finished the contract fixes from Officeyutong's second review**
  - **A campaign cell can no longer be moved out from under its lock during an update**
  - **Receipt checks are tightened so a receipt only goes with its own pledge**

- **Fixed the 10 issues from his review of those fixes**
  - **A pledge too short for its lock can no longer count toward a goal and then get stuck**
  - **A receipt can no longer be destroyed while its pledge stays locked, and every receipt in a transaction is now checked, not just the first**
  - **Other cells can no longer borrow a campaign's pre-deadline exemption, and destroying a campaign now counts every version of the contract**
  - **Deployer key is limited to testnet, and the app builds receipts through the shared helper**

- **Redeployed to testnet twice and tested end to end**
  - **New campaign, campaign lock and receipt contracts are live, and pledge and pledge lock were reused, saving about 54k CKB**
  - **Devnet tests all pass: 27 attack tests, 36 accounting, 18 accumulator, and 39 across the two lifecycle suites**
  - **On the reseeded demo, the bot released one campaign to its creator and refunded the other, with no one's help**
