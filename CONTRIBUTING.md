# Contributing to the Human-AI Governance Framework

Thank you for your interest in contributing. This document explains what kinds of contributions are welcome, how the review process works, and what is out of scope.

The framework is currently maintained by a single maintainer. The contribution process reflects this — substantive contributions go through review by the maintainer, and the framework's normative positions are not up for negotiation through pull requests. As the framework attracts additional maintainers, this process may evolve.

---

## What kinds of contributions are welcome

The framework benefits from contributions in five specific areas:

### 1. Jurisdictional expansion

The framework's v1.0 jurisdictional coverage concentrates on EU and Norwegian instruments, with sectoral extensions for the UK, Germany, France, Netherlands, US, and other comparable systems. Expansion of jurisdictional coverage is a high-priority contribution area.

Contributions in this area typically:

- Identify a binding instrument (law, regulation, directive) not currently covered by the framework
- Propose how it should be integrated — which requirements activate, what the legal logic is, what tier classification applies
- Provide accurate source citations (official text, official journal references, dates of application, transposition deadlines where relevant)
- Suggest specific language additions or modifications to rubric sections

Examples of jurisdictional coverage that would benefit the framework: Latin American HRDD instruments (Brazilian, Mexican), African Union initiatives, Asia-Pacific regional frameworks (Japanese METI Guidelines beyond current sourcing, Korean AI ethics frameworks), state-level US AI regulation (California, Colorado, New York City).

### 2. Citation maintenance

Regulation evolves. Citations need to be kept current as:

- CSDDD national transpositions are adopted (each EU member state's national transposing law)
- AI Act implementing guidance is published by the European Commission and AI Office
- Sector-specific AI regulation emerges
- Voluntary framework standards are updated (OECD revisions, ISO standard updates)
- Court decisions clarify the application of binding instruments

Contributions in this area typically:

- Identify a citation that is out of date or has been superseded
- Provide the corrected citation with official source
- Suggest where in the framework the update should be reflected

### 3. Requirement refinement

The framework's 75 requirements are the result of substantial drafting and review, but they are not final. Contributions that refine specific requirements are welcome where they:

- Improve the precision of a requirement statement
- Strengthen the assessment criteria (covered / partial / missing for prescriptive requirements; strong / can be strengthened / conflicts for hybrid requirements)
- Clarify Generator behavior cascades (what the Generator does at each priority level)
- Identify cross-references that should be added or that don't resolve correctly
- Surface inconsistencies between sections

### 4. Tool building and tool implementation feedback

The framework is designed to be implemented as a working tool. Anyone building such a tool — whether on no-code platforms (Lovable, Codex, Bubble), traditional web frameworks, or as an internal corporate compliance tool — is contributing to the framework's operational maturity.

Contributions in this area typically:

- Report what works and what doesn't when implementing requirements as actual tool logic
- Surface cases where the framework's specification is ambiguous or incomplete for build purposes
- Suggest clarifications to the Generator configuration or rubric to make implementation easier
- Share insights about the questionnaire flow, what users need help understanding, where the framework lands clearly

### 5. Documentation and accessibility

The framework specification is dense. Contributions that make it more accessible are welcome:

- Translations of the README or specific section files into other languages
- Plain-language explainers of the framework's structure or specific positions
- Worked examples showing how the framework applies to specific company profiles
- Visual diagrams of the framework's architecture, configuration model, or translation logic

---

## What is out of scope

The framework's normative positions are the result of deliberate analysis and are not up for negotiation through the contribution process. Pull requests challenging these positions will not be merged. The relevant venue for substantive disagreement with the framework's positions is academic discourse, professional commentary, or alternative framework development — not modification of this framework.

The framework's normative positions are documented in the README under "The framework's distinctive positions" and include:

1. AI is a category of human rights risk addressed within existing HRDD methodology, not in a parallel AI-specific compliance track
2. Worker rights are not separable obligations; transparency, oversight, consultation, and remediation operate together
3. AI-driven worker surveillance is incompatible with the people-first principle; the framework distinguishes worker surveillance from legitimate operational monitoring
4. Voluntary alignment with global standards (UNGPs, OECD Guidelines, ILO Conventions, CoE Framework Convention on AI, ISO/IEC 42001, UNESCO Recommendation on AI Ethics) is baseline expectation, not optional
5. The Human-AI policy extends existing infrastructure, not replaces it; the continuity principle is binding architecture
6. Proportionality is not permissiveness; AI risk classification must be neither reflexively restrictive nor reflexively permissive

Contributions are also out of scope when they:

- Propose adding requirements that conflict with the framework's normative positions
- Propose removing requirements addressing topics the framework has deliberately included (worker surveillance prohibition, voluntary alignment, framework's argument structure)
- Propose voice or tone changes that move away from plain corporate English (the framework's Form A voice is deliberate)
- Propose adding company-facing marketing language to the specification (the specification is for tool builders and evaluators, not end users)

---

## How to submit a contribution

### For minor changes (typo fixes, citation updates, link corrections)

Open a pull request directly with the change. The maintainer will review and merge if appropriate. Title the pull request clearly: "Citation update: [specific citation]" or "Typo fix: [section]."

### For substantive changes (new requirements, requirement refinements, jurisdictional expansion)

Open an issue first describing the proposed change. The issue should explain:

- What the change is
- Why it is appropriate (legal basis, methodological basis, operational basis)
- Which framework files would be affected
- How it interacts with existing requirements

The maintainer will respond with one of three outcomes:

- **Accepted in principle.** The change is welcome; please proceed with a pull request implementing it.
- **Accepted with modification.** The change is welcome but should be refined in specific ways. The maintainer will indicate what to modify.
- **Not accepted.** The change is out of scope, conflicts with the framework's positions, or is otherwise inappropriate. The maintainer will explain why.

This issue-first process protects contributor time. Producing a full pull request that won't be merged is frustrating; the issue-first process surfaces fit early.

### For substantive changes that affect multiple sections

Substantive changes affecting multiple sections (cross-cutting requirements, architectural changes, new configuration axes) require additional discussion. Open an issue describing the proposed change at a high level; the maintainer will work with you on scope, sequencing, and review process.

---

## Review standards

Contributions are reviewed against several standards:

**Substantive accuracy.** Source citations must be accurate. Legal positions must reflect actual binding text or accepted interpretation. Voluntary framework references must reflect the current version of the relevant framework.

**Consistency with framework architecture.** Contributions must fit within the framework's existing architecture — tier classifications, scope tags, jurisdiction tags, legal logic tags, mode (prescriptive vs hybrid), Generator behavior cascade.

**Consistency with framework voice.** Contributions must match the framework's plain English, first-person plural voice. Marketing language, academic register, and legal jargon are not appropriate.

**Cross-reference integrity.** Contributions affecting requirements that are cross-referenced from other sections must be coordinated with those cross-references. The maintainer may request modifications to multiple files to maintain cross-reference integrity.

**Citation format.** Source citations follow a consistent format: full official name on first reference within a section (e.g., "Regulation (EU) 2024/1689 (AI Act)"), shorter forms acceptable in subsequent references within the same section.

---

## Acknowledgement

Contributors are acknowledged in the framework's release notes for each version. Substantial contributions (significant jurisdictional expansion, major requirement refinements, significant tool implementations) may be acknowledged in the README's acknowledgements section.

Contributors retain copyright in their contributions but license those contributions under the same CC BY-NC-SA 4.0 license as the framework. By submitting a contribution, you agree to this licensing.

A note for contributors who want to use their own contributions commercially: contributors retain the right to use their own contributions in their own commercial work (for example, a sustainability consultant who contributes a citation update can still reference their own contribution in their consulting practice). What contributors cannot do — under the framework's license — is take the framework as a whole (including others' contributions) and use it commercially without a separate commercial license. The CC BY-NC-SA license applies to derivative works and to redistribution of the framework, not to the contributor's own subsequent use of their own contributed material.

---

## Commercial use

If your contribution is part of a broader commercial use of the framework (you're contributing as part of consulting work derived from the framework, or you intend to build a commercial offering on the framework), this is a commercial use scenario that requires a separate commercial license. See `LICENSE` for details.

Contributing technically and using the framework commercially are separate decisions. You can contribute citation updates, jurisdictional expansion, requirement refinements, or documentation improvements as standard contributions regardless of how you use the framework personally. But if your professional practice substantively builds on the framework (consulting offering, training program, productized tool), you need a commercial license alongside any contribution work.

For commercial licensing inquiries, contact natalia@humanaipolicy.org.

---

## Communication

For technical contributions and pull requests, use GitHub issues and pull requests in this repository.

For substantive feedback that is not appropriate as a pull request (general feedback, pilot testing observations, concerns about specific positions), use the structured feedback form on the website at humanaipolicy.org/contact or contact the maintainer at natalia@humanaipolicy.org.

For confidential feedback (including pilot company experiences that should not be public, sensitive observations about specific commercial implementations), use the email contact natalia@humanaipolicy.org with "confidential" in the subject line. Confidential feedback is handled outside the public contribution process.

For visibility and community engagement, the framework is discussed on LinkedIn and other professional channels. Engaging there is welcome but not a substitute for the contribution channels above.

---

## Conduct

The framework's contribution process operates on standard expectations of professional respect, technical rigor, and good faith engagement. Specifically:

- Contributors engage with the framework's substance rather than personal characteristics
- Disagreement is welcome; bad faith argument is not
- The maintainer's decisions on what to merge are final, but the maintainer will explain reasoning
- Contributors who have had a contribution declined are welcome to continue engaging in other areas

The framework does not currently operate a formal Code of Conduct document. As the contributor community grows, a formal Code of Conduct may be adopted. In the meantime, professional respect and good faith are expected.

---

## Questions

Questions about the contribution process should be opened as GitHub issues with the "question" label. Questions about specific framework substance should be opened as issues with the appropriate substantive label (jurisdictional, citation, requirement, etc.).

For broader questions about the framework's direction, future development, or governance, contact the maintainer at natalia@humanaipolicy.org.

---

*This document is licensed under CC BY-NC-SA 4.0, the same license as the framework specification. It may be adapted for similar frameworks with appropriate attribution, for non-commercial use. Commercial adaptation requires separate licensing — contact natalia@humanaipolicy.org.*
