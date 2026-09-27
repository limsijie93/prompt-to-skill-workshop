# Facilitator run sheet: Brief to Backlog (5-minute demo)

**Learners:** technical program managers, project leads and coordinators · **Tool:** Claude Cowork · **Format:** video call; learners watch and respond in chat · **Arc:** I do → We do → You do

**Learning objective:** use a reusable skill to turn one roadmap epic into Jira-ready user stories, and keep every ad-hoc ask tied to the roadmap.

## Run of show

| Time | Slide | Segment | You do | Learners do |
|---|---|---|---|---|
| 0:00–0:10 | 1 | Open | Set the scene | — |
| 0:10–0:35 | 2 | Hook + objective | "How many 'can you make tickets for this?' asks did you get last week?" | Type a number |
| 0:35–1:05 | 3 | The ad-hoc ticket trap | A TPM's week: asks become tickets with no epic or roadmap link. Instead: Roadmap → Epic → User stories → Jira tickets | Recognise the pattern |
| 1:05–1:40 | 4 | I do: the skill | Walk `breaking-down-projects-for-jira`: When, Steps, Output, Checks | Listen |
| 1:40–2:50 | 5 | I do: live | Fresh task: attach `data/roadmap-ai-programmes.md`, type "Here's our programme roadmap. Break down E1 into Jira stories." | Watch the skill load; watch the 4 Dec check |
| 2:50–3:25 | 6 | We do: ticket, park or push back? | Three ad-hoc asks against the roadmap strip | Type e.g. A1 B2 C3 |
| 3:25–3:55 | 7 | We do: reveal | "Which roadmap outcome does it serve?" | See the reasoning |
| 3:55–4:30 | 8 | Estimates in plain words | O = optimistic, M = most likely, P = pessimistic; (O + 4M + P) ÷ 6 | Listen |
| 4:30–5:00 | 9 | You do + debrief | Link back to the objective; exit ticket | One ask they'd push back on |

## Setup

- Upload `dist/breaking-down-projects-for-jira.zip`; confirm it's on. Remove the older version if you saved one.
- Put `data/roadmap-ai-programmes.md` in a folder connected to Cowork; open one fresh task.
- Dry-run once and screenshot the output (the live run takes about 40 seconds).

## What good output looks like

- **Roadmap context first:** E1 serves O1 (pilot delivered to 2 clients by 15 Jan 2027); content due 4 Dec; in scope: outline, slides, facilitator guide, 3 labs, pre-course survey; out of scope: extra labs, translations.
- **Estimate key** in plain words above the stories table.
- User stories only for E1, each under 5 working days, with 2–4 acceptance criteria, an owner role, O / M / P days and a key assumption.
- Critical path against 4 Dec: two SME review rounds (~1 week each) make it tight; trainer onboarding depends on content being final.
- Top 3 risks, at least one on the critical path (e.g. SME review slipping).
- A CSV block for Jira's CSV importer.

## Activity answer key

See [activities/ticket-park-or-push-back.md](activities/ticket-park-or-push-back.md): A → Ticket it (E1 scope, critical path) · B → Park it (E6, Q1) · C → Push back (not on the roadmap).

## Backup

- **Slow or failed run:** show the dry-run screenshot and narrate the four things above.
- **Skill doesn't load:** "use the breaking-down-projects-for-jira skill", then note that's what a vague description causes.
- **Silent chat on slide 6:** answer A yourself, then ask "[Name], would you ticket B? It's urgent."
- **Time left after the reveal:** paste the three asks into the same Cowork task ("Sort these requests against the roadmap") and show the skill's Ticket / Park / Push back table.

## Design choices

| Choice | Why |
|---|---|
| Start from the roadmap, not a brief | Mirrors how TPMs should work: an epic only makes sense against the outcome it serves. |
| Break down one epic, not the whole roadmap | Keeps the live run short and models focus: tickets exist only for the epic in play. |
| We-do = sort ad-hoc asks | Practises the judgment the TPM slide sets up; the skill then does the same sorting (step 9). |
| O / M / P spelled out on its own slide | New learners rarely know the abbreviation; the skill also prints the key in every output. |
| Roadmap *building* not taught | Needs priorities and capacity decisions a 5-minute demo can't hold; the lesson consumes a roadmap instead. |

## Where the PM content comes from

The skill's vocabulary follows a standard project management certificate syllabus (e.g. [Ziplines' Project Management course](https://upskill.ziplines.com/ziplines/project-management/syllabus)): work breakdown structure with duration estimates, critical path, Jira and agile, and AI-generated risk registers.
