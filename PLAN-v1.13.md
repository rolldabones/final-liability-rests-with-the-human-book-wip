# Plan for v1.13: the deferred scope additions  [↻ draft]

[Purpose] Records the reader-panel scope additions of the 10 November 2026 review (decision D7) that v1.12.0 did not take, so that v1.13 starts from a list rather than a memory.
[Decisions Made] D7 accepted 10 November 2026: the Punchlist stop test (Chapter 22, Question 51) and the Appendix E enforcement-point field (E17) shipped in v1.12.0; everything below is deferred to v1.13; the board edition is decided separately.
[Outstanding Items] Items 12 to 14 (below) are approved for the weekly sweeps. For items 1 to 11: the primary sources to read first and the estimated size (Session 4 of the review plan). Research is done when drafting, not here.

None of these is a defect in v1.12.0. Each widens what the book covers, so each needs Michael Paik's go before drafting.

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
| 9 | A board edition | Board chair | A shorter text for a whole board; a separate decision, not a v1.13 item by default | Separate repository or a reading guide |
| 10 | Appendices I, J and M shipped with the book, or the references removed | Board chair | They are cited throughout but are separate documents | README and Chapter 1 note |
| 11 | The value case | Board chair | What the governance costs and returns | Chapter 19 or Conclusion |

## Carried from the v1.12.0 full read

Approved by Michael Paik on 10 November 2026 to be picked up in the weekly sweeps. These are the three gaps that kept v1.12.0 at A rather than A+. They are quality gaps, not scope additions, so they need no further go before the work starts; each lands as its own patch release.

| # | Gap | What closes it | Where in the book | Estimated size |
|---|---|---|---|---|
| 12 | US federal, Texas and New York City status carried from Appendix J, not re-verified against primary sources | Read the Executive Order of 11 December 2025 and any later federal action, Texas HB 149 as in force and NYC Local Law 144 with the State Comptroller's audit of 2 December 2025; re-date the Chapter 3 United States box and Appendix J item by item | Chapter 3 (United States box), Chapter 22 fairness note, Appendix J | One session |
| 13 | Length: 836,197 bytes, 1.7% longer than v1.11.3; the reviewers' one-fifth cut was not a ruling and was not done | Michael Paik to decide whether a cut is wanted and at what target; if so, propose cuts chapter by chapter, longest first (Chapter 21 is 70 KB), each for approval before it is made | Whole book | Decision first; then two to three sessions |
| 14 | Chapters 7 and 16, rewritten in v1.12.0, not re-read in the full pass | A line-by-line read of both against the Chapter 7 allocation and the DOCTRINE.md section 8 short forms, with the same scripted checks | Chapters 7 and 16 | Under one session |

Final Liability rests with the Human.
