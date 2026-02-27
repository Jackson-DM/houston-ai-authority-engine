# ENTITY & SCHEMA CHECKLIST
## Houston AI Authority Engine

Purpose: Ensure Google clearly understands:
- Leon Coe (Person)
- Amplify Intelligence (Organization)
- Houston AI Club (Organization)
- Relationship graph between them

Goal: Eliminate entity confusion and strengthen Knowledge Graph signals.

---

# CORE ENTITY MAP
Leon Coe → Founder of Amplify Intelligence
Leon Coe → Founder of Houston AI Club
Leon Coe → Creator of AI First Work
Leon Coe → Creator of Amplified Exec
Amplify Intelligence → Based in Houston
Houston AI Club → Houston recurring event series

All entities must interlink consistently.

---

# REQUIRED STRUCTURED DATA

## 1. Organization Schema (Amplify Intelligence)
Include:
- Name
- Logo
- URL
- SameAs (LinkedIn, YouTube, etc.)
- Service area: Houston, Texas
- Description clearly including "AI consulting in Houston"

---

## 2. Person Schema (Leon Coe)
Include:
- Name
- Job title
- Founder of Amplify Intelligence
- Founder of Houston AI Club
- SameAs links
- Houston location reference
- Profile image

---

## 3. ProfilePage Schema
Used on:
- leoncoe.com bio page
- Key profile pages
Ensure canonical author reference.

---

## 4. Event Schema
Apply to:
- Houston AI Club event pages
- Monthly meetup pages
- Lightning Lesson pages
Include:
- Event name
- Location
- Date
- Organizer
- Performer (speaker)

---

## 5. Article Schema
For:
- Blog posts
- Executive memos
- Case studies
Must include:
- Author reference (Leon canonical profile)
- DatePublished
- DateModified
- Organization publisher

---

# ENTITY COHERENCE RULES
- Always refer to "Amplify Intelligence (Houston AI Consulting)"
- Always reference Houston clearly on commercial pages
- Keep naming consistent across domains
- Use identical logos where appropriate
- Cross-link domains strategically

---

# MONITORING
Quarterly:
- Search Leon Coe (incognito)
- Search Amplify Intelligence Houston
- Search Houston AI Club
- Check for Knowledge Panel consistency
- Check for naming collisions
Log findings in /logs/decisions
