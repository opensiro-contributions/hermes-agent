# Hermes Agent — strategic feedback S4 constructor sufficiency (technical companion)

**PLAN_ONLY / source-grounded construction hypothesis / native tests NOT_RUN.**

**Target transition:** S4=— -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

**Canonical source of case decisions:** [roadmap.md](roadmap.md), which owns the historical accepted six-function vector, six dispositions, priorities, rights, source pins and verdict. **Human-facing fork-Issue draft:** [issue.md](issue.md). Do not treat a separate AI narrative as a second assessment or decision.

## 1. Boundary, owner and counterfactual

Original product: [NousResearch/hermes-agent at 152fe18976002e9a987422b7c6102c805d61264b](https://github.com/NousResearch/hermes-agent/commit/152fe18976002e9a987422b7c6102c805d61264b). Supported first-party boundary: installed Hermes runtime with agent profiles, user-configured cron, bundled research skills and optional configured Kanban orchestrator. External competitor websites, connected services and model providers are **environment**, not S4 operators; Github CI, developer governance, marketplace plugins and unrelated examples are not automatically part of the deployed agent system. A Kanban card is not necessarily a recursively viable organizational subsystem.

The [six dispositions in roadmap.md](roadmap.md) exclude rebuilding S1/S2, do not replace the existing S3 C(P) path or S3* review, and keep ultimate identity and policy under the user/developer S5 parent. For S4 this proposal adds an opted-in **autonomous prospective option generator** with a feedback link to the legitimate current-management owner. Profile/toolset configuration does not by itself grant parent policy authority.

**Function-specific witness:** competitor release or analogous dated external change → source-cited prospective state → at least two future choices (including hold) → a developer-selected S4 autonomous profile chooses a recommendation and proposes only an authorized Kanban triage task → an S3 orchestrator/human accepts, defers or rejects it → subsequent eligible work sees that decision → next S4 watch tick reads it and revises its future options. An unchanged digest alone is not the witness.

**Decisive owner counterfactual:** with the S4 profile and its explicit future-option/decision-return contract removed, cron still fires, competitor-watch still sends digest, and Kanban can still hold manually created tasks. But no first-party opt-in workflow requires source-grounded alternatives to be correlated with S3 outcome and reconsidered at the next cycle. If a simple existing configured prompt already provides this full lawful return, the claimed minimum missing constructor is false.

**Scenario status:** HYPOTHETICAL, not a reported incident, maintainer request for this exact contract or tested operational need. Maintainer/contributor interest in the exact proposed implementation: NOT_STATED. Existing source policy suggests a skill first; this is a placement constraint, not product endorsement.

## 2. Track A — pinned first-party baseline and concurrent original work

| Layer | What actually exists at pinned HEAD / original status | Relevant source and limitation |
| --- | --- | --- |
| External sensing | SHIPPED competitor-news-monitor watch contract with named subjects, sources, cutoff, materiality, citations and state file | [bundled skill](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/skills/research/competitor-news-monitor/SKILL.md); primarily cited digest, no explicit S3 disposition return |
| Scheduler / research execution | SHIPPED agent-backed cron jobs and first-party competitor-watch, weekly-review blueprints; optional monitor script/URL | [blueprint_catalog.py](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/cron/blueprint_catalog.py), [cron docs](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/website/docs/user-guide/features/cron.md) |
| Management bridge | SHIPPED scoped Kanban create/list/comment/status and configured orchestrator profile; dispatcher enforces task ownership | [Kanban first-party docs](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/website/docs/user-guide/features/kanban.md), [tools/kanban_tools.py](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/tools/kanban_tools.py) |
| Task replanning | ISSUE_ONLY #156054 proposes evidence-based hierarchical goals and preserved user root | [#156054](https://github.com/NousResearch/hermes-agent/issues/156054); task execution horizons, not external S4 closure |
| Event trigger efficiency | OPEN_PR #128798 adds monitor_tool source to cron/monitor.py, tool/CLI, docs and tests; patch reviewed, unmerged | [#128798](https://github.com/NousResearch/hermes-agent/pull/128798); event wake, not prospective organizational decisions |
| Repeated condition notice | OPEN_PR #129006 adds level monitor notices; unmerged | [#129006](https://github.com/NousResearch/hermes-agent/pull/129006); alert recurrence, not S4 |
| Toolset compatibility | OPEN_PR #151472 fixes Kanban tool-search exposure | [#151472](https://github.com/NousResearch/hermes-agent/pull/151472); needs recheck if proposed tests exercise that mode |

No unmerged PR is credited as SHIPPED; author-reported test success is not an independently run test. The concrete ordinary baseline is existing competitor-watch with cited digest + manual/Kanban triage. It may turn out to be adequate at much lower engineering cost. Developer-configured cron+Kanban prompts are a particularly strong competitor, not an ignored alternative.

## 3. Track B — smallest function-specific construction

| Required organizational C link | Track A coverage | Proposed on-top C path (not yet shipped) | Defeating evidence |
| --- | --- | --- | --- |
| External/prospective state | Bundled incremental watch state and materiality | Reuse dated source evidence; add stable association between observed event, forward hypothesis, horizon and the decision card | Watch contract already records all needed future option state |
| Autonomous but bounded decision | Configured agent-backed cron and research tools | Developer opts in a named S4 profile and selects board, watch sources and allowed triage effect; skill requires compare hold/investigate/adjust, confidence and alternatives | Actor only paraphrases fixed rules or no independent option changes |
| Lawful first-party effect | Existing Kanban create and optional idempotency key | Reuse Kanban triage creation with stable signal ID and exact evidence, with no unconditional task/goal rewrites | No supported access or duplicate cards after retry |
| Two-way current-management feedback | Kanban comments/status and S3 orchestrator/human owner | Retrieve accept/defer/reject and cause from corresponding proposal card on next scheduled tick, update prospective watch and show what changed | Cannot read S3 outcome, or outcome has no effect on next alternatives |
| Recovery / parent rights | Config/toolset gates, persistent watch file, stopped cron and task state | Fail closed on missing profile, revoked permission, unavailable board/source, old decision or lifecycle conflict; preserve current manual/competitor-watch baseline | Unauthorized writes, loss of actor attribution or false completion |

### Physical design choices and complexity challenge

**Option 1 (cheapest, mandatory negative control):** No new first-party source. Configure a dedicated existing cron job with existing competitor-watch instructions plus a Kanban-enabled orchestrator profile and store signal/task correlation using supported file and comment facilities. If this closes all source/option/authority/effect/return links reproducibly, stop with NO_GO for this patch and document configuration, rather than shipping redundant framework code.

**Option 2 (preferred if option 1 is insufficient):** Add a small reusable bundled skill at skills/research/strategy-feedback-loop/SKILL.md and opt-in cron blueprint in cron/blueprint_catalog.py. The skill instructs the developer on explicit profile, board, input, authority and horizon; it reads prior decision receipts, generates decision alternatives, and closes returned feedback before emitting another triage proposal. Native blueprint/skill tests enforce required slots, no unintentional scheduling or mutation, and stable idempotency guidance. No new scheduler, database or core registry unless source-specific acceptance proves those existing surfaces incapable.

**Option 3 (only on failed option 2 integration):** Add the smallest isolated Kanban feedback query/receipt adapter to correlate actual S3 actor/status/comment with a signal, following existing kanban_db and toolset boundaries. Do not turn it into a second board, second S3, generalized policy engine or unbounded autonomous planner. Check that tool-level readbacks and profile scope cannot already supply the return.

The preferred construction includes a complete **proposed** C cycle with an autonomous S4 decision actor whose future options differ with external evidence and S3 feedback, while enforcement stays on current Kanban and permissions. It is distinct from alert-only PRs, internal memory reflection and issue #156054's execution replanning. **Claimed C sufficiency is architectural and provisional**: no source-native experiment has yet established actual closure or measured gain.

## 4. Priority, authority and stop rules

P0 is the strategy-feedback S4 C hypothesis selected only after the six-function screen in [roadmap.md](roadmap.md). P1: verify configured profile has appropriate cron/web/Kanban read and triage rights; reliable durable signal→card mapping, later S3 comment/status readback and restart behavior; avoid dependence on unmerged monitor-tool PR. P2: NONE. S3 remains the legitimate owner of present commitments, S4 can recommend only within operator-provided scope, and parent S5 keeps goals, credential permissions, identity and mission. The exact external environment can change without making a local S5 mandatory.

**Stop** if an ordinary native composition already completes the same S4 loop, if only a static digest remains, if the result is not returned to later operation, if operator rights are not verifiable, if a maintainer rejects the proposed extension, or if a readback shows source drift that invalidates the bridge. Unknown maintainer interest is neither a fabricated veto nor evidence of demand. Cost measurement is not a proposal-stage prerequisite.

## 5. Proposed native acceptance (all NOT_RUN)

Actual repository test entry: [CONTRIBUTING.md](https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/CONTRIBUTING.md) documents just test with explicit paths, scripts/run_tests.sh, and python scripts/check. Closest existing regression suites: tests/cron/test_blueprint_catalog.py, tests/cron/test_monitor_kind.py, tests/hermes_cli/test_kanban_db.py, tests/tools/test_kanban_tools.py. Suggested commands after an authorized isolated implementation: **just test tests/cron/test_blueprint_catalog.py**, **just test tests/tools/test_kanban_tools.py**, then **python scripts/check** and any new source-native integration tests. They have not been executed in this study.

| Proposed test, matched scenario | Future source-native evidence | Expected result | Falsifier |
| --- | --- | --- | --- |
| Positive external → S4 → S3 → later S4 | Changed canonical competitor changelog, configured board/profile, two cron ticks separated by an S3 action | Source-cited distinct options; one authorized idempotent triage card; recorded S3 accept/defer/reject; later watch revision names the actual returned choice | Digest only, no later feedback or wrong task |
| Independent alternative | Same input but revised parent resource constraint or S3 rejection | Autonomously change future recommendation to hold/defer or investigate; do not force old option | Fixed identical output despite changed legitimate feedback |
| No authority / wrong scope | Missing Kanban toolset, wrong board/profile or revoked authorization | No mutations outside scope; clear refusal/receipt; no fabricated S3 decision | Wrong-board write, silent success or scope escalation |
| Retry/restart/idempotency | Same signal across repeated cron tick and restarted gateway | One proposal linkage, no duplicate card; prior S3 outcome recovered from persisted state | Duplicated effects, lost linkage or false new incident |
| Source/feedback failure | Stale external feed, invalid evidence or missing S3 status | Explicit unknown/hold and next evidence request; existing competitor-watch-only mode works unchanged | Invented certainty or irreversible mutation |
| Cheapest native alternative | Same fixtures under existing competitor-watch + prompted Kanban composition, matched model/tools/budget | Record extra coverage, correctness, setup/maintenance and tokens; select no-change if equivalent | Proposed constructor adds no supported effect or lower cost |

This is a test plan, not green CI, not executed evidence, not a measured improvement and not Index reclassification.

## 6. Verdict, historical divergence and publication boundary

**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

**Primary falsifier:** a source-native existing cron/competitor-watch/Kanban prompt realizes the same complete external planning alternatives, authorized S3 action and returned revision at equal or lower burden, or no lawful autonomous S4 decision/feedback path is achievable at this boundary. Validation state: NOT_RUN. Proposal GO and research NEEDS_EVIDENCE are compatible: the former admits a specific falsifiable construction experiment, not product implementation.

The previous [Hermes model-lifecycle case](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md) was inspected only **after** this independent GO decision. Its NO_GO was for autonomous model-deprecation migration where an advisory was the established narrower need. This S4 case has different external environment, effect and user scenario; it does not invalidate or edit that source-owned historical decision. Research novelty and benefit are unmeasured.

Rights: verified MIT original; current fork meta source independently read ACTIVE / ALLOW and explicit owner event, permitting this internal research artifact without authorizing original/fork public GitHub Issue publication. Current Issues disabled. External publications, product code, grade changes and third-party maintainer interactions: NONE. Actual original and metadata HEAD must be reread before any later effectful action.

Sources of truth: Profile semantics, Skills methodology, accepted Index, first-party Hermes source, then case [roadmap.md](roadmap.md) for derived statuses. **Cost: NOT_MEASURED.** AI-assisted authoring; no independent human audit, personal CLA act or actual native test run. [Human draft](issue.md).
