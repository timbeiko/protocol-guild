# 6. Guidelines for Regular Operation

What follows is an outline for how we plan to start, recommendations, and guidelines for regular operation scenarios.

The Guild should transition to Regular Operation before the end of the Initial Pilot but only after the summary report has made meaningful progress in assessing the Guild's evolving characteristics. Activities during Regular Operation should map directly to the obligations described in **3. Roles & Expectations**. Some things will change regularly, like the current set of sponsors at a specific time, or the membership over time.

## 6.1 Comms
- broadcasting to the community and prospective sponsors when vests are set to start and end

## 6.2 Parameter Setting

  - length of each new vesting period
  - how much of a raise to target for each vesting pool
  - number of months contributing needed ahead of inclusion
  - number of multisig signers, whether it should be proportional to number of members
  - how often signers should be required to prove address control
  - how frequently membership will be updated

## 6.3 Weighting

Antifragility and non-gameability emerge from simple frameworks. This limits the time spent deciding appropriate categories, the methods for collecting and verifying  as well as the time spent weighting contributors. Additionally, this should limit cases of ambiguity gaming that might come up in complicated weighting schemes. Based on member feedback, we've settled on these guidelines: SQRT((`eligibleMonths` - `monthsOnBreak`) * `timeWeighting`)

  - historic contributions are considered in weightings
  - `timeWeighting` can be either 1.0 for full-time or .5 for part-time contributors
  - existing contributors get "diluted" as newcomers come in
  - continuing contributors get additional weight per month they are active. This means historic contributors don't maintain their split weighting if they leave protocol development
  - anyone who stops contributing is removed from the split via periodic Curation Reviews

## 6.4 Discussing new members

If current members believe that the set should be expanded to include another contributor, they should propose them well enough in advance of a Membership Update. This would mean at least a week. The process would look something like this:

1. an existing member (akin to an EIP champion) should send this info in the `proposed-members` channel.

- Name / Identifier
- Team / Project
- Discord handle
- Link to relevant work, eg. github, research
- Summary of their work and eligibility

2. Discussion should be open for at least a few days to give members time to review and contribute to the discussion. This can be either with reacts on the proposal 👍 / 👎, ideally along with some written thoughts on why you think the proposed member fits the eligibility or not. Deliberations should strive to end in rough consensus, resorting to formal voting procedures only in rare extreme situations.

3. Once a positive consensus has been reached, the person can be contacted with the typical onboarding flow. 

If you are an existing core contributor that is not included, please contact an existing member to have them propose your work for consideration.

## 6.5 Onboarding new members

Eligible and confirmed members should be given an onboarding form link to be added to the split contract at the next quarterly update. They should also be added to the Stateful Works discord and given the proper `Guild Member` / Team roles.

When introducing the concept to potential members or onboarding accepted ones, it should be noted that the submitted address should refer to an individual's personal wallet and *not* their employer's. If teams were the atomic unit, all team members would have to agree on whether to accept or decline membership, likely decreasing the number of participants.

## 6.6 Guild Contact

It may be the case that there should be a Guild Contact for each team. The backstop is each team/project, who only need to confirm when a contributor has been added or removed. One member of each team/project (eg. Lighthouse) should agree to be the point of contact responsible for ensuring other members are aware of any significant developments like:

- explaining membership obligations to new team members
- collecting addresses and signatures for inclusion in the eligible set
- migration to a new smart contract
- a change to the weighting scheme
