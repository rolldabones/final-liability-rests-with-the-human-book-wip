# Plan for v1.13: the deferred scope additions  [↻ draft]

[Purpose] Records the reader-panel scope additions of the 10 November 2026 review (decision D7) that v1.12.0 did not take, so that v1.13 starts from a list rather than a memory: for each, why, where in the book, the primary sources to read first and the estimated size.
[Decisions Made] D7 accepted 10 November 2026: the Punchlist stop test (Chapter 22, Question 51) and the Appendix E enforcement-point field (E17) shipped in v1.12.0; everything below is deferred to v1.13. Item 9 ruled 10 November 2026: the board reading guide in AI-Governance-Academy is the board edition for now; revisited after v1.13 ships and the guide has been used in a board session. Items 12 to 14 are approved for the weekly sweeps.
[Outstanding Items] Michael Paik's go, item by item, for items 1 to 8, 10 and 11; the length decision of item 13 first, because the additions below add about 9,900 to 15,700 words. Items 15 to 17, found by the glossary rebuild of 10 November 2026, for his ruling.

None of these is a defect in v1.12.0. Each widens what the book covers, so each needs Michael Paik's go before drafting. The sources named are the ones to read first; nothing below has been read for this plan, and no claim in the book changes on the strength of this list. Research is done when drafting. Sizes are in words of new or rewritten prose; the book is 118,496 words (836,197 bytes, v1.12.1).

| # | Addition | Raised by | Why | Where in the book |
|---|---|---|---|---|
| 1 | An EU section in Chapter 3 | Regulator | Chapter 3 says "Almost none of them specify the keeping"; the EU AI Act's Articles 9 to 17 do specify much of it for high-risk systems, so the claim needs narrowing or support | Chapter 3, after "What Filing Is Not"; the EU status box |
| 2 | DORA Articles 5 and 28 to 30 | Regulator | Financial-entity readers meet AI governance through ICT risk and third-party contracts first | Chapter 17 or 19; Appendix J Part 10 |
| 3 | The revised Product Liability Directive (Directive (EU) 2024/2853) | Regulator | Applies to products placed on the market after 9 December 2026; the disclosure and presumption rules (Articles 9 and 10) bear on the evidence argument | Chapters 19 and 20 |
| 4 | GDPR Article 22 case law | Regulator | Automated decision-making with significant effects; the case law is to be verified before any claim is made | Chapter 12 or 20 |
| 5 | Legal privilege of in-house sign-off records in EU competition proceedings (*Akzo Nobel*, C-550/07 P) | Regulator | The General Counsel's design records may not be privileged; to be verified | Chapters 7 and 16 |
| 6 | A trust-boundary enforcement section | Engineer | Extends Appendix E field E17 into prose: where each prohibited condition is enforced (outside the model, by credential scope, at a human gate or by instruction only) | Chapter 14 |
| 7 | A tiered change taxonomy | Engineer | Which changes need re-authorization, re-validation or only a log entry | Chapter 14 or Appendix E |
| 8 | Chapter 11's benchmark argument reconciled with Chapter 21 | Engineer | Chapter 11 leans on benchmark progress; Chapter 21 shows test-aware models weaken benchmark evidence | Chapters 11 and 21 |
| 9 | A board edition | Board chair | A shorter text for a whole board. **Ruled 10 November 2026:** the board reading guide in AI-Governance-Academy serves as the board edition; no separate text in v1.13 | None in v1.13 |
| 10 | Appendix M shipped with the book, or the references removed | Board chair | Raised for Appendices I, J and M. Since v1.12.0, Appendices I and J ship in this repository as files of record (README, "Files in this repository"), so only Appendix M, maintained as the standalone grc-workbook repository, is still cited and not shipped | README and the Chapter 1 appendix note |
| 11 | The value case | Board chair | What the governance costs and returns | Chapter 19 or Conclusion |

### Primary sources to read first, and size

| # | Primary sources to read first | Estimated size |
|---|---|---|
| 1 | Regulation (EU) 2024/1689 as amended by Regulation (EU) 2026/1744, consolidated text on EUR-Lex: Articles 9 to 17 (with Annex IV for Article 11), 18, 19, 26(6) and 72; the Commission AI Act Service Desk article pages, checked against the consolidated text because the register found Service Desk pages not yet showing the Omnibus amendments. The result is a narrowed sentence and a section on what the Act specifies about keeping and what it leaves to the provider | 1,500 to 2,500 words; one session |
| 2 | Regulation (EU) 2022/2554 (DORA) on EUR-Lex: Article 5 (governance), Articles 28 to 30 (ICT third-party risk, concentration risk, key contractual provisions); the regulatory technical standards made under Articles 28(10) and 30(5), identified on EUR-Lex when drafting | 1,200 to 2,000 words, plus Appendix J Part 10 rows; one session |
| 3 | Directive (EU) 2024/2853 on EUR-Lex: Article 4 (definitions, software as a product), Articles 9 and 10, and the application and transitional articles; the national transposing measures listed on EUR-Lex for the jurisdictions the book's readers face, read as they are published | 1,000 to 1,500 words across Chapters 19 and 20; one session |
| 4 | Regulation (EU) 2016/679, Articles 15(1)(h) and 22, on EUR-Lex; on CURIA, *SCHUFA Holding (Scoring)*, C-634/21 (7 December 2023) and *Dun & Bradstreet Austria*, C-203/22 (27 February 2025), each read in full before any holding is stated; the EDPB-endorsed guidelines on automated decision-making (WP251 rev.01) | 800 to 1,200 words; one session, most of it reading |
| 5 | *Akzo Nobel Chemicals and Akcros v Commission*, C-550/07 P (14 September 2010), judgment on CURIA; for each other jurisdiction the book addresses, privilege for in-house counsel stated only from that jurisdiction's primary text, or recorded as Unknown | 500 to 800 words; under one session. ⚠ External counsel per jurisdiction before the book advises on privilege |
| 6 | The book's own Appendix E field E17 and Chapter 14; OWASP Top 10 for Agentic Applications for 2026 and MITRE ATLAS, as already cited in Chapter 21; NIST AI 800-4, as already cited in Chapter 22. No new external authority is needed for the argument; any vendor control named is read on the vendor's own documentation | 2,000 to 3,000 words; one session |
| 7 | Regulation (EU) 2024/1689: Article 3(23) (substantial modification), Article 25(1)(b) and (c) and Article 43(4); ISO/IEC 42001:2023, the clause on planning of changes; the FDA's final guidance on predetermined change control plans for AI-enabled device software functions, read on fda.gov as the one worked regulatory model of pre-authorized change. Output: a three-tier table (re-authorize, re-validate, log) keyed to Appendix E fields | 1,000 to 1,500 words and one table; one session |
| 8 | Internal: the Chapter 11 benchmark passages and the Chapter 21 test-awareness section, with the studies Chapter 21 already cites re-read at their pinpoints | 300 to 600 words net, mostly rewriting Chapter 11; under one session |
| 9 | None (ruled) | None |
| 10 | The grc-workbook README and the Chapter 1 appendix note; the decision is whether the book points to Appendix M in its standalone form (the current practice) or stops calling it an appendix | About 100 words; within another item's session |
| 11 | Only figures with a primary source: Article 99 of Regulation (EU) 2024/1689 for penalty ceilings; the insurer endorsements Chapter 19 already cites (CG 40 47, CG 40 48, CG 35 08); any cost or return figure from a filing, a regulator's published data or a peer-reviewed study, read in full. Where no such figure exists, the value case is argued from mechanism and the figure is recorded as Unknown | 1,500 to 2,500 words; one to two sessions |

**Total.** About 9,900 to 15,700 words of new prose for items 1 to 8, 10 and 11, or 8 to 13 percent of the book, before any cut under item 13; the tables and Appendix J rows come on top.

⧉ **The single biggest risk.** Items 1 to 8 and 11 lengthen a book the reader panel already found long (item 13). Taking them before the length decision makes the cut larger later. Recommendation: rule on item 13 first; then take items 1, 3 and 6, which carry the book's central evidence argument, and hold 2, 4, 5 and 7 for a sectoral or EU companion if the cut target is tight.

## Carried from the v1.12.0 full read

Approved by Michael Paik on 10 November 2026 to be picked up in the weekly sweeps. These are the three gaps that kept v1.12.0 at A rather than A+. They are quality gaps, not scope additions, so they need no further go before the work starts; each lands as its own patch release.

| # | Gap | What closes it | Where in the book | Estimated size |
|---|---|---|---|---|
| 12 | US federal, Texas and New York City status carried from Appendix J, not re-verified against primary sources | Read the Executive Order of 11 December 2025 and any later federal action, Texas HB 149 as in force and NYC Local Law 144 with the State Comptroller's audit of 2 December 2025; re-date the Chapter 3 United States box and Appendix J item by item | Chapter 3 (United States box), Chapter 22 fairness note, Appendix J | One session |
| 13 | Length: 836,197 bytes, 1.7% longer than v1.11.3; the reviewers' one-fifth cut was not a ruling and was not done | Michael Paik to decide whether a cut is wanted and at what target; if so, propose cuts chapter by chapter, longest first (Chapter 21 is 70 KB), each for approval before it is made | Whole book | Decision first; then two to three sessions |
| 14 | Chapters 7 and 16, rewritten in v1.12.0, not re-read in the full pass | A line-by-line read of both against the Chapter 7 allocation and the DOCTRINE.md section 8 short forms, with the same scripted checks | Chapters 7 and 16 | Under one session |


## Found by the glossary rebuild, 10 November 2026

The glossary for v1.12.2 was built from the whole text, with every place a term is used in a different wording. Of the 26 terms v0.1 of the glossary flagged as inconsistent (built from v1.11.3), the rulings of v1.12.0 settled most; four that remained were corrected in v1.12.2 as rule or term variations (Chapter 4's definition of Services against Appendix L; "named owner" for "named human owner" in Chapter 17; "sign-for test" for the name-the-human test in Chapter 7; Appendix F's HOTL without "override"). The three below are not a wording slip and need a ruling.

| # | Gap | Where in the book | Recommendation | Estimated size |
|---|---|---|---|---|
| 15 | The pre-deployment specification is listed four ways: Chapter 5 (what, on what data, for what users, thresholds, response criteria), Chapter 9 (action scope, data access boundaries, escalation conditions, oversight mode, exit), Chapter 11 (purpose, thresholds, action scope, escalation conditions, exit) and Chapter 21 (performance requirements, thresholds, action scope, data access boundaries, escalation conditions, oversight mode; no exit) | Chapters 5, 9, 11 and 21; Appendix E | One canonical field list, stated in Chapter 9 against the four elements of Informed Intent, with the other chapters pointing to it | Under one session |
| 16 | The Chapter 22 Punchlist pairs "Accountable executive for the deployment" with the Chief Technology Officer as owner, where Chapter 7 names one accountable executive per deployment | Chapter 22 | State the pairing as owner and accountable executive, the executive alone signing for the deployment, as in Chapter 7 | A few lines |
| 17 | Chapter 22 asks whether the board has approved the AI risk appetite; Chapter 7 says the management body owns it. Consistent where the management body is the board, as in EU usage; unclear for a two-tier board | Chapters 7 and 22 | One sentence in Chapter 7 saying which body approves and which owns | A few lines |

Final Liability rests with the Human.
