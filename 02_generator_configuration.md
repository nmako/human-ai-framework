# Generator configuration

**Status:** Working draft v0.2
**Companion to:** `01_rubric_configuration_model.md` (configuration architecture), `03_translation_layer.md` (AI Act / HRDD logic interaction), `architectural_note_hybrid_mode.md` (hybrid mode for Sections 1 and 2), and the twelve section rubric files.
**Purpose:** Specifies how the diagnostic rubric becomes a Generator output. Covers voice, document structure, cross-reference resolution, companion artefact production, and runtime behavior. This document is for tool builders and reviewers; companies using the tool do not see it.

---

## Changelog

### v0.2 — current

- **Part 1 size target revised to ~1,000 words / 2.5 pages** to align with the configuration model v0.5 revision. Original target of ~800 words / 2 pages was based on pre-draft estimates; actual measurement across all twelve sections produces a Part 1 closer to 1,000 words. The framework treats this as natural reach rather than over-runs to compress.

### v0.1
Initial draft. Voice and tone for Form A, document structure for Part 1 and Part 2, cross-reference resolution, companion artefact production, runtime behavior, output format and metadata.

---

## Document map

This configuration covers:

1. **Voice and tone for v1.0 (Form A).** The register, sentence patterns, and language conventions the Generator uses.
2. **Document structure.** How Part 1 (executive policy) and Part 2 (operational detail) are produced and stitched together.
3. **Cross-reference resolution.** How the Generator handles cross-references between sections in the output.
4. **Companion artefact production.** How the Code of Conduct addition and Own Workforce Policy addition are generated.
5. **Runtime behavior.** How the Generator behaves end-to-end when a company runs through the tool.
6. **Output format and metadata.** What the company receives.

---

## Voice and tone for v1.0 (Form A)

For v1.0, the Generator produces all outputs in Form A — generic adaptable language. The voice is consistent across companies; companies adapt the output to their own register if they wish. Form B (voice-matched to the company's existing materials) is deferred to v1.1.

### Voice principles

The Form A voice is designed to land as a professional company policy. Six principles:

**One — Plain corporate English.** The Generator avoids legal jargon where everyday language works; avoids consultant-speak where plain language works; avoids academic register where corporate register works. Where technical terms are necessary (GDPR, AI Act, UNGPs, salience), they are used precisely without elaborate hedging.

**Two — First person plural ("we").** The policy speaks as the company. "We commit to..." not "The Company shall..." or "Organization X commits to...". The "we" framing makes the policy adoptable as the company's own commitment.

**Three — Active voice with clear accountability.** The policy names who does what. "Our AI governance body classifies AI risk" rather than "AI risk is classified". "The CEO is accountable" rather than "Accountability is held at the executive level".

**Four — Sentence length proportionate to content.** Short sentences for commitments ("We do not deploy AI for surveillance of worker behavior.") Longer sentences for procedural detail (where logic requires it). The Generator avoids both extremes — neither aphoristic nor convoluted.

**Five — Honest about scope and uncertainty.** Where the policy commits to something the company will develop ("we are establishing a supplier-facing pathway"), the Generator says so explicitly rather than implying the capability already exists. Where the policy depends on future events (CSDDD applicability from 2028), the Generator names the dependency.

**Six — No marketing language.** The Generator avoids superlatives, value-laden adjectives without substance, and aspirational language untethered to commitment. "We commit to" is allowed; "We are committed to fostering" is not. "Industry-leading" and "best-in-class" are not used. The policy reads as substantive obligation rather than corporate communications.

### Specific conventions

**Addressing the reader.** The policy is addressed to a general internal and external audience. It does not assume the reader is the company's CEO, a regulator, or an external stakeholder specifically — the language works across audiences.

**Naming people.** Specific people (CEO, function heads) are named where the company has provided names through input fields. Where names are not provided, placeholders like *[CEO name]* are used rather than generic roles, because placeholders make the gap visible.

**Cross-references inline.** The policy uses inline cross-references to other sections: *"Section 3 Requirement 3.5 operationalizes worker consultation"*. The references include both the section number and the section topic for readability.

**Citations of binding instruments.** The policy cites binding instruments by official name on first reference, with shorter forms acceptable later: *"the EU AI Act (Regulation (EU) 2024/1689) — referred to in this policy as 'the AI Act'"*. Citations are not footnoted; they are integrated into the prose.

**Lists and structure.** Bullet points are used where the substance is genuinely a list (e.g., the four worker rights, the three populations covered by HRDD). Prose is used where the substance flows as argument. The Generator does not bullet-point everything — over-formatting weakens corporate policy register.

**Numbered requirements internally.** The rubric uses numbered requirements (Section 3 Requirement 3.5, etc.). The Generator output for the company does NOT show these internal numbering conventions to the reader. Internal numbering is for the rubric authors and diagnostic output; the policy output reads as flowing prose with subheadings.

**Tone calibration by section.** Sections 1 (Principles) and 2 (Governance) are written in a more declarative voice. Sections 3 through 8 are operationally more specific. Section 12 (External frameworks) is more list-like because the substance is naming frameworks. The Generator calibrates tone to section purpose.

### Example voice illustrations

For each section, this document includes a brief paragraph showing what Form A sounds like in practice. These are illustrative; the actual Generator output is produced by integrating company-specific inputs with foundation language.

**Section 1 illustration (Principles).**
> Our commitment to people comes first. AI is a tool we use in service of our work, our customers, and our communities — not a replacement for human judgment, human relationships, or human responsibility. We govern AI deliberately. Decisions about what AI we deploy, how we deploy it, and what we expect of it are made by people who are accountable for those decisions.

**Section 3 illustration (Worker rights).**
> Workers know when AI is involved in decisions about their work. Notification is clear, timely, and in language workers can understand. Workers can ask how an AI system that affects them works, in terms they can understand. They can challenge AI-driven outcomes without retaliation. Where AI deployment will materially affect working conditions, we consult workers and their representatives before deployment, not after.

**Section 5 illustration (Data protection).**
> Personal data used in our AI deployments is governed by the data protection framework set out in our [Data Protection / GDPR policy]. AI use does not relax foundational GDPR principles — lawful basis, transparency, data subject rights, purpose limitation, data minimization, accuracy, storage limitation, integrity, and confidentiality. AI-specific risks (training data, inference of special categories, automated decision-making, international transfers in cloud-hosted AI) are addressed alongside the existing framework.

**Section 8 illustration (Supply chain).**
> Our use of AI extends into our supply chain in two ways: through AI tools provided to us by third parties, and through AI used by our suppliers in ways that may affect their own workers. Both are within our governance. We require disclosure of material AI in supplier relationships, prioritize supply chain AI risk by salience, and integrate AI-related risks into our human rights due diligence under [applicable HRDD law].

---

## Document structure

The Generator produces a single document with two visibly separated parts. The document structure is uniform across companies; the content within each part varies by configuration.

### Document opening

The document opens with:

1. **Title:** "Human-AI Policy" with company name appended. Generated as: *"Human-AI Policy — [Company Name]"*.
2. **Version and date:** Version number and date of generation. Default version "1.0" for first generation; the company manages versioning thereafter.
3. **Adoption statement (one paragraph, ~50 words):** "This policy was adopted by [adoption body — board, executive committee, CEO] on [date]. It applies to [scope — typically 'our operations and our staff' for own-operations focus or 'our operations, our staff, and our value chain' for broader Tier C scope]."
4. **Page break to Part 1.**

### Part 1 — Executive policy

Part 1 contains:

1. **Opener (~50 words):** A short framing line setting the policy's purpose and scope. The Generator produces this from a small template tailored to ambition tier.
2. **Section-by-section executive commitments** at the weights specified in `01_rubric_configuration_model_v0.4.md`:
   - Section 1 (Principles) — heavy (60–120 words)
   - Section 2 (Governance and accountability) — heavy (60–120 words)
   - Section 3 (Worker rights and human oversight) — heavy (60–120 words)
   - Section 4 (Transparency and explainability) — medium (40–60 words)
   - Section 5 (Data protection and privacy) — light (30–40 words)
   - Section 6 (AI Risk Classification and Impact Assessment) — medium (40–60 words)
   - Section 7 (Human Rights Due Diligence Integration) — heavy (60–120 words)
   - Section 8 (Supply chain and third-party AI) — heavy (60–120 words)
   - Section 9 (Training and competence) — operational-only (no Part 1 content)
   - Section 10 (Grievance and remedy mechanisms) — medium (40–60 words)
   - Section 11 (Connected internal policies) — operational-only (no Part 1 content)
   - Section 12 (Applicable external frameworks) — light (30–40 words)
3. **Closer (~30 words):** A short closing line about review and revision. Connects to Section 2 Requirement 2.7.
4. **Signature block:** [Signature line — typically CEO]; [Date]; [Optional: board chair signature line for companies where board adoption is documented separately].
5. **Page break to Part 2.**

Total Part 1 target: approximately 1,000 words / 5,500–6,000 characters (executive commitment content) + 80 words (opener and closer) = approximately 1,080 words / 6,000–6,500 characters / 2.5 pages of A4 with normal formatting.

### Part 2 — Operational detail

Part 2 contains the operational detail for each of the twelve sections in order. Each section opens with a section header, includes the section narrative (the longer prose introduction setting context), and then includes the requirement-level substance.

Each section in Part 2 is structured as:

1. **Section header:** Section number and title (e.g., "Section 5: Data protection and privacy").
2. **Section narrative (~150–400 words depending on section):** The longer prose introduction setting context for the requirements that follow. Drawn from each section's narrative as drafted in the rubric files.
3. **Requirement-level substance:** Each requirement appears as a substantive paragraph or short subsection. The requirement number (e.g., 5.4) is NOT shown to the reader — the requirements are integrated into the section's flow as numbered or unnumbered subsections by topic.

Total Part 2 target: approximately 7–10 pages of A4. Length varies significantly by section density and configuration profile. A small company at Tier A ambition produces a Part 2 closer to 6–7 pages; a large multinational at Tier C ambition produces a Part 2 closer to 10–12 pages.

### Document closing

The document closes with:

1. **Appendix A — External frameworks reference (where useful):** A short reference list of binding instruments and voluntary frameworks named in the document, with citations. This duplicates some content from Section 12 but provides a quick reference for legal review.
2. **Appendix B — Glossary (optional, configuration-gated):** Where the configuration profile indicates the company would benefit from a glossary (typically smaller companies or non-EU companies less familiar with the regulatory landscape), the Generator includes a brief glossary of key terms: AI Act, GDPR, UNGPs, CSDDD, FRIA, DPIA, HRIA, aktsomhetsvurderinger, salience, etc.
3. **Document control:** Version history, next review date, accountable function.

---

## Cross-reference resolution

The rubric uses extensive cross-references between sections (e.g., Section 3 Requirement 3.5 cross-references Section 6 Requirement 6.8 and Section 8 Requirement 8.10 for worker consultation; Section 5 Requirement 5.4 cross-references Section 6 Requirement 6.4 for FRIA). The Generator resolves these in three ways depending on the output context.

### In Part 1 (executive policy)

Cross-references in Part 1 are minimized — executive commitments stand on their own without referring readers to other parts of the document. Where cross-references are unavoidable, they use plain language: *"as set out elsewhere in this policy"* rather than *"per Section 5.4"*.

### In Part 2 (operational detail)

Cross-references in Part 2 are explicit with section names: *"Worker consultation operates as set out in Section 3 (worker rights), Section 6 (AI risk classification), and Section 8 (supply chain). The Diagnostic checks for consistency across sections."* The Generator uses section topic names alongside section numbers for readability.

In an electronic version of the output (PDF, web document), cross-references should be hyperlinked to the destination section. In a printed version, the cross-reference text alone is sufficient. The Generator output is structured to support both.

### Cross-references to external documents (rubric files)

In the rubric working files, cross-references appear to `03_translation_layer.md` and similar documents. These are author-facing references for rubric construction. They do NOT appear in the Generator output — the substance the rubric refers to is integrated into the policy directly. Companies do not see internal file references.

### Cross-references to company-specific policies

When the Human-AI policy cross-references the company's existing internal policies (Code of Conduct, Own Workforce Policy, Data Protection policy, etc.), the Generator uses the actual policy names provided through the company-input fields in Section 11. Where actual names are not provided, the Generator uses generic placeholders ("our Code of Conduct"; "our Data Protection policy") with flags that the names should be populated.

---

## Companion artefact production

In addition to the Human-AI policy, the Generator produces two companion artefacts:

### Companion artefact 1: Suggested addition to the Code of Conduct

**Purpose.** Provide ~100–200 words of language the company can insert into its existing Code of Conduct to signal that AI governance is part of the company's core ethical framework.

**Voice.** Same Form A voice as the main policy. Slightly more compressed because Code of Conduct register tends to be terse.

**Content template.**

> *AI in our work.* Where we use artificial intelligence in our operations — internally developed or provided by third parties — we apply the principles set out in our Human-AI Policy. AI assists human work; it does not replace human responsibility. Every AI-supported decision affecting a person has a named human who is accountable. We are transparent with workers, customers, suppliers, and the public about our AI use. We integrate AI-related impacts on people into our existing human rights due diligence. We do not deploy AI for the surveillance of worker behavior.

This is foundation language. The Generator adapts it to company configuration — Tier C companies may include a reference to value chain impacts; deployer-only companies may emphasize the deployer framing.

**Placement guidance.** The Generator includes a note for the company: "Suggested insertion location: in your Code of Conduct's section on responsible business conduct, ethical commitments, or technology use. The addition can be a standalone subsection or integrated into existing technology/digital commitments."

### Companion artefact 2: Suggested addition to the Own Workforce Policy

**Purpose.** Provide ~200–300 words of worker-facing language the company can insert into its Own Workforce Policy (or equivalent People / HR policy). Naming follows CSRD/ESRS S1 terminology so the artefact slots cleanly into companies that already use that framing.

**Voice.** Same Form A voice with a slight shift toward worker-facing register — explaining commitments to workers as readers rather than to a general audience.

**Content template.**

> *Artificial intelligence in our workplace.* This policy section sets out how we use artificial intelligence in ways that affect you as a worker, and what rights you have.
>
> *Your right to know.* If artificial intelligence is involved in decisions about your work — recruitment, performance evaluation, scheduling, task allocation, termination, or other decisions — we tell you. We tell you clearly, in language you can understand, and at the time the AI is used.
>
> *Your right to human review.* Decisions about your work that are made by AI, or substantially supported by AI, are reviewed by a named person with authority to override the AI. We do not let AI make consequential decisions about you alone.
>
> *Your right to information.* You can ask how an AI system that affects you works. We explain what the AI does, what data it uses, what its limitations are, and how you can challenge a decision you disagree with.
>
> *Your right to consultation.* Where AI deployment will materially affect your working conditions, we consult you and your representatives before deployment, not after.
>
> *Your right to be free from AI-driven surveillance.* We do not use AI to monitor your behavior — keystrokes, screen activity, attention, sentiment, or individual productivity surveillance. Legitimate operational monitoring (occupational safety, equipment operation, anti-fraud, security access, payroll time) is governed by our existing safety and security policies and is not extended into worker surveillance.

The Generator adapts to company configuration — jurisdictions with stronger codetermination (Norway, Germany, Netherlands) include explicit reference to the applicable consultation framework; jurisdictions without strong codetermination retain the framework's voluntary commitment to consultation.

**Placement guidance.** The Generator includes a note: "Suggested insertion location: in your Own Workforce Policy (or People / HR policy), under sections addressing worker rights, technology use, or terms of employment. The addition can be a standalone subsection."

### Companion artefact form for v1.0 (Form A)

Both companion artefacts are produced as generic adaptable language. The company inserts the language into its existing policy with whatever stylistic adaptation it wants. Form B (voice-matched and ready to integrate without further adaptation) is deferred to v1.1.

### Future companion artefacts (deferred to v2.0+)

The framework's architecture supports additional companion artefacts in future versions:

- **Supplier Code of Conduct addition.** ~200–300 words addressing AI in supplier relationships. Aligned with CSRD/ESRS S2 (Workers in Value Chain) naming.
- **Public-facing AI use disclosure.** A standalone artefact for companies wanting public AI transparency, aligned with CSRD/ESRS S4 (Affected Communities) where applicable.

These are not produced in v1.0 to keep the v1.0 scope manageable.

---

## Runtime behavior

The Generator operates end-to-end as follows when a company runs through the tool:

### Step 1 — Configuration profile derivation

The company completes the questionnaire (17 core questions plus optional 15-question detailed tailoring). The tool derives the configuration profile:

- Axis 1 — Regulatory exposure (AI Act applicability and role; GDPR; applicable HRDD instruments; CSRD/ESRS scope; sectoral regulation).
- Axis 2 — Ambition scope (Tier A own operations / Tier B supply chain / Tier C value chain).
- Axis 3 — Policy integration (existing policies named).

The configuration profile drives which requirements activate in each section and the language tailoring.

### Step 2 — Upload processing

Company-uploaded materials (Code of Conduct, Data Protection policy, Transparency Act report, HRDD methodology, training catalog, etc.) are processed for extraction. The Generator extracts:

- Specific policy titles (for cross-references in Section 11).
- Existing vocabulary, governance structures, and operational patterns (for voice consistency in extraction-based Generator behavior).
- Specific commitments or framings that map to rubric requirements.

The processing is configuration-aware — the tool knows which extraction targets are relevant for which sections.

### Step 3 — Diagnostic execution (if Diagnostic mode is selected)

If the company runs the Diagnostic mode (assessing an existing policy uploaded for analysis), the Diagnostic compares the uploaded policy against the rubric and produces:

- Per-requirement assessment (covered / partial / missing for prescriptive requirements; strong / can be strengthened / conflicts for hybrid mode requirements).
- Gap analysis with specific suggestions.
- Three-part requirement activation disclosure (currently bound / likely future / voluntary alignment).

The Diagnostic output is separate from the Generator output. A company can run the Diagnostic, address gaps, and then run the Generator — or run them together as a single pass.

### Step 4 — Generator execution

The Generator produces the Human-AI policy and companion artefacts using the cascading priority specified in each section's Generator behavior:

1. **Priority 1:** Company-submitted content (hybrid mode input fields, free-text inputs).
2. **Priority 2:** Extraction from uploaded materials.
3. **Priority 3:** Foundation language with configuration tailoring.

The Generator integrates the three priorities to produce a coherent document. Where company-specific content is available, it integrates into foundation language. Where it is not, foundation language stands with appropriate placeholders.

### Step 5 — Output delivery

The Generator produces:

- The Human-AI policy (Part 1 + Part 2 stitched together as a single document).
- Suggested Code of Conduct addition.
- Suggested Own Workforce Policy addition.
- A summary document that includes the configuration profile (currently bound / likely future / voluntary alignment), a note on placeholders that need company refinement, and recommendations for next steps.

All outputs are delivered in editable formats (Word, Markdown, or PDF) so the company can refine before adoption.

### Step 6 — Versioning and re-run

The company can re-run the Generator after refining inputs (filling in placeholder fields, uploading additional policies, updating ambition tier). Each run produces a versioned output. The tool maintains version history if the company opts in to that functionality (v1.1 feature).

---

## Output format and metadata

### File formats

The Generator produces outputs in three formats by default:

1. **Markdown (.md)** — for easy editing and version control. This is the primary working format.
2. **Microsoft Word (.docx)** — for companies preferring Word for policy review and adoption workflows.
3. **PDF** — for adoption, distribution, and archival.

### Metadata

Each output document includes metadata:

- Date of generation.
- Configuration profile snapshot (the answers that produced this output).
- Version number.
- A reference to the framework version used (e.g., "Generated using Framework v1.0").

Metadata enables traceability — if the framework is updated, the company can re-run the Generator to produce an updated policy aligned with the latest framework version.

### Diagnostic output (separate document)

The Diagnostic output is structured separately from the policy output. It includes:

- Per-requirement assessment results.
- Gap analysis with specific suggestions.
- Configuration profile disclosure (the three-part activation pattern from `01_rubric_configuration_model_v0.4.md`).
- Recommendations for next steps.

The Diagnostic output is designed to be useful internally — for the company's review of an existing policy — rather than as an external-facing document.

---

## Open items for v1.0 build

**Voice consistency review.** Form A voice principles need to be applied consistently across the twelve sections. A consistency pass (item two on the outstanding work list) will check this.

**Cross-reference resolution implementation.** The Generator needs implementation logic to resolve cross-references at runtime — extracting section numbers and topic names, producing hyperlinks where output format supports them. This is a build task.

**Companion artefact production logic.** The Generator's logic for producing companion artefacts integrates the main policy substance into the artefact templates. The integration logic needs build specification.

**Configuration profile disclosure format.** The three-part activation pattern (currently bound / likely future / voluntary alignment) needs a specific display format in both the Generator output and the Diagnostic output. The configuration model v0.4 describes the substance; this document needs to specify the display.

**Glossary content (Appendix B).** Where the configuration indicates a company would benefit from a glossary, the Generator produces one. The glossary content needs specification — which terms, with what definitions, drawn from which authoritative sources.

**Versioning architecture.** The runtime versioning ("re-run with updated inputs") is a v1.1 feature. v1.0 produces one output per run; the company manages versioning manually.
