# Digital Health AI Skills Library

### Naveen Rao V | AI Transformation Business Analyst
**LinkedIn:** linkedin.com/in/naveen-rao-v-01593a169 &nbsp;|&nbsp; **GitHub:** github.com/Naveenraov

---

> A tested library of Claude AI Skills designed specifically for Spectrum.Life's digital health platform — mapped to real departments, real products and real clinical workflows. Every skill is built using a structured BA design methodology, tested across four stages and documented with full business value evidence.

---

## Library At A Glance

| | |
|--|--|
| **Skills** | 12 production-ready Claude Skills |
| **Departments** | 5 departments |
| **Testing** | 4-stage framework — every skill |
| **Governance** | Clinical safety + GDPR + EU AI Act |
| **Members Served** | 15 million across insurer, workplace, education |

---

## Library Structure

```
┌─────────────────────────────────────────────────────────────────┐
│           SPECTRUM.LIFE AI SKILLS LIBRARY                       │
│           Naveen Rao V — AI Transformation BA                   │
└─────────────────────────────────────────────────────────────────┘
                              │
        ┌─────────────────────┼──────────────────────┐
        │                     │                      │
        ▼                     ▼                      ▼
┌───────────────┐   ┌─────────────────┐   ┌─────────────────────┐
│  🏥 CLINICAL  │   │   👥 HR &        │   │  📈 SALES & OPS     │
│   4 Skills    │   │   PEOPLE         │   │   2 Skills          │
│               │   │   2 Skills       │   │                     │
│ ✅ Clinical   │   │                  │   │ 🔜 Salesforce       │
│    Escalation │   │ 🔜 HR Teams      │   │    Record Updater   │
│    Prompter   │   │    Query         │   │                     │
│               │   │    Responder     │   │ 🔜 Insurance        │
│ ✅ MatchTech  │   │                  │   │    Partner          │
│    Triage     │   │ 🔜 Onboarding    │   │    Onboarding       │
│    Router     │   │    Experience    │   │    Planner          │
│               │   │    Planner       │   │                     │
│ 🔜 Between-   │   │                  │   └─────────────────────┘
│    Session    │   └─────────────────┘
│    Check-In   │
│               │
│ 🔜 AI Review  │
│    Requirements│
│    Framer     │
└───────────────┘
        │
        ▼
┌─────────────────────────────────────────────────────────────────┐
│                  ⚙️ AI TRANSFORMATION   3 Skills                │
│                                                                  │
│  🔜 Automation          🔜 Agentforce         🔜 Clinical AI   │
│     Opportunity             Use Case               Governance   │
│     Mapper                  Framer                 Checker      │
└─────────────────────────────────────────────────────────────────┘
        │
        ▼
┌─────────────────────────────────────────────────────────────────┐
│                  📊 REPORTING   1 Skill                         │
│                                                                  │
│              🔜 Executive AI Transformation Update              │
└─────────────────────────────────────────────────────────────────┘
```

---

## Department Libraries

### 🏥 Clinical — 4 Skills
*Supporting Spectrum.Life's clinical operations — member escalation, care pathway triage, between-session continuity and AI Review governance.*

| # | Skill | Maps To | Version | Status |
|---|-------|---------|---------|--------|
| 1 | [Clinical Escalation Prompter](./clinical/clinical-escalation-prompter-v1.1.md) | Cara + Teams + all Claude channels | v1.1 | ✅ Production Ready |
| 2 | [MatchTech Triage Router](./clinical/matchtec-triage-router-v1.1.md) | MatchTech — 5-step NICE pathway | v1.1 | ✅ Production Ready |
| 3 | Between-Session Check-In Contextualiser | Cara + AI Scribe single-thread vision | v1.0 | 🔜 Coming Soon |
| 4 | AI Review Requirements Framer | AI Review — 4 clinical quality agents | v1.0 | 🔜 Coming Soon |

---

### 👥 HR & People — 2 Skills
*Automating HR operations — building on Spectrum.Life's live Claude in Teams implementation.*

| # | Skill | Maps To | Version | Status |
|---|-------|---------|---------|--------|
| 5 | HR Teams Query Responder | Claude in Teams — live HR chatbot | v1.0 | 🔜 Coming Soon |
| 6 | Onboarding Experience Planner | People team — 500+ growing staff | v1.0 | 🔜 Coming Soon |

---

### 📈 Sales & Operations — 2 Skills
*Reducing manual CRM work and scaling Spectrum.Life's growing insurance partner base.*

| # | Skill | Maps To | Version | Status |
|---|-------|---------|---------|--------|
| 7 | Salesforce Record Updater | Salesforce CRM — 3-year optimisation | v1.0 | 🔜 Coming Soon |
| 8 | Insurance Partner Onboarding Planner | L&G Spark + new insurer + Australia | v1.0 | 🔜 Coming Soon |

---

### ⚙️ AI Transformation — 3 Skills
*Powering Stephen Costello's 40-60% automation vision across all departments.*

| # | Skill | Maps To | Version | Status |
|---|-------|---------|---------|--------|
| 9 | Automation Opportunity Mapper | Stephen's 40-60% automation goal | v1.0 | 🔜 Coming Soon |
| 10 | Agentforce Use Case Framer | Agentforce — greenfield implementation | v1.0 | 🔜 Coming Soon |
| 11 | Clinical AI Governance Checker | EU AI Act + GDPR + ISO 27001 | v1.0 | 🔜 Coming Soon |

---

### 📊 Reporting — 1 Skill
*Keeping CEO and CPO informed on AI transformation progress.*

| # | Skill | Maps To | Version | Status |
|---|-------|---------|---------|--------|
| 12 | Executive AI Transformation Update | Weekly reporting to Stephen + Lynda | v1.0 | 🔜 Coming Soon |

---

## Skills Discarded — With Reasons

| Skill | Reason |
|-------|--------|
| Clinical Session Note Summariser | AI Scribe already transcribes 250,000 sessions/year — duplication |
| Cara Wellbeing Response Template | Cara generates responses via Haiku + Nova pipeline — duplication |
| Healthily AI Pathway Requirement Writer | Third-party integration with its own technical teams — too niche |
| Insurance Client Proposal Drafter | Commercial team's domain — wrong function for BA |

*Discarding these demonstrates BA critical thinking — building solutions for real gaps, not duplicating what already exists.*

---

## Testing Methodology

Every skill is tested across four stages before being marked production ready.

```
┌─────────────────────────────────────────────────────────────────┐
│                    4-STAGE TESTING FRAMEWORK                    │
├──────────────┬──────────────┬──────────────┬────────────────────┤
│   STAGE 1    │   STAGE 2    │   STAGE 3    │     STAGE 4        │
│              │              │              │                    │
│    SOLO      │  EDGE CASE   │   REAL       │   GOVERNANCE       │
│ CONSISTENCY  │    TEST      │  SCENARIO    │    REVIEW          │
│              │              │              │                    │
│ Run 3 times  │ Test boundary│ Test with    │ GDPR, clinical     │
│ with standard│ situations,  │ actual       │ safety, audit      │
│ inputs       │ ambiguous    │ Spectrum.Life│ trail, EU AI       │
│              │ cases, user  │ member types │ Act compliance     │
│ Confirm      │ minimisation │ and channels │                    │
│ consistent   │              │              │ Full governance    │
│ output       │ Confirm safe │ Confirm      │ checklist          │
│              │ boundaries   │ real-world   │                    │
│              │              │ accuracy     │ Sign-off           │
└──────────────┴──────────────┴──────────────┴────────────────────┘
```

---

## How To Use These Skills

Each skill file contains:

```
┌─────────────────────────────────────────┐
│           SKILL FILE STRUCTURE          │
│                                         │
│  1. About This Skill                    │
│     → Plain-English explanation         │
│     → Problem it solves                 │
│     → Real Spectrum.Life data           │
│                                         │
│  2. How To Use                          │
│     → Trigger phrase + example          │
│                                         │
│  3. Skill Instructions                  │
│     → Copy directly into Claude Skills  │
│                                         │
│  4. Testing Results                     │
│     → All 4 stages with real inputs     │
│        and outputs                      │
│                                         │
│  5. Business Value                      │
│     → Real Spectrum.Life metrics        │
│                                         │
│  6. Version History                     │
│     → Why the skill evolved             │
└─────────────────────────────────────────┘
```

**To create a skill in Claude:**
1. Go to Claude.ai → Settings → Feature Preview → Skills
2. Click Create New Skill
3. Copy the Name, Description and Instructions from the skill file
4. Save and test

---

## Build Progress

```
Phase 1 — Anchor Skills (One per department)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
✅ Skill 1 — Clinical Escalation Prompter   (Clinical)
✅ Skill 2 — MatchTech Triage Router        (Clinical)
🔜 Skill 5 — HR Teams Query Responder      (HR)
🔜 Skill 7 — Salesforce Record Updater     (Sales & Ops)
🔜 Skill 9 — Automation Opportunity Mapper (AI Transformation)

Phase 2 — Complete Department Libraries
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🔜 Skills 3-4   Clinical department complete
🔜 Skills 5-6   HR department complete
🔜 Skills 7-8   Sales & Ops complete
🔜 Skills 9-11  AI Transformation complete
🔜 Skill 12     Reporting complete

Phase 3 — Full Library Live
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🔜 All 12 skills tested, documented and published
```

---

## About This Library

Built as part of an AI Transformation BA portfolio — demonstrating practical, governed, tested Claude Skills for a real digital health environment. The goal is not to show that AI can automate everything. It is to show that with the right BA thinking — structured problem statements, governed design, rigorous testing and honest documentation — AI Skills can be trusted to handle sensitive, high-stakes interactions consistently and safely.

Every skill in this library was designed AFTER thorough research into Spectrum.Life's real products, real clinical frameworks, real operational challenges and real business targets. Skills that would duplicate existing capabilities (AI Scribe, Cara's pipeline) were discarded. Skills that solve confirmed real gaps were built and tested.

**Built with:**
- Claude by Anthropic — Sonnet for daily building, Opus for deep research
- CRAFT Prompting Framework
- 4-Stage Testing Methodology
- Live website research — spectrum.life + Stephen Costello's Dev Diary series (April 2026)

---

*Naveen Rao V | AI Transformation Business Analyst | Dublin, Ireland*
*LinkedIn: linkedin.com/in/naveen-rao-v-01593a169*
*GitHub: github.com/Naveenraov*
*Built: April 2026*
