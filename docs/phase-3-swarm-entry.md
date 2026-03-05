# Phase 3: Swarm Orchestration Entry

How Jackson Hub orchestration layers onto the existing Phase 2 loop.

---

## 1. Phase 3 Objective

Phase 3 does not replace the Phase 2 loop. It automates the parts of that loop that currently
require manual effort: drafting post queues from memos, packaging content assets, routing
review tasks, and summarizing weekly signals. The goal is to reduce the weekly execution burden
on Jackson and Leon without changing the standards, tone, or decision authority that Phase 2
established.

The mechanism is swarm orchestration through Jackson Hub — a coordinated set of agent roles
(Gemini, Codex, Claude) working from the same inputs the Phase 2 loop already uses. Phase 3
is active when the swarm is producing usable outputs weekly with minimal manual intervention.
Authority over what gets published and what gets logged stays human.

---

## 2. What Stays the Same

No existing architecture is redesigned. The following loop, assets, and repo paths carry
forward unchanged:

- The 3-post standard week cadence and 5-post optional variant
- Office Hours hook usage rules (30–40% of posts, same variant logic)
- Manual signal review and CRM logging as the authoritative record
- Weekly retrospective and decision criteria for doubling down vs. new memo
- All existing assets:
  - `content/executive-memos/` — source of authority for all content
  - `content/linkedin-posts/` — published and draft post assets
  - `templates/linkedin-post-template.md` — formatting standard for new posts
  - `templates/office-hours-hook.md` — hook variants and usage rules
  - `templates/crm-signal-tracker.md` — signal logging template
  - `docs/phase-2-activation-runbook.md` — weekly execution reference

The swarm produces assets and plans. Humans publish and log.

---

## 3. Jackson Hub Orchestration Model

### Agent Role Split

| Agent | Role |
|---|---|
| **Gemini (Claw)** | Orchestration, large-context planning, synthesis across memos/posts/signals |
| **Codex** | Engineering tasks, automation scripts, repo file operations |
| **Claude** | Structured formatting, content packaging, markdown asset creation, LinkedIn copy |

No agent operates outside its lane without explicit instruction. Gemini plans and routes.
Codex builds. Claude formats and drafts.

### Execution Loop

```
Request
   |
   v
Plan (Gemini: review inputs, define task list, assign agents)
   |
   v
Execute (Codex: automation / Claude: content packaging)
   |
   v
Verify (human or Gemini: quality gate check)
   |
   v
Log (commit to repo / update CRM tracker)
```

Each cycle starts with a request — either a standing weekly trigger or a specific task from
Jackson or Leon. Gemini produces a plan. Execution runs in parallel where tasks are
independent. Nothing is committed without passing the quality gate.

---

## 4. Phase 3 Inputs / Outputs

### Inputs

- Executive memos (`content/executive-memos/`) — primary source material
- Existing templates (`templates/`) — formatting and tone constraints
- Phase 2 runbook (`docs/phase-2-activation-runbook.md`) — cadence and hook rules
- Weekly topic focus (optional) — a single theme or memo to prioritize for the week
- Prior week signal summary — to inform whether to double down or open new territory

### Outputs

| Output | Description |
|---|---|
| Post queue | 3–5 draft posts ready to publish, formatted to template |
| Publishing plan | Day-by-day schedule for the week with hook assignments noted |
| Signal summary | Brief synthesis of the prior week's CRM entries |
| Backlog tasks | Any automation, repo, or content tasks flagged for Codex or Claude |

Outputs are committed to the repo or documented in a weekly planning note. Nothing is
auto-published.

---

## 5. Swarm Execution: Weekly Cycle

### Monday Morning — Orchestration Planning

1. Gemini reviews the prior week's signal summary and the current memo library.
2. Gemini produces a weekly plan: topic focus, post count, hook assignment, any backlog tasks.
3. Plan is reviewed by Jackson or Leon before execution begins. (~10 minutes)

### Tuesday–Wednesday — Content Packaging

1. Claude drafts the week's post queue from the assigned memo(s), using
   `templates/linkedin-post-template.md` as the formatting constraint.
2. Hook variants are assigned per post following rules in `templates/office-hours-hook.md`.
3. Drafts are staged in `content/linkedin-posts/` as files, not published.
4. Jackson or Leon reviews drafts and approves or requests revisions.

### Thursday — Automation and Backlog

1. Codex handles any flagged automation tasks: file operations, template updates,
   repo structure changes.
2. Gemini synthesizes any mid-week signals if CRM entries have been logged.

### Friday — Review and Signal Summary

1. Gemini produces a signal summary from the week's CRM entries.
2. Weekly retrospective checklist is run (per Phase 2 runbook, Section 6).
3. Backlog for the following week is drafted and queued.

---

## 6. Task Types and Routing Rules

### Routing

| Task Type | Assigned To |
|---|---|
| Code, scripts, automation, file operations | Codex |
| Markdown asset creation, content formatting | Claude |
| Synthesis across memos, posts, or signals | Gemini |
| LinkedIn copy drafting or tone refinement | Claude (with template constraints) |
| Weekly planning, task routing, decision support | Gemini |

When a task spans two lanes (e.g., synthesize a memo and draft a post from it), Gemini
handles synthesis first and hands the output to Claude for formatting. No agent skips
the handoff.

### Quality Gates

Before any asset is committed to the repo, verify the following:

- [ ] Post copy matches the tone and structure in `templates/linkedin-post-template.md`
- [ ] Hook variant (if used) is drawn verbatim from `templates/office-hours-hook.md`
- [ ] No hype language, urgency framing, or engagement-bait phrasing is present
- [ ] Post is traceable to a specific memo in `content/executive-memos/`
- [ ] File is placed in the correct repo path
- [ ] No other files were modified as a side effect

---

## 7. Definition of Done for Phase 3 Entry

Phase 3 is considered active when the following are all true after one complete weekly cycle:

- [ ] Gemini produced a weekly plan on Monday that was reviewed and approved
- [ ] Claude produced a full post queue (minimum 3 posts) from existing memo assets
- [ ] All posts were formatted to template and committed to `content/linkedin-posts/`
- [ ] Publishing plan was documented with hook assignments noted
- [ ] Quality gate checklist was completed before any commit
- [ ] At least one Codex task was executed and logged (even if trivial)
- [ ] Friday signal summary was produced from CRM entries
- [ ] Weekly retrospective was completed per the Phase 2 runbook

Phase 3 does not require a perfect week. It requires a complete one — all steps executed,
all outputs produced, no manual shortcuts taken that bypass the swarm loop.
