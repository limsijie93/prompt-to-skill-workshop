---
name: breaking-down-projects-for-jira
description: Works from a roadmap down to Jira-ready work. Summarises the roadmap, breaks one chosen epic into user stories with acceptance criteria and three-point estimates (optimistic, most likely, pessimistic), checks the critical path against the deadline, flags top risks, sorts ad-hoc requests against the roadmap, and outputs a CSV for Jira import. Use when the user shares a roadmap, project brief or epic and wants user stories, Jira tickets, estimates, a timeline, or help deciding whether a request belongs in the backlog.
---

# Breaking down projects for Jira

Work from the top down: **roadmap outcome → one epic → user stories → Jira tickets.** Never start from a one-off request.

## Steps

1. **Read the roadmap.** Summarise it in 2–3 lines: the overall goal, each phase's outcome and deadline, and which epics serve which outcome. Note team roles and constraints (holidays, approvals, review turnaround). If there is only a project brief, treat it as a one-outcome roadmap. If the goal, deadline, roles or constraints are missing, list them under **Open questions**; don't guess.
2. **Pick one epic.** Use the epic the user names. If they don't name one, propose the next epic on the critical path and say why. Restate the outcome it serves, its deadline, and what is in and out of scope. Each epic is an outcome ("Course content ready for pilot"), not an activity.
3. **Write user stories for that epic only**, in the form "As a *role*, I want *capability* so that *benefit*." Split any story that would take more than **5 working days**.
4. Give every story **2–4 acceptance criteria** that someone could check off.
5. **Estimate each story with three numbers** in working days, as explained in the Estimate key below, plus the one assumption the estimate depends on most.
6. Name **dependencies** between stories and external waits (approvals, reviews, vendors, people's availability).
7. **Critical path and timeline check:** find the longest chain of dependent stories (the critical path), add up its expected days plus holidays and waits, and compare it with the epic's deadline. Say plainly whether it fits, is at risk, or does not fit.
8. **Top risks:** the 3 risks most likely to move the deadline, each with likelihood and impact (High / Medium / Low), a response and an owner role.
9. **Sort incoming requests.** If the user shares ad-hoc requests, or the input mentions extra asks, decide for each one:
   - **Ticket it:** it serves the chosen epic and fits its scope. Add it as a story.
   - **Park it:** it serves a later epic or outcome on the roadmap. Name that epic; don't ticket it now.
   - **Push back:** it is not on the roadmap, or it changes the epic's scope. Don't ticket it; raise it at the next roadmap review with the trade-off.

## Estimate key

Write this key in plain words above the stories table, every time, because readers may not know the abbreviations.

- **O = Optimistic:** the best case, if nothing goes wrong.
- **M = Most likely:** what usually happens.
- **P = Pessimistic:** the realistic worst case, if the known risks happen.
- **Expected = (O + 4 × M + P) ÷ 6.** The most likely number counts four times, so the expected value stays close to the realistic case but moves with the risk.
- Example: 3 / 5 / 8 days → (3 + 20 + 8) ÷ 6 ≈ **5.2 days**.

## Output format

```
<Roadmap> – epic <ID and name> – draft for team review

Roadmap context
- Goal: ...
- This epic serves: <outcome>, due <date>
- In scope: ...  Out of scope: ...

Estimate key: O = optimistic (best case) · M = most likely · P = pessimistic (worst case) · Expected = (O + 4M + P) ÷ 6

User stories
| ID | User story | Owner (role) | Acceptance criteria | O / M / P days | Expected | Key assumption | Depends on |

Critical path and timeline check
<IDs> = <n> working days + <waits> → <fits / at risk / does not fit> the <deadline>

Top risks
| Risk | Likelihood | Impact | Response | Owner (role) |

Incoming requests (only if any were shared)
| Request | Decision (Ticket it / Park it / Push back) | Why | Roadmap link |

Open questions
- ...

Jira import (CSV)
Issue ID,Issue Type,Summary,Description,Parent,Original Estimate (days),Labels
```

## Quality checks

Before replying, confirm:

- The chosen epic is linked to a named roadmap outcome, and every story belongs to that epic.
- No story was created for work outside the chosen epic; other asks appear under Incoming requests as Park it or Push back.
- The Estimate key appears in plain words, and every story has an owner role, acceptance criteria, O / M / P days and its key assumption.
- No story is longer than 5 working days (M); longer ones are split.
- Every dependency and wait in the input appears in **Depends on** or the timeline check.
- Every risk has a response and an owner role, and at least one sits on the critical path.
- Nothing is invented: unknown owners, dates or scope are marked **TBD** and listed as open questions.
- The output is labelled a **draft for team review**. Estimates are a starting point for the team, not a commitment.
