---
name: breaking-down-projects-for-jira
description: Turns a project brief into Jira-ready epics and stories with acceptance criteria, three-point estimates, a critical-path timeline check, top risks and a CSV for Jira import. Use when the user shares a project brief, scope or kickoff notes and wants epics, tickets, a backlog, estimates or a delivery timeline.
---

# Breaking down projects for Jira

Turn a project brief into a work breakdown the team can review, estimate and import into Jira.

## Steps

1. Read the brief. Note the goal, deadline, team roles and constraints (holidays, approvals, review turnaround). If any of these are missing, list them under **Open questions**; don't guess.
2. Create **3–6 epics**. Each epic is an outcome ("Course content ready for pilot"), not an activity.
3. Break each epic into **stories**. Split any story that would take more than **5 working days**.
4. Give every story **2–4 acceptance criteria** that someone could check off.
5. Estimate each story with **three points** in working days: optimistic (O), most likely (M), pessimistic (P). Expected = (O + 4M + P) / 6. Write the one assumption the estimate depends on most.
6. Name **dependencies** between stories and external waits (approvals, reviews, vendors).
7. **Critical path and timeline check:** find the longest chain of dependent stories (the critical path), add up its expected days plus known holidays and waits, and compare with the deadline. Say plainly whether the plan fits.
8. **Top risks:** list the 3 risks most likely to move the deadline, each with likelihood and impact (High / Medium / Low), a response and an owner role.

## Output format

```
<Project> – deadline <date> – draft backlog for team review

Epics
| Epic | Outcome | Stories | Expected days |

Stories
| ID | Epic | Story | Owner (role) | Acceptance criteria | O / M / P | Expected | Depends on |

Critical path and timeline check
<IDs> = <n> working days + <waits> → <fits / at risk / does not fit> the <deadline>

Top risks
| Risk | Likelihood | Impact | Response | Owner (role) |

Open questions
- ...

Jira import (CSV)
Issue ID,Issue Type,Summary,Description,Parent ID,Original Estimate (days),Labels
```

## Quality checks

Before replying, confirm:

- Every story has an owner role, acceptance criteria and an O / M / P estimate with its key assumption.
- No story is longer than 5 working days (M); longer ones are split.
- Every dependency and external wait named in the brief appears in **Depends on** or the timeline check.
- Every risk has a response and an owner role, and at least one risk sits on the critical path.
- Nothing is invented: unknown owners, dates or scope are marked **TBD** and listed as open questions.
- The output is labelled a **draft for team review**. Estimates are a starting point for the team, not a commitment.
