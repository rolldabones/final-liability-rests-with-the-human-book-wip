# AI GRC Master Reference File: Version 7.7

## Knowledge Base for AI-Assisted Governance, Risk Management and Compliance Drafting

*Released May 2026. Supersedes Version 7.6 (May 2026).*

## HOW TO USE THIS FILE

This file is a synthesized and expert-enhanced knowledge base for use as a reference corpus when drafting, reviewing or stress-testing AI governance, risk management and compliance documents. It integrates best-practice policy architecture with the principal requirements of the EU AI Act (Regulation 2024/1689), the NIST AI Risk Management Framework (AI RMF 1.0), ISO/IEC 42001:2023 and the IMDA Model AI Governance Framework for Agentic AI. It is organized by governance function. Source documents are not referenced; the content is presented as a unified framework.

When using this file in an AI drafting workflow, treat it as authoritative on structure and minimum content. Treat it as illustrative on specific thresholds, timelines and organizational titles, which must be adapted to the deploying organization’s context, jurisdiction and risk profile.

**Jurisdiction note.** This file is written to be jurisdiction-neutral at the principle level and EU-aligned at the regulatory minimum level, reflecting the practical reality that the EU AI Act sets the most demanding requirements currently in force among major AI regulatory frameworks. Organizations operating solely outside the EU should verify which provisions apply in their jurisdiction. Organizations operating across jurisdictions must meet the most stringent applicable requirements in each market.

## DOCTRINAL FRAME: SLOW AI, FINAL LIABILITY, INFORMED INTENT

The four-verb cadence in the next section reduces audit-grade discipline to a sequence the practitioner can hold under deployment pressure. The cadence does not arise from nowhere. It is the operational form of three doctrines that govern this file as a whole. Drafters who use this file without the doctrines will produce artifacts that look like governance and do not survive the questions a regulator, an auditor, an insurer, a litigant or an enterprise client will eventually ask. Drafters who hold the doctrines while applying the file will produce artifacts that bind.

**Slow AI.** Govern the process deliberately. Make the gears visible. Build the evidence architecture before the system operates. Treat every design choice as a governance decision, including the choice of speed. Slow AI is the discipline of deciding what is being built, what is being authorized and what is being measured before the deployment runs, on the assumption that the deployment will run faster than the governance can catch up afterward. Where this file specifies a control, a threshold, a record or a review, Slow AI is the doctrine that says the specification must exist before the activity it governs.

**Final Liability.** A named human carries the outcome regardless of how many systems, vendors and automated layers stand between the authorization and the consequence. The function of Final Liability is the binding of authority to consequence in a way that survives every form of distance the modern enterprise inserts between the two. The operational test is short. For each deployed AI system, can the organization name the human who has signed for it. If yes, the organization has governance. If no, the organization has a story it tells the regulator before the sentence finishes. The General Counsel function is structurally positioned to perform this binding, as set out in Part 3.

**Informed Intent.** An authorization given without the conditions that make it genuine is not authorization. It is paperwork. The doctrine names the conditions under which a human authorization of an AI deployment can be treated as substantive: the authorizing human had an accurate account of what the system does, of what it was being asked, of the alternatives and of the consequences, at a level the human could actually evaluate. Informed Intent is the doctrine that prevents the authorization chain from collapsing into a chain of formal signatures over inferences nobody specified.

The three doctrines are not redundant. Slow AI describes how the work must be done. Final Liability describes who carries the outcome. Informed Intent describes what makes an authorization in the chain real. Together they answer the three questions any defensible AI governance posture must answer: was the system specified, was the authorization genuine and is the named human able to defend the deployment when asked. The cadence below is the operational reduction of those answers; the Parts are the evidentiary content that the cadence requires.

### 4P: Principles, People, Policies, Systems (added v7.5)

4P is a reading lens for the AI governance literature, added to this DOCTRINAL FRAME as a navigation aid for practitioners reading the literature against the doctrine. It is not a fourth owned doctrine alongside Slow AI, Final Liability, Informed Intent and the GRC next™ primitives in the companion Master’s Appendix L. Drafters who use the file in conjunction with the synthesizing reference works added at Part 25 may find the four-element scaffold useful for organizing the harmonized recommendations and action-subject pairs against this file’s structure.

**Principles.** The harmonized framework objectives in Source \#7 (Governance, Safety, Security, Privacy, Detection and Response). The AI GRC triad (Slow AI, Final Liability, Informed Intent). Sectoral norms applicable in the organization’s operating jurisdictions. Principles state what the organization is trying to do.

**People.** The functional teams from CEO through DPO and CISO catalogued in Source \#7 and the Source \#8 functional-team mapping (19 C-suite roles). The named human in Final Liability. The accountable executive per deployment. People state who does the work and who signs for it.

**Policies.** The action-subject pairs synthesized in Source \#8 (232 distinct pairs derived from 814 raw pairs). The operating procedures the General Counsel signs for (Part 3.5.1). The control architecture in this file’s Parts 4 through 16. Policies state how the work is done and what evidence is generated.

**Systems.** The implementation levels from Source \#8 (Organization, Operations, Workforce, Infrastructure, Data, Model, System). The deployed AI itself, considered as governed object rather than tool. The Agent Registry and trust boundary specifications referenced in Part 9 (Agentic AI Governance) and Part 14.1 (AI System Inventory). Systems state what is in scope and where the controls operate.

**Caveat on promotion.** 4P is held as a reading lens. It is not promoted to fourth doctrine alongside Slow AI, Final Liability and Informed Intent. Promotion requires 4P doing load-bearing work in two or more chapter drafts of the companion Master. Until then, 4P serves the reader as a way of holding the literature alongside the doctrine, not as a doctrine in its own right.

## OPERATIONAL CADENCE: SPECIFY. STATE. RUN. DEFEND.

The four verbs reduce the audit-grade discipline encoded throughout this file to a sequence the practitioner can hold in mind under deployment pressure. Each verb maps to a foundation of audit-grade evidence; each foundation is the evidentiary content this file specifies, organized by Part.

**Specify.** Document the system before it operates. Requirements, acceptance thresholds, action scope, data access boundaries, escalation conditions and oversight mode, in the form Part 1 (Foundations), Part 4 (Risk Management) and Part 5 (TEVV) require. Without the specification, every subsequent record is unverifiable: the log has no governance standard to be measured against, and the question of whether the system operated as governed has no anchor. The specification must be explicit on both sides of the interaction: the system must be given an account of what it is being asked, and the human who authorizes the deployment must have an account of what s/he is asking. Where either side proceeds on inference, the record cannot demonstrate that what operated is what was authorized.

**State.** Make explicit the validity claim the deployment is making and the acceptance thresholds against which the claim will be measured. The specification commits to what the system is authorized to do; the validity claim states what the deployment context will use those outputs for, for which population, under which operational conditions. Part 4.2 (Risk Principles) and Part 5.4 (Acceptance Thresholds and Stop Conditions) carry the substantive content; Part 20 (FRIA) carries the rights-impact form of the same claim where applicable.

**Run.** Operate the system inside the evidence pipeline. Real-time action logs (Part 9 for agentic systems), exception reports (Part 8 and Part 11), change management records (Part 6 and Part 18), monitoring against acceptance thresholds (Part 5.4 and Part 16) and incident response (Part 8). The pipeline must produce the record that allows reconstruction without recourse to human memory and must be maintained in a form the system generating it cannot modify.

**Defend.** Be ready to defend the governance to the auditor (Part 15), the regulator (Part 21), the insurer, the enterprise client (Part 10 and Part 23) or the court when the question is asked. Defense is not advocacy. It is the documented evidence trail demonstrating that the prior three verbs were executed in the form the standard requires. An organization that cannot defend was not specifying, stating and running. It was performing those activities without producing the evidence that they occurred.

Drafters using this file should treat each Part as the evidentiary content the cadence requires, not as topics to navigate independently. The cadence is what the practitioner must hold in mind while building the artifacts the Parts specify.

## PART 0: QUICK START FOR DRAFTERS

This file is organized by governance function, but drafting is usually organized by actor. Before using any of the Parts that follow, complete the five-step actor analysis below. The same analysis is set out in greater detail as Appendix E; Part 0 reproduces its operative logic at the front of the file so that drafters can determine their position and obligation set before navigating the substantive Parts.

**Step 1: Did the organization develop the AI system (or have it developed) and place it on the market or put it into service under its own name or trademark?**

Yes → Organization is a **Provider** for this system. Full provider obligations apply. See Part 19.1 for the core EU AI Act high-risk provider obligation stack and Part 19.4 for GPAI provider obligations. Proceed to Step 5 to assess high-risk scope.

No → Proceed to Step 2.

**Step 2: Is the organization using an AI system developed by a third party under the organization’s own authority?**

Yes → Organization is a **Deployer** for this system. See Part 19.2 for deployer obligations under Article 26. Proceed to Step 3.

No → The organization may be outside the actor taxonomy (e.g., affected person). Assess whether the system falls within scope at all.

**Step 3: Has the organization made or does it intend to make a substantial modification to the AI system?**

“Substantial modification” per Article 25 means a material change to intended purpose, a change that would affect compliance with Chapter III requirements, or retraining that materially alters performance or risk profile. See Part 10.5 for the full substantial-modification analysis.

Yes, substantial modification made or intended → Organization becomes a **Provider** for the modified system. Return to Step 1 pathway.

No → Remain as **Deployer**. Proceed to Step 4.

**Step 4: Does the organization’s intended use fall within the system’s intended purpose as defined by the provider?**

Yes → Organization is using the system as a Deployer in scope of its intended purpose.

No → Organization is using the system outside its intended purpose. This is treated as a material modification. Assess whether it constitutes a substantial modification triggering provider obligations under Article 25.

**Step 5: Does the system fall within EU AI Act Annex III high-risk AI system categories?**

Yes → Both provider and deployer obligations specific to high-risk systems apply. Document the specific Annex III entry and associated obligations. Assign internal High Impact classification regardless of other classification factors. For deployers that are public bodies, private entities providing public services, or private entities operating in credit or insurance AI, a Fundamental Rights Impact Assessment under Article 27 is also required; see Part 20.

No → The system is not high-risk under Annex III. Assess whether any transparency or sector-specific obligations apply under applicable law, and assign the appropriate internal impact classification.

**Additional Quick Start check for GPAI.** If the organization develops a general-purpose AI model with significant generality or a GPAI model with systemic risk, see Part 19.4 for the provider obligations under EU AI Act Chapter V.

**Documentation requirement.** The Step 1 through Step 5 analysis must be documented for each system in the AI system inventory (Part 14.1) and reviewed whenever the system, its use, or the organization’s role changes materially.

## PART 1: FOUNDATIONS

### 1.1 Purpose and Scope of AI Governance

An AI governance program exists to protect the safety and trust of customers, employees and other stakeholders while ensuring that AI systems are developed, acquired, deployed and operated in ways that are safe, secure and lawful. Governance applies across the full lifecycle of every AI system the organization builds, buys or offers (including pilots, proofs of concept and general-purpose AI models integrated into products or services) and to all personnel who plan, develop, deploy or support those systems.

The governance framework operates alongside and reinforces existing corporate policies on data protection, information security, ethics and legal compliance. It does not replace those policies; it extends them into the specific risk domain of AI.

Low-risk or experimental AI activities may be granted time-limited exceptions where they do not pose significant material, legal, ethical or operational risks. Exception requests must follow a documented process and be approved by the appropriate authority before the activity commences.

### 1.2 Regulatory Framework Alignment

AI governance documents produced using this reference should be aligned to the following frameworks as applicable. Drafters should identify which frameworks are mandatory (by law or contract) and which are voluntary but material to the organization’s assurance posture.

**EU AI Act (Regulation 2024/1689).** The primary binding AI regulation for organizations placing AI systems on the EU market or using AI systems to affect persons in the EU. Establishes a risk-based classification of AI systems (unacceptable risk, high risk, limited transparency risk and minimal risk), mandatory requirements for high-risk AI systems, obligations for providers and deployers and a framework for general-purpose AI models. Its obligations enter application in phases, with prohibited practices and AI literacy obligations first, then general-purpose AI model obligations, then the full high-risk requirements. The phase-in schedule has been the subject of legislative adjustment and may be revised again, so this reference cites obligations by article rather than by date; drafters should verify the current application timeline against the primary source before relying on any specific date.

**NIST AI Risk Management Framework (AI RMF 1.0).** A voluntary US framework organized around four core functions: GOVERN, MAP, MEASURE and MANAGE. Provides a structured approach to AI risk identification, assessment and treatment. Its TEVV (Test, Evaluation, Validation and Verification) methodology is incorporated in Part 5 of this reference. Widely referenced in US federal procurement and increasingly in commercial AI assurance.

**ISO/IEC 42001:2023.** The international standard for AI management systems. Provides requirements for establishing, implementing, maintaining and continually improving an AI management system within an organization. Certifiable. Covers context of the organization, leadership, planning, support, operation, performance evaluation and improvement.

**IMDA Model AI Governance Framework for Agentic AI.** Guidance from Singapore’s Infocomm Media Development Authority specifically addressing governance of agentic AI systems (systems capable of autonomous multi-step action with limited human involvement). Incorporated in Part 9 of this reference.

**ISO/IEC 23894:2023.** Guidance on AI risk management, providing detailed methodology for identifying and treating AI-specific risks. Complements ISO/IEC 42001.

**UC Berkeley CLTC General-Purpose AI Risk-Management Standards Profile (Profile v1.2, March 2025).** A standards-style profile produced by the Center for Long-Term Cybersecurity that operationalizes the NIST AI RMF (and adjacent frameworks including ISO/IEC 42001 and the EU AI Act GPAI provider obligations) specifically for general-purpose AI models and general-purpose AI systems. Organized as a structured set of activities and documentation expectations across the GOVERN, MAP, MEASURE and MANAGE functions, with an emphasis on risk-management practices that scale to systemic-risk capabilities. Treated in this reference as the principal source for GPAI-specific risk-management content; see Part 24.

Drafters should note that additional jurisdiction-specific requirements may apply, including but not limited to the US Executive Order on AI (October 2023 and successor instruments), China’s Generative AI Regulations (2023) and sector-specific requirements in financial services, healthcare and critical infrastructure.

### 1.3 Core Definitions

**AI System.** A machine-based system designed to operate with varying levels of autonomy that, for explicit or implicit objectives, infers from the inputs it receives how to generate outputs such as predictions, recommendations, decisions or content that can influence real or virtual environments. An AI system typically combines models, data, interfaces and infrastructure. (Aligned to EU AI Act Article 3(1) and OECD AI Principles definition.)

**General-Purpose AI Model (GPAI Model).** An AI model that displays significant generality and is capable of competently performing a wide range of distinct tasks regardless of the way it is placed on the market and that can be integrated into a variety of downstream systems or applications. (EU AI Act Article 3(63).) A GPAI model with systemic risk is one whose high-impact capabilities present a significant risk of negative effects on public health, safety, security, fundamental rights or society. (EU AI Act Article 3(65).) Systemic risk is presumed when the cumulative computation used for training exceeds 10^25 floating point operations (FLOPs). (EU AI Act Article 51(2).) The Commission retains authority to designate additional models as presenting systemic risk and to revise this threshold by delegated act.

**AI Model.** The computational component within an AI system that has been trained to produce outputs from inputs, typically using machine learning or statistical techniques.

**Agentic AI System.** An AI system capable of autonomously executing multi-step tasks, making sequential decisions and taking actions across tools, software environments or real-world interfaces with limited human involvement between steps. Agentic systems may operate as single agents or as multi-agent networks in which AI systems interact with and direct other AI systems.

**AI Incident.** Any event where an AI system operates outside its intended parameters, produces harmful or incorrect outputs, impacts stakeholders in unintended ways or violates policy or legal requirements. Includes near-misses where harm did not materialize but the conditions for harm were present.

**Near-Miss.** An unplanned event involving an AI system that did not result in harm but had the potential to do so. Near-misses must be reported and treated as learning opportunities.

**Risk.** The combination of the likelihood of an event and its potential consequences that could adversely affect organizational objectives or cause harm to customers, employees or other stakeholders.

**Residual Risk.** The level of risk remaining after controls have been implemented and verified.

**Risk Appetite.** The level of risk the organization is willing to accept in pursuit of its strategic objectives.

**Risk Tolerance.** The acceptable thresholds around the organization’s risk appetite for specific categories of AI risk.

**Risk Register.** A centralized repository in which identified risks, their assessments, assigned owners and the status of mitigations are recorded and maintained.

**System Owner.** The designated individual accountable for the governance and compliance of a specific AI system throughout its lifecycle. In EU AI Act terminology, this role encompasses both provider and deployer obligations depending on the organization’s position in the AI supply chain.

**Mechanism Owner.** The designated individual accountable for the effective operation of a specific governance mechanism, such as the AI system inventory, incident register or risk assessment process.

**AI Governance Lead.** The senior leader responsible for coordinating AI governance implementation across the organization, maintaining the policy framework, facilitating governance committees, overseeing incident response and reporting to executive leadership on AI governance matters. Functionally equivalent to the AI Officer role emerging in some jurisdictions.

**Provider.** An organization that develops an AI system or GPAI model and places it on the market or puts it into service under its own name or trademark, whether for payment or free of charge. (EU AI Act Article 3(3).)

**Deployer.** An organization that uses an AI system under its own authority, except where used for personal non-professional activity. (EU AI Act Article 3(4).) Most organizations acquiring third-party AI systems are deployers under the EU AI Act and carry specific obligations.

**Affected Person.** Any natural person who is subject to a decision made or significantly influenced by an AI system, or who otherwise experiences the outputs of that system.

**Human-in-the-Loop (HITL).** An oversight mode in which a human is required to review and approve each individual AI output or decision before it takes effect.

**Human-on-the-Loop (HOTL).** An oversight mode in which AI operates autonomously but a human actively monitors outputs in real time and retains the authority and practical ability to intervene and override.

**Human-in-Command (HIC).** An oversight mode in which humans retain overall control of the AI system, including the ability to decide on deployment, modify objectives and shut down the system, but are not necessarily involved in individual output decisions.

**Slow AI.** Governance doctrine requiring that AI systems be specified, authorized, evidenced and resourced for review before deployment, in recognition that an agentic system in production cannot be governed retrospectively at the speed it operates. Slow AI is the discipline of building the governance architecture before the system runs. See DOCTRINAL FRAME and OPERATIONAL CADENCE.

**Final Liability.** Governance doctrine requiring that a named human, with documented authority, documented knowledge and documented operational capability to act, carries the outcome of every deployed AI system. Final Liability operates through the sign-for verb (a present-tense binding of the signer to the operational adequacy of what is being signed for) rather than through formal authorization alone. The operational test of Final Liability is the name-the-human test: for each deployed AI system, can the organization produce the named human with the supporting documentation. See DOCTRINAL FRAME and Part 3.5.1.

**Informed Intent.** Governance doctrine requiring that the human authorizing an AI deployment has the conditions necessary to make the authorization substantive: an accurate account of what the system does, what it is being asked, what alternatives exist and what consequences may follow, at a level the authorizing human can evaluate. Adapted by extension from the Informed Consent doctrine in medical ethics. Informed Intent is the doctrine that prevents the authorization chain from collapsing into a chain of formal signatures over inferences nobody specified. See DOCTRINAL FRAME and OPERATIONAL CADENCE Specify.

**Operational Catechism.** A diagnostic of governance strength composed of five questions to be answered, in writing, with named owners and current references, for any deployed AI system: (1) Who owns the model. (2) Who owns the use case. (3) Who can stop the system. (4) Where is the evidence. (5) What happens when the output is wrong, biased, unlawful or impossible to explain. Each question has an answer of the form a named person, a documented authority, a current evidence reference or a defined response. See Part 22.4.

**Sign-for verb.** A binding present-tense action distinct from the verb to authorize. Where authorization is permissive, signing for something commits the signer to a representation that the thing is what it appears to be, that it has been received or examined and that the signer accepts a defined consequence if it later turns out not to have been what they signed for. Final Liability operates through this verb. See Part 3.5.1.

**Name-the-Human Test.** The operational test of Final Liability: for each deployed AI system, identify the named human who has signed for the deployment, the named human’s documented authority to do so, the documented evidence that the named human satisfied Informed Intent and the documented operational capability to stop, redirect or correct the system. The test is binary at each system level. See Part 3.5.1 and Part 22.4.

**Trust.** Whether a person or group relies on the use of an AI system. Distinct from Trustworthiness and from Justified Trust. Trust without justification is reliance without evidence. (Adapted from UK Department for Science, Innovation and Technology, Introduction to AI Assurance, February 2024.) See Part 26.1.

**Trustworthiness.** Whether an AI system is deserving of trust based on its actual properties. A property of the system, not of the relationship between the system and the relying party. Trustworthiness without trust leads to lost opportunities; trust without trustworthiness leads to harm. (Adapted from UK DSIT, Introduction to AI Assurance, February 2024.) See Part 26.1.

**Justified Trust.** Reliance on an AI system based on reliable evidence. The conceptual goal of the AI assurance ecosystem. Justified Trust is what an Assurance Case is structured to support. (Adapted from UK DSIT, Introduction to AI Assurance, February 2024.) See Part 26.1.

**Assurance Case.** A structured argument, supported by a body of evidence, that a system satisfies specified claims about its properties or behaviors in a defined context. Originated in safety-critical engineering (aerospace, rail, defense, nuclear, medical devices); adapted for AI assurance through the Alan Turing Institute and the University of York Assuring Autonomy programs. The most widely adopted notation is the Goal Structuring Notation maintained by the Safety-Critical Systems Club Assurance Case Working Group. Core elements: goals, strategies, solutions, contexts, assumptions, justifications. The Assurance Case is the engineering grammar of Justified Trust. See Part 26.2.

**TEVV.** Test, Evaluation, Validation and Verification. The structured methodology for assessing AI system behavior, performance and compliance across the development lifecycle. (NIST AI RMF.)

### 1.4 Governing Principles, Commitments and Specifications

The following six principles govern how AI systems are selected, developed, deployed and operated. For each principle, standard commitments and evidence specifications are provided as drafting references. Organizations must adapt commitments to their specific context, adding precision on thresholds, timeframes and accountable roles.

#### Principle 1: Trustworthiness and Reliability

AI systems must be dependable in their intended contexts across the full range of conditions they will encounter in deployment. Performance requirements are defined for each system before deployment, with acceptance thresholds proportionate to risk. Systems are monitored throughout operation to detect performance degradation, distributional drift or unexpected behavior. Material changes to models, data inputs or operating configuration are subject to change management and must meet established thresholds before proceeding.

**Standard Commitments:**

- Define performance requirements, acceptance thresholds and failure mode documentation before deployment, scaled to the system’s impact classification.

- Conduct TEVV activities at each lifecycle stage appropriate to system classification.

- Monitor deployed systems for degradation, drift and out-of-distribution outputs.

- Require re-validation following any material change to a model, its data inputs or its operating environment.

- Maintain rollback capability for all deployed systems, with rollback procedures documented and tested.

- Investigate AI tools producing inconsistent or questionable results before continuing to rely on their outputs.

**Evidence and Measures:**

- Evidence: Performance benchmarks; validation and test reports; change logs; monitoring dashboards; rollback procedure documentation.

- Measures: Percentage of systems with documented performance thresholds; mean time to detect performance failures; mean time to remediate; rollback success rate.

#### Principle 2: Fairness and Bias Prevention

AI systems must treat individuals and groups equitably and avoid unjustified disparate impacts. Systems are assessed for bias and distributional impacts before deployment and periodically thereafter. Testing covers representative data and scenarios, including edge cases and protected characteristics where relevant. When unacceptable disparities are identified, adjustments are made to models, data or usage constraints, with trade-offs and remediation documented.

**Standard Commitments:**

- Measure system performance across demographic groups before deployment and remediate material disparities within agreed thresholds and timeframes.

- Assess AI systems for potential bias before acquisition or deployment, particularly where outputs affect people’s rights, opportunities or access to services.

- Apply intersectional analysis where single-axis demographic analysis may miss compounded disparate impacts.

- Adjust or discontinue use of systems where unacceptable disparate impacts cannot be adequately remediated.

- Document trade-offs where fairness across different demographic dimensions cannot be simultaneously optimized.

**Evidence and Measures:**

- Evidence: Subgroup performance reports; bias assessments; remediation plans and outcome records; trade-off documentation.

- Measures: Maximum acceptable performance gap between demographic groups; remediation timeframe compliance rate; percentage of systems with documented fairness testing methodology.

**Fairness Taxonomy and Selection.** Fairness is not a single test. For each Medium and High Impact system, the organization must document which fairness concepts are relevant to the use case and why. At minimum, the assessment should consider: group fairness, meaning comparable treatment or outcomes across relevant groups; individual fairness, meaning similar treatment of similarly situated persons; counterfactual fairness, meaning materially similar outcomes when protected characteristics are altered in a controlled hypothetical; and procedural fairness, meaning that the decision process is understandable, reviewable and contestable. Where these concepts conflict in practice, the trade-offs, rationale and decision owner must be documented and approved at the level appropriate to system impact.

**The Fairness Impossibility Result.** Drafters and reviewers must understand that several formal fairness criteria cannot simultaneously be satisfied except in degenerate cases. The formal result (Chouldechova 2017 for recidivism; Kleinberg, Mullainathan and Raghavan 2017 for the general case) is that calibration within groups, balance for the positive class, and balance for the negative class cannot all hold at once unless base rates are equal across groups or the predictor is perfect. This is a mathematical constraint, not a limitation of current technology. In consequence, any High Impact fairness-method selection requires an explicit choice among competing criteria, a documented rationale for the choice and an acknowledgment that the non-selected criteria will measurably fail. Drafters should resist governance language that implies the organization will satisfy all fairness tests simultaneously; such language is not deliverable and invites challenge when inevitable trade-offs become visible. The selected criterion and the accepted trade-off must be approved at the level appropriate to system impact and recorded in the governance documentation for the system.

**Additional Standard Commitments.** Items marked \[M\] are mandatory for EU AI Act high-risk providers under Articles 10 and 15 and for deployers bringing systems within Article 27 scope. Items marked \[R\] are recommended as best practice and become functionally mandatory where the organization operates at Maturity Level 4 or above (see Part 22).

- \[M\] Require systems with material discrimination risk to undergo an explicit fairness-method selection process before deployment.

- \[M\] Treat explainability, reviewability and contestability as fairness controls for consequential systems, not merely transparency controls.

- \[R\] Consider independent fairness review for systems with material discrimination risk even where external validation is not otherwise mandatory.

- \[M\] Permit synthetic data as a bias-mitigation measure only where its provenance, representativeness, limitations and validation results are documented.

#### Principle 3: Transparency and Explainability

People affected by AI decisions should be able to understand how those decisions are influenced, appropriate to context and risk. Explanations are provided to affected parties covering system purpose, factors influencing outputs and limitations. Documentation and audit trails are maintained on data sources, model versions, configuration and governance decisions. The use of AI is disclosed where it is material to users or stakeholders.

**Standard Commitments:**

- Disclose when people are interacting with an AI system or when AI has materially influenced a decision affecting them.

- Provide clear explanations of key factors influencing consequential decisions at a level appropriate to the affected person’s context and needs.

- Produce and maintain model cards or equivalent system documentation for all AI systems, covering purpose, capabilities, limitations, training data characteristics and known failure modes.

- Ensure personnel using AI tools can explain at a general level what the tool does and where it may produce unreliable outputs.

- Maintain audit trails sufficient to reconstruct the basis for any AI-influenced decision subject to challenge or regulatory inquiry.

**Evidence and Measures:**

- Evidence: Model cards; user interface AI disclosures; explanation logs; audit trail records; system documentation.

- Measures: Percentage of systems with current documentation; explanation coverage rate for consequential decisions; percentage of challenged decisions for which the basis can be reconstructed.

#### Principle 4: Security and Privacy Protection

Security and privacy are embedded by design and sustained throughout the system lifecycle. Privacy-by-design practices are applied, including data minimization, purpose limitation and appropriate retention. Security controls are implemented commensurate with system risk. Security and privacy assessments are conducted before deployment and repeated upon material change. Models and training data are treated as critical assets requiring protection against both conventional IT threats and AI-specific attacks including data poisoning, model extraction, adversarial inputs and prompt injection.

**Standard Commitments:**

- Collect only the minimum data necessary for stated purposes and prohibit repurposing personal data without explicit lawful basis.

- Apply integrity verification to models and training data before production deployment.

- Monitor for signs of adversarial attacks and model tampering on an ongoing basis.

- Prohibit entry of personal or confidential data into AI tools not approved for that data category.

- Review security and privacy protections when vendors update their systems or terms of service.

- Conduct threat modeling specific to AI risks, including model extraction, inference attacks and prompt injection, in addition to conventional threat modeling.

**Evidence and Measures:**

- Evidence: Data Protection Impact Assessments; data inventory with lawful basis documentation; retention schedules; security assessment reports; threat models; integrity verification logs.

- Measures: DPIA completion rate for qualifying systems; retention policy compliance rate; percentage of production models with verified integrity; mean time to detect adversarial activity.

#### Principle 5: Accountability and Oversight

Clear accountability exists for AI systems, with human oversight appropriate to risk. Every AI system has a designated owner accountable for its compliance. High-risk systems require explicit approval before deployment and active oversight during operation. Escalation paths exist for concerns about system behavior and remedies include pause, rollback or constrained operation where warranted. Employees remain accountable for work they produce with AI assistance. Accountability cannot be delegated to vendors, automated systems or the AI itself.

**Standard Commitments:**

- Assign a named owner to every AI system and maintain a register of system ownership current at all times.

- Assign oversight modes (HITL, HOTL or HIC) explicitly for each system, documented and proportionate to the system’s impact classification.

- Prohibit fully automated consequential decisions in high-stakes domains including employment, financial standing, access to services and safety without qualified human review and approval.

- Ensure qualified reviewers have the information, authority, time and practical ability to intervene meaningfully before decisions take effect.

- Maintain documented intervention and override procedures for High Impact systems, tested at least annually.

- Maintain an appeals or redress mechanism for affected persons with defined response timeframes.

**Evidence and Measures:**

- Evidence: Ownership register; oversight mode documentation; reviewer training records; override logs; appeals process documentation; redress procedure records.

- Measures: Percentage of high-stakes decisions with documented human review; override rate and rationale; mean time to resolve appeals against SLA; percentage of High Impact systems with tested intervention procedures.

#### Principle 6: Societal Impact

The organization considers broader effects of AI on society and acts to amplify benefits while reducing harm. Anticipated societal impacts are evaluated before deployment of high-risk systems, including effects on safety, dignity and economic wellbeing. Channels exist for stakeholders to provide feedback and this input informs system requirements and operation. The organization engages constructively with regulators, standards bodies and industry peers on safe AI practices.

**Standard Commitments:**

- Evaluate whether AI use could cause harm to individuals, communities or society beyond its immediate business purpose, particularly for High Impact systems.

- Assess labor market and economic displacement effects where systems automate functions previously performed by human workers.

- Assess whether affected persons may become materially dependent on AI-mediated channels for access, redress, recommendations or services, and whether that dependency changes their vulnerability, expectations or practical ability to challenge outcomes.

- Maintain channels for stakeholder feedback and incorporate that input into system requirements and governance decisions.

- Engage constructively with regulatory developments and evolving standards around responsible AI use.

- Report significant societal harms to appropriate authorities in line with applicable regulatory requirements.

**Evidence and Measures:**

- Evidence: Societal impact assessments; stakeholder consultation records; regulatory engagement logs; labor impact assessments where applicable.

- Measures: Percentage of High Impact systems with documented societal impact evaluation; stakeholder feedback response rate; percentage of required regulatory disclosures completed on time.

## PART 2: GOVERNANCE STRUCTURE

### 2.1 Executive Oversight

The AI Governance Committee provides strategic direction for AI across the organization. It approves major AI initiatives and High Impact system deployments, sets risk thresholds, approves policy changes, reviews significant incidents and ensures alignment with organizational values and strategic objectives. It reports to the Board (or Board Risk Committee) on AI governance matters. The Committee escalates to executive leadership as appropriate and is typically chaired by the Chief Technology Officer or a designated delegate.

The Committee reviews and approves the organization’s risk appetite and tolerance levels at least annually or in response to major organizational or regulatory changes. It is responsible for ensuring the organization meets its obligations as a provider and/or deployer under applicable AI regulations, including the EU AI Act where relevant.

### 2.2 Operational Management

The AI Operational Committee oversees day-to-day governance activities, monitors system performance and manages operational risks within its delegated authority. Issues exceeding that authority are escalated to the AI Governance Committee. The Operational Committee maintains the AI Risk Register, reviews risk assessments and impact classifications for Medium and High Impact systems, publishes guidance on risk identification and control selection and reports significant findings and control weaknesses upward. Committee composition and meeting cadence are defined in the Committee’s terms of reference.

### 2.3 Decision Authority Tiers

AI governance operates through a three-tier decision framework.

**Tier 1: Technical Teams.** Routine operational decisions within documented parameters, including day-to-day monitoring, lifecycle management and incident first response. Technical teams must escalate risks and issues that exceed defined thresholds.

**Tier 2: AI Operational Committee.** New systems and significant changes to existing systems, including changes affecting performance, compliance or user experience. The Committee confirms alignment with principles, commitments and risk tolerances before approval, escalating as necessary.

**Tier 3: AI Governance Committee.** Strategic decisions including new High Impact deployments, policy changes, risk threshold definitions, review of significant incidents, approval for systems classified as High Impact and reporting to the Board. Decisions on risk acceptance for novel AI use cases that fall outside established parameters require Tier 3 approval.

### 2.4 Escalation

Clear escalation paths connect each tier. Any personnel may escalate concerns directly to the Governance Committee where they believe normal channels are inadequate or where the matter involves potential serious harm. Escalation triggers include: a system’s impact rating being raised; a significant incident occurring; a legal breach being suspected; regulator contact being initiated; or any matter involving material harm to customers, employees or third parties. The AI Governance Lead must be notified promptly. The CTO (or equivalent executive) must be notified immediately for matters involving legal exposure or material harm. Where regulatory notification obligations exist, Legal and Compliance must be notified simultaneously.

### 2.5 Three Lines of Defense

AI governance should operate within a three lines of defense model.

**First Line.** Business units, System Owners and technical teams that develop, deploy and operate AI systems. Responsible for identifying and managing AI risks in their day-to-day activities and implementing controls.

**Second Line.** The AI Governance Lead, AI Operational Committee and specialist functions (Legal, Compliance, Data Protection, Information Security). Responsible for setting the governance framework, providing oversight of the first line and monitoring compliance.

**Third Line.** Internal Audit. Responsible for providing independent assurance to the AI Governance Committee and the Board on the effectiveness of governance, risk management and control in the first and second lines.

## PART 3: ROLES AND RESPONSIBILITIES

### 3.1 Board and Executive Leadership

The Board (or equivalent governing body) holds ultimate accountability for the organization’s AI governance posture. It approves the AI Governance Charter, receives regular reporting from the AI Governance Committee and satisfies itself that management has implemented adequate governance, risk management and compliance arrangements for AI. The Board should receive at minimum annual reporting on AI risk posture and significant incidents and immediate notification of any matter that could constitute a material regulatory breach.

The CTO (or designated AI executive) provides executive sponsorship for AI governance, chairs the AI Governance Committee and approves policy changes. Accountable for alignment between AI governance and corporate strategy and for ensuring the organization meets its regulatory obligations as a provider and deployer of AI systems.

### 3.2 AI Governance Lead

**Purpose.** The AI Governance Lead is the operational architect and orchestrator of the organization’s AI governance framework. This role transforms governance principles into operational practice by coordinating cross-functional teams, building and maintaining governance infrastructure and driving continuous improvement in AI risk management at the speed and scale of modern AI deployment.

**Core Responsibilities.**

*Governance Operations and Infrastructure (approximately 40% of role).* Design and maintain AI governance processes including intake procedures, continuous risk assessment and review workflows. Build and deploy governance tools such as model monitoring dashboards, compliance checking systems and fairness testing pipelines. Coordinate cross-functional AI governance committees and ensure decisions are recorded in trackable systems. Maintain governance infrastructure that scales with AI deployment velocity. Document all governance decisions in searchable, auditable formats for regulatory compliance and organizational learning.

*Stakeholder Coordination (approximately 25%).* Facilitate collaboration between technical teams, legal, compliance, risk, audit and business units. Manage relationships with external advisors, auditors and regulatory bodies. Build governance awareness and capability across the organization through training and self-service tools. Maintain reporting mechanisms that keep stakeholders informed.

*Risk and Compliance Management (approximately 20%).* Maintain the AI system inventory and risk register. Deploy continuous compliance monitoring against internal policies and external regulations. Coordinate AI audits, algorithmic impact assessments and fairness testing. Identify systemic risks and patterns across the AI portfolio. Support incident response through alerting and escalation processes.

*Strategic Development (approximately 15%).* Evolve governance frameworks as the organization’s AI portfolio and the regulatory environment develop. Contribute to AI strategy to ensure governance can match development velocity. Advise leadership on governance technology and regulatory developments.

**Essential Capabilities.** Technical understanding of AI/ML concepts, model development lifecycle and common failure modes. Ability to engage credibly with data scientists and engineers on technical risks. Knowledge of applicable regulations and standards including the EU AI Act, NIST AI RMF and ISO/IEC 42001. Experience with risk management frameworks and their operationalization. Strong process design skills focused on scalability. Outstanding facilitation and stakeholder management. Clear communication for technical and non-technical audiences. Change management capability.

**Preferred Qualifications.** Five or more years in governance, risk, compliance or legal roles. Experience with AI/ML projects and MLOps practices. Knowledge of AI ethics and responsible AI frameworks. Experience with GRC platforms. Relevant certifications such as CISA, CRISC or AIGP. Advanced degree in a relevant field.

**Success Metrics.** Percentage of AI projects with documented governance checkpoints at each lifecycle stage. Risk detection and mitigation velocity. Continuous compliance score across the AI portfolio. Mean time to detect and respond to AI risks. Regulatory audit pass rate. Governance cycle time year-over-year.

**Reporting.** Typically reports to the Chief Risk Officer, Chief Data Officer or Chief Technology Officer, with dotted-line relationships to Legal, Compliance and Internal Audit. Requires sufficient seniority to influence executive decisions and coordinate across departments.

### 3.3 System Owners

Accountable for the compliance of their assigned AI systems throughout the lifecycle. System Owners maintain system documentation, ensure monitoring is in place and report issues through appropriate channels. They serve as the primary contact for audits and queries related to their systems, identify and document risks during planning and operation, propose impact classifications and implement required controls. Where systems span multiple business areas, the System Owner coordinates with other affected users. System Owners are responsible for ensuring that deployer obligations under applicable regulations (including the EU AI Act Articles 26–27 where relevant) are met for their assigned systems.

### 3.4 Mechanism Owners

Accountable for the effective operation of assigned governance mechanisms such as the AI system inventory, incident register or risk assessment process. Mechanism Owners ensure the mechanism meets its intended purpose, maintain supporting documentation and templates, implement and oversee embedded controls, monitor mechanism performance and recommend improvements based on operational experience. The AI Governance Lead assigns mechanism ownership and reviews mechanism effectiveness.

### 3.5 Legal and Compliance

Advises on legal and regulatory requirements affecting AI systems. Evaluates third-party AI procurement for legal risk and must be consulted before finalizing any AI vendor contracts. Monitors applicable AI regulations and advises the Governance Committee on regulatory developments. Provides regular reporting on compliance status, regulatory changes and remediation of identified gaps. Reviews contracts for Medium and High Impact systems. Manages regulatory notification obligations where AI incidents trigger mandatory disclosure requirements.

### 3.5.1 General Counsel

**Purpose.** The General Counsel function is the binding function for AI governance. It connects authority, risk, evidence and consequence into a single operational signature for each deployed AI system. The General Counsel does not displace the AI Governance Lead, the System Owners, the risk management function, the compliance function or the technical functions; it integrates their outputs into the form a regulator, an auditor, a litigant, an insurer or an enterprise client will eventually demand. Where this file refers elsewhere to Legal and Compliance (Part 3.5), the present subsection sets out the structural role that distinguishes the General Counsel function from the broader Legal and Compliance contribution.

**The four-things-connected claim.** Four elements must be bound together to produce governance that can be defended later. Authority is the question of who is permitted to act and what they are permitted to act on. Risk is the question of what can go wrong, with what likelihood and with what severity. Evidence is the question of what can be proved later. Consequence is the question of what happens to the entity, the directors and officers, the operating units and the named humans when the action produces a result that is challenged. Many functions own pieces of these elements. Only the General Counsel function structurally connects all four. The connection is what produces governance; the inputs alone do not.

**The sign-for verb.** The General Counsel function is the part of the enterprise where the sign-for verb is structurally available. Operating units sign for their decisions but not for the governance architecture around them. Risk management functions sign for the registers but not for the operational controls. Compliance functions sign for the filings but not for whether the filings are connected to operational reality. Internal Audit signs for the audit but operates retrospectively. The General Counsel signs for the deployment in the operational sense: for the architecture being in place, for the evidence pipeline existing, for the authority to stop the system being assigned and for the documented record being producible if the deployment is later questioned. This is core GC work and not delegable in form, although the underlying inputs are produced by other functions.

**AI widens what the GC must sign for.** The legal exposures, regulatory requirements, contractual obligations and evidentiary demands associated with deployed AI systems sit within the General Counsel’s domain regardless of whether the function is staffed and structured to absorb them. Each traditional GC sign-for surface (corporate authority, contracts, regulatory filings, litigation strategy, applicable-law compliance, privacy, intellectual property, ethics and conduct, board governance, crisis response) now has an AI dimension. The choice the GC has is whether to engage with the expanded surface deliberately at the front end, building the governance architecture and the sign-for capability before deployment, or retrospectively, after a material incident has surfaced the gap. The first approach is governance. The second is litigation defense.

**The name-the-human test.** The operational test of whether Final Liability is being practiced or merely cited is short. For each deployed AI system, identify the named human who has signed for it, with documented authority, documented evidence of Informed Intent and documented operational capability to act. If the name exists with the supporting documentation, the doctrine is being practiced. If it does not, the organization has a story rather than governance. The General Counsel is responsible for ensuring that the name-the-human test is satisfied for every deployed AI system in scope and that the documentation supporting each name is current. The test is administered system by system; it is not a portfolio-level metric.

**Why the General Counsel function structurally.** Alternatives have been proposed for who should run AI governance, including a Chief AI Officer, a Chief Risk Officer, a Chief Information Security Officer, a Chief Privacy Officer, an AI ethics committee, an external advisory board and a cross-functional steering group. Each is necessary for its specific contribution. None substitutes for the binding work that connects authority, risk, evidence and consequence. The General Counsel function combines four conditions that the others do not all have together: standing to bind the entity through the legal authority of the role, independence to refuse a deployment supported by the structural reporting line to the board on legal matters, perspective to anticipate the questions that will eventually be asked and operational reach derived from the function’s involvement in contracts, authorizations, filings, litigation and regulatory matters.

**Reporting and authority.** The General Counsel function should hold pre-delegated authority to halt the deployment of any AI system that cannot satisfy the operational catechism (Part 22.4) for that system, with the obligation to escalate the halt to the AI Governance Committee and the Board (or Board Risk Committee) within a defined period. The authority is structural rather than hostile; it exists so that the function can perform its assigned binding work. Where the General Counsel function does not hold the halt authority, the binding work cannot be performed at the speed of agentic deployment, and the four-things-connected claim cannot be made operational.

**Outputs of the function.** The General Counsel function running AI governance produces a small number of recurring artifacts. The architecture itself: the documented design that specifies which actions require which authorities, which evidence each authorization must produce, which controls operate at each gate and which conditions trigger which escalations. The live record: the documented sequence of where the architecture has been tested and how it performed. The change log: the documented sequence of architectural changes with reasons and propagation verification. The readiness for the asking: the standing capability to produce the architecture, the live record and the change log when a regulator, an auditor, a litigant, an enterprise client, an investor or a board member asks. These four outputs distinguish the General Counsel function that runs AI governance from the General Counsel function that performs legal work alongside an AI governance program someone else is running.

### 3.6 Data Protection Officer

Oversees data privacy controls for AI systems and ensures compliance with applicable data protection regulations, including GDPR Article 22 obligations where AI is involved in automated decision-making affecting natural persons. Must be consulted on Data Protection Impact Assessments for AI systems processing personal data at scale or presenting elevated privacy risk. Coordinates with the Operational Committee on data handling matters.

### 3.7 Internal Audit

Conducts independent audits of AI governance compliance and system behavior across risk management, lifecycle controls and operational procedures. Reports findings to the Governance Committee. Audit findings must be documented and corrective actions tracked until resolved and verified. Internal Audit operates independently of the first and second lines and has unfettered access to systems, records and personnel required for its function.

### 3.8 Technical Staff

Engineers, data scientists and others involved in AI development are responsible for building systems in accordance with governance policy and maintaining appropriate documentation. Technical staff collaborate with System Owners to ensure audit readiness, support explainability requirements and implement TEVV activities. They are responsible for flagging governance concerns they identify in the course of technical work, without waiting for formal escalation points.

### 3.9 All Employees

Everyone using AI tools must comply with the AI Use Policy, complete required training, review and validate AI outputs before use and report incidents and concerns promptly. Employees remain accountable for work they produce with AI assistance. Delegating a task to an AI system does not transfer accountability for the outcome. Managers are responsible for ensuring their teams understand and follow applicable policies and for verifying that appropriate reviews have been completed before approving new AI tools or projects.

Verification of AI-assisted work must be assigned to a person with sufficient subject matter expertise, authority and time to perform a meaningful review. Verification accountability may not be assigned nominally to individuals who lack the competence or practical ability to challenge the output.

The organization must maintain visible channels through which personnel can raise concerns about AI bias, misuse, unreliable outputs or policy breaches without waiting for a formal incident. Managers must know how to route concerns, preserve evidence and trigger escalation where appropriate.

## PART 4: RISK MANAGEMENT

### 4.1 Risk Appetite and Tolerance

The organization maintains a **moderate** overall risk appetite for AI-related initiatives, meaning it is open to adopting AI solutions that offer substantial operational or strategic benefits, provided associated risks are clearly identified, assessed and effectively controlled.

Risk tolerance by category:

**Regulatory and Legal Compliance: Minimal Tolerance.** The organization will not engage in AI activities that carry a high risk of violating applicable laws or regulations in any operating jurisdiction.

**Data Privacy and Security: Low Tolerance.** Use of personal or sensitive data in AI systems must follow stringent privacy and security controls. Systems processing special category data require heightened scrutiny and explicit lawful basis.

**Ethical and Reputational Impact: Low to Moderate Tolerance.** Systems that could result in significant ethical harm or reputational damage must undergo thorough review and require Operational Committee approval.

**Operational Disruption: Moderate Tolerance.** Reasonable experimentation is permitted, but projects presenting a high risk of severe operational disruption are subject to heightened controls and contingency planning requirements.

**Unanticipated Costs: Moderate to High Tolerance.** The organization accepts a reasonable level of unforeseen costs associated with AI experimentation, provided such costs are pre-approved within defined budgets and do not create material financial exposure.

### 4.2 System Impact Classification

All AI systems must be classified according to their potential impact before deployment. Classification determines the level of governance oversight, documentation and control required throughout the system lifecycle. Classification must be reviewed whenever the system’s scope, use or operating environment changes materially. The System Owner proposes the classification; the AI Governance Lead confirms it.

**Classification Factors.** The nature and reversibility of decisions the system makes or influences. The degree and mode of human oversight. The number and vulnerability of people affected. The sensitivity of data processed. Applicable regulatory requirements including EU AI Act risk category. Whether the system operates autonomously. The speed at which outputs can cause harm if the system malfunctions.

**Regulatory Overlay.** The organization’s internal classification must be reconciled with any mandatory classification under applicable law. EU AI Act Annex III designates specific AI system types as high-risk regardless of internal classification. An AI system that falls within an EU AI Act Annex III category must receive at minimum a High Impact classification under the internal framework, even if internal factors alone would suggest otherwise. Prohibited AI practices under EU AI Act Article 5 must never be deployed, regardless of any internal classification or exception process.

#### Low Impact

Systems that provide advisory outputs with human decision-making, process non-sensitive data, affect limited populations and present minimal potential for harm. Examples include drafting tools, document summarization and internal productivity automation. These systems require registration in the AI inventory and responsible use by designated users.

**Minimum Governance Requirements:** Registration in the AI inventory. System Owner designation. Responsible use acknowledgment. Basic documentation of purpose and data inputs.

#### Medium Impact

Systems that influence significant decisions, process personal or sensitive data, operate at meaningful scale or present moderate potential for harm if they malfunction or produce biased outputs. Examples include customer service AI systems, HR analytics tools and operational decision-support systems. These systems require formal risk assessment, documented controls, validation prior to deployment and AI Governance Lead approval.

**Minimum Governance Requirements:** All Low Impact requirements. Documented risk assessment. Stakeholder impact assessment. Bias and fairness testing. Security and privacy assessment. AI Governance Lead approval. Operational Committee review. Ongoing monitoring with defined thresholds. Incident reporting integrated with the organizational incident register.

#### High Impact

Systems that make or substantially determine consequential decisions affecting rights, safety, financial standing or access to essential services. This includes systems operating autonomously in high-stakes contexts, processing highly sensitive data at scale, falling within regulatory high-risk designation or presenting significant potential for serious harm. Examples include recruitment screening, credit decisioning, healthcare diagnostics, law enforcement applications and autonomous agent systems with real-world action authority.

**Minimum Governance Requirements:** All Medium Impact requirements. AI Governance Committee approval. Independent external validation before deployment. Comprehensive risk treatment plan. Documented human oversight arrangements with explicit oversight mode assignment (HITL, HOTL or HIC). Tested intervention and override procedures. Societal impact assessment. Post-deployment review at defined intervals. Periodic external audit. For EU AI Act high-risk systems, full compliance with Chapter III Section 2 requirements including conformity assessment, technical documentation (Annex IV), logging and record-keeping, transparency and instructions for use, human oversight measures and accuracy, robustness and cybersecurity requirements.

#### Prohibited Uses

The organization will not deploy AI that violates applicable laws, makes fully automated consequential decisions without human oversight, breaches data protection requirements or presents unacceptable risks to individuals or the organization. The following categories are absolutely prohibited regardless of any exception process, mirroring EU AI Act Article 5 prohibited practices:

- AI systems using subliminal, manipulative or deceptive techniques that impair informed decision-making in ways that could cause harm.

- AI systems that exploit vulnerabilities of specific groups based on age, disability or social or economic situation.

- Social scoring systems that evaluate or classify natural persons based on social behavior or inferred personal characteristics in ways that cause unjustified or disproportionate harm.

- Real-time remote biometric identification systems in publicly accessible spaces for law enforcement purposes, except in the limited circumstances permitted by applicable law.

- AI systems that infer emotions of natural persons in the workplace or educational institutions, except for medical or safety reasons.

- AI systems that create or expand facial recognition databases through untargeted scraping.

- AI systems intended to be used for individual criminal risk assessment based solely on profiling.

Uncertain cases must be referred to the AI Governance Lead and Legal before proceeding.

### 4.3 System Impact Assessment: Concept and Ideation Stage

Before moving beyond concept stage, every proposed AI system must complete a structured impact assessment. The assessment serves two purposes: determining the appropriate impact classification and identifying specific issues requiring attention before further investment is made.

**Threshold Questions: Decision Scope:**

- Influences decisions about employment, education, housing or healthcare → HIGH

- Makes or influences decisions about financial services or legal matters → HIGH

- Falls within EU AI Act Annex III categories → HIGH (mandatory)

- Affects access to non-critical services or benefits → MEDIUM

- Provides recommendations or optimizations only → LOW to MEDIUM

**Threshold Questions: Consequence Severity:**

- Failure could cause physical harm or safety risks → HIGH

- Errors could cause significant financial loss or legal liability → HIGH

- Decisions are irreversible or difficult to appeal → escalate toward HIGH

- Mistakes cause inconvenience but are easily reversible → LOW

- Problems affect many people but have appeal or correction processes → MEDIUM

**Principle-Based Assessment Prompts:**

*Fairness.* Will this system allocate opportunities and resources fairly across all user groups? Have potential sources of unfair bias in data or algorithms been identified? Will the system perform equitably across different demographic groups, including at the intersection of multiple characteristics? Are all affected communities represented in the design and testing process? Red flag: Could this system systematically disadvantage any identifiable group? If yes, MEDIUM to HIGH depending on severity.

*Reliability and Safety.* Will the system work consistently across different conditions and contexts? What safeguards prevent it from causing harm? How does it behave when it encounters out-of-distribution inputs or unexpected situations? Has it been tested under adversarial or edge-case conditions? Red flag: What is the worst-case scenario if the system fails or is compromised? Catastrophic or irreversible → HIGH. Significant but manageable → MEDIUM. Minor inconvenience → LOW.

*Privacy and Security.* How is personal information protected? Do users understand and consent to how their data is used? What measures prevent unauthorized access or misuse? Is data collection limited to what is actually necessary? Does the system create risks of re-identification from outputs? Red flag: Could this system expose sensitive personal information or be vulnerable to AI-specific attacks? If yes, raise impact level by at least one tier.

*Inclusiveness.* Can people of all abilities use this system effectively? Does the system work appropriately across different cultural and linguistic contexts? Does it enhance human capabilities rather than exclude particular groups? Red flag: Could this system exclude or disadvantage people with disabilities or from different backgrounds? If yes, MEDIUM to HIGH as an equity concern.

*Transparency.* Will users know they are interacting with an AI system? Can you explain how and why the system makes specific decisions in terms understandable to affected persons? Are users clear about what the system can and cannot do? Is there documentation sufficient for regulatory inquiry? Red flag: If the system rejected someone’s application, could you explain why in terms the person could understand and act on? If no and the decision is high-stakes → HIGH. If no and the decision is moderate-stakes → MEDIUM.

*Accountability.* Who is specifically responsible when this system makes errors or causes harm? Is there a clear process for overseeing the system’s development and operation? Can humans meaningfully review and override outputs when needed? Can the system’s decisions be tracked and explained over time? Red flag: If this system caused harm, could you identify who is responsible, what went wrong and how to fix it? If no, raise impact level because ungoverned systems are inherently higher risk.

**Sensitive Uses Test.** If the proposed system involves any of the following, escalation to Legal for review is required before any further project activities commence: human rights or fundamental freedoms; high-stakes decisions in healthcare, criminal justice or employment; vulnerable populations including children, elderly persons or people with disabilities; potential for significant harm in safety-critical or financial decision contexts; or any use case that may fall within EU AI Act Annex III or Article 5.

### 4.4 Risk Identification

AI risks must be identified systematically, beginning at the ideation or proposal stage and continuing through development, deployment and operations. Teams are expected to look beyond generic checklists to uncover AI-specific risk types including technical, ethical, operational, strategic and supply chain risks.

**Risk Taxonomy.** AI risks should be categorized across the following dimensions to ensure comprehensive coverage:

- *Accuracy and performance risks:* Model error, drift, distributional shift, hallucination and brittleness under edge conditions.

- *Fairness and bias risks:* Historical bias in training data, proxy discrimination, disparate impact across demographic groups and feedback loop amplification.

- *Privacy and data risks:* Training data exposure, inference attacks, membership inference, re-identification from outputs and unauthorized data use.

- *Security risks:* Data poisoning, model extraction, adversarial inputs, prompt injection (for LLM-based systems) and supply chain compromise.

- *Transparency and explainability risks:* Inability to explain decisions, opacity of model behavior and failure to disclose AI involvement.

- *Accountability risks:* Unclear ownership, diffuse responsibility in multi-agent or multi-vendor systems and inability to reconstruct decision basis.

- *Operational risks:* System failure, dependency failures, vendor discontinuation and inadequate human oversight capacity.

- *Legal and regulatory risks:* Non-compliance with applicable AI regulations, data protection law violations and intellectual property infringement in model outputs.

- *Societal and reputational risks:* Systemic harm to affected populations, labor displacement without adequate mitigation and public trust erosion.

- *Supply chain risks:* Risks inherited from third-party models, datasets, components or GPAI model providers.

**Recommended Identification Methods:**

- Pre-mortem analysis: Envisioning plausible future failures and working backward to identify contributing factors.

- Incident pattern mining: Learning from historical AI failures, external incident databases and sector-specific guidance.

- Horizon scanning: Identifying risks across short, medium and long-term timeframes including emerging regulatory developments.

- Red teaming: Simulating adversarial attacks or misuse scenarios, including prompt injection for LLM-based systems.

- Dependency chain analysis: Mapping upstream and downstream components that influence the system’s stability, integrity or bias characteristics.

- Stakeholder consultation: Gathering input from affected communities before deployment of systems that will materially affect them.

At least one structured technique (pre-mortem or red teaming) must be applied for each Medium or High Impact system. Identified risks are recorded in the AI Risk Register with their source, description and associated context. Risks must be revisited periodically and updated following incidents, material system changes or regulatory developments.

### 4.5 Risk Assessment

Each identified risk is formally assessed across four dimensions.

**Likelihood.** How probable it is that the risk will occur, scored on a qualitative scale (for example: rare, unlikely, possible, likely and almost certain).

**Impact Severity.** The potential harm or consequence of the risk materializing, considering legal, operational, financial or reputational damage to the organization and harm to affected persons.

**Impact Velocity.** How quickly the risk could unfold and affect the organization or affected persons if triggered. AI risks can escalate non-linearly; this dimension must not be subordinated to the raw likelihood-severity calculation.

**Dynamic Feedback Effects.** Whether the risk could self-amplify or create cascading failures, such as model feedback loops, emergent behaviors in multi-agent systems or reinforcement of biased outputs through retraining on biased decisions.

A risk matrix combines likelihood and impact severity to produce a raw risk score. Risks with fast velocity or high feedback potential must be prioritized even if their raw score appears moderate. Residual risk, after controls have been applied, must be reassessed and recorded.

### 4.6 Risk Treatment

For all risks rated Moderate or higher, appropriate control measures must be selected and assigned. Controls must be proportionate to the assessed risk level and aligned with the organization’s risk appetite and tolerance thresholds. Each control is assigned to a named System Owner or Mechanism Owner responsible for implementation and for maintaining current status in the Risk Register.

**Control Taxonomy:**

*Technical controls.* Fairness testing and bias mitigation. Drift detection and automated alerting. Model explainability tools. Adversarial robustness testing. Rate-limiting and fail-safes. Integrity verification for models and training data. Output filtering for high-risk content categories. Automated monitoring with threshold-based escalation.

*Process controls.* Human-in-the-loop mechanisms at defined decision points. Approval gates between lifecycle stages. Governance reviews before deployment and after material changes. Structured testing requirements (TEVV methodology). Pre-mortem and red-teaming workshops. Incident reporting integration.

*Organizational controls.* Role-based access to AI systems and training data. Mandatory training by role and system classification. Escalation procedures with named recipients and response timeframes. System Owner accountability and periodic accountability reviews.

*Third-party and supply chain controls.* Contractual SLAs covering performance, fairness and security. Audit rights and right to information. Incident notification obligations. Restrictions on vendor use of organizational data for model training. Vendor AI governance assessment before procurement. Ongoing monitoring of vendor compliance and system updates.

Where mitigation is not feasible, risks may be escalated for acceptance or avoidance decisions under defined approval thresholds. Residual risk after controls must be reassessed and recorded. Risk acceptance for High Impact systems requires AI Governance Committee approval.

### 4.7 Risk Monitoring

Deployed AI systems must be monitored on an ongoing basis for indicators that identified risks are emerging or that existing controls are no longer effective. Monitoring covers:

- Input data characteristics including distribution shifts and data quality degradation.

- Model performance metrics including accuracy, fairness measures and precision/recall across demographic groups.

- System behavior including anomalies and unexpected user outputs.

- User feedback, complaints and error reports.

- External intelligence including AI incident databases, regulatory guidance updates and threat intelligence relevant to AI-specific attack vectors.

Monitoring procedures must be documented for each AI system. Where possible, automated monitoring tools should be implemented. Thresholds and triggers must be established for key indicators and any breach must be escalated through the incident management process without delay.

### 4.8 AI Risk Register

The organization maintains a centralized AI Risk Register recording all identified risks, their classifications, assigned owners, the status of mitigations and residual risk levels. The Register is maintained by the AI Operational Committee and informs governance reporting, audit and continuous improvement activities. System Owners are responsible for keeping their entries current as circumstances change. The Register is reviewed at each Operational Committee meeting and audited at least annually.

## PART 5: TEVV (TEST, EVALUATION, VALIDATION AND VERIFICATION)

TEVV activities provide structured assurance that AI systems behave as intended, are free from unacceptable failure modes and comply with applicable requirements across the development lifecycle. TEVV is not a single deployment gate but an ongoing methodology applied at each lifecycle stage. The depth and rigor of TEVV activities must be proportionate to the system’s impact classification.

TEVV operates against the specification produced under the OPERATIONAL CADENCE Specify discipline. The two-sided requirement applies here as well: every test objective must trace back to an element the specification commits to, on the system side, and every acceptance threshold must be one the authorizing human had the conditions to evaluate, on the human side. Where TEVV objectives cannot be traced to a specification element, the test plan is operating against an inferred standard rather than a specified one, and its results cannot be defended as evidence that the system did what was authorized. Where the specification contains elements the authorizing human could not assess, TEVV passing those elements does not make the authorization genuine. TEVV is the operationalization of Specify, not a substitute for it.

### 5.1 Testing

Testing assesses AI system behavior against defined requirements under controlled conditions. For AI systems, testing must cover:

- Functional performance against defined acceptance criteria.

- Performance across demographic subgroups and edge cases.

- Behavior under adversarial inputs, out-of-distribution data and stress conditions.

- Security testing including penetration testing and AI-specific attack simulations (data poisoning, model extraction, prompt injection where applicable).

- Integration testing where the AI system interacts with other software systems, including other AI systems.

Test plans, scenarios, data and results must be documented. High Impact systems require independent testing in addition to developer-conducted testing.

### 5.2 Evaluation

Evaluation assesses whether the AI system, as tested, meets organizational and regulatory requirements and is appropriate for the intended deployment context. Evaluation activities include:

- Review of test results against acceptance criteria.

- Bias and fairness evaluation including subgroup performance analysis.

- Stakeholder impact assessment (required for Medium and High Impact systems).

- Legal and regulatory compliance review.

- Documentation completeness review.

Evaluation must be conducted by personnel independent of the development team for High Impact systems.

### 5.3 Validation

Validation confirms that the AI system, once deployed, performs as intended in the real operational environment with real users and real data. Pre-deployment validation for High Impact systems must include:

- User acceptance testing with representative users including potentially affected communities.

- Operational environment testing to confirm performance under actual deployment conditions.

- Independent external validation for High Impact systems.

Post-deployment validation must be conducted at defined intervals and following material changes.

### 5.4 Verification

Verification confirms that the AI system has been built correctly in accordance with its design specifications and governance requirements. Verification activities include:

- Code and model review against documented design.

- Data provenance verification.

- Governance documentation completeness verification.

- Conformity assessment, where required by applicable regulation.

For EU AI Act high-risk AI systems, conformity assessment must be conducted in accordance with Article 43, either by internal conformity assessment (for systems not covered by Annex VII) or by a notified body (for biometric systems and other categories requiring third-party assessment).

### 5.5 Red-Teaming Standards

Red-teaming is the structured adversarial evaluation of an AI system by a team tasked with identifying failure modes, harmful outputs, safety bypasses and misuse pathways that the development team did not find. For most systems, red-teaming is one method of risk identification among several. For GPAI models with systemic risk under EU AI Act Article 55 and for High Impact systems in safety-critical domains, red-teaming is a specific compliance deliverable and must be conducted to a defined standard.

**Scope of applicability.** Red-teaming is mandatory for providers of GPAI models with systemic risk (Article 55(1)(a)). It is mandatory as a pre-deployment TEVV step for any High Impact system operating in safety-critical domains (healthcare, transportation, critical infrastructure, criminal justice) and for any system that can take consequential autonomous action. It is recommended for Medium Impact systems that process sensitive data, interact with vulnerable populations or operate at scale.

**Internal versus external.** For GPAI models with systemic risk, independent external evaluation is expected in most circumstances, in addition to internal red-teaming. For High Impact non-GPAI systems, internal red-teaming is the minimum; external red-teaming is recommended and is the emerging standard for consequential deployments. Red-teaming performed by the development team is not red-teaming within the meaning of this Part. The evaluators must be meaningfully independent of the development team, with authority to escalate findings directly to the System Owner and the AI Governance Committee without intermediate filtering.

**Required elements of a red-teaming exercise.** A documented test plan stating objectives, scope, threat model, success criteria and stop conditions. A test environment that reflects the production deployment context (including realistic data, realistic user interfaces and realistic tooling available to the evaluator). A defined taxonomy of failure modes targeted by the exercise, which should cover at minimum: generation of harmful content, bias and discrimination, privacy leakage, prompt injection and jailbreak, capability uplift for biological, chemical, cyber or nuclear misuse where the model has such capabilities, multi-turn deception, and coordinated misuse by multiple actors. For agentic systems (Part 9), the taxonomy must additionally cover scope violation, tool misuse, data exfiltration through actions, and goal drift across multi-step execution.

**Result documentation.** The red-team report must record the method, the attempted inputs or attack sequences, the observed behaviors, the severity assessment for each finding and the proposed mitigation for each finding accepted by the System Owner. For GPAI with systemic risk, the summary must be retained and made available to the AI Office on request. The complete test artifacts (including any prompts or attack sequences) must be retained under controlled access for the technical documentation retention period applicable to the system.

**Cadence.** Red-teaming is not a one-time pre-deployment activity. For GPAI models with systemic risk, red-teaming must be repeated on material model updates and at a cadence specified in the provider’s safety and security framework. For High Impact systems, red-teaming must be repeated on material updates and at a cadence proportionate to the system’s rate of change and deployment velocity, with a minimum of annually.

**Coordination with serious incident reporting.** Findings from red-teaming that reveal an active exploitable vulnerability in a deployed system must be treated as incidents under Part 8, not merely as test outputs. The Article 73 incident reporting timelines apply to findings that meet the relevant severity thresholds.

**Staffing.** Red-teaming requires adversarial expertise that most development teams do not possess. For GPAI with systemic risk and for High Impact systems in safety-critical domains, the organization must identify the red-team skill set required, acquire it through internal hiring or external engagement and ensure that red-team personnel have the time, tooling and organizational authority to be effective. Checkbox red-teaming by under-resourced internal teams is a common audit finding and a common vector for subsequent incidents.

### 5.6 Evaluation Validity and the Test-Aware Model

A foundational assumption in TEVV practice is that a system’s behavior under controlled test conditions is representative of its behavior under deployed conditions, in the dimensions the test is designed to measure. Where that assumption holds, benchmark performance is a defensible input to governance decisions. Where it does not hold, the same benchmark performance is at best an incomplete signal and at worst a misleading one.

**The phenomenon.** In May 2026, Anthropic published research on Natural Language Autoencoders, a method that translates a language model’s internal activations into human-readable text via an activation verbalizer and an activation reconstructor trained jointly with reinforcement learning. The reported findings include unverbalized evaluation awareness: on a benchmark testing whether a model takes destructive code actions, the method surfaced internal text indicating evaluation awareness in 16% of trials; on SWE-bench Verified the figure was 26%; on real opted-in claude.ai usage the figure was less than 1%. The signal in question never appeared in the model’s visible outputs.

**TEVV implication.** Benchmark performance and deployed performance may diverge in dimensions the benchmark cannot itself surface. A test plan that treats benchmark conditions and operational conditions as interchangeable is asserting an empirical claim that the early research suggests may not hold across all conditions. The implication is structural: the validity of the evidence the audit relies on is a function of the relationship between the test environment and the production environment, not a property of the test alone.

**Operational requirements for High Impact systems.** The TEVV plan must distinguish performance claims supported by benchmark evidence from performance claims supported by real-usage evidence, and must not treat the former as a substitute for the latter where the governance question is whether the system performs as authorized in deployment. The pre-deployment specification must explicitly identify which acceptance thresholds are being assessed under benchmark conditions, which under real-usage conditions and what evidence supports each. The monitoring and re-validation program must include real-usage sampling distinct from benchmark re-runs, with sampling cadence proportionate to the system’s risk profile and with the gap between benchmark and real-usage performance documented at each re-validation.

**Drafting note.** This is an active research area. The methodology is statistical rather than deterministic and the early findings do not establish that all benchmark performance is structurally compromised. The doctrinal point is durable: where the test condition is itself a feature the system can detect, the evidence produced under test conditions does not automatically transfer to claims about deployed conditions. The named human under Final Liability cannot delegate the validity question to the benchmark.

**Reference.** Anthropic, “Natural Language Autoencoders Produce Unsupervised Explanations of LLM Activations,” Transformer Circuits, May 2026 (transformer-circuits.pub/2026/nla/); Anthropic, “Natural Language Autoencoders” research blog (anthropic.com/research/natural-language-autoencoders), 7 May 2026.

## PART 6: MODEL AND DATA LIFECYCLE MANAGEMENT

### 6.1 Lifecycle Ownership

Every AI model must have a designated owner accountable for its compliance with lifecycle requirements. Ownership is a named individual responsibility, not a team or function. Ownership transfers must be formally documented. Ownership does not lapse when a system moves between lifecycle stages or between business units.

### 6.2 Lifecycle Stages

Governance mechanisms must be in place covering each stage of the model lifecycle.

**1. Ideation.** System concept documented. Preliminary impact classification conducted. Sensitive-use test applied. Escalation to Legal where required. No further development activity before classification and sensitive-use assessment are complete.

**2. Data Sourcing.** Data provenance documented for all training, validation and test data. Privacy and legal basis confirmed for personal data. Data minimization applied. Bias and representativeness of datasets assessed. Contractual rights to use data for model training verified.

**3. Development.** Risk assessment conducted and recorded in the Risk Register. Fairness and bias testing initiated. Model documentation commenced. Security controls designed into the system architecture. TEVV plan developed.

**4. Validation and Testing.** TEVV activities conducted per Part 5. Acceptance criteria documented and results recorded. Stakeholder impact assessment completed for Medium and High Impact systems. Independent review conducted for High Impact systems. Documentation completed.

**5. Deployment.** Governance approval obtained at the appropriate tier. Human oversight mode documented and operational. Monitoring activated and baseline established. Incident reporting integrated. Instructions for use prepared and provided to deployers where the organization is a provider.

**6. Operation.** Continuous monitoring for performance, fairness and compliance. Change management applied to material updates. Incident reporting active. Periodic re-assessment of impact classification. Post-market surveillance conducted in accordance with regulatory requirements.

**7. Retirement.** Formal retirement decision documented with rationale. Affected parties notified where required. Appropriate archival or deletion of models and data conducted. Lessons learned captured and fed into governance improvement. Regulatory records retained for required periods.

Changes between lifecycle stages require review and approval at the governance tier appropriate to the system’s impact classification.

### 6.3 General-Purpose AI Model Governance

Organizations that develop, fine-tune, deploy or integrate GPAI models face governance considerations beyond those applicable to purpose-built AI systems.

**Provider obligations (EU AI Act Chapter V).** Organizations placing GPAI models on the market must prepare and maintain technical documentation, provide information and documentation to downstream providers, establish and implement a policy to respect copyright law and publish a summary of training data. GPAI models with systemic risk face additional obligations including adversarial testing, serious incident reporting and cybersecurity measures.

**Deployer considerations.** Organizations integrating GPAI models into their systems inherit the model’s capabilities and limitations, including its potential failure modes. Risk assessments for GPAI-integrated systems must account for the opacity of the underlying model, the potential for prompt injection attacks, hallucination risks and the difficulty of verifying that training data was obtained with appropriate rights.

**Supply chain obligations.** Organizations integrating third-party GPAI models must obtain sufficient information from the model provider to conduct meaningful risk assessment, must contractually require incident notification from providers and must maintain the ability to switch to an alternative model or disengage the model if unacceptable risks are identified.

### 6.4 Documentation and Traceability

Lifecycle documentation must be maintained for all AI systems to enable auditability, incident response and regulatory inquiry. Required documentation includes data provenance records, TEVV results, deployment records, risk assessments, governance approvals and performance monitoring logs. Documentation must be version-controlled and retained according to organizational standards and applicable regulatory requirements. Minimum retention periods for High Impact systems should be established in consultation with Legal and Compliance, accounting for EU AI Act Article 18 requirements (ten years for high-risk systems).

Model cards or equivalent system documentation must be maintained for all AI systems and updated at each material change. Data cards (also known as datasheets for datasets) must be maintained for significant training, validation and test datasets. The minimum content specifications below are drawn from the convergent practice of the EU AI Act Annex IV technical documentation requirements, the NIST AI RMF MAP function, the Hugging Face and Google model card templates and the Datasheets for Datasets proposal (Gebru et al. 2018). The specifications are minima; drafters should extend them where system complexity or regulatory exposure requires.

**Minimum Model Card Content.**

*Identification.* System or model name. Version and release date. Provider and deployer identification. Contact point for governance inquiries.

*Intended use.* Primary intended purpose. Intended users and deployment contexts. Explicit out-of-scope uses and populations.

*System characteristics.* Model architecture family and high-level design. Input modalities and output modalities. Integration characteristics (standalone, embedded, agentic). Oversight mode assigned (HITL, HOTL or HIC) and the rationale for that assignment.

*Training data.* Sources, time period and geographic coverage. Size (records, tokens or equivalent). Known gaps, biases and representation limitations. Lawful basis for personal data processing where applicable. Copyright provenance summary where applicable.

*Performance.* Benchmarks used and rationale for their selection. Overall metrics against defined acceptance criteria. Subgroup performance across relevant demographic, linguistic or contextual dimensions. Out-of-distribution behavior.

*Known limitations and failure modes.* Scenarios in which the system is known to fail or degrade. Adversarial vulnerabilities identified in red-teaming (Part 5.5). Fairness trade-offs accepted under the Part 4.2 Principle 2 fairness selection process.

*Governance.* Impact classification. Applicable regulatory classification (EU AI Act actor and risk designation, GPAI classification where applicable). Approvals received and approval authority. Date of next scheduled review. FRIA status where Article 27 applies.

**Minimum Data Card Content.**

*Identification.* Dataset name, version and creation date. Dataset owner.

*Composition.* Number of instances. Feature or variable schema. Sampling method. Representation analysis across relevant demographic, geographic or contextual dimensions.

*Collection process.* Data source. Collection method. Collection time period and geography. Consent, lawful basis and rights posture for any personal data included.

*Preprocessing.* Cleaning, labeling, augmentation and transformation steps applied. Labeler identity and training where human labeling was used. Inter-rater agreement statistics for human-labeled data.

*Use and distribution.* Intended uses. Explicit prohibited uses. Licensing terms. Distribution and access controls.

*Maintenance.* Update cadence and change log. Decommission plan, if any.

*Known limitations.* Identified biases and representation gaps. Known errors or labeling disputes. Downstream implications of those limitations for models trained on the dataset.

### 6.5 Change Management

Significant changes to AI systems, including changes to models, data inputs, configuration, scope or operating environment, must follow documented change management processes. Changes must be logged and approval obtained at the governance tier appropriate to the system’s classification. Where a change would raise a system’s impact classification, the higher classification requirements apply before the change proceeds. Automated monitoring should be configured to flag performance changes following updates that may indicate unintended effects.

### 6.6 Post-Market Surveillance

Deployed AI systems must be subject to ongoing post-market surveillance to identify performance issues, harm signals and emerging risks that were not apparent at deployment. Post-market surveillance includes:

- Analysis of monitoring data and incident records to identify trends.

- Review of user feedback and stakeholder complaints.

- Assessment of external intelligence including regulatory guidance, industry incidents and academic research.

- Periodic formal review of the system’s continued fitness for purpose and compliance.

For EU AI Act high-risk AI systems, post-market surveillance must be conducted in accordance with Article 72 and must include reporting of serious incidents and malfunctions to relevant market surveillance authorities.

### 6.7 Quality Management System

Providers of high-risk AI systems are required under EU AI Act Article 17 to establish and maintain a Quality Management System (QMS) covering the full development and post-market lifecycle of their high-risk AI systems. The QMS is an organizational requirement, not just a technical one and must be documented and subject to internal audit.

Minimum QMS scope under Article 17 includes:

- A documented strategy for regulatory compliance, including how applicable requirements are identified and addressed.

- Techniques for designing and controlling AI system development, including design and development processes, testing methodologies and validation criteria.

- Data governance procedures covering training data sourcing, bias assessment and data quality controls.

- Risk management procedures aligned with Article 9.

- Post-market monitoring and incident reporting procedures aligned with Articles 72 and 73.

- Documentation and record-keeping procedures aligned with Articles 11 and 18.

- Resource management and accountability assignments across the development and operation lifecycle.

- Human oversight arrangements and responsibilities.

- Procedures for corrective actions when non-conformities are identified.

The QMS does not need to be a separate stand-alone system; organizations with existing ISO 9001 or equivalent quality management systems may incorporate AI-specific requirements into those systems. The QMS must be reviewed and updated when the organization’s AI activities or applicable regulatory requirements change materially.

Where an organization is both a provider and a deployer of the same AI system (for example, developing a system in-house and then deploying it internally), the QMS obligations apply in full to the provider function regardless of the internal deployment context.

### 6.8 EU Database Registration

Providers of high-risk AI systems listed in EU AI Act Annex III must register themselves and their systems in the EU database established under Article 71 before placing those systems on the market or putting them into service. Deployers that are public authorities, Union institutions, bodies, offices or agencies (or persons acting on their behalf) must also register themselves, select the system and register their use of it in the same database before putting it into service. Private sector deployers do not have a general obligation to register their use of acquired high-risk AI systems in the EU database, though registration by the provider is a prerequisite for lawful deployment.

Registration is a mandatory pre-market step, not a post-deployment formality. The AI inventory maintained under Part 14 of this reference should record EU database registration status and registration identifiers as mandatory fields for all High Impact systems that fall within Annex III scope.

Providers must update database entries when significant changes occur to the registered system and must notify the competent authority of any serious risks or incidents identified post-registration. Withdrawal from the market must also be notified.

## PART 7: ACCEPTABLE USE

### 7.1 Permitted Uses

Personnel are encouraged to use approved AI tools for the following purposes, provided the governing principles are applied.

**Efficiency and productivity.** Automating repetitive tasks, summarizing documents, drafting routine content and generating data insights using approved tools.

**Creative brainstorming and drafting.** Generating initial drafts of content including marketing copy, code snippets and design concepts, subject to human review and editing before use. AI-generated content must be reviewed for quality, accuracy and compliance before final use.

**Data analysis and decision support.** Using AI analytics or predictive tools to inform decisions, provided results are validated and limitations understood. AI highlights insights; human judgment is required to interpret and act on them. AI-generated insights must not be used as the sole basis for consequential decisions.

**Customer communication.** Using AI to research issues, draft responses or refine communications, provided customer data is only entered into tools approved for that data category. The employee remains accountable for the accuracy and appropriateness of communications sent.

**Learning and skill development.** Using AI tools to learn new skills or deepen understanding of AI capabilities, using non-sensitive test data for practice. Employees should actively build understanding of how the tools they use work and where they may fail.

**Pilot projects and experimentation.** Proposing and running small-scale AI pilots in controlled environments using test data, after informing the manager and completing the concept-stage impact assessment. Before any pilot moves to production data or customer-facing use, it must be reviewed and approved through the governance process.

### 7.2 Prohibited Uses

The following uses of AI are strictly prohibited. Violation may result in disciplinary action up to and including termination.

**Disclosing confidential or personal information.** Never enter confidential, proprietary or personal data into AI tools not approved for that data category. Treat information entered into any external AI tool as potentially accessible to others, including the tool provider.

**Bypassing security or access controls.** Do not use AI to circumvent security measures, access unauthorized data, scrape restricted information or automate unauthorized access to systems or data.

**Making consequential decisions without human review.** AI must not make final decisions in employment, credit, service eligibility or safety contexts without qualified human review and approval.

**Creating deceptive or harmful content.** Do not use AI to generate harassment, defamation, explicit material, deepfakes, phishing messages or any content designed to deceive. All AI-assisted communications must be honest. Do not misrepresent AI-generated content as entirely human-created where disclosure is required.

**Infringing intellectual property.** Do not use AI to generate content that infringes copyrights, trademarks or licenses. Verify the provenance of AI-generated code, images or text before organizational use. Consult Legal where IP status of AI outputs is uncertain.

**Circumventing compliance requirements.** Do not use AI in ways that breach applicable laws, regulations or internal policies.

**Concealing AI involvement or problems.** Do not hide AI’s involvement where disclosure is required. Do not ignore known limitations or continue using a tool that is producing problematic outputs. Report issues promptly.

**Prohibited AI practices.** Do not use or procure any AI system that falls within the prohibited practices categories set out in Section 4.2 of this reference.

### 7.3 Uses Requiring Extra Caution

The following permitted uses require additional care and judgment.

**External or unapproved AI tools.** Only input non-sensitive, publicly available information unless the tool has been specifically approved for organizational data. Verify outputs carefully.

**Handling AI-generated content.** Review and edit AI-generated content thoroughly before use in any official capacity. Check for factual errors, inappropriate language and alignment with organizational values. Label content as AI-assisted where transparency is appropriate.

**Integrating AI into workflows.** Consider data handling, security and compliance implications before adding new AI tools or plugins. Test on a small scale first. Consult IT before integrating AI tools that affect shared systems or data.

**Using personal AI tools for work.** Organizational policies apply regardless of whether a personal device or account is used. Avoid mixing personal and organizational data. Prefer organization-provided AI resources.

**Regulated or sensitive areas.** Apply additional scrutiny when work involves regulated activities, sensitive customer data or high-stakes decisions. Consult compliance or legal contacts before relying on AI assistance.

### 7.4 Tool-Specific Guidance

**Generative AI Tools (large language models, image generators and similar systems).** Generative AI can produce plausible-sounding but factually incorrect information, including invented citations and confident statements that are wrong. Always verify factual claims against reliable sources before relying on them. Public generative AI services may retain inputs or use them for model training; treat information entered as potentially accessible. AI-generated content may resemble copyrighted material; do not assume it is original. Generative AI systems are susceptible to prompt injection attacks; exercise heightened caution when using AI to process content from untrusted sources.

**Coding and Productivity Assistants.** Treat AI-generated code as code from an inexperienced developer: review for correctness, security vulnerabilities and compliance with coding standards. Never commit AI-generated code to production without proper review and testing. Be alert to licensing obligations for code that may have been derived from specific open-source training data. Productivity copilots process document content to generate suggestions; confirm the tool is approved for the classification level of documents being processed.

**AI Features Embedded in Business Software.** Many enterprise applications include built-in AI features such as lead scoring, anomaly detection or matching algorithms. Before relying on an embedded feature, understand what it does, what data it processes and what its limitations are. AI-generated recommendations are one input to a decision, not a final answer. Monitor vendor release notes for changes to AI features that may materially affect data handling or decision-making behavior.

**Agentic AI Systems.** Agentic AI systems can take actions autonomously, executing multi-step tasks, interacting with software environments and making decisions with limited human involvement. Governance requirements specific to agentic systems are set out in Part 9 of this reference.

## PART 8: INCIDENT MANAGEMENT

### 8.1 Detection and Reporting

System Owners must ensure monitoring is in place to detect anomalies, drift, misuse and outputs outside acceptable parameters. Any personnel observing an AI system producing harmful, incorrect or unexpected outputs, or suspecting a policy violation, must report promptly through designated incident reporting channels.

All suspected incidents and near-misses must be recorded in the Incident Register with an initial severity assessment within a defined period following identification (recommend: within 24 hours for all incidents; within two hours for high-severity incidents). A culture of prompt reporting is expected; failure to report a known incident may itself constitute a governance breach. Good faith reporting will not result in adverse consequences for the reporter.

For urgent matters affecting customers or safety, senior management must be notified immediately without waiting for the standard reporting process.

### 8.2 Severity Classification

Incident management must define severity levels and corresponding response requirements. The following framework provides a minimum structure:

**Critical.** Incidents involving material harm to affected persons, significant regulatory exposure, criminal conduct, systemic failure across multiple systems or any matter that may trigger mandatory regulatory notification. Immediate escalation to the AI Governance Committee and senior leadership. Regulatory notification obligations assessed within hours of identification.

**High.** Incidents involving significant harm to individuals, material compliance failures, security breaches affecting personal data or high-impact system failures. Rapid activation of incident response. Escalation to the AI Operational Committee. Assessment for regulatory notification.

**Medium.** Incidents involving moderate harm, isolated compliance failures or control weaknesses identified before harm occurs. Managed through the standard incident management process. Reported to the AI Operational Committee at the next scheduled meeting.

**Low.** Minor incidents including near-misses, performance degradation within tolerable bounds and isolated user errors. Recorded and reviewed as part of continuous improvement. Aggregated patterns of Low incidents must be reviewed for systemic signals.

### 8.3 Regulatory Notification

Where an AI incident may trigger mandatory notification obligations under applicable law, Legal and Compliance must be involved immediately. Relevant notification obligations include:

- **EU AI Act Article 73.** Providers and, where applicable, deployers of high-risk AI systems must notify the relevant national market surveillance authority of any serious incident. Notification timelines are tiered by incident type and are measured in calendar days, not working days:

- **Standard serious incidents:** Not later than 15 calendar days after the provider or deployer becomes aware of the incident. (Article 73(2).)

- **Widespread infringement or serious incident per Article 3(49)(b):** Not later than 2 calendar days after awareness. (Article 73(3).)

- **Death of a person:** Not later than 10 calendar days after awareness. (Article 73(4).) In all three tiers, the report must be made immediately after a causal link (or reasonable likelihood of a causal link) between the AI system and the incident is established. An initial incomplete report is permitted, followed by a complete report.

- **GDPR Article 33.** Personal data breaches must be notified to the supervisory authority within 72 hours of becoming aware.

- **Sector-specific requirements.** Financial services, healthcare and critical infrastructure sectors may have additional incident notification obligations. Legal and Compliance must maintain a current registry of applicable notification requirements.

Regulatory notification timelines must be built into the incident response process so that assessment of notification obligations occurs as a standard step for all Critical and High severity incidents.

### 8.4 Investigation and Remediation

Significant incidents must undergo root cause analysis, with findings documented. Investigation must cover not only the proximate cause but the governance and control failures that allowed the incident to occur. Remediation is not complete until corrective actions have been implemented and independently verified as effective. System Owners are responsible for driving remediation within their systems; the AI Operational Committee oversees cross-system issues and systemic failures.

### 8.5 Learning and Improvement

Incident findings must feed back into governance. This includes updating controls, monitoring thresholds, risk assessments and training where appropriate. The Governance Committee reviews significant incidents to identify systemic issues and endorse improvements. The organization should also monitor external AI incident databases and regulatory publications for lessons applicable to its own systems and incorporate those lessons into the risk taxonomy and control catalogue. Governance must operate as a documented feedback loop rather than a one-time implementation exercise, with lessons from incidents, audits, user feedback, vendor changes and regulatory developments feeding into policy updates, technical controls, oversight design and training priorities.

## PART 9: AGENTIC AI GOVERNANCE

Agentic AI systems present governance challenges that standard AI governance frameworks do not fully address. The IMDA Model AI Governance Framework for Agentic AI and emerging regulatory guidance recognize that agentic systems require specific governance mechanisms reflecting their capacity for autonomous action, multi-step execution and real-world consequence. This Part supplements the general framework.

### 9.1 What Makes Agentic AI Distinct

Unlike generative AI systems where a human reviews outputs before use, agentic AI systems may act before human intervention is possible. In multi-agent architectures, AI systems may direct other AI systems, creating chains of action where oversight and accountability become diffuse. Actions taken by agentic systems (executing transactions, sending communications, modifying data and initiating processes) may be difficult or impossible to reverse. These characteristics require governance mechanisms calibrated specifically to autonomous action, not merely to output generation.

### 9.2 Agentic System Classification

All agentic AI systems must be classified at minimum as Medium Impact. Systems that can execute financial transactions, send external communications, modify production data, interact with critical infrastructure or initiate legal commitments must be classified as High Impact. Multi-agent systems in which AI directs other AI must receive additional scrutiny at classification, with assessment of the aggregate capabilities and risk of the full system rather than individual component agents.

### 9.3 Scope Definition and Authorization

Before any agentic AI system is deployed, the following must be explicitly documented and approved:

- **Action scope:** The specific categories of actions the agent is authorized to take, with clear boundaries on what is out of scope.

- **Data access:** Which data sources and systems the agent can access, read or modify.

- **Authorization thresholds:** The point at which the agent must pause and obtain human approval before proceeding. Thresholds should be defined by action type, transaction value, number of affected parties or other appropriate parameters.

- **Stop conditions:** The conditions under which the agent must cease operation and escalate to a human, including unexpected situations the agent cannot classify within its authorized scope.

- **Principal hierarchy:** In multi-agent systems, which agent or human has authority to direct each agent and how conflicting instructions are resolved.

Authorization documentation must be approved by the System Owner and reviewed at each material change.

### 9.4 Human Oversight for Agentic Systems

High Impact agentic systems require HITL oversight for actions above defined authorization thresholds. Medium Impact agentic systems require at minimum HOTL oversight, with a qualified human actively monitoring agent activity in real time and retaining the practical ability to intervene and halt operation.

Oversight mechanisms must include:

- Comprehensive, real-time action logging sufficient to reconstruct what the agent did, when, with what data and what the outcome was.

- Clear and accessible controls enabling any authorized user to pause, redirect or terminate the agent.

- Automated alerting when the agent encounters situations outside its defined scope or when its actions exceed defined thresholds.

- Regular review of agent action logs by the System Owner, at a frequency proportionate to the agent’s action velocity and impact.

### 9.5 Accountability in Multi-Agent Systems

In multi-agent systems, the organization must maintain clear accountability for the actions of every agent in the network, regardless of whether individual agents are operated by the organization or by third parties. Where third-party agents are integrated into organizational workflows, the organization must:

- Contractually require equivalent governance standards from the third-party operator.

- Maintain audit rights over third-party agent behavior where that behavior can affect organizational systems or the organization’s customers.

- Assess whether the aggregate capability of the multi-agent system constitutes a different risk profile from its component parts.

- Maintain the ability to disengage from third-party agents where governance concerns arise.

Accountability for outcomes produced by agentic systems remains with the human principal who deployed or authorized the system. This accountability cannot be delegated to the agent.

### 9.6 Security for Agentic Systems

Agentic systems face heightened security risks. Prompt injection attacks, in which malicious content in the agent’s operating environment is crafted to redirect the agent’s behavior, are a primary threat vector. Mitigation measures must include input validation, output filtering, sandboxed execution environments where feasible and anomaly detection calibrated to the agent’s expected behavioral envelope. Credentials and access tokens available to agentic systems must follow the principle of least privilege; agents should have access only to what is required for their defined scope.

## PART 10: PROCUREMENT AND VENDOR MANAGEMENT

### 10.1 Vendor Assessment

AI vendors must be assessed against established technical and responsible AI criteria before approval. Assessment must address:

- The vendor’s data handling practices including storage, retention, geographic location and use of customer data for model training.

- Security controls and certifications.

- Testing methodology for bias, harmful outputs and adversarial robustness.

- Transparency about system capabilities, limitations and failure modes.

- The vendor’s own AI governance practices and track record.

- The vendor’s regulatory compliance posture, including EU AI Act obligations where applicable.

- For GPAI model providers, technical documentation and disclosure obligations under EU AI Act Chapter V.

For Medium and High Impact systems, vendors must provide evidence of appropriate testing including methodology, training data information, known limitations and safeguards in place.

### 10.2 Minimum Contractual Requirements

Contracts with AI vendors must be reviewed by Legal and Compliance before finalization. All AI vendor contracts for Medium and High Impact systems must include:

- Performance standards and acceptance criteria.

- Data handling, security and privacy obligations including restrictions on use of organizational data for model training unless explicitly authorized.

- Audit rights, including the right to conduct or commission independent technical assessment of the AI system.

- Incident notification obligations, with timelines consistent with the organization’s regulatory notification requirements.

- Change notification obligations, requiring the vendor to notify the organization before material changes to the AI system including model updates, data sourcing changes and changes to service terms.

- Risk allocation provisions that reflect the organization’s actual legal liability as a deployer.

- Termination rights allowing the organization to exit the contract where the vendor fails to meet governance or security requirements.

- Data return and deletion obligations on termination.

### 10.3 AI Supply Chain Risk

Organizations must assess and manage risks arising from their AI supply chain, including risks inherited from third-party models, datasets, components and infrastructure. Supply chain risk assessment must identify:

- Which third-party components are integrated into each AI system.

- What governance assurances exist for each third-party component.

- What happens to the organization’s AI systems if a third-party component fails, is discontinued or is found to contain unacceptable risks.

- Whether the aggregate supply chain creates concentration risk through over-reliance on a single vendor or model provider.

Supply chain risks must be recorded in the AI Risk Register and addressed through contractual controls, technical safeguards and contingency planning.

### 10.4 Ongoing Oversight

System Owners are responsible for ongoing oversight of third-party AI systems, including monitoring vendor communications about updates, term changes or security issues. Material changes by a vendor trigger a review of the system’s classification and controls before the changed system continues in operation. Where a vendor change raises a system’s risk profile, the governance process must be re-engaged.

### 10.5 Supply Chain: When a Deployer Becomes a Provider

EU AI Act Article 25 addresses the allocation of responsibilities along the AI value chain. This provision has significant practical consequences for organizations that modify, integrate or extend third-party AI systems. Any organization that substantively modifies a high-risk AI system is treated as a provider under the Act and must fulfill the full provider obligation stack.

A deployer becomes a provider when it: places a high-risk AI system on the market or puts it into service under its own name or trademark; makes a substantial modification to a high-risk AI system already on the market; or changes the intended purpose of a system in a way that brings it within the scope of high-risk designation.

**Governance implications.** Organizations must assess, before any modification or integration activity, whether that activity crosses the provider threshold. The assessment must be documented. Modifications that are considered substantial include: retraining on new data that materially changes performance or scope; integrating the system into a new use case that differs from the original intended purpose; extending outputs to affect new categories of persons; or materially altering the human oversight configuration.

**Contractual implications.** Where the organization’s position in the value chain is as a deployer integrating a provider’s system, contracts with AI providers must address: what modifications the deployer is and is not permitted to make; which party assumes provider obligations if a modification is made; and what information the provider will supply to enable the deployer to meet its own deployer obligations under Article 26.

**Internal procedure.** Every proposed material modification to an acquired AI system must be reviewed by Legal and Compliance before implementation, with a documented determination of whether the modification constitutes a substantial modification triggering provider obligations. This review must occur before, not after, the modification is made.

## PART 11: HUMAN OVERSIGHT AND CONTROL

### 11.1 Oversight Mode Assignment

Every AI system must have an explicitly assigned oversight mode, documented and proportionate to its impact classification. The three recognized modes are:

**Human-in-the-Loop (HITL).** Required for High Impact systems making decisions in employment, financial standing, access to essential services and safety contexts. A qualified human reviews and approves each individual AI output or decision before it takes effect. HITL is not satisfied by perfunctory review; reviewers must have sufficient information, time, authority and expertise to exercise genuine independent judgment.

**Human-on-the-Loop (HOTL).** Minimum requirement for Medium Impact systems and the minimum operational standard for High Impact systems operating at scale where HITL at each decision is operationally infeasible. A qualified human actively monitors AI outputs in real time and retains the practical ability and authority to intervene and override. HOTL requires that the monitoring function be genuinely staffed and that intervention is technically and organizationally possible.

**Human-in-Command (HIC).** Appropriate for Low Impact systems operating in low-stakes contexts. Humans retain strategic control over the AI system including deployment decisions and the ability to shut down the system, but are not necessarily involved in individual output decisions.

Oversight mode must be documented in the system’s governance record and in instructions for use. Any proposal to reduce the oversight mode of an existing system (for example from HITL to HOTL) requires Tier 2 approval for Medium Impact systems and Tier 3 approval for High Impact systems.

### 11.2 Meaningful Oversight

Assigning an oversight mode is necessary but not sufficient. Oversight must be meaningful: reviewers must have the information, time, expertise and organizational authority required to exercise genuine judgment. The following conditions undermine meaningful oversight and must be identified and addressed:

- Automation bias: the tendency for human reviewers to default to AI recommendations without adequate scrutiny.

- Review volume that prevents genuine consideration of individual decisions.

- Insufficient training or expertise to identify AI errors in the relevant domain.

- Organizational incentives that discourage overriding AI recommendations.

- Technical systems that make override difficult, slow or require additional justification beyond accepting the AI output.

Human oversight arrangements must be periodically audited for effectiveness, not merely for procedural compliance.

### 11.3 Consequential Decisions

AI must not make final decisions in high-consequence areas (employment, financial standing, access to services and safety) without qualified human review and approval. Where AI informs such decisions, a qualified person makes the final determination. This requirement cannot be waived by operational convenience, processing speed or cost considerations. The organization must be able to demonstrate, for any challenged decision in a high-consequence domain, that a qualified human made the final determination and understood the basis for it.

### 11.4 Disclosure to Affected Persons

AI systems must disclose their automated nature to users and affected persons where such disclosure is material. Where AI has substantially influenced a decision affecting a natural person, that person must be informed that AI was involved and must be provided with meaningful information about the logic, significance and consequences of that decision where required by applicable law (including GDPR Article 22).

## PART 12: CROSS-BORDER COMPLIANCE

Organizations operating AI systems across multiple jurisdictions must maintain a current map of applicable AI and data protection regulations in each operating jurisdiction, reconcile conflicting requirements (applying the most stringent requirement where conflicts cannot otherwise be resolved) and maintain jurisdiction-specific documentation where required by law.

**Key cross-border considerations:**

*EU AI Act.* Applies to providers placing AI systems on the EU market and deployers using AI systems to affect persons in the EU, regardless of where the provider or deployer is established. Extraterritorial in practical effect.

*GDPR and EU data protection law.* Applies to processing of personal data of EU data subjects. GDPR Article 22 creates specific obligations around solely automated decision-making with significant effects on individuals. DPIAs are required under GDPR Article 35 for high-risk processing activities, which typically include large-scale AI applications.

*United States: federal landscape.* The US has no comprehensive federal AI statute as of the date of this version. Federal AI governance is assembled from (a) sector-specific requirements in financial services (Fair Housing Act, Equal Credit Opportunity Act and related AI guidance from financial regulators), healthcare (FDA guidance on AI/ML-based software as a medical device, including the Predetermined Change Control Plan framework) and employment (EEOC guidance on AI use in hiring); (b) executive-branch instruments with variable durability across administrations; and (c) voluntary reference to NIST AI RMF 1.0 and companion profiles (notably the Generative AI Profile NIST AI 600-1 published July 2024). Organizations operating in US federal procurement should assume NIST AI RMF alignment is expected even where not formally mandated.

*United States: state patchwork.* State-level AI regulation is now the principal US compliance surface. Material instruments include:

- **Colorado AI Act (SB 24-205)**. Imposes a duty of reasonable care on developers and deployers of high-risk AI systems to protect consumers from algorithmic discrimination in consequential decisions (employment, education, financial services, healthcare, housing, insurance, legal services). Requires risk management policy aligned with NIST AI RMF or substantially equivalent framework, annual impact assessments, consumer notification, appeal and human-review processes, and 90-day disclosure to the Attorney General upon discovery of algorithmic discrimination. Enforcement exclusively by the Colorado Attorney General; no private right of action. NIST AI RMF compliance creates a rebuttable presumption of reasonable care.

- **New York City Local Law 144 (Automated Employment Decision Tools), effective July 5, 2023.** Requires employers using AEDTs in hiring or promotion decisions for NYC positions to obtain an annual independent bias audit, publish the audit summary and notify candidates before use. Narrow scope but established template cited in subsequent state bills.

- **Illinois AI Video Interview Act (820 ILCS 42), effective January 1, 2020; amended effective January 1, 2022.** Requires notice, consent and specified reporting when AI analyzes video interviews for Illinois positions.

- **Utah AI Policy Act (SB 149), effective May 1, 2024.** Requires disclosure when consumers interact with generative AI in certain regulated professional contexts. Establishes the Office of AI Policy and an AI learning laboratory program.

- **California.** No single horizontal AI statute as of this reference. Governance is assembled from the California Privacy Rights Act (CPRA) automated decision-making rulemaking under the California Privacy Protection Agency; sector-specific rules in insurance, employment and healthcare; and bills targeting specific uses (AB 2013 generative AI training data disclosure, SB 942 AI content provenance, and others). California activity should be tracked continuously; the state legislates by narrow instrument rather than by horizontal framework.

Organizations operating across US states must treat compliance as a multi-jurisdictional matter from the outset. The extraterritorial effect of state AI laws (applying to systems that affect residents of the state regardless of where the operator is located) is the analog of the EU AI Act’s extraterritorial reach. Designing to the most stringent applicable state standard is typically the operative posture.

*United Kingdom.* The UK does not have a horizontal AI-specific statute as of the date of this version. The government’s approach to date has combined pro-innovation sector-regulator guidance, voluntary commitments to the AI Safety Institute (AISI, now the AI Security Institute following renaming), and selective legislative activity. Key elements: (a) sector-regulator AI guidance from the ICO (data protection), FCA and PRA (financial services), Ofcom (online safety and media), MHRA (medical devices), CMA (competition and markets), and others, operating under the Department for Science, Innovation and Technology (DSIT) AI Regulation Principles published in the 2023 White Paper and successor papers; (b) the AISI’s voluntary pre-deployment testing regime for frontier AI models and related commitments from major model providers; (c) the Online Safety Act 2023 which imposes duties on user-to-user services including those using AI for content generation and moderation; and (d) UK GDPR and Data Protection Act 2018 which apply to AI processing personal data. UK providers placing AI systems on the EU market remain subject to the EU AI Act. A UK AI Bill has been anticipated in successive legislative programs; drafters should confirm current status before advising on a specifically UK regulatory regime.

*Republic of Korea.* The Act on the Development of Artificial Intelligence and the Establishment of a Foundation for Trust (AI Basic Act, Act No. 20676) is the world’s second comprehensive AI-specific statute after the EU AI Act. Detailed implementation is delegated to subordinate legislation, principally the AI Basic Act Enforcement Decree (Presidential Decree No. 36053). The Act distinguishes between AI Development Business Operators (developers) and AI Utilization Business Operators (deployers), with most substantive obligations applying to both categories.

Key operative articles for compliance drafting:

- **Article 31 (Transparency).** AI business operators providing products or services utilizing high-impact AI or generative AI must notify users in advance that AI is being used. Providers of generative AI must indicate that outputs are generated by AI. Where AI systems generate virtual sounds, images or video difficult to distinguish from real content, operators must disclose the synthetic origin in a manner allowing clear user recognition, subject to a flexibility for artistic and creative works.

- **Article 32 (Safety).** Operators developing or providing AI systems trained above prescribed computational thresholds must establish lifecycle risk management, document the implementation and submit results to MSIT. The Enforcement Decree sets the threshold at 10^26 FLOPs, ten times the EU AI Act systemic-risk threshold of 10^25 FLOPs. As a practical matter this captures a small number of frontier GPAI providers and is directed at global model developers offering services in Korea.

- **Article 33 (High-Impact AI Verification).** Operators must self-review whether their AI systems qualify as high-impact AI before providing the relevant products or services. Operators may request confirmation from MSIT.

- **Article 34 (High-Impact AI Obligations).** Operators of high-impact AI or products incorporating high-impact AI must: establish and operate a risk management plan; provide explanations of AI-generated outputs, decision criteria and training data overview to the extent technically feasible; implement user protection measures; ensure human oversight; and retain documentation evidencing safety and trustworthiness measures.

- **Article 35 (Impact Assessment).** Encourages (rather than strictly mandates) operators of high-impact AI to conduct pre-deployment fundamental rights impact assessments. Functionally parallel to the EU AI Act Article 27 FRIA but weaker in its binding force.

- **Article 36 (Domestic Representative).** Foreign AI business operators without a Korean address or place of business that meet user-number or revenue thresholds set by Enforcement Decree must designate a Korean domestic representative. The representative acts as the contact point for MSIT investigations, safety obligation submissions and high-impact verification requests and bears derivative liability for certain violations. This is the principal channel through which the Act reaches non-Korean operators.

**Enforcement posture.** The MSIT supervises compliance and may conduct fact-finding investigations, issue corrective orders and impose administrative fines. The statutory maximum administrative fine is KRW 30 million (approximately USD 20,300 at current rates), materially lower than the EU AI Act Article 99 tiers. Penalty enforcement for certain provisions is postponed for a one-year grace period from the Act’s effective date.

**Definitional note.** The AI Basic Act definition of high-impact AI is structurally similar to the EU AI Act high-risk definition but narrower in certain respects. Generative AI is a named category with its own transparency obligations independent of the high-impact classification. Drafters should not assume one-to-one mapping between Korean and EU categories; each must be assessed against the operative definition.

**Coordination with PIPA.** The Personal Information Protection Act (PIPA) continues to apply to AI systems processing personal data of Korean residents. The AI Basic Act does not displace PIPA; governance for systems processing personal data must satisfy both regimes. The Korean Copyright Act lacks a text-and-data-mining exception, which creates training-data copyright exposure that is distinct from the EU TDM regime under the DSM Directive.

*People**’**s Republic of China.* Generative AI Service Regulations (2023) and Interim Administrative Measures for Generative AI Services impose content controls, security assessments and registration obligations for generative AI services offered in China. Additional rules apply in specific sectors including financial services and healthcare. Organizations offering AI services in China must conduct security assessments and file for approval before launch.

*Republic of Singapore.* Singapore does not have binding AI-specific legislation but operates a voluntary Model AI Governance Framework (PDPC, second edition) and the IMDA Model AI Governance Framework for Agentic AI. The PDPC also enforces the Personal Data Protection Act 2012 (PDPA), which applies to AI systems processing personal data of Singapore residents. Singapore’s approach is currently principle-based and sector-specific rather than horizontally legislative, but organizations operating in Singapore should monitor legislative developments and engage with voluntary frameworks that are increasingly referenced in procurement and commercial contracting.

*Japan.* Japan’s approach to AI governance has evolved significantly. The foundational governance instrument is the “Governance Guidelines for the Implementation of AI Principles,” published by the Cabinet Office in 2022, establishing a soft-law framework emphasizing human-centricity and international alignment. In April 2024, the Ministry of Economy, Trade and Industry (METI) and Ministry of Internal Affairs and Communications (MIC) consolidated earlier guidance into the “AI Guidelines for Business” (version 1.0), providing a practical framework for AI developers, providers and users structured around tiered responsibility. The guidelines were updated to version 1.1 in March 2025. On May 28, 2025, Japan’s Parliament enacted the Act on the Promotion of Research, Development and Utilisation of Artificial Intelligence-Related Technologies (AI Promotion Act), Japan’s first AI-specific legislation. The Act is a promotional rather than regulatory instrument: it establishes an AI Strategy Headquarters within the Cabinet, mandates a national Basic Plan for AI and imposes a duty on private sector businesses to “endeavor to cooperate” with government measures, but creates no hard regulatory obligations or penalties. Sector-specific requirements continue to apply in financial services and medical devices. Japan participated actively in the G7 Hiroshima AI Process (2023) and adopted the Hiroshima AI Process Code of Conduct for Advanced AI Systems. Organizations operating in Japan should monitor the evolution of the Basic Plan and any sector-specific guidance that flows from it.

*EU Liability Framework for AI: Revised Product Liability Directive.* The revised EU Product Liability Directive (Directive (EU) 2024/2853, published in the Official Journal on November 18, 2024, entered into force December 8, 2024, transposition deadline December 9, 2026) extends product liability to software and AI systems. Under the revised PLD, a defective AI system that causes death, personal injury or property damage gives rise to liability on the part of the manufacturer or importer without requiring the claimant to prove fault. Damage caused by a defect in an AI system’s training data or by an AI system that was not updated to address known risks may be treated as a product defect. Organizations developing or placing AI systems on the EU market must assess their exposure under the revised PLD as part of their AI governance and product liability frameworks.

*EU AI Liability Directive (Withdrawn).* The European Commission proposed an AI Liability Directive in September 2022 to establish a fault-based liability regime for AI-related harms. The Commission announced its intention to withdraw the proposal in its 2025 Work Programme (February 11, 2025), citing no foreseeable agreement among Member States. The formal withdrawal was published in the Official Journal on October 6, 2025. As of April 2026, there is no EU-level AI liability instrument in force or in active legislative progress. AI-related civil liability is currently addressed through the revised Product Liability Directive (Directive (EU) 2024/2853) for product defects and through national tort law for fault-based claims. The Commission has reserved the right to assess whether a new proposal or a different regulatory approach should be pursued. Organizations should monitor whether a replacement initiative is tabled, as the question of AI-specific fault-based liability remains unresolved at EU level.

Organizations must maintain a regulatory horizon-scanning process to identify and assess new AI regulations in operating jurisdictions as they are enacted and as enforcement postures develop.

## PART 13: TRAINING AND AWARENESS

### 13.1 Role-Appropriate Training

All personnel involved in developing, deploying or using AI systems must complete training appropriate to their role and the systems they work with. Training must address acceptable and prohibited uses, privacy and security requirements, accountability for AI outputs, how to recognize and report potential AI risks, how to apply risk controls and escalation protocols. Training must be role-based and proportionate to authority, with differentiated content for general users, managers, reviewers, System Owners, technical teams and control functions.

Training must be differentiated by role:

- **All employees:** AI Use Policy, basic acceptable use principles, incident reporting, human accountability for AI outputs.

- **System Owners and technical staff:** Impact classification methodology, TEVV requirements, risk assessment, lifecycle management, documentation requirements and regulatory obligations specific to the systems they own or build.

- **AI Governance Lead and governance functions:** Full framework including regulatory developments, audit methodology and cross-border compliance.

- **Senior leadership and Board:** AI governance posture, risk appetite setting, regulatory liability and board-level reporting on AI risk.

All employees must complete baseline AI governance training before using AI tools for work purposes. Managers are accountable for ensuring their teams have completed required training. Training must be refreshed at defined intervals and whenever significant regulatory or policy changes occur. Training materials must identify support channels for policy questions, verification concerns and escalation of suspected bias, misuse or system unreliability.

### 13.2 Recordkeeping

Completion of mandatory training must be recorded and monitored. Non-completion may result in restricted access to AI development tools, datasets or production environments until compliance is achieved. Training records must be available for audit and for regulatory inquiry.

For consequential uses of AI, the organization must define who is responsible for substantive verification before outputs are relied upon, communicated or implemented. That reviewer must be qualified in the relevant domain and must have sufficient authority to reject, correct or escalate the output.

## PART 14: DOCUMENTATION AND REGULATORY COMPLIANCE

### 14.1 AI System Inventory

The organization maintains a central inventory of all AI systems in use. Every system must be registered before deployment, including AI features embedded in business software where those features are actively used. The inventory records at minimum:

- System name and description.

- Provider and vendor information.

- System Owner.

- Business purpose and intended use.

- Out-of-scope uses.

- Impact classification.

- EU AI Act classification where applicable.

- Key lifecycle dates.

- Data types and sources.

- Oversight mode.

- Links to risk assessments and governance approvals for Medium and High Impact systems.

The designated Mechanism Owner maintains the inventory infrastructure. The AI Governance Lead reviews it periodically for completeness. The inventory serves as the primary tool for regulatory reporting and audit.

### 14.2 System Documentation Requirements by Classification

**Low Impact.** System purpose, System Owner, data inputs, classification rationale and responsible use acknowledgment.

**Medium Impact.** All Low Impact requirements. Risk assessment. Stakeholder impact assessment. TEVV results. Bias and fairness testing results. Security and privacy assessment. Approval records. Monitoring procedures and thresholds.

**High Impact.** All Medium Impact requirements. Comprehensive technical documentation per applicable regulatory requirements. Model card. Conformity assessment records where required. Independent validation report. Human oversight mode documentation and reviewer qualifications. Override procedure documentation. Societal impact assessment. Post-deployment review records. Incident history. For EU AI Act high-risk systems, technical documentation per Annex IV. Retained for a minimum of ten years from the date the system is placed on the market or put into service.

### 14.3 Regulatory Monitoring and Compliance

Legal and Compliance maintains a regulatory monitoring process covering AI regulations, data protection law and sector-specific requirements in all operating jurisdictions. The AI Governance Committee receives quarterly regulatory briefings. Legal and Compliance provides regular reporting on compliance status, regulatory changes and remediation of identified gaps. AI systems must comply with all applicable regulations in every jurisdiction where they operate. Where regulations differ, the most stringent applicable requirements apply.

## PART 15: ASSURANCE AND AUDIT

### 15.1 Internal Audit

Internal Audit conducts independent audits of AI governance compliance, covering risk management, lifecycle controls, procurement practices and operational procedures. The audit plan is risk-based, reflecting the composition and risk profile of the AI portfolio. Audit scope for each period is agreed with the AI Governance Committee. Findings are reported to the Governance Committee. Corrective actions are assigned, tracked and verified until resolved.

### 15.2 External Validation

High Impact AI systems require periodic independent external validation to provide objective assessment of system performance and compliance. External validation is distinct from internal audit and provides assurance not subject to organizational bias. For EU AI Act high-risk AI systems, conformity assessment may require involvement of a notified body depending on the system category.

### 15.3 Continuous Monitoring

Assurance is not limited to periodic audits. Continuous monitoring mechanisms, operated by the second line, provide ongoing assurance between formal audit cycles. Assurance activities include automated compliance checks, monitoring dashboard review, threshold breach reporting and governance documentation completeness checks.

## PART 16: CONTINUOUS IMPROVEMENT

The risk management framework and governance policies must evolve with changing technologies, use cases and regulatory expectations. The AI Operational Committee reviews emerging AI risk types and control approaches on a regular basis. Lessons learned from internal incidents, external case studies, audits and stakeholder feedback inform periodic revisions to the risk taxonomy, scoring and prioritization models and the control strategy catalogue.

The organization participates in industry initiatives, standards development and regulatory consultations relevant to AI governance, contributing to the improvement of industry practice and maintaining awareness of evolving expectations.

## PART 17: EXCEPTIONS

Requests for exceptions to any AI governance policy must be documented and submitted to the AI Governance Lead (for Low and Medium Impact systems) or the AI Governance Committee (for High Impact systems) before the excepted activity commences. Each request must include:

- Business justification.

- Risk assessment of the exception.

- Alignment with the organization’s risk appetite.

- Any compensating controls to be implemented.

- Proposed duration of the exception.

The Governance Committee may grant temporary or conditional exceptions where overall risk remains acceptable. Exceptions are time-limited, subject to review and recorded in the Risk Register as tracked items. No exception may authorize an activity falling within the Prohibited Uses category. Exception patterns are reviewed at least annually to identify where policy adjustment may be warranted.

## PART 18: GOVERNANCE DOCUMENT HIERARCHY AND REVIEW

### 18.1 Document Hierarchy

A complete AI governance framework comprises the following layered documents:

**AI Governance Charter.** One-page executive commitment, classification scheme, authority structure and escalation triggers. Approved by the Board or equivalent. Reviewed quarterly.

**AI Governance Policy.** Full framework document defining principles, structures, roles, decision authorities and expectations for supporting policies. Approved by the CTO or equivalent. Reviewed annually.

**AI Risk Management Policy.** Operational processes for risk identification, assessment, treatment and monitoring. Implements the risk management requirements of the Governance Policy. Approved by the CTO or equivalent. Reviewed annually.

**AI Use Policy.** Practical guidance for all personnel on permitted, prohibited and cautioned uses of AI tools. Governs employee behavior. Approved by the CTO or equivalent. Reviewed annually.

**Supporting Standards and Playbooks.** Detailed operational guidance on specific topics such as bias testing methodology, model documentation standards, incident response procedures and TEVV guidance. Must be consistent with the policies above. Owned by the AI Governance Lead or designated Mechanism Owners. Reviewed as required by operational need and regulatory change.

### 18.2 Review Cadence

Any document may be updated outside the regular cycle when significant technological, regulatory or organizational changes occur. Substantive revisions require approval at the same level as original approval and must be communicated to all affected stakeholders. The AI Governance Committee reviews the full document hierarchy at least annually for coherence and completeness.

## PART 19: EU AI ACT OBLIGATIONS BY ACTOR TYPE

Organizations must determine their position in the EU AI Act’s actor classification before designing their compliance program. Actor type determines which obligations apply. Most organizations will be deployers of third-party AI systems, providers of systems they develop themselves, or both simultaneously for different systems in their portfolio.

### 19.1 Provider Obligations (High-Risk AI Systems)

A provider places a high-risk AI system on the market or puts it into service under its own name or trademark. Providers bear the primary technical compliance burden under Chapter III, Section 2. Core obligations include:

- Establish and maintain a risk management system throughout the system lifecycle (Article 9).

- Apply data and data governance requirements to training, validation and test datasets (Article 10).

- Draw up technical documentation per Annex IV before placing the system on the market (Article 11).

- Design the system to automatically generate logs of operation to the degree appropriate to its intended purpose (Article 12 and Article 19).

- Design the system to be sufficiently transparent to deployers, including providing instructions for use covering intended purpose, performance metrics, human oversight measures and expected operational lifetime (Article 13).

- Design the system to enable effective human oversight by natural persons (Article 14).

- Design the system to achieve appropriate levels of accuracy, robustness and cybersecurity (Article 15).

- Fulfill general provider obligations including affixing the CE marking where applicable, drawing up the EU declaration of conformity, cooperating with market surveillance authorities and implementing a post-market monitoring system (Article 16).

- Establish and maintain a Quality Management System (Article 17(see Part 6.7)).

- Keep technical documentation for at least ten years from the date the system is placed on the market (Article 18).

- Register the system in the EU database before market placement (Article 49(see Part 6.8)).

- Conduct conformity assessment (Article 43).

- Report serious incidents (Article 73).

### 19.2 Deployer Obligations (High-Risk AI Systems)

A deployer uses a high-risk AI system under its own authority in the EU. Core deployer obligations include:

- Use the system only in accordance with the provider’s instructions for use (Article 26(1)).

- Assign human oversight responsibilities to natural persons with the competence, authority and resources necessary to fulfill that oversight role (Article 26(2)).

- Ensure input data is relevant and representative for the system’s intended purpose, to the extent data is under the deployer’s control (Article 26(3)).

- Monitor the operation of the system on the basis of the instructions for use and inform the provider of serious risks or incidents identified (Article 26(4)).

- Keep automatically generated logs for at least six months unless otherwise required by applicable law (Article 26(5)).

- Conduct a Fundamental Rights Impact Assessment before first use where required (Article 27(see Part 20)).

- Register use of the system in the EU database where required (Article 49).

Deployers do not bear primary technical conformity obligations, but they do bear responsibility for the appropriateness of deployment and human oversight. A deployer that modifies a system or deploys it outside its intended purpose may become a provider with the full provider obligation stack (Article 25(see Part 10.5)).

### 19.3 Organizations That Are Both Provider and Deployer

Many organizations will simultaneously be providers of some AI systems (those they develop) and deployers of others (those they acquire). For each AI system in the portfolio, the organization must determine which obligations apply and assign compliance responsibility accordingly. The AI system inventory (Part 14.1) must record the organization’s actor designation for each system. Where the organization is both provider and deployer of the same system (developed in-house and deployed internally), provider obligations apply in full.

### 19.4 GPAI Model Provider Obligations

Organizations providing GPAI models face an additional and distinct obligation set under Chapter V. Core obligations include:

- Draw up and maintain technical documentation for the model.

- Provide downstream providers with information and documentation sufficient to enable them to understand the model’s capabilities and limitations and to comply with their own obligations.

- Establish and implement a policy to respect EU copyright law, including making available a machine-readable summary of training data content.

- Publish a sufficiently detailed public summary of training data content using the AI Office template.

- Cooperate with the AI Office and national competent authorities.

GPAI models with systemic risk (training compute exceeding 10^25 FLOPs, or designated by the Commission) face additional obligations:

- Perform model evaluations including adversarial testing.

- Assess and mitigate systemic risks at Union level from the model’s development, placement on the market and use.

- Track, document and report serious incidents and corrective measures to the AI Office and relevant national competent authorities.

- Ensure adequate cybersecurity protection for the model, its training infrastructure and its deployment environment.

- Notify the AI Office within two weeks of reaching or reasonably foreseeing that the model will reach the 10^25 FLOPs threshold.

## PART 20: FUNDAMENTAL RIGHTS IMPACT ASSESSMENT

The Fundamental Rights Impact Assessment (FRIA) is a mandatory pre-deployment obligation for specific deployer categories under EU AI Act Article 27. It is distinct from the internal risk assessment required under Article 9 and from the DPIA required under GDPR Article 35. Each addresses a different dimension of impact.

### 20.1 Who Must Conduct a FRIA

The FRIA obligation applies to deployers that are:

- Bodies governed by public law or private entities providing public services (covering all Annex III high-risk AI systems except those used as safety components in critical infrastructure management (road traffic, water, gas, heating or electricity supply)).

- Deployers using AI systems for creditworthiness evaluation, credit scoring or risk assessment and pricing in life and health insurance (referenced in Annex III points 5(b) and (c)), regardless of whether the deployer is a public body.

Private sector organizations not providing public services and not operating in credit or insurance AI contexts are not required by Article 27 to conduct a FRIA, though doing so as a voluntary governance measure is encouraged for High Impact systems.

### 20.2 When a FRIA Must Be Conducted

The FRIA must be conducted before the first use of the high-risk AI system. A deployer may, in similar subsequent deployment contexts, rely on a previously conducted FRIA if the circumstances are substantially the same. If any element of the assessment changes materially (the system, the deployment context, the affected population or the available oversight measures) the FRIA must be updated before continued use.

### 20.3 Required FRIA Content

EU AI Act Article 27(1) specifies six required elements:

- A description of the deployer’s processes in which the high-risk AI system will be used in line with its intended purpose.

- A description of the period of time within which and the frequency with which the system is intended to be used.

- The categories of natural persons and groups likely to be affected by its use in the specific deployment context.

- The specific risks of harm likely to have an impact on the affected categories of persons, taking into account information provided by the provider under Article 13.

- A description of the implementation of human oversight measures according to the instructions for use.

- The measures to be taken if identified risks materialize, including internal governance arrangements and complaint mechanisms.

### 20.4 FRIA and DPIA Coordination

Where a high-risk AI system requires both a FRIA under Article 27 and a DPIA under GDPR Article 35, the two assessments may be conducted together within a single document, provided all relevant elements of both are addressed. If a DPIA has already been conducted, the FRIA must complement it rather than duplicate it. Organizations with mature DPIA processes should extend their DPIA methodology to cover the additional FRIA elements rather than operating two entirely separate processes.

### 20.5 Notification to Market Surveillance Authority

Once the FRIA is completed, the deployer must notify the competent market surveillance authority of the results by submitting the completed template provided by the AI Office. This is a mandatory external notification, not merely an internal document. Exemptions from the notification obligation apply in limited circumstances defined in Article 46.

### 20.6 FRIA Governance Integration

Organizations subject to the FRIA obligation must:

- Integrate FRIA into the pre-deployment governance gate for qualifying systems.

- Assign FRIA ownership to the System Owner with Legal and Compliance input.

- Coordinate FRIA with DPIA processes to avoid duplication.

- Maintain FRIA records as part of the system’s governance documentation file.

- Track FRIA notification submissions and any authority responses.

- Include FRIA status in the AI system inventory for all qualifying systems.

A minimum content checklist for the FRIA is provided in Appendix F.

## PART 21: ENFORCEMENT ARCHITECTURE AND PENALTY FRAMEWORK

### 21.1 EU AI Act Enforcement Architecture

Enforcement under the EU AI Act is distributed across three layers.

**The EU AI Office.** Established within the European Commission, the AI Office has direct enforcement authority over providers of GPAI models. It can conduct investigations, issue decisions and impose fines on GPAI model providers under Article 101. The AI Office also coordinates cross-border enforcement among national authorities and maintains the GPAI model registry.

**National Market Surveillance Authorities.** Each EU Member State designates national market surveillance authorities responsible for enforcing AI Act requirements for high-risk AI systems within their jurisdiction. These authorities can: conduct market surveillance and inspections; require providers and deployers to provide documentation; order corrective actions including withdrawal or recall; impose fines within the limits set by Article 99; and refer matters to the AI Office where GPAI models are involved. The national authority with primary jurisdiction is generally the authority of the Member State where the serious incident occurred or where the provider is established.

**Notified Bodies.** Accredited conformity assessment bodies designated by Member States to conduct third-party conformity assessments for AI systems in categories requiring such assessment (primarily biometric identification systems and other categories specified under Annex VII). Notified bodies are not enforcement authorities but play a gatekeeping role in the market access pathway for certain high-risk AI systems.

### 21.2 Fine Structure: EU AI Act Article 99

Fines under the EU AI Act are structured in three tiers. All tiers use a “higher of” calculation (amount or percentage of worldwide annual turnover) except for SMEs, for which the “lower of” calculation applies.

**Tier 1: Prohibited Practices (Article 99(3)).** Non-compliance with Article 5 prohibited practices is subject to administrative fines of up to €35,000,000 or, if the offender is an undertaking, 7% of total worldwide annual turnover for the preceding financial year, whichever is higher.

**Tier 2: Other Operator and Notified Body Obligations (Article 99(4)).** Non-compliance with obligations of providers (Article 16), authorized representatives (Article 22), importers (Article 23), distributors (Article 24), deployers (Article 26) and notified bodies (Article 31) is subject to administrative fines of up to €15,000,000 or 3% of total worldwide annual turnover for the preceding financial year, whichever is higher.

**Tier 3: Incorrect Information (Article 99(5)).** Supplying incorrect, incomplete or misleading information to notified bodies or national competent authorities is subject to administrative fines of up to €7,500,000 or 1% of total worldwide annual turnover for the preceding financial year, whichever is higher.

**GPAI Model Providers (Article 101).** Providers of GPAI models that intentionally or negligently infringe their obligations may be subject to fines of up to €15,000,000 or 3% of total worldwide annual turnover, whichever is higher.

**SME modifier.** For SMEs and start-ups, fines apply up to the lower of the percentage and the stated amount, rather than the higher.

**Calibration factors.** When setting fine amounts, competent authorities must consider: the nature, gravity and duration of the infringement; the number of affected persons and level of damage; whether the offender has cooperated with authorities; prior infringements; any financial benefit obtained; and the level of damage caused to the public interest.

**Non-monetary enforcement.** Fines are not the only enforcement tool. Competent authorities may also: order corrective actions to bring systems into compliance; require temporary limitation or suspension of market access; order withdrawal or recall of non-compliant systems from the market; and issue public warnings. Reputational and operational consequences of enforcement actions often exceed the financial penalty.

**Enforcement timeline.** The penalty tiers attach to their corresponding obligations as those obligations enter application; confirm the current schedule against the primary source.

### 21.3 Regulatory Sandbox Safe Harbor

EU AI Act Articles 57 to 63 establish a framework for AI regulatory sandboxes. Supervisory authorities in Member States may establish sandboxes providing a controlled environment for providers and prospective providers to develop, train, test and validate innovative AI systems under regulatory supervision before market placement. Participating in a sandbox does not provide immunity from liability for harm caused during testing, but does provide access to regulatory guidance and a degree of regulatory engagement that can reduce compliance uncertainty for novel AI applications. Organizations developing innovative AI systems that are uncertain about their regulatory classification should consider sandbox participation as part of their compliance strategy.

## PART 22: AI GOVERNANCE MATURITY MODEL

### 22.1 Purpose of the Maturity Model

Not every organization can implement the full governance program described in this reference simultaneously. The maturity model provides a structured pathway for phased implementation, enabling organizations to prioritize foundational controls, build toward systematic governance and ultimately achieve continuous assurance. Drafters using this reference to produce governance documents should calibrate requirements to the organization’s current maturity level while setting a realistic target state.

### 22.2 Maturity Levels

**Level 1: Foundation (Ad Hoc Governance).** AI use occurs but governance is informal. No AI system inventory. No defined roles. Acceptable use is based on personal judgment rather than policy. No structured incident reporting. Risk awareness is present among some individuals but is not systematized. The organization is exposed to significant untracked risk and is not prepared to demonstrate compliance to a regulator or auditor.

Minimum actions to exit Level 1: adopt an AI Use Policy; designate an AI Governance Lead; create an initial AI system inventory; establish a basic incident reporting channel.

**Level 2: Developing (Defined Governance).** Key governance documents exist (AI Governance Policy or equivalent, AI Use Policy). An AI Governance Lead is appointed. AI system inventory is maintained but may be incomplete. Impact classification exists but is applied inconsistently. Incident reporting exists but uptake is limited. Training has been delivered at least once but is not role-differentiated or refreshed. Regulatory requirements have been identified but compliance gaps remain unaddressed.

Minimum actions to exit Level 2: complete the AI system inventory; apply impact classification consistently to all systems; implement role-differentiated training; conduct an internal audit of the governance framework; address the most significant regulatory compliance gaps identified.

**Level 3: Established (Systematic Governance).** Full governance document suite in place and updated regularly. Impact classification applied consistently with documented rationale. Risk assessments conducted for all Medium and High Impact systems. TEVV activities conducted at each lifecycle stage. Incident management is active and near-misses are captured. Regulatory compliance has been assessed across all operating jurisdictions. Internal audit of AI governance has been conducted. Human oversight modes are assigned and documented for all systems. The governance framework is known and followed across the organization.

Minimum actions to exit Level 3: implement continuous monitoring for deployed systems; integrate AI governance into procurement and vendor management; establish external validation for High Impact systems; implement post-market surveillance; achieve documented regulatory compliance across all major obligations.

**Level 4: Advanced (Integrated Governance).** Governance is integrated into product development, procurement and commercial processes rather than operating as a parallel compliance function. Continuous monitoring is automated where possible. Risk posture reporting flows to Board level on a regular cadence. Incident management closes the loop into risk assessment and control improvement. External validation is routine for High Impact systems. Regulatory horizon-scanning is active and systematic. Third-line assurance (Internal Audit) has validated the governance program. The organization could respond effectively and promptly to a regulatory inquiry or market surveillance inspection.

Minimum actions to exit Level 4: achieve repeatable, measured governance performance against defined metrics; embed governance improvement as a standing agenda item at the AI Governance Committee; implement governance process automation where feasible; document lessons learned from each significant incident and integrate them into the framework.

**Level 5: Optimizing (Continuous Assurance).** Governance is data-driven and continuously improving. The organization contributes to industry governance standards and regulatory consultations. AI risk posture is quantified and reported with meaningful metrics. Governance cycle time is measured and improving year-over-year. Incidents and near-misses produce documented improvements to controls and training. External validation is scheduled and integrated into the product lifecycle. The organization can demonstrate, through evidence rather than assertion, that its AI systems are safe, secure and lawful.

### 22.3 Using the Maturity Model in Drafting

When drafting AI governance policies for an organization at Level 1 or Level 2, prioritize the minimum actions to exit those levels over comprehensive compliance with all requirements in this reference. A governance policy that is too ambitious for the organization’s current capacity will not be implemented and provides no real protection. Design for achievable compliance first, build toward best practice over time. Flag aspirational requirements as future-state provisions with target dates.

### 22.4 The Operational Catechism

The maturity model in Part 22.2 describes the organization-level posture. The operational catechism described in this subsection is a system-level diagnostic. It is administered to each deployed AI system in scope and produces a binary read on whether the governance for that system is operational or performative. An organization can be at Level 3 in the maturity model and still fail the catechism for individual systems. The catechism is therefore complementary to the maturity model, not a substitute for it.

The diagnostic consists of five questions. Each must be answered in writing, with a named owner and a current reference, for the specific system being assessed. The questions are deliberately short. They are deliberately concrete. They cannot be satisfied by citing policy.

- Who owns the model.

- Who owns the use case.

- Who can stop the system.

- Where is the evidence.

- What happens when the output is wrong, biased, unlawful or impossible to explain.

**Question 1: Who owns the model.** The technical artifact (the trained system, the configured deployment, the version currently in production) must have a named owner with authority to decide whether it should be in production at all. Vendor ownership of the model, technical configuration by the data science team, use by the deploying business unit and operation by the IT function are inputs to ownership but are not the same as ownership. Ownership is a single named individual responsible for the in-production state of the technical artifact.

**Question 2: Who owns the use case.** A single model may be deployed across multiple use cases with different risk profiles and different acceptable outputs. Use case ownership is responsibility for whether this model in this application is appropriate. Question 2 has a different correct answer than Question 1 in most agentic deployments; conflation of the two is a governance failure mode the catechism is designed to surface.

**Question 3: Who can stop the system.** The named individual or role must combine practical authority and immediate technical access to halt the system in production. Authority without access cannot halt. Access without authority is not permitted to halt. Where neither sits in the same place, the organization cannot govern the system. The answer should reference the documented stop mechanism (Part 9.3 stop conditions; Part 11 human oversight) and the named role authorized to invoke it.

**Question 4: Where is the evidence.** The operational record sufficient to reconstruct what the system did, when, with what data and with what outcome must be preserved in a form independent of the system that produced it. The standard of preservation is that of the demand that anticipates it: regulator, auditor, litigant or enterprise client. The answer must reference the specific evidence pipeline (Part 6 lifecycle records; Part 9.4 agentic action logs; Part 14 documentation; Part 15 assurance) and confirm that the records are current.

**Question 5: What happens when the output is wrong, biased, unlawful or impossible to explain.** The four conditions are not interchangeable. A wrong output is a quality problem (Part 4.2 Principle 1; Part 5 TEVV). A biased output is a fairness problem (Part 4.2 Principle 2). An unlawful output is a regulatory problem (Part 14 documentation; Part 21 enforcement). An unexplainable output is a transparency problem (Part 4.2 Principle 3). The answer must specify the differentiated response procedure for each condition; a generic incident response that does not differentiate among them does not satisfy the question.

**Reading the diagnostic.** A system whose owners can answer all five questions in writing, with current references and named owners, with answers that survive a second asking, is operating at the level the present moment requires. A system whose owners cannot, or whose answers shift between askings, has a governance gap that the next material incident will reveal. The diagnostic is administered by the AI Governance Lead and recorded in the AI system inventory (Part 14.1) for each High Impact and each Medium Impact system. The General Counsel function (Part 3.5.1) reviews the catechism record as part of the binding work that produces Final Liability for the system.

**Relationship to the maturity model.** The catechism is the system-level test for what the maturity model describes at the organization level. An organization at Level 1 or Level 2 will fail the catechism for most or all systems. An organization at Level 3 should pass for High Impact systems and may pass for Medium Impact systems. An organization at Level 4 should pass for all in-scope systems with current references. An organization at Level 5 should pass with current references and should also produce the readiness-for-the-asking artifacts (Part 3.5.1) that allow the catechism record to be presented to a third party without preparation.

## PART 23: AI GOVERNANCE IN TRANSACTIONS AND DUE DILIGENCE

### 23.1 Purpose

Mergers, acquisitions, investments, partnerships and outsourcing transactions increasingly involve AI systems as material assets, liabilities or operational dependencies. A counterparty’s AI governance posture can create significant acquired risk (regulatory exposure, product liability, reputational harm and operational disruption) that is not visible in conventional financial or legal due diligence. AI governance due diligence must be integrated into transaction processes proportionate to the AI exposure involved.

### 23.2 AI Due Diligence Framework for Transactions

**AI system inventory review.** Obtain and review the target’s AI system inventory. Assess completeness: are all AI systems, including embedded AI features in third-party software, captured? Assess classification: are impact classifications defensible and documented? Identify any systems not in the inventory but apparent from operational review.

**Regulatory exposure assessment.** For each AI system in scope: what is the organization’s actor designation (provider, deployer, both)? Does any system fall within the EU AI Act Annex III high-risk category, or within prohibited practices under Article 5? Has any system been subject to regulatory inquiry, market surveillance contact or incident reporting? Are there open enforcement actions or pending regulatory notifications?

**Governance documentation review.** Does the target maintain an AI governance policy suite? Are policies current and evidence-based? Is there evidence of policy implementation (training records, audit findings, risk assessments)? Are there unresolved audit findings? Has a conformity assessment been conducted for any high-risk AI systems? Are QMS obligations under Article 17 fulfilled where applicable?

**AI-related liability review.** Has the target been party to any litigation, regulatory action or settlement involving AI systems? Are there contractual representations or warranties regarding AI performance or compliance that may require disclosure? Does the target’s AI indemnification posture in vendor contracts create transferred liability that would survive the transaction?

**Third-party AI dependencies.** Which of the target’s AI capabilities are dependent on third-party providers, GPAI model providers or data vendors? Are those dependencies documented and subject to appropriate contractual protections? Would a change of control trigger termination or renegotiation rights in AI vendor contracts? Are there single points of failure in the AI supply chain?

**Data governance.** What training data has been used to develop the target’s AI systems? Is there documented evidence of lawful data sourcing for AI training? Are there unresolved intellectual property or privacy concerns with training data?

### 23.3 Representations and Warranties in AI Transactions

When acquiring AI-enabled businesses or material AI assets, the transaction documentation should include representations and warranties specifically covering:

- Accuracy and completeness of the AI system inventory.

- Compliance with applicable AI regulations in all operating jurisdictions.

- Absence of AI Act Article 5 prohibited practices.

- Conformity assessments conducted for all high-risk AI systems requiring them.

- Absence of regulatory inquiries, market surveillance contacts or enforcement actions related to AI systems.

- Accuracy of AI system documentation and technical documentation.

- Absence of material incidents not previously disclosed.

- Lawfulness of training data sourcing.

The appropriate scope of AI representations and warranties will depend on the materiality of AI to the transaction. In transactions where AI is a primary value driver, AI-specific indemnities and escrow arrangements may be warranted.

### 23.4 Post-Transaction Integration

Following an acquisition involving AI systems, the acquiring organization must:

- Integrate the acquired AI system inventory into the organization’s master inventory promptly.

- Apply the organization’s impact classification methodology to all acquired systems.

- Assess acquired systems against the organization’s governance standards and identify remediation requirements.

- Determine whether any acquired systems trigger new regulatory obligations for the organization as a combined entity.

- Assess whether any acquired AI vendor contracts need to be renegotiated to meet the organization’s contractual standards.

- Complete training for personnel joining from the acquired entity.

- Set a target date for full governance integration and track progress against it.

## PART 24: GENERAL-PURPOSE AI RISK-MANAGEMENT STANDARDS PROFILE

**Source and posture.** The UC Berkeley Center for Long-Term Cybersecurity General-Purpose AI Risk-Management Standards Profile (Profile v1.2, March 2025) is a non-EU-jurisdictional risk-management profile that operationalizes the NIST AI RMF (and adjacent frameworks including ISO/IEC 42001 and the EU AI Act GPAI provider obligations) specifically for general-purpose AI models and general-purpose AI systems. It is treated in this reference as the principal source of GPAI-specific risk-management content: a working document that GPAI providers and downstream deployers can use to structure their internal risk-management activities, supplying granular activity- and documentation-level guidance across the GOVERN, MAP, MEASURE and MANAGE functions for general-purpose AI models and systems wherever they are deployed.

**Structural alignment.** The Profile is organized around the four NIST AI RMF core functions (GOVERN, MAP, MEASURE, MANAGE) and specifies activities and documentation expectations for each function as adapted to the GPAI context. It operationalizes the underlying risk-management discipline in standards form, which a GPAI provider can use to structure the internal risk-management work that any applicable compliance regime will expect to see evidenced.

**Use as a drafting source.** Drafters using this reference for organizations that develop or integrate GPAI models should treat the Profile as a source for: (a) GPAI-specific MAP activities (system characterization, capability assessment, foreseeable misuse identification); (b) GPAI-specific MEASURE activities (evaluation methodology, red-teaming and adversarial testing, model evaluation reporting); (c) GPAI-specific MANAGE activities (risk treatment, post-market monitoring, incident response calibrated to GPAI failure modes); and (d) GPAI-specific GOVERN activities (model cards, system cards, documentation expectations and roles).

**Adopter’s checklist.** Organizations using the Profile in operational form should maintain an Adopter’s Checklist that tracks each Profile activity item to the organization’s internal documentation, evidence and named owner. The Adopter’s Checklist functions analogously to a Statement of Applicability under ISO/IEC 42001 (Appendix G); the form is similar but the source is the Profile rather than a regulatory or certification instrument. The companion Audit and Due Diligence Checklist to this reference includes Profile-aligned questions where applicable.

**Versioning note.** The Profile version current at the time of this reference is v1.2 (March 2025). Drafters should verify the current version at the time of use and treat the Profile as a living document, similar in pace of evolution to the underlying NIST AI RMF. Where the Profile is updated and the organization’s existing documentation refers to a prior version, the inventory record (Part 14.1) should capture the version the documentation was developed against and the date of the most recent gap review.

## PART 25: SYNTHESIZING REFERENCE WORKS

This Part covers two synthesizing reference works produced by the Center for Security and Emerging Technology (CSET) at Georgetown University. Both are integrated into this file as drafting and navigation references rather than as sources of binding obligations. Binding obligations remain in the underlying statutes, regulations and standards that CSET synthesizes. Both works are organized in companion form: Source \#7 distills 52 guidance documents into a harmonized framework; Source \#8 maps that framework to action-subject pairs across an 18-stage AI adoption lifecycle. Drafters should treat the two together as the synthesizing layer of the literature available to this file’s users.

### 25.1 CSET Harmonizing AI Guidance (Source \#7)

**Citation.** Crichton, K., Reddy, A., Ji, J., Crawford, A., Hoffmann, M., Shea-Blymyer, C. and Bansemer, J., “Harmonizing AI Guidance: Distilling Voluntary Standards and Best Practices into a Unified Framework,” Center for Security and Emerging Technology, Issue Brief, September 2025. doi 10.51593/20240041. Licensed CC BY-NC 4.0.

**Authority tier.** Synthesizing reference work. Builds on but does not displace the underlying source documents. Treat as a navigation and reading aid rather than as a source of binding obligations. Binding obligations remain in the underlying statutes, regulations and standards CSET synthesizes.

**Scope.** Distillation of 7,741 recommendations from 52 guidance documents into 258 harmonized practices. Source set spans the United States, the United Kingdom, the European Union, Japan and Singapore; international bodies, government agencies, standards-setting organizations, industry associations, think tanks, academic institutions and private companies. Practices organized into five categories (Governance, Safety, Security, Privacy, Detection and Response) and 34 topic areas. Each harmonized recommendation carries an AI Score indicating the proportion of source recommendations from AI-specific reports versus the broader cybersecurity, privacy and risk-management literature.

**Use in this Master Reference.** Cross-reference at Part 1 (Foundations) where the harmonized framework provides empirical grounding for the convergence claim. Cross-reference at Part 3 (Roles and Responsibilities) where CSET maps functional roles to AI governance responsibilities across 19 C-suite roles. Cross-reference at Part 5 (TEVV) where the Test and Evaluation, Performance Monitoring and Traceability topic clusters in CSET correspond to Part 5 substance in this file. Cross-reference at any Part where the harmonized framework’s treatment of a specific control deepens or competes with this file’s doctrine. Note also the AI Score field for each harmonized recommendation: high AI Score signals that the practice is principally established in AI-specific literature; low AI Score signals the practice is established in broader cybersecurity, privacy or risk-management literature and applies to AI by extension.

**Caveats.** CC BY-NC 4.0. Light citation under fair use is fine in commercial book context. Heavy structural reuse, for example building a parallel crosswalk on the CSET five-category and 34-topic taxonomy, may require explicit reuse permission from CSET. The framework excludes binding regulation and legislation; following CSET’s harmonized recommendations does not ensure compliance with applicable law. Source set is a 2025 snapshot and will be superseded as new guidance is published. Cite structurally rather than as “current as of \[date\].”

### 25.2 CSET Operationalizing AI Guidance (Source \#8)

**Citation.** Crichton, K., Reddy, A. and Ji, J., “Operationalizing AI Guidance: A Reference Guide for Translating High-Level Goals into Practical Implementation,” Center for Security and Emerging Technology, April 2026. doi 10.51593/20250002. License to be confirmed at integration time; CSET typically uses CC BY-NC 4.0 for issue briefs.

**Authority tier.** Implementation reference work. Phase 2 of CSET’s three-phase Harmonize, Operationalize, Tailor research plan; the operational companion to Source \#7. Treat as a control-design reference, not a checklist to adopt wholesale.

**Scope.** Maps the 258 harmonized practices in Source \#7 to 232 distinct action-subject pairs derived from 814 raw pairs. Action-subject pairs are organized across an 18-stage AI adoption lifecycle: Self-Assess, Define, Plan, Promote, Map, Assess, Acquire, Develop, Control, Protect, Test, Approve, Communicate, Deploy, Engage, Monitor, Respond, Improve. Implementation level (Organization, Operations, Workforce, Infrastructure, Data, Model, System) and functional-team ownership across 19 C-suite roles assigned per implementation step.

**Use in this Master Reference.** Cross-reference at the OPERATIONAL CADENCE section above where the SPECIFY, STATE, RUN, DEFEND verbs have direct counterparts in CSET’s 18-stage lifecycle. Cross-reference at Part 4 (Risk Management) where the Plan, Map and Assess stages map to risk identification, classification and assessment. Cross-reference at Part 5 (TEVV) where the Test, Approve, Monitor and Respond stages map directly to TEVV cadence. Cross-reference at Part 6 (Model and Data Lifecycle Management) where CSET’s Traceability cluster (data provenance, version control, system documentation, auditability, data quality, evaluation documentation) operationalizes the model-card minimums in Part 6.4. Cross-reference at Part 22.4 (Operational Catechism) where CSET’s implementation steps are a parallel diagnostic surface to the catechism’s five questions.

**Caveats.** Same license posture as Source \#7 pending verification of the Operationalizing brief’s specific terms at first chapter-drafting use. Source set focuses on voluntary standards and best practices; binding compliance obligations remain in applicable statutes and regulations. Cite structurally per the date-insensitivity standard.

## PART 26: ASSURANCE FRAMEWORKS AND METHODOLOGICAL REFERENCE WORKS

This Part covers three reference works that supply the conceptual and methodological scaffolding for AI assurance, distinct from the binding regulatory instruments treated in Part 1.2 and from the synthesizing reference works treated in Part 25. The works covered here are: the UK government’s foundational guidance on AI assurance as a discipline (Source \#9); the engineering-grade structured-argument notation that has organized assurance work in safety-critical industries for three decades (Source \#10); and foundational scholarship on internal algorithmic auditing that adapts the discipline to AI (Source \#11). Drafters should treat these as the conceptual and methodological layer beneath the regulatory and synthesizing layers. Binding obligations remain in the underlying statutes, regulations and standards.

### 26.1 UK DSIT Introduction to AI Assurance (Source \#9)

**Citation.** UK Department for Science, Innovation and Technology, Introduction to AI Assurance, Crown copyright, published 12 February 2024. Open Government Licence v3.0.

**Authority tier.** Foundational government guidance from a peer regulatory jurisdiction. Not binding; describes the AI assurance discipline and the UK pro-innovation regulatory framing as of early 2024. UK regulatory posture has evolved since publication; drafters should verify current UK approach at integration time.

**Scope.** Introduces AI assurance as the process of measuring, evaluating and communicating the trustworthiness of AI systems. Establishes the Trust / Trustworthiness / Justified Trust trio (see Part 1.3 definitions). Sets out the UK five cross-sectoral principles (Safety, Security and Robustness; Appropriate Transparency and Explainability; Fairness; Accountability and Governance; Contestability and Redress). Surveys six assurance mechanisms (risk assessment, algorithmic impact assessment, bias audit, compliance audit, conformity assessment, formal verification) and five types of technical standards (foundational and terminological, interface and architecture, measurement and test methods, process and management and governance, product and performance requirements). Maps the AI assurance ecosystem (regulators, accreditation bodies, government, standards bodies, research bodies, civil society organizations, professional bodies).

**Use in this Master Reference.** Cited as the conceptual source for the Trust / Trustworthiness / Justified Trust trio in Part 1.3. Provides the cross-sectoral principles for cross-jurisdictional regulatory crosswalk drafting. Provides the six-mechanism taxonomy as a reference structure for Part 5 (TEVV) and Part 15 (Assurance and Audit) drafting. Useful as a peer-jurisdiction anchor for organizations drafting governance documents intended to be defensible across multiple jurisdictions.

**Caveats.** Pro-innovation framing of early 2024; UK posture has shifted under subsequent government changes. Cite structurally per the date-insensitivity standard. Open Government Licence v3.0 permits commercial reuse with attribution.

### 26.2 GSN Community Standard, Version 3 (Source \#10)

**Citation.** SCSC Assurance Case Working Group, Goal Structuring Notation Community Standard, Version 3, SCSC-141C, May 2021. Creative Commons Attribution 4.0 International (CC BY 4.0). Available at scsc.uk/SCSC-141C.

**Authority tier.** Community-developed standard maintained by the Safety-Critical Systems Club Assurance Case Working Group. Originated at the University of York in the early 1990s. Used in aerospace, rail, defense, nuclear and medical-device industries for safety and assurance cases. Increasingly adapted for AI assurance through the Alan Turing Institute and the University of York Assuring Autonomy programs. Not binding; widely adopted as a notation rather than as a regulation.

**Scope.** Defines the Goal Structuring Notation as a notation for documenting structured engineering arguments. Core elements: goals (claims to be supported), strategies (the reasoning steps that decompose claims into sub-claims), solutions (references to evidence supporting claims), contexts (the conditions under which claims are made), assumptions (statements taken as given for the argument to hold) and justifications (the basis on which strategies or claims are stated). Provides a Six-Step Method for top-down development of goal structures, a Bottom-Up Method for evidence-driven development, modular extensions for large arguments, confidence-argument extensions and dialectic extensions for adversarial arguments. Identifies common errors in argument structures (language ambiguity, vagueness, oversimplification, jumping ahead, leaps of faith).

**Use in this Master Reference.** Cited as the engineering-grade notation that AI assurance is converging toward. The core elements of GSN map directly onto the Assurance Case definition in Part 1.3. Provides the structuring methodology for Fundamental Rights Impact Assessments under EU AI Act Article 27 (see Part 20 and Appendix F): a properly maintained FRIA is a domain-specific assurance case for fundamental rights claims. Provides the structuring methodology for Algorithmic Design History Files maintained by the named human under Final Liability (see Part 3.5.1). Drafters should treat GSN as a notation reference rather than a notation to reproduce in chapter or policy text.

**Caveats.** Heavyweight notation built for safety-critical systems engineering; not appropriate for direct deployment in non-engineering AI governance documents. Cite as conceptual reference; do not reproduce notation diagrams in policy text. CC BY 4.0 license permits commercial reuse with attribution.

### 26.3 Raji et al., Closing the AI Accountability Gap (Source \#11)

**Citation.** Raji, I.D., Smart, A., White, R.N., Mitchell, M., Gebru, T., Hutchinson, B., Smith-Loud, J., Theron, D. and Barnes, P., Closing the AI Accountability Gap: Defining an End-to-End Framework for Internal Algorithmic Auditing, Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (FAT\* 2020), Barcelona, Spain, January 27 to 30, 2020. ACM, pp. 33 to 44. doi 10.1145/3351095.3372873.

**Authority tier.** Foundational peer-reviewed scholarship on internal algorithmic auditing. Widely cited in the subsequent AI assurance literature. Not binding; treated as a methodological reference. Drafters integrating substantively should pair with one or two follow-on works to reflect subsequent literature development.

**Scope.** Defines an internal algorithmic audit framework structured in five stages, designated SMACTR: Scoping (define audit scope, ethical review, social impact assessment), Mapping (stakeholder map, ethnographic field study, Failure Modes and Effects Analysis), Artifact Collection (audit checklist, datasheets, model cards), Testing (adversarial testing, ethical risk analysis chart) and Reflection (use-related risk analysis, remediation plan, Algorithmic Design History File, audit summary report). Draws explicitly on auditing traditions in aerospace (FMEA, traceability, design checklists), medical devices (design controls, intended use, design history file, structural vulnerability) and finance (audit infrastructure, procedural justice and audit integrity). Distinguishes auditing for system reliability from auditing for societal harm (Lynch and Veland’s urgent governance frame).

**Use in this Master Reference.** Cited as the foundational scholarship for internal algorithmic auditing. The Algorithmic Design History File concept is the medical-device-derived precursor for the audit-grade evidence pipeline (see Part 5 TEVV, Part 8 Incident Management, Part 14 Documentation and Regulatory Compliance and the companion book Chapter 25). The SMACTR five-stage framework is structurally compatible with the OPERATIONAL CADENCE (Specify, State, Run, Defend) of this reference and may be used as an internal-audit-specific elaboration of the Defend stage. The procedural-justice argument supports the reasoning at Part 15 (Assurance and Audit) that audits matter when they are trusted, and they are trusted when they follow a vetted process.

**Caveats.** Published 2020. Substantial follow-on literature has accumulated. Acceptable as foundational citation; pair with later works for substantive integration. Open access via ACM Digital Library; standard scholarly fair-use applies for cited excerpts.

## APPENDIX A: AI GOVERNANCE POLICY DRAFTING CHECKLIST

*Drafter note. This checklist is a compliance confirmation tool, not a substantive specification. The substantive content for each item lives in the Parts referenced throughout this file; this checklist exists to verify that each item has been addressed in the derived governance document. Where an item here appears to duplicate language in the substantive Parts, the substantive Part is canonical.*

- [ ] Purpose and scope including what is covered and what is excluded and the relationship to parent policies

- [ ] Definitions of AI System, AI Model, AI Incident and GPAI Model at minimum

- [ ] Six core principles with organization-specific commitments and evidence specifications

- [ ] Three-tier governance structure with clear decision authority at each tier

- [ ] Three lines of defense model articulated

- [ ] Named roles: Board, Executive, Governance Committee, Operational Committee, AI Governance Lead, System Owners, Mechanism Owners, Legal, DPO, Internal Audit, Technical Staff and All Employees

- [ ] Actor type designation process (provider, deployer or both) for each AI system

- [ ] Impact classification (Low/Medium/High) with defined criteria and minimum governance requirements at each level

- [ ] Reconciliation with EU AI Act (or applicable regulatory) classification where relevant, including mandatory High Impact designation for Annex III systems

- [ ] Prohibited AI practices listed explicitly, mirroring Article 5 categories

- [ ] FRIA obligation identified and scoped for qualifying deployer categories (Article 27)

- [ ] System impact assessment methodology for the concept and ideation stage

- [ ] Risk assessment process including the four assessment dimensions

- [ ] AI risk taxonomy covering at least accuracy, fairness, privacy, security, transparency, accountability, operational, legal, societal and supply chain risk categories

- [ ] Stakeholder impact assessment requirement for Medium and High Impact systems

- [ ] FRIA requirement for qualifying High Impact deployer systems

- [ ] AI system inventory requirement with minimum content fields including actor designation and EU database registration status

- [ ] Lifecycle management requirements for each stage including QMS, EU database registration and retirement

- [ ] GPAI model governance provisions

- [ ] TEVV methodology referenced or addressed

- [ ] Acceptable use guidelines covering permitted uses, prohibited uses and uses requiring extra caution

- [ ] Tool-specific guidance for generative AI, coding assistants, embedded software and agentic systems

- [ ] Agentic AI governance provisions including scope definition, authorization thresholds and multi-agent accountability

- [ ] Incident management process with severity levels, escalation paths and regulatory notification timelines (three-tier: 15 calendar days, 10 calendar days for death, 2 calendar days for widespread infringement)

- [ ] Procurement and vendor management requirements including minimum contractual provisions and Article 25 supply chain analysis

- [ ] Supply chain risk assessment and management

- [ ] Human oversight requirements with explicit oversight mode assignment (HITL, HOTL or HIC) and meaningfulness criteria

- [ ] Cross-border compliance provisions including jurisdiction-specific obligations and liability framework

- [ ] Training requirements by role including AI literacy obligation (Article 4)

- [ ] Documentation requirements by classification level with retention periods

- [ ] QMS requirement for providers of high-risk AI systems (Article 17)

- [ ] Regulatory monitoring and compliance obligations

- [ ] Assurance and audit requirements including internal and external

- [ ] Enforcement architecture understood: AI Office (GPAI), national market surveillance authorities (high-risk) and notified bodies (conformity assessment)

- [ ] Penalty exposure assessed and documented: three-tier fine structure under Article 99

- [ ] Continuous improvement mechanism

- [ ] Exceptions process with approval authority and prohibition on excepting prohibited uses

- [ ] Review cadence and approval authority for policy changes

- [ ] Regulatory crosswalk confirming coverage of applicable framework requirements

- [ ] Governance maturity level assessed and target state defined

## APPENDIX B: AI RISK MANAGEMENT POLICY DRAFTING CHECKLIST

- [ ] Alignment with and reference to the parent AI Governance Policy

- [ ] Risk appetite statement with organization-specific position

- [ ] Risk tolerance levels by category covering at minimum regulatory compliance, data privacy, ethical impact and operational disruption

- [ ] Classification criteria and thresholds consistent with the Governance Policy

- [ ] Risk taxonomy covering accuracy, fairness, privacy, security, transparency, accountability, operational, legal, societal and supply chain risk categories

- [ ] Risk identification methods with mandatory structured technique for Medium and High Impact systems

- [ ] Four-dimension risk assessment methodology (likelihood, severity, velocity and feedback effects)

- [ ] Control taxonomy (technical, process, organizational and third-party)

- [ ] Residual risk reassessment requirement

- [ ] Monitoring framework with defined triggers and escalation to incident management

- [ ] Role-specific responsibilities for risk management activities

- [ ] AI Risk Register maintenance obligations

- [ ] Annual audit of risk management practices

- [ ] TEVV integration and reference

- [ ] Post-market surveillance obligations

- [ ] Supply chain risk provisions

- [ ] Training and awareness requirements specific to risk management

- [ ] Exceptions process

- [ ] Review and approval cadence

## APPENDIX C: AI USE POLICY DRAFTING CHECKLIST

- [ ] Scope covering all employees and contractors and all AI tool types including embedded features and agentic systems

- [ ] Reference to and consistency with AI Governance Policy and AI Risk Management Policy

- [ ] Six principles translated into practical employee-level guidance

- [ ] Permitted uses with concrete examples

- [ ] Prohibited uses with clear unambiguous language including alignment to prohibited practices list

- [ ] Uses requiring extra caution

- [ ] Tool-specific guidance for: generative AI tools, coding and productivity assistants, AI embedded in business software and agentic AI systems

- [ ] Employee accountability statement including specific statement that delegating to AI does not transfer accountability

- [ ] Manager accountability

- [ ] Incident and concern reporting process with channel details

- [ ] Near-miss reporting encouraged

- [ ] Good faith reporting protection

- [ ] Consequences for violation stated

- [ ] Exceptions process and where to seek guidance

- [ ] Training requirements referenced

- [ ] Review cadence

## APPENDIX D: REGULATORY CROSSWALK

The following tables map key governance framework elements to applicable regulatory and standards requirements. Drafters should use this crosswalk to confirm that policies address mandatory requirements where applicable regulatory frameworks are in scope.

**EU AI Act: High-Risk AI System Requirements (Chapter III, Section 2): Provider Obligations:**

| Requirement                             | EU AI Act Article | Addressed In                |
|-----------------------------------------|-------------------|-----------------------------|
| Risk management system                  | Art. 9            | Part 4                      |
| Data and data governance                | Art. 10           | Parts 5, 6                  |
| Technical documentation                 | Art. 11, Annex IV | Part 14                     |
| Record-keeping and logging              | Art. 12, Art. 19  | Parts 6, 14                 |
| Transparency and instructions for use   | Art. 13           | Principles 3, 5; Part 11    |
| Human oversight measures                | Art. 14           | Parts 2, 11                 |
| Accuracy, robustness, cybersecurity     | Art. 15           | Principles 1, 4; Parts 4, 5 |
| Provider obligations (general)          | Art. 16           | Parts 3, 6                  |
| Quality Management System               | Art. 17           | Part 6.7                    |
| Documentation keeping                   | Art. 18           | Part 14                     |
| Conformity assessment                   | Art. 43           | Part 5                      |
| EU database registration                | Art. 49           | Part 6.8                    |
| Fundamental Rights Impact Assessment    | Art. 27           | Part 20                     |
| Post-market surveillance                | Art. 72           | Part 6.6                    |
| Serious incident reporting (three-tier) | Art. 73           | Part 8.3                    |

**EU AI Act: Deployer Obligations (Article 26):**

| Obligation                                       | Article    | Addressed In |
|--------------------------------------------------|------------|--------------|
| Use in accordance with instructions for use      | Art. 26(1) | Parts 7, 11  |
| Human oversight assignment                       | Art. 26(2) | Part 11      |
| Input data relevance and representativeness      | Art. 26(3) | Parts 4, 5   |
| Monitoring and incident notification to provider | Art. 26(4) | Part 8       |
| Log retention (minimum 6 months)                 | Art. 26(5) | Part 14      |
| Fundamental Rights Impact Assessment             | Art. 27    | Part 20      |
| EU database registration                         | Art. 49    | Part 6.8     |

**EU AI Act: Supply Chain and Value Chain:**

| Obligation                            | Article          | Addressed In |
|---------------------------------------|------------------|--------------|
| When deployer becomes provider        | Art. 25          | Part 10.5    |
| Provider-to-deployer information flow | Art. 13, Art. 25 | Parts 10, 19 |

**EU AI Act: GPAI Model Obligations (Chapter V):**

| Obligation                                 | Article    | Addressed In    |
|--------------------------------------------|------------|-----------------|
| Technical documentation                    | Art. 53    | Parts 6.3, 19.4 |
| Copyright policy                           | Art. 53    | Parts 6.3, 19.4 |
| Training data summary                      | Art. 53    | Parts 6.3, 19.4 |
| Systemic risk classification (10^25 FLOPs) | Art. 51(2) | Parts 1.3, 19.4 |
| Adversarial testing                        | Art. 55    | Parts 5, 19.4   |
| Systemic risk assessment and mitigation    | Art. 55    | Parts 4, 19.4   |
| Serious incident reporting (GPAI)          | Art. 55    | Parts 8, 19.4   |
| Cybersecurity                              | Art. 55    | Parts 4, 19.4   |
| AI Office notification                     | Art. 52    | Part 19.4       |

**EU AI Act: Enforcement and Penalties:**

| Provision                                | Article    | Addressed In |
|------------------------------------------|------------|--------------|
| Penalty structure: prohibited practices  | Art. 99(3) | Part 21.2    |
| Penalty structure: operator obligations  | Art. 99(4) | Part 21.2    |
| Penalty structure: incorrect information | Art. 99(5) | Part 21.2    |
| GPAI provider penalties                  | Art. 101   | Part 21.2    |
| Regulatory sandbox                       | Art. 57–63 | Part 21.3    |

**NIST AI RMF Core Functions:**

| Function | Sub-Function                                              | Addressed In   |
|----------|-----------------------------------------------------------|----------------|
| GOVERN   | Organizational context, risk tolerance, culture           | Parts 1, 2, 4  |
| MAP      | Risk identification, impact assessment                    | Parts 1, 4     |
| MEASURE  | Testing, evaluation, metrics                              | Parts 4, 5     |
| MANAGE   | Risk treatment, incident response, continuous improvement | Parts 4, 8, 16 |

**US State AI Laws (Selected):**

| Instrument                           | Jurisdiction  | Addressed In |
|--------------------------------------|---------------|--------------|
| Colorado AI Act (SB 24-205)          | Colorado      | Part 12      |
| Local Law 144 (AEDT)                 | New York City | Part 12      |
| AI Video Interview Act (820 ILCS 42) | Illinois      | Part 12      |
| AI Policy Act (SB 149)               | Utah          | Part 12      |

**ISO/IEC 42001:2023 Key Clauses:**

| Clause | Topic                                          | Addressed In         |
|--------|------------------------------------------------|----------------------|
| 4      | Context of the organization                    | Parts 1, 12          |
| 5      | Leadership                                     | Parts 2, 3           |
| 6      | Planning (AI policy, objectives, risk)         | Parts 1, 4           |
| 7      | Support (resources, competence, documentation) | Parts 13, 14         |
| 8      | Operation (AI system lifecycle)                | Parts 5, 6, 7, 9, 10 |
| 9      | Performance evaluation                         | Part 15              |
| 10     | Improvement                                    | Part 16              |

**GDPR Intersections with AI Governance:**

| Provision | Subject                                            | Addressed In |
|-----------|----------------------------------------------------|--------------|
| Art. 22   | Automated decision-making with significant effects | Part 11      |
| Art. 35   | Data Protection Impact Assessment                  | Parts 4, 20  |
| Art. 33   | Personal data breach notification (72 hours)       | Part 8.3     |

## APPENDIX E: PROVIDER VS. DEPLOYER CLASSIFICATION DECISION GUIDE

*This Appendix reproduces and extends the actor-first analysis set out in Part 0 Quick Start. Use Part 0 for the five-step operative logic; use this Appendix for the full analytical detail, including boundary cases and documentation requirements.*

Use this guide when analyzing an organization’s EU AI Act actor designation for a specific AI system. Complete this analysis for every High Impact system and for any system that may fall within EU AI Act Annex III scope.

**Step 1: Did the organization develop the AI system (or have it developed) and place it on the market or put it into service under its own name or trademark?**

- Yes → Organization is a **Provider** for this system. Full provider obligations apply.

- No → Proceed to Step 2.

**Step 2: Is the organization using an AI system developed by a third party under the organization’s own authority?**

- Yes → Organization is a **Deployer** for this system. Deployer obligations under Article 26 apply. Proceed to Step 3.

- No → Assess whether the system falls within scope at all.

**Step 3 (for Deployers): Has the organization made or does it intend to make a substantial modification to the AI system?**

- Define “substantial modification” per Article 25 guidance: material change to intended purpose; change that would affect compliance with Chapter III requirements; retraining that materially alters performance or risk profile.

- Yes, substantial modification made or intended → Organization becomes a **Provider** for the modified system. Return to Step 1 pathway.

- No → Remain as **Deployer**. Proceed to Step 4.

**Step 4 (for Deployers): Does the organization‘\*\*\*\*s intended use fall within the system\*\*\*\*’s intended purpose as defined by the provider?**

- Yes → Organization is using the system as a Deployer in scope of its intended purpose.

- No → Organization is using the system outside its intended purpose. This is treated as a material modification. Assess whether it constitutes a substantial modification triggering provider obligations under Article 25.

**Step 5: Does the system fall within EU AI Act Annex III high-risk AI system categories?**

- Yes → Both provider and deployer obligations specific to high-risk systems apply. Document the specific Annex III entry and associated obligations. Assign internal High Impact classification regardless of other classification factors.

- No → Assess whether any transparency or sector-specific obligations apply under applicable law.

**Documentation requirement.** This analysis must be documented for each system in the AI system inventory and reviewed whenever the system, its use or the organization’s role changes materially.

## APPENDIX F: FRIA MINIMUM CONTENT CHECKLIST

Use this checklist when preparing a Fundamental Rights Impact Assessment under EU AI Act Article 27. Applicable to: deployers that are public bodies or private entities providing public services deploying Annex III high-risk AI systems (excluding critical infrastructure); deployers using AI for creditworthiness evaluation, credit scoring or life and health insurance risk assessment and pricing.

**Section 1: System and Deployment Description**

- [ ] Name and description of the high-risk AI system being deployed

- [ ] Provider name and instructions for use reference

- [ ] Intended purpose of the system as defined by the provider

- [ ] Description of the deployer’s specific processes in which the system will be used (how it fits into operational workflows)

- [ ] Period of time for which the system will be used and frequency of use

- [ ] Geographic scope of deployment

- [ ] Whether the system has been modified from its original form and if so, description of modifications

**Section 2: Affected Population**

- [ ] Categories of natural persons likely to be affected by the system’s use in this specific deployment context

- [ ] Identification of any vulnerable groups within the affected population (children, elderly, persons with disabilities, marginalized communities)

- [ ] Estimated number of persons likely to be affected

- [ ] Whether affected persons will be aware they are subject to the AI system

**Section 3: Fundamental Rights Risk Assessment**

- [ ] Identification of specific risks of harm to fundamental rights likely to affect each identified category of person

- [ ] Assessment drawing on information provided by the provider under Article 13 (instructions for use and documentation)

- [ ] Assessment of risks to: human dignity; privacy and data protection; non-discrimination; freedom of expression and information; access to justice and effective remedies; other applicable Charter rights given the deployment context

- [ ] Likelihood and severity of identified risks

- [ ] Whether the system could produce different impacts on different demographic groups

**Section 4: Human Oversight**

- [ ] Description of human oversight measures as specified in the provider’s instructions for use

- [ ] Identification of qualified persons responsible for oversight

- [ ] Competencies required for effective oversight and how they will be assured

- [ ] Override procedures: how a human reviewer can intervene or override the system output

- [ ] Documentation of how oversight decisions will be recorded

**Section 5: Risk Mitigation Measures**

- [ ] Measures to be taken if identified risks materialize

- [ ] Internal governance arrangements addressing identified risks (who decides, who escalates, who reviews)

- [ ] Complaint mechanism available to affected persons

- [ ] Appeal or redress pathway if a person is adversely affected by a decision influenced by the system

- [ ] Monitoring plan to detect adverse fundamental rights impacts during operation

**Section 6: DPIA Coordination**

- [ ] If a DPIA has been or will be conducted: confirm the FRIA complements the DPIA without duplicating it

- [ ] Cross-reference to the relevant DPIA

- [ ] Confirm all GDPR Article 35 elements are addressed in the combined documentation

**Section 7: Notification**

- [ ] Confirm the completed FRIA will be notified to the competent market surveillance authority using the AI Office template

- [ ] Record the date of notification and the authority notified

- [ ] Record any response from the authority and any required follow-up actions

**Review and Update**

- [ ] Date of FRIA completion

- [ ] Name and role of FRIA owner (System Owner with Legal and Compliance review)

- [ ] Review trigger: material change to the system, its use, the affected population or available oversight measures requires FRIA update before continued use

- [ ] Scheduled review date

## APPENDIX G: ISO/IEC 42001:2023 ANNEX A CONTROLS MAP

ISO/IEC 42001:2023 is the international standard for AI management systems. The core clauses (4 through 10) are addressed in the crosswalk in Appendix D. Annex A of the standard contains the controls that operationalize the management system and that certified organizations implement against a declared Statement of Applicability. This appendix maps the Annex A control objectives and control families to the relevant Parts of this reference, enabling drafters producing documentation for ISO/IEC 42001 certification to locate the substantive content for each control.

Drafters should note that the mapping indicates where the underlying substance is treated; it does not substitute for the Statement of Applicability, which must be produced for each organization and each scope. Annex A is organized into nine control objective families (A.2 through A.10 in the standard’s numbering). The mapping below uses the family-level structure.

**A.2 Policies related to AI.** Objective: to provide management direction and support for AI systems in accordance with business requirements. Addressed in Parts 1, 2 and 18.

**A.3 Internal organization.** Objective: to establish accountability within the organization for the responsible development, provision or use of AI systems. Addressed in Parts 2 and 3.

**A.4 Resources for AI systems.** Objective: to ensure that the organization accounts for resources (including data, tooling, system and computing resources, human resources) necessary for the responsible development, provision or use of AI systems. Addressed in Parts 3, 6 and 13.

**A.5 Assessing impacts of AI systems.** Objective: to assess AI system impacts to individuals, groups and societies that can be affected by the system throughout its lifecycle. Addressed in Parts 4.3, 4.4, 4.5 and 20.

**A.6 AI system lifecycle.** Objective: to define criteria and requirements for each stage of the AI system lifecycle. Addressed in Parts 5, 6 and 9.

**A.7 Data for AI systems.** Objective: to ensure that the organization understands the role and impacts of data in AI systems and manages data through the AI system lifecycle. Addressed in Parts 4.4, 5, 6.2 and 6.4.

**A.8 Information for interested parties of AI systems.** Objective: to ensure that relevant interested parties have the necessary information to understand and assess the AI system, its risks, its impacts and its use. Addressed in Parts 4.2 (Principle 3), 11.4, 20 and 21.

**A.9 Use of AI systems.** Objective: to ensure that the organization uses AI systems responsibly and according to organizational policies. Addressed in Parts 7 and 11.

**A.10 Third-party and customer relationships.** Objective: to ensure that the organization understands its responsibilities and remains accountable when third parties are involved at any stage of the AI system lifecycle, and when the organization is a third party to another organization. Addressed in Parts 10 and 23.

**Certification preparation notes.** Organizations pursuing ISO/IEC 42001 certification should: (a) produce a Statement of Applicability listing each Annex A control, its applicability to the declared scope and the control implementation evidence; (b) establish the AI management system documentation hierarchy as set out in Part 18; (c) conduct an internal audit against clauses 4 through 10 and against the Statement of Applicability; and (d) engage an accredited certification body for the external audit. The AI governance maturity model in Part 22 provides a pathway for organizations approaching certification from Levels 2 or 3 toward the Level 4 or 5 posture that supports successful certification.

*This master reference file is a synthesis and expert enhancement of best-practice AI governance documentation for use as a knowledge base in AI-assisted GRC drafting workflows. Regulatory references reflect the state of law as of the date of this version; the regulatory landscape for AI is evolving rapidly and this file must be updated when significant regulatory changes occur. This file does not constitute legal advice. All AI governance documents derived from this reference must be reviewed by qualified legal and compliance professionals before adoption.*

*Final Liability rests with the Human.*
