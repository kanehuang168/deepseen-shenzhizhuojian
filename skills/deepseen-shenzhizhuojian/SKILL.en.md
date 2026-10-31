---
name: deepseen-shenzhizhuojian
description: Plan complex decisions or recurring failures using competing explanations,
  observable evidence and reversible interventions. Read-only by default. 深知灼见。
license: MIT
metadata:
  author: 祥子｜跨境无疆&DeepSeen AI创始人
  product: DeepSeen
  version: 1.0.1
  audience: 主要面向TikTok跨境卖家
  invocation_policy: MODEL_ELIGIBLE
  languages: en, zh-CN
---

[简体中文](SKILL.md)

# DeepSeen Decision Planner — 深知灼见

Plan complex decisions, recurring failures and changes crossing boundaries with falsifiable evidence and reversible interventions. Applies to products, operations, Skills and software. Reply in the user's language. Clear, local, low-impact work should proceed directly.

Default to read-only research and planning. Advice alone does not authorize edits to code, data, accounts, Skills or production. Implementation follows an explicit request. Use existing evidence and available tools, without requiring private DeepSeen ontology, ADR or employee APIs.

## Establish what would change the decision

Define the user's observable goal, preserved behavior, exclusions and acceptance. Separate facts, inferences and unknowns. History and source code are clues, not confirmed causes: obtain current evidence that reproduces the original symptom. If it is missing, design the smallest useful measurement rather than announcing a root cause or total rebuild.

Keep genuinely competing explanations and the observations that support or refute them. Rank qualitatively by impact, uncertainty and measurement cost, not invented probabilities. Look up available evidence before asking; clarify only decision-changing uncertainty.

## Compare sufficient interventions

Consider relevant choices: observe/measure, delete/simplify, local repair or larger restructuring. Address the bottleneck; more rules or abstraction are not inherently better. Connect evidence, mechanism hypothesis, intervention, expected observable change, narrow validation and rollback.

Across boundaries check requested versus effective values, identity/permission changes, ordering, partial failure and authoritative records. Caches, defaults and usually-successful retries do not prove correctness.

Challenge the draft with another explanation or simpler alternative. If no independent reviewer is available, label the review as author self-review; do not invent independence or launch a fixed agent team. Revise material issues without endless debate.

Deliver a [minimal implementation handoff](references/decision-brief.en.md): goal, evidence, hypotheses, recommendation, validation, risks, authorization and rollback. Separate static checks, build, deployment, real operation and user confirmation. If useful, Project Manager can organize execution; do not inject this planning discussion into image/video generation prompts. See the [fictional recovery example](assets/decision-example.en.md).
