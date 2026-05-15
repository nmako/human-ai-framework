# Translation layer: AI Act and human rights due diligence

**Status:** Working draft v0.1
**Companion to:** `00_rubric_scope.md`, `01_rubric_configuration_model.md`, individual rubric sections (especially Sections 7 and 8)
**Purpose:** Explains how the EU AI Act and human rights due diligence regimes (Norwegian Transparency Act, EU CSDDD, UK Modern Slavery Act, German LkSG, French Loi de Vigilance, UNGPs methodology) relate to each other, where they overlap, where they diverge, and how the rubric handles their intersection.

---

## Why this document exists

A diagnostic tool that treats AI governance and human rights due diligence as a single bundle of obligations is intellectually wrong and operationally unhelpful. Sophisticated legal teams will spot the conflation in five minutes. Companies trying to operationalize the framework will find themselves applying the wrong logic to the wrong question.

The two regimes use different legal architectures. The rubric has to be explicit about this. This document is the explanation.

---

## The two legal logics

### AI Act: product safety with role-based obligations

The EU AI Act (Regulation (EU) 2024/1689) is structured as a **product safety regulation**. Its legal architecture comes from the same EU tradition that governs medical devices, machinery, toys, and chemicals. The core logic:

- **Risk is classified by use case.** AI systems are categorized as prohibited (Article 5), high-risk (Article 6 and Annex III), limited-risk (Article 50 transparency obligations), or minimal-risk. The classification is determined by what the system *does*, not by who is harmed.
- **Obligations attach to roles.** Different obligations apply to providers (Articles 8–25 and 47–49), deployers (Articles 26–29), importers, and distributors. The same AI system carries different obligations for different actors in its lifecycle.
- **Compliance is verified through conformity.** High-risk AI systems require conformity assessment, technical documentation, post-market monitoring, and CE marking. The model is the same as for any other regulated product.
- **Enforcement is regulatory.** Member State market surveillance authorities and the AI Office enforce the regulation. Penalties scale with company turnover.

What the AI Act *does not do*: it does not impose duties of care toward affected persons across an entire value chain. It does not require companies to identify, assess, prevent, mitigate, and remediate adverse impacts on workers downstream of their operations. Those obligations live in a different legal architecture entirely.

### HRDD regimes: impact-based duty across the value chain

The Norwegian Transparency Act, EU CSDDD, German LkSG, French Loi de Vigilance, and the UNGPs methodology that underlies all of them use a fundamentally different legal logic.

- **Risk is identified by adverse impact on people.** The starting question is not "what does this product do?" but "where might our operations and value chain cause, contribute to, or be linked with adverse impacts on human rights and decent work?"
- **Obligations attach to the company's own operations and its value chain.** The duty extends to direct suppliers, subsidiaries, and (under CSDDD and Loi de Vigilance) further tiers where impacts are severe or likely. It does not respect product boundaries.
- **Compliance is procedural and substantive.** Companies must integrate due diligence into policies (CSDDD Article 7), identify and assess impacts (Article 8), prioritize (Article 9), prevent (Article 10), end actual impacts (Article 11), remediate (Article 12), engage stakeholders (Article 13), and monitor effectiveness (Article 15). The Norwegian Transparency Act § 4 expresses the same logic in compressed form.
- **Enforcement varies but increasingly includes civil liability.** France's Loi de Vigilance has had civil liability since 2017. CSDDD includes a civil liability regime (Article 29). Norwegian Transparency Act enforcement runs through the Consumer Authority with infringement fines.

What HRDD regimes *do not do*: they do not classify AI by technical risk category, prescribe conformity assessments, or impose role-based obligations along the AI value chain. Those mechanisms live in product safety regulation.

---

## Where the two regimes overlap

Despite their different architectures, the regimes overlap in several places. This is where the framework has to be most careful, because overlap is where companies most often misapply one regime's logic to the other regime's question.

**Worker impacts from AI use.** Under the AI Act, AI systems used in workforce contexts (recruitment, performance evaluation, task allocation, monitoring) are classified high-risk under Annex III, point 4. This triggers conformity, transparency, and human oversight obligations on providers and deployers. Under HRDD, the same use cases trigger an obligation to identify potential adverse impacts on workers, prevent or mitigate them, and provide remediation if impacts occur. Both regimes apply simultaneously to the same use case but ask different questions and require different answers.

**AI in the supply chain.** The AI Act stops at the contracting boundary — it does not impose obligations on a company for how its suppliers use AI on their own workers. HRDD regimes do reach this far: where a supplier uses AI in ways that cause or contribute to adverse impacts on its workers, the buying company has obligations under CSDDD Article 8 (identification), Article 9 (prioritization), Article 11 (ending impacts), and Article 12 (remediation), as well as under Norwegian Transparency Act § 4. This is the gap the framework's Section 8 addresses, and the gap most current AI governance templates miss entirely.

**Affected persons and stakeholder engagement.** Under the AI Act, deployers of high-risk AI systems making decisions about natural persons must inform those persons (Article 26(11)). Under CSDDD Article 13 and UNGPs Principle 18(b), companies must engage meaningfully with affected stakeholders, including workers and worker representatives. The two requirements are not equivalent — Article 26(11) is a notification duty; Article 13 is a participation duty — but they cover overlapping territory and a well-designed policy can satisfy both with integrated practice.

**Documentation and reporting.** AI Act high-risk systems require technical documentation (Article 11) and automatic logging (Article 12). HRDD regimes require public reporting on due diligence (Norwegian Transparency Act § 5; CSDDD Article 16; UK Modern Slavery Act § 54). The reports cover different content but overlap where AI use is itself a material due diligence finding.

---

## Where the two regimes diverge

**Provider obligations have no HRDD analogue.** AI Act Articles 8–25 (provider obligations) impose duties on the entity that builds, trains, or substantially modifies an AI system. HRDD does not parallel this — the only HRDD-relevant question about a provider is whether the provider's product, when used by the buying company or its suppliers, causes adverse impacts. For most companies that will use this rubric, this divergence is operationally moot because they are deployers, not providers.

**HRDD reaches further upstream than the AI Act.** A company subject to CSDDD must identify and address adverse impacts in its chain of activities, including upstream suppliers and (in some categories) downstream activities like distribution and storage. The AI Act has no equivalent reach into the value chain — its obligations stop at the company's role and its direct AI system relationships.

**HRDD applies to non-AI risks alongside AI risks.** A company's HRDD process addresses modern slavery, child labor, freedom of association, decent wages, occupational health and safety, environmental rights, and AI-related impacts in a single integrated process. The AI Act addresses only AI. Companies should not run a separate "AI HRDD" process — they should integrate AI as a category within their existing aktsomhetsvurderinger or equivalent.

**Trade controls operate on different logic again.** The US UFLPA, Mexico's Federal Law on Forced Labour, and similar instruments are formally trade controls, not HRDD regimes. They impose import bans with rebuttable presumptions, which functions operationally as heightened due diligence pressure but uses customs enforcement as its mechanism. The framework treats these in Requirement 8.11 specifically.

---

## How findings under one regime inform work under the other

This is the operational core of the translation layer. The two regimes are not substitutes, but findings under one materially inform work under the other.

**An AI Act risk classification informs but does not replace a salient human rights risk assessment.** If an AI system is classified high-risk under Annex III because it makes employment decisions, that classification tells the HRDD process: this is a use case where adverse impacts on workers are likely. The HRDD assessment then asks the additional questions the AI Act does not ask: which workers, where in the value chain, with what severity, what scope, what likelihood, and what is our leverage to address the risk? The AI Act classification is a useful starting signal; it is not the whole assessment.

**An HRIA on an AI use case feeds back into AI Act conformity work.** When the HRDD process identifies that a particular AI deployment is causing or risking adverse worker impacts, that finding has direct implications for AI Act compliance. The AI system's Article 14 human oversight measures may need strengthening. The Article 13 transparency information to deployers may need supplementation. The Article 26 deployer use-instructions may need modification. The Article 9 risk management system (for providers) may need updating to reflect the identified impact.

**Stakeholder engagement is jointly satisfied through integrated practice.** A company that consults workers and worker representatives on AI deployment under CSDDD Article 13 / UNGPs Principle 18 simultaneously builds the foundation for Article 26 deployer obligations on human oversight. A company that runs a Platform Work Directive Article 9 worker information process also generates documentation that supports HRDD Article 13. Designed well, the practices reinforce each other; designed badly, they multiply compliance burden.

---

## Three worked examples

### Example 1: AI scheduling tool used on factory floor

**Use case.** A manufacturing company deploys an AI scheduling system that determines worker shift assignments based on historical productivity data, demand forecasts, and worker availability.

**Under the AI Act.** The system is high-risk under Annex III, point 4 (employment, workers management, access to self-employment). The company is the deployer. Article 26 obligations apply: use according to instructions, ensure human oversight, monitor operation, keep logs, ensure input data is relevant, notify affected workers (Article 26(11)). If the company is also the provider (built or substantially modified the system), Articles 8–25 apply additionally.

**Under HRDD.** The deployment is a salient potential adverse impact on workers. Identification under CSDDD Article 8 / Transparency Act § 4 requires assessing whether the scheduling system causes or risks discriminatory outcomes (against women with caring responsibilities, workers with disabilities, older workers), wage suppression effects, work-family conflict, or breach of collective agreements. Prioritization under Article 9 considers severity, scope, and likelihood. Worker consultation under Article 13 / UNGPs Principle 18 is required before deployment because workers are the affected stakeholders. Monitoring under Article 15 must track actual outcomes, not just system performance.

**How the rubric handles it.** Section 6 (AI Risk Classification and Impact Assessment) requires both the AI Act classification *and* the salient human rights risk assessment, with explicit cross-referencing. Section 3 (Worker Rights and Human Oversight) requires worker notification (Article 26(11)) and consultation (Article 13) as cross-cutting commitments. Section 7 (HRDD Integration) requires the impact assessment for this use case to be integrated into the company's existing HRDD process.

### Example 2: Algorithmic management at a tier-2 supplier

**Use case.** A Norwegian furniture manufacturer's tier-2 leather supplier uses AI-driven productivity monitoring that automatically docks pay for workers identified as below performance thresholds.

**Under the AI Act.** The buying company has no AI Act obligations here. The system is at a supplier outside the company's role. The AI Act's reach stops at the contracting boundary.

**Under HRDD.** The buying company has substantive obligations. Under Norwegian Transparency Act § 4 and CSDDD Article 8, the company must identify this as a salient human rights risk in its value chain. Under Article 9, given the severity (wage deprivation), it likely warrants prioritization. Under Article 11, the company must take appropriate action — engaging the supplier, supporting remediation, or in extreme cases disengagement. Under Article 12, where actual adverse impacts on workers have occurred, remediation is required. Under Article 13, worker representatives at the affected supplier are stakeholders to engage with.

**How the rubric handles it.** This is exactly the case Section 8 was designed for. Requirements 8.2 (identification of supplier AI use), 8.3 (prioritization), 8.6 (monitoring), 8.7 (remediation), and 8.10 (worker consultation) all activate. The AI Act-derived requirements do not activate because there is no AI Act obligation. The legal logic tag on each requirement makes this distinction explicit.

### Example 3: Generative AI customer service tool

**Use case.** A company deploys a customer-facing generative AI chatbot that handles routine support queries.

**Under the AI Act.** The system is not high-risk under Annex III. Article 50 transparency obligations apply: customers must be informed they are interacting with an AI. If the chatbot generates content presented as human-authored, additional Article 50 obligations apply.

**Under HRDD.** The deployment is unlikely to constitute a salient adverse impact on workers if it merely augments customer service capacity. If the chatbot replaces customer service workers (workforce displacement), the workforce impact becomes salient and HRDD identification applies. If the chatbot is trained on customer data without adequate safeguards, the data protection dimension activates GDPR rather than HRDD.

**How the rubric handles it.** Section 4 (Transparency and Explainability) covers the Article 50 obligation. Section 6 (Risk Classification) requires assessment for both AI Act classification and HRDD relevance — and where HRDD relevance is low, the diagnostic surfaces the Article 50 obligation as the primary live obligation. This shows the framework's proportionality: not every AI use case triggers both regimes equally.

---

## What the rubric does at the intersection

Three operational implications follow from the translation layer:

**One. Each requirement carries an explicit Legal logic tag.** AI Act-derived, HRDD-derived, or both. This is one of the four tags in the configuration model (alongside Tier, Scope, and Jurisdiction). Reading any requirement, a reviewer can see immediately which legal logic it operates under and therefore which kind of compliance question it answers.

**Two. The Diagnostic produces findings grouped by legal logic.** When the tool assesses an uploaded policy, the output distinguishes "AI Act compliance findings" from "human rights due diligence findings" rather than blending them into a single narrative. Two columns or two tabs in the output — not one merged story. This is what allows sophisticated legal reviewers to use the diagnostic without immediately distrusting it.

**Three. The Generator produces policy text that respects the distinction.** A Human-AI policy generated by the framework explicitly addresses both legal logics in the relevant sections, with cross-references between them. Section 6 explicitly references both AI Act risk classification and HRDD salience assessment. Section 8 explicitly references both AI Act deployer obligations on supplier-provided AI and HRDD obligations on supplier-on-supplier-worker AI. The integration is visible in the policy itself, not just in the rubric's underlying logic.

---

## Limitations of this translation layer

This document covers the present state of the two regimes. Three things will change it over time:

The CSDDD is in transposition. Member State implementations will create national variations between 2027 and 2028+. Some Member States (notably Germany, France, Netherlands) have stronger national HRDD instruments that will continue alongside CSDDD; others will have only the CSDDD-transposed law. The translation layer will need an update once major implementations are clear.

The AI Act is still being operationalized. Commission delegated and implementing acts, AI Office guidance, and the General-Purpose AI Code of Practice will refine many obligations. Where the rubric currently relies on the regulation's plain text, future revisions may need to incorporate authoritative guidance.

The Council of Europe Framework Convention on AI (2024) and OHCHR B-Tech Project work on AI and human rights are evolving the global understanding of how these regimes interact. The rubric's interpretive grounding should track this work.

This is a v0.1 document. Significant updates expected through v1.0 and beyond.
