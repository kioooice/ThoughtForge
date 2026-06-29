# judgment-chain

## Purpose

Forge a deep conversation or evolving idea into a traceable judgment chain.

This skill does **not** produce a normal summary. It records how a judgment changed, why it changed, what exposed the weakness of the previous judgment, and what the next move should be.

## Use When

Use this skill when:

- a conversation produced a meaningful shift in judgment;
- the user moved from one framing to another;
- a project idea was challenged, compressed, expanded, or redirected;
- a normal summary would flatten the important doubts, turns, and reversals.

Do not use this for simple factual Q&A or ordinary meeting notes.

## Input

- Conversation transcript or selected dialogue segment;
- Current topic name;
- Optional previous judgment or prior state archive.

## Process

1. Identify the starting judgment.
2. Identify the trigger that made the starting judgment unstable.
3. Extract the major judgment transformations.
4. Mark which transformations are explicit user judgments and which are AI inference.
5. Expose weak points, leaps, overclaims, and unresolved tensions.
6. Form a current, more stable judgment without making it final.
7. Define the next validation step.
8. Extract a transferable thinking pattern if one exists.

## Output Format

```markdown
# Judgment Chain

## Topic

## Decision State

## 1. Starting Judgment

## 2. Triggering Tension

## 3. Judgment Transformation Path

A → B → C → D

## 4. Key Turning Points

## 5. Weak or Risky Steps

## 6. Current Working Judgment

## 7. Next Validation Step

## 8. Transferable Pattern

## 9. Source Labels

- [User]
- [AI-Inference]
- [Co-formed]
- [Hypothesis]
- [Needs-Validation]
- [Rejected]
```

## Guardrails

- Do not make the chain look smoother than the real discussion.
- Preserve doubt, hesitation, reversal, and contradiction.
- Do not convert a working judgment into a final conclusion.
- Do not hide AI inference behind user language.
- If the conversation does not contain a real judgment shift, say so and recommend `state-archive` or ordinary summary instead.
