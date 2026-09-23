# Week 29 Progress Report

## Topics Covered

#### Decentralized Kickstarter

- **CrowdCell relaunch is live**
  - **New name and visual identity, built on the CKB cell model**
  - **New landing page explaining how pledges settle and who can do what, checked against the contracts**
  - **The app moves to its own page, with a roadmap and FAQ on the landing page**

- **Campaign deadlines fixed**
  - **Deadlines ended about 6 days early on a 30-day campaign: the form ignored time zones and assumed 10-second blocks, while testnet runs at 8**
  - **The 1-hour minimum deadline is now shown on the form instead of applied silently**
  - **"Destroy campaign" only appears once the contract allows it, about 180 days after the deadline**

- **Pledges under load**
  - **Three simultaneous pledges to one campaign now all land (450 of 450 CKB, previously 100)**
