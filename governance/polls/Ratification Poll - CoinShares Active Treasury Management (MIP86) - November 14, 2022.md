---
title: Ratification Poll for CoinShares Active Treasury Management (MIP86) - November 14, 2022
summary: Under MIP86, a portion (from 100M to 500M) of the USDC in the PSM will be managed by CoinShares, which will invest the funds in various traditional financial assets according to MIP13c3-SP12.
discussion_link: https://forum.makerdao.com/t/mip86-coinshares-active-treasury-management/17900
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 10000 }
            ]
        }
        - {type : default, value : 2 }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2022-11-14T16:00:00
end_date: 2022-11-28T16:00:00
---
# Ratification Poll for CoinShares Active Treasury Management (MIP86) - November 14, 2022

The Governance Facilitators have placed a ratification poll into the [voting system](https://vote.makerdao.com/polling) as part of the responsibilities defined in [MIP51](https://mips.makerdao.com/mips/details/MIP51). This Governance [Poll](https://community-development.makerdao.com/en/learn/governance/on-chain-gov) will be active for fourteen days beginning on Monday, November 14 at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community may vote in this poll to express support or opposition to MIP86 being accepted and implemented in the Maker Protocol.

A brief summary of this proposal has been provided by the MIP Author and is shown below:

*Under MIP86, a portion (from $100M to $500M) of the PSM’s USDCs will be managed by CoinShares, which will invest on behalf of MakerDAO the funds in various traditional financial assets according to [MIP13c3-SP12](https://mips.makerdao.com/mips/details/MIP13c3SP12). CoinShares aims to provide a variable APY above the SOFR interest rate (3.01% as of October 26, 2022) in the community’s preferred currency (DAI, USDC, USD…) to MakerDAO and that can be withdrawn on-chain. This MIP describes the architecture of the project.*

Please review the links below to inform your position on this proposal before voting.
* [Canonical Proposal Version](https://github.com/makerdao/mips/blob/247f11f556ad5b2be78525c7fa6c9966da76ecec/MIP86/MIP86.md)
* [Latest Proposal Version](https://mips.makerdao.com/mips/details/MIP86)
* [Proposal Discussion Thread](https://forum.makerdao.com/t/mip86-coinshares-active-treasury-management/17900)

## Outcomes

This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation is currently set to **10,000 MKR**.

**If the votes for the 'Yes' option exceed the votes for the 'No' option AND the votes for the 'Yes' option exceed 10,000 MKR, then the following actions will be taken:**
* The MIP Editors will mark the proposal **Accepted** and the Governance Facilitators will confirm its passage on the Governance and Risk call on Thursday, December 1.
* Any further work required to implement the proposal will be tasked to the relevant [Core Units](https://mips.makerdao.com/mips/details/MIP38#mip38c2-core-unit-state).

**Otherwise, this proposal will be marked as rejected per [MIP51](https://mips.makerdao.com/mips/details/MIP51#mip51c2-ratification-poll).**

---

## Resources

[MIP51: Monthly Governance Cycle](https://mips.makerdao.com/mips/details/MIP51) describes this type of poll and its position and significance within the rest of the governance cycle.

If you are new to voting in the Maker Protocol, please see the [voting guide](https://community-development.makerdao.com/en/learn/governance/how-voting-works/) to learn how voting works, and this [wallet setup guide](https://community-development.makerdao.com/en/learn/governance/voting-setup/) to set up your wallet to vote.

Additional information about the Governance process can be found in the [Governance](https://community-development.makerdao.com/en/learn/governance) section of the MakerDAO community portal.

To participate in future Governance calls, please [join us](https://github.com/makerdao/community/tree/master/governance/governance-and-risk-meetings) every Thursday at 17:00 UTC.

To add current and upcoming votes to your calendar, please see the [MakerDAO Public Events Calendar](https://calendar.google.com/calendar/embed?src=makerdao.com_3efhm2ghipksegl009ktniomdk%40group.calendar.google.com&ctz=UTC&mode=week&showCalendars=0&showPrint=0).
