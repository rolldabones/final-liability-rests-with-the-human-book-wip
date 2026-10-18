# Changelog

All notable changes to this repository are documented here. Versioning follows [Semantic Versioning](https://semver.org/). The README and this file version in lockstep; prior versions are superseded, never silently overwritten.

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
