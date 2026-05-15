# Section 4: Transparency and explainability

**Status:** Working draft v0.3
**Section position:** Section 4 of 12 in the rubric
**Configuration dependencies:** Most requirements activate at all ambition tiers because legal floor demands it. External transparency requirements activate based on Axis 1. Some requirements scale by AI deployment maturity.
**Density:** Medium (7 requirements).
**Mode:** Prescriptive throughout.
**Executive part weight:** Medium (40–60 words target).

---

## Changelog

### v0.3 — current

- **Pilot company names removed.** Generic company profiles replace named pilots. Section header renamed for consistency. Stray pilot-specific references in Requirement 4.6 Generator behavior also replaced with generic language ("small companies"/"mid-size and larger companies").

### v0.2

- **Executive commitment block added** at the top of the section, weighted medium per the configuration model v0.4 section weighting.

### v0.1
Initial draft. Seven requirements at medium density across three audience levels (workers, customers, public).

---

## Executive commitment (Part 1 — Executive policy)

> *Generator output for Part 1. ~55 words.*
>
> **Transparency and explainability.** People affected by our AI use have a right to know — workers, customers, suppliers, and the public. We disclose AI in customer interactions and AI-generated content; we maintain inventory and explainability of AI systems making decisions about people; we report substantively on our AI governance under applicable sustainability and due diligence reporting; and we publish a basic public statement of approach where no reporting obligation requires it.

---

## Section purpose

This section establishes how the company is transparent about its AI use to the audiences that have a right to know: workers (covered primarily in Section 3, with system-level transparency dimensions here), customers and end-users, suppliers, and the public.

The framework's transparency principle from Section 1 establishes that transparency is a *precondition* for the rest of the policy — accountability, consultation, due diligence, and grievance all depend on the people affected knowing AI is in play. Section 4 operationalizes that principle through specific disclosure requirements at each audience level.

Several binding instruments converge here. AI Act Article 50 imposes transparency obligations on providers and deployers of specific AI systems regardless of risk classification: chatbots, AI-generated synthetic content (including deepfakes), AI-generated content on matters of public interest, emotion recognition systems, and biometric categorization systems. GDPR Articles 13 and 14 establish information obligations to data subjects about personal data processing, including AI-driven processing. CSRD and ESRS standards require disclosure of material sustainability matters, which increasingly include AI use where it is material to the company's impacts on people and the environment. Norwegian Transparency Act § 5 requires public disclosure of due diligence work and findings — including AI-related findings where they emerge.

The framework's distinctive position in this section is that AI transparency is not a marketing function. It is a governance function. The disclosures required by this section serve the people affected by AI, not the company's communications strategy. A "transparency report" that markets the company's AI ethics without naming the AI systems in use, the risks identified, or the mitigations applied does not satisfy this section's requirements.

---

## Section narrative (the policy-level commitment)

> *Suggested policy text the Generator produces for this section, adapted to company configuration:*
>
> **Transparency and explainability.** People affected by our AI use have a right to know. Transparency is the precondition for accountability, consultation, and remedy — without it, the rest of this policy cannot operate.
>
> We commit to transparency at three audience levels:
>
> *Workers.* Workers know when AI is involved in decisions about their work (Section 3 of this policy operationalizes individual worker notification). At the system level, we maintain an inventory of AI systems in use that affect workers, and we share appropriate information about that inventory with worker representatives where they exist.
>
> *Customers and end-users.* When customers interact with AI, they know it. Where AI generates content shared with customers — whether text, images, audio, or video — we disclose that the content is AI-generated, in line with AI Act Article 50 obligations and our own commitment to honesty in customer relationships. We do not deploy chatbots that imitate human service representatives without disclosure. We do not deploy synthetic content that imitates real people without consent.
>
> *Public.* Where reporting obligations require public disclosure of our AI use (CSRD/ESRS, Norwegian Transparency Act § 5, sustainability reporting), we provide substantive information about the AI systems we use, the risks we have identified, the mitigations we apply, and the outcomes of our review processes. Where no obligation requires disclosure, we still publish a basic statement of our approach to AI governance, because transparency to the public is part of how we hold ourselves accountable.
>
> We commit to explainability where it matters. AI systems making or substantially supporting decisions about people are explainable to the humans accountable for those decisions and, on request, to the people affected. Explainability does not require us to publish proprietary algorithms; it does require us to be able to explain, in language a reasonable person can understand, what an AI system does, what data it uses, what its limitations are, and how a person can challenge an AI-driven outcome.

---

## Generator behavior for this section

This section is prescriptive. Generator behavior follows a consistent cascade across requirements.

**Priority 1 — Existing transparency commitments.** If the company has uploaded a sustainability report, Transparency Act report, modern slavery statement, CSRD/ESRS disclosure, customer terms of service, or other transparency-facing documents, the Generator extracts existing transparency vocabulary, audience framing, and disclosure cadences. Specific extraction targets: how the company refers to its public disclosures, what cadence operates (annual report, quarterly disclosure), what audience-facing language the company uses for customers and public.

**Priority 2 — Adjacent company materials.** If the company has uploaded a Code of Conduct or Communications policy with transparency principles, the Generator draws on that voice. The company website's existing AI-related disclosures, where present, are extracted.

**Priority 3 — Foundation language with jurisdictional and configuration tailoring.** If no company material is available, the Generator produces foundation language meeting AI Act Article 50, GDPR Articles 13–14, and applicable reporting regime minimum. CSRD/ESRS disclosure language activates only for in-scope companies. Norwegian Transparency Act § 5 reporting language activates only for in-scope companies. The framework's distinctive position — that transparency is a precondition rather than a marketing function — is preserved verbatim.

For the AI inventory requirement (4.1), Generator behavior extracts existing IT asset inventory or system catalog references where uploaded; if no such material is available, the Generator produces foundation language with placeholder for company-specific inventory framework.

For the explainability requirement (4.7), Generator behavior is largely universal — explainability obligations under AI Act Article 13 (provider-to-deployer) and Article 86 (deployer-to-affected-persons for high-risk systems) follow specific binding language that the Generator preserves, while the framework's broader explainability commitment is universal.

---

## Requirements

### Requirement 4.1 — AI system inventory and internal disclosure

**Statement.** The company maintains an inventory of AI systems in use across its operations, sufficient to support governance, deployer obligations under the AI Act, and the transparency commitments in this policy. The inventory identifies, at minimum: each AI system in use, its function or business purpose, its provider and deployment context, the data it processes, its risk classification under the AI Act (where applicable), and the human accountable for its use. Where worker representatives exist (works councils, unions, employee representative bodies), the inventory or appropriate summary is shared with them in line with applicable codetermination frameworks.

**Tier:** 1b (binding under AI Act Article 26 deployer obligations for high-risk AI systems; binding under Platform Work Directive Article 9 for digital labour platforms; established best practice for non-high-risk AI deployment). 1c where inventory is required to operationalize HRDD obligations (CSDDD Article 7, Transparency Act § 4).

**Scope:** All — applies regardless of ambition tier. Inventory is the foundation of every other obligation in this policy; companies cannot govern AI tools they do not know about.

**Jurisdiction:** EU AI Act Article 26 (deployer obligations including knowing what high-risk AI systems are in use); EU Platform Work Directive Article 9; Norwegian Working Environment Act on workplace control measures (where AI affects workers); CSDDD Article 7 (integration of AI into governance and risk management).

**Legal logic:** Cross-cutting. AI Act-derived primarily; HRDD-derived where inventory supports due diligence.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 26.
- *Binding:* Directive (EU) 2024/2831 (Platform Work Directive), Article 9.
- *Binding:* Directive (EU) 2024/1760 (CSDDD), Article 7.
- *Interpretive:* ISO/IEC 42001:2023 on AI management system inventory and asset management.

**What to look for in a policy.** The policy should commit to maintaining an AI system inventory, specify the minimum data fields, identify where the inventory lives (which function maintains it), commit to sharing with worker representatives where they exist, and address how the inventory is updated as new AI systems are deployed.

**Assessment criteria:**
- *Covered:* The policy commits to a structured AI inventory with minimum data fields named, identifies the maintaining function, addresses worker representative access, and addresses the update cycle.
- *Partial:* The policy mentions awareness of AI use but does not commit to a structured inventory, or commits without specifying fields or maintenance.
- *Missing:* The policy is silent on inventory, leaving the company unable to discharge AI Act Article 26 obligations or to operationalize the rest of this policy.

**Generator behavior.** *(1) If the company has uploaded an existing IT asset register, AI tool inventory, or system catalog, the Generator extracts the existing structure and adapts it to AI-specific governance fields. (2) If the company has uploaded data protection records (Article 30 records of processing under GDPR), the Generator notes the relationship — AI inventory and Article 30 records overlap but are not identical. (3) If no company material is available, the Generator produces foundation language with a structured inventory framework: tool name, supplier, function, data processed, AI Act risk classification, accountable human. The maintaining function is named based on Section 2's discipline allocation (typically IT or a designated AI governance lead).*

---

### Requirement 4.2 — Customer-facing AI disclosure (chatbots and conversational AI)

**Statement.** When customers or end-users interact with an AI system that simulates human conversation — chatbots, virtual assistants, AI-driven customer service tools — the policy commits the company to clear disclosure that the user is interacting with AI, not a human. Disclosure occurs at the start of the interaction, in language the user can understand, and is not buried in terms of service. The policy does not deploy AI in customer interactions in ways that imitate human service representatives without disclosure.

**Tier:** 1b (binding under AI Act Article 50(1) for providers and deployers of AI systems intended to interact directly with natural persons).

**Scope:** All — applies regardless of ambition tier wherever the company deploys customer-facing conversational AI.

**Jurisdiction:** EU AI Act Article 50(1); applicable consumer protection law; sector-specific honest-marketing standards.

**Legal logic:** AI Act-derived primarily.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 50(1) — providers and deployers of AI systems intended to interact directly with natural persons must ensure those systems are designed and developed in such a way that the natural persons concerned are informed they are interacting with an AI system, unless this is obvious from the perspective of a reasonably well-informed natural person taking into account the circumstances and the context of use.
- *Interpretive:* European Commission guidelines on Article 50 transparency obligations (most current version).
- *Interpretive:* Consumer protection authorities' guidance on AI in customer interactions (jurisdiction-specific).

**What to look for in a policy.** The policy should commit to clear customer disclosure when AI is the interaction partner, specify the form of disclosure (timing, language, accessibility), and exclude AI deployments that imitate human service representatives without disclosure.

**Assessment criteria:**
- *Covered:* The policy explicitly commits to disclosure when customers interact with AI, specifies form and timing of disclosure, and excludes deceptive imitation of human representatives.
- *Partial:* The policy mentions transparency in customer interactions but does not specify form or timing, or limits disclosure to terms-of-service notices that customers may not see at the point of interaction.
- *Missing:* The policy is silent on customer-facing AI disclosure, or permits AI to interact with customers without disclosure of its AI nature.

**Generator behavior.** *(1) If the company has uploaded customer-facing terms of service, customer service procedures, or AI deployment documentation, the Generator extracts existing customer-disclosure framing and ensures it meets Article 50(1) requirements. (2) If the company has uploaded a Code of Conduct or marketing/communications policy with honesty commitments, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting Article 50(1) minimum, including a specific disclosure protocol (disclosure at start of interaction, in language users can understand, accessible).*

---

### Requirement 4.3 — AI-generated content disclosure (synthetic content, deepfakes, AI-generated text)

**Statement.** Where the company deploys AI to generate content shared externally — synthetic text, images, audio, or video — the policy commits to disclosing that the content is AI-generated, in machine-readable form for technical compliance and in human-readable form for affected persons. This includes: AI-generated text in matters of public interest, AI-generated synthetic media (including but not limited to deepfakes), and AI-generated content presented as if it were human-authored. The policy does not deploy AI-generated synthetic content that imitates a real person without that person's consent.

**Tier:** 1b (binding under AI Act Article 50(2) for providers of AI systems generating synthetic content; binding under Article 50(4) for deployers of AI systems generating or manipulating image, audio, or video content constituting a deepfake; binding under Article 50(4) for deployers using AI to generate or manipulate text published on matters of public interest).

**Scope:** All — applies regardless of ambition tier wherever the company deploys generative AI for external content.

**Jurisdiction:** EU AI Act Article 50(2)–(4); applicable copyright and personality rights law; defamation law.

**Legal logic:** AI Act-derived primarily.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 50(2) — providers of AI systems generating synthetic audio, image, video, or text content must ensure outputs are marked in a machine-readable format and detectable as artificially generated or manipulated.
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 50(4) — deployers of AI systems generating or manipulating image, audio, or video content constituting a deepfake must disclose that the content has been artificially generated or manipulated. Deployers using AI to generate or manipulate text published with the purpose of informing the public on matters of public interest must disclose AI generation/manipulation.
- *Interpretive:* European Commission guidelines on Article 50 (most current version).

**What to look for in a policy.** The policy should commit to disclosure of AI-generated content in both machine-readable and human-readable forms, identify the categories covered (synthetic media, deepfakes, AI-generated text on matters of public interest), and exclude deployments that generate content imitating real persons without consent.

**Assessment criteria:**
- *Covered:* The policy commits to AI-generated content disclosure in both forms, identifies the relevant categories under Article 50(2)–(4), and addresses the consent requirement for synthetic content imitating real persons.
- *Partial:* The policy commits to disclosure but does not distinguish between provider obligations (machine-readable marking) and deployer obligations (human-readable disclosure), or covers only some categories of generative AI use.
- *Missing:* The policy is silent on AI-generated content disclosure, or permits generative AI deployment for external content without disclosure obligations.

**Generator behavior.** *(1) If the company has uploaded marketing/communications policies, content guidelines, or AI usage policies addressing generative AI, the Generator extracts existing disclosure framing. (2) If the company has uploaded customer-facing materials with disclosure language, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting Article 50(2)–(4) minimum, distinguishing provider machine-readable obligations from deployer human-readable obligations and addressing consent for synthetic content imitating real persons. The Generator notes that companies using generative AI tools (LLMs, image generators) provided by third parties typically have deployer obligations under Article 50(4) even when they are not providers under Article 50(2).*

---

### Requirement 4.4 — Disclosure of emotion recognition and biometric categorization systems

**Statement.** Where the company deploys AI systems for emotion recognition (outside the AI Act Article 5(1)(f) workplace prohibition) or biometric categorization (outside the AI Act Article 5(1)(g) prohibition on inferring sensitive characteristics), the policy commits to informing the natural persons exposed to those systems about their operation. The policy notes that emotion recognition in workplaces is prohibited except for medical or safety reasons (Section 3 Requirement 3.8 addresses the prohibition); biometric categorization for sensitive characteristics is prohibited regardless of context.

**Tier:** 1b (binding under AI Act Article 50(3) for deployers of emotion recognition or biometric categorization systems; cross-references AI Act Article 5(1)(f) and 5(1)(g) prohibitions handled in Section 3 Requirement 3.8).

**Scope:** Activates conditionally on company use of emotion recognition or biometric categorization systems (typically rare for the framework's pilot users; may activate in security, retail, healthcare, public sector contexts).

**Jurisdiction:** EU AI Act Article 50(3); GDPR Article 9 (special categories of personal data); cross-references AI Act Article 5(1)(f) and 5(1)(g).

**Legal logic:** AI Act-derived; intersects with GDPR for personal data dimensions.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 50(3) — deployers of emotion recognition or biometric categorization systems must inform natural persons exposed to those systems.
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 5(1)(f) and 5(1)(g) — prohibitions on emotion recognition in workplaces and biometric categorization for sensitive characteristics.
- *Binding:* Regulation (EU) 2016/679 (GDPR), Article 9 (special categories including biometric and health data).
- *Cross-reference:* Section 3 Requirement 3.8 of this rubric (prohibited AI uses affecting workers).

**What to look for in a policy.** Where the company uses or plans to use emotion recognition or biometric categorization systems, the policy should commit to informing affected persons in line with Article 50(3), confirm that prohibited deployments under Article 5(1)(f) and 5(1)(g) are excluded, and address the GDPR special category dimension where applicable. Where the company does not use such systems, the policy should commit that any future deployment will activate this requirement.

**Assessment criteria:**
- *Covered:* The policy addresses emotion recognition and biometric categorization disclosure where applicable, confirms exclusion of prohibited deployments, and addresses GDPR Article 9 dimension. For companies not currently in scope, the policy commits to activation upon future deployment.
- *Partial:* The policy mentions emotion recognition or biometric categorization without distinguishing permitted from prohibited uses, or addresses disclosure without addressing GDPR Article 9.
- *Missing:* The policy is silent on these system categories despite material exposure, or permits deployment without disclosure.

**Generator behavior.** *(1) Configuration-gated — activates conditionally based on the detailed questionnaire (D1, D2, D3) and any extracted information about emotion recognition or biometric system use. (2) If the company has uploaded materials addressing biometric data processing (often required under GDPR Article 9), the Generator extracts existing disclosure framing. (3) If no company material is available and the configuration profile indicates exposure, the Generator produces foundation language meeting Article 50(3) minimum with explicit cross-reference to Section 3 Requirement 3.8 prohibitions. For companies not currently in scope, the Generator produces a brief commitment that future deployment will activate this requirement, without burdening the policy with inapplicable detail.*

---

### Requirement 4.5 — Public disclosure of AI use under sustainability and reporting obligations

**Statement.** Where the company is subject to public reporting obligations that include AI use as a material disclosure topic — CSRD/ESRS sustainability reporting, Norwegian Transparency Act § 5 due diligence reports, modern slavery statements, sector-specific disclosure regimes — the policy commits to substantive public disclosure of AI use, risks identified, mitigations applied, and outcomes of review processes. Disclosure addresses AI's intersection with material sustainability matters: workforce, value chain, affected communities, and (where applicable) environmental impact.

**Tier:** 1b (binding under specific reporting laws). Activates only when the company is subject to such laws.

**Scope:** Tier B and Tier C ambition for the substantive reach (the company commits to disclosure that addresses workers, value chain, communities). Activates regardless of ambition tier where binding law mandates disclosure.

**Jurisdiction:** Directive (EU) 2022/2464 (CSRD) and ESRS standards (especially ESRS 2 General Disclosures, ESRS S1 Own Workforce, ESRS S2 Workers in Value Chain, ESRS S4 Affected Communities); Norwegian Transparency Act § 5; UK Modern Slavery Act § 54; Australian Modern Slavery Act 2018 (Cth); Canadian Bill S-211; California SB 657.

**Legal logic:** HRDD-derived primarily (the reporting laws are HRDD instruments); CSRD/ESRS sits alongside as the EU sustainability reporting framework.

**Source citations:**
- *Binding:* Directive (EU) 2022/2464 (CSRD) and Commission Delegated Regulation (EU) 2023/2772 (ESRS standards).
- *Binding:* Lov om virksomheters åpenhet og arbeid med grunnleggende menneskerettigheter og anstendige arbeidsforhold (åpenhetsloven), § 5 (annual due diligence report by 30 June each year).
- *Binding:* UK Modern Slavery Act 2015, § 54.
- *Binding:* Modern Slavery Act 2018 (Australia, Cth).
- *Binding:* Fighting Against Forced Labour and Child Labour in Supply Chains Act (Canada, Bill S-211, 2024).
- *Binding:* California Transparency in Supply Chains Act (SB 657, 2010).
- *Cross-reference:* Section 8 Requirement 8.9 of this rubric (public reporting on supply chain AI risks).

**What to look for in a policy.** The policy should commit to addressing AI in mandatory public reporting where applicable, name the specific reporting obligations the company is subject to, address AI's intersection with the reporting framework's material topics (workforce, value chain, communities, environment), and ensure consistency between the AI policy and what the company actually reports.

**Assessment criteria:**
- *Covered:* The policy commits to substantive AI disclosure in mandatory public reporting, names the specific obligations, addresses material topic intersections, and ensures policy-to-reporting consistency.
- *Partial:* The policy mentions reporting in general terms but does not name specific obligations or address material topic intersections.
- *Missing:* The policy is silent on public reporting, or treats AI as not material to the company's sustainability disclosures despite obvious relevance.

**Generator behavior.** *(1) If the company has uploaded a Transparency Act report, modern slavery statement, sustainability report, or CSRD/ESRS disclosure, the Generator extracts existing reporting structure and integrates AI as a topic within that structure. The reporting language and cadence should match what the company already operates. (2) If the company has uploaded a sustainability strategy or materiality assessment, the Generator extracts the company's identified material topics and addresses AI's intersection with them. (3) If no company material is available, the Generator produces foundation language meeting the applicable reporting obligation minimum based on the configuration profile. For companies not subject to any such reporting, the Generator produces a brief commitment to voluntary public statement of approach, without prescribing reporting content.*

---

### Requirement 4.6 — Voluntary public statement of AI governance approach

**Statement.** Even where no binding reporting obligation requires it, the policy commits the company to publishing a basic public statement of its approach to AI governance. The statement names the company's AI governance commitments, identifies the AI governance body, and provides a contact point for AI-related concerns. The framework's position is that public accountability on AI governance is not optional even for companies not in CSRD or HRDD reporting scope; basic transparency to the public is part of how companies hold themselves accountable.

**Tier:** 3 (framework principle). The framework takes a position that voluntary public statement is appropriate even where no binding law requires it.

**Scope:** All — applies regardless of ambition tier. Companies above legal floor for reporting (4.5) satisfy this requirement through their mandatory disclosures.

**Jurisdiction:** Framework-original. Aligned with UNGPs Principle 21 (communicating about due diligence) and OECD Guidelines for MNEs Chapter II.

**Legal logic:** Framework-original; informed by HRDD-derived communicating principle.

**Source citations:**
- *Interpretive:* UN Guiding Principles on Business and Human Rights (2011), Principle 21 (communicating).
- *Interpretive:* OECD Guidelines for Multinational Enterprises (2023 update), Chapter II.
- *Framework-original:* The voluntary public statement commitment for non-reporting-scope companies.

**What to look for in a policy.** Where the company is not subject to mandatory public reporting (typically smaller companies or those in jurisdictions without HRDD reporting law), the policy should commit to a basic public statement. The statement should name AI governance commitments, identify the governance body, and provide a contact point. Where the company is subject to mandatory reporting (4.5 covers this), the voluntary statement is satisfied through the mandatory disclosure.

**Assessment criteria:**
- *Covered:* The policy commits to voluntary public statement (where mandatory reporting does not apply), names what the statement contains, and provides a contact point. Or, the policy is satisfied by mandatory reporting under Requirement 4.5.
- *Partial:* The policy commits to public statement in general terms but does not specify content or contact point.
- *Missing:* The policy is silent on public communication, leaving the company without a public-facing accountability mechanism for AI governance.

**Generator behavior.** *(1) If the company has uploaded a public AI policy, sustainability page content, or website governance disclosures, the Generator extracts existing public-facing voice. (2) If the company has uploaded a Code of Conduct with public commitment language, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language for a brief public statement framework — typically 200–400 words covering AI governance commitments, governance body identification, and contact point. For small companies (60–250 employees) below most reporting thresholds, the public statement is genuinely brief; for mid-size and larger companies (1,000+ employees) subject to sustainability reporting, it is more substantial and likely integrated with mandatory reporting under 4.5.*

---

### Requirement 4.7 — Explainability of AI systems making decisions about people

**Statement.** AI systems making or substantially supporting decisions about people are explainable to the humans accountable for those decisions and, on request, to the people affected. Explainability does not require publishing proprietary algorithms; it does require the company to be able to explain, in language a reasonable person can understand, what the AI system does, what data it uses, what its limitations are, and how a person can challenge an AI-driven outcome.

**Tier:** 1b (binding under AI Act Article 13 for provider-to-deployer transparency requirements; binding under AI Act Article 86 for deployer obligations to explain decisions to affected persons in high-risk AI contexts; binding under GDPR Articles 13(2)(f), 14(2)(g), and 22 for meaningful information about the logic involved in automated decision-making).

**Scope:** All — applies regardless of ambition tier wherever AI is used in decisions about people.

**Jurisdiction:** EU AI Act Articles 13, 14, 86; GDPR Articles 13(2)(f), 14(2)(g), 15(1)(h), 22; Council of Europe Framework Convention on AI Article 8.

**Legal logic:** Both AI Act-derived and GDPR-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 13 (transparency and provision of information to deployers — provider obligation supplying deployers with information necessary to understand and use the high-risk AI system).
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 86 (right to explanation of individual decision-making — deployer obligation to provide affected persons with clear and meaningful explanations of decisions taken using high-risk AI systems).
- *Binding:* Regulation (EU) 2016/679 (GDPR), Articles 13(2)(f) and 14(2)(g) (information about automated decision-making including meaningful information about logic involved); Article 15(1)(h) (right of access including meaningful information about logic); Article 22 (right not to be subject to decision based solely on automated processing producing legal or significant effects, with right to obtain human intervention, express point of view, and contest the decision).
- *Interpretive:* European Data Protection Board guidance on Article 22 right to explanation; European Commission guidance on AI Act Article 86 (most current version).
- *Interpretive:* Council of Europe Framework Convention on Artificial Intelligence (2024), Article 8.

**What to look for in a policy.** The policy should commit to explainability of AI systems making decisions about people, distinguish between explainability to humans accountable (internal) and to affected persons (on request, external), specify the substance of explanations (what the AI does, what data, what limitations, how to challenge), and clarify that proprietary algorithms need not be published but explanations must be substantive.

**Assessment criteria:**
- *Covered:* The policy commits to explainability, distinguishes internal and external explanation contexts, specifies the substance of explanations, addresses both AI Act Article 86 (where high-risk AI is deployed) and GDPR Article 22 (where solely automated decisions producing significant effects are made), and clarifies the proprietary-algorithm exclusion appropriately.
- *Partial:* The policy commits to explainability in general terms but does not specify substance or distinguish internal from external contexts, or claims proprietary algorithm protection in ways that defeat substantive explanation.
- *Missing:* The policy is silent on explainability, or treats AI as a black box that cannot be explained to affected persons.

**Generator behavior.** *(1) If the company has uploaded materials addressing GDPR Article 22 right to explanation procedures, the Generator extracts existing explanation framework. (2) If the company has uploaded customer service procedures with information-rights handling, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting AI Act Articles 13, 86, and GDPR Articles 13(2)(f), 14(2)(g), 22 minimum. The Generator distinguishes provider obligations under Article 13 (deactivates for deployer-only companies) from deployer obligations under Article 86 (activates for deployers of high-risk AI systems) and GDPR explanation obligations (activates for any solely automated decision-making producing significant effects on people).*

---

## How this section activates across company profiles

**Profile A — Mid-size manufacturer with mature HRDD:** All seven requirements activate with substantial reach. AI inventory (4.1) is operationally meaningful given existing AI deployment maturity. Customer-facing disclosure (4.2) and AI-generated content (4.3) activate where the company uses customer service AI or marketing-side generative AI. Public reporting (4.5) activates strongly — companies in this profile are subject to Norwegian Transparency Act § 5 reporting now and will be subject to CSRD/ESRS reporting and CSDDD Article 16 reporting as those phase in. Voluntary public statement (4.6) is satisfied through mandatory reporting. Explainability (4.7) activates wherever the company uses AI in employment or customer decisions.

**Profile B — Safety-critical operations company in group context:** All seven requirements activate. Inventory (4.1) is light at exploratory deployment but will grow as the company deploys AI tools. Customer-facing disclosure (4.2) is less material in B2B operational contexts. AI-generated content (4.3) may activate for marketing/communications use. Public reporting (4.5) activates under Norwegian Transparency Act § 5. The group context (parent's reporting practice) informs how subsidiary reporting is structured. Voluntary public statement (4.6) is satisfied through Transparency Act reporting.

**Profile C — Small specialty distributor below regulatory thresholds:** All seven requirements activate with lighter operational scope. Inventory (4.1) is small (digital tools, possibly demand forecasting). Customer-facing AI disclosure (4.2) and AI-generated content disclosure (4.3) are most material — companies in this profile may use generative AI for product descriptions, marketing content, and customer service. Public reporting (4.5) does not activate (companies below regulatory thresholds are not subject to Transparency Act, CSRD, or modern slavery regimes). The voluntary public statement (4.6) becomes meaningful here — it is the framework's commitment to public accountability for companies below the regulatory threshold.

This activation pattern shows the framework's three-audience transparency model at work. Worker-facing transparency (much of which is in Section 3) applies regardless of company size. Customer-facing transparency (4.2, 4.3, 4.4) scales with AI deployment in customer contexts. Public-facing transparency (4.5, 4.6) splits based on regulatory exposure: where binding reporting applies, mandatory disclosure carries the obligation; where it does not, voluntary public statement carries it.

---

## Open items for review

**Section 3 / Section 4 worker transparency overlap.** Section 3 covers individual worker notification (3.1) and information rights (3.3); Section 4 covers system-level worker transparency through AI inventory (4.1). The cross-reference in the section narrative directs readers to Section 3 for individual notification. Worth your view on whether this division is right or whether Section 4 should take the worker dimension entirely.

**Voluntary public statement (4.6) as Tier 3.** The voluntary public statement is a framework principle going beyond binding law. I tagged it Tier 3. An argument exists for making it Tier 2 (best practice) since UNGPs Principle 21 and OECD Guidelines arguably establish public communication as best practice for HRDD-conscious companies. The substantive treatment is the same; the tier tag changes how the diagnostic surfaces non-compliance. Worth your view.

**Generative AI specific handling (4.3).** I gave generative AI its own requirement because deployment is increasingly common across all three pilots and AI Act Article 50(2)–(4) creates specific obligations. An alternative would be to fold it into 4.2 (customer-facing AI). I went with separate treatment because the disclosure obligations are distinct and the synthetic content / deepfake dimension warrants explicit handling. Worth your view.

**Explainability (4.7) and proprietary algorithm protection.** The requirement clarifies that proprietary algorithms need not be published but explanations must be substantive. This is the area where companies and AI providers most often push back on transparency obligations. Worth your view on whether the framing is the right balance.
