# Rubric configuration model

**Status:** Working draft v0.5
**Companion to:** `00_rubric_scope.md`, `02_generator_configuration.md`, `03_translation_layer.md`, `architectural_note_hybrid_mode.md`
**Purpose:** Explains how the diagnostic rubric adapts to a given company's profile, so that both the Generator (Module 1) and the Diagnostic (Module 2) produce outputs proportionate to the company being assessed.

---

## Changelog

### v0.5 — current

- **Part 1 size target revised upward** to reflect actual reach after all twelve sections were drafted. Original target was approximately 670 words / 4,000 characters / 2 pages. Revised target is approximately 1,000 words / 5,500–6,000 characters / 2.5 pages. The revision is based on a consistency-pass measurement of actual executive commitment word counts, which together produce a Part 1 closer to 1,000 words than to 670. The section weighting distribution (heavy / medium / light / operational-only) is unchanged; the per-section word count ranges in the weighting were always upper bounds (e.g., "60–120 words" for heavy), and the actual content has settled toward the upper end of those ranges. Sections 9 and 11 remain operational-only with no Part 1 contribution.

### v0.4

- **"What the tool produces" expanded** to specify the two-part Generator output structure: an executive policy sitting at the front of the document, followed by an operational detail section for sustainability, HR, IT, Legal, and AI governance body use.
- **Section weighting introduced** for executive-part contributions: Heavy (60–120 words) for Sections 1, 2, 3, 7, 8; Medium (40–60 words) for Sections 4, 6, 10; Light (30–40 words) for Sections 5, 12; Operational-only for Sections 9 and 11.

### v0.3
Three-artefact output spec; CSRD/ESRS S1 alignment for Own Workforce Policy naming; three core questions on existing policy landscape; final-step items added; detailed tailoring questionnaire designed; Form A as v1.0 commitment; example output updated.

### v0.2
Substantive revision based on two independent reviews. Tier 1 split into 1a/1b/1c. Axis 2 reframed as ambition above legal floor. Voice moved to separate Generator config doc. Translation layer referenced as separate deliverable. Q6 derived from operational answers. Q9 expanded. Activated requirements output restructured into three-part disclosure. Per-section scope override; multi-jurisdiction reported separately by source; questionnaire restructured as core + optional detailed.

### v0.1
Initial draft.

---

## What the tool produces

The tool produces three artefacts for v1.0, plus diagnostic output when used in Diagnostic mode.

### Primary artefact: the Human-AI Policy

The primary artefact is the Human-AI Policy itself, produced as a single document with two visibly separated parts.

**Part 1 — Executive policy (~2.5 pages, roughly 5,500–6,500 characters depending on configuration).** Sits at the front of the document. Contains:
- A short overall opener (~50 words) stating the policy's purpose and scope.
- Section-by-section executive commitments at the weights specified below.
- A short closing line and signature block.

This is what the CEO, Board, external readers, and the company's external website see. It is adoptable on its own terms — a company can extract Part 1 alone for board approval, public posting, or sustainability reporting.

**Part 2 — Operational detail (~7–10 pages).** Sits immediately after Part 1 in the same document. Contains:
- The substantive operational language for each section, drawn from the rubric's requirements.
- Cross-references to existing internal policies (Code of Conduct, Own Workforce Policy, Data Protection policy, Whistleblowing, etc.).
- Cross-references to applicable laws and frameworks.
- Where applicable, definitions, examples, and operational specifics.

This is what sustainability, HR, IT, Legal, Compliance, and the AI governance body work from. It is the company's operational reference for what the executive commitments mean in practice.

The two parts are produced together by the Generator. There is no manual extraction step. The document structure has the executive part visibly at the front, separated by a clear divider, with the operational detail following.

### Section weighting for executive-part contributions

Not every section contributes equally to the executive part. The framework's substantive commitments live in some sections more than others; technical or operational sections need less executive treatment or none at all. The distribution is:

**Heavy executive treatment (60–120 words each).** Sections where the framework's substantive commitments live and where executive-level adoption matters most.
- Section 1 — Principles
- Section 2 — Governance and accountability
- Section 3 — Worker rights and human oversight
- Section 7 — Human Rights Due Diligence Integration
- Section 8 — Supply chain and third-party AI

**Medium executive treatment (40–60 words each).** Sections that carry real commitments but are operationally specific enough that the operational detail does most of the work.
- Section 4 — Transparency and explainability
- Section 6 — AI Risk Classification and Impact Assessment
- Section 10 — Grievance and remedy mechanisms

**Light executive treatment (30–40 words each).** Sections that are technical extensions of existing infrastructure or standard policy elements.
- Section 5 — Data protection and privacy
- Section 12 — Applicable external frameworks

**Operational-only (no executive part).** Sections that are entirely cross-references and operational substance, not executive commitments.
- Section 9 — Training and competence
- Section 11 — Connected internal policies

**Total target for executive content** (excluding opener and closer): approximately 1,000 words / 5,500–6,000 characters based on actual draft measurement across all twelve sections. With opener and closer added: approximately 5,500–6,500 characters / 2.5 pages of A4 with normal formatting. Where a company's configuration produces more substantive content (e.g., a Tier C ambition company with extensive jurisdictional exposure), the executive part may run slightly longer; where configuration produces less (e.g., a Tier A small company), it may run shorter.

The 2.5-page target replaces the original 2-page target after a consistency-pass measurement of actual section content. The shift reflects that the per-section word count ranges (60–120 for heavy, 40–60 for medium, etc.) were always upper bounds, and the framework's substantive commitments settled toward the upper end of those ranges. The framework's intellectual core in particular (Section 1 Principles, Section 7 HRDD Integration, Section 8 Supply chain) carries enough substance that compression below the upper bound would lose meaningful content.

### Companion artefact 1: Suggested addition to the Code of Conduct

Approximately 100–200 words of executive-level commitment language that signals AI governance is part of the company's core ethical framework. Designed to be inserted into an existing Code of Conduct's relevant section.

### Companion artefact 2: Suggested addition to the Own Workforce Policy

Approximately 200–300 words of worker-facing language. Naming follows CSRD/ESRS S1 terminology so the artefact slots cleanly into companies that already use that framing for sustainability reporting.

### Generator output form (v1.0)

Form A — generic adaptable language. The Generator produces companion artefacts as suggested language the company can adapt, with explicit notes on where to insert. Form B (voice-matched, native-looking additions) deferred to v1.1.

### Future scope (v2.0+)

Companion artefacts addressing value chain workers (ESRS S2 territory) — likely a suggested addition to a Supplier Code of Conduct — and affected communities (ESRS S4 territory) — likely a public-facing AI use disclosure. The architecture is designed to extend; v1.0 covers own operations and Code of Conduct only.

---

## The three configuration axes

[Content unchanged from v0.3 — see prior version for full text on Axis 1 (Regulatory exposure and role), Axis 2 (Ambition scope), Axis 3 (Policy integration).]

---

## How configuration affects requirement activation

[Content unchanged from v0.3 — see prior version for full text on Tier tags (1a/1b/1c/2/3), Scope tags, Jurisdiction tags, Legal logic tags.]

---

## Intake questionnaire

[Content unchanged from v0.3 — see prior version for full text on the 17-question core intake plus 15-question optional detailed tailoring.]

---

## Configuration profile output

[Content unchanged from v0.3 — see prior version for the example output structure showing currently bound / likely future / voluntary alignment, requirement activation breakdown, and output artefacts.]

---

## Multi-jurisdiction handling

[Content unchanged from v0.3.]

---

## Versioning

[Content unchanged from v0.3.]

---

## Open items for v1.0

- The Generator configuration document (`02_generator_configuration.md`) needs to be drafted to pick up voice and Generator-specific concerns.
- Detailed implementation of how the Generator stitches together executive commitments from each section into Part 1 with consistent formatting.
- "Save and return later" functionality flagged as a v1.1 feature.

## Future scope (v2.0+)

[Content unchanged from v0.3.]
