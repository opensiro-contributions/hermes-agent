# Hermes Agent — strategic external feedback S4 roadmap receipt

## Identity and pins

- Receipt contract: proposal-gate
- Original repository: NousResearch/hermes-agent
- Original HEAD: 152fe18976002e9a987422b7c6102c805d61264b
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/he/hermes-agent.md
- Accepted assessment blob SHA: 23b9c8ccc3dd063a03d15c96eee2bf8359ee2377
- Accepted review ref: 16bddc88dd325c5eef27c2cc71bbb14c16b870aa
- Accepted reviewed at: 2026-09-17
- Index corpus pin: 394ce776e6945115891b8f7cc459f5a7f7d7aa39
- Profile version: 0.2.1
- Assessment procedure version: 0.3.1
- System in focus: First-party Hermes persistent agent runtime with opt-in multi-profile Kanban, scheduled research and configured orchestrator; external source providers are environment, while dev evaluation, CI, marketplace plugins and external maintainer governance are excluded from runtime closure.
- Repository-wide source map: README.md, AGENTS.md, CONTRIBUTING.md, website/docs/developer-guide/architecture.md, website/docs/user-guide/features/cron.md, kanban.md, plugins.md, security.md, cron/blueprint_catalog.py, cron/monitor.py, skills/research/competitor-news-monitor/SKILL.md, skills/productivity/weekly-review-planning/SKILL.md, hermes_cli/kanban_decompose.py, tools/kanban_tools.py, agent/background_review.py, gateway/session_policy.py, original tests and CI.
- Accepted VSM vector: S1=A · S2=A · S3=C(P) · S3*=C · S4=— · S5=—
- S1 disposition: ALREADY_A; persistent autonomous profiles and task workers; no compulsory C conversion.
- S2 disposition: ALREADY_A; decomposer, tasks/dependencies, room and Kanban coordination; no duplicate S2 target.
- S3 disposition: ALREADY_C; C(P) historical configured orchestrator plus parent board-control mode; reuse current board management, do not invent universal active S3.
- S3* disposition: ALREADY_C; configured reviewer, request-changes and Swarm verifier; no duplicate S3* controller.
- S4 disposition: C_CANDIDATE; scheduled external scanning and planning primitives exist, but the proposed first-party prospective alternatives plus later S3 outcome-return path has not been confirmed.
- S5 disposition: PARENT_RESERVED; operator-authored profile identity, SOUL, tool permissions and ultimate authorization remain parent-controlled; intent beyond these facts is UNVERIFIED, not a new Index grade.
- Priority rationale: S4 has an externally oriented shipped input and legitimate composable S3 downstream, plus a testable missing two-way planning-feedback contract. S1/S2 are already A, S3/S3* have C paths; S5 lacks evidence of lawful locally delegated ultimate-policy choices.
- Target transition: S4=— -> S4=C
- P1 dependencies: Validate a safe opted-in profile/toolset and board scope; ensure existing Kanban comments/status can be read on a later cron tick; verify durable watch state, idempotent triage proposal and exact parent restrictions.
- P2 optional: NONE
- Proposed C construction: Opt-in first-party strategy-feedback skill and cron blueprint reuse competitor-news-monitor signals and Kanban; an autonomous configured profile proposes distinct future options and emits deduplicated triage cards, S3 accepts/defers/rejects, and the S4 profile reads that decision on its next tick to revise its watch and alternatives.
- C sufficiency falsifier: Existing shipped first-party competitor-watch plus configurable cron/Kanban already supplies the same source-attributed option/decision/authorized-effect/S3-return cycle with no missing reusable constructor link.
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Compare identical source-change and board inputs against shipped competitor-watch plus manual Kanban; test two distinct lawful future options, actual triage effect, returned S3 decision, restart, missing authority and source failure in a native test environment.
- Validation state: NOT_RUN
- Proposal falsifier: A matched native baseline already closes the full bidirectional loop or the proposed actor cannot lawfully influence later operations and consume S3 feedback.
- Result: PLAN_ONLY
- Operator readiness: NEEDS_EVIDENCE
- Operator decision: GO
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

## Rights and authority

Original is MIT licensed (https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/LICENSE); CONTRIBUTING prefers a skill over a new tool unless justified, focused PRs, search for duplicates, native tests and existing plugin edges. No personal CLA acceptance, third-party publication or original maintainer endorsement is claimed. A public matching fork was independently verified: opensiro-contributions/hermes-agent, fork=true, parent NousResearch/hermes-agent, opensiro/meta branch. At readback of metadata SHA 0a9d3c8f018c02872a598059bdaddf967b33e87a, .opensiro/state.json is ACTIVE / ALLOW, supported by event 20261119T182226Z--owner-upstream58-active. Issue #58's earlier PAUSE table is stale relative to the fork-local event; no assumption that ALLOW grants external publication. Fork Issues are disabled; no attempt to enable them or post a public Issue.

## Existing work / overlap

- SHIPPED: https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/cron/blueprint_catalog.py includes competitor-watch and weekly-review blueprints.
- SHIPPED: https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/skills/research/competitor-news-monitor/SKILL.md maintains watchlist, incremental signals, materiality, cited digest and persistent cutoff; it does not itself declare a bounded S3 proposal/decision-return contract.
- SHIPPED: https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/website/docs/user-guide/features/kanban.md documents configured orchestrator use of Kanban create, list, comments, claim and review, alongside dispatcher limits; cron agent sessions run tools according to configuration.
- SHIPPED: cron/monitor.py supports script and URL change-detection with stored state; existing alerts are not by themselves prospective S4 closure.
- ISSUE_ONLY: https://github.com/NousResearch/hermes-agent/issues/156054 adaptive hierarchical goals proposes user-root-preserving execution replanning, not an established external prospective S3/S4 loop.
- OPEN_PR: https://github.com/NousResearch/hermes-agent/pull/128798 proposes monitor_tool event wake for connector/MCP responses, with diff touching cron/monitor.py, cron/jobs.py, tool, CLI, docs and tests; not merged into pinned HEAD.
- OPEN_PR: https://github.com/NousResearch/hermes-agent/pull/129006 proposes level-triggered reminders; not merged into pinned HEAD.
- OPEN_PR: https://github.com/NousResearch/hermes-agent/pull/151472 concerns tool-search listing for Kanban lifecycle; a compatibility warning, not a strategy constructor.
- ORIGINAL NATIVE POLICY: https://github.com/NousResearch/hermes-agent/blob/152fe18976002e9a987422b7c6102c805d61264b/CONTRIBUTING.md prefers a skill first and checks overlapping Issues/PRs.
- HISTORICAL COMPARISON, inspected only after independent decision: https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md decided NO_GO for autonomous model migration against existing catalogs and advisory #5452. That is a different bounded user task; do not overwrite or relabel it.

## Function ownership

S1 worker autonomy and S2 dependencies transport task execution; S3 configured orchestrator or parent owns current accepted commitments, not new ultimate goals. S3* can review proposals when configured but is not automatically an independent auditor on this new path. Proposed S4 alone owns interpretation of external competitive changes, candidate future options, and revision of its own hypothesis after S3 returns a choice. The S4 actor can create scoped triage recommendations only, not change parent S5 policy, revoke approvals or force existing active work. External competitor feeds and connectors are environment, not first-party function owners. At this source boundary, a cron digest without alternative choices and returned management outcome does not establish the proposed C witness.

## Capability priority

P0 is the smallest original-native opt-in developer-composed S4 constructor, not a blanket deployment recommendation. P1 is only the scope/feedback/idempotency evidence above; P2 is NONE. Proposal GO means a complete credible construction route exists with a logical autonomous decision actor and downstream/return path; not proof it works, costs less or warrants maintainer adoption. Some apparent S4 outputs may be reproducible by existing user prompt composition: this is the strongest no-change counterfactual and a mandatory native test. Intent of missing S4 and local S5 is not inferred merely from Index dashes.

## Parallel contribution-on-top review

- Evaluation object: Hermes opt-in externally oriented strategy feedback loop from competitive-event evidence to lawful S3 board choice and return to the next S4 cycle.
- Existing-work overlap: competitor-watch already senses and rates prospective external events, weekly-review plans, Kanban can carry tasks and comments, and monitor PRs seek cheaper triggers; no reviewed source established the exact two-way strategic record as a supported bundled constructor.
- Our on-top contribution: compose a first-party research skill and opt-in cron blueprint that reuse watch contract and Kanban, persist proposal/event linkage, enumerate explicit alternative horizons and consume S3 decision evidence on the next tick.
- Incremental benefit: hypothetically lower manual integration and more traceable follow-through than a digest alone; unmeasured and possibly zero if a simple native prompt already suffices.
- Decision scope: Plan only; no code, product PR, fork Issue or original Issue, comments, publication, automatic owner permission or Index grade change.

| C-sufficiency link | Track A source and state | Track B minimum on-top link | Falsifier |
| --- | --- | --- | --- |
| External disturbance and remembered state | SHIPPED competitor-news-monitor watch contract and cron monitor hash | Reuse exact source/cutoff; associate a stable signal ID with a bounded future-horizon hypothesis | Existing watch already preserves all required prospective state |
| Lawful alternatives and autonomous S4 actor | SHIPPED configured cron profile, web tools, existing skill prompt and strategy-relevance ranking | One opt-in skill contract generates at least hold, investigate and defer alternatives with reasons; developer selects the authorized profile and board | No meaningful alternative beyond a fixed alert |
| Operational management effect | SHIPPED Kanban create, status, dependencies and triage board | Create idempotent proposal card in authorized board only, not automatic root policy changes | Prompt-only native composition yields same cards and rights |
| Feedback and S3 dialogue | SHIPPED Kanban comment/status and orchestrator/human selection | Link S3 accept/defer/reject to the original signal and read outcome on next research tick to update next options | Outcome cannot be retrieved or changes nothing at later tick |
| Negative and compatibility | SHIPPED toolset gates, profile scope, persistence and scheduling | Stop safely when permission, board scope, source or S3 feedback is absent; preserve competitor-watch-only baseline | Wrong principal, duplicated cards, false closure or unauthorized mutation |

## Implementation options

Preferred low-cost construction: add skills/research/strategy-feedback-loop/SKILL.md, a user-opt-in entry in cron/blueprint_catalog.py, and source-native blueprint/skill tests, reusing the existing Kanban/cron tools and watch contract. Add a tiny first-party board-return adapter only if tests demonstrate that ordinary Kanban comments/status cannot be reliably queried or correlated; do not fork the scheduler or introduce a new S3/S5 controller. A plain prompt+existing skill is the mandatory cheapest alternative. The user must explicitly select a permissible profile, board, watchlist and triage-only scope; absent rights mean no writes. Source PR #128798 can later reduce monitor tick costs but is not a precondition and is not assumed merged.

## Specification and domain alternatives

No Profile/Skills change or domain grade is proposed. The method should permit a legitimate no-construction outcome if the existing source is already sufficient or the owner wants manual/parent strategic choices. Competing issue #156054 is about execution-goal replanning, a possible complementary downstream S3 workflow, not a substitute for external future intelligence. The original maintainers own all product decisions; contributor/maintainer interest in this exact construction is NOT_STATED.

## Cost experiment

NOT_MEASURED. A later matched test must compare source coverage, evidence quality, alternative discrimination, returned S3 action, false alarms, token/API cost, setup and review time, and maintenance for baseline competitor-watch + manual board entry versus the opt-in proposed path. A passing smoke test is not evidence of lower total engineering cost or broad S4 capability.

## Delivery and publication

This case is a distinct plan-only research record; no .opensiro/contributions entry, product branch, original Issue/PR or new public fork Issue. [Human decision](issue.md) and [AI/developer contract](constructor-sufficiency.md) derive target, verdict and research state from this receipt. Original PR/Issue links are citations, not outreach. Native tests NOT_RUN and independent human review NOT_PERFORMED. Structural validator only checks form, not semantic truth. AI-assisted authoring disclosure applies. Any future public publication requires separate exact current-conversation consent; owner control and current original HEAD must be reread before subsequent writes.
