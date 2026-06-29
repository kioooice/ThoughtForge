# post-forge-review

## Purpose

Review a completed build, validation attempt, or abandoned idea against the original ThoughtForge judgments.

This skill closes the loop. It improves future judgment by comparing what was expected before development with what actually happened after action.

## Use When

Use this skill after:

- a prototype is built;
- a manual workflow has been tested;
- a project is abandoned;
- a build estimate was wrong;
- the user wants to learn from a development decision.

## Input

- Original judgment chain;
- Forge audit output;
- Development gate output;
- Build ledger output;
- Handoff brief if available;
- Actual result after build or validation.

## Process

1. Reconstruct the original decision.
2. Compare expected cost with actual cost.
3. Compare expected value with actual value.
4. Identify correct judgments.
5. Identify wrong or overconfident judgments.
6. Identify avoidable scope expansion.
7. Decide whether to continue, revise, pause, or archive.
8. Extract a reusable decision lesson.

## Output Format

```markdown
# Post-Forge Review

## Project

## Original Decision State

## Current Outcome

## 1. Why We Decided to Act

## 2. Expected vs Actual Cost

## 3. Expected vs Actual Value

## 4. Judgments That Held Up

## 5. Judgments That Failed

## 6. Scope Drift

## 7. Continue / Revise / Pause / Archive

## 8. Lessons for Future Decisions

## 9. Updated Decision State
```

## Guardrails

- Do not defend the original decision automatically.
- Do not treat completion as success.
- Do not ignore user supervision cost.
- Do not hide that a project may have been unnecessary.
- The goal is not blame; the goal is improving future judgment.

## Core Principle

> No Forge Without Review.
