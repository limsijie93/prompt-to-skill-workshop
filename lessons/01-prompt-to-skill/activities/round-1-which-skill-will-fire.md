# Round 1: Which skill will fire?

Two skills are installed. Claude sees only their descriptions when deciding which one to use.

**1 · analyzing-course-feedback**
> Turns post-course feedback into a prioritised improvement backlog. Use when the user shares course evaluations or learner comments.

**2 · comparing-vendor-quotes**
> Compares 2–4 vendor quotes side by side and flags gaps. Use when the user shares vendor quotes or proposals and asks which is better value.

For each request, answer **1**, **2** or **0** (neither).

- **A.** "Here are Friday's survey results. What should we fix first?"
- **B.** "Three studios quoted for the e-learning build. Which is better value?"
- **C.** "Compare this run's learner ratings with last quarter's."
- **D.** "Draft a welcome email for next week's learners."

<details>
<summary>Answer key</summary>

- **A → 1.** Survey results are course evaluations.
- **B → 2.** Vendor quotes plus "better value" match the Use-when clause.
- **C → 1, not 2.** "Compare" is not the trigger; the subject (learner ratings, not quotes) is. A vague description like "compares things" would misfire here.
- **D → 0.** Nothing matches, so Claude answers normally. Most requests use no skill.

**Takeaway:** the description is the trigger. Say what the skill does and when to use it, in the words your users type.
</details>
