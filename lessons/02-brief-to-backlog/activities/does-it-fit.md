# Activity: Does it fit the roadmap?

You're the TPM on a learning-content team building **AI for People Managers**, a programme that helps managers make the transition into AI. Your team is working on **E1 · Pilot course content ready**, which serves **O1: pilot delivered to 2 clients by 15 Jan 2027** ([roadmap](../data/roadmap-ai-programmes.md)).

Three requests land in chat this morning. For each one, make the same call the `clarifying-roadmap-asks` skill makes:

- **1 · Fits now:** it serves E1 and is within its scope. It can become a ticket.
- **2 · Fits later:** it's on the roadmap, but in a later epic.
- **3 · Doesn't fit:** it's not on the roadmap, or it's listed as out of scope.
- **4 · Unclear, ask first:** the roadmap can be read both ways. Write the question you'd ask, and who you'd ask.

- **A.** "Can you set up the SME review of the lab instructions?"
- **B.** "Sales needs the Mandarin slides for a January prospect. Can we start now?"
- **C.** "One client wants a custom dashboard of their managers' progress."

<details>
<summary>Answer key</summary>

| Request | Decision | Why | Question worth asking |
|---|---|---|---|
| A. SME review of lab instructions | **1 · Fits now** | The labs are in E1's scope and SME review is on its critical path. | None; it becomes a ticket in Part 2. |
| B. Mandarin slides now | **2 · Fits later** | It's E6 (Q1 2027). Urgent-sounding, but starting now pulls people off E1 and puts the 15 Jan pilot at risk. | To the product manager: is this prospect worth moving E6 earlier, and what would slip? (A **4** with this question is also a good answer.) |
| C. Custom client dashboard | **3 · Doesn't fit** | "Custom work for a single client" is explicitly not on this roadmap. Raise it at the roadmap review with the trade-off, rather than ticketing it quietly. | To the client lead: what decision would the dashboard help them make? The standard LMS reporting in E9 may cover it. |

**Takeaway:** the question isn't "can we build it?" but "which roadmap outcome does it serve?" When the roadmap can't answer, ask before you ticket. The `clarifying-roadmap-asks` skill does both every time.
</details>
