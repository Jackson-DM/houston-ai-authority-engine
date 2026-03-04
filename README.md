# Houston AI Authority Engine

> A strategic AI content and authority-building system designed to position Leon Coe and Amplify Intelligence as the leading AI voice in Houston.

---

## Project Overview

This repository is the operating system behind a regional AI authority strategy.

It is not a content vault. It is the infrastructure that drives a structured, repeatable process for producing executive-level AI insights, distributing them across the right channels, and converting thought leadership into consulting opportunities.

The system combines structured prompt engineering, multi-model AI orchestration, and a defined conversion funnel — generating authority assets consistently, at scale, without drift.

---

## What This System Does

- Generates executive AI memos tailored to Houston's key industries
- Converts research and strategy into LinkedIn authority content
- Funnels senior executives into AI Office Hours discussions
- Tracks engagement signals and maps them to enterprise opportunities

---

## Current Phase

**Phase 2 — Controlled Activation**

The system has produced three executive authority assets — one per target vertical. Each memo targets C-suite and VP-level readers, runs approximately 800 words, and ends with a direct call to action for the Executive AI Office Hours.

| Memo | Vertical |
|---|---|
| [Energy AI Operating Model](content/executive-memos/houston-energy-ai-operating-model.md) | Energy |
| [Healthcare AI Governance](content/executive-memos/houston-healthcare-ai-governance.md) | Healthcare |
| [Professional Services AI Operating Model](content/executive-memos/houston-professional-services-ai-operating-model.md) | Professional Services |

---

## System Architecture

The engine runs a structured, sequential pipeline:

```
Strategy
  → Templates
  → AI Execution Agents (Claude, Codex, Gemini)
  → Executive Memos
  → LinkedIn Distribution
  → AI Office Hours Funnel
  → CRM Signal Tracking
```

Full pipeline documentation: [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md)

---

## Repository Structure

```
/docs        Architecture and strategy documentation
/templates   Repeatable content frameworks
/content     Generated authority assets
/logs        System execution history
```

Documentation index: [`docs/INDEX.md`](docs/INDEX.md)

---

## Development Philosophy

- **Structured prompts over ad-hoc generation** — every output begins from a template that enforces format, voice, and audience
- **Deterministic AI execution** — agents operate within defined cognitive boundaries; output quality comes from constraint
- **Multi-agent orchestration** — each model has a specific role; no duplication, no overlap
- **Authority content as a system** — every asset type is repeatable, every vertical is activatable on demand

---

## Future Phases

**Phase 3 — Scaled Execution**
Content atomization across all three verticals, increased publication cadence, and KPI tracking activated.

**Phase 4 — Authority Automation**
Recurring agent deployment for weekly briefs, SEO monitoring, and pipeline updates — with a full orchestration layer routing tasks across agents automatically.

---

Houston first. Web amplified. Enterprise focused.
