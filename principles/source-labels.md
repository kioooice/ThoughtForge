# Source Labels

ThoughtForge treats every important statement as a claim with provenance.

The purpose of source labels is to prevent AI-generated summaries from becoming falsely authoritative.

## Labels

| Label | Meaning |
|---|---|
| `[User]` | The user explicitly said this. |
| `[AI-Inference]` | The AI inferred this from the conversation. It may be wrong. |
| `[Co-formed]` | The claim emerged through user-AI discussion. |
| `[Hypothesis]` | A useful but unverified possibility. |
| `[Needs-Validation]` | A claim that should not be treated as stable yet. |
| `[Rejected]` | A direction, claim, or framing that has been explicitly rejected or deprioritized. |

## Rule

> **No Judgment Without Source.**

A judgment that cannot be labeled should not enter the core archive.

## Example

```text
[User] I am not sure whether Brain needs to be a standalone app.
[AI-Inference] The current need may be closer to judgment-chain tracking than knowledge management.
[Co-formed] ThoughtForge should sit before engineering workflows like Superpowers.
[Hypothesis] A Markdown-only skill pack may be enough for the first prototype.
[Needs-Validation] The skills will be useful only if they are used repeatedly in real conversations.
[Rejected] Do not build a full Brain app as the first step.
```
