# AI Review Requirements Framer

**Department:** Clinical
**Category:** AI Governance & Quality
**Version:** 1.0
**Author:** Naveen Rao V — AI Transformation BA
**Organisation:** Spectrum.Life
**Status:** ✅ Production Ready — Tested April 2026

---

## About This Skill

### What This Skill Is About

AI Review is Spectrum.Life's most unique and proprietary AI product. While the industry reviews 2-5% of clinical sessions, AI Review gives Spectrum.Life visibility across 100% of consented sessions — running every transcript through four structured agents aligned to best-practice clinical supervision frameworks.

Stephen Costello described the four agents in his Dev Diary on April 8, 2026:
- **Clinical quality** — therapeutic model application, collaboration, structure, interventions
- **Safety and risk** — risk exploration, safeguarding, escalation pathways
- **Consistency** — standards maintained over time, not just isolated sessions
- **Governance** — consent evidenced, boundaries maintained, documentation complete

As Spectrum.Life's clinical standards evolve — as new therapeutic models are adopted, as regulatory requirements change, as the organisation grows into Australia and new markets — new review agents will need to be designed, specified and built. That is requirements work. That is BA work.

### The Real Problem This Solves

Right now, when a clinical leader identifies a new quality standard that AI Review should check for — a new safeguarding requirement, a new therapeutic model, a new governance obligation — there is no structured way to translate that clinical knowledge into an agent specification that the engineering team can build from.

The clinical team knows what good looks like. The engineering team knows how to build agents. The gap between them is a requirements document. This skill writes that document — turning a clinical leader's description of a new review standard into a structured, precise agent specification ready for the development team.

### When This Skill Comes Into Picture

A clinical lead or medical director identifies a new standard they want AI Review to check — for example, a new safeguarding obligation following a regulatory change, or a new therapeutic model being adopted across the clinical team. They describe what they want to the BA. The BA uses this skill to produce a complete agent specification — what the agent monitors, what good and poor practice looks like, how it scores, what it flags, what the output means for the clinician.

### What It Gives The Team

Clinical leaders get their standards translated into buildable requirements without needing to understand AI or engineering. The engineering team receives a precise, unambiguous specification they can build from directly. The clinical governance team gets a documented audit trail of what each agent checks and why. And Stephen's AI Review product continues to evolve as Spectrum.Life's clinical standards evolve — maintaining the 100% visibility that makes it commercially unique.

### The Before and After

**Before this skill** — when a clinical leader wants to add a new review standard, the requirements are communicated informally. The engineering team interprets the clinical intent as best they can. What gets built may not reflect what the clinician meant. Iterations waste time. The agent may miss nuance that took years of clinical practice to develop.

**After this skill** — every new AI Review agent starts with a structured, clinically validated specification. The BA facilitates the translation between clinical expertise and technical build. Requirements are precise, testable and documented. The agent reflects exactly what the clinical team intended.

> AI Review's value is 100% visibility into clinical quality. This skill ensures that as Spectrum.Life grows, every new quality standard gets built into that visibility — precisely, quickly and with full clinical governance documentation.

---

## Real Spectrum.Life Data Behind This Skill

### The Four Existing AI Review Agents — Confirmed from Dev Diary April 8, 2026

| Agent | What It Reviews |
|-------|----------------|
| **Clinical Quality** | Therapeutic model application, collaboration, structure, interventions used |
| **Safety and Risk** | Risk exploration, safeguarding, escalation pathways |
| **Consistency** | Standards maintained over time — not just isolated sessions |
| **Governance** | Consent evidenced, boundaries maintained, documentation complete |

### Key Facts

| Metric | Source | Relevance |
|--------|--------|-----------|
| 100% of consented sessions reviewed | Dev Diary April 8, 2026 | Every new agent immediately applies at full scale |
| 250,000 sessions/year transcribed | Dev Diary April 8, 2026 | Volume of data new agents will run against |
| Industry standard: 2-5% reviewed | Dev Diary April 8, 2026 | Context for why quality of agent requirements matters |
| 350 in-house clinicians | Dev Diary April 8, 2026 | Clinical expertise that feeds requirements |
| 1,000+ network clinicians | Dev Diary April 8, 2026 | Scale of workforce agents will support |
| Australia expansion — 3 acquisitions | March 2026 press release | New markets = new regulatory requirements = new agents |

### Stephen's Exact Words on AI Review Build Philosophy

> *"Our clinicians translate years of therapeutic practice into the structured logic that powers AI Review. They design the escalation protocols that govern Cara. They validate that the output meets the same clinical standards they hold themselves to every day."*

This skill formalises that translation process — making it consistent, documented and scalable.

---

## How To Use This Skill

**Trigger phrase:**

```
AI Review agent: [describe the new clinical 
standard or quality check to be built]
```

**Examples:**

```
AI Review agent: We want to check whether 
clinicians are adequately exploring suicidal 
ideation when a member mentions hopelessness 
— specifically whether they are using a 
structured risk assessment approach.

AI Review agent: We need an agent that checks 
whether clinicians are maintaining appropriate 
professional boundaries — particularly around 
dual relationships and self-disclosure.

AI Review agent: Following our expansion into 
Australia, we need to check compliance with 
Australian safeguarding obligations for 
mandatory reporting of child safety concerns.
```

---

## The Skill Instructions

Copy everything in the block below exactly into the Claude Skills instructions field when creating this skill.

---

```
SKILL NAME: AI Review Requirements Framer

DEPARTMENT: Clinical
CATEGORY: AI Governance & Quality
VERSION: 1.0
BUILT BY: Naveen Rao V — AI Transformation BA
ORGANISATION: Spectrum.Life

TRIGGER: "AI Review agent: [describe the new 
clinical standard or quality check to be built]"

════════════════════════════════════════════════
PURPOSE
════════════════════════════════════════════════

Translate a clinical leader's description of a 
new quality standard into a structured, precise 
AI Review agent specification — ready for the 
engineering team to build from.

This skill bridges the gap between Spectrum.Life's 
clinical expertise and its engineering capability — 
ensuring every new AI Review agent is built to 
exactly the standard the clinical team intends.

This skill produces a complete agent specification 
covering:
- What the agent monitors and why
- What good and poor practice looks like
- How the agent scores and flags
- What the output means for the clinician
- What governance and testing requirements apply

════════════════════════════════════════════════
CORE PRINCIPLES — NEVER VIOLATE THESE
════════════════════════════════════════════════

PRINCIPLE 1 — CLINICAL INTENT FIRST
The specification must faithfully capture the 
clinical intent behind the new standard. If the 
intent is unclear — flag it for clarification 
before completing the specification.

PRINCIPLE 2 — DEVELOPMENT NOT SURVEILLANCE
Every agent specification must frame output 
as clinician development. Flags are learning 
opportunities — not performance management.
This is Stephen's stated philosophy — honour it.

PRINCIPLE 3 — PRECISION OVER BREVITY
Vague requirements produce poor agents. Be 
specific about what the agent looks for — 
provide examples of good practice, poor 
practice and edge cases.

PRINCIPLE 4 — TESTABLE REQUIREMENTS
Every requirement must be testable. If a 
requirement cannot be verified — rewrite it 
until it can. Engineering cannot build what 
cannot be tested.

PRINCIPLE 5 — REGULATORY AWARENESS
Flag any regulatory, legal or compliance 
considerations that affect the agent — 
GDPR, EU AI Act, MHRA, Australian mandatory 
reporting, NICE guidelines, MHC standards.

════════════════════════════════════════════════
OUTPUT STRUCTURE — PRODUCE ALL 6 PARTS
════════════════════════════════════════════════

PART 1 — AGENT OVERVIEW
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Agent Name: [clear descriptive name]
Agent Category: [Clinical Quality / Safety & 
Risk / Consistency / Governance / New category]
Clinical Rationale: [why this standard matters]
Regulatory Driver: [any compliance requirement]
Priority: [Critical / High / Standard]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PART 2 — WHAT THE AGENT MONITORS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Primary monitoring focus: [what specifically]
Input data: [what transcript elements it reads]
Context required: [session type, member history, 
                   clinician context if needed]
Scope: [which session types this applies to]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PART 3 — GOOD PRACTICE INDICATORS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
List exactly what GOOD practice looks like:
- Minimum 3 specific, observable indicators
- Include example language or behaviour
- Reference clinical framework where relevant
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PART 4 — POOR PRACTICE INDICATORS AND FLAGS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
List exactly what POOR practice looks like:
- Minimum 3 specific, observable indicators
- Include example language or behaviour
- Distinguish between: 
  LEARNING FLAG — practice to develop
  SAFETY FLAG — requires supervisor review
  URGENT FLAG — requires immediate action
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PART 5 — SCORING AND OUTPUT SPECIFICATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Scoring approach: [how the agent rates the session]
Output format for clinician dashboard:
  - What they see
  - What a flag looks like
  - What the flag links to in the transcript
  - What action is expected from the clinician
Supervisor visibility: [what supervisors see]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PART 6 — GOVERNANCE AND TESTING REQUIREMENTS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Clinical validation required: [yes/no + who]
Regulatory flags: [GDPR, EU AI Act, NICE, 
                   MHRA, MHC, Australian regs]
Test cases required: [minimum number + types]
False positive risk: [low/medium/high + mitigation]
False negative risk: [low/medium/high + mitigation]
Clinician communication plan: [how to introduce]
Review frequency: [how often agent is reviewed]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

════════════════════════════════════════════════
LANGUAGE RULES
════════════════════════════════════════════════

ALWAYS:
- Use precise, unambiguous language
- Give observable, specific examples
- Frame flags as development opportunities
- Reference clinical frameworks by name
- Flag any ambiguity for clarification

NEVER:
- Use vague language — "appropriate" without 
  defining what appropriate means
- Write untestable requirements
- Frame output as performance management
- Ignore regulatory implications
- Assume clinical knowledge the engineer 
  would not have

════════════════════════════════════════════════
GOVERNANCE RULES
════════════════════════════════════════════════

CLINICAL VALIDATION:
- All agent specifications require review 
  by a clinical lead before engineering begins
- This skill produces a draft — clinical 
  sign-off is mandatory before build

REGULATORY:
- EU AI Act Article 13 — transparency 
  requirements apply to AI Review agents
- GDPR — agent output must not create 
  identifiable profiles beyond clinical need
- NICE guidelines — reference where relevant

QUALITY:
- Every specification must include minimum 
  test case requirements
- False positive and false negative risks 
  must be assessed before build sign-off
```

---

## Testing Results

### Testing Methodology

AI Review Requirements Framer is tested against three different types of new agent requests — a safety-focused agent, a clinical quality agent and a governance agent — to confirm the skill produces precise, testable, clinically sound specifications in every case. The critical test confirms the skill correctly handles an ambiguous request by flagging it for clarification rather than proceeding with assumptions.

---

### Stage 1 — Solo Consistency Test

*Confirm the skill produces complete, precise specifications for standard new agent requests.*

---

**Test 1A — Standard: Suicidal Ideation Exploration Agent**

**Input:**
```
AI Review agent: We want to check whether 
clinicians are adequately exploring suicidal 
ideation when a member mentions hopelessness — 
specifically whether they are using a structured 
risk assessment approach.
```

**Part 1 — Agent Overview:**
```
Agent Name: Suicidal Ideation Exploration Checker
Agent Category: Safety & Risk
Clinical Rationale: When members express hopelessness 
or implicit risk indicators, clinicians must 
systematically explore suicidal ideation rather 
than accepting surface-level reassurance. Inadequate 
exploration is a significant clinical safety risk.
Regulatory Driver: Mental Health Commission (MHC) 
standards for risk assessment — mandatory in Ireland. 
NICE Clinical Guideline CG90 (Depression in Adults).
Priority: Critical
```

**Part 2 — What The Agent Monitors:**
```
Primary Focus: Whether clinician explicitly explores 
suicidal ideation when hopelessness or implicit risk 
indicators appear in member's language.

Input Data: Full session transcript — member 
language, clinician responses, session flow.

Context Required: Presenting issue, session type 
(triage / support / therapy). Higher scrutiny 
applies in triage sessions.

Scope: All session types where member expresses 
hopelessness, worthlessness, or implicit 
risk language.
```

**Part 3 — Good Practice Indicators:**
```
1. Clinician explicitly names and explores 
   suicidal ideation within 2-3 exchanges of 
   hopelessness language appearing
   Example: "When you say things feel hopeless, 
   I want to make sure I understand — are you 
   having any thoughts of harming yourself?"

2. Clinician uses structured risk assessment 
   approach — frequency, intent, plan, means, 
   protective factors
   Example: "How often are these thoughts 
   occurring?" / "Do you have a plan?"

3. Clinician documents risk level and 
   communicates next steps clearly to member
   Example: "Based on what you've shared, 
   I want to make sure we have a safety plan 
   in place before we finish today."

4. Clinician explores protective factors 
   alongside risk
   Example: "What has kept you safe when 
   these thoughts have been strongest?"
```

**Part 4 — Poor Practice Indicators and Flags:**
```
LEARNING FLAG:
- Clinician acknowledges hopelessness but 
  does not explicitly ask about suicidal ideation
  Example: "It sounds like things feel very 
  difficult right now. Let's talk about what 
  has been happening." [no direct risk exploration]

LEARNING FLAG:
- Risk exploration occurs but is incomplete — 
  frequency asked but intent/plan not explored

SAFETY FLAG:
- Member expresses explicit suicidal ideation 
  and clinician does not follow escalation 
  pathway within the session

URGENT FLAG:
- Member discloses active plan or intent and 
  clinician does not immediately activate 
  safeguarding protocol
```

**Part 5 — Scoring and Output:**
```
Scoring: 0-3 scale per session
3 — Full structured exploration documented
2 — Partial exploration — some elements missing
1 — Acknowledgement only — no direct exploration
0 — Risk language present — no exploration at all

Dashboard output for clinician:
- Score displayed with session reference
- Flag links to exact moment risk language 
  appeared in transcript
- Flag links to clinician's response (or absence)
- Suggested development resource attached

Supervisor visibility:
- All scores below 2 surfaced to supervisor
- All Safety and Urgent flags require 
  supervisor acknowledgement within 24 hours
```

**Part 6 — Governance:**
```
Clinical Validation: Required — Medical Director 
(Dr Rizwan Khalid) and Mental Health Clinical Lead
Regulatory Flags: MHC standards, NICE CG90, 
EU AI Act transparency, GDPR
Test Cases Required: Minimum 20 — covering 
explicit ideation, implicit ideation, false 
reassurance, and no-risk baseline
False Positive Risk: Medium — agent may flag 
sessions where risk was explored verbally 
but not transcribed. Mitigation: human review 
of all Safety flags before clinician delivery.
False Negative Risk: High — agent may miss 
subtle implicit risk language. Mitigation: 
clinician-authored phrase bank for training.
Clinician Communication: Introduce as 
development support — frame as "helping 
you capture every important moment"
Review Frequency: Quarterly — or following 
any serious incident involving missed risk
```

**Result: ✅ Pass** — Complete 6-part specification. Precise and observable indicators. Three flag levels correctly used. Regulatory drivers identified. False positive/negative risks assessed.

---

**Test 1B — Standard: Therapeutic Boundaries Agent**

**Input:**
```
AI Review agent: We need an agent that checks 
whether clinicians are maintaining appropriate 
professional boundaries — particularly around 
self-disclosure and dual relationships.
```

**Part 1 — Agent Overview:**
```
Agent Name: Professional Boundaries Compliance Checker
Agent Category: Governance
Clinical Rationale: Boundary violations are a 
leading cause of regulatory complaints and 
member harm in therapeutic settings. Consistent 
monitoring protects members, clinicians and 
the organisation.
Priority: High
```

**Part 3 — Good Practice Indicators:**
```
1. Self-disclosure is purposeful, brief and 
   in service of the member — not clinician need
   Example: "I can understand that — many people 
   find that." [normalising, not personal]

2. Clinician maintains professional role clarity 
   throughout — does not shift to advice-giving, 
   friendship or personal relationship
   
3. Clinician appropriately declines or redirects 
   personal questions from member
   Example: "I appreciate you asking — but this 
   time is really for you."
```

**Result: ✅ Pass** — Correct governance category. Observable indicators. All 6 parts produced with appropriate precision.

---

### Stage 2 — Edge Case Test

*Test boundary situations — including ambiguous requests.*

---

**Test 2A — Critical Edge Case: Ambiguous Request**

**Input:**
```
AI Review agent: We want the agent to check 
if clinicians are doing good therapy.
```

**Output — Part 1:**
```
⚠️ CLARIFICATION REQUIRED BEFORE PROCEEDING

This request is too broad to produce a precise, 
testable agent specification. "Good therapy" is 
not a single observable standard — it is a 
collection of distinct competencies each 
requiring its own specification.

PRINCIPLE 3 APPLIED: Precision over brevity. 
Vague requirements produce poor agents.

CLARIFICATION QUESTIONS FOR CLINICAL LEAD:

1. Which specific aspect of therapeutic quality 
   do you want to monitor? For example:
   - Therapeutic alliance (rapport, collaboration)
   - CBT technique application
   - Goal-setting and review
   - Session structure and pacing
   - Psychoeducation quality

2. Is this for a specific therapy model 
   (CBT, DBT, ACT, person-centred)?

3. Is this triggered by a specific clinical 
   incident or quality concern?

4. Which clinician group does this apply to?

Please clarify and I will produce a precise 
agent specification for each distinct standard.
```

**Result: ✅ Pass — Critical** — Skill correctly refused to proceed with a vague request. Clarification questions asked. Principle 3 applied. This is exactly the right BA behaviour — precision over speed!

---

**Test 2B — Edge Case: New Regulatory Requirement (Australia)**

**Input:**
```
AI Review agent: Following our Australia expansion, 
we need to check clinician compliance with 
Australian mandatory reporting obligations 
for child safety concerns.
```

**Part 1 — Agent Overview:**
```
Agent Name: Australian Mandatory Reporting 
           Compliance Checker
Agent Category: Governance — Regulatory
Clinical Rationale: Australian mandatory reporting 
laws require clinicians to report reasonable 
belief of child harm or risk of harm to 
relevant authorities. Non-compliance carries 
criminal liability in all Australian states.
Regulatory Driver: Children and Young Persons 
(Care and Protection) Act 1998 (NSW), Children 
Youth and Families Act 2005 (VIC) — and 
equivalent state legislation across all 
Australian states and territories.
Priority: Critical
```

**Part 6 — Governance:**
```
Clinical Validation: Australian Clinical Lead 
required — Valion Health clinical governance 
team (acquired March 2026)
Regulatory Flags: Australian state-specific 
mandatory reporting legislation — varies by 
state. AHPRA (Australian Health Practitioner 
Regulation Agency) standards. GDPR equivalent 
under Australian Privacy Act 1988.
CRITICAL NOTE: This agent specification must 
be reviewed by Australian-qualified legal 
counsel before build commences.
```

**Result: ✅ Pass** — Correctly identified as critical priority. Australian-specific regulatory framework applied. Legal counsel flag raised. Shows awareness of post-acquisition compliance obligation.

---

### Stage 3 — Real Spectrum.Life Scenario Test

*Test with a scenario reflecting Spectrum.Life's actual AI Review architecture and clinical context.*

---

**Test 3A — New Agent Building on Existing Framework**

**Input:**
```
AI Review agent: The existing safety and risk 
agent checks for risk exploration. We now want 
a separate consistency agent that checks whether 
individual clinicians maintain the same risk 
exploration standards across all their sessions 
over time — not just in individual sessions.
```

**Part 1 — Agent Overview:**
```
Agent Name: Risk Exploration Consistency Tracker
Agent Category: Consistency — extends existing 
               Safety & Risk agent
Clinical Rationale: A clinician who explores 
risk thoroughly in one session but inconsistently 
across sessions may have developed unhealthy 
assumptions about certain members. Consistency 
monitoring identifies this pattern before it 
becomes a safety concern.
Priority: High
```

**Part 2 — What The Agent Monitors:**
```
Primary Focus: Pattern of risk exploration 
behaviour across a single clinician's sessions 
over a 30-day rolling window.

Input Data: Aggregated scores from the existing 
Suicidal Ideation Exploration Checker — applied 
across all sessions for a single clinician.

Context Required: Session count, member caseload 
complexity, session types in the window.

Scope: All clinicians with 10+ sessions in 
the rolling window.
```

**Result: ✅ Pass** — Correctly identified as a consistency layer on an existing agent. Rolling window approach specified. Builds on AI Review's existing architecture precisely.

---

### Stage 4 — Governance & Safety Review

| Governance Check | Result |
|-----------------|--------|
| All specifications include clinical validation requirement | ✅ Confirmed |
| Ambiguous requests flagged for clarification | ✅ Confirmed |
| Development not surveillance framing throughout | ✅ Confirmed |
| Regulatory flags identified in every specification | ✅ Confirmed |
| False positive and negative risks assessed | ✅ Confirmed |
| Three flag levels used correctly | ✅ Confirmed |
| All 6 output parts produced consistently | ✅ Confirmed |
| Australian regulatory context correctly handled | ✅ Confirmed |
| Legal counsel flag raised for high-risk regulatory items | ✅ Confirmed |
| Clinician communication plan included | ✅ Confirmed |

**Governance Result: ✅ Approved for Production**

---

## Version History

| Version | Change | Reason |
|---------|--------|--------|
| v1.0 | Initial build | Built directly from Stephen Costello's Dev Diary April 8, 2026 — four AI Review agents confirmed with exact scope |

---

## Test Summary

| | |
|--|--|
| **Skill** | AI Review Requirements Framer |
| **Version** | 1.0 |
| **Tests Run** | 5 across 4 stages |
| **Tests Passed** | 5 / 5 |
| **Critical Tests** | 2 (ambiguous request + Australian regulatory) |
| **Critical Tests Passed** | 2 / 2 |
| **Agent Types Tested** | Safety & Risk, Governance, Consistency |
| **Iteration Needed** | None |
| **Production Ready** | ✅ Yes |

---

## Skill Description (For Claude Skills Field)

```
Translates clinical leaders' descriptions of new 
quality standards into structured AI Review agent 
specifications — ready for Spectrum.Life's 
engineering team to build from. Produces agent 
overview, monitoring scope, good and poor practice 
indicators, scoring specification, and governance 
requirements. Flags ambiguous requests for 
clarification rather than proceeding with 
assumptions. Applies EU AI Act, GDPR, NICE and 
Australian regulatory awareness throughout.
```

---

## Estimated Business Value — Real Numbers

| Metric | Real Context | How This Skill Helps |
|--------|-------------|---------------------|
| 100% session visibility | AI Review core capability | Every new agent immediately applies at full scale — 250,000 sessions/year |
| 350 in-house clinicians | Dev Diary April 8, 2026 | Requirements capture their expertise precisely |
| 3 Australian acquisitions | March 2026 | New regulatory requirements = new agents needed immediately |
| Industry standard 2-5% reviewed | Dev Diary | Maintaining 100% requires constantly evolving agents |
| Clinical quality moat | Stephen's commercial thesis | Precise requirements = better agents = stronger competitive differentiation |

---

## Relationship To Other Skills

| Scenario | Skill Activated |
|----------|----------------|
| New clinical standard identified | AI Review Requirements Framer ← this skill |
| Agent built — member in session | Clinical Escalation Prompter |
| Member triaged | MatchTech Triage Router |
| Between-session support | Between-Session Check-In Contextualiser |

> AI Review Requirements Framer is the only skill in this library that is outward-facing to the engineering team rather than member-facing. It is the BA's core contribution to Spectrum.Life's most proprietary and commercially valuable AI product.

---

*Spectrum.Life AI Skills Library | Skill 4 of 12 | Clinical Department*
*Built and tested by Naveen Rao V — AI Transformation BA | April 2026*
*GitHub: github.com/Naveenraov/ba-digitalhealth-skills-library*
