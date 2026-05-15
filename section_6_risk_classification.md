# Section 6: AI Risk Classification and Impact Assessment

**Status:** Working draft v0.3
**Section position:** Section 6 of 12 in the rubric
**Configuration dependencies:** Most requirements activate at all ambition tiers because AI Act risk classification applies to all in-scope AI systems regardless of ambition. Provider-side risk management obligations activate only when the company self-identifies as a provider. FRIA obligations activate based on company role and AI system category. HRDD impact assessment integration activates based on Axis 1 jurisdictional exposure to HRDD law.
**Density:** Heavy (9 requirements). This is one of the structurally important sections — it operationalizes the proportionality commitment from Section 2.5 and connects AI Act product safety logic with HRDD impact-based logic per the translation layer.
**Mode:** Prescriptive throughout. Risk classification and impact assessment obligations are determined by binding law and established methodology.
**Executive part weight:** Medium (40–60 words target).

---

## Changelog

### v0.3 — current

- **Pilot company names removed.** Generic company profiles replace named pilots. Section header renamed for consistency.

### v0.2

- **FRIA placement open item marked resolved.** Section 5 v0.3 now cross-references Section 6.4 cleanly; Section 6.4 maintains bidirectional cross-reference. Surfaced in the consistency pass across all twelve sections.

### v0.1
Initial draft. Nine requirements at heavy density covering AI Act risk classification, FRIA, HRDD impact assessment integration, translation logic, pre-deployment timing, worker consultation, and ongoing reassessment.

---

## Section purpose

This section establishes how the company classifies AI risk and conducts AI impact assessment. It is where the AI Act's product safety logic and HRDD's impact-based logic most directly intersect at the requirement level — and where the translation layer's operational implications become specific.

The framework transposes several binding instruments here. AI Act Articles 6–7 establish the risk classification framework (prohibited / high-risk / limited-risk / minimal-risk) with Annex III defining high-risk use cases. Article 9 imposes risk management system obligations on providers. Article 27 establishes Fundamental Rights Impact Assessment obligations for deployers of certain high-risk AI systems. The HRDD instruments — UNGPs Principles 17–21, CSDDD Articles 8–9, Norwegian Transparency Act § 4 — establish salient human rights risk identification and prioritization methodology. CSRD/ESRS double materiality assessment, where applicable, provides the sustainability reporting frame for material AI-related risks.

The framework's distinctive position in this section, drawing on the translation layer (`03_translation_layer.md`):

*AI Act risk classification informs but does not replace human rights risk assessment.* An AI Act high-risk classification under Annex III tells the company that a use case is likely to produce adverse impacts on people. The HRDD assessment then asks the additional questions the AI Act does not ask: which people, where in the value chain, with what severity, what scope, what likelihood, what is our leverage to address.

*Conversely, an HRIA on an AI use case feeds back into AI Act conformity work.* When the HRDD process identifies an adverse impact, that finding has direct implications for AI Act Article 14 human oversight, Article 13 deployer information, Article 26 deployer use practices, and (for providers) Article 9 risk management.

*Proportionality is not an excuse for permissiveness.* The Section 2.5 commitment to proportionate risk classification means risk classification cannot be reflexively restrictive; it also means it cannot be reflexively permissive. The classification must be evidence-based, must engage with the actual use case, and must be revisited as deployment matures.

*Worker consultation is a cross-cutting requirement.* Risk assessments for AI use cases that materially affect workers cannot be conducted without worker consultation per Section 3 Requirement 3.5. The cross-reference is operationally binding.

---

## Executive commitment (Part 1 — Executive policy)

> *Generator output for Part 1. ~55 words.*
>
> **AI risk classification and impact assessment.** We classify AI risk proportionately and substantively, integrating AI Act product-safety classification with our existing human rights and data protection impact assessment. Risk findings under one regime inform but do not replace findings under the others. Worker consultation is part of impact assessment for AI use cases that materially affect workers.

---

## Section narrative (Part 2 — Operational detail)

> *Suggested policy text for Part 2. The Generator produces this language as the opening of the operational detail for this section, providing context for the requirements that follow.*
>
> **AI risk classification and impact assessment — operational detail.** Our approach to AI risk operates across three connected disciplines: AI Act risk classification (the product safety logic), human rights impact assessment (the HRDD logic), and data protection impact assessment (handled in Section 5 with cross-references here). These are connected but not equivalent. A finding under one informs work under the others; none of them substitutes for the others.
>
> *AI Act risk classification.* We classify AI systems we use or deploy according to the AI Act framework: prohibited practices (Article 5 — excluded under Section 3 Requirement 3.8 and elsewhere), high-risk systems (Article 6 with Annex III categories), limited-risk systems with transparency obligations (Article 50), and minimal-risk systems. Where we are a provider, additional risk management obligations under Article 9 apply.
>
> *Fundamental rights impact assessment.* Where we are a deployer of high-risk AI systems in categories specified by Article 27 — public sector bodies, private operators providing public services, deployers of credit scoring or insurance pricing AI under Annex III points 5(b) and 5(c) — we conduct a fundamental rights impact assessment before deployment.
>
> *Human rights impact assessment in our HRDD process.* Where AI use creates salient human rights risks in our operations or value chain, we identify, assess, and address those risks through our existing human rights due diligence process (Section 7 of this policy operationalizes this integration). The assessment uses UNGPs methodology and is integrated with our work under the Norwegian Transparency Act, CSDDD where applicable, and other HRDD instruments.
>
> *Translation between regimes.* We operate the three disciplines as distinct but connected: AI Act findings flag use cases warranting HRIA; HRIA findings inform AI Act compliance work; DPIA findings under Section 5 inform both. We do not allow one regime to substitute for the others.

---

## Generator behavior for this section

This section is heavily prescriptive (substance is determined by binding AI Act, HRDD instruments, and DPIA requirements). Generator behavior follows the cascading priority:

**Priority 1 — Existing risk and impact assessment frameworks.** If the company has uploaded a risk management policy, enterprise risk register, DPIA template, HRIA methodology, or CSRD/ESRS materiality assessment, the Generator extracts the existing risk vocabulary, methodology, and integration points. AI risk classification is integrated into the existing risk register rather than operating as a parallel track.

**Priority 2 — Adjacent company materials.** If the company has uploaded a Code of Conduct, sustainability policy, or compliance framework with risk-related commitments, the Generator draws on that voice and methodology.

**Priority 3 — Foundation language with configuration tailoring.** If no company material is available, the Generator produces foundation language meeting AI Act Articles 6–9 and 27, applicable HRDD impact assessment methodology, and the translation logic between regimes. Provider-side Article 9 risk management obligations activate only when Q7 indicates provider role. Article 27 FRIA obligations activate conditionally on the company's role and AI use case categories.

For the worker consultation cross-reference (within multiple requirements), Generator behavior follows the same cascade as Section 3 Requirement 3.5.

---

## Requirements

### Requirement 6.1 — AI Act risk classification of AI systems in use

**Statement.** The policy commits the company to classifying AI systems it uses or deploys according to the AI Act risk framework: prohibited practices under Article 5 (excluded — see Section 3 Requirement 3.8 and Section 4 Requirement 4.4), high-risk systems under Article 6 with reference to Annex I and Annex III, limited-risk systems with transparency obligations under Article 50, and minimal-risk systems. The classification is documented in the AI inventory (Section 4 Requirement 4.1) and informs all subsequent obligations under this policy.

**Tier:** 1b (binding under AI Act for in-scope AI systems; classification is the foundation of provider and deployer obligations).

**Scope:** All — applies regardless of ambition tier wherever the company uses or deploys AI systems within the AI Act's scope.

**Jurisdiction:** EU AI Act Articles 5, 6, 50, Annex I, Annex III. The Annex III categories most likely to surface for the framework's pilot users include: AI in employment / workforce management (point 4), AI in essential services such as credit, insurance, public services (point 5), AI in education and vocational training (point 3 for some sector contexts), AI in safety components of products under existing EU harmonization legislation (Annex I).

**Legal logic:** AI Act-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 5 (prohibited AI practices), Article 6 (classification rules for high-risk AI systems), Article 7 (amendments to Annex III), Annex I (Union harmonisation legislation), Annex III (high-risk AI systems referred to in Article 6(2)).
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 50 (transparency obligations for certain AI systems).
- *Cross-reference:* Section 3 Requirement 3.8 (prohibited uses); Section 4 Requirements 4.2–4.4 (Article 50 transparency obligations).
- *Interpretive:* European Commission guidelines on AI Act risk classification (most current version); AI Office implementing guidance.

**What to look for in a policy.** The policy should commit to AI Act risk classification of all AI systems in use, name the classification framework (prohibited / high-risk / limited-risk / minimal-risk) and its source articles, address how classification integrates with the AI inventory, specify who in the governance structure is accountable for classification (typically IT and Information Security per Section 2.4, with input from other functions for use case categorization), and address how reclassification operates as systems change.

**Assessment criteria:**
- *Covered:* The policy commits to AI Act risk classification, names the classification framework with article references, integrates with the AI inventory, allocates accountability, and addresses reclassification.
- *Partial:* The policy mentions AI risk classification but does not name the AI Act framework specifically, or allocates classification responsibility without addressing the multi-functional input required (especially for Annex III categorization).
- *Missing:* The policy is silent on AI Act risk classification, or treats AI risk as a generic IT risk category without the AI Act's specific framework.

**Generator behavior.** *(1) If the company has uploaded a risk classification methodology, enterprise risk register, or AI tool assessment framework, the Generator extracts the existing structure and integrates AI Act-specific classification dimensions. (2) If the company has uploaded a Code of Conduct or compliance framework with risk language, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language naming the AI Act four-tier classification with article references, integrating with the AI inventory commitment in Section 4 Requirement 4.1, and allocating classification accountability per Section 2 Requirement 2.4.*

---

### Requirement 6.2 — Identification of Annex III high-risk AI use cases

**Statement.** The policy commits the company to specifically identifying AI use cases in its operations that fall under AI Act Annex III high-risk categories. The most likely categories for typical deployer companies include: biometrics (point 1), critical infrastructure (point 2), education and vocational training (point 3), employment, workers management and access to self-employment (point 4), access to and enjoyment of essential private services and essential public services (point 5), law enforcement (point 6), migration, asylum and border control management (point 7), and administration of justice and democratic processes (point 8). Where the company uses AI in any Annex III category, the heightened obligations under Article 26 deployer requirements activate.

**Tier:** 1b (binding under AI Act for deployers of high-risk AI systems).

**Scope:** All — applies regardless of ambition tier wherever the company uses AI in Annex III categories.

**Jurisdiction:** EU AI Act Article 6(2), Annex III.

**Legal logic:** AI Act-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 6(2), Annex III.
- *Interpretive:* European Commission guidelines on Annex III categorization (most current version).

**What to look for in a policy.** The policy should commit to identifying Annex III categories applicable to the company's AI use, list the categories most likely to apply based on company sector and AI deployment, and address what activates when an Annex III categorization is identified (Article 26 deployer obligations including human oversight, monitoring, logs, fundamental rights impact assessment for relevant points, instructions for use compliance).

**Assessment criteria:**
- *Covered:* The policy commits to Annex III identification, names the relevant categories for the company's profile, and addresses what activates upon Annex III identification (Article 26 obligations).
- *Partial:* The policy mentions high-risk AI in general terms but does not specifically address Annex III categorization or the activation of Article 26 obligations.
- *Missing:* The policy is silent on Annex III categories despite material AI deployment in Annex III territory (most commonly point 4 employment AI).

**Generator behavior.** *(1) If the company has uploaded materials identifying their AI use cases (AI inventory, IT asset register), the Generator extracts the use cases and maps them against Annex III categories. (2) If the detailed questionnaire (D1, D2, D3) indicates specific high-risk use cases, the Generator addresses those specifically. (3) If no company material is available, the Generator produces foundation language listing the most commonly-applicable Annex III categories for the company's sector profile, with explicit activation of Article 26 obligations upon identification.*

---

### Requirement 6.3 — AI Act provider risk management obligations (where applicable)

**Statement.** Where the company is a provider of high-risk AI systems under the AI Act, the policy commits the company to operating a risk management system meeting Article 9 obligations: risk identification and analysis through the AI system's lifecycle, risk evaluation, adoption of risk management measures, and testing under realistic conditions. The risk management system covers known and reasonably foreseeable risks and adverse impacts on health, safety, and fundamental rights.

**Tier:** 1b (binding under AI Act Article 9 for providers of high-risk AI systems).

**Scope:** Activates only when the company self-identifies as a provider in Q7 of the core questionnaire. Deactivates as "Not applicable to your role" for deployer-only companies.

**Jurisdiction:** EU AI Act Article 9.

**Legal logic:** AI Act-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 9 (risk management system).

**What to look for in a policy.** For deployer-only companies, this requirement deactivates and surfaces in the diagnostic output as "Not applicable to your role." For provider companies, the policy should commit to operating a risk management system meeting Article 9 obligations across the AI system lifecycle, address each Article 9 element (identification, analysis, evaluation, management measures, testing), and integrate with the company's broader risk governance.

**Assessment criteria:**
- *Covered (for providers):* The policy commits to a complete Article 9 risk management system addressing all required elements.
- *Partial (for providers):* The policy addresses some Article 9 elements but not the full set, or operates risk management without integration with the company's broader risk governance.
- *Missing (for providers):* The policy treats the company as a deployer despite being a provider, or addresses provider risk management only superficially.
- *Not applicable:* For deployer-only companies, this requirement deactivates.

**Generator behavior.** *(1) Configuration-gated — activates only for providers per Q7. For deployer-only companies, the Generator produces no content for this requirement and the diagnostic output reports it as "Not applicable to your role." (2) For provider companies, the Generator extracts existing risk management methodology from uploaded company materials. (3) If no company material is available and the company is a provider, the Generator produces foundation language meeting Article 9 minimum across the AI system lifecycle.*

---

### Requirement 6.4 — Fundamental Rights Impact Assessment (FRIA) for applicable deployers

**Statement.** Where the company is a deployer of high-risk AI systems falling within AI Act Article 27's scope — bodies governed by public law, private operators providing public services, or deployers of high-risk AI systems referred to in Annex III points 5(b) (assessing creditworthiness or establishing credit scores) or 5(c) (insurance risk assessment and pricing) — the policy commits the company to conducting a Fundamental Rights Impact Assessment before putting the AI system into use. The FRIA addresses: the deployer's processes in which the high-risk AI system will be used; the period and frequency of use; the categories of natural persons and groups likely to be affected; the specific risks of harm; the human oversight measures; and the measures to be taken in case of materialization of risks. The FRIA is integrated with DPIA where required (Section 5 Requirement 5.4) and HRIA where required (Section 7).

**Tier:** 1b (binding under AI Act Article 27 for in-scope deployers).

**Scope:** Activates conditionally based on company role and AI use case category. Specifically activates for: public sector bodies, private operators providing public services, deployers of credit scoring AI under Annex III point 5(b), deployers of insurance pricing AI under Annex III point 5(c).

**Jurisdiction:** EU AI Act Article 27.

**Legal logic:** AI Act-derived; intersects with DPIA (Section 5) and HRIA (Section 7).

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 27 (fundamental rights impact assessment for high-risk AI systems).
- *Cross-reference:* Section 5 Requirement 5.4 (DPIA); Section 7 (HRDD integration).
- *Interpretive:* European Commission guidance on Article 27 FRIA template and methodology (most current version).

**What to look for in a policy.** Where the company is in FRIA scope, the policy should commit to FRIA for in-scope AI deployments, address each Article 27 element substantively, integrate FRIA with DPIA and HRIA where applicable, identify the human accountable for FRIA (typically the AI governance body per Section 2 with sustainability/human rights and data protection input), and address the timing (before deployment).

**Assessment criteria:**
- *Covered:* The policy commits to FRIA for in-scope deployments, addresses Article 27 elements, integrates with DPIA and HRIA, identifies accountability, addresses timing.
- *Partial:* The policy mentions FRIA but does not address the integration with DPIA and HRIA, or treats FRIA as a checkbox compliance exercise rather than substantive assessment.
- *Missing:* The policy is silent on FRIA despite the company being in scope, or treats FRIA as covered by DPIA without addressing the AI Act-specific dimensions.
- *Not applicable:* For deployer companies not in FRIA scope, the policy may state this explicitly with an activation flag for any future change in role or use case.

**Generator behavior.** *(1) Configuration-gated — activates conditionally based on Q1 (sector — public sector triggers FRIA), AI use case answers, and detailed questionnaire D2 (decision-making contexts including credit and insurance). (2) If the company has uploaded a DPIA template or HRIA methodology, the Generator integrates FRIA with those existing frameworks. (3) If no company material is available and the company is in FRIA scope, the Generator produces foundation language meeting Article 27 minimum with explicit integration with DPIA and HRIA.*

---

### Requirement 6.5 — AI impact assessment within HRDD process

**Statement.** Where AI use creates salient human rights risks in the company's own operations or value chain, the policy commits the company to assessing those risks through its existing human rights due diligence process (operationalized in Section 7), using UNGPs methodology — identification of actual and potential adverse impacts, prioritization based on severity and likelihood, prevention and mitigation measures, remediation where impacts occur, and tracking of effectiveness. The assessment is integrated with the company's existing aktsomhetsvurderinger or equivalent HRDD process and informs (does not replace) AI Act risk classification and FRIA work.

**Tier:** 1c (binding under HRDD law for in-scope companies — Norwegian Transparency Act § 4, CSDDD Articles 8–11, German LkSG, French Loi de Vigilance); Tier 2 for companies operating HRDD voluntarily.

**Scope:** Activates regardless of ambition tier where AI creates salient human rights risks. Legal floor activates for companies bound by HRDD law.

**Jurisdiction:** Norwegian Transparency Act § 4; EU CSDDD Articles 8, 9, 10, 11; German LkSG §§ 4–5; French Loi de Vigilance Article L. 225-102-4; UNGPs Principles 17–21.

**Legal logic:** HRDD-derived.

**Source citations:**
- *Binding:* Lov om virksomheters åpenhet og arbeid med grunnleggende menneskerettigheter og anstendige arbeidsforhold (åpenhetsloven), § 4.
- *Binding:* Directive (EU) 2024/1760 (CSDDD), Articles 8 (identifying impacts), 9 (prioritisation), 10 (preventing potential impacts), 11 (ending actual impacts).
- *Binding:* Lieferkettensorgfaltspflichtengesetz (LkSG, Germany), §§ 4–5.
- *Binding:* Loi n° 2017-399 relative au devoir de vigilance, Code de commerce Article L. 225-102-4.
- *Interpretive:* UN Guiding Principles on Business and Human Rights, Principles 17–21.
- *Cross-reference:* Section 7 of this rubric (HRDD integration); Section 8 (supply chain HRDD).

**What to look for in a policy.** The policy should commit to assessing AI-related human rights risks through existing HRDD methodology, name UNGPs salience-based methodology, integrate with the company's existing HRDD process (named explicitly), address the connection to AI Act risk classification (informs but does not replace), and commit to the full UNGPs cycle (identification, prioritization, prevention/mitigation, remediation, tracking).

**Assessment criteria:**
- *Covered:* The policy commits to AI human rights impact assessment through existing HRDD methodology, names UNGPs salience approach, integrates with named HRDD process, addresses translation logic with AI Act risk classification, and commits to the full UNGPs cycle.
- *Partial:* The policy mentions human rights impact of AI but does not integrate with existing HRDD process, or addresses some UNGPs cycle elements but not all.
- *Missing:* The policy treats AI risk as exclusively an AI Act matter without HRDD dimension, despite the company being in scope of HRDD law.

**Generator behavior.** *(1) If the company has uploaded a Transparency Act report, CSDDD due diligence document, modern slavery statement, or HRDD methodology, the Generator extracts existing HRDD vocabulary and methodology, and integrates AI risk assessment within that framework. (2) If the company has uploaded a sustainability strategy or materiality assessment, the Generator references the company's identified material topics and integrates AI. (3) If no company material is available, the Generator produces foundation language meeting the UNGPs cycle with explicit jurisdiction-specific integration based on Axis 1 exposure (Norwegian Transparency Act, CSDDD, German LkSG, French Loi de Vigilance as relevant).*

---

### Requirement 6.6 — Translation between AI Act risk classification, FRIA, DPIA, and HRDD impact assessment

**Statement.** The policy commits the company to operating the multiple risk and impact assessment regimes (AI Act risk classification, FRIA where applicable, DPIA where applicable, HRIA within HRDD) as connected but distinct disciplines. Findings under one regime inform work under the others. The policy does not allow one regime to substitute for the others, and does not produce parallel, disconnected assessments. The translation logic is documented in the company's risk and impact assessment methodology (or referenced from `03_translation_layer.md` of this framework where the company adopts the framework's approach).

**Tier:** 3 (framework principle). The translation logic is a framework-original commitment going beyond what any single binding instrument requires.

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original. Aligned with the integration logic running through CSDDD Article 7 (integrating due diligence into company policies and risk management systems).

**Legal logic:** Framework-original; informed by both AI Act-derived and HRDD-derived obligations.

**Source citations:**
- *Reference:* `03_translation_layer.md` of this framework (the substantive document explaining how AI Act and HRDD regimes interact).
- *Interpretive:* Directive (EU) 2024/1760 (CSDDD), Article 7 (integration).
- *Framework-original:* The translation logic between AI Act risk classification and HRDD impact assessment as a named operational discipline.

**What to look for in a policy.** The policy should commit to operating the regimes as connected but distinct, name the connection points (AI Act findings flag use cases for HRIA; HRIA findings inform AI Act compliance), commit to integrated rather than parallel assessment, and reference the methodology used to translate between regimes.

**Assessment criteria:**
- *Covered:* The policy commits to integrated assessment, names the connection points between regimes, references the methodology, and avoids producing parallel disconnected assessments.
- *Partial:* The policy mentions integration in general terms but does not specify the connection points, or describes integration that does not match operational practice.
- *Missing:* The policy treats the regimes as parallel separate compliance tracks, or substitutes one for another (e.g., treating DPIA as covering HRIA).

**Generator behavior.** *(1) If the company has uploaded an integrated risk and impact assessment methodology, the Generator extracts and references it. (2) If the company has uploaded separate DPIA, HRIA, and AI risk methodologies, the Generator notes the integration opportunity and produces language committing to integration going forward. (3) If no company material is available, the Generator produces foundation language committing to integrated assessment with reference to the framework's `03_translation_layer.md` document.*

---

### Requirement 6.7 — Pre-deployment risk and impact assessment

**Statement.** The policy commits that AI risk classification and impact assessment occur before deployment, not after. New AI systems do not enter productive use until classification (Requirement 6.1), Annex III identification (Requirement 6.2), provider risk management (Requirement 6.3 where applicable), FRIA (Requirement 6.4 where applicable), DPIA (Section 5 Requirement 5.4 where applicable), and HRIA within HRDD (Requirement 6.5 where applicable) have been completed and any required mitigations implemented. The AI governance body (Section 2 Requirement 2.1) is responsible for verifying pre-deployment completion.

**Tier:** 1b (binding under AI Act Articles 9 and 27 for pre-deployment timing of risk management and FRIA; binding under GDPR Article 35 for DPIA pre-deployment timing; binding under HRDD instruments for due diligence as a continuous process starting before activity).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Multiple binding instruments require pre-deployment timing — AI Act Articles 9, 27; GDPR Article 35; CSDDD Article 8 (identification of potential adverse impacts).

**Legal logic:** Both AI Act-derived and HRDD-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Articles 9, 27.
- *Binding:* Regulation (EU) 2016/679 (GDPR), Article 35.
- *Binding:* Directive (EU) 2024/1760 (CSDDD), Article 8.
- *Cross-reference:* Section 2 Requirement 2.1 (governance body); Section 2 Requirement 2.5 (proportionate risk classification).

**What to look for in a policy.** The policy should commit to pre-deployment timing for all risk and impact assessment regimes, identify the AI governance body as responsible for verifying completion, address the deployment gate (no productive use until completion), and address what happens when assessment surfaces material risks (mitigations required, deployment delayed or refused).

**Assessment criteria:**
- *Covered:* The policy commits to pre-deployment assessment across all applicable regimes, identifies the governance body as responsible for verification, addresses the deployment gate, and addresses material risk findings.
- *Partial:* The policy commits to pre-deployment assessment but does not address all applicable regimes, or commits without identifying the deployment gate.
- *Missing:* The policy permits AI deployment to proceed before assessment, treats assessment as post-deployment, or treats the deployment gate as an IT-only function without governance body verification.

**Generator behavior.** *(1) If the company has uploaded a deployment gate process, change management procedure, or governance review framework, the Generator extracts existing pre-deployment verification practice. (2) If the company has uploaded risk management methodology with pre-deployment elements, the Generator integrates those. (3) If no company material is available, the Generator produces foundation language committing to pre-deployment assessment across all applicable regimes with the governance body as the verification authority.*

---

### Requirement 6.8 — Worker consultation in AI risk and impact assessment

**Statement.** Where AI risk and impact assessment addresses use cases that materially affect workers, the policy commits to worker consultation as part of the assessment process, in line with Section 3 Requirement 3.5 and applicable codetermination law. Worker consultation is operationally integrated with assessment, not added afterward as a formality. The assessment cannot be considered complete without meaningful consultation where the AI use case materially affects workers.

**Tier:** 1c (binding under CSDDD Article 13 stakeholder engagement; binding under Platform Work Directive provisions; binding under national codetermination law).

**Scope:** Activates wherever AI risk and impact assessment addresses worker-affecting AI use cases.

**Jurisdiction:** EU CSDDD Article 13; EU Platform Work Directive; Norwegian Working Environment Act § 4-2, § 8 and Hovedavtalen LO-NHO; German Betriebsverfassungsgesetz; Netherlands Wet op de ondernemingsraden; UNGPs Principle 18(b).

**Legal logic:** Both AI Act-derived (Platform Work Directive intersection) and HRDD-derived.

**Source citations:**
- *Cross-reference:* Section 3 Requirement 3.5 (worker consultation before AI deployment).
- *Binding:* All sources cited in Section 3 Requirement 3.5 apply here.

**What to look for in a policy.** The policy should integrate worker consultation into the risk and impact assessment process (not as a separate step afterward), cross-reference Section 3 Requirement 3.5, name the consultation framework, and address what consultation contributes to assessment (worker perspective on impacts, surfacing risks the company has not identified, informing prioritization).

**Assessment criteria:**
- *Covered:* The policy integrates worker consultation into risk and impact assessment, cross-references Section 3 Requirement 3.5, names the framework, addresses what consultation contributes.
- *Partial:* The policy mentions consultation but does not integrate it into assessment, treating consultation as separate from risk analysis.
- *Missing:* The policy is silent on worker consultation in risk assessment, or treats risk assessment as exclusively a technical exercise without stakeholder input.

**Generator behavior.** *(1) Worker consultation framework extraction follows the same cascade as Section 3 Requirement 3.5. The Generator ensures the consultation reference in this section is consistent with the consultation framework named in Section 3. (2) The Generator addresses how consultation operationally integrates with risk assessment (what worker representatives are consulted on, when in the assessment process, what the consultation produces). (3) If no company material is available, the Generator produces foundation language committing to worker consultation as integrated with assessment, with cross-reference to Section 3 Requirement 3.5.*

---

### Requirement 6.9 — Ongoing reassessment as deployment matures

**Statement.** The policy commits to reassessment of AI risk classification and impact as deployment matures and as evidence accumulates about the AI system's actual performance and effects. Risk classifications are not static. Initial assessments based on intended use are revisited based on operational experience, surfaced incidents, evolving regulatory guidance, and changing context. The reassessment cadence is at minimum annual, more frequently for systems with significant deployment changes or surfaced concerns.

**Tier:** 1b (binding under AI Act Article 26 for deployer ongoing monitoring; binding under HRDD instruments — CSDDD Article 15 for monitoring at minimum every 12 months; Norwegian Transparency Act § 4 for continuous due diligence). Tier 2 for the broader best-practice element of evidence-based reassessment beyond minimum binding cadence.

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** EU AI Act Article 26; EU CSDDD Article 15; Norwegian Transparency Act § 4.

**Legal logic:** Both AI Act-derived and HRDD-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 26.
- *Binding:* Directive (EU) 2024/1760 (CSDDD), Article 15.
- *Binding:* Lov om virksomheters åpenhet og arbeid med grunnleggende menneskerettigheter og anstendige arbeidsforhold (åpenhetsloven), § 4.
- *Cross-reference:* Section 2 Requirement 2.7 (governance review cycle).

**What to look for in a policy.** The policy should commit to ongoing reassessment, specify the cadence (at minimum annual), address the triggers for reassessment beyond cadence (deployment changes, incidents, regulatory changes), integrate with the broader governance review cycle in Section 2.7, and address how reassessment findings flow back into risk classification, impact assessment, and any required FRIA / DPIA / HRIA updates.

**Assessment criteria:**
- *Covered:* The policy commits to ongoing reassessment, specifies cadence, addresses triggers beyond cadence, integrates with governance review cycle, addresses how findings flow back.
- *Partial:* The policy mentions reassessment but does not specify cadence or triggers, or treats reassessment as separate from governance review cycle.
- *Missing:* The policy treats AI risk classification as one-time, or commits to assessment without addressing what happens as deployment matures.

**Generator behavior.** *(1) If the company has uploaded materials with ongoing assessment cadences (risk register update cycles, due diligence reporting cycles, governance review cadences), the Generator extracts and integrates those. (2) If the company has uploaded a Transparency Act reporting cycle (annual due diligence report by 30 June), the Generator references that as the natural integration point. (3) If no company material is available, the Generator produces foundation language with at-minimum-annual cadence, triggers beyond cadence, and integration with Section 2 Requirement 2.7.*

---

## How this section activates across company profiles

**Profile A — Mid-size manufacturer with mature HRDD:** All nine requirements activate. AI Act risk classification (6.1) and Annex III identification (6.2) are operationally important given typical manufacturing AI deployment, which likely touches employment AI (Annex III point 4) for HR processes and may touch product safety AI under Annex I for manufacturing equipment. Provider obligations (6.3) deactivate. FRIA (6.4) likely deactivates — companies in this profile are typically not public sector bodies, public services providers, credit scoring, or insurance pricing deployers. HRIA within HRDD (6.5) activates strongly given mature HRDD process under Norwegian Transparency Act and forthcoming CSDDD scope. Translation logic (6.6) is operationally meaningful because the company will run multiple parallel assessment regimes. Pre-deployment timing (6.7) and worker consultation (6.8) activate fully given collective agreement framework. Reassessment (6.9) integrates with the annual Transparency Act reporting cycle.

**Profile B — Safety-critical operations company in group context:** All nine requirements activate. AI Act classification (6.1) is light at exploratory deployment stage but commits the company to classify as deployment grows. Annex III (6.2) is most relevant for employment AI if used (point 4) and potentially for safety-critical AI under Annex I given the sector. Provider obligations (6.3) deactivate. FRIA (6.4) deactivates. HRIA within HRDD (6.5) activates under Norwegian Transparency Act. Translation logic (6.6) is operationally important because the company runs parallel HSE risk processes that need to integrate with AI risk assessment. Pre-deployment timing (6.7) is centrally important given safety-critical sector — the deployment gate matters most here. Worker consultation (6.8) activates fully. Reassessment (6.9) activates.

**Profile C — Small specialty distributor below regulatory thresholds:** All nine requirements activate, but operationally lighter at 60 employees with light AI deployment. AI Act classification (6.1) applies even to small companies with simple AI tools. Annex III (6.2) likely activates around employment AI if the company uses any AI in HR processes. Provider obligations (6.3) deactivate. FRIA (6.4) deactivates. HRIA within HRDD (6.5) deactivates at the legally-binding level (companies below regulatory thresholds are not bound by Transparency Act or CSDDD) but surfaces as voluntary alignment opportunity per the framework's position. Translation logic (6.6) is light because there are fewer parallel regimes for a small non-HRDD-bound company. Pre-deployment timing (6.7) and worker consultation (6.8) activate but operationally lighter at 60 employees. Reassessment (6.9) activates with integration with whatever review cycle the small company operates.

The activation pattern shows how the section's nine requirements scale across very different company profiles. The substantive obligations are the same; the operational complexity scales with company size, sector, and regulatory exposure.

---

## Open items for review

**Translation logic (6.6) tier classification.** I tagged Requirement 6.6 as Tier 3 (framework principle) because the explicit translation logic between AI Act risk classification and HRDD impact assessment is framework-original. An argument exists for Tier 1c — CSDDD Article 7 integration logic could be read as requiring this kind of cross-regime integration. The substantive treatment is the same; the tier tag changes how the diagnostic surfaces non-compliance. Worth your view.

**FRIA placement (6.4) and Section 5.4 cross-reference — resolved.** FRIA was moved primarily to Section 6 from Section 5 in v0.1. Section 5 v0.3 now maintains a clean cross-reference to Section 6 Requirement 6.4 rather than treating FRIA as a DPIA element. Section 6.4 maintains a bidirectional cross-reference to Section 5 Requirement 5.4. The clean architecture: DPIA in Section 5, FRIA in Section 6, HRIA in Section 7, integration logic in Section 6.6.

**Scope of AI risk classification (6.1).** The requirement covers AI Act classification across all four tiers (prohibited / high-risk / limited-risk / minimal-risk). For most companies, the substantive work is identifying high-risk and limited-risk systems and applying appropriate obligations. Worth your view on whether the requirement needs to address minimal-risk AI explicitly (the framework's position is that minimal-risk AI still requires inventory and basic governance, just not heightened obligations).

**Length and density.** Section 6 came in at 9 requirements at heavy density. Total length is substantial. Worth your view on whether any requirements could be merged (for example, 6.1 and 6.2 are closely related and could potentially merge as a single classification requirement with sub-elements; 6.3 provider obligations could potentially merge with Section 2.6 provider governance obligations as a more general provider treatment).

**Annex III categories (6.2) listed in full.** I listed all eight Annex III categories. The most relevant for the framework's pilots are points 4 (employment) and 5 (essential services). Worth your view on whether the requirement should be focused on the most-likely-applicable categories or maintain the full list for completeness.
