# Lesson 02 · Brief to Backlog (10 minutes)

**Learning objective:** use two reusable skills to check every stakeholder ask against the roadmap, then turn one clear epic into Jira-ready user stories.

**Learners:** technical program managers (TPMs), project leads and coordinators on course and learning-content teams · **Tool:** Claude Cowork

**Scenario:** learners play the TPM on a team that builds courses to help professionals transition into AI. The sample roadmap is for one such programme, **AI for People Managers**. Part 1 questions the asks that land on the roadmap; Part 2 breaks its first epic (the pilot course content) into Jira tickets.

| Part | Phase | What happens | Material |
|---|---|---|---|
| Set-up | — | The ad-hoc ticket trap: requests become tickets with no epic or roadmap link | — |
| 1 · Understand the roadmap | I do | Skill 1 reads the roadmap, flags what it leaves unclear, decides whether a client's ask fits, and drafts the questions to send | [`clarifying-roadmap-asks`](skills/clarifying-roadmap-asks/SKILL.md), [sample roadmap](data/roadmap-ai-programmes.md), [live-demo ask](data/stakeholder-ask-live-demo.md) |
| 1 · Understand the roadmap | We do | [Does it fit?](activities/does-it-fit.md) Learners sort three asks: fits now, fits later, doesn't fit, or unclear | activity |
| 2 · Break it down | I do | Skill 2 breaks epic E1 into user stories with three-point estimates, checks the critical path and risks, and outputs a Jira CSV | [`breaking-down-projects-for-jira`](skills/breaking-down-projects-for-jira/SKILL.md) |
| Wrap | You do | Get the skills from this repo, install them in Claude, then run the next stakeholder ask through skill 1 and the epic through skill 2 | [`dist/`](dist), [install steps](../../README.md#install-a-skill-about-a-minute) |

**Why two skills:** handling roadmap uncertainty and breaking down work are different jobs, triggered by different questions ("does this fit?" vs "break this down"). Separate skills keep each description sharp, so Claude loads the right one, and the Jira skill only tickets asks that already fit.

**Three-point estimates:** O = optimistic (best case), M = most likely, P = pessimistic (realistic worst case). Expected = (O + 4 × M + P) ÷ 6. Skill 2 prints this key in every output.

**Facilitator:** [run-sheet.md](run-sheet.md) · **Upload-ready skills:** [`dist/`](dist)
