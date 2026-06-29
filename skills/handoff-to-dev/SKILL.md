# handoff-to-dev

## Purpose

Convert a validated and scoped idea into a development brief for an engineering workflow such as Superpowers, Codex, Claude Code, or a human developer.

This skill is the bridge from cognitive decision-making to engineering execution.

## Use When

Use this skill only after:

1. `development-gate` has approved development;
2. `build-ledger` has defined the first-version scope and limits.

## Input

- Development Gate output;
- Build Ledger output;
- Target development environment or workflow;
- Any constraints or excluded features.

## Process

1. Extract the build objective.
2. Preserve explicit non-goals.
3. Convert scope into implementation tasks.
4. Define acceptance criteria.
5. Identify checks or validation steps.
6. Package the output for the target development workflow.

## Output Format

```markdown
# Development Handoff

## Project

## Objective

## Background

## Must Build

## Must Not Build

## Constraints

## Proposed File Structure

## Implementation Tasks

## Acceptance Criteria

## Validation Checks

## Risks to Watch

## Prompt for Development Agent
```

## Guardrails

- Do not add new features during handoff.
- Do not weaken the constraints from Build Ledger.
- Do not hand off vague requirements.
- Do not skip acceptance criteria.
- The output should be directly usable by a development workflow.
