---
title: Atlas Edit Weekly Cycle Proposal - November 23, 2026
summary: This Atlas edit proposal 1) adds NFATs and the NFAT Pilot, 2) adds the Swap Asset Facet, 3) adds the Spark Diamond PAU to the Ethereum Mainnet PAS, 4) allows Demand Side Reward payments through the Monthly Settlement Cycle, 5) names the Sky Surplus Buffer as the source of buffer transfers, 6) allows smart contracts to hold the Allocator role on Morpho vaults, 7) updates the ERC-4626 facet's Highest Production Deposit rate limit, 8) prepares the Osero Artifact for the NFAT Pilot, 9) raises the Osero ERC-4626 deposit and CCTP rate limits, 10) adds Yearn Finance as an Osero Distribution Reward Instance, 11) makes housekeeping updates.
discussion_link: https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-23/28446
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 480000000 }
            ]
        }
        - {type : default, value : 2 }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2026-11-23T16:00:00
end_date: 2026-11-26T16:00:00
---

# Atlas Edit Weekly Cycle Proposal - November 23, 2026

The Core Facilitators have placed an [Atlas Edit Weekly Cycle Proposal](https://sky-atlas.io/#14e99d92-71fc-44d9-9dbf-933bce2e1b32) into the [voting system](https://vote.sky.money/polling) [on behalf of Ranked Delegate Bonapublica](https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-23/28446/3). This Governance Poll will be active for three days beginning on Monday, November 23 at 16:00 UTC.

**This is a binary vote.**

- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community may vote in this poll to express support or opposition to the following Atlas Edit Weekly Cycle Proposal:

- [Atlas Edit Pull Request](https://github.com/sky-ecosystem/next-gen-atlas/pull/387)
- [Proposal Discussion Thread](https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-23/28446)

A brief summary of this Atlas Edit has been provided by the Author and is shown below:

_This proposal includes the following edits:_

- _**Add NFATs And The NFAT Pilot** - Defines NFATs and NFAT Facilities and specifies the five-phase NFAT Pilot and the Test NFAT Facility._
- _**Add The Swap Asset Facet** - Adds the Swap Asset Facet and its Controller functions to the Diamond PAU documents, ahead of its approval on the Beacon in a future Executive Vote._
- _**Add The Spark Diamond PAU To The Ethereum Mainnet PAS** - Adds the Spark Diamond PAU to the Ethereum Mainnet PAS, to be configured in a future Executive Vote._
- _**Allow Demand Side Reward Payments Through The Monthly Settlement Cycle** - Allows Distribution Reward, Integration Boost and Pioneer Rewards payments to be made from the Demand Side Buffer or within the Monthly Settlement Cycle._
- _**Name The Sky Surplus Buffer As The Source Of Buffer Transfers** - Specifies that the monthly buffer transfers and Demand Side Buffer top-ups are made from the Sky Surplus Buffer._
- _**Allow Smart Contracts To Hold The Allocator Role On Morpho Vaults** - Allows a smart contract or the Multisig that holds the Curator role to hold the Allocator role on Morpho vaults._
- _**Update The ERC-4626 Facet's Highest Production Deposit Rate Limit** - Records 15,000,000 USDC and 10,000,000 USDC per day as the highest deposit rate limit operated in production._
- _**Prepare The Osero Artifact For The NFAT Pilot** - Adds the Test NFAT Facility as an Osero Allocation System Primitive Instance, with subscribe rate limits for each pilot phase._
- _**Raise The Osero ERC-4626 Deposit And CCTP Rate Limits** - Raises Osero's Gauntlet Instance deposit rate limits to 50,000,000 USDC and 50,000,000 USDC per day, and its CCTP rate limits to 25,000,000 USDC._
- _**Add Yearn Finance As An Osero Distribution Reward Instance** - Adds reward code 3017 (Yearn Finance) to Osero's Distribution Reward Instances._
- _**Housekeeping Updates** - Corrects the X Layer Spark-curated Morpho USDC Vault co-curator addresses, updates the PAU Factory and Administered Agent Factory addresses and removes the PAU Assembler, adds the Morpho Vault Change Note Template location, points Osero's rate limit values to each Instance Configuration Document, and updates completed implementation language._

## Outcomes

This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation for Atlas Edit Weekly Cycle Proposals is currently set to **480,000,000 SKY**.

**If the votes for the 'Yes' option exceed the votes for the 'No' option AND the votes for the 'Yes' option equal or exceed 480,000,000 SKY, then the following actions will be taken:**

- The associated Pull Request will be merged into The Atlas.

---

## Resources

If you are new to voting in the Sky Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [Sky Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).
