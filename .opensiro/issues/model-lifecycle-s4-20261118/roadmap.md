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
- Proposed C construction: Developer opts into a separate Hermes profile + Cron/skill or plugin watching dated official provider lifecycle signals and catalog capabilities; that profile independently chooses retain/prepare/hold with two lawful alternative future routes, posts a source-linked versioned Kanban proposal to a configured S3 orchestrator, reads its accept/defer/reject and observed subsequent-session model/outcome back, and revises its future hypothesis. S3/parent alone authorizes effect on future sessions, never a silent active-session rewrite.
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

## Specification and domain alternatives

No evidence demands changed Profile/Skills definitions or a whole-system S5 reconstruction. Another original-native feature design or a standalone plugin may be product-preferred; selection belongs to the maintainer and does not negate the separate architectural feasibility hypothesis. No user-facing public request published.

## Cost experiment

`NOT_MEASURED`: compare identical verified impending model deprecation, permitted profiles and next-session routes under (A) current catalog warning + manual selection and (B) S4 profile option+feedback. Include implementation/review/test effort, credential and provider expenses, operator decisions, failed transitions, ongoing maintenance and actual later successful task outcomes. No savings, performance or utility preference claimed.

## Delivery and publication

Human [issue.md](issue.md), AI [constructor-sufficiency.md](constructor-sufficiency.md), and canonical [roadmap.md](roadmap.md) share this Wave 4 `S4=— -> S4=C` proposal verdict; historical Git commit c8e467899e7abbbaa4dcc2321835b81b2d571b57 remains a frozen NO_GO reference. Native tests **NOT_RUN**; validation here structural only. External original Issue/PR, fork public Issue/PR and release **NOT PUBLISHED**. Internal queue coordination: [Upstream #58](https://github.com/opensiro/upstream/issues/58). Next permissible work is the source-native bounded acceptance proof under a separately authorized implementation request; no automatic adoption.
