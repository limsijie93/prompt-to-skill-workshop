# Lesson 02 · Brief to Backlog (5 minutes)

**Learning objective:** use a reusable skill to turn one roadmap epic into Jira-ready user stories, and keep every ad-hoc ask tied to the roadmap.

**Learners:** technical program managers, project leads and coordinators · **Tool:** Claude Cowork

| Phase | What happens | Material |
|---|---|---|
| Set-up | The ad-hoc ticket trap: requests become tickets with no epic or roadmap link | — |
| I do | The skill works top-down: summarises the roadmap, breaks epic E1 into user stories with three-point estimates, checks the critical path and risks, outputs a Jira CSV | [`breaking-down-projects-for-jira`](skills/breaking-down-projects-for-jira/SKILL.md), [sample roadmap](data/roadmap-ai-programmes.md) |
| We do | [Ticket it, park it, or push back?](activities/ticket-park-or-push-back.md) Learners sort three ad-hoc asks against the roadmap | activity |
| You do | Run your next epic, and every ad-hoc ask, through the skill | [templates](../../templates) |

**Three-point estimates:** O = optimistic (best case), M = most likely, P = pessimistic (realistic worst case). Expected = (O + 4 × M + P) ÷ 6. The skill prints this key in every output.

**Facilitator:** [run-sheet.md](run-sheet.md) · **Upload-ready skill:** [`dist/`](dist)
