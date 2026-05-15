# Architectural note: Hybrid mode for Sections 1 and 2

**Status:** Working draft v0.1
**Companion to:** `01_rubric_configuration_model.md`, `section_1_principles.md`, `section_2_governance.md`
**Purpose:** Documents the hybrid mode used in Sections 1 and 2 of the rubric, where the framework establishes foundation principles and structural requirements but invites companies to provide their own language and specifics.

---

## What hybrid mode is

The rubric operates in two modes depending on the section.

**Prescriptive mode** (Sections 3–12, mostly): the framework prescribes substantive content because the substance is determined by binding law (AI Act, GDPR, CSDDD, Norwegian Transparency Act) or by established best practice (UNGPs methodology, OECD Guidelines). Companies adopt the prescribed content or are flagged as missing the relevant commitment. Assessment uses three states: covered / partial / missing.

**Hybrid mode** (Sections 1 and 2, plus specific requirements within other sections): the framework establishes a foundation that the company is invited to express in their own voice. Companies submit their own principles or governance specifics; the Diagnostic evaluates the submitted language against the foundation and produces three-level feedback: strong / can be strengthened / conflicts with human rights or binding law. Where no company input is submitted, foundation language stands and assessment reverts to covered / missing.

The two modes coexist in the same rubric. The configuration model accommodates both. The Generator handles them differently.

---

## Why two modes

Sections 1 (Principles) and 2 (Governance and accountability) are where the company's voice should be most visible. In other sections of the rubric, the framework's voice is appropriate because the substance is largely determined by law:

- Section 3 (Worker rights and human oversight) transposes AI Act Article 14, GDPR Article 22, Platform Work Directive Article 7. The substance is what these laws say, not what each company decides.
- Section 5 (Data protection and privacy) transposes GDPR. Same.
- Section 6 (AI risk classification) transposes AI Act risk classification logic.
- Section 7 (HRDD integration) transposes CSDDD, Transparency Act, UNGPs methodology.
- Section 8 (Supply chain) transposes the same plus trade controls.

In these sections, prescribing substance is appropriate because the substance comes from outside the company and outside the framework. A company that does not transpose AI Act Article 14 has a compliance gap, and the framework should say so plainly.

Sections 1 and 2 are different. Principles are framework-original commitments — the framework takes a position on what a Human-AI policy is for, but companies often have their own AI-related thinking already articulated internally. Governance structures are company-specific — every company has its own board composition, its own functional organization, its own CEO. The framework prescribing six specific governance seats or one specific principle formulation would be presumptuous and would produce generic outputs companies dismiss.

Hybrid mode preserves the framework's substantive commitments (the foundation principles, the structural requirements) while inviting company voice on how those commitments are expressed.

---

## How hybrid mode works operationally

For each requirement in hybrid mode, the rubric provides:

**A statement of the requirement.** What the framework's foundation commits to. Same format as prescriptive-mode requirements.

**Tier, scope, jurisdiction, and legal logic tags.** Same as prescriptive-mode.

**Source citations.** Same as prescriptive-mode.

**Company input invitation.** Explicit text inviting the company to share what they have already developed internally, with the framing: *"If you have already discussed something internally, or if you have strong preferences, please insert it here. We will measure it against best-practice principles already in our system."*

**Empty input fields.** Specific places where the company provides their own language, names, structures, or details.

**Foundation language.** The framework's default text, used by the Generator if the company does not provide input, or as the basis for enrichment when the company does.

**Three-level assessment criteria for company-submitted language:**

- *Strong:* Meets or exceeds the foundation. The company's submitted language is at least as strong as the framework's foundation in its commitment, names the relevant specifics, and operates substantively.
- *Can be strengthened:* Partially aligns with the foundation. Specific suggested improvements are produced. The submitted language passes through but with feedback.
- *Conflicts with human rights or binding law:* Actively incompatible with foundational human rights principles or binding law. Cannot pass through. The Diagnostic produces a specific explanation and recommends the company revisit. This level is reserved for substantive incompatibility, not for language that is merely weaker than the foundation.

**Assessment criteria when no company language is submitted:** Reverts to covered / missing. Foundation language stands; the Diagnostic confirms its presence.

---

## Generator behavior in hybrid mode

The Generator always produces hybrid-mode sections using the foundation language as the default. It then enriches the language by drawing from any of the following sources where available:

- Uploaded internal policies (Code of Conduct, Own Workforce Policy, sustainability policies, IT policies)
- Public company website (mission, values, leadership pages, sustainability reporting, governance disclosures)
- Uploaded organizational charts or governance documents
- The questionnaire's free-text input field (Q18) and explicit company-input fields in the relevant requirements

Where the company has provided input — even just a name, a link, or a few sentences — the Generator integrates that into the foundation language to produce something that reads in the company's voice. Where no company input is available for a given field, the Generator produces the foundation language with placeholder phrasing the company can refine later (for example, *"[CEO name] is ultimately accountable"*).

The output is always usable from first generation. It becomes more tailored as the company provides more inputs. Blank fields never block generation.

---

## Diagnostic behavior in hybrid mode

The Diagnostic, when assessing an uploaded policy in hybrid-mode sections, recognizes that company-specific tailoring is expected and rewards it.

When the company has submitted their own language:
- Three-level evaluation applies.
- Strong outcomes are recognized as such — the policy is treated as fully covered.
- Can-be-strengthened outcomes are reported with specific suggestions.
- Conflicts-with-human-rights-or-binding-law outcomes are flagged with specific explanation and the company is advised to revisit.

When the company has not submitted their own language and the policy contains the foundation language:
- The policy is treated as covered.
- The Diagnostic notes that the company has used the foundation language as-is and may wish to develop their own articulation over time.

When the company has not submitted their own language and the policy lacks the foundation language:
- The policy is treated as missing the requirement.

---

## Where hybrid mode is used

**Section 1: Principles.** All four requirements (1.1, 1.2, 1.3, 1.4) operate in hybrid mode. Companies are invited to share their own principles; the Diagnostic evaluates against the foundation.

**Section 2: Governance and accountability.** Requirements 2.1 (governance body composition), 2.2 (CEO accountability), 2.3 (board oversight specifics), and 2.4 (discipline-specific accountability allocation) operate in hybrid mode because they depend on company-specific structure. Requirements 2.5 (proportionate risk classification), 2.6 (provider obligations), and 2.7 (review cycle) remain prescriptive — they are framework positions or universal commitments rather than company-specific structures.

**Other sections:** Mostly prescriptive. Specific requirements within Sections 3–12 may operate in hybrid mode where company-specific structure is genuinely material (for example, in Section 11 Connected internal policies, where the cross-references depend on the company's existing policy infrastructure). These will be flagged as such when those sections are drafted.

---

## What hybrid mode does not do

Hybrid mode is not a way for companies to opt out of substantive obligations. The "conflicts with human rights or binding law" gradation is the framework's hard line. Language that contradicts UNGPs Foundational Principle 11 (people-first commitment), AI Act Article 14 (human oversight), GDPR Article 22 (no solely automated decisions producing legal effects), or other binding obligations cannot pass through, regardless of how the company phrases it.

Hybrid mode is also not voice-matching of the entire generated policy to the company's existing register. That capability — Form B in the configuration model — is a v1.1 feature that requires the Generator to pattern-match register and structure across an entire document. Hybrid mode is more focused: the foundation language is enriched with company-specific phrasing in particular fields, not stylistically rewritten throughout.

---

## Versioning

Hybrid mode is introduced in Section 1 v0.2 and Section 2 v0.2 (May 2026). The configuration model v0.3 will be updated in v0.4 to reference hybrid mode formally. Until then, this architectural note serves as the documentation.
