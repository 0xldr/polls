---
title: Atlas Edit Weekly Cycle Proposal - November 2, 2026
summary: This Atlas edit proposal 1) adds Temporary Capital Ratio requirements, 2) clarifies Morpho vault deployment verification responsibility and timing, 3) updates the Osero Gauntlet Instance parameters, 4) removes the planning and review documents from the Distribution Reward and Integration Boost Invocation protocols, 5) records the September 24, 2026 grant transfers for Spark and Grove, 6) records the Osero Gauntlet Vault Timelocks and Force-Deallocate penalty, 7) makes housekeeping updates.
discussion_link: https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-02/28368
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
start_date: 2026-11-02T16:00:00
end_date: 2026-11-05T16:00:00
---

# Atlas Edit Weekly Cycle Proposal - November 2, 2026

The Core Facilitators have placed an [Atlas Edit Weekly Cycle Proposal](https://sky-atlas.io/#14e99d92-71fc-44d9-9dbf-933bce2e1b32) into the [voting system](https://vote.sky.money/polling) [on behalf of Ranked Delegate BLUE](https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-02/28368/2). This Governance Poll will be active for three days beginning on Monday, November 2 at 16:00 UTC.

**This is a binary vote.**

- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community may vote in this poll to express support or opposition to the following Atlas Edit Weekly Cycle Proposal:

- [Atlas Edit Pull Request](https://github.com/sky-ecosystem/next-gen-atlas/pull/369)
- [Proposal Discussion Thread](https://forum.skyeco.com/t/atlas-edit-weekly-cycle-proposal-week-of-2026-11-02/28368)

A brief summary of this Atlas Edit has been provided by the Author and is shown below:

_This proposal includes the following edits:_

- _**Add Temporary Capital Ratio Requirements** — Applies temporary Instance Total CRRs approved by the Core Council to listed Instances from November 1, 2026, without replacing a higher Prime Agent Artifact CRR or a 100% CRR._
- _**Clarify Morpho Vault Deployment Verification Responsibility And Timing** — Makes Prime Agents responsible for verifying every Morpho vault they deploy or enable to receive capital, and requires Prime Spell reviewers to review the resulting Morpho Verification Report before signing off the Prime Spell for deployment._
- _**Update The Osero Gauntlet Instance Parameters** — Increases the Maximum Exposure for Osero's Gauntlet USDC Prime Morpho Vault V2 Instance from 10,000,000 to 25,000,000 USDC, lowers its Capital Ratio Requirement from 25% to 10%, and raises its deposit rate limit to 15,000,000 USDC with a slope of 10,000,000 USDC per day._
- _**Remove The Planning And Review Documents From The Distribution Reward And Integration Boost Invocation Protocols** — Has the Prime Agent submit its request directly to Operational GovOps for a feasibility review, instead of through Initial Planning and Operational GovOps Review documents._
- _**Record The September 24, 2026 Grant Transfers For Spark And Grove** — Records the Spark and Grove grant transfers executed through the September 24, 2026 Executive Vote._
- _**Record The Osero Gauntlet Vault Timelocks And Force-Deallocate Penalty** — Records the timelock delays, abdicated functions and 0.01% force-deallocate penalty of Osero's Gauntlet USDC Prime Morpho Vault V2._
- _**Housekeeping Updates** — Removes empty documents from Prime Agent Artifact Data Repositories, links grant transfer records to their authorizations, renames single rate limit documents to the singular, and moves Osero's SparkLend USDS Instance, which no longer holds exposure, to Completed Instances._

## Outcomes

This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation for Atlas Edit Weekly Cycle Proposals is currently set to **480,000,000 SKY**.

**If the votes for the 'Yes' option exceed the votes for the 'No' option AND the votes for the 'Yes' option equal or exceed 480,000,000 SKY, then the following actions will be taken:**

- The associated Pull Request will be merged into The Atlas.

---

## Resources

If you are new to voting in the Sky Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [Sky Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).
