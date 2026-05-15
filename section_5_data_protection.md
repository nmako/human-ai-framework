# Section 5: Data protection and privacy

**Status:** Working draft v0.4
**Section position:** Section 5 of 12 in the rubric
**Configuration dependencies:** Most requirements activate at all ambition tiers because GDPR applies regardless of ambition. AI Act Article 10 data governance obligations activate for high-risk AI systems specifically and for providers more broadly than deployers.
**Density:** Medium (6 requirements).
**Mode:** Prescriptive throughout.
**Executive part weight:** Light (30–40 words target).

---

## Changelog

### v0.4 — current

- **Pilot company names removed.** Generic company profiles replace named pilots. Section header renamed for consistency.

### v0.3

- **FRIA realigned to Section 6.** Requirement 5.4 (Data Protection Impact Assessment) now cross-references Section 6 Requirement 6.4 for AI Act Article 27 Fundamental Rights Impact Assessment substance, rather than carrying FRIA itself. The cleaner architecture: DPIA stays in Section 5, FRIA lives in Section 6, HRIA lives in Section 7, with explicit integration logic in Section 6.6.

### v0.2

- **Executive commitment block added** at the top of the section, weighted light per the configuration model v0.4 section weighting. The section's substantive operational content is delivered in Part 2; the executive commitment is brief because the framework's continuity principle means companies' existing GDPR policies carry the foundational data protection work.

### v0.1
Initial draft. Six requirements addressing AI-specific intersections with GDPR plus AI Act Article 10 data governance.

---

## Executive commitment (Part 1 — Executive policy)

> *Generator output for Part 1. ~35 words.*
>
> **Data protection and privacy.** Personal data in our AI deployments is governed by our existing data protection framework with heightened safeguards for special category data, AI training data, automated decisions, and international transfers — extended, not relaxed, by AI use.

---

## Section purpose

This section addresses where AI deployment changes what data protection requires. It does not aim to replace or restate the company's existing GDPR or data protection policy — most companies have those, and the framework's continuity principle means the Human-AI policy extends rather than parallels existing infrastructure.

What changes when AI enters the picture: data flows become harder to map (training data, inference data, output data, model parameters); purposes shift between training and operational use; special category data risks emerge from inference even where the input data is not sensitive; data minimization becomes harder to assess when AI systems benefit from more data; international data transfers multiply when AI tools are cloud-hosted; data subject rights — particularly the rights to access, erasure, and explanation — collide with AI system architectures that may not easily support them.

The framework transposes binding obligations here. GDPR's core principles (Article 5), lawful basis requirements (Article 6 and 9), data subject rights (Articles 12–22), data protection by design and default (Article 25), Data Protection Impact Assessment requirements (Article 35), and processor obligations (Article 28) all apply to AI deployment as they apply to any other personal data processing — sometimes with sharper edges. AI Act Article 10 imposes data governance obligations specifically on providers of high-risk AI systems regarding training, validation, and testing datasets. The two regimes overlap at points (data quality, bias, special category handling) and diverge at others (the AI Act's product safety logic does not displace GDPR's data subject rights).

The framework's distinctive position in this section is that data protection in AI is not a procedural compliance box. It is the operational foundation of the human accountability and worker rights commitments elsewhere in the policy. A company that handles data well in AI deployment is better positioned to meet its obligations across the rest of the policy; a company that handles it badly creates compliance and human rights problems that no amount of governance language can paper over.

---

## Section narrative (the policy-level commitment)

> *Suggested policy text the Generator produces for this section, adapted to company configuration:*
>
> **Data protection and privacy.** Our use of AI is governed by the data protection commitments we already maintain — our existing GDPR / data protection policy, our information security framework, our data subject rights procedures — extended to address AI-specific concerns.
>
> *Personal data in AI deployment.* Personal data used in AI systems we deploy is governed by the same lawful basis requirements, transparency obligations, and data subject rights as any other personal data processing in our company. AI use does not relax these obligations.
>
> *Special category data.* AI systems handling special category data — health, biometric data, ethnic or racial origin, political opinions, religious beliefs, trade union membership, sexual orientation, sex life, genetic data — operate under heightened safeguards. We do not deploy AI that infers special category data from non-sensitive inputs without explicit lawful basis under GDPR Article 9. We do not deploy AI for biometric categorization to deduce sensitive characteristics (cross-references Section 3 Requirement 3.8 prohibition).
>
> *AI training data.* Where we use AI tools provided by third parties, we verify how training data was governed and what obligations the provider has discharged. Where we contribute data to AI training, we do so in line with our lawful basis and the consent or notification given to data subjects.
>
> *Data protection by design.* Data protection considerations are integrated into AI deployment decisions from the earliest stage, not retrofitted after deployment. We conduct Data Protection Impact Assessments for AI deployments meeting the GDPR Article 35 threshold, integrated with AI risk classification and impact assessment under Section 6 of this policy.
>
> *Data subject rights.* The data subject rights in our existing data protection policy — access, rectification, erasure, restriction, objection, portability, and rights regarding automated decision-making under GDPR Article 22 — apply to AI processing. We commit to operationalizing these rights for AI deployments, including where the AI system architecture makes some rights technically harder to implement.
>
> *International data transfers.* AI tools are often cloud-hosted across multiple jurisdictions. We govern international transfers of personal data in AI deployments under the same Chapter V GDPR framework that governs other transfers, with appropriate adequacy determinations, standard contractual clauses, or other safeguards as required.

---

## Generator behavior for this section

This section is prescriptive. Generator behavior follows a consistent cascade across requirements.

**Priority 1 — Existing data protection commitments.** If the company has uploaded a Data Protection / GDPR policy, Information Security policy, Records of Processing under GDPR Article 30, or DPIA template, the Generator extracts the existing data protection vocabulary, methodology, lawful basis framing, and data subject rights procedures. The Human-AI policy section is written to extend these existing commitments rather than restate them.

**Priority 2 — Adjacent company materials.** If the company has uploaded a Code of Conduct or IT policy with data-related commitments, the Generator draws on that voice. Privacy notices on the company website are extracted where accessible.

**Priority 3 — Foundation language meeting GDPR and AI Act Article 10 minimum.** If no company material is available, the Generator produces foundation language meeting GDPR Articles 5, 6, 9, 13–22, 25, 28, 35, and Chapter V minimum, plus AI Act Article 10 where the company has provider obligations. The Generator notes that companies without an existing data protection policy have a more fundamental gap than this section can address — Section 11 (Connected internal policies) flags this and the Generator output for such companies includes a recommendation to develop a foundational data protection policy alongside the Human-AI policy.

For provider-specific AI Act Article 10 obligations, the Generator activates only when the company self-identifies as a provider in Q7 of the core questionnaire.

---

## Requirements

### Requirement 5.1 — Personal data in AI deployment governed by existing data protection framework

**Statement.** The policy commits the company to governing personal data used in AI deployments under the same data protection framework that governs other personal data processing in the company. AI use does not relax lawful basis requirements (GDPR Articles 6 and 9), transparency obligations (Articles 13–14), data subject rights (Articles 12–22), purpose limitation (Article 5(1)(b)), data minimization (Article 5(1)(c)), accuracy (Article 5(1)(d)), storage limitation (Article 5(1)(e)), or integrity and confidentiality (Article 5(1)(f)).

**Tier:** 1b (binding under GDPR — these are the foundational obligations that apply to all personal data processing).

**Scope:** All — applies regardless of ambition tier. GDPR applies to any company processing personal data of EU/EEA residents regardless of company size, sector, or ambition.

**Jurisdiction:** Regulation (EU) 2016/679 (GDPR); UK GDPR (Data Protection Act 2018); national data protection laws in non-EU/EEA jurisdictions where the company operates.

**Legal logic:** GDPR-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2016/679 (GDPR), Articles 5 (principles), 6 (lawfulness), 9 (special categories), 12–22 (data subject rights).
- *Binding:* UK Data Protection Act 2018 and UK GDPR (where applicable).
- *Interpretive:* European Data Protection Board Guidelines on AI and personal data processing (most current version).

**What to look for in a policy.** The policy should commit to applying the company's existing data protection framework to AI deployments without creating an AI carve-out, cross-reference the company's existing data protection or GDPR policy, and confirm that AI-specific requirements layer on top of rather than replacing the foundational GDPR framework.

**Assessment criteria:**
- *Covered:* The policy explicitly commits that AI deployments are governed by the company's existing data protection framework, names that framework (cross-referencing the specific data protection policy), and confirms no AI carve-out from foundational GDPR principles.
- *Partial:* The policy mentions data protection but does not cross-reference the existing framework, treats AI as creating its own data protection track, or implies AI use relaxes any foundational GDPR principle.
- *Missing:* The policy is silent on the relationship to existing data protection framework, or contains language suggesting AI-specific data handling exceptions.

**Generator behavior.** *(1) If the company has uploaded a Data Protection or GDPR policy, the Generator names that policy specifically in the cross-reference. (2) If the company has uploaded an IT policy or Code of Conduct with data protection commitments, the Generator references that material. (3) If no company material is available, the Generator produces foundation language with placeholder reference to "our data protection policy" and a flag that a foundational data protection policy should exist alongside the Human-AI policy.*

---

### Requirement 5.2 — Special category data and inference of sensitive characteristics

**Statement.** AI systems handling special category data under GDPR Article 9 — health, biometric data, ethnic or racial origin, political opinions, religious beliefs, trade union membership, sexual orientation, sex life, genetic data — operate under heightened safeguards. The policy commits that the company does not deploy AI to infer special category data from non-sensitive inputs without explicit lawful basis under Article 9. Where the company processes special category data through AI, the lawful basis is identified, the technical and organizational safeguards required by Article 9 are documented, and a Data Protection Impact Assessment under Article 35 is conducted.

**Tier:** 1a where biometric categorization to infer sensitive characteristics is the issue (AI Act Article 5(1)(g) prohibition — handled in Section 3 Requirement 3.8); 1b for GDPR Article 9 substantive safeguards.

**Scope:** All — applies regardless of ambition tier wherever AI processes or could infer special category data.

**Jurisdiction:** GDPR Articles 9 (special categories), 35 (DPIA); AI Act Article 5(1)(g) (biometric categorization prohibition); national laws on special category data (e.g., German BDSG provisions on special categories, Norwegian Personopplysningsloven provisions).

**Legal logic:** Both GDPR-derived (Article 9) and AI Act-derived (Article 5(1)(g) prohibition).

**Source citations:**
- *Binding:* Regulation (EU) 2016/679 (GDPR), Article 9 (processing of special categories of personal data) and Article 35 (data protection impact assessment).
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 5(1)(g) — prohibition on biometric categorization to deduce or infer race, political opinions, trade union membership, religious or philosophical beliefs, sex life, or sexual orientation.
- *Cross-reference:* Section 3 Requirement 3.8 of this rubric (prohibited AI uses including biometric categorization for sensitive characteristics).
- *Interpretive:* European Data Protection Board Guidelines on the processing of personal data through AI systems (most current version); EDPB Guidelines on Article 9 processing.

**What to look for in a policy.** The policy should address special category data in AI deployment specifically, confirm the prohibition on inferring sensitive characteristics through biometric categorization (cross-referencing Section 3 Requirement 3.8), commit to identifying lawful basis under Article 9 where special category data is processed, commit to DPIA where required, and address technical and organizational safeguards.

**Assessment criteria:**
- *Covered:* The policy addresses special category data in AI deployment, confirms the biometric categorization prohibition, identifies lawful basis requirements under Article 9, commits to DPIA where required, and addresses safeguards.
- *Partial:* The policy mentions special category data but does not address inference from non-sensitive inputs, or addresses one regime (GDPR or AI Act) without the other.
- *Missing:* The policy is silent on special category data in AI, or treats it as covered by general GDPR commitments without AI-specific provisions.

**Generator behavior.** *(1) If the company has uploaded special category data handling procedures, biometric data policy, or health data policy, the Generator extracts existing safeguards and integrates them. (2) If the company has uploaded a DPIA template or DPIA records, the Generator references the existing DPIA process. (3) If no company material is available, the Generator produces foundation language meeting GDPR Article 9 and AI Act Article 5(1)(g) minimum, with explicit cross-reference to Section 3 Requirement 3.8 and to whichever Section 6 risk classification approach the company adopts.*

---

### Requirement 5.3 — AI training data governance

**Statement.** Where the company uses AI tools provided by third parties, the policy commits to verifying how training data was governed and what obligations the provider has discharged regarding the data used to train the AI system. Where the company contributes data to AI training — its own data being used to train provider models, or its own AI systems being trained on internal data — the policy commits to ensuring lawful basis is established for training use, that the training use is compatible with the original purpose of data collection, and that data subjects have been informed appropriately.

**Tier:** 1b (binding under AI Act Article 10 for providers of high-risk AI systems; binding under GDPR Article 5(1)(b) purpose limitation and Article 6 lawful basis for any data used in training; converging best practice for non-high-risk AI training).

**Scope:** All — applies regardless of ambition tier where the company uses AI tools or contributes data to training. Provider-side obligations under AI Act Article 10 activate for company-as-provider.

**Jurisdiction:** EU AI Act Article 10 (data and data governance for high-risk AI systems); GDPR Articles 5(1)(b), 5(1)(d), 6, 9; EDPB guidance on AI training data.

**Legal logic:** Both AI Act-derived and GDPR-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 10 — providers of high-risk AI systems must ensure training, validation, and testing datasets are subject to data governance practices including relevance, representativeness, freedom from errors, and completeness; bias examination requirements; processing of special categories where strictly necessary for bias detection and correction with appropriate safeguards.
- *Binding:* Regulation (EU) 2016/679 (GDPR), Articles 5(1)(b) (purpose limitation), 5(1)(d) (accuracy), 6 (lawfulness), 9 (special categories).
- *Interpretive:* European Data Protection Board Opinion on AI training and personal data (most current version); recent Court of Justice of the European Union case law on training data.

**What to look for in a policy.** The policy should address two scenarios: (a) the company as deployer using third-party AI — commit to verifying provider training data governance; (b) the company as data contributor to AI training — commit to lawful basis and purpose compatibility. For provider companies (gated by configuration), the policy should address the substantive Article 10 obligations on training data quality, bias detection, and special category handling.

**Assessment criteria:**
- *Covered:* The policy addresses both deployer-as-AI-user and company-as-data-contributor scenarios, commits to verifying provider training data governance, confirms lawful basis for training use of company data, and addresses purpose compatibility. For providers, the policy addresses Article 10 substantively.
- *Partial:* The policy addresses one scenario but not the other, or commits in general terms without specific operational practice (no verification mechanism, no purpose compatibility analysis).
- *Missing:* The policy is silent on training data, or treats training data as a provider-only concern when the company is also a data contributor.

**Generator behavior.** *(1) If the company has uploaded vendor management procedures, third-party risk assessment frameworks, or AI tool procurement policies, the Generator extracts existing verification practice and integrates AI training data verification. (2) If the company has uploaded data sharing agreements or data licensing policies, the Generator draws on existing voice for the data-contributor scenario. (3) If no company material is available, the Generator produces foundation language meeting AI Act Article 10 (where company is provider) and GDPR Article 5(1)(b), 6 minimum. The provider-side substantive Article 10 obligations are configuration-gated and produced only when Q7 indicates provider role.*

---

### Requirement 5.4 — Data Protection Impact Assessment for AI deployments

**Statement.** The policy commits the company to conducting Data Protection Impact Assessments under GDPR Article 35 for AI deployments meeting the DPIA threshold, integrated with AI risk classification and impact assessment under Section 6 of this policy. The DPIA is conducted before deployment, addresses the specific risks AI introduces (training data, inference outputs, automated decision-making, special category data implications), involves the Data Protection Officer where one is appointed, and informs the company's deployment decision substantively.

**Tier:** 1b (binding under GDPR Article 35 for high-risk processing including most AI use cases involving personal data).

**Scope:** All — applies regardless of ambition tier where AI deployment crosses the DPIA threshold under GDPR Article 35.

**Jurisdiction:** GDPR Article 35; national DPIA criteria from supervisory authorities (e.g., the Norwegian Datatilsynet's guidance, the UK ICO's DPIA guidance, the EDPB's WP248 list of processing operations requiring DPIA).

**Legal logic:** GDPR-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2016/679 (GDPR), Article 35 (data protection impact assessment) and Article 36 (prior consultation with supervisory authority).
- *Interpretive:* Article 29 Working Party Guidelines on Data Protection Impact Assessment (WP248) and successor EDPB guidance.
- *Interpretive:* Norwegian Datatilsynet guidance on DPIA; UK ICO DPIA guidance.
- *Cross-reference:* Section 6 Requirement 6.4 (Fundamental Rights Impact Assessment under AI Act Article 27, where applicable to the company's role and AI use case category).
- *Cross-reference:* Section 6 of this rubric (AI risk classification and impact assessment); Section 6 Requirement 6.6 (translation logic between DPIA, FRIA, and HRIA).

**What to look for in a policy.** The policy should commit to DPIA for AI deployments meeting the threshold, integrate the DPIA with AI risk classification and impact assessment (Section 6), specify timing (before deployment), address the AI-specific risks the DPIA must cover, involve the DPO where appointed, and where the company is subject to AI Act Article 27 FRIA obligations, cross-reference Section 6 Requirement 6.4 for the FRIA substance. The framework's position is that DPIA, FRIA, and HRIA operate as connected disciplines (Section 6 Requirement 6.6 documents the translation logic) — the policy should not duplicate FRIA substance in Section 5 but should make the integration visible.

**Assessment criteria:**
- *Covered:* The policy commits to DPIA for AI deployments meeting threshold, integrates with Section 6 risk classification, specifies pre-deployment timing, addresses AI-specific risks, involves DPO, and where the company is in Article 27 FRIA scope, cross-references Section 6 Requirement 6.4.
- *Partial:* The policy commits to DPIA but does not integrate with AI risk classification, or treats DPIA as a checkbox rather than a substantive analysis.
- *Missing:* The policy is silent on DPIA for AI, or treats AI as not triggering DPIA thresholds despite obvious applicability.

**Generator behavior.** *(1) If the company has uploaded a DPIA template, DPIA procedure, or DPIA records, the Generator extracts the existing DPIA framework and ensures AI-specific risks are addressed. (2) If the company has uploaded a DPO charter or data governance procedure, the Generator integrates that role. (3) If no company material is available, the Generator produces foundation language meeting GDPR Article 35 minimum with AI-specific risk categories named (training data, inference, automated decisions, special category implications). For companies subject to AI Act Article 27 FRIA (configuration-gated by sector and AI use case), the Generator produces a cross-reference to Section 6 Requirement 6.4 rather than duplicating FRIA substance in this requirement.*

---

### Requirement 5.5 — Data subject rights in AI deployments

**Statement.** The policy commits the company to operationalizing data subject rights — access, rectification, erasure, restriction, objection, portability, and rights regarding automated decision-making under GDPR Article 22 — for AI processing. The policy addresses the practical challenges AI architecture creates for some rights (erasure from trained models, access to inference logic, portability of AI-generated profiles) and commits to substantive responses rather than treating technical difficulty as a defense against the obligation.

**Tier:** 1b (binding under GDPR Articles 12–22).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** GDPR Articles 12–22; national data protection law on data subject rights enforcement; AI Act Article 86 right to explanation (cross-references Section 4 Requirement 4.7).

**Legal logic:** GDPR-derived primarily.

**Source citations:**
- *Binding:* Regulation (EU) 2016/679 (GDPR), Articles 12 (transparent information and exercise of rights), 13–14 (information to data subjects), 15 (right of access), 16 (right to rectification), 17 (right to erasure), 18 (right to restriction), 20 (right to data portability), 21 (right to object), 22 (rights regarding automated decision-making).
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 86 (right to explanation of individual decision-making for high-risk AI deployers).
- *Cross-reference:* Section 1 Requirement 1.2 (human accountability), Section 3 Requirement 3.4 (right to challenge AI-driven outcomes), Section 4 Requirement 4.7 (explainability).
- *Interpretive:* European Data Protection Board guidelines on data subject rights and AI (most current version).

**What to look for in a policy.** The policy should commit to operationalizing data subject rights for AI processing, address the practical AI-specific challenges (erasure from models, access to inference logic, portability of AI-generated data), commit to substantive responses, and cross-reference Section 4 explainability and Section 3 challenge rights.

**Assessment criteria:**
- *Covered:* The policy commits to operationalizing all data subject rights for AI processing, addresses the AI-specific challenges substantively, commits to specific response procedures and timeframes, and cross-references the related sections of this rubric.
- *Partial:* The policy commits to data subject rights in general terms but does not address AI-specific challenges, or treats technical difficulty as a defense.
- *Missing:* The policy is silent on data subject rights in AI, or relies entirely on the general GDPR policy without addressing AI-specific operationalization.

**Generator behavior.** *(1) If the company has uploaded a data subject rights procedure, GDPR rights handling SOPs, or DSAR (data subject access request) procedures, the Generator extracts the existing rights handling framework and ensures AI-specific dimensions are addressed. (2) If the company has uploaded customer service procedures with rights-handling integration, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting GDPR Articles 12–22 minimum, with explicit AI-specific operationalization for each right, and cross-references to Sections 1, 3, and 4.*

---

### Requirement 5.6 — International data transfers in cloud-hosted AI

**Statement.** Where AI tools used by the company involve international transfers of personal data — typically because AI tools are cloud-hosted across multiple jurisdictions — the policy commits to governing these transfers under GDPR Chapter V with appropriate adequacy determinations, standard contractual clauses, binding corporate rules, or other transfer safeguards as required. The policy addresses the specific risks AI cloud-hosting creates for international transfers (data routing complexity, processor sub-processing chains, US government access concerns post-Schrems II).

**Tier:** 1b (binding under GDPR Chapter V, particularly Articles 44–49).

**Scope:** All — applies regardless of ambition tier wherever AI tools involve international transfers.

**Jurisdiction:** GDPR Chapter V (Articles 44–49); UK GDPR international transfer regime; EU-US Data Privacy Framework (where applicable); EDPB Schrems II guidance and successor case law; national data localization requirements where applicable.

**Legal logic:** GDPR-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2016/679 (GDPR), Chapter V (Articles 44–49) on transfers of personal data to third countries or international organizations.
- *Binding:* Implementing Decision (EU) 2023/1795 establishing the EU-US Data Privacy Framework.
- *Interpretive:* Court of Justice of the European Union, C-311/18 (Schrems II) on third country transfers and supplementary measures; subsequent jurisprudence.
- *Interpretive:* European Data Protection Board Recommendations 01/2020 on supplementary measures and successor guidance.

**What to look for in a policy.** The policy should commit to governing international transfers in AI deployments under Chapter V, identify the typical transfer mechanisms (adequacy, SCCs, BCRs, Article 49 derogations), address AI-specific complexities (sub-processor chains, data routing in cloud-hosted AI), and address the post-Schrems II supplementary measures regime where applicable.

**Assessment criteria:**
- *Covered:* The policy commits to Chapter V governance for AI international transfers, addresses transfer mechanisms, addresses AI-specific complexities, and addresses post-Schrems II supplementary measures.
- *Partial:* The policy commits to compliance with Chapter V in general terms but does not address AI-specific complexities or sub-processor chains.
- *Missing:* The policy is silent on international transfers in AI deployments, despite cloud-hosted AI being the operational reality for most companies.

**Generator behavior.** *(1) If the company has uploaded an international data transfer policy, vendor data processing addendums, or sub-processor management procedures, the Generator extracts the existing transfer framework. (2) If the company has uploaded vendor management procedures with international hosting considerations, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting Chapter V minimum, naming SCCs and adequacy as the most common mechanisms, addressing AI-specific sub-processor complexity, and addressing Schrems II supplementary measures. For companies operating only within the EEA without third-country AI tool dependencies (rare but possible), the Generator produces a brief statement that international transfers are not currently in scope but will activate this requirement upon any change.*

---

## How this section activates across company profiles

**Profile A — Mid-size manufacturer with mature HRDD:** All six requirements activate. The existing data protection policy (typical for a 2,000+ employee EU-trading company) carries the foundational work; the AI-specific layers in this section operate on top. Special category data (5.2) activates where the company uses AI in HR processes (potentially health data through occupational health) or biometric data (potentially facility access). DPIA (5.4) activates for material AI deployments. International transfers (5.6) activates given cloud-hosted AI tools. Provider-side training data obligations (within 5.3) deactivate.

**Profile B — Safety-critical operations company in group context:** All six requirements activate. Group-level data protection framework likely operates at parent level with subsidiary integration; the policy cross-references the applicable group framework. Special category data (5.2) activates around health data (occupational health, accident reporting in safety-critical sector). DPIA (5.4) activates for material AI deployments — particularly important given exploratory AI in safety-critical contexts. International transfers (5.6) activates.

**Profile C — Small specialty distributor below regulatory thresholds:** All six requirements activate, but operationally lighter. At 60 employees, the company may have a basic data protection policy and a privacy notice rather than a full data protection framework. The Generator output flags where the company's existing infrastructure may need development alongside the Human-AI policy. Special category data (5.2) activates for any HR-related AI use. DPIA (5.4) activates conditionally — small companies often miss DPIA obligations because they think DPIAs are for large companies, which is incorrect. International transfers (5.6) activates because most cloud-hosted AI tools (including the typical AI tools a small company uses) involve some level of international transfer.

The activation pattern shows a useful framework property: the data protection section applies consistently across company sizes because GDPR applies consistently. The differences between mid-size mature companies and small companies are in what the *underlying* data protection infrastructure looks like, not in what AI-specific obligations apply. This is why the framework's continuity principle matters here — companies are expected to have foundational data protection policies; the Human-AI policy extends those, and where the foundational policy is missing, the framework flags that as a gap requiring attention beyond what this section can fix.

---

## Open items for review

**Section 5 / existing data protection policy boundary.** The section deliberately stays focused on AI-specific intersections rather than restating GDPR. This means the section is shorter and more focused than a full GDPR section would be. Worth your view on whether the boundary is right, or whether some additional AI-specific GDPR obligations need explicit treatment (e.g., Article 25 data protection by design and default in AI architecture; Article 28 processor obligations specific to AI vendors; Article 32 security in AI systems).

**Article 22 cross-section coverage.** GDPR Article 22 appears in Sections 1.2, 3.2, 3.4, 4.7, and now 5.5. The cross-references manage the overlap, but Article 22 is doing a lot of cross-cutting work in the rubric. Worth your view on whether it should have its own dedicated requirement somewhere or whether the cross-cutting treatment is correct.

**FRIA placement (5.4) — resolved in v0.3.** FRIA was moved primarily to Section 6 Requirement 6.4 in this revision. Section 5.4 now cross-references Section 6.4 rather than carrying FRIA substance. This is the cleaner architecture: DPIA in Section 5, FRIA in Section 6, HRIA in Section 7, with explicit integration logic in Section 6.6.

**International transfers (5.6) given Norwegian context.** Norway is in the EEA and the EU-US Data Privacy Framework adequacy decision applies. But several Norwegian sectors (public sector, healthcare, finance) have stricter data localization expectations than the EU minimum. The framework currently treats this generically. Worth your view on whether Norwegian-specific data residency expectations need explicit treatment or whether they are adequately covered by the general Chapter V framing.

**Length and density.** Section 5 came in at six requirements, lighter than Sections 3, 4, and 8. This reflects the deliberate scope — AI-specific intersections only, not full GDPR transposition. Worth confirming this density is right or whether the section needs additional requirements.
