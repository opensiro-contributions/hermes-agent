# Hermes Agent — model lifecycle S4 roadmap (OpenSiro plan-only; NO_GO)

**PLAN_ONLY / DECISION_READY · Operator decision: NO_GO · Public Issue: NOT PUBLISHED**

## Why Opensiro and the accepted assessment

Opensiro tests whether reusable VSM-informed specifications can standardize harness development and reduce implementation, integration and maintenance cost. Cost savings remain unmeasured; maintainers have no obligation to adopt VSM.

**S1=A · S2=A · S3=C(P) · S3*=C · S4=— · S5=—**

[Accepted Index assessment](https://github.com/opensiro/vsm-harness-index/blob/5f6ea0c777733813ca42e3f210390a719488dcfb/assessments/he/hermes-agent.md), blob `23b9c8ccc3dd063a03d15c96eee2bf8359ee2377`; reviewed 2026-09-17 at `16bddc88dd325c5eef27c2cc71bbb14c16b870aa`; Profile 0.2.1 / procedure 0.3.1. The assessment is 62 calendar days old on 2026-11-18. Recommend an Index-owned, source-pinned reassessment before relying on these labels for current architecture; this roadmap neither regrades nor blocks on that advisory. No pending reassessment has been credited as accepted evidence.

| Function | Accepted state | Meaning and roadmap consequence |
| --- | --- | --- |
| S1 · Operations | A | Autonomous persistent profiles execute work; excluded from new constructor work. |
| S2 · Coordination | A | Bot/board interactions coordinate distinct profiles; preserve existing ownership. |
| S3 · Current control | C(P) | Configured orchestrator and human board control; no compulsory reconstruction. |
| S3* · Complementary audit | C | Configurable reviewer/verifier with corrective return; preserve independence. |
| S4 · Future adaptation | — | No accepted external/prospective S3↔S4 closure at the assessed revision; investigate usefulness rather than fill the slot. |
| S5 · Identity/policy | — | No accepted ultimate-policy closure; no separate source-native S5 need established here. |

## Decision for the human

**NO_GO now: do not build a separate autonomous model-lifecycle S4 controller.** The candidate task was: an operator configures an adaptation agent to interpret an upcoming provider/model change, compare lawful replacements or hold, obtain current resource constraints, and change only eligible future sessions with observed feedback.

The first-party need actually established is narrower: [#5452](https://github.com/NousResearch/hermes-agent/issues/5452) asks for an advisory deprecation warning. Current catalog refresh and explicit model selection already address inventory and operator choice. The inspected evidence does not establish a material additional operator outcome requiring the autonomous controller or its engineering overhead. This rejects this speculative constructor now, not the usefulness of warning users.

**Best native alternative:** use existing live/remote catalogs and explicit `hermes model` selection; investigate the small advisory requested in #5452 through the existing discussion if separately selected for engineering. No automatic replacement or background monitor is proposed by this decision.

## Existing work and residual uncertainty

| Evidence | Observed status on 2026-11-18 | Consequence |
| --- | --- | --- |
| [Remote catalog](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/hermes_cli/model_catalog.py) and [provider discovery](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/hermes_cli/model_switch_providers.py) | Shipped at the pinned original source | Refresh/caching and discovery are already available; catalog transport alone is not S4. |
| [#5452](https://github.com/NousResearch/hermes-agent/issues/5452) | OPEN; no comments returned | Concrete demand is advisory sunset warnings, not delegated migration authority. |
| [PR #5443](https://github.com/NousResearch/hermes-agent/pull/5443) | CLOSED_UNMERGED; head `9ceb66aa9a685b71c48fcfc0276de8797235a46a` | Advisory preflight proposal; not shipped. Discussion questions its complexity. |
| [PR #26297](https://github.com/NousResearch/hermes-agent/pull/26297) | OPEN, unmerged; head `5a77493a1975a193beed532fd906780c4bc5ac6b` | Parallel deprecation database/redirect proposal. Automated review flags provider scope, profile state and omitted-but-valid catalog entries; not proof of an S4 constructor. |
| [PR #157299](https://github.com/NousResearch/hermes-agent/pull/157299) | OPEN, unmerged; head `8ae2d16110cb11488599b71cb1ce6e1bfc038ed0` | Narrow Nebius fallback-list repair; not generic adaptation closure. Author-reported tests were not independently rerun. |

Full source map, authority boundaries, proposal falsification and conditional native acceptance are in the [AI/developer contract](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md).

## Priority and minimum sufficient result

| Priority | Present decision | Conditional requirement |
| --- | --- | --- |
| P0 · S4 model-lifecycle constructor | Rejected for implementation now | Demonstrate an operator task that current catalog + explicit selection + small advisory cannot meet materially as well. |
| P1 · Would-be prerequisites | No implementation backlog admitted | Only after that demand: scoped agent authority, external signal provenance, options/hold, future-session enforcement and S3 feedback. |
| P2 | NONE | No independently justified second constructor or parent-mode extension. |

No shipped C is claimed. S1/S2/S3/S3* already have accepted A/C arrangements; S5 is outside this bounded opportunity. A, C and P describe ownership, not a maturity ladder.

## Acceptance, stop and alternatives

Reconsider only with a real consumer, legitimate delegated decision scope, supported first-party execution seam, a matched native baseline and later-session feedback. A notice, updated catalog or deterministic redirect does not prove S4. Any proposed switch must preserve profile/provider scope, explicit model IDs and current-session prompt-cache invariants. An absent actor or revoked authority must leave configuration untouched.

Native tests: **NOT_RUN** (plan-only, no product implementation). Proposed conditional cases are not executed results. Cost status: **NOT_MEASURED**. Compare the same authorized migration task, including setup, review, operational disruption and maintenance, against the cheapest native alternative before claiming savings.

The current source is [NousResearch/hermes-agent at 2263438821ff3b9f1521096dc9997b04ef9d0834](https://github.com/NousResearch/hermes-agent/commit/2263438821ff3b9f1521096dc9997b04ef9d0834). The verified fork parent matches that original; original/fork roots had no conflicting .opensiro directory. MIT license and contributor guide were read. AI development instructions exist; no CLA/DCO requirement was found in the inspected documents, which is not proof that none can apply later.

This case initializes research metadata as **DORMANT / PAUSE**, with no engineering RESUME. Product code, accepted Index labels and external discussions are unchanged. The fork currently has Issues disabled. The complete title and this body are an unpublished fork-Issue draft; enabling Issues and posting would require a distinct authorized action and exact public consent. No original Issue is proposed because #5452 already owns the narrower demand.

[Case receipt](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md) · [AI contract](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md)
