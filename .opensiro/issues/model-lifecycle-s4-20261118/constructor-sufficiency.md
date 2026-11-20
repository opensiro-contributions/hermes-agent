# Hermes Agent — model-lifecycle S4 constructor sufficiency (Wave 4)

**CURRENT: proposal GO / NEEDS_EVIDENCE · PLAN_ONLY · native tests NOT_RUN**

[issue.md](issue.md) · [roadmap.md](roadmap.md) · [immutable historical NO_GO contract](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md)

**Target transition:** S4=— -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

## Scope / historical mapping

Accepted `S1=A · S2=A · S3=C(P) · S3*=C · S4=— · S5=—` at [Index main dadcf25d6e7f](https://github.com/opensiro/vsm-harness-index/blob/dadcf25d6e7ffcbdb298e476a249b8be187c53b4/assessments/he/hermes-agent.md); blob `23b9c8ccc3dd063a03d15c96eee2bf8359ee2377`, review `16bddc88dd325c5eef27c2cc71bbb14c16b870aa` on 2026-09-17, Profile 0.2.1, Skills procedure 0.3.1. New original `main@2de9f51b8008a7d49a49221c184f2f11cbfc4af1` is a different source pin and has **not** been regraded. Operations S1 and coordination S2 already operate. S3 has configurable and parent control of board commitments; S3* configurable adversarial review; S5 provider/policy/identity reserved to owner. Neither generic scheduling nor internal learning is credited as shipped S4.

## Source-backed constructor

| S4 port | First-party reuse and missing binding | Positive/negative sufficiency |
| --- | --- | --- |
| External future signal | [models.dev source](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/agent/models_dev.py) and optional explicit provider notices read by separate configured agent; status may be stale | Dated provider/model provenance; stale/missing data => UNKNOWN/hold |
| Autonomous options/choice | First-party [Cron](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/user-guide/features/cron.md) isolated profile with skill/plugin, native available provider models and fallback check | Profile chooses retain/prepare/hold and two lawful candidates; no actor or no alternative => no invented choice |
| S3 policy/current integration | [Kanban](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/tools/kanban_tools.py), configured orchestrator and parent board owner | Source-linked versioned triage proposal, S3 accept/defer/reject with authority and idempotent write/return; S4 must not bypass parent |
| Authorized later effect | Existing model config/fallback owner controls, active-session caching invariant from [AGENTS](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/AGENTS.md) | Only owner-approved next sessions; no active-session prompt mutation, credential leak, manual-pin override, cross-profile/provider switch, or stale CAS |
| Return/learning | [Hooks](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/developer-guide/observer-hooks.md) for request and error receipts + Kanban result links | Actual next-session succeeded/failed route and S3 decision correlated back into the same S4 watch state and changed future options; observer hooks are not write authority |

This is a **proposed first-party C-construction**, not a statement that an installed Hermes runtime currently ships the full link. The S4 identity, decision scope and downstream/return feedback must be supplied explicitly. A generic LLM cron digest, catalog refresh, retry chain, fixed redirect, or unapproved plugin is insufficient.

## Independent Track A / B and counterfactual

Track A: [#5452](https://github.com/NousResearch/hermes-agent/issues/5452) advisory model-sunset warning; [#5437](https://github.com/NousResearch/hermes-agent/issues/5437) capability checks; native `hermes model`, fallback check and model catalog. [PR #26297](https://github.com/NousResearch/hermes-agent/pull/26297) is open/unmerged deprecation detection/redirect, [PR #115486](https://github.com/NousResearch/hermes-agent/pull/115486) open/unmerged opt-in routing policy, and [#150930](https://github.com/NousResearch/hermes-agent/issues/150930) open credential-safe switch interface request; none proves a shipped future S4 loop or that maintainers consider present code permanent.

Track B: (1) reuse unchanged native controls, (2) implement opt-in dedicated S4 profile/skill+C choice and Kanban S3 two-way bridge, (3) simpler advisory + human route action, or (4) use a new generic plugin seam only if a concrete consumer and supported request require it. Compare the actual *decision-and-return ownership*, not only whether users eventually get working models. No first-party equivalent C closure was established at the pinned source; no future construction is proven yet.

## Acceptance matrix — all PROPOSED / NOT_RUN

| Test | Exact stimulus | Required first-party observation / falsifier |
| --- | --- | --- |
| True prospective transition | Source says model retires on a date; two allowed candidate routes | Independent S4 alternative/hold decision; S3 board accepts/defers/rejects, with source/time and reason |
| No reliable source | Offline/cached/omitted new model, preview/account-specific ID | Does not infer retirement from missing listing; hold and report uncertainty |
| Authority denied | S3/S5 denies, wrong profile, secrets unavailable, stale revision | No switch, credential leak or overwrite; blocked action logged and returned |
| Active session and manual pin | Existing conversation cache, new sessions and per-job pins | Existing session unchanged; legitimate future sessions follow explicitly approved scope |
| Later result feedback | Authorized next session succeeds, fails or changes model on fallback | Correlated final provider/model/result returned to same S4 identity; next decision reflects it |
| Negative equivalence | Native warning/manual baseline runs same future task | If equivalent first-party **autonomous** S4 control and S3 feedback already exists, disqualify new C |
| Independent owner removed | Disable dedicated S4 profile but retain native catalogue and fallback | Manual path still works; proposed autonomous prospective decision disappears, proving separate role |
| No framework seam | Existing hooks do not allow credential-safe configuration action | Requires a minimal generic approved port or result BLOCKED; never fake successful effect |

## v0.18.1 native-specific engineering / falsification addendum — not implemented

This is a refinement of the same [Wave 4 source-only first pass](https://github.com/opensiro/upstream/issues/58#issuecomment-7043074679), not a new independent claim. Original source was frozen at `2de9f51b8008a7d49a49221c184f2f11cbfc4af1` during first-pass research; updated `main@f998a982cb8be2ac46b062d49996e8116b5171f7` was [compared](https://github.com/NousResearch/hermes-agent/compare/2de9f51b8008a7d49a49221c184f2f11cbfc4af1...f998a982cb8be2ac46b062d49996e8116b5171f7) (five CI / plugin-import compatibility commits, no modified model/Cron/Kanban/skills operation paths). Accepted Index `included` and historical six-function labels unchanged.

**Smallest source-native change**: propose **new** `skills/research/model-lifecycle-watch/SKILL.md`, shipped as an **opt-in Hermes Skill**, not a core daemon/hook. It configures a *named profile's own* Cron job (see [`cron/scheduler.py`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/cron/scheduler.py) and [`tests/cron/test_cron_profile_isolation.py`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/tests/cron/test_cron_profile_isolation.py)), source freshness/monotone watch state under that profile home, official exact-provider/model notices cross-checked with cached [models.dev `ModelInfo.status`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/agent/models_dev.py), and bounded autonomous future-option selection. [Existing competitor news watch](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/skills/research/competitor-news-monitor/SKILL.md) supplies primary-source/dedup/cutoff design precedent but is **not** itself a model-lifecycle implementation. No new builtin provider or implicit S5 mandate.

The first-party [Kanban tool schemas](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/tools/kanban_tools_schemas.py) are the precise S3 bridge: opt-in `kanban`-enabled watcher calls `kanban_create(title,assignee,body,idempotency_key,board)`, stores the returned task ID, and later calls `kanban_show(task_id,board)` to read the assignee's disposition, comments, status and real run attempts. `kanban_comment` can carry bounded extra evidence; a comment alone must never be equated to an authorized model switch. The S3 owner (configured orchestrator or human) may approve a **separately authorized** future-session route or a scoped validation card. The subsequent genuine attempted run plus result must return through Kanban/observability to the watcher. No arbitrary `ctx.switch_model` or provider-credential access is credited: [#150930](https://github.com/NousResearch/hermes-agent/issues/150930) remains a request, and the [observer hooks](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/website/docs/developer-guide/observer-hooks.md) mostly report outcomes without mutation rights.

| Test target | Input stimulus | Proof and negative boundary |
| --- | --- | --- |
| Future notice | Officially dated provider/model retirement; `models.dev` status/cache may be stale | Correct provider-qualified source, an option+hold comparison and credible future decision; stale/missing source returns UNKNOWN/HOLD |
| Minimal edit | Install proposed skill to opt-in profile, schedule through existing Cron, enable the existing `kanban` toolset | No unsupported new core route, no shared-root profile leakage, no automatic privilege escalation |
| Dedup/authority | Same alert observed twice, different tenant / assignee / model pin | `idempotency_key` yields one stable real board card; wrong scope or no owner authority blocks without mutation |
| S3↔S4 closure | S3 accepts/defers/rejects card and runs allowed bounded validation in assigned profile | Subsequent `kanban_show` sees correlated **actual run result** and watcher adapts next choice; absence of outcome must remain NEEDS_EVIDENCE |
| No side effects | Active cached session, account-gated/omitted-but-valid ID, explicit pin or invalid provider | No silent model rewrite, no arbitrary redirect, no secret sharing across profiles or false retirement |
| Counterfactual | Same scenario with native `hermes model`, catalog warning and configured fallback check | Baseline can satisfy current warning/manual selection, but does not own the same independent prospective S4 choice+S3 return; if equivalent autonomous C is found, downgrade to NO_GO |

**Falsifier strengthened:** no supported way to make an opt-in profile produce an independent future choice and durable Kanban S3 response/outcome, or no lawful authorized later-session effect, makes this **not proven C** and may require a smaller *generic* first-party seam before a GO can be validated. A merely drafted skill/prompt cannot establish `C` absent a complete tested owner/effect/feedback chain. Implementation/tests are **NOT_RUN** and this remains a *proposal-stage* `GO / NEEDS_EVIDENCE`, not `DECISION_READY` or product adoption.

**Reviewable follow-up tests (new test cases to add only if implementing):** isolate two profile homes (`tests/cron/test_cron_profile_isolation.py`), ensure Cron environment cannot borrow Kanban worker privileges (`tests/cron/test_cron_kanban_env_isolation.py`), assert idempotent create/readback+denial (`tests/tools/test_kanban_tools.py`), and confirm only configured fallback routes are live-tested (`tests/hermes_cli/test_fallback_check.py`). All are exact source-native test suites on the current HEAD, **not tests executed in this Roadmap run**. Preserve [`AGENTS.md`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/AGENTS.md) prompt-cache constraints and [`CONTRIBUTING.md`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/CONTRIBUTING.md) plugin/skill placement rules.

**Outcome remains `GO / NEEDS_EVIDENCE`, P0 one S4 constructor, P1 dedicated profile/watch/board feedback acceptance, P2 none.** VSM is an architectural hypothesis, not a requirement to implement a feature; original maintainers alone decide adoption. Archived internal [PR #83](https://github.com/opensiro/upstream/pull/83) CLOSED_UNMERGED and listed in [Supplementary](https://github.com/opensiro/upstream/blob/main/docs/ROADMAP_REPORT.md#supplementary). Per merged reporting policy, no new Upstream status PR or standalone Markdown report was produced.

## Decision and attribution

**P0 `GO / NEEDS_EVIDENCE`**, scenario **HYPOTHETICAL**, for proposed `S4=— -> S4=C` only. P1 tests: source provenance, future-session effect and feedback. P2 NONE. Native tests not executed; economic effect not measured. A product maintainer can reasonably reject this additional capability regardless of architectural C feasibility.

First-pass source-only result was written to [Upstream #58](https://github.com/opensiro/upstream/issues/58#issuecomment-7043074679) before any previous case was opened. [Historical NO_GO](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md) judged product incremental usefulness; neutral v0.18.0 asks C constructibility and preserves the historical record, yielding a changed current verdict. A distinct [Hermes strategic external feedback case](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/hermes-strategic-feedback-s4-20261119/roadmap.md) is not superseded or edited. No product code or public Issue/PR authored.
