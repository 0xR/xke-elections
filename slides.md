---
theme: ./slidev-theme-xebia
title: How To Make (workers council) Elections Better
---

# How To Make (Workers Council) Elections Better

Ruben Oostinga  
2024-09-17

---

# Contents
- Election Theory
- Election Software
- Work council election options

# TODO: add work council law
    Election systems around the world
    Tactical voting
    Electing small parties
    First-past-the-post voting
    Contingent vote
    Two-round system
    Ranked choice voting
    Single Non-transferable Vote (SNTV)
    Single Transferable Vote (STV)
    Meek STV
    Instant-runoff voting
    Party-list proportional representation
    Paid and open-source election software


---

# Election categories

- Single-winner elections
  - Presidents
  - Mayors
- Multi-winner elections
  - Lower house
  - Workers' councils


---

# Tweede kamer elections in Netherlands
- Proportional representation: A party gets same percentage of seats as the percentage of votes
- Seat distribution using the D'Hondt method
- Single district / District at large
- Party lists


---

# US Congressional Elections:

## House of Representatives
- Single-member districts
- Plurality voting (First-Past-The-Post)

## Senate:
-   Two senators per state
-   Direct elections since 1913 (17th Amendment)
-   Plurality voting (First-Past-The-Post)

---

# French Presidential and Legislative Elections

## Presidential Elections:
- Direct election by popular vote
- Two-round system: If no candidate wins a majority in the first round, the top two candidates face off in a second round
## Legislative Elections (National Assembly):
- Single-member districts
- Two-round system: If no candidate wins an absolute majority in the first round, a second round is held
- Candidates in second round: All candidates who received at least 12.5% of the vote in the first round

---
layout: two-cols-header
---

# Plurality Voting vs Proportional Representation

::left::

## Plurality Voting
- **Key Features:**
  - Single-member districts; candidate with most votes wins
  - Simple and clear winner, potentially stable governments
  - Often leads to two-party dominance
- **Drawbacks:**
  - 'Wasted' votes and disproportionate representation

::right::

## Proportional Representation
- **Key Features:**
  - Multi-member districts; seats distributed by vote percentage
  - Accurate representation of electorate's preferences
  - Encourages multi-party systems and diverse viewpoints
- **Drawbacks:**
  - Complex processes and potential for coalition governments

---
layout: image
image: /party-by-municipality-people.png
---

<!--
Missing parties
- D66
- BBB
- CDA
- SP
- FVD
- PVDD
- DENK, CU, SGP, VOLT

depending on district boundaries
SGP -> PVV
VVD -> GL-PVDA
-->

---

# Dáil Éireann Elections in Ireland
- Single Transferable Vote (STV) system
  - Voters rank candidates in order of preference
- Multiple District (Unlike single district in NL)
- Competition between candidates of the same party and district
- Quota system
  - Candidates need to reach a certain quota of votes to be elected
- Surplus and transfer
  - Excess votes for elected candidates are transferred to next preferences
  - Eliminated candidates' votes are also transferred to next preferences

<!--

Lower house, tweede kamer

-->

---
layout: center
---

<!-- ranked choice voting us -->
<Youtube id="gq7N2hmX9FI"  :width="1000" :height="560" />

---
layout: center
---
<!-- scotland -->
<Youtube id="P38Y4VG1Ibo"  :width="1000" :height="560" />

---

## Restrictions on Works Council Elections (Wet op de ondernemingsraden)

- Elections must be secret and in writing (Article 9(1)).
- Candiates can be submitted by (Article 9(2)):
  - Employee associations meeting specific criteria.
  - Individual eligible employees or groups.

- **Reserving Seats for Specific Departments (Article 9(3) and (4)):**
  - Works council can reserve seats for specific groups.
  - Ensures diverse representation within the council.

- **Election Procedures (Articles 10 and 11):**
  - Works council sets additional rules for:
    - Candidate nomination.
    - Election setup.
    - Result announcement.

## Objective
- Ensure fair and representative elections.
- Reflect interests of various groups within the organization.

<!--
- STV not mentioned

-->

---

# Xebia Workers Council Elections

## What

- Electing a workers council.
- Many ways to organize.
- Goals:
    - Ensure representation for all.
    - Ensure smaller departments represented.
- 11 council seats.
- ~500 voters.
- Unknown turnout.
- Different departments may have different turnouts.

---
layout: two-cols-header
---
# Solution 1

## Single Non-Transferable Vote

::left::

## Pro

- Voting is easy.
- Counting votes is easy.

::right::

## Con

- Popular vote dilutes impact.
- Unpopular candidates unrepresented.
- Departments spoil votes for each other.
- Tactical voting needed.

---
layout: two-cols-header
---
# Solution 2

## Open List Party-List Proportional Representation

::left::

## Pro

- Every department represented.
- Weight determined by voters.
- Familiar approach.

::right::

## Con

- Downsides of Solution 1 within departments.
- Candidates must represent a department.
- Voters can't vote outside their department.
- Multiple elections needed.

---
layout: two-cols-header
---
# Solution 3

## Pre-assigned Seats to Departments

::left::

## Pro

- Every department represented.
- Weight predetermined by management.

::right::

## Con

- Weight not voter-represented.
- Candidates must pick a department.
- Voters can't vote outside their department.
- Multiple elections needed.

---
layout: two-cols-header
---
# Solution 4

## Single Transferable Vote

::left::

## Pro

- Small departments can get representation.
- Voters can express varied preferences.
- Multiple candidates can be ranked equally.
- No tactical voting needed.
- Votes always count for a winner.

::right::

## Con

- Complex vote counting; needs specialized software.
- Unfamiliar system.
- Small departments might still lack representation.

---

# Open Questions

- Actual election method: online or physical?
- Count votes ourselves or use a service?
- Online tool requirements: single vote enforcement.
- Options: Microsoft Forms, Election SaaS.
- Anonymous voting?
- Support for recounts?
