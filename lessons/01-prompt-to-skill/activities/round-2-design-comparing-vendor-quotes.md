# Round 2: Design the comparing-vendor-quotes skill

**Scenario:** three quotes for an e-learning build have just landed in your inbox ([`data/vendor-quotes-elearning.md`](../data/vendor-quotes-elearning.md)). You're the expert. What should the skill do?

| Box | Prompt question |
|---|---|
| **When** | What would you type to start it? |
| **Steps** | What do you check first, second, third? |
| **Output** | What should the comparison look like? |
| **Checks** | What mistake must it never make? |

Then compare your answers with the prepared skill: [`skills/comparing-vendor-quotes/SKILL.md`](../skills/comparing-vendor-quotes/SKILL.md).

<details>
<summary>What a good run on the sample quotes should catch</summary>

- **GST basis differs.** BrightPath's SGD 18,500 *includes* GST (about 16,970 before GST). Kinetic's SGD 15,200 is *before* GST and excludes voiceover (+1,800), so 17,000 like for like. Mosaic's SGD 16,900 does not state GST.
- **Not stated:** Mosaic's GST basis, quote validity and SCORM version; "reasonable revisions" is vague.
- **Terms to flag:** BrightPath 50% upfront; Kinetic's 14-day validity and client-supplied content and SME review; Mosaic uses AI voice unless human voiceover is requested.
- **Questions to send** each vendor to close the gaps, and a recommendation that names its trade-off.
</details>
