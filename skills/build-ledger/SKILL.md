# build-ledger

## Purpose

Estimate the development scope, resources, costs, dependencies, and risks after an idea passes the development gate.

This skill does not produce an exact quote. It creates a development cost profile so the project does not enter engineering with hidden scope or underestimated maintenance burden.

## Use When

Use this skill after `development-gate` returns a build-positive verdict, such as:

- Build Script;
- Build Plugin;
- Build Lightweight Skill Pack;
- Ready for Engineering.

## Input

- Development Gate output;
- Intended first version scope;
- Known constraints;
- Preferred implementation path;
- Tools or platforms involved.

## Process

1. Define what the first version must do.
2. Define what the first version must not do.
3. Estimate files, modules, and components.
4. Identify technical dependencies.
5. Estimate AI usage cost, user supervision cost, time cost, cash cost, and maintenance cost.
6. Identify scope explosion points.
7. Recommend the correct build form.
8. Define strict handoff limits for engineering.

## Output Format

```markdown
# Build Ledger

## Project

## Decision State

## Build Verdict

## 1. First-Version Scope

### Must Build

### Must Not Build

### Explicitly Forbidden Add-ons

## 2. Files and Modules

## 3. Technical Dependencies

## 4. Cost Profile

- AI usage cost:
- User supervision cost:
- Time cost:
- Cash cost:
- Maintenance cost:

## 5. Complexity Profile

- Functional complexity:
- Technical complexity:
- Review complexity:
- Maintenance complexity:

## 6. Risk Ledger

- Scope explosion risk:
- Technical risk:
- Validation risk:
- Long-term usage risk:

## 7. Recommended Build Form

## 8. Engineering Handoff Limits
```

## Guardrails

- Do not pretend to know exact costs when only ranges are possible.
- Do not expand the first version while estimating it.
- Do not approve hidden dependencies without naming them.
- Do not move to handoff if the first version cannot be stated in one core action.

## Core Principle

> No Estimate Without Ledger.
