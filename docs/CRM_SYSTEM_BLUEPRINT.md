# CRM SYSTEM BLUEPRINT
## Houston AI Authority Engine

Purpose: Track executive movement through funnel stages with clarity and precision. This CRM must:
- Be simple
- Be enforceable
- Be updated weekly
- Tie directly to funnel architecture

---

# RECOMMENDED TOOL OPTIONS
**Phase 1 (Lightweight):**
- Airtable (recommended)
- Notion database
- Google Sheets

**Phase 2 (If pipeline grows):**
- HubSpot
- Pipedrive

*Do not overcomplicate early.*

---

# CORE DATABASE STRUCTURE
## Table: EXECUTIVE PIPELINE
Each row = One executive

---

# REQUIRED FIELDS

## Identity
- Full Name
- Company
- Title
- Industry
- LinkedIn URL
- Email

---

## Funnel Tracking
- **Funnel Stage (Dropdown)**
  - Stage 0: Visibility
  - Stage 1: Identified Executive
  - Stage 2: Follow-Up Sent
  - Stage 3: Office Hours Attendee
  - Stage 4: Sprint Conversation
  - Stage 5: Paid Sprint
  - Stage 6: Retainer
- **Source**
  - Houston AI Club
  - LinkedIn
  - Referral
  - Other
- **Date Entered**
- **Last Interaction Date**
- **Next Action Date**
- **Owner** (Jackson / Leon)

---

## Revenue Forecasting
- Estimated Deal Size
- Probability (%)
- Weighted Value (auto formula = Deal Size × Probability)

---

## Status Tracking
- Sprint Proposal Sent? (Yes/No)
- Retainer Signed? (Yes/No)
- Lost? (Yes/No)
- Loss Reason (if applicable)

---

# DASHBOARD VIEWS
Create filtered views:
1. **Active Pipeline** - Stages 2–5 only
2. **Office Hours Candidates** - Stage 2 only
3. **Sprint Opportunities** - Stage 4 only
4. **Retainers** - Stage 6 only
5. **Stalled** (>14 days no interaction)

---

# WEEKLY RITUAL (MANDATORY)
Every Friday:
1. Review pipeline
2. Update probabilities
3. Move stage positions
4. Schedule next actions
5. Log summary in `/logs/sessions`

---

# HEALTH METRICS
Healthy pipeline indicators:
- 5–10 executives in Stage 2
- 3–5 in Office Hours monthly
- 1–2 active Sprint conversations
- ≥1 Retainer per quarter (minimum early target)

---

# AUTOMATION (PHASE 2)
When ready:
- Auto-add event RSVP data to CRM
- Auto-tag LinkedIn engaged executives
- Reminder triggers for follow-up
- Pipeline summary auto-generated weekly via Gemini

*Not required yet.*
