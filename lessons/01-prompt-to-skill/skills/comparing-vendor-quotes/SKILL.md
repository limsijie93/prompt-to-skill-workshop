---
name: comparing-vendor-quotes
description: Compares 2–4 vendor quotes or proposals side by side (total price, GST basis, lead time, payment terms, validity, inclusions and exclusions) and flags gaps and risks. Use when the user shares vendor quotes, proposals or RFQ responses and asks which is better value or wants a comparison.
---

# Comparing vendor quotes

Put competing quotes on a level playing field so the coordinator can decide quickly and ask the right follow-up questions.

## Steps

1. For each vendor, extract: total price, currency, GST included or excluded, lead time, payment terms, quote validity, what is included, what is excluded.
2. Normalise prices so they compare like for like (same GST basis; note any optional add-ons needed to match scope).
3. Flag anything **missing, unclear or unusual** (e.g. large upfront payment, short validity, key item excluded).
4. If the user gave criteria (budget, deadline), check each vendor against them.
5. Recommend, with the main trade-off stated.
6. Draft the clarification questions to send each vendor.

## Output format

```
Comparison – <what is being bought> – <n> quotes

| | Vendor A | Vendor B | Vendor C |
| Total (like-for-like, excl. GST) | | | |
| Lead time | | | |
| Payment terms | | | |
| Valid until | | | |
| Included | | | |
| Excluded | | | |

Gaps and red flags
- ...

Recommendation
<vendor> if <condition>; <other vendor> if <other condition>. Main trade-off: ...

Questions to send
- Vendor A: ...
```

## Quality checks

Before replying, confirm:

- A value that is not in the quote is written **"Not stated"**, never assumed.
- Every price shows its GST basis.
- The recommendation names at least one trade-off and leaves the final decision to the user.
- Each vendor with a gap has at least one clarification question.
