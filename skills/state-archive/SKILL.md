# state-archive

## Purpose

Compress the current thinking state into a future-readable archive.

This skill is for re-entry. It helps the future user or AI quickly recover the current state of a topic without reading the whole conversation again.

## Use When

Use this skill when:

- ending a deep conversation;
- switching topics;
- preparing a handoff to a new chat;
- preserving the current state of a project, idea, or question;
- the user needs a compact entry point for future continuation.

## Input

- Conversation or notes;
- Optional judgment chain;
- Optional current topic page or previous state archive.

## Process

1. Identify the current working judgment.
2. Preserve the active tension, not just the conclusion.
3. List unresolved questions.
4. Mark rejected or deferred directions.
5. Extract ignition lines that can restart thinking.
6. Define the next continuation point.
7. Add source labels and decision state.

## Output Format

```markdown
# State Archive

## Topic

## Decision State

## Current Working Judgment

## Active Tension

## Confirmed So Far

## Rejected or Deferred

## Open Questions

## Next Continuation Point

## Ignition Lines

## Source Labels
```

## Guardrails

- Do not write a long chronological recap.
- Do not flatten the unresolved tension.
- Do not pretend the topic is settled.
- Keep it short enough to be useful as a future handoff.
- If there is a judgment chain, preserve its outcome without rewriting the whole chain.
