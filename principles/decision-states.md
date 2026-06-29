# Decision States

ThoughtForge tracks the state of an idea or judgment so that future sessions can see whether it is merely a spark, a hypothesis, a validated direction, or ready for development.

## States

| State | Meaning |
|---|---|
| `Spark` | A raw idea, intuition, or unresolved feeling. |
| `Question` | A recurring question worth exploring. |
| `Hypothesis` | A possible explanation or direction. |
| `Under Audit` | Being checked for distortion, overclaiming, missing evidence, or premature productization. |
| `Validated for Archive` | Worth preserving as a state archive or judgment chain. |
| `Deferred` | Interesting, but not ready for action. |
| `Rejected` | Explicitly ruled out or deprioritized. |
| `Ready for Build` | Passed the development gate and can move toward engineering. |
| `In Build` | Currently being implemented or prototyped. |
| `Archived` | Kept for reference, no active action. |

## Rule

A ThoughtForge artifact should always state its current decision status.

## Example

```text
Project: ThoughtForge
State: Ready for Skill Prototype
Meaning: Suitable for a Markdown skill-pack prototype, not suitable for a full application yet.
```
