# Activity: Fix the ticket

This is what a one-line prompt ("Create Jira tickets for this project") often produces:

> **Create course content**
> Make the slides and labs for the course.
> Estimate: 2 weeks

**In chat: what's missing before your team would accept this ticket?**

<details>
<summary>What to look for</summary>

| Gap | Why it matters | Where it lives in the skill |
|---|---|---|
| No acceptance criteria | Nobody can say when it's done | Every story has 2–4 acceptance criteria |
| No owner | It sits in the backlog unclaimed | Every story has an owner role |
| Too big (2 weeks, two deliverables) | Hides risk, can't be tracked | Split anything over 5 working days |
| Single-number estimate, no assumption | False precision | O / M / P estimate + key assumption |
| No dependency | SME review (2 rounds, ~1 week each) is invisible | Dependencies and waits named |
| No epic | Can't roll up to a roadmap | Every story belongs to an epic |

**Takeaway:** your team's Definition of Ready is the skill's **Checks**. Write it once, and every ticket meets it.
</details>
