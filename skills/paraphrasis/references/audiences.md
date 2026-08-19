# Audience models

An audience is not a tone. It is a set of prior knowledge, a motive, a patience budget, and a burden of proof. Naming a tone ("friendly", "professional") produces a restatement that sounds different and says the same thing to nobody in particular.

Each model below answers four questions: what they already know, what they want, what loses them, and **what they are entitled to** — the part that is not negotiable when you restate for them.

---

## Developer

- **Knows** the domain vocabulary. Does not need the concept explained.
- **Wants** to know whether it works, how it fails, and what it costs to adopt.
- **Loses them** with adjectives, benefit language, and any claim without a mechanism.
- **Entitled to** the failure modes and the limits. A developer restatement that hides the caveat is worse than useless, because they will find it in ten minutes and stop trusting everything else.

Lead with the mechanism. Numbers survive intact or you have not restated for a developer.

---

## Buyer

- **Knows** their own problem, not your category.
- **Wants** the outcome, the price, and the risk of being wrong.
- **Loses them** with architecture, and with anything that reads as evasion.
- **Entitled to** the cost and the conditions. A buyer may be given a different emphasis. They may not be given a different number.

The strongest buyer restatement is usually the source claim with the jargon removed and nothing else touched.

---

## Executive

- **Knows** how to read a hedge, and reads one as a warning.
- **Wants** the decision, the tradeoff, and what happens if they do nothing.
- **Loses them** past the first screen, and with process narration.
- **Entitled to** the uncertainty stated plainly rather than removed. Compressing for an executive is where caveats die fastest. Put the limit in the first three sentences or it will not be read at all.

---

## Beginner

- **Knows** nothing you can rely on, including the words.
- **Wants** to not feel stupid.
- **Loses them** at the first unexplained term, and does not come back.
- **Entitled to** an honest picture rather than a simplified one that will need unlearning. Simplify the vocabulary, never the shape of the truth.

Expansion is a restatement too, and it drifts in the same ways. A worked example invented to explain a real finding is still an invented specific.

---

## Skeptic

- **Knows** roughly as much as you and expects to be sold to.
- **Wants** the evidence, and to find the seam.
- **Loses them** with any claim stronger than its support, permanently.
- **Entitled to** narrower claims and more evidence than the original, never fewer.

**The burden moves in one direction.** Copy for a skeptic that hedges *less* than the source has inverted the assignment. If a claim cannot survive being stated more carefully, it should not be stated at all.

---

## Hostile reader

- **Knows** what they think and is looking for confirmation that you are what they suspect.
- **Wants** to catch you.
- **Loses them** at the first overreach, which they will quote.
- **Entitled to** their strongest objection stated before your answer, in the form they would state it.

Peitho's ethics rail already requires the counterargument. For a hostile reader it is also the only part that gets read. Steelman first, respond second, and never characterise their position more weakly than they hold it.

---

## Existing user

- **Knows** the old behavior and has built habits on it.
- **Wants** to know what changed and whether it breaks them.
- **Loses them** with launch language for something they already use.
- **Entitled to** the breakage, up front, undiluted. A release note that leads with the improvement and buries the migration is the canonical failure.

---

## Choosing what leads

Adaptation is mostly this one decision. The same claim inverts its emphasis by audience:

> **Source:** Six seats on six providers in one signed session. Two answered, four failed to rate limits and exhausted balances.

- **Developer** — "Four of six seats failed on free-tier limits. Here is the failure breakdown and what it costs to avoid."
- **Buyer** — "Runs across six providers at once. Budget for paid tiers; free tiers throttle mid-session."
- **Executive** — "Multi-provider works. Reliability under free-tier limits is not yet proven."
- **Skeptic** — "One session, six providers, two of six seats returned. The failures are signed into the record rather than dropped."

Four different leads. **The same four facts in all of them.** Nothing was softened for the buyer and nothing was sharpened for the skeptic. Only the order and the vocabulary moved.

That is the whole discipline.
