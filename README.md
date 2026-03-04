# Houston AI Authority Engine

An AI-driven authority engine designed to establish **Leon Coe** and **Amplify Intelligence** as the dominant AI voice in Houston across Energy, Healthcare, and Professional Services.

---

## Project Overview

This repository is the operating infrastructure for a structured AI authority campaign. It is not a content vault — it is the strategic and execution backbone that powers a repeatable system for generating, distributing, and converting AI thought leadership into business opportunities.

The engine combines structured prompts, deterministic AI execution, multi-model agent orchestration, and CRM-integrated conversion tracking to produce enterprise-grade authority assets at scale.

**Three Pillars:**
- **Leon Coe** — Human trust anchor and thought leader
- **Amplify Intelligence** — Delivery, proof, and enterprise conversion engine
- **Houston AI Club** — Community convening and visibility layer

---

## System Goals

- Build and sustain AI authority for Leon Coe across Houston's key industries
- Generate executive-level AI insights that drive industry-specific conversations
- Convert thought leadership into business opportunities via a structured conversion funnel
- Create repeatable, scalable content infrastructure that compounds over time

---

## Current Project Phase

**Phase 2 — Controlled Activation**

The first authority assets have been produced by the system and are live in `/content/executive-memos`:

| Asset | Vertical |
|---|---|
| Houston Energy AI Operating Model | Energy |
| Houston Healthcare AI Governance | Healthcare |
| Houston Professional Services AI Operating Model | Professional Services |

These executive memos represent the system's first real-world output — demonstrating that the pipeline from strategy to published authority asset is fully operational.

---

## System Architecture Overview

The authority engine runs a linear, feedback-driven pipeline:

```
Strategy → Templates → AI Execution → Content Assets → Distribution → CRM Tracking
```

1. **Strategy** — Master authority plan defines target verticals, personas, and content angles
2. **Templates** — Structured prompt templates constrain AI output to the correct format and voice
3. **AI Execution** — Multi-model agents execute content generation with defined cognitive roles
4. **Content Assets** — Executive memos, case studies, briefs, and event recaps are produced
5. **Distribution** — Assets flow to LinkedIn, blog, newsletter, and office hours funnels
6. **CRM Tracking** — Engagement signals are captured and mapped to pipeline opportunities

See [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md) for the full pipeline diagram.

---

## Repository Structure

```
/content
  /executive-memos        — Published authority assets (memos, briefs)

/templates                — Reusable structured prompt templates
  executive-memo.md
  case-study.md
  event-recap.md
  weekly-brief.md
  pipeline-entry.md
  content-atomization.md

/docs                     — System architecture, strategy, tracking, and agent docs
  INDEX.md                — Documentation navigation hub
  ARCHITECTURE.md         — Pipeline diagram and stage-by-stage explanation
  MASTER_AUTHORITY_SYSTEM_PLAN.md
  AGENT_ARCHITECTURE.md
  FUNNEL_ARCHITECTURE.md
  CRM_SYSTEM_BLUEPRINT.md
  SEO_KEYWORD_MAP.md
  VERTICAL_WEDGE_STRATEGY.md
  EXECUTION_ROADMAP.md
  (and more)

/logs
  /sessions               — Session-by-session execution records and decision logs

SYSTEM_CONTEXT.md         — Current phase, active priorities, and KPIs
TASKS.md                  — Active execution tracker
HANDOFF.md                — Tool instructions and next-session context
```

---

## Executive Memo Outputs

Three executive memos have been produced as Phase 2 authority assets:

| File | Vertical | Core Argument |
|---|---|---|
| [`houston-energy-ai-operating-model.md`](content/executive-memos/houston-energy-ai-operating-model.md) | Energy | Energy leaders are mis-sequencing AI — governance must precede deployment |
| [`houston-healthcare-ai-governance.md`](content/executive-memos/houston-healthcare-ai-governance.md) | Healthcare | Healthcare AI must start with governance, not tools |
| [`houston-professional-services-ai-operating-model.md`](content/executive-memos/houston-professional-services-ai-operating-model.md) | Professional Services | Firms treating AI as individual productivity miss the structural opportunity |

Each memo targets C-suite and VP-level executives, runs ~800 words, and ends with a CTA to the Executive AI Office Hours funnel.

---

## Development Philosophy

The system is built on four principles:

**Structured Prompts** — Every content output begins from a template that enforces format, voice, audience, and length. No freeform generation.

**Deterministic AI Execution** — Agents operate within defined cognitive boundaries. Each model has a specific role. Output quality comes from constraint, not creativity.

**Agent Orchestration** — Multiple AI models collaborate with clearly separated responsibilities: ChatGPT for strategy, Claude Code for structured building, Gemini for long-context synthesis, with future NanoClaw and ZeroClaw agents handling recurring execution and orchestration.

**Repeatable Authority Generation** — Every asset type follows a documented template. Any vertical can be activated by feeding the template and strategy context to the appropriate agent.

See [`docs/AGENT_ARCHITECTURE.md`](docs/AGENT_ARCHITECTURE.md) for the full agent responsibility model.

---

## Future Phases

**Phase 3 — Scaled Execution**
Activate content atomization across all three verticals. Increase publication cadence. Begin tracking rank movement and engagement signals against KPI baselines.

**Phase 4 — Authority Automation**
Deploy NanoClaw recurring agents for weekly brief generation, SEO monitoring, and pipeline updates. Activate ZeroClaw orchestration layer to route tasks automatically across agents.

---

## Principle

Houston first. Web amplified. Enterprise focused.
