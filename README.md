# From Prompt to Skill workshops

Short, hands-on lessons that show professionals how to turn a prompt they keep retyping into a reusable **Agent Skill** that Claude picks up on its own.

## Lessons

| Lesson | Length | Learners | Skills | Start here |
|---|---|---|---|---|
| [01 · From Prompt to Skill](lessons/01-prompt-to-skill) | 10 min | Vendor coordinators and course owners | `analyzing-course-feedback`, `comparing-vendor-quotes` | [run sheet](lessons/01-prompt-to-skill/run-sheet.md) |
| [02 · Brief to Backlog](lessons/02-brief-to-backlog) | 10 min | Course TPMs, project leads and coordinators | `clarifying-roadmap-asks`, `breaking-down-projects-for-jira` | [run sheet](lessons/02-brief-to-backlog/run-sheet.md) |

Both lessons follow **I do → We do → You do**: a live demo of the skill, a short practice activity, then learners build their own.

## Repo layout

```
lessons/
  01-prompt-to-skill/
    run-sheet.md      timing, prompts, expected outputs, backup plans
    skills/           one folder per skill, each with a SKILL.md
    dist/             the same skills zipped, ready to upload
    data/             fictional sample data for the demos
    activities/       practice rounds with answer keys
  02-brief-to-backlog/
    (same structure)
templates/            blank skill canvas and SKILL.md for learners
```

## Install a skill (about a minute)

1. Download a zip from a lesson's `dist/` folder. The zip must contain a folder whose name matches the skill's `name`.
2. In Claude, go to **Settings → Capabilities → Skills** and click **Upload skill**. (Menus can move between app versions; look for the Skills section.)
3. Check the skill is in the list and switched **on**. Skills need code execution enabled.
4. Test it: open a **fresh** chat or Cowork task and just do the job. Don't name the skill; it should load on its own.

On Team and Enterprise plans, an admin can add a skill for everyone.

## Anatomy of a skill

```markdown
---
name: analyzing-course-feedback          # lowercase, hyphens, matches the folder name
description: What it does. Use when ...  # the trigger: the only part Claude reads up front
---

## Steps           # the procedure you'd explain to a new hire
## Output format   # the exact shape of the answer, every time
## Quality checks  # your quality bar before it answers
```

**The description is the trigger.** Say what the skill does and when to use it, in the words your users actually type. Claude only reads each skill's name and description until a task matches, then loads the full file.

## Build your own

1. Pick a task you've typed into AI at least three times.
2. Fill in [`templates/skill-canvas.md`](templates/skill-canvas.md).
3. Copy [`templates/SKILL-template.md`](templates/SKILL-template.md) into a new folder, fill it in from your canvas, zip the folder and upload it. Or ask Claude's skill-creator to draft it from your canvas.
4. Test it in a fresh task. When it misfires, fix the description first.

## Naming convention

Skill names use **lowercase, hyphens and a verb in -ing form** that says what the skill does (`analyzing-course-feedback`, `clarifying-roadmap-asks`). The name must match its folder.

## Further reading

- [Introduction to Agent Skills](https://anthropic.skilljar.com/introduction-to-agent-skills) (Anthropic Academy)
- [What are Skills?](https://support.claude.com/en/articles/12512176-what-are-skills) and [Using Skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude) (Claude Help Center)
- [Agent Skills open format](https://agentskills.io)

---

All vendors, courses, projects and learner comments in the `data/` folders are fictional and for training use only.
