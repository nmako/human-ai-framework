# Section 11: Connected internal policies

**Status:** Working draft v0.2
**Section position:** Section 11 of 12 in the rubric
**Configuration dependencies:** Activates at all ambition tiers because the continuity principle applies regardless of company configuration. Requirements scale by the company's existing policy infrastructure — a company with mature policy infrastructure has more named cross-references; a company with lighter infrastructure has fewer with explicit flags where foundational policies should exist.
**Density:** Light (4 requirements). Section is structurally a cross-reference index rather than substantive commitment territory. The substantive content lives in the policies it references; this section makes the connections explicit.
**Mode:** Prescriptive with hybrid elements. The framework's position on continuity is prescriptive; the specific policies named depend on the company's actual policy infrastructure.
**Executive part weight:** Operational-only (no executive commitment block).

---

## Section purpose

This section names the company's existing internal policies that the Human-AI policy connects to, operates alongside, or extends. It is the operational instantiation of the continuity principle from Section 1 Requirement 1.4: the Human-AI policy does not stand apart from the company's other commitments; it extends them.

The section serves three functions. First, it ensures the policy is operationally connected — staff reading the Human-AI policy can find the related policies they need to consult for fuller treatment of specific topics (data protection details in the Data Protection policy, grievance procedures in the Whistleblowing policy, supplier expectations in the Supplier Code). Second, it ensures the policy is consistent — by naming the cross-references, it makes visible where the Human-AI policy depends on the other policies being maintained and where conflicts would surface if other policies changed without coordination. Third, it surfaces gaps — where a company does not have a foundational policy that the Human-AI policy would normally extend, the section flags this as a structural issue the company needs to address.

The framework's distinctive position in this section is that the Human-AI policy is not self-contained. It is a layer on top of existing policy infrastructure that does most of the substantive work — data protection commitments live in the Data Protection policy, not duplicated in the AI policy; worker rights commitments operate through the Own Workforce or People policy with AI-specific extensions; ethical commitments live in the Code of Conduct. The Human-AI policy adds AI-specific obligations on top of these existing commitments.

This produces an operationally important consequence: a company without foundational policies cannot operate a Human-AI policy in isolation. The framework treats this as a gap the company needs to address rather than as a fact to work around. The Generator output for a company lacking foundational policies includes explicit flags identifying which foundational policies should exist alongside the Human-AI policy.

The section is weighted operational-only because the substantive commitments live in the cross-referenced policies. The Human-AI policy's executive part does not need to enumerate cross-references at policy-statement level; it needs to name the continuity principle (handled in Section 1's executive commitment) and rely on this section for operational specifics.

---

## Generator behavior for this section

This section is mixed mode but lean. Generator behavior follows the cascading priority:

**Priority 1 — Company-uploaded policies and named policy infrastructure.** If the company has uploaded specific policies, the Generator names them in the Human-AI policy by their actual titles (e.g., "Code of Conduct for [Company Name] Group," "Hovedavtalen-aligned employee participation procedure," "GDPR Compliance Framework"). The Generator uses the company's actual policy naming conventions rather than generic placeholders.

**Priority 2 — Company-input on policy infrastructure.** Where the questionnaire's policy integration questions (Q14–Q16 in the core questionnaire) or the input fields below indicate which foundational policies the company operates, the Generator names them in the AI policy. The Generator distinguishes between policies the company has uploaded (extraction-confirmed) and policies the company has named but not uploaded (input-only).

**Priority 3 — Foundation language with gap flagging.** If neither uploads nor input fields confirm a foundational policy, the Generator produces foundation language that references the expected policy type (e.g., "our Data Protection policy") with an explicit flag that this foundational policy should exist alongside the Human-AI policy. The diagnostic output for such companies includes a recommendation to develop the missing foundational policy. The framework treats missing foundational policies as a gap the company needs to address, not as a fact to work around.

---

## Requirements

### Requirement 11.1 — Named cross-references to existing internal policies

**Statement.** The policy names the existing internal policies that the Human-AI policy connects to, operates alongside, or extends. The cross-references are operationally specific — the Human-AI policy identifies each connected policy by its actual title and indicates the substantive area where the connection applies. The cross-references typically include, at minimum: the Code of Conduct (general ethical framework and worker commitments), the Data Protection / GDPR policy (data protection substance), the Own Workforce / People policy (worker rights substance, where this exists separately from the Code of Conduct), the IT and Information Security policy (operational AI deployment), the Whistleblowing procedure (grievance channels), and the Supplier Code of Conduct (supplier expectations, where this exists separately). Additional cross-references depend on the company's policy infrastructure.

**Tier:** 3 (framework principle — the continuity principle made operational). Tier 2 (established best practice in policy coherence).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original; informed by CSDDD Article 7 integration logic and Norwegian Transparency Act § 4(a) requirement to embed responsible business conduct in the enterprise's policies.

**Legal logic:** Framework-original; HRDD-derived.

**Source citations:**
- *Framework-original:* The named cross-references requirement operationalizes Section 1 Requirement 1.4 continuity principle.
- *Interpretive:* Directive (EU) 2024/1760 (CSDDD), Article 7.
- *Interpretive:* Lov om virksomheters åpenhet og arbeid med grunnleggende menneskerettigheter og anstendige arbeidsforhold (åpenhetsloven), § 4(a).
- *Cross-reference:* Section 1 Requirement 1.4 (continuity principle).

**Company input.** *Please tell us about your existing internal policies that this Human-AI policy will connect to. If you have uploaded specific policies, we will extract their titles. Where you have not uploaded but the policy exists, please name it so we can reference it accurately. Where a policy type does not yet exist in your organization, please indicate that — the framework will flag it as a gap.*

[FIELD: Title of your Code of Conduct or equivalent ethical framework]

[FIELD: Title of your Data Protection or GDPR policy]

[FIELD: Title of your Own Workforce, People, or HR policy]

[FIELD: Title of your IT and Information Security policy]

[FIELD: Title of your Whistleblowing or grievance procedure]

[FIELD: Title of your Supplier Code of Conduct, where applicable]

[FIELD: Any other policies the Human-AI policy should reference (specify name and area)]

**Foundation language (used by the Generator if no company input is provided, or as the basis for enrichment when company input is provided):** *This Human-AI policy connects to and operates alongside our existing internal policies: our [Code of Conduct] for general ethical framework and worker commitments; our [Data Protection / GDPR policy] for personal data substance referenced in Section 5; our [Own Workforce or People policy] for worker rights substance referenced in Section 3; our [IT and Information Security policy] for operational AI deployment; our [Whistleblowing procedure or grievance channel framework] for grievance pathways referenced in Section 10; and (where applicable) our [Supplier Code of Conduct] for supplier expectations referenced in Section 8.*

**Assessment criteria:**
- *Covered:* The policy names existing cross-referenced policies by their actual titles, identifies the substantive areas where each connection applies, and the named policies actually exist and have been uploaded or confirmed.
- *Partial:* The policy mentions cross-references in general terms ("we comply with our other policies") but does not name specific policies, or names policies that do not yet exist without flagging the gap.
- *Missing:* The policy is silent on cross-references to other internal policies, treating the Human-AI policy as self-contained.

**Generator behavior.** *(1) If the company has uploaded specific policies, the Generator extracts their actual titles and uses those in the Human-AI policy cross-references. (2) If the company has provided policy titles through the input fields, the Generator uses those names. (3) If neither extraction nor input fields provide a policy title for a foundational policy type, the Generator uses generic placeholder language ("our Code of Conduct," "our Data Protection policy") with an explicit flag that the foundational policy should be developed if it does not exist. The placeholder makes the gap visible.*

---

### Requirement 11.2 — Relationship type: extension, supplement, or operational integration

**Statement.** The policy is explicit about how the Human-AI policy relates to each cross-referenced policy. Three relationship types typically apply:

- **Extension** — the Human-AI policy extends an existing policy's commitments to address AI-specific dimensions without replacing the existing policy's substance. Example: the Data Protection policy continues to govern personal data; the Human-AI policy extends data protection commitments to address AI training data, special category inference, and automated decision-making.
- **Supplement** — the Human-AI policy operates alongside an existing policy, with each policy addressing distinct but related questions. Example: the IT and Information Security policy addresses general technical security; the Human-AI policy addresses AI-specific operational deployment with reference to the IT policy for security substance.
- **Operational integration** — the Human-AI policy integrates with existing operational infrastructure without adding new substantive commitments. Example: AI-related grievances flow through the existing Whistleblowing channel; the Human-AI policy connects to the Whistleblowing procedure without duplicating it.

The policy identifies the relationship type for each major cross-reference to avoid ambiguity about how the policies interact.

**Tier:** 2 (established best practice in policy architecture).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original.

**Legal logic:** Framework-original; informed by integration principles in HRDD methodology.

**Source citations:**
- *Framework-original:* The relationship type taxonomy is a framework approach to policy architecture.
- *Cross-reference:* Section 1 Requirement 1.4 (continuity principle).

**What to look for in a policy.** The policy should identify, for each major cross-reference, the relationship type (extension, supplement, or operational integration). This is not a checkbox exercise — the relationship type should match the actual operational interaction. A policy that claims "extension" of the Data Protection policy but operates as a parallel data protection track is mis-identifying the relationship.

**Assessment criteria:**
- *Covered:* The policy identifies relationship types for each major cross-reference, and the identified types match actual operational interaction.
- *Partial:* The policy identifies cross-references without naming relationship types, or names relationship types inconsistent with operational reality.
- *Missing:* The policy is silent on relationship types, leaving ambiguity about how the Human-AI policy interacts with other policies.

**Generator behavior.** *(1) For each cross-referenced policy identified through extraction or input, the Generator suggests the appropriate relationship type based on the substantive area (data protection: extension; IT security: supplement; whistleblowing: operational integration; Code of Conduct: extension). (2) The Generator presents these as the framework's default mapping; companies can adjust where their operational reality differs. (3) If no company-specific cross-references are available, the Generator produces the default mapping with the placeholder cross-reference language from Requirement 11.1.*

---

### Requirement 11.3 — Foundational policies that should exist alongside the Human-AI policy

**Statement.** Where a company lacks foundational policies that the Human-AI policy normally extends or supplements, the policy explicitly identifies the gap. The framework's position is that certain foundational policies should exist in any company operating a Human-AI policy: a basic Code of Conduct or equivalent ethical framework, a basic data protection commitment (proportionate to company size and personal data processing scope), a basic worker rights framework (employee handbook or Own Workforce policy), a basic IT use framework, and a grievance pathway. Where one or more of these is absent, the Human-AI policy commits to developing the missing foundational policy alongside the Human-AI policy implementation. The Human-AI policy does not operate effectively in a company without basic policy infrastructure; the gap is structural and needs to be addressed.

**Tier:** 3 (framework principle). The framework takes a position that certain foundational policies are baseline expectations for any company operating a Human-AI policy.

**Scope:** Activates only when the questionnaire or uploaded materials indicate absence of one or more foundational policies. Most likely to activate for small companies (60 employees and below) and for companies in jurisdictions or sectors where formal policy infrastructure is not standard practice.

**Jurisdiction:** Framework-original. Aligned with UNGPs Principle 16 on senior-level policy commitment and CSDDD Article 7 on integration into existing policies.

**Legal logic:** Framework-original.

**Source citations:**
- *Framework-original:* The baseline foundational policy expectation is framework-original.
- *Interpretive:* UN Guiding Principles on Business and Human Rights, Principle 16.
- *Interpretive:* Directive (EU) 2024/1760 (CSDDD), Article 7.

**What to look for in a policy.** Where the company has confirmed presence of all foundational policies, this requirement deactivates as "Not applicable — foundational policy infrastructure in place." Where one or more foundational policies are absent, the policy should identify the gap explicitly and commit to development with named timeframe and accountability.

**Assessment criteria:**
- *Covered (when foundational policies are present):* The requirement deactivates appropriately.
- *Covered (when foundational policies are absent):* The policy identifies the missing foundational policies explicitly, commits to development, names accountability, and addresses timeframe.
- *Partial (when foundational policies are absent):* The policy acknowledges missing foundational policies in general terms but does not commit to development with specificity.
- *Missing (when foundational policies are absent):* The policy is silent on missing foundational policies, attempting to operate the Human-AI policy without the foundational infrastructure it requires.

**Generator behavior.** *(1) Configuration-gated by Requirement 11.1 outputs. Where Requirement 11.1 confirms presence of all foundational policies (through uploads or input), this requirement produces "Not applicable — your foundational policy infrastructure is in place" language. (2) Where one or more foundational policies are flagged as absent, the Generator produces foundation language identifying the missing policies explicitly, committing to development, and recommending timeframe (typically 6–12 months for basic foundational policies). The Generator does not pretend the missing policies exist; it makes the gap visible and operationalizes the company's commitment to addressing it.*

---

### Requirement 11.4 — Consistency maintenance across policy updates

**Statement.** The policy commits the company to maintaining consistency between the Human-AI policy and the cross-referenced internal policies as those policies are updated. When a cross-referenced policy is revised, the AI governance body (Section 2 Requirement 2.1) reviews whether the revision affects Human-AI policy commitments and updates the Human-AI policy where needed. Conversely, when the Human-AI policy is revised, the relevant function reviews whether cross-referenced policies need corresponding updates. Consistency maintenance is integrated with the broader governance review cycle (Section 2 Requirement 2.7).

**Tier:** 2 (established best practice in policy governance).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** Framework-original.

**Legal logic:** Framework-original.

**Source citations:**
- *Framework-original:* The consistency maintenance commitment operationalizes the continuity principle.
- *Cross-reference:* Section 2 Requirement 2.1 (AI governance body); Section 2 Requirement 2.7 (governance review cycle).

**What to look for in a policy.** The policy should commit to consistency maintenance, identify accountability (typically the AI governance body for AI-side review and the relevant function head for policy-side review), integrate with the broader governance review cycle, and address what happens when conflicts emerge between policies.

**Assessment criteria:**
- *Covered:* The policy commits to consistency maintenance, identifies accountability, integrates with governance review, addresses conflict resolution.
- *Partial:* The policy mentions consistency in general terms but does not name accountability or integrate with governance review.
- *Missing:* The policy is silent on consistency maintenance, treating each policy revision in isolation.

**Generator behavior.** *(1) If the company has uploaded a policy governance procedure or document control system, the Generator extracts the existing approach and integrates AI policy consistency maintenance. (2) If the company has uploaded the broader governance review cycle materials, the Generator aligns consistency maintenance with the review cadence. (3) If no company material is available, the Generator produces foundation language assigning accountability to the AI governance body and the relevant function heads, integrating with Section 2 Requirement 2.7 review cycle.*

---

## How this section activates across company profiles

**Company with mature policy infrastructure (formal Code of Conduct, separate Data Protection policy, Own Workforce or People policy, IT policy, Whistleblowing procedure, Supplier Code, etc.):** All four requirements activate substantively. Requirement 11.1 names actual policies by their titles, populated through uploads and input. Requirement 11.3 deactivates as foundational infrastructure is in place. Requirement 11.4 integrates with established policy governance procedures.

**Company with moderate policy infrastructure (Code of Conduct exists, Data Protection policy exists, employee handbook serves as Own Workforce policy, IT policy informal, no separate Supplier Code):** Requirements 11.1 and 11.2 activate with the policies the company has, generic placeholders for the ones it doesn't have, and explicit flags for the gaps. Requirement 11.3 may activate partially around the Supplier Code gap. Requirement 11.4 activates with lighter governance procedures.

**Company with minimal policy infrastructure (small company with employee handbook, no formal Code of Conduct, no formal data protection policy, no IT policy):** Requirement 11.3 activates strongly — the framework flags multiple foundational policy gaps and commits the company to development. The Human-AI policy is positioned as one element of a broader policy framework the company is building. The diagnostic output for such a company makes this gap clearly visible.

This activation pattern reinforces the framework's position that the Human-AI policy is not a standalone artefact — it operates within a broader policy ecosystem. The Generator produces a usable Human-AI policy regardless of the company's policy maturity, but the diagnostic output makes the foundational gaps visible where they exist.

---

## Open items for review

**Section length and density.** Section 11 came in at 4 requirements at light density, operational-only weighting. The section is structurally a cross-reference index rather than substantive commitment territory; the density reflects this. Worth your view on whether 4 requirements is the right count or whether some could merge (11.1 and 11.2 could potentially merge as "named cross-references with relationship types").

**Hybrid mode elements (11.1).** Requirement 11.1 has seven input fields for policy titles. This is similar to Section 10's input field count. The fields are operationally necessary — the Generator needs to know what to name in the cross-references. Worth your view on whether the field count is right or whether the questions should be consolidated.

**Foundational policy expectation (11.3).** The framework's position that certain foundational policies should exist in any company operating a Human-AI policy is normative. Smaller companies in some jurisdictions may not have all of these as formal policies — but the practical commitments may exist (a 60-employee company may not have a formal Code of Conduct but has clear ethical commitments operationally). The framework's position is that the formal policy should exist. Worth your view on whether this is right or whether the framework should accept practical commitments without formal policy.

**No executive commitment block.** Per the configuration model section weighting, Section 11 is operational-only and produces no Part 1 content. The continuity principle is in Section 1's executive commitment; the operational specifics of cross-references do not warrant executive treatment. Worth confirming this is right.

**Naming convention guidance.** The framework expects the Generator to use the company's actual policy naming conventions. This requires the input fields to capture exact titles, and the extraction to preserve them. Worth your view on whether the naming convention question is sufficiently flagged or whether explicit guidance is needed (e.g., "use the title as it appears on the cover page of the policy document").
