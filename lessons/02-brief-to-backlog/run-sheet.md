# Facilitator run sheet: Brief to Backlog (10-minute demo)

**Learners:** technical program managers (TPMs), project leads and coordinators on course and learning-content teams · **Tool:** Claude Cowork · **Format:** video call; learners watch and respond in chat · **Arc:** I do → We do → You do

**Learning objective:** use two reusable skills to check every stakeholder ask against the roadmap, then turn one clear epic into Jira-ready user stories.

## Scenario (set this up on slide 1)

Learners are the **TPM on a learning-content team**. The team builds courses that help working professionals make the transition into AI. The TPM owns delivery of one programme's roadmap: **AI for People Managers**, a 1-day workshop for managers leading teams that now use AI tools. It's piloted with 2 corporate clients, then scaled to 5 clients, a Mandarin version and a self-paced version. Every ask in the lesson (a responsible-AI module, Mandarin slides, a custom client dashboard, an extra lab) is a realistic request a course TPM gets from sales, clients and trainers.

## Run of show

| Time | Slide | Segment | You do | Learners do |
|---|---|---|---|---|
| 0:00–0:15 | 1 | Open | Set the scene: "You're the TPM on a course team delivering AI for People Managers." Two skills, two parts | — |
| 0:15–0:40 | 2 | Hook + objective | "How many 'can you make tickets for this?' asks did you get last week?" | Type a number |
| 0:40–1:20 | 3 | The ad-hoc ticket trap | A TPM's week: asks become tickets with no epic or roadmap link. Instead: Roadmap → Does it fit? → Epic → User stories → Jira tickets | Recognise the pattern |
| **Part 1** | | **Understand the roadmap** | | |
| 1:20–2:00 | 4 | I do: skill 1 | Walk `clarifying-roadmap-asks`: summarise, flag gaps, four fit calls, questions. "Unclear means ask" | Listen |
| 2:00–3:20 | 5 | I do: live | Fresh task: attach the roadmap and paste the ask in `data/stakeholder-ask-live-demo.md` (responsible-AI module) | Watch it land on "Unclear, ask first" and write the questions |
| 3:20–4:05 | 6 | We do: does it fit? | Three asks against the roadmap strip, using the skill's four calls | Type e.g. A1 B2 C3, plus a question for any 4 |
| 4:05–4:40 | 7 | We do: reveal | "Which roadmap outcome does it serve?" Only A fits now | See the reasoning |
| **Part 2** | | **Break it down** | | |
| 4:40–5:15 | 8 | I do: skill 2 | Walk `breaking-down-projects-for-jira`: roadmap → one epic → stories; tickets only asks that fit now | Listen |
| 5:15–6:40 | 9 | I do: live | Same task: "Ask A fits now: set up the SME review of the lab instructions. Break down E1 into Jira stories, including that." | Watch a different skill load; watch the 4 Dec check |
| 6:40–7:20 | 10 | Estimates in plain words | O = optimistic, M = most likely, P = pessimistic; (O + 4M + P) ÷ 6. Challenge the assumption, not the number | Listen |
| 7:20–7:50 | 11 | Two skills, one habit | Ask → skill 1 → your answers → skill 2. Name the gap, ask the right person, ticket only what fits | Listen |
| 7:50–8:20 | 12 | Debrief | Link back to the objective; ask the exit ticket and let answers come in during the next three slides | One ask they'd answer with a question |
| **You do** | | **Get started** | | |
| 8:20–8:50 | 13 | Get the skills | The GitHub repo: `dist/` has the zips, `skills/` the readable SKILL.md, `data/` the practice roadmap. Click a zip, then the download button | — |
| 8:50–9:25 | 14 | Install | Settings → Capabilities → Skills → Upload skill; upload both zips; check both are on (code execution enabled); admins can add for a team | — |
| 9:25–10:00 | 15 | Use it | Just describe the job: "Does it fit?" loads skill 1, "break it down" loads skill 2; name the skill if it doesn't load. Read two exit tickets; thank you | — |

The full talk track for every slide is in the deck's speaker notes.

## Setup

- Upload `dist/clarifying-roadmap-asks.zip` and `dist/breaking-down-projects-for-jira.zip`; confirm both are on. Remove older versions and the retired skills (`meeting-recap`, `course-feedback-backlog`, `vendor-quote-comparison`).
- Put `data/roadmap-ai-programmes.md` in a folder connected to Cowork; open one fresh task. Keep `data/stakeholder-ask-live-demo.md` open to copy the prompt.
- Dry-run both prompts once, in the same task, and screenshot each output (about 30 and 40 seconds).

## What good output looks like

**Part 1 · `clarifying-roadmap-asks`** (full list in [`data/stakeholder-ask-live-demo.md`](data/stakeholder-ask-live-demo.md)):

- Roadmap in brief, then the gaps, quoting both "course outline and learning outcomes" (in E1 scope) and "new course topics" (not on this roadmap).
- Decision: **Unclear, ask first**, with a confidence level and the one fact that would change it.
- Questions to the client (part of the 1-day or extra time? needed for the 15 Jan pilot?) and to the product manager (what comes out of the day?), plus a draft reply that doesn't promise the work.

**Part 2 · `breaking-down-projects-for-jira`:**

- **Roadmap context first:** E1 serves O1 (pilot delivered to 2 clients by 15 Jan 2027); content due 4 Dec; in scope: outline, slides, facilitator guide, 3 labs, pre-course survey; out of scope: extra labs, translations.
- **Estimate key** in plain words above the stories table.
- User stories only for E1 (including the lab SME review from ask A), each under 5 working days, with 2–4 acceptance criteria, an owner role, O / M / P days and a key assumption.
- Critical path against 4 Dec: two SME review rounds (~1 week each) make it tight; trainer onboarding depends on content being final.
- Top 3 risks, at least one on the critical path (e.g. SME review slipping).
- A CSV block for Jira's CSV importer.

## Activity answer key

See [activities/does-it-fit.md](activities/does-it-fit.md): A → 1 Fits now (E1 scope, critical path) · B → 2 Fits later (E6, Q1; a 4 with a good question for the product manager also counts) · C → 3 Doesn't fit (single-client custom work is not on the roadmap).

## Backup

- **Slow or failed run:** show the dry-run screenshot and narrate the points above.
- **Wrong skill loads:** in Part 1, say "use the clarifying-roadmap-asks skill"; in Part 2, "use the breaking-down-projects-for-jira skill". Then note that's what an overlapping description causes, and why each description says when *not* to use it.
- **Part 1 says Fits now or Doesn't fit instead of Unclear:** ask "What in the roadmap supports that?" It should quote one line; point to the other line and ask what it would change. Good discussion either way.
- **Silent chat on slide 6:** answer A yourself, then ask "[Name], does B fit now? It's urgent."
- **Running long:** cut slide 11 (the chain) and say its one line on the debrief slide. Slides 13–15 can be skimmed in 45 seconds: say "it's all in the repo README" and share the link in chat.
- **Time left at the end:** paste B into the Part 1 task and show the skill's questions for the product manager.

## Design choices

| Choice | Why |
|---|---|
| Two skills, not one | "Does this fit?" and "break this down" are different jobs with different triggers. Keeping them apart keeps each description sharp, and the handoff (ticket only what fits) is itself the lesson. |
| Part 1 before Part 2 | Mirrors how TPMs should work: resolve roadmap uncertainty before creating tickets. |
| A grey-area live ask | The responsible-AI module can be read both ways, so the skill shows its most valuable behaviour: naming the gap and asking, not guessing. |
| Four fit calls, including "Unclear" | Most real asks arrive half-specified; "ask first" gives learners a legitimate option other than yes or no. |
| Part 2 runs in the same task | Shows the chain: the roadmap is already understood, and a different skill loads from different words. |
| Get-started slides after the debrief | Learners leave knowing where the skills live, how to install them and what to type, so the You do actually happens. Exit-ticket answers come in while you show them. |
| O / M / P spelled out on its own slide | New learners rarely know the abbreviation; skill 2 also prints the key in every output. |
| Roadmap *building* not taught | Needs priorities and capacity decisions a 10-minute demo can't hold; the lesson consumes and questions a roadmap instead. |

## Where the PM content comes from

The skills' vocabulary follows a standard project management certificate syllabus (e.g. [Ziplines' Project Management course](https://upskill.ziplines.com/ziplines/project-management/syllabus)): scope management and change control, stakeholder communication, work breakdown structure with duration estimates, critical path, Jira and agile, and AI-generated risk registers.
