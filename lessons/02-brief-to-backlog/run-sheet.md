# Facilitator run sheet: Brief to Backlog (5-minute demo)

**Learners:** project leads and coordinators · **Tool:** Claude Cowork · **Format:** video call; learners watch and respond in chat · **Arc:** I do → We do → You do

**Learning objective:** use a reusable skill to turn a project brief into Jira-ready epics and tickets, with estimates your team can challenge.

## Run of show

| Time | Slide | Segment | You do | Learners do |
|---|---|---|---|---|
| 0:00–0:10 | 1 | Open | Set the scene: you're project leads with a new brief | — |
| 0:10–0:40 | 2 | Hook + objective | "How long did your last brief take to turn into tickets and a timeline?" | Type hours or days |
| 0:40–1:20 | 3 | I do: the skill | Walk `breaking-down-projects-for-jira`: When, Steps, Output, Checks | Listen |
| 1:20–2:35 | 4 | I do: live | Fresh task: drop `data/project-brief-ai-for-managers.md`, type "Here's the brief for our new pilot. Can you plan it?" | Watch the skill load; watch the timeline check |
| 2:35–3:15 | 5 | We do: fix the ticket | Show the one-line-prompt ticket | Name one missing thing each |
| 3:15–3:45 | 6 | We do: reveal | Map their fixes onto the skill's Checks | See their words in the skill |
| 3:45–4:25 | 7 | Estimates + roadmap | Three-point ranges; roadmap as the next skill | Listen |
| 4:25–5:00 | 8 | You do + debrief | Link back to the objective; exit ticket | One check their team would add |

## Setup

- Upload `dist/breaking-down-projects-for-jira.zip`; confirm it's on.
- Put the brief in a folder connected to Cowork; open one fresh task.
- Dry-run once and screenshot the output (the live run takes about 40 seconds).

## What good output looks like

- 3–6 **outcome** epics (e.g. course content ready, LMS listing live, trainer ready, pilot delivered and reviewed).
- No story over 5 working days; each with 2–4 acceptance criteria, an owner role and O / M / P days plus its key assumption.
- Dependencies named: 2 SME review rounds (~1 week each), LMS approval (10 working days), trainer available only from 1 Dec, clients need dates 3 weeks ahead.
- Critical path and timeline check account for the 24 Dec – 1 Jan shutdown and say whether 15 Jan is at risk.
- Top 3 risks with likelihood, impact, response and owner; at least one on the critical path (e.g. SME review slipping, trainer availability from 1 Dec, LMS approval).
- Open questions for anything the brief doesn't say (e.g. which 2 clients, pilot date, owner of the pre-course survey).
- A CSV block for Jira's CSV importer.

## Backup

- **Slow or failed run:** show the dry-run screenshot and narrate the three things above.
- **Skill doesn't load:** "use the breaking-down-projects-for-jira skill", then note that's what a vague description causes.
- **Silent chat on slide 5:** name the gaps yourself, one at a time, and ask "[Name], which would bite you first?"

## What was cut from the 10-minute version, and why

| Cut | Why |
|---|---|
| Live lazy-vs-structured prompt demo | Two live runs cost ~90 s. The bad ticket on slide 5 makes the same contrast in one slide, and learners do the diagnosing. |
| "Which skill will fire?" round | Five minutes supports one practice activity. For PM learners, the expertise lives in the Checks (Definition of Ready), so that's the activity kept. |
| Designing a whole skill together | Replaced by fixing one ticket: same idea (learner rules become the skill), a third of the time. |
| Install walkthrough | Procedural, not part of the objective; it's in the README. |
| Separate estimation segment | Folded into the skill (O / M / P + assumption) and one slide, because the lesson is the guardrail, not the formula. |
| Roadmapping demo | Depends on the epics and estimates being right, and needs priorities and capacity a brief doesn't hold. Shown as the next skill in the chain instead of a rushed third demo. |

## Where the PM content comes from

The skill's vocabulary follows a standard project management certificate syllabus (e.g. [Ziplines' Project Management course](https://upskill.ziplines.com/ziplines/project-management/syllabus)): work breakdown structure with duration estimates, critical path, Jira and agile, and AI-generated risk registers. The Fix-the-ticket activity mirrors that syllabus's exercise of comparing human-created and AI-generated work breakdowns. Status reports, budgets, stakeholder plans and closure reports are natural next skills built the same way.
