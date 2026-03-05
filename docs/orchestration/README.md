# Orchestration Reference

## orchestrator-map.html

This file is a visual architecture map of the AI orchestrator model used in the Jackson Hub
swarm system. It was adapted from Leon Coe's orchestrator system.

### What It Shows

- **Agent roles** — Gemini (Claw), Codex, and Claude, and how each is scoped within the orchestration model
- **Scripts and commands** — the automation layer that connects agents to tasks
- **Orchestration modes** — how requests are routed, planned, executed, and verified across agents

### How to Use

Open `orchestrator-map.html` directly in a browser. No server or build step required.
The file is self-contained and can be viewed locally on any machine.

### Context

This document is informational. It describes the underlying orchestration architecture that
Phase 3 draws from, but it does not define or modify the Phase 2 or Phase 3 architecture of
the Houston AI Authority Engine. The operational specs for those phases live in:

- `docs/phase-2-activation-runbook.md`
- `docs/phase-3-swarm-entry.md`
