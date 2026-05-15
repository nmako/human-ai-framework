# Section 3: Worker rights and human oversight

**Status:** Working draft v0.4
**Section position:** Section 3 of 12 in the rubric
**Configuration dependencies:** Most requirements activate at all ambition tiers because legal floor demands it. Cross-cutting worker consultation requirement scales by jurisdictional codetermination context. Some requirements activate only when company is subject to Platform Work Directive or operates in jurisdictions with strong codetermination law.
**Density:** Medium (8 requirements).
**Mode:** Prescriptive throughout.
**Executive part weight:** Heavy (60–120 words target).

---

## Changelog

### v0.4 — current

- **Pilot company names removed.** Generic company profiles replace named pilots. Section header renamed for consistency. The 3.6 scope line is also generalized from specific pilot relevance to sector-based applicability.

### v0.3

- **Executive commitment block added** at the top of the section, weighted heavy per the configuration model v0.4 section weighting.

### v0.2
Monitoring removed from legitimate AI use case lists. Requirement 3.8 expanded to include AI-driven worker surveillance as a prohibited use. Generator behavior specifications added per requirement. Section narrative updated.

### v0.1
Initial draft. Eight requirements at medium density.

---

## Executive commitment (Part 1 — Executive policy)

> *Generator output for Part 1. ~115 words.*
>
> **Worker rights and human oversight.** Where AI is used in ways that affect our workers — recruitment, performance evaluation, scheduling, task allocation, termination, or other decisions about their work — we respect rights we do not negotiate around. Workers know when AI is involved in decisions about their work; have those decisions reviewed by a named human with override authority; can ask how the AI works in language they understand; can challenge outcomes without retaliation; are consulted before deployment that materially affects working conditions; are protected by occupational safety obligations where AI operates in safety-critical contexts; and are protected from discrimination in AI-driven decisions. We do not deploy AI for surveillance of worker behavior.

---

## Section purpose

This section establishes the rights of workers in relation to AI use that affects them, and the human oversight obligations that operationalize those rights. It is where the human accountability principle from Section 1 becomes binding obligation: every AI-supported decision affecting a worker has a named human who reviews, approves, and bears responsibility, and the worker has a right to know.

The framework transposes several binding instruments here. AI Act Article 14 establishes human oversight obligations for high-risk AI systems. AI Act Article 26(11) requires deployers to inform natural persons subject to high-risk AI systems making or assisting decisions about them. GDPR Article 22 establishes the right not to be subject to solely automated decisions producing legal or similarly significant effects. The Platform Work Directive (2024/2831) establishes algorithmic management transparency and human oversight obligations. The Norwegian Working Environment Act (Arbeidsmiljøloven) and collective agreement frameworks create codetermination obligations that, in Nordic and several Continental European contexts, are stronger than the EU minimum.

The framework's distinctive positions in this section:

*Worker rights and human oversight are not separable obligations.* A worker who does not know AI is in play cannot exercise oversight rights. A human "in the loop" who has no real authority to override the AI is not exercising oversight. A consultation that happens after deployment is not consultation.

*AI-driven worker surveillance is incompatible with the people-first principle.* The framework distinguishes between legitimate operational monitoring (occupational health and safety, equipment operation, anti-fraud in financial services, security access to restricted areas, time tracking for payroll) and AI-driven surveillance of worker behavior (keystroke logging, screen monitoring, sentiment analysis, behavioral tracking, individual productivity surveillance). The first is necessary in defined contexts; the second is not how this framework permits AI to be deployed.

---

## Section narrative (the policy-level commitment)

> *Suggested policy text the Generator produces for this section, adapted to company configuration:*
>
> **Worker rights and human oversight.** Where AI is used in ways that affect our workers — recruitment, performance evaluation, scheduling, task allocation, termination, or other decisions about their work — workers have rights that we commit to respecting and that we do not negotiate around.
>
> *The right to know.* Workers know when AI is involved in decisions about their work. Notification is clear, timely, and in language workers can understand. Notification is not buried in employment contracts or terms of service.
>
> *The right to human review.* Decisions made by AI or substantially supported by AI that affect a worker materially — pay, promotion, discipline, termination, scheduling that affects family or health — receive human review by a named person with authority to override the AI. Where binding law (GDPR Article 22, AI Act Article 14) requires human oversight, that oversight is meaningful, not nominal.
>
> *The right to information.* Workers can ask how an AI system that affects them works, in terms they can understand. They are told what data the AI uses, what its limitations are, and how to challenge or appeal a decision they disagree with.
>
> *The right to consultation.* Where AI deployment will materially affect workers' working conditions, we consult workers and their representatives before deployment, not after. In contexts where collective agreements or codetermination law require this (Norwegian Arbeidsmiljøloven, German Betriebsverfassungsgesetz, Nordic collective agreement frameworks, EU Platform Work Directive Article 9), consultation follows the applicable framework. Where no such framework binds us, we still consult — because deploying AI that affects workers without their input is not how we work.
>
> *The right to safety.* Where AI is deployed in safety-critical contexts (manufacturing equipment, demolition, environmental remediation, healthcare, transport), the AI's role in safety is governed by occupational health and safety obligations alongside AI-specific obligations. AI does not reduce our duty to provide a safe workplace.
>
> *The right to non-discrimination.* AI used in decisions about workers must not discriminate on the basis of protected characteristics. We monitor outcomes for discriminatory patterns and remediate where they occur.
>
> *Freedom from AI-driven surveillance.* We do not deploy AI for surveillance of worker behavior — keystroke logging, screen monitoring, sentiment analysis, behavioral tracking, or individual productivity surveillance. AI in our company supports work; it does not surveil people who do work. Legitimate operational monitoring necessary for occupational safety, equipment operation, financial fraud prevention, security access, and payroll time tracking is governed by existing OHS, security, and operational policies and is not extended into worker surveillance.

---

## Requirements

### Requirement 3.1 — Notification to workers about AI use in decisions affecting them

**Statement.** The policy commits the company to notifying workers when AI is used in decisions or processes that materially affect their employment, working conditions, or treatment in the workplace. Notification is timely (before the AI is deployed in ways affecting the worker, not after the worker is harmed), clear (in language workers can understand, not buried in legal disclaimers), and substantive (identifies what AI is in use, what it does, what data it uses, and what the worker's options are).

**Tier:** 1b (binding under AI Act Article 26(11) for deployers of high-risk AI systems making decisions about natural persons; binding under GDPR Articles 13 and 14 for personal data processing including AI-driven processing; binding under Platform Work Directive Article 9 for digital labour platforms; converging best practice for non-high-risk and non-platform-work contexts).

**Scope:** All — applies regardless of ambition tier where AI affects workers.

**Jurisdiction:** EU AI Act Article 26(11); GDPR Articles 13, 14, 22; EU Platform Work Directive Articles 9–11; Norwegian Working Environment Act Chapter 9 § 9-1 to § 9-4.

**Legal logic:** Both AI Act-derived and GDPR-derived; HRDD-derived where the framework extends notification beyond binding minimum.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 26(11).
- *Binding:* Regulation (EU) 2016/679 (GDPR), Articles 13, 14, 22.
- *Binding:* Directive (EU) 2024/2831 (Platform Work Directive), Articles 9, 10.
- *Binding:* Lov om arbeidsmiljø, arbeidstid og stillingsvern mv. (Arbeidsmiljøloven, Norway), Chapter 9.
- *Interpretive:* Council of Europe Framework Convention on Artificial Intelligence (2024), Article 8.

**What to look for in a policy.** The policy should commit to notifying workers about AI use affecting them, specify when notification occurs (before deployment), specify the form (clear language, accessible format), specify what the notification contains, and reference applicable legal frameworks.

**Assessment criteria:**
- *Covered:* The policy commits to worker notification, specifies pre-deployment timing, specifies form and content, addresses both individual and collective notification.
- *Partial:* The policy commits to notification but does not specify timing or content, treats notification as one-time disclosure, or limits notification to AI Act Article 26(11) high-risk strictly.
- *Missing:* The policy is silent, or treats notification as covered by general employment contract terms.

**Generator behavior.** *(1) If the company has uploaded an existing AI policy, IT policy, or employment information document containing notification commitments, the Generator extracts that language and integrates it as the basis for the requirement, supplemented to address gaps against binding law. (2) If the company has uploaded a Code of Conduct, Own Workforce Policy, or sustainability policy with adjacent transparency commitments, the Generator draws on that voice and approach. (3) If no relevant company material is available, the Generator produces foundation language meeting AI Act Article 26(11), GDPR Articles 13–14, and Platform Work Directive Article 9 minimum, with notification timing, form, and content specified at the level required by binding obligations.*

---

### Requirement 3.2 — Human oversight of AI-supported decisions affecting workers

**Statement.** Where AI is used in decisions that materially affect workers — recruitment, performance evaluation, promotion, discipline, termination, scheduling that affects family or health, pay determination, task allocation — those decisions receive meaningful human oversight by a named person with authority to override the AI's output. Oversight is not nominal sign-off; the human reviewer has access to relevant information, time to exercise judgment, and consequence-free authority to disagree with the AI.

**Tier:** 1b (binding under AI Act Article 14, GDPR Article 22, Platform Work Directive Article 7).

**Scope:** All — applies regardless of ambition tier.

**Jurisdiction:** EU AI Act Article 14; GDPR Article 22; EU Platform Work Directive Article 7; Norwegian Working Environment Act on workplace control measures.

**Legal logic:** AI Act-derived and GDPR-derived primarily.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 14.
- *Binding:* Regulation (EU) 2016/679 (GDPR), Article 22.
- *Binding:* Directive (EU) 2024/2831 (Platform Work Directive), Article 7.
- *Interpretive:* European Data Protection Board Guidelines on Article 22.

**What to look for in a policy.** The policy should commit to meaningful human oversight, name decision categories requiring oversight, specify the human reviewer's authority to override, specify what information and time the reviewer has, and address GDPR Article 22 right where applicable.

**Assessment criteria:**
- *Covered:* The policy commits to meaningful oversight, names decision categories, specifies override authority, addresses GDPR Article 22, ensures reviewer access to needed information.
- *Partial:* The policy treats oversight as supervision rather than meaningful review with override authority, or limits to AI Act high-risk strictly.
- *Missing:* The policy permits AI decisions about workers without meaningful human review, or describes oversight as rubber-stamping.

**Generator behavior.** *(1) If the company has uploaded HR procedures, decision-making protocols, or AI policy material specifying human review processes, the Generator extracts and integrates that language. (2) If the company has uploaded a Code of Conduct, Own Workforce Policy, or grievance procedure, the Generator draws on existing review and accountability framing. (3) If no company material is available, the Generator produces foundation language meeting AI Act Article 14, GDPR Article 22, and Platform Work Directive Article 7 minimum, naming the categories of worker-affecting decisions where meaningful oversight applies and specifying that oversight includes override authority, not just supervision.*

---

### Requirement 3.3 — Workers' right to information about AI affecting them

**Statement.** Workers have the right to ask how an AI system that affects them works, in terms they can understand. The policy commits the company to providing information about AI logic, data used, system limitations, and the worker's options for challenging AI-driven outcomes. Information is provided in language accessible to the worker, not in technical or legal jargon that functions as obstruction.

**Tier:** 1b (binding under GDPR Articles 13–15, AI Act Article 26(11), Platform Work Directive Articles 9–10).

**Scope:** All — applies regardless of ambition tier where personal data processing or AI affecting individuals is involved.

**Jurisdiction:** GDPR Articles 13, 14, 15; EU AI Act Article 26(11); EU Platform Work Directive Articles 9, 10.

**Legal logic:** GDPR-derived primarily; AI Act-derived for high-risk system contexts.

**Source citations:**
- *Binding:* Regulation (EU) 2016/679 (GDPR), Articles 13, 14, 15.
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 26(11).
- *Binding:* Directive (EU) 2024/2831 (Platform Work Directive), Articles 9, 10.
- *Interpretive:* Council of Europe Framework Convention on Artificial Intelligence (2024), Article 8.

**What to look for in a policy.** The policy should commit to a worker's right to information, specify what information is available on request, specify the request process and response timeframe, ensure accessible language.

**Assessment criteria:**
- *Covered:* The policy commits to the right, specifies information categories, specifies process and timeframe, commits to accessible language.
- *Partial:* The policy mentions information rights but does not specify categories or process.
- *Missing:* The policy is silent, or treats information rights as exclusively covered by GDPR access rights without AI-specific provision.

**Generator behavior.** *(1) If the company has uploaded a GDPR / data protection policy with information request procedures, the Generator extracts that procedural framework and adapts it for AI-specific information requests. (2) If the company has uploaded other policies addressing transparency or information rights, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting GDPR Articles 13–15 and AI Act Article 26(11) minimum, including a specific request process and response timeframe.*

---

### Requirement 3.4 — Workers' right to challenge AI-driven outcomes

**Statement.** Workers have the right to challenge AI-driven outcomes that affect them and to have their challenge reviewed by a human with authority to overturn the AI's output. The policy commits to a clear and accessible process for raising challenges, a fair review by a person not involved in the original AI deployment, a substantive response that addresses the worker's concerns, and the absence of retaliation for raising a challenge.

**Tier:** 1b (binding under GDPR Article 22(3), Platform Work Directive Article 11; established best practice in employment law).

**Scope:** All — applies regardless of ambition tier where AI is used in worker-affecting decisions.

**Jurisdiction:** GDPR Article 22(3); EU Platform Work Directive Article 11; Norwegian Working Environment Act provisions on dispute resolution.

**Legal logic:** GDPR-derived primarily; cross-references Section 10 (grievance and remedy mechanisms).

**Source citations:**
- *Binding:* Regulation (EU) 2016/679 (GDPR), Article 22(3).
- *Binding:* Directive (EU) 2024/2831 (Platform Work Directive), Article 11.
- *Cross-reference:* Section 10 of this rubric.

**What to look for in a policy.** The policy should commit to the right to challenge, specify the process, specify reviewer independence, specify response obligations, prohibit retaliation, cross-reference grievance mechanisms.

**Assessment criteria:**
- *Covered:* The policy commits to the right, specifies process and reviewer independence, sets response obligations, prohibits retaliation, cross-references grievance mechanisms.
- *Partial:* The policy commits to challenge rights without specifying process or reviewer, fails to address retaliation, or treats challenges as covered by general grievance procedures without AI-specific provision.
- *Missing:* The policy is silent, or directs workers exclusively to GDPR rights without AI-specific recognition.

**Generator behavior.** *(1) If the company has uploaded a grievance procedure, whistleblowing channel, or appeal mechanism, the Generator extracts that procedural framework and adapts it for AI-specific challenges, ensuring AI challenges have a defined path. (2) If the company has uploaded an Own Workforce Policy or HR procedures with internal review provisions, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting GDPR Article 22(3) and Platform Work Directive Article 11 minimum, specifying a challenge process, reviewer independence, response timeframe, and explicit anti-retaliation protection.*

---

### Requirement 3.5 — Worker consultation before AI deployment affecting workers

**Statement.** Where AI deployment will materially affect workers' working conditions, the policy commits the company to consulting workers and their representatives before deployment, not after. In contexts where collective agreements, codetermination law, or directives require formal consultation, the policy follows the applicable framework. In contexts where no such framework binds the company, the policy still commits to consultation as a matter of governance, because deploying AI that affects workers without their input is incompatible with the framework's people-first principle.

**Tier:** 1c (binding under CSDDD Article 13 for in-scope companies; binding under Platform Work Directive provisions; binding under national codetermination law in Germany, Austria, Netherlands, Norway, and other jurisdictions; UNGPs Principle 18(b)). Tier 3 (framework principle) for the framework's extension beyond binding minimum.

**Scope:** All — applies wherever AI deployment materially affects workers.

**Jurisdiction:** EU CSDDD Article 13; EU Platform Work Directive; Norwegian Working Environment Act § 4-2, § 8 (and underlying Hovedavtalen LO-NHO and equivalent collective agreements); German Betriebsverfassungsgesetz §§ 87, 90; Austrian Arbeitsverfassungsgesetz; Netherlands Wet op de ondernemingsraden Articles 25, 27; EU European Works Councils Directive where applicable; UNGPs Principle 18(b).

**Legal logic:** Both AI Act-derived and HRDD-derived.

**Source citations:**
- *Binding:* Directive (EU) 2024/1760 (CSDDD), Article 13.
- *Binding:* Directive (EU) 2024/2831 (Platform Work Directive).
- *Binding:* Lov om arbeidsmiljø, arbeidstid og stillingsvern mv. (Arbeidsmiljøloven, Norway), § 4-2, § 8.
- *Binding (Germany):* Betriebsverfassungsgesetz §§ 87, 90.
- *Binding (Netherlands):* Wet op de ondernemingsraden Articles 25, 27.
- *Interpretive:* UNGPs Principle 18(b); OECD Guidelines for Multinational Enterprises Chapter V.

**What to look for in a policy.** The policy should commit to pre-deployment consultation, name applicable consultation framework, specify substance of consultation, indicate commitment even where no binding framework applies.

**Assessment criteria:**
- *Covered:* The policy commits to pre-deployment consultation, names the applicable framework(s), specifies substance, commits to consultation as a principle even where no framework binds.
- *Partial:* The policy commits to consultation without specifying framework or substance, or commits to information-only without genuine opportunity to influence deployment.
- *Missing:* The policy is silent, or treats consultation as post-deployment.

> **Cross-reference note.** Worker consultation is cross-cutting — appears in Sections 3, 6, 7, 8, 10. The Diagnostic checks for consistency.

**Generator behavior.** *(1) If the company has uploaded materials referencing collective agreements (Hovedavtalen LO-NHO, sector-specific tariff agreements), works council procedures, employee representation structures, or existing pre-deployment consultation processes, the Generator extracts that framework and integrates it as the consultation foundation. (2) If the company has uploaded Code of Conduct or Own Workforce Policy material on stakeholder engagement, the Generator draws on that voice. (3) If no company material is available, the Generator produces foundation language meeting CSDDD Article 13, Platform Work Directive provisions, and applicable national codetermination law minimum. For Norwegian companies the default reference is Arbeidsmiljøloven and Hovedavtalen unless company-specific framework is provided.*

---

### Requirement 3.6 — AI in safety-critical worker contexts

**Statement.** Where AI is deployed in safety-critical contexts that affect worker safety — manufacturing equipment, demolition operations, environmental remediation, transport and logistics, healthcare equipment, industrial machinery — the AI's role in safety is governed by both occupational health and safety obligations and AI-specific obligations, with the OHS framework controlling where the two would conflict. AI does not reduce the company's duty to provide a safe workplace; it can only support that duty.

**Tier:** 1a where AI failure could cause physical harm and OHS framework imposes hard requirements; 1b for AI Act high-risk classifications under Annex III, point 5 or Annex I; 1c where worker safety is the human rights dimension at issue under HRDD frameworks.

**Scope:** Activates conditionally on AI use in safety-critical operational contexts (Q10 in core questionnaire, D13 in detailed questionnaire). Critical for companies in construction, manufacturing, environmental remediation, transport, healthcare; potentially relevant for companies with manufacturing equipment AI; unlikely for B2B and B2C service-only companies.

**Jurisdiction:** EU AI Act Article 6 and Annex I, Annex III point 5; EU Machinery Regulation 2023/1230; EU OSH Framework Directive 89/391/EEC; Norwegian Arbeidsmiljøloven Chapter 4; UNGPs Principle 11; ILO Convention 155.

**Legal logic:** Cross-cutting.

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 6 and Annex I, Annex III point 5.
- *Binding:* Regulation (EU) 2023/1230 (Machinery Regulation).
- *Binding:* Directive 89/391/EEC (OSH Framework Directive).
- *Binding:* Lov om arbeidsmiljø, arbeidstid og stillingsvern mv. (Arbeidsmiljøloven, Norway), Chapter 4.
- *Interpretive:* ILO Convention 155; UNGPs Principle 11.

**What to look for in a policy.** Where the company uses or plans to use AI in safety-critical contexts, the policy should commit to OHS framework primacy, specify how AI safety integrates with existing OHS processes, identify additional safeguards where AI introduces new safety considerations, address worker training. Where the company does not currently use such AI, the policy should commit to activation upon future deployment.

**Assessment criteria:**
- *Covered:* The policy addresses AI in safety-critical contexts where applicable, commits to OHS framework primacy, integrates AI safety with OHS, addresses training, references applicable OHS regulation.
- *Partial:* The policy mentions safety considerations but does not address OHS integration, or treats AI safety as exclusively a technical matter.
- *Missing:* The policy is silent despite material exposure, or treats safety-critical AI as covered by general AI risk management without OHS integration.

**Generator behavior.** *(1) If the company has uploaded HSE policies, OHS management systems, safety procedures, or risk assessments addressing AI or automated equipment, the Generator extracts that framework and integrates AI safety within existing OHS commitments. This is particularly important for companies in safety-critical sectors (construction, manufacturing, transport, healthcare). (2) If the company has uploaded Code of Conduct or sustainability material referencing worker safety, the Generator draws on that voice. (3) If no company material is available and the configuration profile indicates exposure to safety-critical AI use, the Generator produces foundation language meeting Machinery Regulation, OSH Framework Directive, and applicable national OHS law minimum, with explicit OHS framework primacy stated.*

---

### Requirement 3.7 — Non-discrimination in AI affecting workers

**Statement.** AI used in decisions about workers — recruitment, performance evaluation, promotion, discipline, scheduling, pay, termination — must not discriminate on the basis of protected characteristics (gender, ethnicity, age, religion, sexual orientation, disability, family situation, trade union activity, or other characteristics protected by applicable equality law). The policy commits the company to checking AI outputs for discriminatory patterns at the system level, conducting bias audits where appropriate, and remediating identified discriminatory outcomes including by halting deployment of biased systems.

**Tier:** 1a where binding equality law prohibits the discrimination at issue; 1b for AI Act bias-related obligations under Article 10 and Article 15; 1c where worker discrimination is the human rights dimension at issue.

**Scope:** All — applies regardless of ambition tier wherever AI affects workers.

**Jurisdiction:** Equality law is jurisdiction-specific. EU: Equal Treatment Directive 2000/78/EC, Race Equality Directive 2000/43/EC, Gender Goods and Services Directive 2004/113/EC, recast Equal Treatment in Employment Directive 2006/54/EC, Pay Transparency Directive 2023/970. Norway: Likestillings- og diskrimineringsloven. UK: Equality Act 2010. AI Act: Articles 10, 15.

**Legal logic:** Cross-cutting. Equality law-derived primarily; AI Act-derived for the bias monitoring and data governance dimensions.

**Source citations:**
- *Binding:* Multiple EU equality directives (2000/78/EC, 2000/43/EC, 2004/113/EC, 2006/54/EC, 2023/970).
- *Binding:* Lov om likestilling og forbud mot diskriminering (Likestillings- og diskrimineringsloven, Norway).
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Articles 10, 15.
- *Interpretive:* European Union Agency for Fundamental Rights reports on bias in AI; OHCHR B-Tech Project on AI and human rights.

**What to look for in a policy.** The policy should commit to non-discrimination, specify checking AI outputs at system level for discriminatory patterns, commit to bias audits where AI is used in significant employment decisions, specify remediation including halt-of-deployment authority, reference applicable equality law.

**Assessment criteria:**
- *Covered:* The policy commits to non-discrimination, specifies system-level outcome checking across protected characteristics, commits to bias audits, specifies remediation including halt-of-deployment authority, references equality law.
- *Partial:* The policy commits in general terms but does not specify mechanisms, or limits non-discrimination to AI Act bias monitoring without addressing equality law.
- *Missing:* The policy is silent, or treats non-discrimination as covered by general equality policies without AI-specific provision.

**Generator behavior.** *(1) If the company has uploaded an equality policy, anti-discrimination procedure, or DEI policy, the Generator extracts that framework and integrates AI-specific non-discrimination commitments into it, including bias auditing and halt-of-deployment authority. (2) If the company has uploaded an Own Workforce Policy or Code of Conduct addressing equality, the Generator draws on that voice and ensures consistency. (3) If no company material is available, the Generator produces foundation language meeting applicable equality law minimum (jurisdictionally-tailored — Norwegian Likestillings- og diskrimineringsloven, EU equality directives, etc.) and AI Act Articles 10 and 15 minimum, with specific bias monitoring and remediation processes named.*

---

### Requirement 3.8 — Prohibited AI use cases affecting workers

**Statement.** The policy explicitly identifies AI use cases that the company will not deploy in worker contexts because they are prohibited under applicable law or because the company has determined they are inconsistent with worker rights. This includes, at minimum:

(a) **Emotion recognition systems in workplace contexts** — prohibited under AI Act Article 5(1)(f) except for medical or safety reasons.

(b) **Social scoring of workers** — prohibited under AI Act Article 5(1)(c).

(c) **Biometric categorization to deduce or infer sensitive personal characteristics** — prohibited under AI Act Article 5(1)(g).

(d) **Solely automated decision-making producing legal or similarly significant effects on workers without GDPR Article 22 safeguards** — prohibited under GDPR Article 22.

(e) **AI-driven worker surveillance.** The framework treats AI-driven observation and surveillance of worker behavior as incompatible with the people-first principle. This includes keystroke logging, screen monitoring, sentiment analysis, behavioral tracking, AI-driven productivity surveillance at the individual level, and similar practices that observe worker behavior rather than supporting work. The framework distinguishes worker surveillance from legitimate operational monitoring necessary in defined contexts: occupational health and safety monitoring (preventing fatigue-related accidents and verifying use of safety equipment), equipment operation monitoring that incidentally records who operated machinery, anti-fraud monitoring in financial services, security access monitoring for restricted-access areas, and time tracking for payroll. Legitimate operational monitoring is governed by existing OHS, security, and operational policies and is not extended into worker surveillance under any reframing.

**Tier:** 1a for items (a)–(d) — binding AI Act and GDPR prohibitions, hard limits with active legal violation if breached. Tier 3 (framework principle) for item (e) — the framework's position on worker surveillance, going beyond binding law.

**Scope:** All — applies regardless of ambition tier. Items (a)–(d) apply to all AI Act and GDPR-bound entities. Item (e) is a framework-original commitment that activates at all ambition tiers because it derives from the people-first principle in Section 1.

**Jurisdiction:** EU AI Act Article 5; GDPR Article 22, Article 9. For item (e): UNGPs Principle 11; ILO Conventions on workers' rights and dignity at work; Council of Europe Framework Convention on AI emphasizing human dignity.

**Legal logic:** AI Act-derived and GDPR-derived for items (a)–(d); framework-original (HRDD-grounded) for item (e).

**Source citations:**
- *Binding:* Regulation (EU) 2024/1689 (AI Act), Article 5(1)(c), Article 5(1)(f), Article 5(1)(g).
- *Binding:* Regulation (EU) 2016/679 (GDPR), Articles 22, 9.
- *Interpretive:* European Commission guidelines on AI Act prohibited practices.
- *Interpretive (for item e):* UN Guiding Principles on Business and Human Rights, Foundational Principle 11; OHCHR B-Tech Project on AI and human rights, particularly outputs on workplace surveillance and worker dignity; ILO Conventions and Recommendations on workers' rights and decent work; Council of Europe Framework Convention on Artificial Intelligence (2024).
- *Framework-original:* The treatment of AI-driven worker surveillance as a category of prohibited use is a framework position.

**What to look for in a policy.** The policy should explicitly name the prohibited AI use cases and commit that the company will not deploy them. Items (a)–(d) should track AI Act Article 5 and GDPR Article 22 prohibitions. Item (e) should be addressed substantively — naming worker surveillance practices the company commits not to deploy and distinguishing them from legitimate operational monitoring with carve-outs named explicitly.

**Assessment criteria:**
- *Covered:* The policy explicitly names items (a)–(d) AI Act and GDPR prohibitions material to worker contexts and commits to exclusion. The policy addresses item (e) substantively — naming worker surveillance practices not deployed, naming legitimate operational monitoring carve-outs explicitly so the boundary is clear, and committing that legitimate operational monitoring will not be extended into surveillance under reframing. May extend to additional company-specific exclusions.
- *Partial:* The policy commits to compliance with AI Act and GDPR in general terms but does not explicitly name prohibited uses (items a–d). For item (e), the policy mentions worker dignity or non-surveillance in general terms but does not specify the practices excluded or name the operational monitoring carve-outs, leaving the boundary unclear.
- *Missing:* The policy is silent on prohibited AI uses, leaving open AI Act Article 5 prohibited practices. For item (e), the policy is silent on worker surveillance or treats it as a permissible management practice.

**Generator behavior.** *(1) If the company has uploaded an existing AI policy, IT policy, or HR policy addressing prohibited or restricted practices, the Generator extracts that exclusion language and ensures it covers items (a)–(e). (2) If the company has uploaded a Code of Conduct, Own Workforce Policy, or Whistleblowing procedure with statements on worker dignity, monitoring limits, or prohibited management practices, the Generator draws on that voice and integrates the framework's position on worker surveillance with company-specific framing. (3) If no company material is available, the Generator produces foundation language naming items (a)–(d) directly with AI Act Article and GDPR Article citations, and produces foundation language for item (e) that explicitly distinguishes worker surveillance from legitimate operational monitoring, with the operational monitoring carve-outs (OHS, equipment, anti-fraud, security access, payroll time) named explicitly so the boundary is clear.*

---

## How this section activates across company profiles

**Profile A — Mid-size manufacturer with mature HRDD:** All eight requirements activate. Notification (3.1) and oversight (3.2) requirements apply to AI in employment contexts. Norwegian Arbeidsmiljøloven and underlying collective agreement frameworks (where the company operates in Nordic codetermination jurisdictions) make consultation (3.5) operationally meaningful; similar provisions apply in German Betriebsverfassungsgesetz and Dutch Wet op de ondernemingsraden contexts. Safety-critical AI requirement (3.6) activates if AI is used in manufacturing equipment with worker safety implications. Non-discrimination (3.7) is material for AI in HR processes. The worker surveillance prohibition in 3.8(e) is consistent with the existing Code of Conduct values typical of this profile.

**Profile B — Safety-critical operations company in group context:** All eight requirements activate. National collective agreement framework applies. Safety-critical AI (3.6) is centrally important — companies in this profile operate in inherently safety-critical sectors (construction, environmental remediation, transport, healthcare) and any AI deployment activates OHS framework primacy. Worker surveillance prohibition in 3.8(e) is operationally significant — sectors with high physical labor intensity have historically been areas where AI-driven productivity monitoring tools are marketed, and the framework's position takes them off the table.

**Profile C — Small specialty distributor below regulatory thresholds:** All eight requirements activate, but operationally lighter at 60 employees. The notification (3.1) and information rights (3.3) requirements apply to any AI use affecting workers. Safety-critical AI (3.6) is unlikely to activate in distribution or service operations. Prohibited AI uses (3.8) including the worker surveillance prohibition activate regardless of size — a 60-person company could plausibly purchase worker monitoring software, and the framework's position prevents that as clearly as for larger companies.

---

## Open items for review

**Item (e) tier classification.** I tagged item (e) as Tier 3 (framework principle) because it goes beyond binding law. An argument could be made that it's Tier 1c (HRDD-derived duty of care) where workers' dignity rights under UNGPs Principle 11 are framed as binding obligations under HRDD law. The substantive treatment in the requirement is the same; the tier tag changes how the diagnostic surfaces non-compliance. Worth your view.

**Operational monitoring carve-outs.** I named five categories of legitimate operational monitoring (OHS, equipment, anti-fraud, security access, payroll time). This list is meant to be specific enough to prevent surveillance from being recharacterized as operational, while broad enough to permit genuinely necessary functions. Worth your view on whether the list captures what it should and excludes what it should.

**Cross-cutting consultation.** Worker consultation (3.5) cross-references appear in Sections 6, 7, 8, 10. The Diagnostic checks for consistency. Worth confirming this approach holds as we draft those sections.

**Generator behavior cascade format.** Each requirement now has explicit Generator behavior with three priority levels. Worth your view on whether this format works or whether it should be more compact.
