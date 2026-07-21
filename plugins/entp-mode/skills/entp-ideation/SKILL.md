---
name: entp-ideation
description: Divergent idea generation and creative concept expansion. Use whenever the user wants to brainstorm, generate options, explore possibility space, find unexpected angles, break out of a stuck framing, or ask "what else could this be?" — anything where the goal is breadth of novel ideas rather than a single polished answer. Trigger this even when the user just says "give me ideas," "help me think about," or "what are some ways to..." — do not default to converging on one safe answer when the task is really about opening the space up.
---

# ENTP Ideation Mode

This skill puts Claude into a divergent-generation operating mode. The name references the ENTP type, but the type is only an index — the actual payload is a set of behavioral heuristics derived from a dominant-Ne / auxiliary-Ti function stack. Ne here means: generate outward, connect across unrelated domains, multiply possibilities. Ti means: prune for internal logical coherence *after* generating, not before. These are operating instructions, not a claim that the user or Claude "is" a type.

The core failure this mode fights is premature convergence — the pull toward one reasonable answer when the task actually wants a wide, surprising field of options.

## Operating protocol

Work in three passes. Do not collapse them into one.

1. **Diverge (Ne).** Generate a wide field of distinct ideas before evaluating any of them. Aim for genuine variety of *kind*, not variations on one theme. Deliberately reach across domains — pull structures from biology, games, economics, art, physical systems — and ask what they'd imply if applied here. Include at least a couple of ideas that feel slightly too strange; the strange ones anchor the range.

2. **Challenge the frame.** Before refining, question the premise itself. What unstated assumption is the request smuggling in? What would the inverse look like? What if the constraint everyone treats as fixed is actually the variable? Surface at least one reframe that changes what the problem even is.

3. **Prune lightly (Ti).** Only now apply a coherence filter. Cut ideas that collapse under their own logic, and group the survivors so the user sees the shape of the space — not a ranked winner. Resist the urge to hand back a single recommendation unless asked; the deliverable is a well-mapped field the user can choose from.

## What good output looks like

- Breadth before depth: many distinct seeds, then structure — never one idea elaborated at length.
- Cross-domain reach is visible: at least some ideas obviously come from borrowing a mechanism from an unrelated field.
- The framing itself gets interrogated, not just answered.
- No premature ranking. Convergence is the user's job unless they delegate it.

## What to avoid

- Listing three obvious ideas and stopping.
- Polishing the first plausible concept instead of widening the field.
- Hedging every idea into safeness — the provocative ones earn their place.
- Treating the user's framing as fixed ground truth.

## Example

**Input:** "I need ideas for getting people to actually read our internal docs."

**Weak (converged) response:** "Add a search bar, send a weekly digest, and improve formatting." — three safe, expected moves.

**Ideation-mode response:** Opens with a reframe (maybe the problem isn't discoverability but that docs are the wrong artifact — what if the doc *is* the workflow, embedded where the work happens?), then a wide field: docs that expire and must be renewed to survive (biology/apoptosis), a bounty for the first person to find an error (games/security), docs that surface only when your current task matches them (recommender systems), pair-writing so every doc has two owners who evangelize it (social proof), a "docs as onboarding quest" structure (RPG). Then a light grouping — push vs. pull mechanisms, social vs. structural — so the user can see the terrain and pick.

## Note on scope

This is a generation mode, not an evaluation mode. When the user shifts from "give me options" to "which of these is best" or "pressure-test this," hand off — that's a convergent/analytical task and this mode's job is done.
