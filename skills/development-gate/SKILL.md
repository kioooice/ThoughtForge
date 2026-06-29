# development-gate

## Purpose

Decide whether an idea is ready to enter development.

This skill prevents premature productization. It distinguishes between a real development candidate and something that should remain a conversation, template, manual workflow, note, or experiment.

## Use When

Use this skill when:

- the user says they want to build a project;
- an idea starts turning into an app, plugin, script, or system;
- there is uncertainty about whether development is necessary;
- the user wants to avoid overengineering.

## Input

- Idea description;
- Judgment chain or state archive if available;
- Known constraints, tools, and current workflow;
- Evidence of repeated usage or pain.

## Process

1. Identify the real problem behind the idea.
2. Check whether the problem is frequent enough.
3. Check whether a manual or existing-tool workflow has been tried.
4. Identify the repeated friction that development would remove.
5. Determine whether the idea can be reduced to one core action.
6. Check for overengineering, concept inflation, and premature UI/app assumptions.
7. Produce a gate verdict.

## Output Format

```markdown
# Development Gate

## Idea

## Decision State

## 1. Real Problem

## 2. Frequency

## 3. Existing Non-Development Solution

## 4. Manual Validation Status

## 5. Repeated Friction

## 6. Minimum Buildable Action

## 7. Overengineering Risk

## 8. Gate Verdict

Choose one:

- Do Not Build
- Continue Observing
- Use Template
- Use Existing Tool
- Build Script
- Build Plugin
- Build Lightweight Skill Pack
- Ready for Engineering

## 9. Conditions for Reconsideration
```

## Guardrails

- Do not reward excitement alone.
- Do not approve development if the manual workflow has not been tried.
- Do not approve a full app if a template or skill can validate the need.
- Always specify what development would reduce: copying, sorting, rewriting, searching, deciding, validating, or handoff.

## Core Principle

> No Build Without Gate.
