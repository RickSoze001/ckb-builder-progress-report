# Week 24 Progress Report

## Topics Covered

#### Decentralized Kickstarter

- **Community feedback on v1.2 design**
  - **RetricSu and Arthur reviewed the v1.2 fee/treasury proposal on Nervos Talk**
  - **Fee rate raised from 3% to 5% on RetricSu's recommendation (config cell makes it adjustable later anyway)**
  - **Arthur surfaced a finalization trust gap in v1.1: the campaign-type script doesn't verify Success/Failed against actual raised funds, only structural invariants**

- **Internal pre-review of v1.1 contracts**
  - **Reviewed all 5 contracts looking for trust-boundary issues before external audit**
  - **3 medium-severity issues identified, all folded into v1.2 scope**
  - **Closes the audit surface area before paying for external review**

- **Rebrand decision: CrowdCell**
  - **"Kickstarter" not viable on mainnet for trademark reasons**
  - **Picked CrowdCell: plays on "Crowd-Sell" with CKB cell substitution**
