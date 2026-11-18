# Hermes Agent — model lifecycle constructor sufficiency and NO_GO

**PLAN_ONLY / DECISION_READY · Decision: NO_GO.** [Human decision and public fork-Issue draft](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/issue.md). No implementation, new Index grade, public Issue or executed native test.

## Boundary and accepted baseline

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

System in focus: the first-party Hermes runtime's model discovery, selection and future-session configuration at [original 2263438821ff3b9f1521096dc9997b04ef9d0834](https://github.com/NousResearch/hermes-agent/commit/2263438821ff3b9f1521096dc9997b04ef9d0834). The accepted assessment has a broader Bot/Kanban boundary; its historical grades are context, not a fresh six-function assessment of this revision. External providers are environmental sources, not first-party decision owners. Private/uninstalled plugins, maintainer governance, training a model and the OpenSiro organization are excluded.

Candidate actor/task/output: a developer composes a prospective adaptation agent; a credible impending model retirement triggers comparison of replacement/hold options under operator constraints; an authorized choice changes eligible future sessions and their outcomes return to the current-control owner and adaptation agent. This task is **not qualified by the present evidence**.

## Functional ownership

- S2 manages inter-profile interference; a picker cache or catalog refresh thread alone does not establish it.
- S3 owns current board commitments/resources in the accepted topology. This does not imply unrestricted power to change all profile model settings.
- S4 requires prospective external interpretation, alternatives, an autonomous decision actor and two-way S3 feedback. Inventory refresh, task-local retry, internal skill learning and a static redirect table do not alone demonstrate that closure.
- S5 retains legitimate purpose/ultimate policy. No delegated power over data locality, provider credentials, spend or whole-profile policy is inferred here.
- Complementary review is historically configurable S3*. No plan may silently reuse the implementer as independent auditor.

## Shipped source and competing work

| Port or native behavior | Source / actual observation | Sufficiency implication |
| --- | --- | --- |
| Remote inventory and fallback | [model_catalog.py](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/hermes_cli/model_catalog.py), blob `8927b9c950df9c229f6c1764c0d934bd98c70969` | get_catalog/refresh_catalogs support TTL, disk/stale fallback and forced refresh. Transport is available; no autonomous migration choice follows. |
| Provider/profile discovery | [model_switch_providers.py](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/hermes_cli/model_switch_providers.py) | _save_discovered_models_to_config and _discovered_catalog_stale scope discovery updates and preserve user-curated metadata. Updating an inventory is not choosing a future operational strategy. |
| Live catalog/cache | [models.py](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/hermes_cli/models.py) | Live/provider inventories, cached recommendations and account-aware selection already exist. This is the closest native alternative, not proof of complete S4. |
| Explicit ID compatibility | [models_validate.py](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/hermes_cli/models_validate.py), blob `675bded598bf5b841c2a9254187e98ff8096fbab` | _match_in_catalog explicitly avoids fuzzy rewriting; catalog omission can include legitimate newer/account-gated models. Absence is not a retirement proof. |
| External status metadata | [agent/models_dev.py](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/agent/models_dev.py), blob `709fb6be63ed8be9069807de302f08ecb99d807c` | Model metadata includes status/release_date; sensing is available, but scope/freshness and use must be established for a concrete consumer. |
| Native lifecycle boundary | [AGENTS.md](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/AGENTS.md) | Prompt caching and narrow core are explicit design invariants. New hooks without a concrete consumer are rejected; changes to prompt state defer to next session unless explicitly requested now. |
| User demand | [#5452](https://github.com/NousResearch/hermes-agent/issues/5452) OPEN | Advisory warning, not delegated migration. |
| Advisory overlap | [#5443](https://github.com/NousResearch/hermes-agent/pull/5443) CLOSED_UNMERGED at `9ceb66aa9a685b71c48fcfc0276de8797235a46a` | Inspected body/diff/comment; no shipped behavior inferred from this proposal or its claimed 84 tests. |
| Redirect/database overlap | [#26297](https://github.com/NousResearch/hermes-agent/pull/26297) OPEN at `5a77493a1975a193beed532fd906780c4bc5ac6b` | Inspected current head/diff/review. Proposed validation/database/known redirects do not establish developer-composed autonomous S4 or two-way management feedback. |
| Provider-specific maintenance | [#157299](https://github.com/NousResearch/hermes-agent/pull/157299) OPEN at `8ae2d16110cb11488599b71cb1ce6e1bfc038ed0` | Inspected head/diff: replaces Nebius fallback IDs and adjusts a test/docs. It is not complete generic adaptation. |

The #26297 [automated review](https://github.com/NousResearch/hermes-agent/pull/26297#pullrequestreview-4682154506) explicitly asks to reconcile #5443/#5452 rather than maintain a parallel system. It flags an incorrect hardcoded deprecation, provider-insensitive lookup, default-profile writes and catalog omissions. This is an attributable automated review, not independent human approval. The inspected patch confirms known redirects, provider availability checks and database operations; no native matched experiment was run. Consequently overlap remains **partial**, not proof that all user needs are already solved.

## Conditional construction chain — not an implementation specification

No C target is admitted. These are the missing properties a later qualified consumer would have to justify; the logical ports below do not assert existing APIs.

| Required property | Existing reuse | Missing proof / decision owner |
| --- | --- | --- |
| Attributable prospective signal | models.dev metadata and provider catalogs | Dated retirement signal for exact provider/model; unknown or incomplete catalog must stay unknown. |
| Alternatives plus hold | Native model inventory and explicit selection | Feasible replacements under actual task, quality, cost, data-location and tool-call constraints. |
| Developer-composed autonomous decision | Ordinary runtime can execute tasks | No supported migration actor binding or consumer mandate established. A generic agent/cron prompt is insufficient. |
| Authorized future operation | Existing model/config selection surfaces | Scope to eligible next sessions, avoid changing cached active conversations, validate current principal and revision. No hidden policy transfer. |
| Operational feedback / S3↔S4 | General persistent runtime and board primitives in historical assessment | No verified future-session route/use receipt linked to an adaptation case and returned management constraints/outcomes. General logs alone do not prove this. |

Remove the proposed autonomous actor while retaining catalog refresh, explicit selection and advisory: the demonstrated issue's warning task remains achievable by a smaller native change. Conversely, that baseline does not autonomously choose a strategy; the additional capability simply lacks a demonstrated consumer and benefit. This is the decisive **NO_GO now**, not a claim that a warning logically implements S4.

## P0 / P1 / P2

**P0:** proposed S4 migration controller rejected now. **P1:** conditional evidence/authority/feedback prerequisites only; not an approved backlog. **P2: NONE**. No mandatory new S1/S2/S3/S3*/S5 constructors. No parent-assisted variant has independent demand in this case.

## Source-specific acceptance if the case is reopened

These checks derive from Hermes' catalog, profile and prompt invariants. They are **PROPOSED / NOT_RUN**, not copied required test IDs.

| Case | Matched scenario | Observable acceptance / rejection |
| --- | --- | --- |
| Real future-session benefit | Provider-attributed upcoming retirement, real selected profile and task; compare explicit native selection/advisory with composed actor under identical constraints | A useful additional lawful adaptation outcome must be demonstrated; a warning alone fails the C claim. |
| Alternative or hold | Same signal; permitted replacement violates cost/data/tool constraints or actor chooses hold | Eligible future route differs lawfully or remains unchanged; explicit decision and actual later-session route/result return to current control and adaptation actor. |
| Omitted but valid model | Catalog lacks an account-gated, preview or custom explicit ID, reflecting models_validate behavior | No automatic retirement claim, rewrite or forced fallback from omission. |
| Profile and authority negative | Two profile homes, same model ID across different providers; absent/revoked actor or stale config revision | No cross-profile/provider or unauthorized writes; denial returned honestly. |
| Active-session compatibility | Existing cached conversation plus later eligible session | Preserve current conversation/prompt prefix; verify changes only at supported future-session boundary. |
| Provider or persistence failure | Offline/stale catalog, denied switch or failed later session | No invented successful migration; retain lawful baseline/hold and return actual failure. |

Candidate native starting points: [test_model_catalog.py](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/tests/hermes_cli/test_model_catalog.py) (forced refresh and network/stale fallback) and [test_model_cache_swr.py](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/tests/hermes_cli/test_model_cache_swr.py) (forced refresh bypass and deduplication). These sources were read, not executed. Any later product change must use `scripts/run_tests.sh` / `just test` and `just check` in an isolated HERMES_HOME, following current area instructions; do not infer model-quality results from mocks. No live paid-model/provider calls were made.

## Rights, distribution and cost

MIT [license](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/LICENSE) permits the derivative path subject to notice. [CONTRIBUTING](https://github.com/NousResearch/hermes-agent/blob/2263438821ff3b9f1521096dc9997b04ef9d0834/CONTRIBUTING.md) permits ordinary focused contributions and routes new capability to existing edges/plugins; third-party products belong outside core. AGENTS expressly supports AI coding. No CLA/DCO obligation was found in inspected root/policy/template sources; later submission must freshly check applicable personal acts, contributor identity mapping and current policy. No human review, signature or CLA acceptance is asserted.

Fork identity/permissions and absence of meta were checked via first-party GitHub. Initial metadata records this research only as DORMANT / PAUSE; no engineering or later mutation can infer RESUME from this case. Public fork Issues are disabled; no settings were changed. Exact outward public approval is absent.

**Cost status: NOT_MEASURED.** A future comparison must include native advisory/manual selection versus the full proposed authorized path: operator success, setup, integration, review, regressions, provider spend and maintenance. No saving estimate is reported.

## Terminal handoff

**Decision: NO_GO.** Preserve and use the simpler native paths; link the existing #5452 discussion rather than open a duplicate. Reopen only when a concrete consumer demonstrates additional benefit and scope, followed by current source/PR reconciliation and applicable owner rights. The stored Human document is the complete unpublished public fork-Issue draft. No original Issue draft is needed: existing #5452 covers the qualified narrow request.

[Human document](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/issue.md) · [receipt](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md)
