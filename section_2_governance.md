# Section 2: Governance and accountability

**Status:** Working draft v0.5
**Section position:** Section 2 of 12 in the rubric
**Configuration dependencies:** Section activates at all ambition tiers and jurisdictions. Some requirements scale by company size — what "designated governance body" means for a 60-employee company differs from what it means for a 2,400-employee company, and the assessment criteria reflect this. Provider-specific governance obligations activate only when the company self-identifies as a provider.
**Density:** Medium (7 requirements).
**Executive part weight:** Heavy (60–120 words target).

---

## Changelog

### v0.4 — current

- **Executive commitment block added** at the top of the section, weighted heavy per the configuration model v0.4 section weighting.

### v0.3
Generator behavior specifications added per requirement.

### v0.2
Hybrid mode for company-specific structural requirements (2.1–2.4); prescriptive mode for universal commitments (2.5–2.7).

### v0.1
Initial draft. Seven requirements at medium density.

---

## Executive commitment (Part 1 — Executive policy)

> *Generator output for Part 1. ~110 words. Adapted to company configuration with placeholders for company-specific information (CEO name, board cadence, governance body composition).*
>
> **Governance and accountability.** Decisions about AI in our company are made by people who are accountable for them. Our AI governance body brings together executive leadership, HR/people, supply chain or procurement, IT and information security, legal, and sustainability or human rights — with consolidation of disciplines named honestly where company size requires it. [CEO name or equivalent most-senior executive] is ultimately accountable; the board has oversight responsibility with AI on the standing risk and governance agenda. We commit to proportionate AI risk classification — neither reflexively restrictive (which produces shadow AI) nor reflexively permissive (which exposes affected people to harm). Governance is reviewed at minimum annually.

---

## Section purpose

This section establishes who governs AI within the company, how accountability is allocated, what the board's role is, and how governance scales to company size. It is the section that makes the rest of the policy operational — every other commitment in this document depends on someone being identifiably responsible for it.

The framework's position is that AI governance is a multi-disciplinary responsibility that cannot sit in IT alone, in HR alone, in Legal alone, or in Sustainability alone. AI deployment decisions touch employment, supply chain, customer relationships, data protection, human rights, and operational risk — each of which has its own governance home in most companies. The Human-AI policy connects those existing governance functions to a coherent body that owns AI deployment decisions across them.

The framework also takes a position on proportionality. Risk classification of AI tools cannot default to restrictive (which produces shadow AI as workers route around the policy) nor to permissive (which produces the harms the rubric is designed to prevent). The governance body is responsible for ensuring classification is proportionate to actual risk, neither reflexively cautious nor reflexively allowing.

This section is the second of two in the rubric (with Section 1: Principles) where the company's voice should be most visible. The company's existing governance structure — who its CEO is, how its board operates, how its functions are organized, what cross-functional bodies it has — cannot be inferred reliably from external sources. The framework establishes the principles and invites the company to populate the specifics.

---

## Section narrative (the policy-level commitment)

> *Suggested policy text the Generator produces for this section, adapted to company configuration. The Generator produces foundation language by default and enriches it with company-specific structural information drawn from inputs.*
>
> **Governance and accountability.** Decisions about AI in our company are made by people who are accountable for them. We do not delegate governance to a single function — AI touches too many parts of how we work for that to be honest.
>
> Our AI governance body brings together the disciplines that need to be at the table: executive leadership, people (HR), supply chain or procurement, IT and information security, legal and compliance, and sustainability or human rights. Where our size requires that one person hold multiple disciplines, that is named explicitly and we ensure the perspectives are represented even when the headcount is consolidated.
>
> [Company-specific: Name of CEO or most-senior executive ultimately accountable] is ultimately accountable for AI decisions in the company. The board has oversight responsibility, with AI as a standing topic on the board's risk and governance agenda.
>
> Accountability for specific AI decisions is shared by discipline. IT and information security are accountable for technical risk classification and operational deployment. HR (or our People function) is accountable for AI use that affects our own workers. Supply chain or procurement is accountable for third-party AI and supplier-related AI commitments. Legal is accountable for regulatory compliance. Sustainability or human rights is accountable for the integration of AI into our human rights due diligence.
>
> We commit to proportionate risk classification. Our governance body is responsible for ensuring our approach to AI risk is neither reflexively restrictive (which pushes AI use underground) nor reflexively permissive (which exposes our people and our suppliers' people to harm). Risk classification is proportionate to actual risk, evidence-based, and revisited as our deployment matures and as the risk landscape evolves.

---

## Generator behavior for this section

When generating this section, the Generator:

1. Produces the foundation language as the default content.
2. Enriches the language by drawing from any of the following sources where available: uploaded Code of Conduct (which often names the Board of Directors, leadership structure, and accountability allocations), public company website (leadership pages, organizational charts, governance disclosures, sustainability reporting), uploaded org charts or governance documents, the questionnaire's free-text inputs, and explicit company-input fields in the requirements below.
3. Where the company has provided specific names, structures, or accountability allocations, the Generator integrates them into the foundation language so the output reads as the company's voice.
4. Where no company input is available for a given field, the Generator produces the foundation language with placeholder phrasing the company can refine — for example, *"[CEO name] is ultimately accountable"* or *"our AI governance body comprises the disciplines named below; specific role-holders to be confirmed."* Blank fields never block generation.
5. For requirements 2.5, 2.6, and 2.7 (universal commitments), the Generator produces the foundation language without seeking company-specific tailoring.

The output is always usable from first generation. It becomes more tailored as the company provides more inputs.

---

## Requirements

### Requirement 2.1 — Multi-disciplinary AI governance body (hybrid mode)

**Statement.** The company designates a multi-disciplinary AI governance body responsible for AI deployment decisions, AI risk oversight, and the operationalization of this policy. The body brings together the disciplines that AI deployment materially touches: executive leadership, HR/people, supply chain/procurement, IT/information security, legal/compliance, and sustainability/human rights. Where company size requires consolidation of disciplines into fewer seats, the policy names which disciplines are consolidated and ensures the perspectives are represented even when the headcount is.

**Tier:** 2 (established best practice).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original structure, informed by AI Act Article 26 deployer obligations, CSDDD Article 7 integration logic, and ISO/IEC 42001 governance standards.

**Legal logic:** Cross-cutting.

**Source citations:**
- *Interpretive:* Regulation (EU) 2024/1689 (AI Act), Article 26.
- *Interpretive:* Directive (EU) 2024/1760 (CSDDD), Article 7.
- *Interpretive:* ISO/IEC 42001:2023.
- *Interpretive:* OECD AI Principles, Principle 2.4 (accountability).

**Company input.** *Please describe your AI governance body, or how you plan to govern AI decisions in your organization. If you already have a governance committee, working group, or designated function for AI matters, describe its composition. If your organization is small enough that multiple disciplines are held by one or two people, please describe that honestly. We will evaluate your structure against the foundation principle and produce specific feedback on whether all relevant disciplines are represented.*

[FIELD: Composition of your AI governance body — names of people, roles, or functions represented]

[FIELD: Meeting cadence and decision scope of the governance body]

[FIELD: Where one person covers multiple disciplines (small companies), describe the consolidation]

**Foundation language:** *Our AI governance body brings together the disciplines that need to be at the table: executive leadership, people (HR), supply chain or procurement, IT and information security, legal and compliance, and sustainability or human rights. Where our size requires that one person hold multiple disciplines, we name this explicitly and ensure the perspectives are represented even when the headcount is consolidated.*

**Assessment criteria (for evaluating company-submitted structure):**

- *Strong:* The company's submitted governance structure represents the relevant disciplines (executive leadership, HR/people, supply chain or procurement, IT, legal, sustainability or human rights), names specific people or roles, establishes meeting cadence and decision scope, and is honest about consolidation for smaller companies.
- *Can be strengthened:* The company's submitted structure represents some but not all relevant disciplines, or names roles without clarifying meeting cadence and decision scope, or claims a body that is not yet operational. Specific suggested strengthenings: add the missing discipline(s) most material to the company's AI footprint; commit to operational launch within a stated timeframe; clarify decision authority and escalation.
- *Conflicts with human rights or binding law:* The company's submitted structure places AI governance entirely within IT (without HR, sustainability, or legal involvement) in ways that would prevent the company from discharging deployer obligations under AI Act Article 26 or HRDD obligations under CSDDD Article 7. This framing cannot pass through; the Diagnostic produces a specific explanation and recommends a multi-disciplinary structure.

**Assessment criteria (when no company structure is submitted):** *Covered:* foundation language is included with placeholder phrasing the company can refine. *Missing:* the policy is silent on who governs AI in the company.

**Generator behavior.** *(1) If the company submitted their own governance body composition, the Generator integrates that structure (after Diagnostic evaluation). (2) The Generator extracts governance body information from uploaded Code of Conduct (which often names committees), public website leadership pages, organizational charts, and the questionnaire's free-text inputs. (3) If no company material is available, the Generator produces the foundation language with placeholder phrasing for body composition: "Our AI governance body comprises representation from executive leadership, HR/people, supply chain or procurement, IT and information security, legal and compliance, and sustainability or human rights. Specific role-holders to be confirmed by the company." Blank fields never block generation.*

---

### Requirement 2.2 — CEO ultimate accountability (hybrid mode)

**Statement.** The policy names the Chief Executive Officer (or, in groups and complex structures, the most senior executive with operational authority over the relevant entity) as the person ultimately accountable for AI use in the company. This accountability cannot be delegated downward to a Chief Information Officer, Chief Technology Officer, Chief AI Officer, or equivalent technical lead. Operational responsibility may be delegated; ultimate accountability rests with the CEO.

**Tier:** 2 (established best practice in corporate governance).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original structure, informed by CSDDD Article 7 and Article 25 governance integration; UNGPs Principle 16 on senior-level policy commitment.

**Legal logic:** Cross-cutting.

**Source citations:**
- *Interpretive:* Directive (EU) 2024/1760 (CSDDD), Article 7 and Article 25.
- *Interpretive:* OECD AI Principles, Principle 2.4.
- *Interpretive:* UN Guiding Principles on Business and Human Rights, Principle 16.

**Company input.** *Please name your CEO or the most senior executive ultimately accountable for AI use in your organization. The framework's position is that ultimate accountability rests at the most senior executive level and cannot be delegated to a technical lead (CTO, CIO, Chief AI Officer). If your structure differs and you have reason for a different allocation, please explain.*

[FIELD: Name and role of person ultimately accountable for AI use]

[FIELD: If different from CEO, explain the structure]

**Foundation language:** *[CEO or equivalent most-senior executive] is ultimately accountable for AI decisions in the company. Operational responsibility for specific aspects of AI governance is delegated to function heads and the AI governance body, but ultimate accountability rests at the most senior executive level.*

**Assessment criteria (for evaluating company-submitted accountability):**

- *Strong:* The company names the CEO or equivalent most-senior executive as ultimately accountable, clearly distinguishes ultimate accountability from operational responsibility, and does not delegate ultimate accountability to a technical lead.
- *Can be strengthened:* The company commits to senior accountability but is vague about who specifically holds it, or distinguishes accountability from responsibility without naming the accountable person. Specific suggested strengthening: name the specific role-holder.
- *Conflicts with human rights or binding law:* The company places ultimate accountability on a Chief Technology Officer, Chief AI Officer, or other technical lead, which is incompatible with the senior-level policy commitment expected under UNGPs Principle 16 and the integrated governance expected under CSDDD Article 7.

**Assessment criteria (when no specific role-holder is named):** *Covered:* the policy commits to CEO-level (or equivalent) accountability with placeholder phrasing for the specific person. *Missing:* the policy is silent on ultimate accountability or distributes it without senior-level commitment.

**Generator behavior.** *(1) If the company submitted a CEO name or senior executive accountable, the Generator integrates that name. (2) The Generator extracts CEO/senior executive identity from uploaded Code of Conduct (which often names the Board and CEO), the company website (leadership pages, governance disclosures), and public corporate registries where accessible. (3) If no specific name is available, the Generator produces foundation language with placeholder: "[CEO name] is ultimately accountable" or "Our CEO is ultimately accountable for AI decisions in the company" — leaving the specific name for the company to populate.*

---

### Requirement 2.3 — Board oversight of AI governance (hybrid mode)

**Statement.** The board of directors (or equivalent supervisory body) has oversight responsibility for AI governance. AI is a standing topic on the board's risk and governance agenda — not necessarily as a separate item at every meeting, but as a category that is reviewed regularly and that the board can engage with substantively. The board does not micromanage AI deployment but does verify that governance is operating, that material risks are surfaced, and that the company's AI use is consistent with its stated commitments.

**Tier:** 2 (established corporate governance best practice).

**Scope:** All — applies regardless of ambition tier. Board oversight requirements scale by company size; smaller companies without a formal board commit to equivalent senior leadership review.

**Jurisdiction:** Framework-original structure, informed by CSDDD Recital 78 and Article 25; CSRD/ESRS board engagement expectations; UK Corporate Governance Code; Norwegian Code of Practice for Corporate Governance (NUES).

**Legal logic:** Cross-cutting.

**Source citations:**
- *Interpretive:* Directive (EU) 2024/1760 (CSDDD), Recital 78 and Article 25.
- *Interpretive:* Directive (EU) 2022/2464 (CSRD) and ESRS standards.
- *Interpretive:* UK Corporate Governance Code (FRC), where applicable.
- *Interpretive:* Norwegian Code of Practice for Corporate Governance (NUES), where applicable.

**Company input.** *Please describe how your board (or equivalent supervisory body) oversees AI matters. If you do not have a formal board, describe the senior leadership review that performs an equivalent function. Please indicate the cadence (quarterly, semi-annual, annual) and the scope of board engagement with AI topics.*

[FIELD: Description of board oversight structure for AI matters]

[FIELD: Cadence of board AI review (quarterly / semi-annual / annual / other)]

[FIELD: For companies without a formal board, describe the equivalent senior leadership review]

**Foundation language:** *The board (or equivalent supervisory body) has oversight responsibility for AI governance. AI is a standing topic on the board's risk and governance agenda, reviewed at [cadence to be confirmed by company]. The board verifies that governance is operating, that material risks are surfaced, and that the company's AI use is consistent with its stated commitments.*

**Assessment criteria (for evaluating company-submitted oversight structure):**

- *Strong:* The company describes regular board oversight of AI, names a specific cadence, defines the scope of board engagement, and creates a clear reporting line from the AI governance body to the board. For companies without a formal board, the senior leadership review is named and operates equivalently.
- *Can be strengthened:* The company commits to board oversight but does not specify cadence or scope, or describes board oversight that does not match operational reality (e.g., the policy claims quarterly review but the board has not yet engaged with AI). Specific suggested strengthenings: commit to specific cadence; name the reporting line.
- *Conflicts with human rights or binding law:* The company explicitly states that AI is exclusively an operational matter not requiring board engagement, in ways that would conflict with CSDDD board oversight expectations or with the senior-level policy commitment expected under UNGPs Principle 16.

**Assessment criteria (when no oversight structure is submitted):** *Covered:* foundation language is included with placeholder cadence the company can refine. *Missing:* the policy is silent on board oversight.

**Generator behavior.** *(1) If the company submitted board oversight structure and cadence, the Generator integrates that. (2) The Generator extracts board structure from uploaded Code of Conduct, governance disclosures (annual reports, sustainability reports, governance code compliance statements where applicable), and public website governance pages. (3) If no company material is available, the Generator produces foundation language with placeholder cadence: "AI is reviewed by the board at [cadence to be confirmed by company; framework default: annually with material updates as needed]" — leaving cadence specifics for the company to confirm. For companies without a formal board, the foundation language refers to "equivalent senior leadership review" with the company filling in the specific structure.*

---

### Requirement 2.4 — Discipline-specific accountability allocation (hybrid mode)

**Statement.** The policy assigns specific accountability for AI-related decisions to the company's existing governance functions. IT and Information Security are accountable for technical risk classification, operational AI deployment, and information security implications. HR (or the function carrying People responsibilities) is accountable for AI use that affects the company's own workers. Supply chain or procurement is accountable for third-party AI and supplier-related AI commitments. Legal/Compliance is accountable for regulatory compliance with AI Act, GDPR, and applicable HRDD law. Sustainability or Human Rights (where this function exists) is accountable for integrating AI into existing human rights due diligence.

**Tier:** 2 (established best practice).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original structure.

**Legal logic:** Cross-cutting.

**Source citations:**
- *Interpretive:* Regulation (EU) 2024/1689 (AI Act), Articles 13, 14, 26.
- *Interpretive:* Directive (EU) 2024/1760 (CSDDD), Article 7.
- *Interpretive:* OECD Due Diligence Guidance for Responsible Business Conduct (2018).

**Company input.** *Please describe how you allocate accountability across functions in your organization. The framework's foundation expects accountability to be distributed across IT, HR/People, Supply Chain or Procurement, Legal, and Sustainability or Human Rights — but every organization is structured differently. If you have a Chief Sustainability Officer who covers human rights, name that. If your HR function is split across People Operations and a separate Talent function, describe it. We will evaluate the allocation against the principle that AI accountability cannot rest in one function alone.*

[FIELD: Functional accountability allocation for AI matters in your organization]

[FIELD: Where one person or function covers multiple areas, describe the consolidation]

**Foundation language:** *Accountability for specific AI decisions is shared by discipline. IT and information security are accountable for technical risk classification and operational deployment. HR (or our People function) is accountable for AI use that affects our own workers. Supply chain or procurement is accountable for third-party AI and supplier-related AI commitments. Legal is accountable for regulatory compliance. Sustainability or human rights is accountable for the integration of AI into our human rights due diligence.*

**Assessment criteria (for evaluating company-submitted allocation):**

- *Strong:* The company's submitted allocation distributes accountability across the relevant functions, is honest about the company's actual organizational structure, and addresses consolidation honestly for smaller companies. The allocation maps cleanly to the substantive sections of the policy (e.g., IT accountability for technical risk classification connects to Section 6; HR accountability connects to Section 3).
- *Can be strengthened:* The company's allocation covers some functions but not all, or describes allocation that does not match how the company actually operates, or names accountability without defining what accountable means operationally. Specific suggested strengthenings: add the missing functional accountability; clarify what accountability means in operational terms.
- *Conflicts with human rights or binding law:* The company's allocation concentrates all AI accountability in IT (which would prevent discharge of deployer obligations under AI Act Article 26 that depend on multi-disciplinary input) or treats AI as exclusively a technical matter. This framing cannot pass through.

**Assessment criteria (when no allocation is submitted):** *Covered:* foundation language is included with placeholder for company-specific functional names. *Missing:* the policy is silent on functional accountability allocation.

**Generator behavior.** *(1) If the company submitted their accountability allocation, the Generator integrates it. (2) The Generator extracts functional structure from uploaded organizational documents, Code of Conduct (which often names function heads and responsibilities), and the company website. Particular extraction targets: whether a sustainability function exists, whether HR is one function or multiple, whether procurement and supply chain are separate functions or combined, whether legal includes compliance. (3) If no company material is available, the Generator produces foundation language with placeholders for the functions: "Our IT and Information Security function is accountable for technical risk classification and operational deployment. Our [HR or People function] is accountable for AI use that affects our own workers..." — leaving function names for the company to populate where standard naming does not apply.*

---

### Requirement 2.5 — Proportionate risk classification commitment (universal — prescriptive mode)

**Statement.** The policy commits the company to proportionate AI risk classification. Risk classification of AI tools — whether for internal deployment, supplier-provided AI, or generative AI use — is neither reflexively restrictive (which produces shadow AI as workers route around the policy and creates harms the policy is meant to prevent) nor reflexively permissive (which exposes affected people to risk and exposes the company to regulatory and reputational consequences). The AI governance body is responsible for ensuring classification is evidence-based, proportionate to actual risk, and revisited as deployment matures and as the risk landscape evolves.

**Tier:** 3 (framework principle).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original. Aligned with AI Act Article 9 risk management proportionality.

**Legal logic:** Framework-original; informed by AI Act-derived risk management proportionality.

**Source citations:**
- *Interpretive:* Regulation (EU) 2024/1689 (AI Act), Article 9.
- *Interpretive:* OECD AI Principles, Principle 1.3 and Principle 2.2.
- *Framework-original:* The "neither reflexively restrictive nor reflexively permissive" framing.

**What to look for in a policy.** The policy should commit to proportionate risk classification, explicitly acknowledge that over-restriction produces shadow AI and under-restriction produces harm, place responsibility for proportionality with the governance body (not solely with IT), and commit to revisiting classification as evidence accumulates.

**Assessment criteria:**
- *Covered:* The policy commits to proportionate risk classification, names the governance body as responsible for proportionality, acknowledges the trade-off between over- and under-restriction, and commits to evidence-based revisiting of classifications.
- *Partial:* The policy commits to risk classification but does not address proportionality explicitly, or places responsibility for classification entirely with IT without governance body oversight.
- *Missing:* The policy treats AI risk classification as an IT-only function, or operates a default-deny approach without acknowledging the costs of over-restriction, or operates a default-allow approach without acknowledging the costs of under-restriction.

**Generator behavior.** *(1) Universal commitment — the Generator does not seek company-specific tailoring of substance for this requirement. (2) The Generator may extract risk-related language and approach from uploaded company risk management policies to harmonize voice with existing risk governance vocabulary. (3) If no company material is available, the Generator produces the foundation language for proportionate risk classification verbatim, with the framework's distinctive position on neither-restrictive-nor-permissive intact.*

---

### Requirement 2.6 — Provider-specific governance obligations (where applicable — prescriptive mode)

**Statement.** Where the company is a provider of AI systems under the AI Act (builds, trains, or substantially modifies AI systems placed on the market or put into service), additional governance obligations apply. The company designates accountability for AI Act provider obligations including conformity assessment, technical documentation, post-market monitoring, automatic logging, quality management system, and corrective actions. Provider obligations are integrated with deployer obligations rather than operated as a parallel governance track.

**Tier:** 1b. Activates only when the company is a provider; deactivates as "Not applicable to your role" for deployer-only companies.

**Scope:** Activates only when the company self-identifies as a provider (AI Act role from Q7 of the core questionnaire).

**Jurisdiction:** EU AI Act Articles 8–25, 47–49, 53–55.

**Legal logic:** AI Act-derived.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Articles 8, 9, 11, 12, 16, 17, 20, 47, 48.
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Articles 53–55 — for providers of general-purpose AI models.

**What to look for in a policy.** For deployer-only companies (the typical pilot user), this requirement deactivates and surfaces in the diagnostic output as "Not applicable to your role." For companies that are providers, the policy should designate accountability for the full provider obligation set and integrate provider obligations with deployer obligations operationally.

**Assessment criteria:**
- *Covered (for providers):* The policy designates accountability for the complete set of provider obligations and integrates provider with deployer obligations.
- *Partial (for providers):* The policy addresses some provider obligations but not the full set, or operates provider and deployer obligations as parallel tracks.
- *Missing (for providers):* The policy treats the company as a deployer despite being a provider, or addresses provider obligations only in passing.
- *Not applicable:* For deployer-only companies, this requirement deactivates.

**Generator behavior.** *(1) Configuration-gated — activates only when the company self-identifies as a provider in Q7 of the core questionnaire. For deployer-only companies, the Generator produces no content for this requirement and the diagnostic output reports it as "Not applicable to your role." (2) For provider companies, the Generator extracts any existing technical documentation, conformity assessment, or quality management system references from uploaded company materials. (3) If no company material is available and the company is a provider, the Generator produces foundation language naming the AI Act provider obligation set (Articles 8–25, 47–49, and 53–55 where applicable) with explicit accountability allocation to be confirmed by the company.*

---

### Requirement 2.7 — Governance review cycle (universal — prescriptive mode)

**Statement.** The policy commits to a regular governance review cycle for AI use, AI risk, and the policy itself. The review verifies that the AI governance body is operating, that AI deployment matches stated commitments, that risk classifications remain proportionate as evidence accumulates, that new AI deployments enter governance before going live, and that the policy itself reflects the company's current AI footprint and the evolving regulatory landscape. Review frequency is at minimum annual, with more frequent review for companies with rapid AI deployment growth or in periods of regulatory change.

**Tier:** 2 (established best practice; AI Act and HRDD instruments imply but do not strictly mandate review cycles for the deployer-only governance role).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Informed by AI Act Article 26 (deployer monitoring); CSDDD Article 15 (monitoring at minimum every 12 months); Norwegian Transparency Act § 4 (continuous due diligence).

**Legal logic:** Cross-cutting.

**Source citations:**
- *Interpretive:* Regulation (EU) 2024/1689 (AI Act), Article 26.
- *Binding:* Directive (EU) 2024/1760 (CSDDD), Article 15.
- *Binding:* Lov om virksomheters åpenhet og arbeid med grunnleggende menneskerettigheter og anstendige arbeidsforhold (åpenhetsloven), § 4.

**What to look for in a policy.** The policy should commit to regular review of AI governance, AI risk, and the policy itself; specify the review cadence (at minimum annual); identify the governance body as responsible for review; and commit to revising the policy where review surfaces material gaps.

**Assessment criteria:**
- *Covered:* The policy commits to regular review at named cadence (at minimum annual), assigns review responsibility to the AI governance body, addresses what review covers, and commits to policy revision where needed.
- *Partial:* The policy mentions review but does not specify cadence or scope, or commits to review without naming the responsible body.
- *Missing:* The policy is silent on governance review, or treats the policy as static once issued.

**Generator behavior.** *(1) Universal commitment with company-specific cadence. (2) The Generator extracts review cycle information from uploaded risk management policies, sustainability policies, or governance documents that may already establish review cadences for related governance topics. The framework default is at minimum annual review. (3) If no company material is available, the Generator produces foundation language with the at-minimum-annual default and assigns review responsibility to the AI governance body named in Requirement 2.1.*

---

## How this section activates across company profiles

**Profile A — Mid-size manufacturer with mature HRDD:** All seven requirements activate. The hybrid-mode requirements (2.1–2.4) draw rich company-specific detail from the existing Code of Conduct (which often names the Board of Directors, leadership responsibilities, and several functional accountabilities), the public website (leadership pages), and any uploaded organizational chart. The Generator output for companies in this profile will be substantively tailored. The universal requirements (2.5–2.7) apply prescriptively. Provider obligations (2.6) deactivate.

**Profile B — Safety-critical operations company in group context:** All seven requirements activate. The hybrid-mode requirements draw from the company's group context — some accountability allocations may sit at the parent level rather than at the subsidiary entity level, and the policy honestly names this consolidation. The Generator output reflects the parent-subsidiary dynamic without formally modeling cascade (which is a v1.1 feature). Universal requirements apply prescriptively.

**Profile C — Small specialty distributor below regulatory thresholds:** All seven requirements activate, but consolidation is significant for the hybrid-mode requirements. A 60-person company likely has two or three people who collectively cover the disciplines named in 2.1, with the policy honestly naming this. The CEO accountability (2.2) is operationally meaningful but the CEO and the AI governance lead may be the same person. Board oversight (2.3) probably operates through a small board or owners' group. Discipline allocation (2.4) names which disciplines are consolidated. The proportionality commitment (2.5) is particularly important at this scale because over-restriction is more likely to drive shadow AI in a small company without formal compliance infrastructure. Provider obligations (2.6) deactivate.

This activation pattern shows the framework's proportionality at work: governance requirements scale with company structure. A 60-person company that names consolidation honestly is treated as covered; a 2,400-employee company that names six seats but has only one functioning is treated as partial. The hybrid mode is what makes this scaling honest — the framework does not impose six separate seats on a company that does not have them, and does not pretend a six-seat structure exists where it does not.

---

## Open items for review

**The six disciplines.** The disciplines I went with: executive leadership, HR/people, supply chain/procurement, IT/information security, legal/compliance, and sustainability/human rights. Worth your view on whether this is the right set.

**Hybrid mode boundaries.** I placed 2.1, 2.2, 2.3, and 2.4 in hybrid mode because they depend on company-specific structure. I kept 2.5, 2.6, and 2.7 in prescriptive mode because they are positions the framework takes (proportionality), configuration-gated (provider obligations), or universal commitments (review cycle). Worth your view on whether this allocation is right.

**Section narrative voice and placeholders.** The narrative now contains explicit placeholders ([CEO name], [cadence to be confirmed], etc.) where company input is invited. Read this as a Generator output draft. If the placeholder approach reads too much like a fill-in-the-blank template, we can soften the framing.
