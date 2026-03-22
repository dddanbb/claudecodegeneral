# Australian Bank Cheque Phase-Out: Comprehensive Research Report

**Date:** 22 March 2026
**Research methodology:** Multi-agent web research targeting authoritative bank and government sources
**Red Hat review:** Independently acid-tested (see red-hat-analysis.md) -- overall rating 6/10; headline regulatory dates confirmed accurate; corrections applied below

---

## Executive Summary

The Australian cheque system is being formally wound down under a government-mandated plan. **All cheque issuance ceases 30 June 2028; all cheque acceptance ceases 30 September 2029.** Many banks — particularly smaller institutions — have already exited the system years ahead of schedule.

Cheque usage has declined **almost 90% over the last decade** (~86.5% measured) and now represents **less than 0.1% of all retail payments**. In the RBA's 2022 Consumer Payments Survey (999 participants, ~11,000 payments), only **7 personal cheque payments** were recorded in the entire survey week.

---

## Regulatory Framework

| Milestone | Date | Authority |
|---|---|---|
| Strategic Plan for Australia's Payments System released | 7 June 2023 | Treasury |
| Consultation paper on winding down cheques | December 2023 | Treasury |
| **Cheques Transition Plan published** | **18 November 2024** | **Treasury** |
| ACCC interim authorisation for AusPayNet wind-down | 18 December 2024 | ACCC |
| ACCC final authorisation granted (AA1000689) | 2 July 2025 | ACCC |
| Government ceases cheque use | End of 2028 | Treasury |
| **All issuance ceases** | **30 June 2028** | **Treasury** |
| **All acceptance ceases** | **30 September 2029** | **Treasury** |
| ACCC authorisation expires | 31 December 2030 | ACCC |

The 15-month gap between issuance and acceptance cessation is deliberate — cheques become legally "stale" 15 months after being drawn.

**Key regulatory sources:**
- [Cheques Transition Plan (Treasury)](https://treasury.gov.au/publication/p2024-555854)
- [Cheques Transition Plan PDF](https://treasury.gov.au/sites/default/files/2024-11/p2024-555854.pdf)
- [Treasurer media release — Phasing out cheques](https://ministers.treasury.gov.au/ministers/jim-chalmers-2022/media-releases/modernising-payments-infrastructure-phasing-out-cheques)
- [Treasurer media release — Future of cash & cheques](https://ministers.treasury.gov.au/ministers/jim-chalmers-2022/media-releases/ensuring-future-cash-and-next-steps-phasing-out-cheques)
- [ACCC Final Determination PDF](https://www.accc.gov.au/system/files/public-registers/documents/Final%20Determination%20-%2002.07.25%20-%20PR%20-%20AA1000689%20AusPayNet.pdf)
- [AusPayNet Cheques Transition](https://auspaynet.com.au/insights/Cheques_Transition)
- [RBA Payments Statistics (C5/C5.1)](https://www.rba.gov.au/payments-and-infrastructure/resources/payments-data.html)

---

## Volume Statistics: The Decline of Cheques

| Period | Metric | Source |
|---|---|---|
| 1980s peak | ~85% of all non-cash payments | RBA |
| Mid-1990s | ~50 cheques per capita per year; ~3M cheques/day worth >$17B | RBA |
| 2007 | 1.2% of consumer payments | RBA CPS |
| 2013 | 0.4% of consumer payments | RBA CPS |
| 2016 | 0.2% of consumer payments; 20% annual decline | RBA CPS / Bulletin |
| 2019 | 0.2%; all cheque users over 50; 80% over 65 | RBA CPS |
| 2020 | ~27% annual decline | AusPayNet |
| 2022 | 0.1% share; only 7 personal cheques in entire survey week | RBA CPS 2022 |
| May 2024 | ~1.3M cheques in prior 12 months; value $17.9B (down 17%) | RBA |
| FY2025 | Value down 20.6% year-on-year | AusPayNet |
| Sept 2025 | 3.5M bank cheques worth $820M uncashed (80% over 3 years old) | AusPayNet |

**Key data sources:**
- [RBA 2022 Consumer Payments Survey — Cheques](https://www.rba.gov.au/publications/rdp/2023/2023-08/cheques.html)
- [RBA Bulletin: The Ongoing Decline of the Cheque System (2017)](https://www.rba.gov.au/publications/bulletin/2017/jun/7.html)
- [RBA Consumer Payments Explorer](https://www.rba.gov.au/payments-and-infrastructure/consumer-payments-explorer/)
- [AusPayNet Payments Monitor](https://auspaynet.com.au/insights/Payments-Monitor/November-2025)

---

## Top 20 Australian Banks: Cheque Phase-Out Status

### Master Table

| # | Bank | Tier | Est. Assets (AUD) | Est. Market Share (Cheque Volume) | Stop Issuing Date | Stop Accepting Date | Status | Official Source |
|---|---|---|---|---|---|---|---|---|
| 1 | **Commonwealth Bank (CBA)** | Big 4 | ~$1,254B | ~25% | Jun 2023 (new accounts) | 30 Sep 2029 (national) | Winding down | [commbank.com.au/business/latest/changes-to-cheques.html](https://www.commbank.com.au/business/latest/changes-to-cheques.html) |
| 2 | **Westpac** | Big 4 | ~$1,004B | ~20% | May 2025 (corp new accts); Aug 2026 (PPS bank cheques) | 30 Sep 2029 (national) | Winding down | [westpac.com.au/corporate-banking/transactional-banking/cheque-updates/](https://www.westpac.com.au/corporate-banking/transactional-banking/cheque-updates/) |
| 3 | **NAB** | Big 4 | ~$952B | ~18% | Mar 2023 (new accounts) | 30 Sep 2029 (national) | Winding down | [nab.com.au/customer-notices/cheque-changes](https://www.nab.com.au/customer-notices/cheque-changes) |
| 4 | **ANZ** | Big 4 | ~$895B | ~17% | Jun 2024 (new); Nov 2024 (counter cheques) | 30 Sep 2029 (national) | Winding down | [anz.com.au/learn/cheque-changes/](https://www.anz.com.au/learn/cheque-changes/) |
| 5 | **Macquarie Bank** | Medium | ~$331B | ~3% | Jan 2024 (new books); May 2024 (over-counter) | 1 Nov 2024 | **FULLY CEASED** | [macquarie.com.au/help/general/cheque-and-cash-changes.html](https://www.macquarie.com.au/help/general/cheque-and-cash-changes.html) |
| 6 | **Bendigo & Adelaide Bank** | Medium | ~$100B | ~2% | Nov 2023 (no new books) | TBD (by Sep 2029) | Issuance ceased | [bendigobank.com.au/ways-to-bank/cheques/](https://www.bendigobank.com.au/ways-to-bank/cheques/) |
| 7 | **Bank of Queensland (BOQ)** | Medium | ~$100B | ~2% | Dec 2025 (no new books) | TBD (by Sep 2029) | Issuance ceased | [boq.com.au/help-and-support/cheque-changes](https://www.boq.com.au/help-and-support/cheque-changes) |
| 8 | **Suncorp Bank** (now ANZ) | Medium | ~$80B | ~1.5% | 1 Mar 2024 | 14 Feb 2025 | **FULLY CEASED** | [suncorpbank.com.au/help-support/cheques-payments-options.html](https://www.suncorpbank.com.au/help-support/cheques-payments-options.html) |
| 9 | **ING Australia** | Medium | ~$65B | ~1.5% | Mar 2026 (bank cheques) | Still accepting (via Bank@Post) | Winding down | [ing.com.au/faq-result.html?faqid=7340](https://www.ing.com.au/faq-result.html?faqid=7340) |
| 10 | **HSBC Australia** | Medium | ~$50B (est.) | ~1% | Ongoing (no new books) | TBD (by Sep 2029) | Issuance ceased | [hsbc.com.au/help/important-notices/](https://www.hsbc.com.au/help/important-notices/) |
| 11 | **AMP Bank** | Small | ~$28B | ~0.5% | May 2024 | 24 Nov 2024 | **FULLY CEASED** | [amp.com.au/personal-banking/ways-to-bank](https://www.amp.com.au/personal-banking/ways-to-bank) |
| 12 | **People First Bank** (Heritage + People's Choice) | Mutual | ~$24.5B | ~0.4% | Mar 2024 (PC); 2024 (Heritage) | May 2024 (PC); 2024 (Heritage) | **FULLY CEASED** | [peopleschoice.com.au/managing-my-money/cheques](https://www.peopleschoice.com.au/managing-my-money/cheques) |
| 13 | **Newcastle Permanent** (NGM Group) | Mutual | ~$23B | ~0.4% | Not confirmed | Not confirmed | Possibly still active | [newcastlepermanent.com.au/tools-and-services/accessing-your-money](https://www.newcastlepermanent.com.au/tools-and-services/accessing-your-money) |
| 14 | **Great Southern Bank** (ex-CUA) | Mutual | ~$20B | ~0.3% | Before May 2024 | 24 May 2024 | **FULLY CEASED** | [greatsouthernbank.com.au/help-and-contact/support/cheque](https://www.greatsouthernbank.com.au/help-and-contact/support/cheque) |
| 15 | **Citibank Australia** (acquired by NAB) | Acquired | N/A (now NAB) | ~0.5% | Feb 2024 (migration) | Feb 2024 | **FULLY CEASED** | [nab.com.au/customer-notices/cheque-changes](https://www.nab.com.au/customer-notices/cheque-changes) |
| 16 | **Bank Australia** | Mutual | ~$12B | ~0.2% | 12 Jan 2024 | 28 Mar 2024 | **FULLY CEASED** | [bankaust.com.au/ways-to-bank-without-cheques](https://www.bankaust.com.au/ways-to-bank-without-cheques) |
| 17 | **Teachers Mutual Bank** (TMBL) | Mutual | ~$11B | ~0.2% | 2023 | 2023 | **FULLY CEASED** | [tmbank.com.au/ways-to-bank/cheque-decommission](https://www.tmbank.com.au/ways-to-bank/cheque-decommission) |
| 18 | **Beyond Bank Australia** | Mutual | ~$8.9B | ~0.1% | May 2024 | 17 May 2024 | **FULLY CEASED** | [beyondbank.com.au/help-and-contact/faqs/cheques/](https://www.beyondbank.com.au/help-and-contact/faqs/cheques/) |
| 19 | **ME Bank** (BOQ subsidiary) | Subsidiary | ~$30B (est.) | ~0.5% | 1 May 2025 | 1 May 2025 | **FULLY CEASED** | [mebank.com.au/support/cancelling-a-cheque/](https://www.mebank.com.au/support/cancelling-a-cheque/) |
| 20 | **Bankwest** (CBA subsidiary) | Subsidiary | ~$30B (est.) | ~1% | Mar 2024 (new/replacement books); Nov 2024 (business cheque acct) | Aligned with CBA (Sep 2029) | Issuance ceased | [bankwest.com.au/help/payments/cheque-books](https://www.bankwest.com.au/help/payments/cheque-books) |

---

## Volume Impact Heuristic Methodology

The "Est. Market Share (Cheque Volume)" column estimates each bank's proportional share of remaining cheque volume based on:

1. **Deposit market share** — proxy for payment activity (Big 4 hold ~80% of system deposits)
2. **Customer demographics** — banks with older customer bases (e.g., Big 4, Bendigo) likely have disproportionately higher cheque usage since 80%+ of remaining cheque users are over 65
3. **Business banking concentration** — business cheques are a larger proportion of remaining volume; banks with stronger SME/corporate franchises weighted higher
4. **Known cheque usage data** — ANZ reported only 3.5% of eligible customers had cheque books; Macquarie reported <0.1% affected
5. **Already-exited institutions** have effectively 0% current volume

**Estimated current cheque volume distribution (March 2026):**

| Segment | Est. Share of Remaining Volume | Status |
|---|---|---|
| Big 4 (CBA, Westpac, NAB, ANZ) | ~80% combined | Still operating, winding down |
| Medium banks still operating (Bendigo, BOQ, ING, HSBC) | ~7% combined | Issuance ceased, acceptance winding down |
| Newcastle Permanent / NGM | ~0.4% | Possibly still operating |
| Already fully ceased (Macquarie, Suncorp, AMP, People First, Great Southern, Citi, Bank Australia, Teachers Mutual, Beyond Bank, ME Bank) | ~0% (exited) | **No longer processing cheques** |
| Government & other | ~12.6% | Winding down by end 2028 |

---

## Net Market Impact Analysis

### Banks That Have Fully Exited (as of March 2026)

**11 of the 20 banks have already fully ceased all cheque operations.** These represent approximately 15-20% of the banking system by assets but a smaller proportion of cheque volume (estimated 5-8% of total volume at time of exit) because most had very low cheque usage.

### Remaining Active Participants

The **Big 4** carry the overwhelming majority of remaining cheque volume (~80%) and have committed to operating until the national deadline (30 September 2029). This means the practical market impact of the remaining wind-down is concentrated in the final 3.5 years:

| Phase | Timeline | Impact |
|---|---|---|
| **Already done** (Mar 2026) | Complete | 11/20 banks fully exited; minimal volume impact (~5-8% of cheques) |
| **Current wind-down** (2026-2028) | Now → 30 Jun 2028 | Big 4 + remaining medium banks progressively restricting issuance |
| **Final issuance cutoff** | 30 June 2028 | ALL banks stop issuing cheques; ~1M remaining cheques in circulation |
| **Final acceptance cutoff** | 30 September 2029 | System permanently closes; Cheques Act 1986 to be repealed |

### Sectors Still at Risk

1. **Property conveyancing** — bank cheques were 9% of volume but >50% of value; largely migrating to PEXA
2. **Government payments** — 98% of Commonwealth cheques from Health, Services Australia, and ATO
3. **Gaming/gambling** — some state legislation mandates cheque payment for winnings
4. **Older Australians** — 14% of 65+ made a cheque payment in prior year (2022 CPS)
5. **Charities and regional small businesses** — higher-than-average reliance

---

## Key Findings

1. **The Australian cheque system is in terminal decline but not yet dead.** At <0.1% of retail payments and declining 20%+ annually, cheques are functionally irrelevant to the payment system. The remaining volume is heavily concentrated in the Big 4 banks.

2. **Smaller banks exited first** — driven by third-party cheque processing agreements expiring, not customer demand. Most relied on larger banks for cheque clearing access.

3. **The Big 4 are the system's life support.** CBA, Westpac, NAB, and ANZ collectively process ~80% of remaining cheques and have guaranteed participation until September 2029.

4. **CBA and NAB moved earliest** among the Big 4 (March-June 2023). **Westpac is the laggard** — still issuing personal cheque books without restriction as of 2024, only restricting corporate from May 2025.

5. **The "stale cheque" mechanism** is elegant: by ceasing issuance 15 months before ceasing acceptance, all legally valid cheques expire naturally.

6. **Legislative reform is required** — 4 Commonwealth Acts mandate cheque payment; state gambling legislation must be amended; the Cheques Act 1986 itself must be repealed.

---

## Appendix: All Authoritative Source URLs

### Government & Regulatory
| Source | URL |
|---|---|
| Treasury Cheques Transition Plan | https://treasury.gov.au/publication/p2024-555854 |
| Treasury Transition Plan PDF | https://treasury.gov.au/sites/default/files/2024-11/p2024-555854.pdf |
| Treasury Consultation Paper (Dec 2023) | https://treasury.gov.au/sites/default/files/2023-12/c2023-471331-cp.pdf |
| Treasurer media release (phasing out) | https://ministers.treasury.gov.au/ministers/jim-chalmers-2022/media-releases/modernising-payments-infrastructure-phasing-out-cheques |
| Treasurer media release (Nov 2024) | https://ministers.treasury.gov.au/ministers/jim-chalmers-2022/media-releases/ensuring-future-cash-and-next-steps-phasing-out-cheques |
| AusPayNet Cheques page | https://auspaynet.com.au/network/cheques |
| AusPayNet Cheques Transition | https://auspaynet.com.au/insights/Cheques_Transition |
| AusPayNet Nov 2024 media release | https://auspaynet.com.au/insights/Media-Release/ChequesNov24 |
| ACCC Final Determination (AA1000689) | https://www.accc.gov.au/system/files/public-registers/documents/Final%20Determination%20-%2002.07.25%20-%20PR%20-%20AA1000689%20AusPayNet.pdf |
| ACCC Authorisations register | https://www.accc.gov.au/public-registers/authorisations-and-notifications-registers/authorisations-register/australian-payments-network-limited |
| RBA Payments Statistics (C5/C5.1) | https://www.rba.gov.au/payments-and-infrastructure/resources/payments-data.html |
| RBA 2022 CPS — Cheques | https://www.rba.gov.au/publications/rdp/2023/2023-08/cheques.html |
| RBA Bulletin: Decline of Cheque System | https://www.rba.gov.au/publications/bulletin/2017/jun/7.html |
| RBA Consumer Payments Explorer | https://www.rba.gov.au/payments-and-infrastructure/consumer-payments-explorer/ |
| Cheques Act 1986 | https://www.legislation.gov.au/Details/C2007C00573 |

### Big 4 Banks
| Bank | URL |
|---|---|
| CBA — Changes to cheques | https://www.commbank.com.au/business/latest/changes-to-cheques.html |
| CBA — Declining use of cheques | https://www.commbank.com.au/articles/business/foresight/declining-use-of-cheques.html |
| Westpac — Cheque updates (corporate) | https://www.westpac.com.au/corporate-banking/transactional-banking/cheque-updates/ |
| Westpac — Cheques and bank cheques (personal) | https://www.westpac.com.au/personal-banking/services/banking-services/cheques-and-bank-cheques/ |
| Westpac IQ — Moving on from cheques | https://www.westpaciq.com.au/thought-leadership/2025/06/cheat-sheet-how-to-move-on-from-cheques |
| NAB — Cheque changes | https://www.nab.com.au/customer-notices/cheque-changes |
| NAB — Cheque alternatives | https://www.nab.com.au/help-support/better-ways-to-bank/cheque-alternatives |
| NAB — Cheque policy | https://www.nab.com.au/personal/bank-accounts/cheque-payments/cheque-policy |
| ANZ — Cheque changes hub | https://www.anz.com.au/learn/cheque-changes/ |
| ANZ — Personal cheque changes | https://www.anz.com.au/learn/cheque-changes/personal/ |
| ANZ — Business cheque changes | https://www.anz.com.au/learn/cheque-changes/business/ |

### Mid-Tier Banks
| Bank | URL |
|---|---|
| Macquarie — Cheque and cash changes | https://www.macquarie.com.au/help/general/cheque-and-cash-changes.html |
| Bendigo — Cheques | https://www.bendigobank.com.au/ways-to-bank/cheques/ |
| BOQ — Cheque changes | https://www.boq.com.au/help-and-support/cheque-changes |
| Suncorp — Cheques & payment options | https://www.suncorpbank.com.au/help-support/cheques-payments-options.html |
| ING — Cheque deposit FAQ | https://www.ing.com.au/faq-result.html?faqid=7340 |
| HSBC — Important notices | https://www.hsbc.com.au/help/important-notices/ |
| AMP — Ways to bank | https://www.amp.com.au/personal-banking/ways-to-bank |

### Smaller Banks & Mutuals
| Bank | URL |
|---|---|
| People's Choice — Cheques | https://www.peopleschoice.com.au/managing-my-money/cheques |
| Newcastle Permanent — Accessing money | https://www.newcastlepermanent.com.au/tools-and-services/accessing-your-money |
| Great Southern Bank — Cheque services | https://www.greatsouthernbank.com.au/help-and-contact/support/cheque |
| Teachers Mutual — Cheque decommission | https://www.tmbank.com.au/ways-to-bank/cheque-decommission |
| Beyond Bank — Stopping cheques | https://www.beyondbank.com.au/help-and-contact/faqs/cheques/ |
| Bank Australia — Banking without cheques | https://www.bankaust.com.au/ways-to-bank-without-cheques |
| ME Bank — Cancelling a cheque | https://www.mebank.com.au/support/cancelling-a-cheque/ |

---

---

## Risk Factors and Caveats (from Red Hat Analysis)

1. **UK precedent risk:** The UK attempted to abolish cheques by 2018 and reversed course due to public opposition from elderly and charity groups. If similar political pressure emerges in Australia, the 2028/2029 timeline could slip.

2. **Digital exclusion:** 66.5% of Australians aged 75+ are digitally excluded; 40.9% of First Nations people; ~1.1 million Australians with disability are "highly digitally excluded" (2025 Australian Digital Inclusion Index).

3. **Legislative barriers:** 4 Commonwealth Acts still mandate payment by cheque; state gambling legislation requires cheque payment for some winnings. Legislative reform is required but timeline not confirmed.

4. **Charity sector impact:** Major charities (Heart Foundation, Greenpeace, Sydney Eye Hospital Foundation) have published explicit guidance on cheque phase-out impact on donations.

5. **Volume still material:** Despite <0.1% of transactions, cheques still cleared ~$12.89 billion monthly (Feb 2025 RBA data). 3.5 million bank cheques worth $820 million remain uncashed (AusPayNet, Sep 2025).

6. **Volume heuristic limitations:** The market share estimates in this report are heuristic-based using deposit share as a proxy. The RBA C5/C5.1 data tables contain primary volume data and should be consulted for any material financial decisions.

7. **URL durability:** Several bank URLs may become stale due to corporate restructuring (Suncorp now ANZ, People's Choice now People First Bank, Citi now NAB). Verify URLs before citing.

---

*Report generated by multi-agent research team, 22 March 2026. All URLs are from authoritative bank, government, or regulatory sources. Volume estimates are heuristic-based and should be validated against RBA C5/C5.1 data tables for precision. Red hat analysis independently verified key claims via 37 web searches -- see red-hat-analysis.md for full critical assessment.*
