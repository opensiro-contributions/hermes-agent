# Hermes Agent — opt-in strategic feedback S4 constructor (OpenSiro roadmap)

**PLAN_ONLY · proposal GO · research NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**

**Target transition:** S4=— -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

**One-sentence proposal:** Reuse Hermes' existing competitor watch, cron and Kanban to let a configured autonomous research profile propose lawful future alternatives, hand them to an S3 decision owner, and incorporate the actual returned outcome in its next research cycle.

**Canonical decision receipt:** [roadmap.md](roadmap.md) owns pins, all six dispositions, P0/P1/P2, the target and statuses.
**AI/developer contract:** [constructor-sufficiency.md](constructor-sufficiency.md) owns Track A/B, missing links and native future tests.
**Working fork:** opensiro-contributions/hermes-agent; separate metadata branch opensiro/meta; case hermes-strategic-feedback-s4-20261119.

## Why OpenSiro

OpenSiro tests the hypothesis that reusable organizational specifications informed by the Viable System Model can reduce design, integration and maintenance effort for agent harnesses. This is a research hypothesis, **not** demonstrated savings or a requirement that Hermes adopt VSM. We use the accepted historical Index mapping as a transparent starting point, then inspect current first-party source separately.

### Central accepted historical assessment (not today's grade)

Accepted [Hermes Agent assessment](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/he/hermes-agent.md), blob 23b9c8ccc3dd063a03d15c96eee2bf8359ee2377, reviewed **2026-09-17** at original 16bddc88dd325c5eef27c2cc71bbb14c16b870aa. Profile 0.2.1 / assessment procedure 0.3.1. The six ownership labels describe who owned organizational closure at that pinned boundary; they are not quality scores or current-HEAD findings.

| Function | Historical ownership | What current source suggests; research priority |
| --- | --- | --- |
| **S1 · Operations** | A | Autonomous persistent profiles/workers; NO_TARGET. |
| **S2 · Coordination** | A | Kanban dependencies, assignments and dispatcher; NO_TARGET. |
| **S3 · Current control** | C(P) | Configured autonomous board orchestrator and human control; reuse as downstream owner, not a new S3 constructor. |
| **S3* · Complementary audit** | C | Configurable reviewer and corrective return; reuse if appropriate, not a new reviewer. |
| **S4 · Future intelligence** | — | External watch exists but the proposed alternatives → S3 choice → next S4 cycle lacks a verified bundled constructor; P0 C_CANDIDATE. |
| **S5 · Identity / policy** | — | Parent-defined profile/permissions and user objectives remain reserved; no qualified local S5 target. |

A means autonomous closure observed, C is a developer-composable constructor, P is a parent-controlled mode, combinations denote mixed modes, — means not established and ? means unresolved. No historical — mechanically demands a feature.

## What user/operator gets

**Scenario: HYPOTHETICAL.** An operator wants an opt-in autonomous Hermes researcher to follow changes in a specified competitor's public product releases, evaluate whether to **hold the plan**, **investigate**, or **propose a future adjustment**, and route those alternatives to a configured Kanban management owner. The S3 owner actually chooses accept/defer/reject; the next scheduled S4 tick reads that decision and updates its hypothesis. The profile must never silently replace parent goals, mutate unrelated board tasks or claim a result from its own proposal.

The simplest outcome is **reusable research-to-decision traceability**, not another notification tool, scheduler or unrestricted planner. Operator/maintainer interest specifically in this loop is **NOT_STATED**; benefit is **NOT_MEASURED**.

## Existing native work versus smallest proposed gap

**Track A (SHIPPED):** [competitor-news-monitor](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/skills/research/competitor-news-monitor/SKILL.md) persists a watch contract and materiality/cutoff state, and [cron blueprints](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/cron/blueprint_catalog.py) include competitor-watch and weekly-review. [Kanban](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/website/docs/user-guide/features/kanban.md) already offers orchestrator-visible tasks, comments and feedback. These capabilities are a genuine baseline, not an absent-feature claim.

**Other work:** Original [issue #156054](https://github.com/NousResearch/hermes-agent/issues/156054) proposes evidence-driven hierarchical execution replanning; [PR #128798](https://github.com/NousResearch/hermes-agent/pull/128798) proposes monitor_tool triggers and [PR #129006](https://github.com/NousResearch/hermes-agent/pull/129006) proposes repeated level reminders. The open PRs are **not shipped** in the pinned original. None by itself demonstrates the particular S3→S4 outcome-return path.

**Track B (P0):** Add a small first-party strategy-feedback research skill and opt-in cron blueprint. Reuse the watch contract and existing Kanban tools; the developer supplies the authorized profile, board and scope. Link each material source event to alternative future actions and one idempotent triage proposal, then read the actual S3 status/comment on the next tick. Only add a new board-read adapter if native tests prove the existing tools insufficient.

## Priorities, falsification and next decision

**P0:** opt-in S4=C constructor proposal. **P1:** verify profile/board permissions, durable event→decision ID correlation, idempotency and feedback retrieval. **P2: NONE.** We prefer a skill/blueprint to a new core service because the [original contribution policy](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/CONTRIBUTING.md) directs focused new workflows toward skills.

**GO is for constructing and testing this proposal, not permission to implement or publish it.** Research remains NEEDS_EVIDENCE. Compare the same watch inputs against a simple configured competitor-watch plus manual Kanban workflow. A distinct autonomous choice must produce a permitted triage operation and a later S3 outcome must measurably alter a subsequent S4 decision. Explicitly test another lawful alternative, no owner/permission, stale event, failed external source and restarted process. Tests: NOT_RUN.

**Stop / falsifier:** if an ordinary current Hermes cron prompt plus existing watch and Kanban tools already does this completely, with the same authorized choice, durable feedback and no added first-party mechanism, reject this proposed constructor as unnecessary. Also stop on authority failure, duplicate effects, a missing S3 return or a loop that is only digest generation.

## Independence and historical comparison

This source-first analysis reached GO **before** opening the previous OpenSiro [model-lifecycle S4 case](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md). That old NO_GO concerned autonomous **provider/model migration**, with a narrower advisory issue and existing selection tools as the cheaper alternative. The new proposal concerns **external strategic watch and future-plan feedback**. It does not overturn or edit the old case. Both can legitimately coexist, because the tested operation and counterfactual differ.

## Delivery and authority

Original HEAD: [152fe18976002e9a987422b7c6102c805d61264b](https://github.com/NousResearch/hermes-agent/commit/152fe18976002e9a987422b7c6102c805d61264b). Fork-local owner state was independently read as **ACTIVE / ALLOW** with an attributable 2026-11-19 owner event; issue #58 retained an older PAUSE table. This authorizes the bounded fork-local case write, **not** external publication. Fork Issues were disabled at observation.

**Decision:** retain a source-pinned, plan-only GO + NEEDS_EVIDENCE hypothesis and compare the proposed native loop with the cheapest no-change composition before any code approval. No product code, original Issue, PR, comment, external publication, grade change, S5 delegation or measured cost claim is being made. This is the complete **unpublished** fork-Issue draft. AI-assisted; no independent native test or human review has been performed.

[AI/developer companion](constructor-sufficiency.md) · [Canonical receipt](roadmap.md).
