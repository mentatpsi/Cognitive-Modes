---
name: istp-troubleshooting
description: Diagnose a malfunction at the mechanism level and find the pragmatic fix — debugging, root-causing a failure, figuring out why something concrete isn't working. Use when something is broken and needs diagnosis: 'why isn't this working,' 'debug this,' 'root-cause this failure,' 'what's actually going wrong here.' Trigger whenever the task is hands-on diagnosis of a concrete malfunction, not design or planning.
---

# ISTP Troubleshooting Mode

A diagnostic mode built on dominant Ti (build a precise internal model of how the mechanism works) with auxiliary Se (engage directly with what's actually in front of you, right now). It isolates the real cause by understanding the mechanism and testing against reality, not theory.

The core failure this mode fights is fixing symptoms and guessing — swapping parts or adding code until it seems to work, without knowing why it broke or whether it's truly fixed.

## Operating protocol

1. **Reproduce and observe.** Get the actual failure in front of you. What exactly happens, under what conditions? Work from the real signal, not a description of it.
2. **Model the mechanism.** Understand how it's supposed to work well enough to locate where reality diverges from the model. You can't find the break without knowing the machine.
3. **Isolate by bisection.** Narrow the fault — split the system, test which half misbehaves, repeat — and change one variable at a time so you know what did what.
4. **Fix the cause and verify.** Address the actual root cause, then reproduce the original condition to prove it's gone and check nothing else broke. 'Seems fine now' isn't verification.

## What good output looks like

- Works from a reproduced, observed failure.
- Models the mechanism to locate the divergence.
- Isolates by controlled bisection.
- Fixes the root cause and verifies against the original condition.

## What to avoid

- Guessing and swapping parts.
- Changing many variables at once.
- Treating a disappeared symptom as a confirmed fix.
- Theorizing without touching the actual system.

## Note on scope

This mode diagnoses and fixes a concrete malfunction. Redesigning the system so the class of failure can't recur is a different, structural task — worth flagging once the fire is out.
