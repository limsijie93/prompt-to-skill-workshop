---
name: clarifying-roadmap-asks
description: Reads a roadmap, flags what it leaves unclear, and checks whether a stakeholder's ask fits it. Decides Fits now, Fits later, Doesn't fit or Unclear - ask first, and drafts the questions to send the requester and the roadmap owner. Use when the user shares a roadmap together with a request, change or new idea from a stakeholder and asks whether it fits, whether to take it on, what to ask, or how to respond. Not for breaking an epic into tickets.
---

# Clarifying roadmap asks

Before anything becomes a ticket, answer one question: **which roadmap outcome does this ask serve?** When the roadmap can't answer that, say so and ask; don't guess.

## Steps

1. **Understand the roadmap.** Summarise it in 3 lines at most: the goal, each outcome with its deadline, and the epic currently in progress. Note who owns the roadmap and who owns the epic in progress.
2. **Flag what the roadmap leaves unclear.** List up to 3 gaps that matter for this ask: scope lines that could be read two ways, missing owners or dates, unstated dependencies, or no rule for approving changes. Quote the roadmap's own words where the gap is.
3. **Restate the ask** in one line: who asked, what they want, by when, and the problem behind it. Mark anything the requester didn't say as **unknown**.
4. **Check fit.** Match the ask to an outcome and epic. Check it against scope, out of scope, "not on this roadmap", deadlines and team capacity. Pick one:
   - **Fits now:** it serves the epic in progress and is within its scope. Hand it to the ticketing step.
   - **Fits later:** it serves a later epic or outcome. Name that epic and when it starts.
   - **Doesn't fit:** it isn't on the roadmap, or it's listed as out of scope. It goes to the roadmap owner as a trade-off, not a ticket.
   - **Unclear, ask first:** the roadmap can be read both ways, or a key unknown from step 3 decides it.
5. **Say how sure you are** (High / Medium / Low) and which single fact would change the answer.
6. **Write the questions.** Up to 3 for the requester (the problem, the deadline, what happens if it waits) and up to 2 for the roadmap owner (the trade-off to decide). Each question must be answerable in one line. Don't ask anything the roadmap already answers.
7. **Draft a short reply** to the requester, in a friendly tone: what you'll do next and when they'll hear back. Never promise the work before the fit is clear.

## Output format

```
Roadmap in brief
- Goal: ...
- Outcomes: O1 ... (due ...), O2 ..., O3 ...
- In progress: <epic> (owner: <role>), serving <outcome>

What the roadmap leaves unclear
- "<quoted words>": <why it matters for this ask>

The ask
<who> wants <what> by <when>, because <problem or unknown>

| Ask | Decision | Roadmap link | Why | Confidence | Would change if |

Questions to send
To the requester:
1. ...
To the roadmap owner:
1. ...

Draft reply
"..."
```

For several asks, give one table row per ask and group the questions by ask.

## Quality checks

Before replying, confirm:

- Every decision names a roadmap outcome or epic, or quotes the roadmap line that rules it out.
- "Unclear, ask first" is used when the roadmap is ambiguous; don't force a yes or no.
- Nothing the requester didn't say is stated as fact; unknowns are marked **unknown**.
- Every question is one the roadmap doesn't already answer.
- Nothing is ticketed here. "Fits now" asks go to the ticketing step, for example the `breaking-down-projects-for-jira` skill.
- The reply commits to a next step and a time, not to the work.
