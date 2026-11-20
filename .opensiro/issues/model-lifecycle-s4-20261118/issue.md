# Hermes Agent — model lifecycle S4 roadmap (OpenSiro plan-only)

**CURRENT Wave 4 · 2026-11-20 · GO / NEEDS_EVIDENCE (proposal only) · Public Issue: NOT PUBLISHED**

[roadmap.md](roadmap.md) · [constructor-sufficiency.md](constructor-sufficiency.md) · [historical case snapshot](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/model-lifecycle-s4-20261118/issue.md)

**Target transition:** S4=— -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

## Proposed original-native capability

An opt-in, *developer-composable* future provider/model retirement watcher using Hermes' supported separate profiles, Cron jobs, model catalogue, skills/plugin hooks and Kanban. A designated independent future-analysis profile reads **dated provider lifecycle evidence**, autonomously chooses `retain / prepare successor / hold` from verified lawful options, and sends source-linked, versioned choices to the explicitly configured current-work S3 owner. The operator/current owner controls any model changes, especially credentials, future-session effects and rejected proposals. A subsequent task/route outcome returns to the same watcher for revision of its next recommendation.

This is a constructor hypothesis, not a current shipped Hermes feature or claim of customer demand. It requires explicit opt-in, an external signal, a real autonomous choice, executable feedback/effect boundaries and an observed future outcome. A generic Cron digest, model-catalog refresh or automatic fallback does not establish that path.

## Why this is separately assessable

The [accepted historical Index assessment](https://github.com/opensiro/vsm-harness-index/blob/dadcf25d6e7ffcbdb298e476a249b8be187c53b4/assessments/he/hermes-agent.md) (blob `23b9c8ccc3dd063a03d15c96eee2bf8359ee2377`; 2026-09-17; source `16bddc88dd325c5eef27c2cc71bbb14c16b870aa`; Profile 0.2.1 / procedure 0.3.1) classifies ownership/configurability, not product quality. It does **not** claim current 2026-11-20 code has changed grade.

| Function | Accepted state | Current-source interpretation and constructor decision |
| --- | --- | --- |
| **S1 · Operations** | A | Autonomous Hermes profiles and Kanban workers; no new S1 target |
| **S2 · Coordination** | A | Bot handoffs, task ownership and dependencies; no new S2 target |
| **S3 · Inside-and-now** | C(P) | Configured orchestrator board control plus human board owner; reused for authorized choices |
| **S3* · Independent audit** | C | Configured review/verifier with corrective return; keep separate |
| **S4 · Outside-and-then** | — | No historical prospective choice+S3 feedback closure; **optional proposed S4=C** |
| **S5 · Policy and identity** | — | Owner/provider policy and credentials not delegated by this plan |

A means autonomous owned closure; C means developer-composable owned closure; P means parent-controlled closure where the Skills grammar permits it; `—` is no accepted closure, **not a defect or mandate**. The transition is hypothetical and does not update these accepted historical states.

## Track A — source-native baseline

At [original main@2de9f51b8008a7d49a49221c184f2f11cbfc4af1](https://github.com/NousResearch/hermes-agent/commit/2de9f51b8008a7d49a49221c184f2f11cbfc4af1), first-party [model metadata](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/agent/models_dev.py) already includes status/release/capability fields; [fallback configuration](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/user-guide/features/fallback-providers.md) supports ordered failover and dry-run/live checks; [Cron](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/user-guide/features/cron.md) can run isolated recurring profiles; [Kanban](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/user-guide/features/kanban-tutorial.md) carries assignments, dependencies and run outcomes; [observer hooks](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/developer-guide/observer-hooks.md) expose provider attempt/result/error telemetry. None independently establishes an autonomous *prospective* model-life decision and S3↔S4 closure.

Existing original [Issue #5452](https://github.com/NousResearch/hermes-agent/issues/5452) asks for a deprecation warning, and [#5437](https://github.com/NousResearch/hermes-agent/issues/5437) for compatibility preflight. [PR #26297](https://github.com/NousResearch/hermes-agent/pull/26297) remains **OPEN/UNMERGED** for reactive detection and redirect; [PR #115486](https://github.com/NousResearch/hermes-agent/pull/115486) remains **OPEN/UNMERGED** for routing policy. [#150930](https://github.com/NousResearch/hermes-agent/issues/150930) documents an unresolved plugin switch contract. Existing proposals cannot be credited as merged behavior or used to infer maintainers' final choice.

## Track B — bounded constructor and alternatives

| Option | New user-visible function if validated | Boundary |
| --- | --- | --- |
| A · reuse native warning/manual selection | Warning and manual operator choice; no claimed additional C | Lowest-cost product baseline and legitimate alternative |
| B · opt-in S4 profile + watcher + Kanban two-way link | External future signal → autonomous options/hold → S3 decision → next-session outcome → revised S4 option | Source-native candidate; needs tests, narrow lawful authority |
| C · automatic redirect, separate catalog daemon, generic new hook | Reactive convenience or infrastructure, not sufficient prospective S4 | Avoid duplicate #26297 / unused core surface |

**GO means construction can be coherently specified using the first-party extension and decision boundaries if implemented**, not that Hermes should implement it. The actual model switch and choice of allowed providers remain with current S3/parent and the original maintainer. Product adoption is the maintainer's decision.

## Required acceptance and falsifiers (NOT_RUN)

1. A real dated provider+model deprecation with trustworthy source, and an expired/stale/omitted/account-gated model negative without false retirement claims.
2. At least two supportable future candidates (including `hold`) and a distinct S4 model/profile **choosing** between them under declared constraints; missing actor produces no decision.
3. A durable S3 Kanban proposal accepted, deferred or rejected; no silent global override, cross-profile credentials, manual pins, current-session context rewrite or stale-revision write.
4. A subsequent eligible session actually uses the authorized route (or fails honestly), with correlated provider/response outcome returned to S4 for a changed subsequent recommendation. Existing read-only hooks do not grant mutation.
5. Native A/B versus warning + manual picker on the **same** future transition. If existing first-party paths already own equivalent complete S4 closure, the new construction is not qualified.

No native tests or provider calls were run. Benefits, costs and maintainers' intentions are **NOT_MEASURED / NOT_INFERRED**.

## Decision and provenance

**P0 `S4=— → S4=C`: `GO / NEEDS_EVIDENCE`** for assessment-neutral architectural constructibility, `PLAN_ONLY / HYPOTHETICAL`. **P1:** validate actor, source, scoped authority, future-session effect and S3 feedback. **P2:** NONE.

The [earlier 2026-11-18 NO_GO](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/model-lifecycle-s4-20261118/issue.md) used a material product-benefit criterion; preserve it as a historical decision, not as a veto of constructibility. This v0.18.0 post-release rerun was [sealed independently before old-case readback](https://github.com/opensiro/upstream/issues/58#issuecomment-7043074679). A [distinct Hermes external-strategy S4 case](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/hermes-strategic-feedback-s4-20261119/roadmap.md) stays separate and unchanged.

Working fork `opensiro-contributions/hermes-agent@opensiro/meta`: `ACTIVE/ALLOW` read immediately before metadata commit; internal research writes permitted. MIT/CONTRIBUTING/AGENTS read; no third-party or public fork Issue/PR permission follows. Full text is **an unpublished fork-Issue draft only**. No product code, Index regrade or external communication occurred.
