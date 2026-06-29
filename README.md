# ThoughtForge

> **A cognitive forge for judgment chains, state archives, and development decisions.**

**ThoughtForge** 是一套认知锻造技能系统，用于将灵感、怀疑与判断变换转化为有来源标注、可审计、可复盘、可进入开发决策的认知资产。

它不是知识库，不是第二大脑，也不是另一个聊天 AI。ThoughtForge 关注的是：

- 一个判断是如何产生的；
- 它为什么发生变化；
- 这一步推理哪里可能有问题；
- 当前状态如何被未来重新接上；
- 一个想法是否真的值得进入开发；
- 如果值得开发，需要多少范围、资源、成本和维护代价。

## Positioning

ThoughtForge stands **before engineering execution**.

它不替代 Superpowers、Codex、Claude Code 或其他工程开发流程。它的职责不是写代码，而是在代码之前完成认知锻造：

```text
scattered idea / deep conversation
        ↓
judgment chain
        ↓
forge audit
        ↓
state archive
        ↓
development gate
        ↓
build ledger
        ↓
handoff to development workflow
```

一句话：

> **ThoughtForge helps decide whether an idea is ready to become a project; engineering workflows help build it once it is ready.**

## Core Principles

### 1. No Judgment Without Source

没有来源标注的判断，不进入沉淀。

每个重要判断都应区分：

- `[User]` 用户明确表达；
- `[AI-Inference]` AI 推断；
- `[Co-formed]` 对话共同形成；
- `[Hypothesis]` 暂时假设；
- `[Needs-Validation]` 需要验证；
- `[Rejected]` 已否定。

### 2. No Judgment Is Final Without Audit

未经审计的判断，不进入核心沉淀。

AI 生成的总结、判断链和开发建议都只是 **Draft Judgment / 判断草案**，必须经过 `forge-audit` 检查：是否过度确定、概念膨胀、遗漏反例、偷换问题或提前产品化。

### 3. No Build Without Gate

没有通过开发门槛的想法，不进入开发。

一个想法必须先回答：

- 真实问题是什么；
- 是否高频；
- 手动流程是否跑通过；
- 现有工具是否已经足够；
- 开发能减少哪一步具体摩擦；
- 第一版是否能压缩成一个核心动作。

### 4. No Estimate Without Ledger

没有开发账本，不进入工程交接。

即使一个想法值得开发，也要先看清楚第一版范围、技术依赖、AI 使用成本、用户监督成本、维护成本和范围爆炸点。

### 5. No Forge Without Review

没有锻后复盘，判断能力无法进化。

每次开发、验证或放弃之后，都应回看：当初为什么判断要做？哪些判断对了？哪些判断错了？成本是否被低估？下次类似想法该如何更好地判断？

## Skill Set

第一版 ThoughtForge 包含 7 个核心 skills：

| Skill | 中文名 | Purpose |
|---|---|---|
| `judgment-chain` | 判断链锻造 | 记录“我怎么从一个判断走到另一个判断” |
| `forge-audit` | 锻造审计 | 审查 AI 总结和判断链中的偏差、跳跃和过度确定 |
| `state-archive` | 状态存档 | 保存当前思考状态，让未来能重新进入现场 |
| `development-gate` | 开发门槛 | 判断一个想法是否真的值得进入开发 |
| `build-ledger` | 开发资源账本 | 估算第一版开发范围、资源、成本、依赖和风险 |
| `handoff-to-dev` | 开发交接 | 将通过审核的想法整理成交给工程流程的 brief |
| `post-forge-review` | 锻后复盘 | 事后复盘当初判断是否准确，改进下一次决策 |

## Repository Structure

```text
ThoughtForge/
  README.md
  principles/
    source-labels.md
    decision-states.md
  skills/
    judgment-chain/SKILL.md
    forge-audit/SKILL.md
    state-archive/SKILL.md
    development-gate/SKILL.md
    build-ledger/SKILL.md
    handoff-to-dev/SKILL.md
    post-forge-review/SKILL.md
  templates/
    judgment-chain.md
    forge-audit.md
    state-archive.md
    development-gate.md
    build-ledger.md
    handoff-to-dev.md
    post-forge-review.md
  examples/
    thoughtforge-origin.md
```

## Usage Pattern

在一次深度对话、项目构思或方向摇摆之后，可以按以下顺序调用：

```text
Use ThoughtForge / judgment-chain to extract the judgment transformation in this conversation.
Use ThoughtForge / forge-audit to audit the judgment chain for overclaiming, distortion, and missing counterarguments.
Use ThoughtForge / state-archive to preserve the current state for future continuation.
Use ThoughtForge / development-gate to decide whether this idea is ready for development.
Use ThoughtForge / build-ledger to estimate the development scope and cost.
Use ThoughtForge / handoff-to-dev to prepare a development brief.
Use ThoughtForge / post-forge-review after implementation or validation.
```

中文触发方式：

```text
使用 ThoughtForge / judgment-chain 处理这轮对话。
使用 ThoughtForge / forge-audit 审计这份判断链。
使用 ThoughtForge / development-gate 判断这个想法是否值得开发。
使用 ThoughtForge / build-ledger 估算第一版开发资源和成本。
```

## Current Status

`Prototype / Skill System Draft`

当前阶段只做 Markdown skills、模板和示例。明确不做：

- App；
- UI；
- Obsidian 插件；
- 数据库；
- 自动写入；
- 多端同步；
- 模型调用系统。

ThoughtForge 的第一阶段目标不是软件产品化，而是验证这套判断链、审计和开发门槛机制是否真实有用。
