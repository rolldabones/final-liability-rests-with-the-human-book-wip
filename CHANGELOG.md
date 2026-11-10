# Changelog

All notable changes to this repository are documented here. Versioning follows [Semantic Versioning](https://semver.org/). The README and this file version in lockstep; prior versions are superseded, never silently overwritten.

## v1.12.0 (2026-11-10)

Minor release, 10 November 2026 (KST): the book and instruments review of that date. Every change below rests on a ruling in Recommended Rulings v0.2 or on decisions D1 to D7 of Book Findings and Decisions v0.1, all accepted by Michael Paik on 10 November 2026; facts were checked against Verification Register v0.5, with its primary-check rows preferred where they differ from model rows. Prepared with Claude, for Michael Paik's approval.

### Corrections
- **Colorado (first commit).** The *X.AI LLC v. Weiser* minute order (ECF No. 24) bars enforcement for alleged violations of SB24-205 "(or any legislation replacing or amending SB24-205 enacted during this legislative session)"; SB 26-189, enacted in that session to replace it, is therefore within the stay. Chapter 3 and Appendix J (C6, Part 12, 6-1-1707) say so in the order's words; SB 26-189 "repeals and reenacts" SB 24-205; case number with the -DDD-CYC suffix; the 28-day filing trigger added; docket re-read to 9 November 2026. Register V0020 to V0022, B0018, B0178, B0179.
- **Korea.** Presidential Decree No. 36580 of 18 August 2026, in force 20 August 2026, is the current Enforcement Decree throughout; No. 36506 is marked superseded. Act No. 22076 of 20 October 2026, in force 21 April 2027, recorded from law.go.kr with its effect Unknown. Register B0016.
- **Legal and factual corrections, Preface to Chapter 9 (rulings B1 to B21).** NotebookLM rename; "chop" etymology; headcount claim as the author's observation; appendix note with letters and Article 27; NYC Local Law 144 audit content and the Comptroller's findings; IMDA framework version 1.5 and its controls; Korean Act No. 21311 and ISO/IEC 42001:2023; CLTC Profile Version 1.2; Yanagi pinpoint, translator's punctuation kept; CSET five stages and eighteen substages (nineteen counting Manage), 232 action-subject pairs, Approve closing Implementation (Part C check 1; register V0046).
- **Legal and factual corrections, Chapters 10 to 15 (B23 to B58).** Hofstede, GLOBE and Trompenaars restated to their sources, the functional-subculture extension marked as the author's; Berkeley Function Calling Leaderboard; DILEMA quotations; NIST AI RMF Core and GOVERN 3.2; WildChat sample; the 2017 European Parliament resolution; Bryson, Diamantis and Grant quoted; *Moffatt v. Air Canada* paras 27 and 44, CA$812.02 (Part C check 2; register V0103 to V0109); vendor cap in general terms; GDPR Article 82, Directive (EU) 2024/2853 and FTC Act Section 5; Three Lines Model renamed in 2020; Article 25(1) triggers; Glass Lewis figures without the investor-company comparison; Deloitte survey identified (Part C check 3; register V0130); Equilar and Qorvo; *Boeing* facts as pleaded (register V0141); GDPR Article 33 threshold restated.
- **Legal and factual corrections, Chapters 17 to 22 and the Epilogue (B59 to B89).** ISO generative-AI endorsements CG 40 47, CG 40 48 and CG 35 08; Articles 18(1) and 26(6); Article 25(1); GDPR fine record; ForHumanity CORE: sixteen pillars, scheme version 1.5; fruit of the poisonous tree; SWE-bench Verified; NIST MEASURE; ISAE 3000 (Revised) attestation engagement; OWASP Top 10 for LLM Applications 2025 and for Agentic Applications for 2026; MITRE ATLAS; NIST AI 800-4 open questions; ISO/IEC 42001 and the voluntary NIST AI RMF; AI GRC Master List of Minimum Questions; the bliss point without the economics-origin claim; the Scrum Definition of Done.
- **Legal and factual corrections, Appendices D to L (B90 to B132).** Three Lines in D2; Articles 26(5) and 73 in D10; the pilot arithmetic (19 of 1,200; Wilson interval 1.0 to 2.5 percent); AI Act operator roles and Article 25(1) in E4; Article 6 in E5; worked-example dates aligned and the FRIA cited as a dated draft before approval; Article 27(1)(a) to (f), 27(2), 27(3) and 27(5), Article 46(1), Article 3(49), Articles 9(2)(a), 14(4) and 26(2) in Appendix F; Article 26(7) as a duty to inform; instrumental convergence as one hypothesis; EU AI Act, ISO 42001 and NIST GOVERN 1 restated; Appendix K as an independent adopter's guide with the full Profile citation; impact tolerance per FCA SYSC 15A.2.5R and PRA SS1/21.
- Rejected, unchanged: B4, B16, B17, B22 and B60 (register mismatches). Correction B8, omitted from the first pass, applied in the D6 commit.
- **High findings (A1 to A47).** 39 accepted and 7 modified: the section 8 short forms where a passage varied a rule (Chapters 1, 2, 5, 6, 11, 17, 21; Appendices H and K); Chapter 8 points to Chapter 9 for the five conditions; Chapter 12's conditions in canonical order and "a named human, acting for the institution"; cross-references in Chapters 9 and 12 and Appendices D and E; Chapter 13's lifecycle; Chapter 15 "five cases"; Chapter 19's tire valuation; Chapter 14's threshold restated (Final Liability always attaches; past the threshold the allocation is defective); Punchlist committee owners named by chair; Appendix J v7.14 and Checklist v5.3 as their amendment notes record. A29 rejected: the Preface lyric is unchanged.

### Decisions
- **D1, doctrine compressions.** Further rule variations fixed in Chapters 5, 12, 18 and 20; Chapter 12's five components of agency mapped to the five authorizer conditions. The fuller restatements are proposed for DOCTRINE.md "Altitude restatements in force" (v1.2.4) as a separate change in rolldabones/rolldabones, for approval.
- **D2, the named human.** Chapter 7 states one allocation: Final Liability attaches to the accountable executive named per deployment; the General Counsel owns the authority design; engineering owns enforcement and evidence; internal audit assures the join; the management body owns the risk appetite. Chapter 16 is rewritten as that allocation and withdraws the claim that the General Counsel alone connects authority, risk, evidence and consequence. Chapter 14 and Appendix E (E7) aligned.
- **D3, repetition.** The fifteen bold restatement paragraphs after the codas are cut; the codas stay. One home each: the incident architecture in Chapter 20 (Chapter 15 keeps one paragraph); the triad dependency in Chapter 8; the indemnity and Article 85 analysis in Chapter 17 (Chapter 13 keeps one paragraph); the stamp in Chapter 1 and the Conclusion, the Demon Cat in Chapter 1, the tire warehouse in Chapter 2.
- **D4, the Conclusion.** The familiar is argued in the book, each clause of the figure tied to a doctrine and to what agents do (Chapters 12, 14, 21); new sections "How Many Familiars", carrying the Chapter 14 threshold forward, and "What No Risk Appetite Can Justify", which ends the Conclusion on four delegations no appetite can justify. The Epilogue reconciles "good enough" with the Punchlist: satisfice on the standard, binary on the evidence.
- **D5, counts.** Part II subtitle "Three Propositions That Do Not Negotiate"; Chapter 6 reconciled with Chapter 5's five misreadings; Chapter 15 "five cases". New Appendix N, a crosswalk of the eight question sets to the Punchlist and the Checklist IDs.
- **D6, volatile facts.** Chapter 3 ends with one dated box per jurisdiction (European Union, Republic of Korea, United States federal and states, Singapore), each saying what was verified on 10 November 2026; the Colorado docket detail moves from the prose to its box and to Appendix J item C6.
- **D7, scope.** Now: Punchlist Question 51, Stopping (pause and rollback named, tested and the time-to-stop measured), so the Punchlist has fifty-one questions without renumbering 1 to 50; Appendix E field E17, Enforcement Points and Stop Test. Deferred: PLAN-v1.13.md.
- **Spelling out.** "governance, risk management and compliance" in all book prose, Chapter 4's section headings included; the Chapter 4 title is unchanged and glossed once.

### Full read
A line-by-line read of the whole manuscript after the rulings were applied; about 170 edits, none changing a ruling, a doctrine or a count. By class:
- **Doctrine wording.** Informed Intent stated with the five authorizer conditions and Final Liability with its three attributes wherever a chapter paraphrased them (Chapters 1, 9, 12, 13); the Chapter 7 allocation carried into Chapters 4, 8 and 14 (the system owner is the accountable executive; stop authority is pre-delegated); the intent specification mapped to purpose, authority, boundaries and exit (Chapter 9, Appendix H).
- **Law and citations.** *Caremark* 698 A.2d 959, 967; *Marchand* 212 A.3d 805 (Del. 2019); *Boeing* 2021 WL 4059934; *Silverthorne*, *Nardone* and *Wong Sun* with U.S. Reports citations; apparent authority restated to Restatement (Third) of Agency §§ 2.03 and 3.03; the disclosure-gap point attributed to commentary on *Sanford*, not the court (Chapter 20, as Chapter 15 already had it); GDPR access requests run on a one-month deadline, not thirty days (Chapter 18); Presidential Decree No. 36580 cited in full in Chapter 20; the Qorvo paragraph without an unsupported rationale; Chapter 19's demand points named as procurement, insurance and regulation, as the chapter argues them.
- **Cross-references.** Checklist Section 0 cited by its own title (Chapter 14, Appendix E); Appendix E's Checklist pointers re-stated; the appendix note lists N; Chapter 17's closing names the one chapter left in Part IV; Chapter 22's NIST AI 800-4 sentence says several questions, not all, are NIST's open questions; the Master List, the Copilot and the Slow AI Kitchen given their repository links.
- **Style.** Serial commas removed from prose (quotations and titles unchanged); stripped possessives restored in Chapters 17 and 18; dates in day-month-year form throughout, the account's convention; "Client" capitalized throughout; acronyms spelled out at first use (TEVV, HITL, HOTL, HIC, E&O, D&O, ISO as the Insurance Services Office, GDPR, CLTC, SaaS, RTO and RPO); titles italicized; a duplicated coda sentence cut in Chapter 20; the Epilogue's Punchlist reconciliation moved after the passage it interrupted; Chapter 21's definition of audit-grade evidence moved after the paragraph it split; Chapter 13's two paragraphs on public callings put in argument order.
- **Worked examples.** Appendix D's April evaluation is the post-upgrade evaluation of v2.4, consistent with the Production promotion of 1 March 2026 in Appendix E; its Wilson interval re-run (1.0 to 2.5 percent).

### Instruments
- `AI_GRC_Master_Reference_v7_13.md` reissued as `AI_GRC_Master_Reference_v7_14.md`, with a dated amendment note, Version 7.14. `AI_Audit_Due_Diligence_Checklist_v5_2.md` reissued as `AI_Audit_Due_Diligence_Checklist_v5_3.md`, with a dated amendment note, v5.3.0; question count unchanged at 199. Superseded versions removed, per the convention; they remain in the tag chain.

### Lockstep
- `manuscript/` regenerated at the 240,000-byte ceiling (33 parts, Appendix N added; 836,197 bytes) and `master-reference/` at the 60,000-byte ceiling (six parts, the first renamed for Version 7.14; 269,463 bytes), each verified to rebuild its source byte for byte. Confirmed with the account's `split_markdown.py` (--max-bytes 240000 and 60000): regenerating from the branch produced no diff, and --verify passed for both sets. README masthead, appendix paragraph, accuracy table, Status and How to Cite, and `CITATION.cff`, to v1.12.0.

## v1.11.3 (2026-11-09)

Patch release. Train D of the improvement rotation (review of 24 October 2026). Prepared with Claude, approved by Michael Paik.

- README, License: one line points to `rolldabones/LICENSING.md` (v1.0.0, new), which states once what the account's two licenses permit, that a Client's use in its own operations may fall outside NonCommercial, how to ask and why the two licenses do not mix.
- README and `CITATION.cff` to v1.11.3; no other file changed.

## v1.11.2 (2026-11-03)

- README, A note on accuracy: the reissue history, one 413-word paragraph, becomes a table of dates, changes and issues between an opening paragraph (the EU AI Act status as re-checked on 30 July 2026) and a closing one (amendment notes, Unknown and counsel flags, not legal advice). No claim changed; "an independent review" for 20 October 2026 reads as the change it made. The manuscript and the instruments are unchanged byte for byte.
- README and `CITATION.cff` to v1.11.2. Train C of the improvement rotation (review of 24 October 2026). Prepared with Claude, approved by Michael Paik.

## v1.11.1 (2026-11-02)

Patch release. `AI_Audit_Due_Diligence_Checklist_v5_2.md`, "IDs and Master Reference Parts": the link to the Master Reference still named `AI_GRC_Master_Reference_v7_12.md`, which v1.11.0 removed; it names `AI_GRC_Master_Reference_v7_13.md`, and the v5.2.0 amendment note says so. Found by the account's sweep gate (B2 HIGH) after the v1.11.0 release, where the pre-release check had passed because the old file was still present. README masthead, How to Cite and `CITATION.cff` to v1.11.1. Prepared with Claude, approved by Michael Paik.

## v1.11.0 (2026-11-02)

Minor release, 2 November 2026 (KST): train B of the improvement rotation (whole-account review of 24 October 2026, reader report 02), on Michael Paik's approval of the drafted text the same day. Prepared with Claude, approved by Michael Paik.

### Manuscript
- **Three doctrines.** Introduction: "It has two anchoring principles" reads "It rests on three doctrines, and two of them anchor it", and the paragraph closes with one sentence naming Informed Intent in the DOCTRINE.md section 8 sentence form and pointing to Chapter 9. Chapter 9: "the two doctrines at the center of this book" reads "the first two of the three doctrines at the center of this book"; the gap argument that follows is unchanged.
- **One five-condition test, end to end (Chapter 9).** The paragraph naming the five authorizer conditions places the competence to understand under Knowledge, as DOCTRINE.md section 2 does, not under Authority, and states Evidence as the account, its testing and the residual risk in the record. The audit paragraph and the "Informed Intent breaks this pattern" paragraph, which had named three conditions, now name all five.
- **The exit.** The pre-deployment specification (Chapter 9), the principal's written commitment (Chapter 11) and Punchlist item 21 (Chapter 22) add exit to the specification's elements: who may withdraw the system, on what trigger and to what fallback (DOCTRINE.md section 2: "An authorization missing its exit is not an authorization; it is a hope").
- `manuscript/` regenerated with `split_markdown.py` at the 240,000-byte ceiling: same 32 part names, four parts change in text, verified to rebuild the manuscript byte for byte (822,260 bytes).

### Instruments
- `AI_GRC_Master_Reference_v7_12.md` reissued as `AI_GRC_Master_Reference_v7_13.md`. Part 12, Colorado: the entry names the statutory allocation of liability beside the disclosure regime and says "no new private right of action"; a paragraph states C.R.S. 6-1-1707 (1), (2), (4), (5), (6) and (7)(a) to (d), read from SB 26-189 as finally passed on leg.colorado.gov on 2 November 2026 (KST), with the practical consequence for own-acts indemnities in developer-deployer contracts. Dated amendment note, Version 7.13. `master-reference/` regenerated at the 60,000-byte ceiling: six parts, the first renamed for the new version, verified to rebuild the source byte for byte (264,597 bytes).
- `AI_Audit_Due_Diligence_Checklist_v5_1.md` reissued as `AI_Audit_Due_Diligence_Checklist_v5_2.md`: ID 1.28 added on Michael Paik's express ruling of 2 November 2026, which reopens the no-further-additions rule for this row alone (developer-deployer contracts against 6-1-1707 and the deployer's uses against the developer's intended-use documentation, Master Reference Part 12); question count 198 to 199; synchronized with the Master Reference v7.13; dated amendment note, v5.2.0.
- Removed, per the convention that superseded versioned instruments are deleted: `AI_GRC_Master_Reference_v7_12.md`, `AI_Audit_Due_Diligence_Checklist_v5_1.md` and the superseded first `master-reference/` part; prior versions remain in the tag chain.
- Not reproduced and not changed: the review's Article 111(2) item (no grandfathering passage in the manuscript, the Master Reference or the Checklist at v1.10.0); the Master Reference "triad" line, which already names all three doctrines.

### Lockstep
- README masthead, the instruments paragraph (new filenames, 199 questions, the accuracy note) and How to Cite, and `CITATION.cff`, to v1.11.0.

## v1.10.0 (2026-10-31)

Manuscript release (minor), 31 October 2026 (KST), on Michael Paik's instruction of the same day to revise the Conclusion to the thinking set out in *The Artificial Familiar* (AI Governance Academy v1.15.0, 30 October 2026). Prepared with Claude, approved by Michael Paik. No appendix instrument changes.

### Changed
- `Final_Liability_Rests_with_the_Human.md`, Conclusion, "The Workshop" and "Lamp, Bench, Seal". **Change of view, recorded in the text.** The Conclusion called the homunculus "the right figure for the agent"; it now says that the author first took it so, that his thinking on agentic AI has moved and why (the homunculus invites the question of resemblance, and agents that plan and call tools make that mistake easier and more expensive), and it makes the familiar the figure for the agent: commissioned for a purpose on stated terms, kept small enough to be owned and sent away when the work is done. *The Artificial Familiar* is cited, with its link, as where that thinking now lives. The three stations, the lamp and the first seal now name the familiar; the second seal reads "A familiar answers to the name its keeper gave it; the seal carries the keeper’s own." **Correction:** "The oldest dream of making a mind is the homunculus" is replaced, because older made beings exist (the bronze guardian of Crete, the clay man of the Talmud); the passage now places the alchemist's homunculus among them. The workshop image keeps the clerk-engine and its key and drops the "soot-smudged fingers" and "labors" language, in line with the piece's premise that AI is not anthropomorphized. Doctrine unchanged; the lamp, bench and seal and every other passage of the Conclusion unchanged.
- `manuscript/24-conclusion.md` carries the same text, so the derived parts still rebuild the source of record byte for byte; `manuscript/README.md` gives the part's size as 10 KB.
- README masthead, How to Cite and `CITATION.cff` to v1.10.0 in lockstep.

## v1.9.2 (2026-10-20)

Corrections release (patch), 20 October 2026 (KST). Independent review of 20 October 2026; changes made with Claude, approved by Michael Paik. Both appendix instruments are reissued under new version numbers rather than edited in place; the manuscript is corrected in place, as the file of record.

### Changed
- `AI_GRC_Master_Reference_v7_11.md` reissued as `AI_GRC_Master_Reference_v7_12.md` (262,037 bytes) with a dated amendment note of 20 October 2026 (KST). Law and citation: EU AI Act application dates pinned to Art. 113, third paragraph, points (a) and (c), as replaced by Regulation (EU) 2026/1744, Art. 1, point (40), and Art. 111(4) (Art. 1, point (39)(b)); the Article 5(1)(ba) and (bb) date confirmed at 2 December 2026 and the Unknown at C3 and C4(d) closed; Art. 43 conformity assessment restated (Annex VI, Annex VII as a procedure, Art. 43(3) as replaced); sandboxes are Arts 57 to 59; Art. 53(1)(c) and (d) separated. Korea: Act No. 21311 in force 22 January 2026 except its 21 July 2026 provisions; Decree No. 36580 described; Art. 32 rests on the three conjunctive criteria of Decree Art. 24(1); Art. 36(3) deems the appointing operator, not the representative, to have committed a violation; the grace period is MSIT administrative policy. Colorado: SB 26-189 enacted 14 May 2026, repeal effective 1 January 2027; HB 26-1263 took effect 12 August 2026, operator duties from 1 January 2027; the *xAI v. Weiser* stay cited as *X.AI LLC v. Weiser*, No. 1:26-cv-01515 (D. Colo. Apr. 27, 2026) (minute order, ECF No. 24), its date and scope verified from the docket text as published by PacerMonitor, read 20 October 2026 (the signed order was not read), with the scope stated and the absence of a preliminary-injunction motion as of 6 October 2026 recorded. Facts: UC Berkeley CLTC Profile Version 1.2 is April 2026; CSET Operationalizing AI Guidance has 18 steps under top-level stages, licensed CC BY-NC 4.0; Kleinberg, Mullainathan and Raghavan dated 2017. Doctrine: the Doctrinal Frame opens each doctrine with its DOCTRINE.md section 8 sentence form, verbatim. (BOOK-03, -04, -07, -08, -09, -15, -16, -17, -20, -25, -29, -38, -45, -46, -48, X-01.)
- `AI_Audit_Due_Diligence_Checklist_v5_0.md` reissued as `AI_Audit_Due_Diligence_Checklist_v5_1.md` with a dated amendment note: IDs 0.08 (Art. 113 pinpoints; pointer to Master Reference item C3), 4.14 and the tier key (Art. 111(4)), 5.07 (Art. 43 procedures), 6.13 (Art. 3, point (49)(d)), 10.13 (CLTC Profile date), 1.21 (date form); currency date defined; synchronized with Master Reference v7.12. No question added, withdrawn or renumbered. (BOOK-04, -07, -08, -09, -10, -24, -36.)
- `Final_Liability_Rests_with_the_Human.md`. Law: *Caremark* framed as care and good faith, loyalty placement attributed to *Stone v. Ritter*; Appendix F-1 matrix G3 and G4 aligned with Art. 26(7) and Recital 96; FDA design controls restated under the QMSR (21 CFR 820.30 reserved since 2 February 2026; ISO 13485:2016 cl. 7.3); Colorado repeal enacted 14 May 2026 with effect from 1 January 2027, and the *X.AI LLC v. Weiser* minute order (ECF No. 24) cited, its date and scope verified from the docket text on 20 October 2026; FRIA B2 and B5 rest on Art. 26(1) and (4); F6 quotes Art. 3, point (49)(d). Facts and sources: Glass Lewis figures (February 2026, 2025 proxies); CSET Harmonizing brief dated September 2025 and its groupings called topic areas; Informed Consent history (*Schloendorff*, *Salgo*, Nuremberg); bliss point originates in economics; Block "about four thousand"; NIST AI 800-4 wording and participant count; CSET Operationalizing "eighteen steps"; the *Sanford* "materially inconsistent" point attributed to commentary, without quotation marks; the GDPR enforcement sentence stated as the author's reading. Cross-references: Checklist IDs for vendor due diligence (1.17 to 1.19, 0.06), FRIA Section D row 5, H5 trigger review, "Checklist IDs" in D13; ToC entries for Appendices D, E, F, K and L match their headings. Instruments: the Appendix E worked example's system now scores hardship-credit and forbearance applications, so its Annex III point 5(b) basis applies; the FRIA "shaded" instruction is removed until the mandatory set is settled; GRCnext's five primitives stated, Evidence not a primitive. Doctrine: Chapter 7's attributes and Chapter 9's authorizer conditions use the DOCTRINE.md section 8 list forms. Consistency: Chapter 5 counts five misreadings, as Chapter 6 treats them; "specification" names the first inspection point throughout. Style and conversion: 50 orphan Punchlist footnote markers and 86 pandoc list separators (Appendices K and L) removed; US spelling (equalized, materialize, defense, catalog, cataloged, cataloging); three serial commas removed. (BOOK-01, -02, -05, -06, -11, -12, -13, -17, -18, -19, -20, -21, -22, -23, -24, -26, -27, -28, -30, -31, -33, -37, -39, -40, -41, -42, -43, -44, -45, -47, -48.)
- `README.md`: the three doctrines stated in their DOCTRINE.md section 8 sentence forms, verbatim (X-01); edition line records the October corrections (BOOK-35); instrument links to v7.12 and v5.1; the accuracy note records this release; masthead and How to Cite to v1.9.2. `CITATION.cff` to 1.9.2 in lockstep.
- `manuscript/` regenerated with `split_markdown.py` at the 240,000-byte ceiling: same 32 part names, verified to rebuild the manuscript byte for byte (820,820 bytes).
- `master-reference/` regenerated from `AI_GRC_Master_Reference_v7_12.md` at the 60,000-byte ceiling: six parts (previously five, because one part passed the ceiling), verified to rebuild the source byte for byte (262,037 bytes).

### Removed
- `AI_Audit_Due_Diligence_Checklist_v5_0.md`, `AI_GRC_Master_Reference_v7_11.md` and the superseded `master-reference/` part files, per the convention that superseded versioned instruments are deleted; prior versions remain in the tag chain.
- From the manuscript, the "About BABL AI" promotional block that closed Appendix H (BOOK-14).

### Errata to shipped entries
- v1.9.0: the Annex III point 5(b) worked example it describes as in "the Appendix D worked example" is in Appendix E; the sentence it places "at Chapter 14" sending vendor due diligence to "Sections 1 and 2" was in Chapter 19, Chapter 21 and Appendix E (corrected in this release) (BOOK-34).

### Not changed, and why
- The Part II subtitle "Two Propositions That Do Not Negotiate" is the author's title and stays (BOOK-32). The one-column "Field" tables in Appendices D to F stay as they are (BOOK-40, in part).
- The book README's "thirty-five years" against the account's "more than 25 years" waits for the author's ruling on one figure (X-07).
- `grc/README.md`, in another repository, still links `AI_Audit_Due_Diligence_Checklist_v5_0.md` and `AI_GRC_Master_Reference_v7_11.md`; those links move with that repository's next release.

## v1.9.1 (2026-10-20)

- LICENSE: two defects against the Creative Commons legal code corrected (the space in 'ShareAlike. In'; the CC0 sentence of the closing notice). Operative terms unchanged.
- README masthead, How to Cite and `CITATION.cff` to v1.9.1 in lockstep.

## v1.9.0 (2026-10-18)

The two monoliths, book half: session T8 of the whole-account review of 15 October 2026 (KST) (doc section 7; reviewer reports 05 and 06), under rulings 1 and 3 of 15 October 2026. Structure for both appendix instruments; three classes of correction in the manuscript and nothing else in it.

### Changed
- `AI_Audit_Due_Diligence_Checklist_v4_11.md` reissued as `AI_Audit_Due_Diligence_Checklist_v5_0.md` (ruling 3). Every one of the 198 questions carries a stable section-dotted ID, 0.01 to 10.16, append-only, in the order the questions stood at v4.11, so the no-renumbering rule recorded at v4.10 holds. A Master Reference Part column names, per question, the Part or Appendix of the Master Reference v7.11 that states the control (sub-block default, row overrides where a prose pointer stood) and replaces the seven prose pointers inside question and How to Check cells. Alignment spaces inside table rows removed: 213,976 bytes to 97,866. The tier key, a pandoc HTML table whose column widths GitHub strips, is restated with the same text as two sections, Risk tier tags and Deployment context tags. The Regulation (EU) 2026/1744 application-date paragraph in the tier key and the four Unknowns in the currency note become pointers to the Master Reference's Currency and Open Points items C2 and C4. Master Reference Parts 24 to 26 cited as Appendix H.1 to H.3. Live UK spellings to US spelling; two dates to day-month-year. Dated amendment note on the instrument; no question added, withdrawn or changed in substance.
- `AI_GRC_Master_Reference_v7_10.md` reissued as `AI_GRC_Master_Reference_v7_11.md` (254,532 bytes). New head section, Currency and Open Points, items C1 to C7 (instruments and as-at date, EU AI Act application dates, Article 5(1)(ba) and (bb), the four Unknowns moved from the 30 July 2026 note, Korea, Colorado, the AI Liability Directive), each dated and cited by number from the Checklist. Item C5 records, as Unknown in content, a further amendment of the Korean Enforcement Decree, Presidential Decree No. 36580, in force 20 August 2026, shown on law.go.kr when read on 18 October 2026; nothing in Part 12 is changed on it. Parts 24 to 26, bibliography entries numbered as governance Parts, become Appendix H (H.1 to H.3); cross-references re-pointed; Parts 1 to 23 keep their numbers. "Source #7" to "#11" replaced by the works' short names. Part 1.3's three doctrine definitions open with the DOCTRINE.md section 8 sentence forms verbatim and the DOCTRINAL FRAME carries the pointer form; the Final Liability definition had named documented authority, knowledge and operational capability in place of the canon's three attributes (account guard F13, MR:215 at v7.10). Literal asterisks in Appendix E removed; two "(Article NN(see Part N.N))" re-punctuated; 3.5.1 set one heading level below 3.5; live UK spellings to US except proper names; three serial commas removed; one common-noun "Humans" lowercased. Dated amendment note on the instrument.
- `Final_Liability_Rests_with_the_Human.md`, under ruling 1 (legal pinpoints, Checklist citations, FRIA Section D matrix; nothing structural, no style edits). Thirty edits. **Legal pinpoints**, each against the primary text read on 18 October 2026 (EUR-Lex, Regulation (EU) 2024/1689 and Regulation (EU) 2026/1744; law.go.kr; leg.colorado.gov; the *X.AI LLC v. Weiser* docket, D. Colo. No. 1:26-cv-01515, ECF No. 24): Appendix F Art. 14(5) to 14(4)(d); Art. 27(4) to 27(3) with the template at 27(5), three places; re-use Art. 27(1) to 27(2); worker consultation rests on Art. 26(7) and national labor law, not Art. 27, two places plus the Section G heading; public consultation is not required by Art. 27 (Recital 96 encourages stakeholder involvement), two places; one sentence that Art. 27 applies to Annex III deployers from 2 December 2027 (Art. 113, third paragraph, point (c), as replaced by Regulation (EU) 2026/1744, Art. 1, point (40)); the Appendix E worked example's FRIA marked as required from 2 December 2027 and completed in advance; the Appendix D worked example's Annex III point 5(b) basis restated as creditworthiness evaluation on a stated illustrative assumption, since 5(b) does not cover complaint triage; Chapter 19 states the Official Journal publication (24 July 2026) and entry into force (27 July 2026) of Regulation (EU) 2026/1744; Chapters 15 and 20 state that Korea's Enforcement Decree is in force (since 22 January 2026, most recently amended by Presidential Decree No. 36580, in force 20 August 2026) instead of "once implementing regulations are finalized"; Chapters 14 and 19 confine the Art. 25 deployer-to-provider shift to high-risk AI systems (Art. 25(1)(b) and (c)); Chapter 3 names Senate Bill 26-189 and the *X.AI v. Weiser* minute order of 27 April 2026. **Checklist citations**: the manuscript cited question numbers the Checklist never carried; each is re-keyed by content to a v5.0 ID (Q18 to Q21 to IDs 1.09 to 1.12; Q21 to 1.12; Q101 to 6.13; Q12 and Q24 to 1.17 to 1.19) or, where the sentence gives a bare number with no content to match (Q67, Q72, Q104), to the Checklist section; "Section 1 (Vendor and Third-Party DD)" corrected to the vendor rows of Section 1 and Sections 3 to 5; the question count "one hundred and eighty-seven" to "one hundred and ninety-eight". **FRIA Section D**: the one-column table left by conversion is restored as a fillable six-column matrix (Fundamental Right, Affected, Severity, Probability, Reversibility, Rationale) over the same fifteen rights, the columns taken from the template's own text and Master Reference Appendix F.
- `manuscript/` regenerated with `split_markdown.py` at the 240,000-byte ceiling: same 32 part names, nine parts change in text, verified to rebuild the manuscript byte for byte (820,783 bytes).
- `master-reference/` regenerated at the 60,000-byte ceiling: five parts, all renamed because the head section and Appendix H move the H2 boundaries, verified to rebuild the source byte for byte (254,532 bytes).
- `README.md`: masthead and How to Cite to v1.9.0; Files in this repository links both instruments by their new filenames and states the ID scheme; the accuracy note records the 18 October 2026 restructuring and the scope of the manuscript corrections. `CITATION.cff` to 1.9.0 in lockstep.

### Removed
- `AI_Audit_Due_Diligence_Checklist_v4_11.md`, `AI_GRC_Master_Reference_v7_10.md` and the five superseded `master-reference/` part files, per the convention that superseded versioned instruments are deleted; prior versions remain in the tag chain.
- From the Master Reference, four author drafting notes that read as published guidance, recorded here: "Light citation under fair use is fine in commercial book context" (CSET Harmonizing entry); "License to be confirmed at integration time; CSET typically uses CC BY-NC 4.0 for issue briefs" (CSET Operationalizing entry, replaced by an instruction to verify the license on the publication page); "pending verification of the Operationalizing brief's specific terms at first chapter-drafting use" (same entry); "Promotion requires 4P doing load-bearing work in two or more chapter drafts of the companion Master" (DOCTRINAL FRAME, 4P caveat).

### Not changed, and why
- The manuscript's structure, repetition, proportion, doctrine variants, house style, footnote markers, conversion debris other than Section D, duplicated appendices and unsourced figures (report 06 sections A8 to A12, B3 to B6 and C) are report-only under ruling 1; the structural editorial pass is a separate track Michael opens after T9. Two items the corrections touched and left: Chapter 19 still omits the Annex I (2 August 2028) and Art. 50(2) (2 December 2026) dates, and a sentence at Chapter 14 sends vendor due diligence to "Sections 1 and 2" without a question number.
- Which FRIA rights the source shaded as mandatory is Unknown: the shading was lost in conversion and the restored matrix does not guess it.
- Master Reference additions the review proposed (Illinois HB 3773 in Part 12 and Appendix D; ISO/IEC 42005, 42006, 27701:2025 and 29100:2024 editions) are additions of law and standards not verified against primary sources in this session; left for a later release.
- The account guard's F13 lines at Checklist ID 1.24 and Master Reference 3.5.1 are read as heuristic false positives: the GC sign-for's four operational components and the rhetorical "authority, risk, evidence and consequence" are not enumerations of the authorizer conditions.

## v1.8.1 (2026-10-17)

README doctrine conformance, session T3 of the whole-account review of 15 October 2026 (doc section 1; reviewer report 05, Elegance item 7). README only; the manuscript, its parts, the Checklist and the Master Reference are unchanged byte for byte.

### Changed
- **README, The argument in three doctrines:** the Slow AI paragraph stated the doctrine as a speed rule ("running at speed everywhere else"), which DOCTRINE.md section 1 disclaims; the Informed Intent and Final Liability paragraphs compressed the doctrines without the instrument's four elements or the three attributes. Each paragraph now carries the sentence form of DOCTRINE.md v1.2.0 section 8, keeping the book's own closing clause, and a sentence points to DOCTRINE.md.
- **README, Part of the ecosystem:** computational-drafting added as the fifth nearest neighbor, returning the pointer it gives this repository (ECOSYSTEM.md protocol item 9).
- `CITATION.cff`, the README masthead and How to Cite move to v1.8.1 in lockstep.

### Not changed, and why
- The Checklist and Master Reference mechanical items the review lists (MR masthead and Part cross-references, "Chapter 25", literal asterisks, "(Article 17(see Part 6.7))", UK spellings in both instruments) wait for session T8, which re-versions both instruments in one release (Checklist v5.0.0, Master Reference v7.11), so neither re-versions twice in a week and the versioned filenames other repositories link to stay valid until then.
- The manuscript's doctrine variants and house-style lines are report-only under ruling 1 of 15 October 2026; T8 corrects only its legal pinpoints, Q-citations and the FRIA Section D matrix.

## v1.8.0 (2026-10-15)

Legal currency release for the two appendix instruments, session T1 of the whole-account review of 15 October 2026 (KST). Corrections only; the structural changes the review scheduled (Checklist IDs and a Master Reference Part column, Master Reference currency head section) wait for session T8. Every correction of substance is struck in place and itemized in a dated amendment note on the instrument's face; nothing is silently re-dated. The manuscript is unchanged byte for byte.

### Changed
- `AI_GRC_Master_Reference_v7_9.md` reissued as `AI_GRC_Master_Reference_v7_10.md` (247,179 bytes) with an amendment note of 15 October 2026 (KST). **Corrections of substance.** *[Binding law. As at 15 October 2026 (KST).]* Part 12: HB 26-1263 was signed on 29 May 2026, not 1 July 2026 (Colorado House Democrats release of 29 May 2026; leg.colorado.gov for the 1 January 2027 effective date); the 1 July figure entered on 30 July 2026 from a search summary and is struck. Part 4.2: the Article 5 list gains point (g), biometric categorisation inferring protected characteristics, which it had omitted. Part 21: the Article 99(4) list gains point (g), the Article 50 transparency obligations, the basis for the EUR 15M or 3 percent figure the Checklist cites. Part 21: "maintains the GPAI model registry" struck; the Act establishes no such registry. Part 1.4: the [M] marking no longer claims Articles 10 and 15 mandate a named fairness method; Article 10(2), points (f) and (g), require bias examination and mitigation only. **Corrections of citation and fact.** China's Interim Measures named once; Japan's 2022 Governance Guidelines attributed to METI, not the Cabinet Office; the EEOC hiring guidance recorded as removed in January 2025; the AILD entry anchored to the OJ notice of 6 October 2025 (C/2025/5423) instead of "as of April 2026"; Korea's Act No. 21311 carries the one English name the account uses, with the Korean title; NYC Local Law 144 in effect 1 January 2023, enforced from 5 July 2023; "Part 4.2 Principle" corrected to Part 1.4 in six places; "companion book Chapter 25" corrected to Chapter 20; "substantial modification per Article 25" now cites Article 3, point (23); the undated USD conversion deleted; masthead "Supersedes Version 7.7 (May 2026)" corrected to Version 7.8 (July 2026). Found by reviewer report 05 (items A1, A3, A5 to A7, A9 to A15) of the review.
- `AI_Audit_Due_Diligence_Checklist_v4_10.md` reissued as `AI_Audit_Due_Diligence_Checklist_v4_11.md` (213,976 bytes). **One question row added**, All Tiers, screening every system against the original Article 5(1), first subparagraph, prohibitions, points (a) to (h), with the Article 5(2) to (7) conditions where real-time remote biometric identification is in scope; the instrument previously tested only points (ba) and (bb). **Question count 197 to 198** (All Tiers 106, High-Risk 81, GPAI 6, Limited Risk 5), counted by script: a question row carries a tier tag in cell one and a non-empty cell two. The Art. 50(3) row added at v4.10 carried three of five cells and now carries Deployment Context (Customer-Facing) and Status. The serious-incident definition is pinpointed to Art. 3, point (49). The masthead names the Master Reference version it is synchronized with. Two amendment notes added at the foot: 13 August 2026 (recording v4.10, which shipped without one) and 15 October 2026. Reviewer report 05, items A2, A4, A18 and B1, B6.
- `master-reference/` regenerated from `AI_GRC_Master_Reference_v7_10.md` with `split_markdown.py` at the 60,000-byte ceiling: five parts, largest 58,997 bytes, verified to rebuild the source byte for byte (247,179 bytes). The first part is renamed `00-ai-grc-master-reference-file-version-7-10-to-part-2.md`; the four others keep their names and change in text only where the source changed.
- `README.md`: masthead and How to Cite to v1.8.0; Files in this repository links both instruments by their current filenames and states the Checklist count; the accuracy note records the v4.10 and 15 October 2026 reissues (it had still read "v4.9"). `CITATION.cff` to 1.8.0 in lockstep.

### Removed
- `AI_Audit_Due_Diligence_Checklist_v4_10.md`, `AI_GRC_Master_Reference_v7_9.md` and `master-reference/00-ai-grc-master-reference-file-version-7-9-to-part-2.md`, per the convention that superseded versioned instruments are deleted; prior versions remain in the tag chain.

### Not changed, by ruling
- The manuscript's five Appendix F pinpoints, the Annex III 5(b) misclassification in the worked example, the outrun entry-into-force and Korea sentences and the Q-number citations are recorded in the review (doc §2, reviewer report 06) and wait for session T8 under ruling 1 of 15 October 2026.

## v1.7.1 (2026-10-15)

Byline correction, on the author's instruction of 15 October 2026 (KST). No change to the analysis.

- **`README.md` masthead:** "Former General Counsel, BABL AI. CEO, GRC Solutions Korea." now reads "CEO, GRC Solutions Korea."
- **`Final_Liability_Rests_with_the_Human.md`, three lines.** Title page: the line "Former General Counsel, BABL AI" and the blank line after it are removed, so the title page reads name, then "CEO, GRC Solutions Korea". Appendix H byline: "Son-U Michael Paik \| former General Counsel, BABL AI" now reads "Son-U Michael Paik \| CEO, GRC Solutions Korea". Appendix H sign-off: "Former General Counsel, BABL AI" now reads "CEO, GRC Solutions Korea". SHA-256 `b7de127791f1575edf04e58b49910d5d07d5484fd88791eb978e2f1404cc955c`, 823,287 bytes; it was `8892648a7cd63eae8665baca474554d88a48a26b286dd293eab8542506c783f4`, 823,334 bytes.
- **`manuscript/` regenerated in the same release**, under the standing rule. `split_markdown.py` at a 240,000-byte ceiling, same 32 part file names. The 32 parts rebuild the manuscript byte for byte, 823,287 bytes, verified before commit. Two parts change in their text (`00-table-of-contents.md`, `29-appendix-h-why-slow-ai.md`). The reading index `manuscript/README.md` also changes: 26 of its 32 Size (KB) figures read 1 higher. Run against the v1.7.0 manuscript, the current tool reproduces all 32 parts byte for byte and gives the same 26 higher figures, so the index committed at v1.6.0 came from an earlier version of the tool and the difference is not caused by this edit.
- Biography prose naming the former role is unchanged. Masthead, How to Cite and `CITATION.cff` move to v1.7.1 in lockstep. `AI_Audit_Due_Diligence_Checklist_v4_10.md`, `AI_GRC_Master_Reference_v7_9.md`, `master-reference/` and `LICENSE.md` are unchanged byte for byte.

## v1.7.0 (2026-09-07)

Structure release, and one correction of substance in the Master Reference. Same shape as v1.6.0 for the manuscript: a new publication surface, no change to the analysis.

**Correction of substance, `AI_GRC_Master_Reference_v7_9.md` line 65.** *[Author's doctrine. As at 7 September 2026 (KST).]* The doctrinal frame paragraph read "the GRC next™ primitives in the companion Master's Appendix L", using the retired spaced form of the mark. **That is struck.** The canonical form is the closed-up **GRCnext™**, adopted account-wide on 30 July 2026 and logged at `ECOSYSTEM.md` v1.7.2. The line is live prose carrying no supersession marker, so it asserted the retired form as current; it was reported as a HIGH class D1 finding by the weekly account sweep on 6 and 7 September 2026 and is the last surviving occurrence of the spaced form in live prose anywhere in the account. One character. The file is 242,311 bytes, one byte smaller than at v1.6.1.

**`master-reference/` added: 5 derived parts and a reading index.** Generated by `split_markdown.py` in the private `account-maintenance` toolchain at a 60,000-byte ceiling. The parts carry the Master Reference text unchanged; the only inserted lines are the navigation blocks fenced by sentinels at the head and foot of each part, which the verifier strips. The 5 parts rebuild `AI_GRC_Master_Reference_v7_9.md` byte for byte, 242,311 bytes, verified as a separate run before this release.

**The monolith stays where it is.** `AI_GRC_Master_Reference_v7_9.md` remains at the repository root as the source of record, the file to cite and the file to download, and every existing link to it continues to resolve. Decision D-A2, 6 September 2026.

**Why 60,000 and not the account's 240,000 splitting ceiling.** At 240,000 the file yields two parts, the larger 238,641 bytes, which is 1,359 bytes of headroom and a part that is itself close to the size the browser was struggling with. The ceiling that matters is distance from the render bound, not distance from the next part boundary: the smallest file measured on this account not to render is 311,517 bytes, and 60,000 puts every part at under a fifth of it. The five parts range from 25,337 to 58,452 bytes, which sits between the manuscript's parts (median 21,577) and the Primer's (median 62,136), so this repository's two derived-parts directories are now comparable to read.

**Standing rule, restated for this document.** The parts are derived, never edited. Any change to `AI_GRC_Master_Reference_v7_9.md` is followed by regenerating `master-reference/` from it in the same release, and the weekly account sweep verifies that the parts rebuild it byte for byte. A part edited by hand is a defect, not a variant. `RUNBOOK.md` section 3.

**README** records the new reading surface in Files in this repository; masthead, How to Cite and `CITATION.cff` in lockstep at v1.7.0. Every other file in this repository is unchanged byte for byte.

## v1.6.1 (2026-09-06)

Citation infrastructure, doctrine citation line and lockstep maintenance. Session C of the September 2026 improvement pack, one patch release per repository across all 21 public repositories.

- **`CITATION.cff` added** in the house form settled at D-C1: no `type` field, `version` and `date-released` in lockstep with the README, `license` as the SPDX identifier for this repository's licence, `abstract` taken from this repository's ECOSYSTEM.md role line rather than newly written.
- **How to Cite block** aligned to this release and pointing at `CITATION.cff`.
- **Doctrine citation line added** to the Part of the ecosystem section. This repository restates a doctrine and cited DOCTRINE.md nowhere, which is the Class E2 finding the new guards report.
- All other files in this repository are unchanged byte for byte.

## v1.6.0 (2026-09-06)

Structure release. The manuscript is published in parts that GitHub renders. No change to the manuscript, to either appendix instrument or to the analysis.

**`manuscript/` added: 32 derived parts and a reading index.** Generated by `split_markdown.py` in the private `account-maintenance` toolchain. The parts carry the manuscript text unchanged; the only inserted lines are the navigation blocks fenced by sentinels at the head and foot of each part, which the verifier strips. The 32 parts rebuild `Final_Liability_Rests_with_the_Human.md` byte for byte, 823,334 bytes, verified before this release.

**Correction of substance, README.** *[Author's doctrine. As at 6 September 2026 (KST).]* The README stated that `Final_Liability_Rests_with_the_Human.md` "renders in the browser, so you can read the whole book from the repository page." **That is struck.** GitHub does not render a markdown file above its size limit, and the manuscript has been above that limit since first publication, so the statement was false for the whole life of the file. Verified 4 September 2026 against GitHub's blob payload for the file, which returns `richText: null` and `richTextTruncated: true` and offers no source view either. The replacement text names the manuscript as the file of record and points readers to `manuscript/`.

**Standing rule.** The parts are derived, never edited. Any change to the manuscript is followed by regenerating `manuscript/` from it in the same release, and the weekly account sweep verifies that the parts rebuild the manuscript byte for byte. A part edited by hand is a defect, not a variant.

**Unchanged, byte for byte.** `Final_Liability_Rests_with_the_Human.md`, SHA-256 `8892648a7cd63eae8665baca474554d88a48a26b286dd293eab8542506c783f4`. `AI_Audit_Due_Diligence_Checklist_v4_10.md`, `AI_GRC_Master_Reference_v7_9.md` and `LICENSE.md`, all byte for byte. The two appendix instruments render as they are and are not split.

## v1.5.2 (2026-08-17)

Decision recorded. No change to any instrument, to the manuscript or to the analysis.

**The `v7_9` reissue question is answered: `v7_9` stands.** v1.5.1 carried the Korea citation correction as a dated amendment note rather than reissuing `AI_GRC_Master_Reference_v7_9.md` as `v7_10`, and flagged the choice as open. It is now decided.

**The rule, going forward, for both appendix instruments.** The reissue convention that governed `v7_8` to `v7_9` and `v4_9` to `v4_10` is reserved for changes to **the analysis, the question set or the obligation mapping**. A corrected instrument number, carried in a dated amendment note that names what was struck, does not meet it. Reissuing an 1,800-line reference to correct two statute numbers would bury the correction in a whole-file diff, which is the opposite of what the supersession convention is for.

**Why this is a release and not a silent edit.** The open question was published in the v1.5.1 changelog. Answering it in place would have re-written a released entry. The v1.5.1 entry stands as written and this entry supersedes it on the point.

**Unchanged.** `AI_GRC_Master_Reference_v7_9.md`, `AI_Audit_Due_Diligence_Checklist_v4_10.md` and the manuscript, all byte for byte.

## v1.5.1 (2026-08-17)

Maintenance. Korea instrument citations in the Master Reference corrected to the texts in force.

**Correction of substance.** *[Binding law. Pinpoint: Act No. 21311; Presidential Decree No. 36506. As at 17 August 2026 (KST).]* `AI_GRC_Master_Reference_v7_9.md` Part 12 named **Act No. 20676** and **Presidential Decree No. 36053** as the operative Korean instruments. **That is struck.** The Act in force is **Act No. 21311 of 20 January 2026**; the Enforcement Decree in force is **Presidential Decree No. 36506 of 20 July 2026**; both in force 21 July 2026. The original enactments are retained as the commencement record. This correction was made in `ai-governance-for-boards` v1.5.0 on 13 August 2026 and did not propagate here at the time.

**Recorded as an amendment note, not a reissue.** The correction is carried as a dated amendment note at the head of the file, following the practice adopted for this instrument on 30 July 2026. The filename is unchanged and `v7_9` is not reissued as `v7_10`: the correction is to a citation, not to the analysis, and the reference is designed to cite obligations by article rather than by date.

**Unchanged.** The manuscript, byte for byte. `AI_Audit_Due_Diligence_Checklist_v4_10.md`, byte for byte; it carries no Korean instrument numbers.

## v1.5.0 (2026-08-13)

Checklist v4.10, closing the Article 50(3) tier-note gap.

- `AI_Audit_Due_Diligence_Checklist_v4_9.md` reissued as `AI_Audit_Due_Diligence_Checklist_v4_10.md`. v4_9 is deleted per the supersession convention; prior versions remain retrievable from the tag chain.
- **New question row, Art. 50(3).** The risk-tier key already listed emotion recognition and biometric categorization among the Article 50 categories, but no question row covered them. The Checklist carried Art. 50(1), 50(2), 50(4) and 50(7) and skipped 50(3). That gap is now closed. Question count 196 to 197.
- The new row states the point that makes Art. 50(3) different: it is a **deployer** duty. Unlike Art. 50(1) and Art. 50(2), it is not discharged upstream by the provider, so an organization that merely procures and switches on an emotion recognition or biometric categorization system holds it directly. Verification guidance covers the GDPR lawful basis and the Article 9 special-category condition, which biometric and emotion data will usually engage, and requires that reliance on the law-enforcement derogation be authorized and recorded.
- License metadata sweep folded into this release: `SPDX-License-Identifier: CC-BY-NC-SA-4.0` and the canonical Creative Commons legal code added inside the existing license file, filename unchanged, human summary retained above the legal code.

## v1.4.0 (2026-07-30)

Minor release. Substantive review of both appendix instruments against the published text of Regulation (EU) 2026/1744.

### Changed
- `AI_Audit_Due_Diligence_Checklist_v4_8.md` reissued as `AI_Audit_Due_Diligence_Checklist_v4_9.md`. The risk-tier key stated that the Digital Omnibus was awaiting Official Journal publication and that "the enacted dates remain binding", which would have directed an auditor to scope Annex III high-risk obligations as applying from 2 August 2026. That instruction was correct when written and became wrong on 27 July 2026. It is replaced with the in-force position: deferrals to 2 December 2027 (Article 6(2) and Annex III) and 2 August 2028 (Article 6(1) and Annex I) per Recital 40, with the general application date of 2 August 2026 unchanged. The Article 50 note now records the four-month Article 50(2) transitional period ending 2 December 2026, available to providers only and only for systems placed on the market before 2 August 2026 (Recital 38). The Article 50 marking question is split so that the Article 50(2) provider marking duty and the Article 50(4) disclosure duty are tested separately. The Article 25 alert carries the amended value-chain duties. Nine questions added: three on the new Article 5(1)(ba) and (bb) prohibitions and their Article 5(1a) scoping, one on Article 4 AI literacy as replaced, one on the Article 3(14) and Article 6(1a) to (1c) safety-component narrowing, one on Article 2(13) limitations, one on the Article 4a bias-detection legal basis replacing the deleted Article 10(5), one on the Article 42(3) cybersecurity presumption, and one from the Article 50 split. Count moves from 187 to 196 across the same 11 domains. No existing question was renumbered; the instrument carries no question numbers and new rows were appended within their sub-blocks so that ordinal positions of existing rows are preserved.
- `AI_GRC_Master_Reference_v7_8.md` reissued as `AI_GRC_Master_Reference_v7_9.md`. A dated amendment note was added rather than re-dating the reference wholesale, consistent with the practice adopted across the account on 30 July 2026 and with the file's own design of citing obligations by article rather than by date. The note enumerates thirteen changes made by Regulation (EU) 2026/1744 with article and recital citations. The Part 21 enforcement-timeline paragraph carried the same superseded "pending publication" wording as the Checklist and is corrected. The Part 4.2 prohibited-uses list gains the two new Article 5 prohibitions. The Article 4 references in Part 1 and Appendix A are re-based to the replaced text. The Appendix D crosswalk row still named the repealed Colorado SB 24-205 and now names the SB 26-189 ADMT Act, matching Part 12. The Part 12 Colorado entry gains the *xAI v. Weiser* enforcement stay and the Chatbot Safety Act (HB 26-1263).
- README masthead updated to v1.4.0 in lockstep, with the accuracy note recording the reissue of both instruments.

### Removed
- `AI_Audit_Due_Diligence_Checklist_v4_8.md` and `AI_GRC_Master_Reference_v7_8.md` deleted, per the v1.2.0 precedent that superseded versioned instruments are removed rather than retained alongside their successors.

### Recorded as Unknown
- Four points are flagged for external counsel and recorded as Unknown in both instruments rather than resolved: whether a deployer offering a general-purpose interface falls within the Article 5(1a)(b) purpose test; whether the Article 63 simplified quality-management route extends to small mid-cap enterprises as well as SMEs, Recital 28 naming SMEs only; the status of the Article 50(7) implementing-act empowerment, Recital 41 stating it is removed while the operative text retains it; and the application date of the new Article 5 prohibitions, widely reported as 2 December 2026 but not confirmed against the operative amendment to Article 113.

### Unchanged
- The manuscript, byte for byte.

## v1.3.1 (2026-07-30)

Patch release. Regulatory currency in the README only.

### Changed
- A note on accuracy: the EU AI Act status re-checked on 30 July 2026 and the sentence rewritten. The Digital Omnibus on AI was adopted as Regulation (EU) 2026/1744 of 8 July 2026, published in the Official Journal on 24 July 2026 (OJ L, 2026/1744, 24.7.2026) and in force since 27 July 2026. The prior wording, that the original AI Act timeline remains the binding law until publication, ceased to be accurate on 27 July 2026. The note now records the binding deferrals (stand-alone Annex III high-risk obligations to 2 December 2027, AI embedded in Annex I regulated products to 2 August 2028) and that the general application date of 2 August 2026 is unchanged.
- README masthead updated to v1.3.1 in lockstep.

### Unchanged
- The manuscript, byte for byte.
- Both appendix instruments (AI Audit and Due Diligence Checklist v4.8, AI GRC Master Reference v7.8), byte for byte. Their in-file currency notes re-date when each instrument next versions, per the v1.1.0 policy. Both are queued for a substantive v4.9 and v7.9 pass triggered by the Official Journal publication.

## v1.3.0 (2026-07-15)

Manuscript housekeeping release. No content changes.

### Changed
- Manuscript (Final_Liability_Rests_with_the_Human.md): drafting-workflow completion marks (36 checkmarks) and the "Master Contents (Static Reference)" label removed from the Table of Contents. Chapter titles, structure and all body text unchanged.

## v1.2.0 (2026-07-15)

Same-day release versioning both appendix instruments following a full review pass, and correcting the omnibus procedural posture in both new versions by same-day in-place amendment, recorded here so that no versioned document is silently edited.

### Changed
- AI Audit and Due Diligence Checklist v4.7 replaced by v4.8. Corrections: EU AI Act Art. 26 deployer sub-article citations (input data 26(4), monitoring and provider notification 26(5), log retention 26(6)); new GPAI (Ch. V) tier tag added to the key and applied to six GPAI-obligation rows previously tagged High-Risk (Art. 6), with a key note that Section 10 agentic rows carry the High-Risk tag as a control-stringency scoping choice rather than an EU AI Act classification; dated digital omnibus timeline note in the risk-tier key; duplicated Section 4 subsection header removed and the OECD alignment row relocated; apostrophes normalized; header meta line updated to reflect the four-tag taxonomy.
- AI GRC Master Reference v7.7 replaced by v7.8. Corrections: the same Art. 26 sub-article fixes in Part 19.2 and Appendix D (the propagation source of the checklist error); Colorado entry rewritten to reflect SB 26-189 (signed May 14, 2026, effective January 1, 2027), which repealed and replaced SB 24-205; Texas TRAIGA (HB 149, effective January 1, 2026) added to the state patchwork; California bullet updated for TFAIA (SB 53), AB 2013, the SB 942 delay to August 2, 2026 and SB 243; federal landscape updated for the December 11, 2025 Executive Order on a national AI policy framework, with the caveat that state obligations remain in force unless displaced; Part 1 reference to the revoked October 2023 Executive Order updated; dated omnibus note added to Part 21; markdown glitch in the PRC heading fixed.
- Same-day amendment to both new versions: the omnibus notes as first committed described the regulation as awaiting Council adoption; the Council in fact gave final adoption on 29 June 2026, so both notes now record Parliament approval (16 June 2026), Council adoption (29 June 2026) and entry into force on the third day after the pending Official Journal publication. The operative conclusion is unchanged: the enacted dates remain binding until publication.

### Removed
- AI_Audit_Due_Diligence_Checklist_v4_7.md and AI_GRC_Master_Reference_v7_7.md. Superseded versions remain available in the commit history.

### Watch
- Official Journal publication of the digital omnibus regulation is the trigger for a substantive v4.9/v7.9 pass: cite the final article numbers for the Art. 50(2) watermarking grace period (December 2, 2026, for systems placed on the market before August 2, 2026), confirm that the other Art. 50 transparency obligations apply from August 2, 2026 as scheduled, and add the new Art. 5 prohibition on AI generation of non-consensual sexual or intimate content and CSAM (applying from December 2, 2026) to the checklist tier key and the Master Reference prohibited-practices coverage.

## v1.1.0 (2026-07-15)

First versioned release under the repository improvement program. The pre-existing repository state (first edition, June 2026, revised July 2026) is treated as implicit v1.0.0; manuscript history before this release remains in the commit log and is not retrofitted here.

### Added
- Version, date, license and CHANGELOG header in the README.
- Part of the ecosystem section linking the canonical ECOSYSTEM.md in the profile repository plus four nearest neighbors (grc-workbook, slow-ai-kitchen, ai-governance-for-boards, definition-of-done), placed at the end of the README before the closing line.
- LICENSE.md (CC BY-NC-SA 4.0) and a short README License section, formalizing the pre-existing "released free and for non-commercial use" statement.
- CHANGELOG.md (this file).

### Changed
- A note on accuracy: the currency claim is now day-dated. The EU AI Act status was re-checked on 15 July 2026 (Digital Omnibus endorsed by the Parliament 16 June 2026 and approved by the Council 29 June 2026, Official Journal publication pending; the original timeline remains binding until publication). The note also records the appendix-instrument policy: in-file currency notes are re-dated when each instrument next versions, so versioned documents are never edited in place.

### Unchanged
- The manuscript and both appendix instruments (AI Audit and Due Diligence Checklist v4.7, AI GRC Master Reference v7.7), byte for byte.

## v1.0.0 (implicit)

Pre-existing repository state: README, the full manuscript (Final_Liability_Rests_with_the_Human.md, first edition June 2026, revised July 2026) and two appendix instruments maintained as separate documents, Appendix I (AI Audit and Due Diligence Checklist, v4.7) and Appendix J (AI GRC Master Reference, v7.7, released May 2026).

Final Liability rests with the Human.
