# AI Error Log

A running list of moments when my AI assistant got something wrong
about geophysics — what it said, why it was wrong, and how I
verified.

This file lives in `ai_logs/error_log.md` and grows across the course.
It is referenced in my final project's reproducibility section as
evidence of my fact-checking practice.

---

## Entry template

```yaml
date: YYYY-MM-DD
tool: [name + version if known]
session_link: ai_logs/lab6_session_NN.md
topic: [seismic refraction / earthquake location / NMO / gravity / etc.]
```

**What the AI said (quote or paraphrase):**

> [paraphrased claim or pasted excerpt — keep it short]

**Why it is wrong:**

[Specific reason in your own words. One short paragraph.]

**Primary-source verification:**

[The textbook page, equation number, or course lecture URL that
disproves the AI's claim. Include the exact quote if the source
contradicts the AI directly.]

**How I would have detected this with prompt strategy alone:**

[One sentence — e.g., "I should have asked for a unit check before
accepting the formula."]

---

## Entry 1

```yaml
date: 2026-05-25
tool: Claude 3 - Sonnet 4.6
session_link: none
topic: seismic refraction
```

**What the AI said (quote or paraphrase):**

> Incorrect claim: travel time for a refracted wave is given by 2h/V1

**Why it is wrong:**

This is just the travel time for a direct vertical wave, not a refracted wave.

**Primary-source verification:**

Couse lecture, Refraction I, Section 3.3, Equation 55

**How I would have detected this with prompt strategy alone:**

I would have asked it to derive a second way to ensure the end result was the same.

## Entry 2

[Add entries as the course progresses — Labs 7, 8, final project.]
