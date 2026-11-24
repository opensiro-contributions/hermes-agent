# Hermes Agent — capability roadmap receipt (Wave 4, 2026-11-20)

## Identity and pins

- Receipt contract: proposal-gate
- Original repository: NousResearch/hermes-agent
- Original HEAD: 2de9f51b8008a7d49a49221c184f2f11cbfc4af1
- Observed at: 2026-11-20
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/dadcf25d6e7ffcbdb298e476a249b8be187c53b4/assessments/he/hermes-agent.md
- Accepted assessment blob SHA: 23b9c8ccc3dd063a03d15c96eee2bf8359ee2377
- Accepted review ref: 16bddc88dd325c5eef27c2cc71bbb14c16b870aa
- Accepted reviewed at: 2026-09-17
- Index corpus pin: dadcf25d6e7ffcbdb298e476a249b8be187c53b4
- Profile version: 0.2.1
- Assessment procedure version: 0.3.1
- System in focus: First-party Hermes persistent runtime plus opt-in Cron profiles, model metadata, plugin hooks and Kanban S3; external provider announcements are environmental evidence, and uninstalled plugins are not credited as shipped first-party S4.
- Repository-wide source map: README.md, AGENTS.md, CONTRIBUTING.md, agent/models_dev.py, website/docs/user-guide/features/fallback-providers.md, website/docs/user-guide/features/cron.md, website/docs/user-guide/features/kanban-tutorial.md, website/docs/developer-guide/observer-hooks.md, tools/kanban_tools.py, hermes_cli/plugins.py, cron/scheduler.py, test directories, original Issues and PRs.
- Accepted VSM vector: S1=A · S2=A · S3=C(P) · S3*=C · S4=— · S5=—
- S1 disposition: ALREADY_A; persistent autonomous profile agents and Kanban workers; no S1 build requested.
- S2 disposition: ALREADY_A; Bot handoffs and Kanban dependencies/atomic claims coordinate independent units; no S2 build requested.
- S3 disposition: ALREADY_C; configured orchestrator board control and human parent control are C(P), not universal automatic authority over provider config.
- S3* disposition: ALREADY_C; configured verifier and request-changes review, not a reason to add a second auditor.
- S4 disposition: C_CANDIDATE; existing catalog, Cron, supported profile/skill/plugin and Kanban interfaces permit a scoped autonomous prospective decision-and-return construction, not shipped S4 closure.
- S5 disposition: PARENT_RESERVED; model access, credentials, provider selection policy, data locality and ultimate goals remain owner-defined; no S5 constructor authorized.
- Priority rationale: S4 is the only separately qualified configurable C hypothesis at this boundary; the nontrivial delta is autonomously choosing future options and consuming actual S3 results, not fixing a current failure or filling an empty vector cell.
- Target transition: S4=— -> S4=C
- P1 dependencies: Verify exact-model/provider source provenance, first-party configured watch identity, isolated profile permission, versioned S3 board handoff, user-approved next-session effect and returned later-session evidence.
- P2 optional: NONE
- Proposed C construction: Proposed new opt-in Hermes-native skills/research/model-lifecycle-watch/SKILL.md: profile-scoped Cron checks dated official provider lifecycle notices + models.dev metadata; configured kanban-enabled watch profile autonomously chooses retain/prepare/hold, creates one idempotent kanban_create decision card for a configured S3 profile, then on a later tick reads kanban_show real S3 disposition and bounded validation-run outcome. No new core daemon, credential-switch hook, silent route edit or S5 delegation is assumed.
- C sufficiency falsifier: No independent choice actor, no legitimate S3 feedback/effect channel, unsafe credential or configuration ownership, or an equivalent existing first-party autonomous prospective bidirectional controller in current original main.
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Pinned synthetic provider sunset and two valid/invalid alternatives; isolate active sessions and manual pins; test opt-in/deny/stale evidence, owner approval/rejection, later first-party route execution/failed outcome and feedback to the independent S4 profile against current catalog/manual-warning baseline.
- Validation state: NOT_RUN
- Proposal falsifier: A real native A/B cannot establish autonomous future option selection plus lawful S3 decision/returned operational feedback; or the same loop is already fully owned by a shipped first-party path.
- Evaluation object: Existing model-lifecycle-s4-20261118 case; new post-v0.18.0 assessment-neutral architectural constructibility re-run, not the independent strategic feedback case.
- Existing-work overlap: Original main has model selection/fallback/catalog/cron/Kanban and a plugin observer API; #5452 and #5437 request notices/preflight; PR #26297 and #115486 are OPEN, unmerged; none is established as deployed equivalent prospective S4 decision/feedback.
- Our on-top contribution: Optional developer-composed first-party S4 option loop using existing scheduled profiles, supported tools and a bounded S3 Kanban bridge; no original product change in this research.
- Incremental benefit: Enables *potential* independent prospective alternative/hold choice and return of management outcome absent from static warning/manual model picker; benefit not measured or required for architecture GO.
- Decision scope: Proposal constructibility only; no product adoption decision, new current Index grade, resource/policy delegation, fork public Issue, original contact, code implementation or tests.
- Result: PLAN_ONLY
- Operator readiness: NEEDS_EVIDENCE
- Operator decision: GO
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

First-pass verdict sealed in [#58 source-only checkpoint](https://github.com/opensiro/upstream/issues/58#issuecomment-7043074679) **before** historical case comparison. Accepted Index is historical and unchanged; original HEAD is separately current-pinned.

## Rights and authority

Correctly parented public fork `opensiro-contributions/hermes-agent` → `NousResearch/hermes-agent`, metadata branch `opensiro/meta`; current [state.json](https://github.com/opensiro-contributions/hermes-agent/blob/opensiro/meta/.opensiro/state.json) is `ACTIVE / ALLOW` under owner activation and inspected again before write. Original [MIT LICENSE](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/LICENSE), [CONTRIBUTING](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/CONTRIBUTING.md) and [AGENTS](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/AGENTS.md) support scoped edge/skill/plugin approaches, but do not delegate provider credentials, policy, user consent or cross-profile configuration mutations. Existing fork Issues disabled at source review. No external/fork public Issue or PR publication was approved; plan artifacts are internal OpenSiro metadata on a public branch, not original-facing communication.

## Existing work / overlap

| Grounded original source at 2de9f51b8008 | Coverage / boundary |
| --- | --- |
| [models.dev status and cached registry](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/agent/models_dev.py) | `status`, release date, costs, capabilities; may be stale/missing, not proof of imminent retirement or an autonomous chooser |
| [model and fallback user guide](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/user-guide/features/fallback-providers.md) | Manual `hermes model` and ordered fallback, static/live route checks; reactive failure recovery, not independently prospective intelligence |
| [Cron guide](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/user-guide/features/cron.md) + [scheduler](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/cron/scheduler.py) | User-configured recurring/isolated agent runs; a timed prompt is not automatically S4 |
| [Kanban tutorial](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/user-guide/features/kanban-tutorial.md) + [tools](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/tools/kanban_tools.py) | First-party state, dependencies, comments, configured management/orchestrator, review and run outcomes; prospective S4↔S3 bridge still to be built and proven |
| [observer hooks](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/website/docs/developer-guide/observer-hooks.md) | Request/error/turn correlation, mostly read-only; not a credential-owning/route-mutation permission |
| [#5452](https://github.com/NousResearch/hermes-agent/issues/5452), [#5437](https://github.com/NousResearch/hermes-agent/issues/5437) | OPEN advisory deprecation and compatibility preflight requests, not a blanket maintainer rejection or future strategy controller |
| [PR #26297](https://github.com/NousResearch/hermes-agent/pull/26297), [PR #115486](https://github.com/NousResearch/hermes-agent/pull/115486) | OPEN/UNMERGED deprecation redirection and opt-in route policy; heads/diffs read; no shipped equivalence credited |
| [#150930](https://github.com/NousResearch/hermes-agent/issues/150930), [#158207](https://github.com/NousResearch/hermes-agent/issues/158207) | OPEN requests for credential-isolated model switch / per-turn routing extension; any implementation must respect these unresolved seams |

Competing original-native baseline: status warning from #5452, manual choice via `hermes model`, `hermes fallback check` and approved operator changes, with no new autonomous future loop. It already addresses the narrow warning task; this **does not** veto a different C constructor. No shipped `S4=C` or whole-repo current reassessment is claimed.

## Function ownership

- S1: each running profile and Kanban worker performs operational tasks.
- S2: room handoffs, assignments and dependencies address interference without becoming strategic intelligence.
- S3: configured board orchestrator and owner decide current admitted commitments; accept/defer/reject a future route proposal and own any authorized next-session config transition.
- S3*: the separate review path may scrutinize outcomes; it cannot substitute for S4 learning or inherit policy power.
- S4: only the **proposed independent profile** would read external and prospective changes, autonomously compare alternatives/hold and amend its next outlook based on S3 feedback. A catalog updater or cron script alone is not S4.
- S5: owner keeps policy/identity/credential and provider allowlist authority; no new S5 grant. The system boundary includes configured first-party construction, not external provider operations or unpublished plugins.

## Parallel contribution-on-top review

- Track A: evaluate shipped manual picker, fallback/error recovery, cached external catalog, configured Cron and Kanban, issue #5452 and open PR #26297; both source and intended scope inspected without presuming permanent maintainer intent.
- Track B: option A reuse warning/manual path unchanged (no new S4); option B compose Cron/skill + dedicated S4 profile + Kanban S3 two-way link (bounded C hypothesis); option C duplicate automated redirect #26297 (not prospective S4); option D add plugin hooks without concrete consumer (not warranted by [AGENTS](https://github.com/NousResearch/hermes-agent/blob/2de9f51b8008a7d49a49221c184f2f11cbfc4af1/AGENTS.md)).
- Evidence gate: a C label requires independent authorizable decision owner, external future signal, options/hold, S3 decision effect and subsequent observed outcome returned to the same S4 actor; warn/digest/retry alone fail.
- On-top result: `GO / NEEDS_EVIDENCE` **at proposal stage**. The cheapest native alternative and its right to be preferred by maintainers remain explicit.

## Capability priority

P0: S4 `— → C` **GO** for bounded source-native constructibility, **NEEDS_EVIDENCE**, `PLAN_ONLY / HYPOTHETICAL`. P1: only source-specific auth/config/routing/feedback validation; no product issue or implementation is admitted. P2: NONE.

**Historical comparison, AFTER sealed independent verdict:** The same [2026-11-18 case at immutable fork meta](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md) records `NO_GO / DECISION_READY`, primarily because an *incremental product benefit* over catalogs/manual warnings was not demonstrated. The published Upstream v0.18.0 neutrality contract evaluates architectural C constructibility **separately** from product usefulness; the bounded current result is thus `GO / NEEDS_EVIDENCE`, **changed** from historical NO_GO without rewriting its Git provenance. The separately persisted [Hermes strategic-feedback S4 case](https://github.com/opensiro-contributions/hermes-agent/blob/c8e467899e7abbbaa4dcc2321835b81b2d571b57/.opensiro/issues/hermes-strategic-feedback-s4-20261119/roadmap.md) concerns general external strategy signals, not this provider/model-lifecycle object, and is untouched.

## Implementation options

1. Retain native picker/catalog/fallback and implement only owner-selected advisory: zero newly asserted S4 functionality.
2. Optional first-party opt-in profile/skill or standalone plugin with scheduled external lifecycle watcher; source-attributed `retain / prepare / hold` decisions, versioned Kanban proposal for human/manager; next-session route remains owner-authorized, with logged later outcomes and readback to S4. Use public plugin APIs only; do not mutate running context, borrow auth, override manual pins or violate parent scope.
3. If native first-party hooks lack the necessary bidirectional/credential-safe seam, label this **needs validation/limited generic extension**, not already implemented. An incompatible or forbidden route must yield `hold`, not a silent switch.

## Post-v0.18.1 Hermes-native refinement — same proposal, not an additional run

**Source freshness and scope.** This is an attributed continuation of the already completed Wave 4 first-pass at [original `2de9f51b8008a7d49a49221c184f2f11cbfc4af1`](https://github.com/NousResearch/hermes-agent/commit/2de9f51b8008a7d49a49221c184f2f11cbfc4af1), **not** an independent first attempt or a newly accepted Index grade. Current original [`main@f998a982cb8be2ac46b062d49996e8116b5171f7`](https://github.com/NousResearch/hermes-agent/commit/f998a982cb8be2ac46b062d49996e8116b5171f7) is five commits ahead; the [exact compare](https://github.com/NousResearch/hermes-agent/compare/2de9f51b8008a7d49a49221c184f2f11cbfc4af1...f998a982cb8be2ac46b062d49996e8116b5171f7) changes catalog-plugin import compatibility CI, plugin developer documentation and guards but not the model metadata, fallback, Cron, Kanban or existing skill implementation files underpinning this proposal. Current Index main `62fc6b9d2a1ed1292d588ca607bc46f8565f9abf` still reports the identical `included` Hermes assessment blob `23b9c8ccc3dd063a03d15c96eee2bf8359ee2377` and catalog `review_ref=16bddc88dd325c5eef27c2cc71bbb14c16b870aa`. Upstream patch v0.18.1 main `ae7a8a6d32b4da1c5fd97c6862821460503bf9e2` adds only a *nonbinding* recommendation for native-specific proposals, not a new gate. The frozen Wave 4 source pin above remains the actual first-pass provenance.

### Concrete first-party components, minimum proposed edit and authority

| Native Hermes surface | Shipped capability / precise proposed use |
| --- | --- |
| [`agent/models_dev.py`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/agent/models_dev.py) | `ModelInfo.status`, `release_date`, modalities and cost data from an ETag/TTL/stale-capable registry; source is an *indicator*, not an authoritative sunset date. Require dated **official provider notice** for claimed future retirement; use explicit `provider:model` identity |
| [`hermes_cli/models_validate.py`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/hermes_cli/models_validate.py), [fallback guide](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/website/docs/user-guide/features/fallback-providers.md) | Preserve explicit user-selected model ID, including valid models missing from catalog. `hermes fallback check [--live --json]` validates the **configured fallback chain only**, not arbitrary proposed models; it does not authorize a route change |
| [`skills/research/competitor-news-monitor/SKILL.md`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/skills/research/competitor-news-monitor/SKILL.md), [`cron/blueprint_catalog.py`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/cron/blueprint_catalog.py) | Reuse the shipped stateful watch/primary-source/cutoff pattern and Cron blueprint machinery, **not** the company-news skill as if it already supported exact model sunsets |
| [`cron/scheduler.py`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/cron/scheduler.py), [Cron guide](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/website/docs/user-guide/features/cron.md) and [cron isolation tests](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/tests/cron/test_cron_profile_isolation.py) | Configure a named `model-watch` profile with its **own** scheduled Cron task and its own profile-scoped watch contract; no shared-root job and no background coordinator daemon |
| [`tools/kanban_tools_schemas.py`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/tools/kanban_tools_schemas.py) | A `kanban`-enabled configured model-watch profile invokes `kanban_create(title, assignee=<configured-S3-profile>, body=<source/options/hold>, idempotency_key=<stable-provider-model-event>)`. The returned real task ID is stored under the watch's own state; no invented task ID |
| [`kanban_show` and `kanban_comment` schemas](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/tools/kanban_tools_schemas.py), [Kanban tutorial](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/website/docs/user-guide/features/kanban-tutorial.md) | The S3 owner makes or records `accept / defer / reject` on the concrete task; an actual permitted follow-up task is run by its assigned profile, then the S4 watcher reads **that task's** status, comments and run attempts on the next Cron tick. No generic global route override or inferred S5 delegation |
| [`AGENTS.md`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/AGENTS.md) and [`CONTRIBUTING.md`](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/CONTRIBUTING.md) | Preserve per-conversation prompt caching, explicit operator model selection, secret isolation and skill/plugin-first contribution placement. A new model-switch core hook or service is **not** the default proposal |

**Minimum on-top change (PLAN_ONLY, not implemented):** one opt-in first-party procedure at proposed **new** `skills/research/model-lifecycle-watch/SKILL.md` describing watch setup, explicit provider/model allowlist, exact cited official sources, monotonic cutoff/dedup, `retain | prepare | hold` alternatives, `kanban_create` idempotent handoff, `kanban_show` feedback, and fail-closed conditions. It composes **existing** named profiles + Cron + Kanban without adding a new agent runtime, core provider route or separate Upstream reporting system. An additional code/blueprint/plugin interface is *not assumed necessary*; if the focused native acceptance test reveals a missing permitted return/effect seam, document the smallest generic extension needed and keep `NEEDS_EVIDENCE`, rather than claiming it already exists. The watcher itself is the autonomous S4 actor; the S3 orchestrator or human retains all authority to select a permitted future-session model route.

**Concrete operating example:** official provider announces retirement of a provider-qualified model used by one Hermes named profile. A scheduled watch tick confirms the announcement date and exact model identity, checks current capabilities and authorized alternatives, and autonomously chooses `prepare` or `hold` with source-linked uncertainty. It writes one idempotent Kanban decision card to an explicitly configured S3 assignee. S3 can reject, defer or approve a bounded *separate* validation run; only the owner may actually change future-session route defaults using Hermes' supported model/config surfaces. The next watch tick consumes the real card's decision and validation-run outcome before changing its next option. **No model is migrated solely from an HTTP 404, missing catalog row, or LLM guess.**

### Specific falsifier and next evidence (not tests already passed)

1. **No false deprecation:** stale `models.dev`, offline official sources, wrong provider identity, valid unlisted/preview models and no dated notice produce `UNKNOWN / HOLD`, never forced provider migration.
2. **S4 autonomy:** two independent future choices (`retain/prepare/hold`) from the same sourced scenario; without the configured S4 profile, neither the existing catalog nor fallback performs this proactive decision.
3. **Native board write:** one `kanban_create` with real idempotency key deduplicates retries; assignee authority and profile/board tenant are checked. An S3 refusal does not become an accepted routing change.
4. **Return evidence:** `kanban_show(task_id)` on a later scheduled tick observes the actual S3 comment and a completed/failed **real assigned validation run**, not a conjectured provider success; S4 updates its next selection. Merely seeing a new card is not a two-way S4↔S3 witness.
5. **No unauthorized side effect:** disabled profile, missing `kanban` toolset, disallowed provider, wrong profile scope, revoked authority, manual model pin and active cached conversation leave routes and credentials untouched. The existing profile-scoped [Cron](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/tests/cron/test_cron_profile_isolation.py) and [Kanban](https://github.com/NousResearch/hermes-agent/blob/f998a982cb8be2ac46b062d49996e8116b5171f7/tests/tools/test_kanban_tools.py) tests are relevant starting points, not substitutes for proposed end-to-end proof.
6. **Simplest native counterfactual:** `hermes model` + catalog/status warning + manual decision and existing fallback check. Compare under the same dated retirement and profile scenario. Whether maintainers prefer this baseline is **outside** the C-constructibility verdict.

**Post-patch conclusion: `GO / NEEDS_EVIDENCE` retained** for the *hypothetical* opt-in configurable S4 decision-and-return constructor, because the concrete Hermes native ports support a coherent design and no shipped first-party path was found that already independently closes this *same* S4 ownership/effect/feedback loop. This does **not** assert that a new skill alone has been tested or that a future C grade is deserved. P0 unchanged; P1 is precisely the profile/board/feedback native acceptance above; P2 none. Native product tests `NOT_RUN`, costs and operator benefits `NOT_MEASURED`, original product adoption **reserved to maintainers**, third-party publication `NOT_PUBLISHED`. Archived internal status [PR #83](https://github.com/opensiro/upstream/pull/83) is CLOSED_UNMERGED and navigable only from [Supplementary](https://github.com/opensiro/upstream/blob/main/docs/ROADMAP_REPORT.md#supplementary); no new Upstream PR or per-run report is created.

## Specification and domain alternatives

No evidence demands changed Profile/Skills definitions or a whole-system S5 reconstruction. Another original-native feature design or a standalone plugin may be product-preferred; selection belongs to the maintainer and does not negate the separate architectural feasibility hypothesis. No user-facing public request published.

## Cost experiment

`NOT_MEASURED`: compare identical verified impending model deprecation, permitted profiles and next-session routes under (A) current catalog warning + manual selection and (B) S4 profile option+feedback. Include implementation/review/test effort, credential and provider expenses, operator decisions, failed transitions, ongoing maintenance and actual later successful task outcomes. No savings, performance or utility preference claimed.

## Delivery and publication

Human [issue.md](issue.md), AI [constructor-sufficiency.md](constructor-sufficiency.md), and canonical [roadmap.md](roadmap.md) share this Wave 4 `S4=— -> S4=C` proposal verdict; historical Git commit c8e467899e7abbbaa4dcc2321835b81b2d571b57 remains a frozen NO_GO reference. Native tests **NOT_RUN**; validation here structural only. External original Issue/PR, fork public Issue/PR and release **NOT PUBLISHED**. Internal queue coordination: [Upstream #58](https://github.com/opensiro/upstream/issues/58). Next permissible work is the source-native bounded acceptance proof under a separately authorized implementation request; no automatic adoption.

## 2026-11-24 — external-proposal reconciliation (same case, incomplete)

- Publication review status: ROADMAP_NOT_READY_FOR_EXTERNAL_PROPOSAL
- Observed original source HEAD: 4c84e78629cf1cdfcb79bea3b39aa4a49003c829
- Observed UTC date: 2026-11-24
- Candidate route: original_issue_comment, not a new Issue
- Candidate existing Issue: https://github.com/NousResearch/hermes-agent/issues/5452
- Publication review outcome: BLOCKED — incomplete bounded history and no demonstrated incremental product utility. No approval requested.

This is an owner-directed in-place continuation, not a new assessment or independent research pass. The accepted Index blob remains 23b9c8ccc3dd063a03d15c96eee2bf8359ee2377; current catalog blob a1c757bbca63620cf3edcd583deaa24da6f88347 retains review_ref 16bddc88dd325c5eef27c2cc71bbb14c16b870aa. Historical source, GO / NEEDS_EVIDENCE, target and grades remain unchanged. Upstream persistence gate is now effective at 3c8cb344681a96f3acf57ee9331034d05bb82841 (PR #111).

### New native evidence and disposition

- [#5452](https://github.com/NousResearch/hermes-agent/issues/5452): OPEN, created 2026-04-06T07:18:17Z (232 calendar days), updated 2026-05-01T02:35:24Z (207 days), no comments, labels type/feature, comp/agent, P3; full body re-read. Requests only advisory models.dev deprecated status warning at preflight/init; it does not request a new strategic controller. Reuse its discussion only if an additive concrete contribution is justified. Prior #5443 was closed unmerged, and #26297 and #139455 were open unmerged at earlier readback; do not credit as shipped. PR #139455 already describes a temporary read-only watchdog and future periodic lifecycle refresh; PR #142953 proposes catalog-based doctor checks. PR #29277 merged xAI-specific warnings/migration; current source corroborates [xAI retirement implementation](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/hermes_cli/xai_retirement.py). Full fresh overlap reconciliation is not complete; historical observations are not a claim of current exhaustive status. No new Issue justified at this checkpoint.
- [Optional watchers Skill](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/optional-skills/devops/watchers/SKILL.md) already provides recurring RSS, GitHub and JSON polling, deduplicated watermark, bounded state and Cron integration. Do not propose another monitoring mechanism. [Competitor monitor](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/skills/research/competitor-news-monitor/SKILL.md) supplies source hierarchy, freshness/cutoff, significance, and dedup pattern. [Community model-drift-watch catalog entry](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/plugin-catalog/model-drift-watch.yaml) describes quality drift measurement/alerts with explicit costs; not evidence of installed first-party prospective retirement decision closure. Plugin internals not assessed.
- [Cron](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/website/docs/user-guide/features/cron.md), [models.dev metadata](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/agent/models_dev.py), [Kanban tools](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/tools/kanban_tools_schemas.py) and [fallback checks](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/website/docs/user-guide/features/fallback-providers.md) re-read at this pin. Catalog absence/stale status is not proof of sunset. Fallback check only checks configured entries. Existing scheduled profiles, skill-backed jobs and idempotent cards are sufficient seams for a user-configured experiment. Reuse existing watchers, not a duplicate detector; prefer a recipe/user-authored skill or Hub if ordinary native composition suffices. The only remaining hypothetical delta is a prospective retain/prepare/hold choice by a configured watch profile, one card to the authorized management owner, and actual later validation outcome returned to the watch profile. No measured utility, need for a new bundled skill, or new S4 grade is demonstrated.
- [Contributor policy](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/CONTRIBUTING.md) favors skill over tool, optional/Hub for niche workflows, and reviewing existing PRs over competing duplicates. [Skill policy](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/skills/AGENTS.md) requires human-first attribution for future skill contribution; no implementation or signoff here. MIT, exact fork parent verified, owner ACTIVE/ALLOW as of observed meta 36bf948e61e784787cc925adf080b0958070b629.
- [Source compare](https://github.com/NousResearch/hermes-agent/compare/8545feeb1a53fc73375dfa98cf65cafadba66bf0...4c84e78629cf1cdfcb79bea3b39aa4a49003c829) 14 commits ahead, 0 behind at observed pin; mostly gateway/environment/dashboard changes, not the pinned core seams above. The exact source pin is an observation, not assurance of later freshness.

### Blocked publication preflight

Scoped discovery using current Upstream main, candidate existing Issue title `Model deprecation / sunset warnings`, action original_issue_comment, exact #5452 destination, returned HISTORY_UNVERIFIED / ROADMAP_NOT_READY_FOR_EXTERNAL_PROPOSAL (exit 1). Provider returned HTTP 403 for pinned fork roadmap read, archive HEAD and original discussion availability; native PR query `deprecation warnings` was truncated. Report had 128 returned search candidates, not exhaustive; no review digest generated. Do not invent a digest or mark the required publication review fields resolved. The GitHub connector separately read the canonical case, but this does not replace the integrated live scan. New evidence includes existing monitoring and watchdog mechanisms; material overlap, full age-triggered re-review and a useful concrete comment still require reconciliation. No original-facing draft is ready. Next: recover live bounded history coverage, inspect material matches/related diffs and actual feedback, verify a narrowly useful delta against native composition; if no delta, record no outreach. If a useful comment remains, persist exact current review/draft and pass all gates before showing the owner. This checkpoint does not grant any outward authority.
