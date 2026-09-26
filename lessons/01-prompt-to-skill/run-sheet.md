# Facilitator run sheet (10-minute demo)

**Learners:** vendor coordinators and course owners · **Tool:** Claude Cowork · **Format:** video call; the group watches and responds in chat · **Arc:** I do → We do → You do

## Run of show

| Time | Segment | You do | Learners do |
|---|---|---|---|
| 0:00–0:45 | Hook | "How many times this week did you type the same instructions into an AI?" | Type a number in chat |
| 0:45–1:30 | Relevance + objective | The 3-times rule; read the objective | Listen |
| 1:30–3:00 | I do: prompting | Task A: lazy prompt, then structured prompt, on `feedback-run-12sep.csv` | Name one difference in chat |
| 3:00–3:30 | The problem | A great prompt lives in one chat: retyped, drifts, not shared, checks skipped | React |
| 3:30–4:15 | Skill anatomy | Walk `analyzing-course-feedback`: When, Steps, Output, Checks | Listen |
| 4:15–5:00 | Install | Show both skills in Settings → Capabilities → Skills | Watch |
| 5:00–6:15 | I do: live skill | Task B (fresh): drop `feedback-run-19sep.csv`, no instructions; the skill fires | Watch for the skill to load |
| 6:15–7:30 | We do #1 | [Which skill will fire?](activities/round-1-which-skill-will-fire.md) | Type e.g. A1 B2 C1 D0 |
| 7:30–9:10 | We do #2 | [Design comparing-vendor-quotes](activities/round-2-design-comparing-vendor-quotes.md) (~50 s), then Task C (fresh) with the quotes (~50 s) | Supply each box |
| 9:10–10:00 | You do + debrief | Link the rounds to the objective; exit ticket | One task they'll turn into a skill |

If you run long: cut the install toggle first, then take only two canvas boxes from the group.

## Setup (day before)

- Upload both zips from `dist/`; confirm they're on and code execution is enabled. Switch off any older versions of these skills.
- Put the three files from `data/` in a folder connected to Cowork.
- Open three Cowork tasks: A (prompting), B (fresh), C (fresh).
- Dry-run B and C; screenshot the outputs as a fallback.
- Share only the Cowork window; bump font size; mute notifications.

## Copy-paste prompts

**Task A, lazy:**

> Summarize this feedback. [attach feedback-run-12sep.csv]

**Task A, structured:**

> You are the product manager for this course. Attached are 14 learner responses from the 12 Sep run of GenAI for Workplace Productivity. Turn the comments into an improvement backlog. Output a table with: fix, type (content / trainer / logistics), number of mentions, one short evidence quote, priority (High / Medium / Low). Only include themes with 2 or more comments; put single mentions in a watch list. Use counts from the data only, and don't include learner names.

**Task B, fresh:**

> Here's the feedback from last Friday's run. [attach feedback-run-19sep.csv]

**Task C, fresh:**

> Which of these is better value? [attach vendor-quotes-elearning.md]

## What good output looks like

- **Task A (12 Sep):** afternoon hands-on rushed (4), industry-specific examples wanted (3), outdated slide screenshots (2), laptop / wifi login (2); late lunch on the watch list; trainer praised (4).
- **Task B (19 Sep):** exercise 2 instructions unclear (3), prompt template handout (3), too much theory (2), ran over time (2), room too cold (2); group activity under Keep doing (4); parking on the watch list (1).
- **Task C:** see the answer key in [round 2](activities/round-2-design-comparing-vendor-quotes.md).

## Backup plans

- **Wrong skill fires, or none:** "That's the lesson from Round 1." Name the skill in the prompt, then show the description and ask what to change.
- **Cowork is slow or down:** use the dry-run screenshots.
- **Group is silent in Round 2:** answer the four boxes yourself, thinking aloud as a coordinator.
