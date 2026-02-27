# AGENT ARCHITECTURE
## Houston AI Authority Engine

Purpose: Define clear cognitive boundaries between tools to prevent overlap, chaos, and token waste.

Each agent has:
- A cognitive domain
- A scope of authority
- A type of output
- A guardrail

No agent should duplicate another agent’s role.

---

# SYSTEM OVERVIEW
**Human:** Jackson (Operator / Architect) | Leon (Authority Figure)

**AI Layers:**
- **ChatGPT** (Strategic Architect)
- **Claude Code** (Structured Builder)
- **Codex** (Logical Systems Engineer)
- **OpenClaw (Gemini 3 Flash)** (Long Context Synthesizer)
- **NanoClaw** (Recurring Task Agents – Future)
- **ZeroClaw** (Orchestration Controller – Future)

---

# 1. ChatGPT (Strategic Architect)
**Primary Role:** High-level modeling, system design, strategic decisions.
**Used For:**
- Authority modeling
- Repo structure planning
- Funnel design
- Content framework design
- KPI modeling
- Long-term expansion thinking
**Not Used For:**
- Editing 20 markdown files at once
- Deep code refactors
- Large transcript processing
**Strength:** Clarity + reasoning + architectural thinking

---

# 2. Claude Code (Structured Builder)
**Primary Role:** Implementer inside the repo.
**Used For:**
- Creating and editing markdown files
- Enforcing formatting consistency
- Refactoring templates
- Building structured documents
- Creating structured output from templates
**Not Used For:**
- Strategic rethinking of entire system
- Authority modeling
- SEO conceptual design
**Strength:** Deterministic structure execution.

---

# 3. Codex (Logical Systems Engineer)
**Primary Role:** Refinement + structural logic.
**Used For:**
- Pipeline design
- Automation logic structuring
- File refactors
- Reorganizing architecture cleanly
- Designing deterministic systems
**Not Used For:**
- Writing marketing copy
- Strategic narrative decisions
**Strength:** Clean logic, minimal fluff, high clarity.

---

# 4. OpenClaw (Gemini 3 Flash – Long Context Synthesizer)
**Primary Role:** Mass-context synthesis + recurring intelligence.
**Used For:**
- Weekly Houston AI Brief generation
- Long research synthesis
- Reviewing entire session logs
- Cross-referencing research with outputs
- Pattern recognition across 50+ documents
**Not Used For:**
- Micro file edits
- Small markdown formatting tasks
**Strength:** 2M token window = whole-system thinking.

---

# 5. NanoClaw (Future – Recurring Micro Agents)
**Primary Role:** Scheduled recurring jobs.
**Examples:**
- Weekly Houston AI Brief auto-draft
- Monthly SEO ranking review
- Event recap draft starter
- KPI dashboard updater
*NanoClaw agents are narrow and repeatable.*

---

# 6. ZeroClaw (Future – Orchestrator)
**Primary Role:** Assign tasks to other agents.
**Examples:**
- Detect new event → trigger recap template
- Detect blog publish → trigger LinkedIn derivative
- Detect case study → trigger internal link update
- Detect new week → trigger weekly brief
*ZeroClaw never writes content. It routes tasks.*

---

# DOMAIN SEPARATION PRINCIPLE
- **Strategic Layer** → ChatGPT
- **Implementation Layer** → Claude Code
- **Logic Refinement** → Codex
- **Mass Context** → Gemini (OpenClaw)
- **Recurring Execution** → NanoClaw
- **Orchestration** → ZeroClaw

*Never overlap domains unnecessarily.*

---

# CONTEXT MANAGEMENT RULE
Each session must:
- Log actions in `/logs/sessions`
- Update `TASKS.md`
- Update `SYSTEM_CONTEXT.md` if major change

Before large execution:
- Provide relevant context files to agent
- Avoid dumping entire repo blindly

---

# ESCALATION MODEL
If output feels:
- **Too verbose** → use Codex
- **Too shallow** → use ChatGPT
- **Too fragmented** → use Gemini
- **Too messy structurally** → use Claude Code

---

# PRINCIPLE
We are building distributed cognition. Each model does what it is best at. No duplication. No chaos. Clear boundaries.
