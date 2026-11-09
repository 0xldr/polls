---
title: Atlas Edit Weekly Cycle Proposal - November 9, 2026
summary: This Atlas edit proposal 1) adds weETH as eligible collateral for Morpho vaults, 2) adds a Morpho vault curation governance process, 3) defines the Governance Poll process, 4) replenishes the Demand Side Buffer through the Monthly Settlement Cycle, 5) updates the recognized audit firm categories, 6) adds the Spark Foundation grant for December 2026, 7) adds the Grove Foundation grant for November 2026, 8) adds the CCTP Facet Controller functions, 9) adds Osero to the Base Parallelized Allocation System, 10) updates the Osero Artifact for the November 19, 2026 Executive Vote, 11) clarifies audit recordkeeping requirements, 12) removes references to the Powerhouse system.
discussion_link: https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-09/28389
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
start_date: 2026-11-09T16:00:00
end_date: 2026-11-12T16:00:00
---

# Atlas Edit Weekly Cycle Proposal - November 9, 2026

The Core Facilitators have placed an [Atlas Edit Weekly Cycle Proposal](https://sky-atlas.io/#14e99d92-71fc-44d9-9dbf-933bce2e1b32) into the [voting system](https://vote.sky.money/polling) [on behalf of Ranked Delegate Bonapublica](https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-09/28389/2). This Governance Poll will be active for three days beginning on Monday, November 9 at 16:00 UTC.

**This is a binary vote.**

- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community may vote in this poll to express support or opposition to the following Atlas Edit Weekly Cycle Proposal:

- [Atlas Edit Pull Request](https://github.com/sky-ecosystem/next-gen-atlas/pull/377)
- [Proposal Discussion Thread](https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-09/28389)

A brief summary of this Atlas Edit has been provided by the Author and is shown below:

_This proposal includes the following edits:_

- _**Add weETH As Eligible Collateral For Morpho Vaults** — Adds weETH as eligible collateral for Morpho vaults and sets a 60,000 weETH exposure cap shared between Spark and Grove._
- _**Add Morpho Vault Curation Governance Process** — Defines which changes to Morpho vaults used by Prime Agents require governance approval and which require only disclosure, with announcement and reporting requirements. Adds a Morpho Vault Change Note Template that may be used instead of the Technical Scope Template for qualifying changes._
- _**Define The Governance Poll Process** — Consolidates the rules for creating, reviewing, publishing and voting on Governance Polls into a single process definition._
- _**Replenish The Demand Side Buffer Through The Monthly Settlement Cycle** — Replenishes the Demand Side Buffer monthly through the Monthly Settlement Cycle and updates how its payments are recognized as Expenses._
- _**Update Recognized Audit Firm Categories** — Renames the audit firm tiers to Category 1 and Category 2, and moves OpenZeppelin, ConsenSys Diligence and Trail Of Bits to Category 1._
- _**Add Spark Foundation Grant For December 2026** — Authorizes the December 2026 grants to the Spark Foundation and the Spark Asset Foundation._
- _**Add Grove Foundation Grant For November 2026** — Authorizes the November 2026 grant to the Grove Foundation._
- _**Add CCTP Facet Controller Functions** — Adds the CCTP Facet's Controller functions and specifies the ERC-4626 emergency withdrawal on chains other than Ethereum Mainnet._
- _**Add Osero To The Base Parallelized Allocation System** — Adds Osero's Diamond PAU on Base ahead of the November 19, 2026 Executive Vote._
- _**Update The Osero Artifact For The November 19, 2026 Executive Vote** — Adds Osero's allocations on Base and updates the parameters of its Osero x Gauntlet USDC Prime vault._
- _**Clarify Audit Recordkeeping Requirements** — Clarifies where audit records for Spells and deployments must be published._
- _**Remove References To The Powerhouse System** — Removes references to the planned Powerhouse system across the Atlas._

## Outcomes

This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation for Atlas Edit Weekly Cycle Proposals is currently set to **480,000,000 SKY**.

**If the votes for the 'Yes' option exceed the votes for the 'No' option AND the votes for the 'Yes' option equal or exceed 480,000,000 SKY, then the following actions will be taken:**

- The associated Pull Request will be merged into The Atlas.

---

## Resources

If you are new to voting in the Sky Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [Sky Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).
