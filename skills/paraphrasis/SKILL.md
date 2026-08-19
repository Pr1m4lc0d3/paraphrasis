---
name: paraphrasis
description: Use when saying the same thing to a different audience — restating, re-voicing, translating for a new reader, shortening, expanding, or adapting a message for a developer, a buyer, an executive, a beginner, a skeptic, or a hostile reader. Also use when compressing to a word count, writing a summary or TL;DR, turning a spec into an announcement, a changelog into a release note, a paper into a post, or one channel's copy into another's. Carries the drift catalog, the fidelity ledger, and the reversal test. Not for improving prose in place — that is peitho. Not for rendering audio into text — that is metaphrasis.
---

# Paraphrasis

Sense-for-sense restatement, with the meaning held still.

Named against its opposite. **Metaphrase** is word-for-word; **paraphrase** is sense-for-sense. Dryden drew the line and put the danger on this side of it: once you stop moving words and start moving sense, nothing mechanical is left to check your work. This skill is the check.

## What this is for

One message, a different reader. A spec becomes an announcement. A finding becomes a landing page. Nine hundred words become ninety. The claim is supposed to survive all of it.

Usually it does not.

## The third job

`peitho` forks two ways: **Compose** when no draft exists, **Edit** when one does. Restating is neither, and running it as either causes damage.

| Job | Words | Meaning | Characteristic failure |
| --- | --- | --- | --- |
| Compose | new | new | slop, dishonest persuasion |
| Edit | mostly kept | kept | voice theft, recomposition |
| **Restate** | **replaced on purpose** | **must not move** | **drift** |

Edit protects the writer's voice by leaving the sentences alone. Restate cannot do that, because replacing the sentences is the entire assignment. So it needs a different guard, and the guard has to be on the meaning rather than the words.

## The axiom

**Everything may change except what is being claimed.**

| Free to change | Must survive unchanged |
| --- | --- |
| vocabulary, register, tone | claim strength |
| length, order, structure | scope and conditionality |
| examples, metaphors, framing | attribution and source |
| format, channel, medium | numbers and units |
| what to lead with | caveats and exclusions |
| how much context to supply | who or what is doing the acting |

If the right column moved, you did not paraphrase. You wrote a different claim in a similar voice, which is the failure this skill exists to catch.

## The fidelity ledger

**Every restatement returns one.** It is the deliverable, not a courtesy.

```
IN   →  Three seats on three providers returned three different rankings
        from one fixed prompt (Exhibit A, bb4aa857, 2026-08-15).

OUT  →  Ask three models the same question and you get three different
        answers. We logged it.

KEPT     three seats · three providers · three rankings · one prompt · logged
DROPPED  exhibit id, date          — recoverable from the source, not load-bearing here
ADDED    nothing
```

`ADDED` is the field that matters. Anything in the output with no ancestor in the input is invented, and inventing under a paraphrase reads as sourced when it is not. **A non-empty ADDED line is a stop, not a note.**

`DROPPED` needs a reason each time. "Cut for length" is only acceptable for detail that does not condition the claim. A caveat is never merely detail.

## The drift catalog

Named failures. Restatement finds these on its own; nobody has to intend them.

**Upgrade.** Hedged becomes absolute. *"seats disagreed in one session"* → *"councils reach better decisions."* The most common drift by a distance, because the upgraded version is always the more useful sentence.

**Scope creep.** A bounded instance becomes a general property. *"in one logged run"* → *"consistently."* *"on three of four providers"* → *"across providers."*

**Quantifier slide.** *some* → *most*. *up to* → *typically*. *can* → *does*. Each step is small and defensible; the chain is not.

**Agency shift.** *"can be configured to run locally"* → *"runs locally."* Capability restated as behavior.

**Evidence laundering.** The attribution drops, the claim survives, and the claim now floats. This is how "studies show" gets written by people who are not lying.

**Compression loss.** Under a word count the qualifier is the cheapest thing to cut and usually the load-bearing one. **When you shorten, cut examples before caveats.** If the caveat will not fit, the claim does not fit either.

**Register inflation.** Neutral → marketing → superlative, one restatement per step, each one only slightly warmer than the last.

**Nominalisation.** *"we measured X"* → *"X is proven."* The actor disappears and the finding hardens.

**Audience flattery.** Restating for a buyer quietly removes what the buyer would not want to hear. The audience may change what you lead with. It may not change what is true.

## The reversal test

Run before returning anything.

**Paraphrase the output back toward the input. Is the round trip stronger than the original?**

If restating your own OUT produces something the source would not support, you drifted, and the direction of the drift is now visible. Weaker is usually fine. Stronger never is.

## Hostile and skeptical readers

A skeptical reader is not a different tone. It is a different **burden of proof**, and it moves in one direction: toward more evidence and narrower claims, never fewer and broader. Copy for a skeptic that hedges less than the original has inverted the assignment.

For a hostile reader, state the strongest version of their objection before your answer. Peitho's ethics rail requires the counterargument anyway. Here it is also the only thing that gets read.

## The claims rail

**If the project has a claims file, check the output against it before returning.** Look for `truth.md`, `claims-register.md`, or a FORTRESS pack in a `.monkeys/` folder.

Restatement is the exact moment a barred claim re-enters approved copy, because nobody re-checks a rewrite of something already approved. A rail that lists withdrawn wording exists precisely for this pass. Where a project bars an upgrade in writing, treat that bar as blocking rather than advisory.

Where no claims file exists, the ledger is the whole rail, and `ADDED` must be empty.

## Delegation

**Prose quality is `peitho`'s.** Invoke it for the output. Do not restate its rules here.

This skill decides what the restatement may and may not carry. Peitho decides how the resulting sentences read: the em-dash law, the tells, openings, closings, the honest-persuasion rail. Two skills, two jobs, one canonical home for each. When they disagree about a sentence, fidelity wins and Peitho gets the next pass.

## Workflow

1. **Name the audience.** What they know, what they want, what they will not sit through, what they will resist. Vague audiences produce vague restatements.
2. **Inventory the claims in the source.** Each one separately, with its strength, scope, and attribution attached.
3. **Decide what leads.** This is the audience's real entitlement, and it is nearly all of the adaptation.
4. **Restate.** Move everything in the left column freely.
5. **Build the ledger.** KEPT, DROPPED with reasons, ADDED.
6. **Run the reversal test.**
7. **Check the claims rail** if one exists.
8. **Hand the prose to `peitho`.**
9. **Return the restatement and the ledger together.** Never the restatement alone.

## Composes with

- **`peitho`** — the prose pass on the output. Always. Paraphrasis holds the meaning, Peitho makes the sentences read.
- **`fortress` / `fortress-truth`** — supplies the claims rail. Restating without one is how withdrawn wording returns.
- **`janus`** — when the same product must be said two opposed ways to two audiences and both must stay true, the contradiction is the positioning rather than a drift to launder.
- **`raid` / `raid-draft`** — channel-specific restatement, one message into many rooms.
- **`metaphrasis`** — the mirror. It crosses a medium literally, this crosses an audience faithfully.

Full graph in `../SKILLS-MAP.md`.

## References

- `references/drift-catalog.md` — worked before-and-after examples for every named drift
- `references/audiences.md` — audience models, and what each is genuinely entitled to
