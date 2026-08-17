# Changelog

All notable changes to this repository are documented here. Versioning follows [Semantic Versioning](https://semver.org/). The README and this file version in lockstep; prior versions are superseded, never silently overwritten.

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
