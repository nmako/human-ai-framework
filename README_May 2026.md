# Human-AI Governance Framework

**An open-source specification for integrating AI governance with Human Rights Due Diligence (HRDD)**

---

## What this is

This repository contains the **framework specification** for a diagnostic and policy generation tool for Human-AI governance. The framework's distinctive contribution is to treat AI-related impacts on people — including workers, supplier workers, customers, and affected communities — as a **category of human rights risk addressed within existing HRDD methodology**, not as a parallel AI-specific compliance discipline.

The framework integrates AI governance with binding HRDD instruments (Norwegian Transparency Act, EU CSDDD, German LkSG, French Loi de Vigilance, UK Modern Slavery Act, and others) and with global voluntary standards (UN Guiding Principles on Business and Human Rights, OECD Guidelines for Multinational Enterprises, ILO Conventions, Council of Europe Framework Convention on AI). It also integrates AI governance with binding AI regulation (EU AI Act, GDPR, Platform Work Directive) using a defined translation logic between AI Act product-safety classification and HRDD impact-based assessment.

---

## What the framework produces

For a company using the eventual tool (built from this specification), the framework produces three artefacts:

**1. A Human-AI Policy** — a single document with two visibly separated parts:
- **Part 1 — Executive policy (~2.5 pages):** Section-by-section executive commitments designed for board approval, public posting, and external use.
- **Part 2 — Operational detail (~7-10 pages):** Substantive operational language for sustainability, HR, IT, Legal, and AI governance body use.

**2. Suggested addition to the Code of Conduct** — approximately 100-200 words of executive-level commitment language that signals AI governance as part of the company's core ethical framework.

**3. Suggested addition to the Own Workforce Policy** — approximately 200-300 words of worker-facing language. Naming follows CSRD/ESRS S1 terminology so the artefact slots cleanly into companies that already use that framing for sustainability reporting.

The framework can operate in two modes:
- **Generator mode:** Produces the three artefacts above for a company starting fresh or replacing an existing policy.
- **Diagnostic mode:** Assesses an existing uploaded policy against the framework, identifies gaps, and produces specific suggestions for strengthening.

---

## What this repository is — and isn't

**This repository contains the framework specification.** It is the engineering document that defines what the framework checks, how it adapts to different companies, what the Generator produces in different scenarios, and how all the parts fit together.

**This repository is not the tool that companies use.** End users — companies running through the questionnaire to produce their Human-AI policy — will interact with a web-based tool built from this specification. They will not see the rubric documents directly.

This distinction matters because it shapes who this repository is for.

### Audience 1 — Project contributors

If you are contributing to the framework (proposing new requirements, refining existing requirements, updating citations as regulation evolves, expanding jurisdictional coverage), this repository is your working document. The twelve rubric sections, the configuration model, the translation layer, the Generator configuration, and the architectural notes are all here.

### Audience 2 — Tool builders

If you are building the web-based tool from this specification (whether on Claude Code, Lovable, Cursor, or any other platform), this repository is your source of truth. The rubric specifies the requirements the diagnostic checks. The configuration model specifies how the tool adapts to different companies. The Generator configuration specifies what the tool produces and how. The architectural notes cover hybrid mode (Sections 1 and 2), the translation between AI Act and HRDD logic, and other cross-cutting concerns.

### Audience 3 — Sophisticated evaluators

If you are an academic, regulator, NGO, sustainability consultant, lawyer, or policy researcher evaluating the framework's substantive rigor, this repository is your reference. Source citations are documented per requirement. The framework's positions are made explicit. Tier classifications (1a / 1b / 1c / 2 / 3) distinguish hard legal obligations from best practice from framework principles. The translation layer documents how the framework handles the intersection between AI Act and HRDD logic.

---

## Framework structure

The framework consists of twelve sections covering the full scope of Human-AI governance:

| Section | Topic | Mode | Density |
|---------|-------|------|---------|
| 1 | Principles | Hybrid | Light (4 requirements) |
| 2 | Governance and accountability | Hybrid | Medium (7 requirements) |
| 3 | Worker rights and human oversight | Prescriptive | Medium (8 requirements) |
| 4 | Transparency and explainability | Prescriptive | Medium (7 requirements) |
| 5 | Data protection and privacy | Prescriptive | Medium (6 requirements) |
| 6 | AI Risk Classification and Impact Assessment | Prescriptive | Heavy (9 requirements) |
| 7 | Human Rights Due Diligence Integration | Prescriptive | Heavy (9 requirements) |
| 8 | Supply chain and third-party AI | Prescriptive | Heavy (11 requirements) |
| 9 | Training and competence | Prescriptive | Medium (6 requirements) |
| 10 | Grievance and remedy mechanisms | Mixed | Medium-heavy (7 requirements) |
| 11 | Connected internal policies | Mixed | Light (4 requirements) |
| 12 | Applicable external frameworks | Mixed | Light (4 requirements) |

**Total:** approximately 75 requirements across the rubric.

**Mode meanings:**
- **Prescriptive:** The framework prescribes the substantive content because the substance is determined by binding law or established methodology. Assessment uses covered / partial / missing.
- **Hybrid:** The framework establishes a foundation but invites the company to express it in their own voice. Used in Sections 1, 2, and selected requirements elsewhere where company-specific structure determines content. Assessment uses strong / can be strengthened / conflicts with human rights or binding law.
- **Mixed:** Some requirements prescriptive, some hybrid, within the same section.

---

## How the framework adapts to different companies

The framework uses three configuration axes to scale across companies of different sizes, sectors, and regulatory contexts:

**Axis 1 — Regulatory exposure and AI Act role.** Which binding instruments apply to the company (AI Act, GDPR, CSDDD, Transparency Act, sector-specific instruments). The questionnaire derives this from company profile rather than asking companies to self-assess their own legal exposure.

**Axis 2 — Ambition scope.** Three tiers above the immovable legal floor:
- **Tier A:** Own operations
- **Tier B:** Own operations + supply chain
- **Tier C:** Own operations + supply chain + value chain (downstream activities, end-users, affected communities)

The legal floor cannot be lowered by ambition selection. Ambition determines the ceiling, not the floor.

**Axis 3 — Policy integration.** Which foundational internal policies the company already operates (Code of Conduct, Data Protection policy, Own Workforce Policy, Whistleblowing procedure, Supplier Code, etc.). The framework extends existing policies rather than replacing them; where foundational policies are absent, the framework flags this as a structural gap.

Each requirement carries four tags: tier (1a binding hard limit / 1b binding procedural / 1c binding duty of care / 2 established best practice / 3 framework principle), scope (which ambition tier activates), jurisdiction (which laws apply), and legal logic (AI Act-derived / HRDD-derived / both / framework-original).

---

## The framework's distinctive positions

The framework takes several positions that distinguish it from typical AI ethics templates and AI governance frameworks:

**One — AI is a category of human rights risk within existing HRDD.** Most current AI policy templates operate AI compliance as a parallel track separate from human rights due diligence. The framework's central argument is that this fragments the work and produces gaps. AI-related impacts on people are human rights matters and operate through the same UNGPs methodology applied to other human rights categories. Section 7 makes this argument explicit; Section 8 operationalizes it for supply chain; Section 6 documents the translation logic with AI Act risk classification.

**Two — Worker rights are not separable obligations.** A worker who does not know AI is in play cannot exercise oversight rights. Human oversight without override authority is rubber-stamping. Consultation after deployment is not consultation. Section 3 operationalizes these positions through specific requirements rather than aspirational language.

**Three — AI-driven worker surveillance is incompatible with the people-first principle.** The framework distinguishes between legitimate operational monitoring (occupational safety, equipment operation, anti-fraud, security access, payroll time) and AI-driven surveillance of worker behavior (keystroke logging, screen monitoring, sentiment analysis, individual productivity surveillance). The first is necessary in defined contexts; the second is excluded by the framework as a framework principle.

**Four — Voluntary alignment with global standards is baseline expectation.** Even where binding HRDD law does not apply to a company, the framework treats UNGPs methodology, OECD Guidelines, ILO Conventions, the Council of Europe Framework Convention on AI, ISO/IEC 42001, and the UNESCO Recommendation on AI Ethics as baseline commitments. Voluntary alignment operates as the path to accountability beyond legal compulsion.

**Five — The Human-AI policy extends existing infrastructure, not replaces it.** The framework's continuity principle means the policy is layered on top of the company's existing Code of Conduct, Data Protection policy, Own Workforce Policy, IT and Information Security policy, Whistleblowing procedure, and other foundational documents. Where these are absent, the framework treats it as a structural gap the company needs to address rather than as a fact to work around.

**Six — Proportionality is not permissiveness.** AI risk classification must be neither reflexively restrictive (which produces shadow AI as workers route around the policy) nor reflexively permissive (which exposes affected people to harm). The framework requires evidence-based classification proportionate to actual risk, revisited as deployment matures.

---

## Repository structure

```
.
├── README.md                                  This file
├── LICENSE.md                                 CC BY-SA 4.0 licensing terms
├── CONTRIBUTING.md                            Contribution guidelines
├── 00_rubric_scope.md                         Scope and methodology of the framework
├── 01_rubric_configuration_model.md           How the framework adapts to companies (Axes 1-3, questionnaire, output spec)
├── 02_generator_configuration.md              Voice, document structure, runtime behavior of the Generator
├── 03_translation_layer.md                    AI Act ↔ HRDD logic interaction
├── architectural_note_hybrid_mode.md          Hybrid mode for Sections 1 and 2
├── human_ai_framework_rubric_v1.0_COMPLETE.md Combined rubric document — all twelve sections in one file
├── legal_disclaimer_language_v0.1.md          Disclaimer language for tool implementations
├── section_1_principles.md                    Section 1: Principles
├── section_2_governance.md                    Section 2: Governance and accountability
├── section_3_worker_rights.md                 Section 3: Worker rights and human oversight
├── section_4_transparency.md                  Section 4: Transparency and explainability
├── section_5_data_protection.md               Section 5: Data protection and privacy
├── section_6_risk_classification.md           Section 6: AI Risk Classification and Impact Assessment
├── section_7_hrdd_integration.md              Section 7: Human Rights Due Diligence Integration
├── section_8_supply_chain.md                  Section 8: Supply chain and third-party AI
├── section_9_training.md                      Section 9: Training and competence
├── section_10_grievance.md                    Section 10: Grievance and remedy mechanisms
├── section_11_connected_policies.md           Section 11: Connected internal policies
└── section_12_external_frameworks.md          Section 12: Applicable external frameworks
```

---

## Getting started

### If you're building the tool

Read in this order:

1. **`00_rubric_scope.md`** — what the framework is for and what it covers
2. **`01_rubric_configuration_model.md`** — how the framework adapts to different companies; the questionnaire; the output specification
3. **`02_generator_configuration.md`** — what the Generator produces and how; voice and document structure
4. **`03_translation_layer.md`** — how AI Act and HRDD logic interact
5. **`architectural_note_hybrid_mode.md`** — special handling for Sections 1 and 2
6. **Section files** — twelve sections containing approximately 75 requirements

Each section file follows a consistent structure: status, configuration dependencies, executive commitment (Part 1 contribution), section narrative (Part 2 contribution), Generator behavior, and individual requirements with tier / scope / jurisdiction / legal logic tags, source citations, assessment criteria, and Generator behavior per requirement.

### If you're evaluating the framework

Start with this README, then read Section 1 (Principles) and Section 7 (HRDD Integration). These are where the framework's argument is most visible. Section 6 (Risk Classification and Impact Assessment) shows how the framework handles the translation between AI Act and HRDD logic. Section 8 (Supply chain) is where the framework's defining contribution gets the fullest operational expression.

Source citations are documented per requirement against binding instruments and interpretive frameworks. Tier classifications distinguish what the framework treats as hard legal obligation from what it treats as best practice or framework principle.

### If you're contributing

The repository is open for contribution under the licensing terms specified in `LICENSE.md`. Contributions are welcome in the following areas:

- **Jurisdictional expansion.** Adding HRDD instruments and AI regulation from jurisdictions currently not well-covered (Latin American instruments, African Union initiatives, Asia-Pacific regional frameworks).
- **Citation maintenance.** Updating citations as regulation evolves (CSDDD national transpositions, AI Act implementing guidance, sector-specific regulation).
- **Requirement refinement.** Proposing improvements to existing requirements based on operational experience.
- **Tool building.** Building the end-user tool from this specification.

Contribution guidelines are documented in `CONTRIBUTING.md`.

---

## What's in scope for v1.0

The current v1.0 release covers:

- The twelve-section rubric with approximately 75 requirements
- The configuration model with three axes and the questionnaire
- The Generator configuration document specifying voice, structure, and runtime behavior
- The translation layer document explaining AI Act ↔ HRDD logic interaction
- The architectural note on hybrid mode for Sections 1 and 2
- Three output artefacts (Human-AI Policy, Code of Conduct addition, Own Workforce Policy addition)
- Form A output (generic adaptable language) for all three artefacts

## What's deferred to future versions

- **v1.1: Form B output** (voice-matched, native-looking additions to the company's existing policies)
- **v1.1: Group / parent-subsidiary cascade architecture** for companies operating in group contexts
- **v1.1: Save and return later** functionality in the eventual tool
- **v2.0: Companion artefacts for value chain workers** (Supplier Code of Conduct addition; ESRS S2 alignment) and affected communities (ESRS S4 alignment, public-facing disclosure artefact)

---

## Limitations and honest scope

The framework is an open-source specification. It is not a substitute for legal advice. Companies adopting policies generated from this framework should obtain qualified legal review before adoption, particularly for binding obligations under the AI Act, GDPR, CSDDD, national HRDD instruments, and sector-specific regulation.

The framework operates under several explicit constraints:

**One.** The framework provides foundation language adapted to the company's configuration. The Generator output is intended as a starting point for company-specific refinement, not as a final adoptable artefact without internal review.

**Two.** The framework's voluntary alignment positions (UNGPs methodology applied to AI, OECD Guidelines alignment, voluntary public statement, etc.) reflect the framework's normative positions on responsible business conduct. Companies disagreeing with these positions can adapt the foundation language.

**Three.** The framework's translation logic between AI Act risk classification and HRDD impact assessment is framework-original architecture. It is informed by the underlying regimes but does not substitute for compliance with either regime independently.

**Four.** Jurisdictional coverage in v1.0 is concentrated on EU and Norwegian instruments with sector-specific extensions for the UK, Germany, France, Netherlands, US (UFLPA), and other comparable systems. Jurisdictional expansion is a contribution opportunity.

**Five.** The framework does not address every aspect of AI governance. Topics not covered in v1.0 (and not currently scoped for v1.1 or v2.0) include: AI provider obligations in detail beyond the deployer-first treatment, military and law enforcement AI uses, frontier AI safety research, AI's environmental impact at the model training and inference level.

---

## Versioning

The framework uses semantic versioning. v1.0 is the first complete release. v1.1 and v2.0 plans are documented in the configuration model. Individual rubric files carry their own version numbers (e.g., `Section 5 v0.4`) reflecting the iteration history of each component; framework-level releases consolidate component versions.

---

## License

The framework is released under the Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0). See `LICENSE.md` for full terms.

---

## How to engage

- **For tool building:** Read the specification, build the tool, and share back what you learn. The framework's design assumes its operational behavior will be tested through actual tool implementation.
- **For substantive evaluation:** Read the rubric sections, surface gaps or disagreements through GitHub issues or direct contact.
- **For jurisdictional expansion:** Propose new jurisdictional coverage through pull requests with citations to binding instruments and interpretive frameworks.
- **For pilot testing:** Three v1.0 pilots are confirmed. Open a GitHub issue or contact the maintainer to discuss further pilots.

---

## Acknowledgements

This framework draws on the work of many people and organizations. Particular acknowledgement is owed to:

- The UN Office of the High Commissioner for Human Rights B-Tech Project on AI and human rights
- The OECD's work on responsible business conduct and AI principles
- The Council of Europe's work on the Framework Convention on Artificial Intelligence
- The International Labour Organization's work on workers' rights in digital labour
- The European Data Protection Board's guidance on AI and personal data
- Academic and practitioner literature on HRDD methodology, including work by Shift Project, the Danish Institute for Human Rights, and various business and human rights research centers

Specific source citations are documented per requirement in the rubric files.

---

*Framework specification version 1.0. Last updated: May 2026. For questions, please open a GitHub issue.*
