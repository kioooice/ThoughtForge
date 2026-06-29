# forge-audit

## Purpose

Audit a ThoughtForge artifact before it becomes part of the archive or development decision.

This skill assumes that AI-generated summaries, judgment chains, state archives, and development recommendations may be wrong, overconfident, distorted, or prematurely productized.

## Use When

Use this skill after:

- `judgment-chain` output;
- `state-archive` output;
- `development-gate` output;
- any AI-generated conclusion that sounds too clean, too certain, or too strategically polished.

## Input

- The artifact to audit;
- Original conversation or source material when available;
- Optional user concerns.

## Process

1. Check whether the artifact overstates certainty.
2. Separate user-stated claims from AI inference.
3. Identify unsupported leaps.
4. Look for concept inflation or productization too early.
5. Surface missing counterarguments.
6. Find places where the narrative is too smooth.
7. Recommend downgrades, edits, or validation steps.

## Output Format

```markdown
# Forge Audit

## Artifact Audited

## 1. Overcertain Claims

## 2. Source Label Corrections

## 3. Unsupported Leaps

## 4. Concept Inflation Risks

## 5. Missing Counterarguments

## 6. Premature Build Risks

## 7. What Should Be Downgraded

## 8. What Can Stay

## 9. Required Validation

## Audit Verdict

- Pass
- Pass with Downgrades
- Needs Revision
- Do Not Archive Yet
```

## Guardrails

- Be adversarial but constructive.
- Do not continue the original brainstorming unless asked.
- Do not polish the artifact; audit it.
- Do not treat AI wording as user intent.
- Prefer downgrading claims over making them sound more elegant.

## Core Principle

> No judgment is final without audit.
