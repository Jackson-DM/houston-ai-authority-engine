# Phase 2 Activation Runbook

Operational guide for consistent weekly execution.
Intended for: Jackson or Leon.

---

## 1. Objective

Phase 2 activation is the process of converting the Authority Engine's written assets into a
steady, visible presence on LinkedIn — publishing executive-level content at a consistent
cadence, monitoring inbound signals from that content, logging qualified interest in the CRM
tracker, and converting meaningful signals into direct conversations. The goal is not volume
or virality. It is to build a recognizable, credible voice in the Houston market over time,
such that the right decision-makers know who to call when an AI initiative requires outside
perspective or execution support.

---

## 2. Required Inputs

All assets referenced in this runbook live in the repository at the paths below.

| Asset | Path |
|---|---|
| Executive memos | `content/executive-memos/` |
| LinkedIn posts | `content/linkedin-posts/` |
| Office Hours hook template | `templates/office-hours-hook.md` |
| CRM signal tracker template | `templates/crm-signal-tracker.md` |

Before beginning a weekly cycle, confirm that the post queue contains at least three
ready-to-publish posts. If it does not, draft new posts before executing the cadence.

---

## 3. Weekly Cadence

### Standard Week — 3 Posts

| Day | Activity |
|---|---|
| Monday | Publish Post 1. Log any weekend signals in CRM. |
| Tuesday | Engagement review: respond to comments on Post 1. |
| Wednesday | Publish Post 2. |
| Thursday | Engagement review: respond to comments on Posts 1–2. Signal review. |
| Friday | Publish Post 3. Weekly retrospective (see Section 6). |

### Extended Week — 5 Posts (optional)

Add a post on Tuesday and Thursday, shifting engagement review to morning and publishing
to afternoon on those days. Do not exceed 5 posts per week. Quality over frequency.

### Hook Usage Rules

Apply the Office Hours hook (from `templates/office-hours-hook.md`) to approximately 30–40%
of posts — roughly one post per standard week, two per extended week.

**Appropriate post types for the hook:**
- Posts framing a specific organizational challenge
- Posts presenting a framework or decision model
- Posts drawing a contrast between two approaches

**Post types that should not carry the hook:**
- Observational or data-only posts
- Short-form takes or single-insight posts
- Any post that already ends with a direct question to the audience

Use only one variant per post. Do not stack variants or repeat the same variant in
consecutive posts.

---

## 4. Daily Process (10 Minutes)

Each business day, run through the following in order.

**Signal Review**

- [ ] Open LinkedIn notifications and review activity on all posts published in the last 7 days.
- [ ] Check DMs for any replies to published posts or outreach.
- [ ] Note any profile visits if visible.

**What counts as a signal:**
Any interaction that suggests a real person with organizational context engaged intentionally.
This includes: substantive comments, shares with context, direct messages, connection requests
from relevant roles, and referrals. A like alone is a weak signal (score 1–2); log it only
if the person's role or company is relevant.

**Logging**

- [ ] For each qualifying signal, open a new entry in the CRM tracker
      (`templates/crm-signal-tracker.md`) or your working copy of it.
- [ ] Fill in: date, contact, company, role, source post, signal type, signal strength (1–5),
      and notes. Leave next action and follow-up date blank if not yet determined.
- [ ] Set status to `New` or `Reviewed` depending on whether action is needed.

Keep this step under 10 minutes. If a signal requires a thoughtful response, flag it and
address it during the engagement review block later in the day.

---

## 5. Office Hours Execution

### Mentioning Office Hours in Posts

Append the selected hook variant at the end of the post body, preceded by a blank line.
Do not modify the variant text. Do not combine it with a call-to-action or question.
The hook stands alone.

### Handling Inbound Interest

When someone replies to a post, comments with a substantive question, or DMs following
a post that carried the hook, respond using the following outline:

1. **Acknowledge specifically.** Reference what they said or the context they shared.
   One sentence. Do not use generic openers.
2. **Offer the conversation directly.** Something like: "Happy to set aside 30 minutes
   to talk through how this applies to your situation." No pitch, no agenda framing.
3. **Make it easy to proceed.** Provide a direct way to book or reply — a Calendly link,
   an email address, or a simple "reply here and we can find a time." One option only.

Log all inbound interest in the CRM tracker with signal strength 4 or 5 before responding.

### Cadence Recommendation

Hold Office Hours as needed based on inbound demand — biweekly is a reasonable default
when content is publishing consistently. Do not commit to a fixed public schedule.
The goal is availability on request, not a recurring broadcast.

---

## 6. Measurement and Review

### Metrics to Track Without Tools

Track these manually at the end of each week in a simple note or spreadsheet.

| Metric | What to Count |
|---|---|
| Posts published | Number of posts that went live |
| Executive-level comments | Comments from VP, Director, C-Suite, or Owner roles |
| Inbound DMs | Unsolicited direct messages following a post |
| Office Hours requests | Explicit requests for a call or conversation |
| Calls booked | Conversations that made it onto the calendar |

No analytics platform required. These numbers are observable directly in LinkedIn and the
CRM tracker.

### Weekly Retrospective Checklist

Run this on Friday after publishing the final post of the week.

- [ ] Were 3 posts published? If not, what prevented it?
- [ ] Were all signals logged in the CRM tracker within 24 hours?
- [ ] Did any inbound interest go unaddressed for more than 48 hours?
- [ ] Was the Office Hours hook used on approximately one post this week?
- [ ] Are there any open CRM entries with status `New` that need a next action set?
- [ ] Does the post queue have at least 3 posts ready for next week?

### Decision Criteria

Adjust the cadence or content approach if any of the following conditions persist for
three or more consecutive weeks:

- Zero executive-level signals across all posts
- Consistent drop in comment quality (only likes, no substantive engagement)
- Office Hours hook is generating no inbound interest at 30–40% usage rate
- Post queue is consistently empty at the start of the week (process problem, not content)

When a decision threshold is hit, treat it as a prompt to review the memo library and
post asset quality before changing cadence. The problem is more often content relevance
than posting frequency.

### Double Down vs. New Memo Needed

When a topic generates repeated inbound questions, comments referencing the same challenge,
or multiple DMs with similar context, apply the following decision rule:

**Double down** if:
- The same question or theme surfaces from two or more independent contacts within a 2-week window
- Comments indicate the audience recognizes the problem but lacks a framework for it
- The existing post on the topic performed above your average signal rate

Doubling down means publishing a follow-on post that goes one level deeper — a second frame,
a specific application, or a contrast case. It does not mean repeating the original post.

**New memo needed** if:
- The inbound questions reference a domain, industry, or challenge not covered in `docs/memos/`
- Signals indicate the audience is operating in a context where the existing framing does not land
- A contact asks a question that would require more than a post to address properly

In that case, draft a new executive memo before producing new post assets for that topic.
The memo is the source of authority; posts are derived from it.

---

## 7. Completion Criteria

Phase 2 is operationally complete — and the engine is running — when all of the following
are true for four consecutive weeks:

- [ ] Three or more posts published per week, drawn from the existing memo library
- [ ] All inbound signals logged in the CRM tracker within 24 hours of receipt
- [ ] Office Hours hook in active use on 30–40% of posts
- [ ] At least one inbound DM or conversation request per two-week period
- [ ] Weekly retrospective completed each Friday
- [ ] Post queue replenished before the start of each new week

Phase 2 does not complete on a date. It completes when the loop is self-sustaining:
content produces signals, signals are tracked, tracked signals convert to conversations,
and the process repeats without requiring a standing effort to restart it.
