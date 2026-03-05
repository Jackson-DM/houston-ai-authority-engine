# Start Here

## What This Repo Is

- An operating system for building executive authority in the Houston market — not a content vault.
- It produces a consistent LinkedIn presence, tracks inbound signals, and routes execution across human and AI agents.
- Phase 2 runs the weekly content loop manually. Phase 3 layers swarm orchestration on top.
- Everything needed to run the engine is in this repo.

---

## Current Status

| Phase | Status |
|---|---|
| Phase 1 | Complete — foundational memos and post assets created |
| Phase 2 | Active — assets, templates, runbook, and run commands in place |
| Phase 3 | Documented — swarm entry model and commands ready; not fully automated yet |

---

## Run the Engine

Start here every week:

| Command | When to Use |
|---|---|
| [`commands/run-phase-2-week.md`](../commands/run-phase-2-week.md) | Running the week manually — standard 3-post cadence with signal review. |
| [`commands/run-phase-3-swarm-week.md`](../commands/run-phase-3-swarm-week.md) | Running the week with Jackson Hub swarm assistance — Gemini plans, Claude packages, Codex executes. |

---

## Where Things Live

| Path | Contents |
|---|---|
| `content/executive-memos/` | Source-of-authority memos by industry and topic |
| `content/linkedin-posts/` | Draft and published post assets |
| `templates/` | Post template, Office Hours hook variants, CRM signal tracker |
| `docs/` | Runbooks, phase entry docs, and this file |
| `docs/orchestration/` | Visual architecture map of the Jackson Hub orchestration model |
| `logs/weekly/` | Weekly execution logs and signal summaries (one file per week) |

---

## Operating Rules

- Maintain calm executive tone in all content — no hype, no urgency, no engagement bait.
- Apply the Office Hours hook to 30–40% of posts (approximately 1 per standard week).
- Log all qualifying inbound signals in the CRM tracker within 24 hours.
- Nothing gets published or committed without passing the quality gate in the relevant run command.
