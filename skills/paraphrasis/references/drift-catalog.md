# Drift catalog — worked examples

Every pair below is a real restatement failure. The OUT column is not a straw man. In each case it is the sentence a competent writer produces when asked to say the same thing more clearly, more briefly, or to someone else.

That is the point. **Drift is what good writing does to a claim when nobody is guarding it.**

---

## Upgrade

Hedged becomes absolute. The upgraded sentence is always the better sentence, which is why this one is so hard to catch.

| | |
| --- | --- |
| IN | Three seats on three providers returned three different rankings from one fixed prompt. |
| OUT ✗ | Running several models produces better decisions. |
| WHY | "Different" became "better". Nothing measured better. The source establishes that the decision *changes*, not that it improves. |
| OUT ✓ | Ask three models the same question and they rank the options differently. We have the log. |

| | |
| --- | --- |
| IN | An agent given structured vocational fields cited four sources where the same model with a role-play persona cited zero or one, on three of four providers. |
| OUT ✗ | Vocational agents are better grounded. |
| WHY | Drops the fourth provider where it did not hold, and upgrades a citation count into a general property. |
| OUT ✓ | On three of four providers the vocational build cited four sources against zero or one. On the fourth it showed no advantage. |

---

## Scope creep

A bounded instance becomes a general property. Usually accomplished by deleting four words.

| | |
| --- | --- |
| IN | In one logged session the same option ranked fifth, fifth, and first. |
| OUT ✗ | The same option ranks fifth, fifth, and first across providers. |
| WHY | "In one logged session" was the scope. Present tense turns one observation into a standing behavior. |

| | |
| --- | --- |
| IN | Seven providers verified live on 2026-08-18. |
| OUT ✗ | Works with every major provider. |
| WHY | Seven verified on a date is a measurement. "Every major provider" is a promise, and it will be tested by the first user holding the eighth. |

---

## Quantifier slide

Each step is defensible. The chain is not. Watch for it across successive rewrites of the same copy.

```
some  →  many  →  most  →  nearly all
up to  →  around  →  typically  →  consistently
can  →  will  →  does
in testing  →  in practice  →  always
```

| | |
| --- | --- |
| IN | Sessions can run with each seat on its own provider. |
| OUT ✗ | Every session runs each seat on its own provider. |
| WHY | `can` → `does`, and a capability became a description of normal behavior. A user with one API key will find this false immediately. |

---

## Agency shift

Capability restated as behavior. The most common form in product copy, because the capability sentence is clumsier.

| | |
| --- | --- |
| IN | Can be configured to run entirely on your machine. |
| OUT ✗ | Runs entirely on your machine. |
| WHY | The configuration was the condition. Removing it converts an option into a guarantee, and privacy claims are where this hurts most. |

---

## Evidence laundering

The attribution drops and the claim floats free. Nobody intends this one; it happens because the citation is bulky and the claim is not.

| | |
| --- | --- |
| IN | Green & Brock (2000) found transported readers counterargue less. |
| OUT ✗ | Studies show immersive writing lowers reader scrutiny. |
| WHY | One named study became an unnamed body of research. Peitho bans "studies show" outright for this reason. Name it or cut it. |

---

## Compression loss

**The single most destructive drift, because it is invited.** Given a word count, the qualifier is the cheapest thing to cut and almost always the load-bearing part.

| | |
| --- | --- |
| IN | In that run only two of six seats answered; the rest failed to a rate limit, a 503, a turn limit and an exhausted balance, and the failures are signed in as failures. |
| OUT ✗ | Six seats, six providers, one signed session. |
| WHY | The failure rate was two thirds. Removing it leaves a sentence that is true word by word and false as a whole. |
| OUT ✓ | Six providers in one signed session. Two seats answered, four failed, and the failures are in the record. |

**Rule: when shortening, cut examples before caveats.** If the caveat will not fit, the claim does not fit either. Choose a smaller claim.

---

## Register inflation

Neutral becomes marketing becomes superlative, one restatement per step. Detectable only by comparing against the original rather than the previous draft.

```
"records who said what"          (spec)
"keeps the disagreement"         (announcement)
"never loses a dissenting voice" (landing page)
"the only tool that..."          (ad)
```

By step four nothing traces to step one, and each step looked like a small warming of the one before it. **Always restate from the source, never from the last restatement.**

---

## Nominalisation

The actor disappears and the finding hardens into a property.

| | |
| --- | --- |
| IN | We measured a rank inversion on one prompt. |
| OUT ✗ | Rank inversion is proven. |
| WHY | "We measured, once, on one prompt" carries its own limits. "Is proven" carries none. |

---

## Audience flattery

Restating for a buyer removes what the buyer would not enjoy. This is the drift that feels most like doing the job well.

| | |
| --- | --- |
| IN | Roughly 12,500 tokens of overhead per seat, which exhausted a free-tier limit mid-run. |
| OUT ✗ | Efficient enough for everyday use. |
| WHY | The cost was the fact. A buyer is entitled to a different emphasis, not to a different number. |

**The audience may change what you lead with. It may not change what is true.**

---

## The self-check

Before returning, read only the OUT column and ask what it entitles a reader to believe. Then read the IN column and ask whether the source supports it.

If the answer is no, the drift is named somewhere above.
