# Hermes Agent — source-native S4 construction technical contract

Canonical storage: opensiro-contributions/hermes-agent@opensiro/meta, model-lifecycle-s4-20261118.
[issue.md](issue.md) · [roadmap.md](roadmap.md).
**DRAFT — NOT PUBLISHED**; PLAN_ONLY; native tests NOT_RUN; no grade change.

## 1. Function-specific construction boundary and methodology checks

**Source and mode boundary:** Original main 4c84e78629cf1cdfcb79bea3b39aa4a49003c829, observed 2026-11-24; targeted freshness review of [Cron](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/website/docs/user-guide/features/cron.md), [model metadata](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/agent/models_dev.py), [Kanban schemas](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/tools/kanban_tools_schemas.py), [fallback checks](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/website/docs/user-guide/features/fallback-providers.md), [skill rules](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/skills/AGENTS.md) and [contributing](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/CONTRIBUTING.md). Historical whole-function review and first-pass source pin retained in [roadmap.md](roadmap.md); original detailed technical artifact [immutable historical copy](https://github.com/opensiro-contributions/hermes-agent/blob/36bf948e61e784787cc925adf080b0958070b629/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md). Installed configured profiles, Cron and Kanban, not external provider operation or maintainer governance.
**Target transition:** S4=— -> S4=C
**Six-function dependencies (S1/S2/S3/S3*/S4/S5):** Profile operations and existing coordination carry work; configured current owner accepts/defer/rejects card; separate audit stays independent; new optional prospective profile owns future comparison; parent owns provider, credential and policy envelope.
**Function witness:** Dated future retirement creates external variety; watcher chooses retain/prepare/hold inside allowed routes, sends one decision card to lawful current owner; actual authorized later result returns to the watcher and changes next choice.
**Counterfactual owner test:** Without the watcher, existing Cron transport, catalog and Kanban remain; no separately configured actor is evidenced to own the exact prospective selection-and-return workflow. A simple existing configured workflow that achieves it is a valid negative control.
**Possible methodological negative control:** User manual decision with existing warning/fallback is legitimate; missing local S4 does not imply defect.
**Contributor / maintainer priorities:** Current source recommends capability at edges, Skill before tool, optional/Hub for niche workflows; preference on exact proposal NOT_STATED.

## 2. Source-pinned baseline and parallel native Track A / on-top Track B

**Original native workflow:** Skill-backed Cron runs an isolated agent with configured toolset; model metadata can be stale; configured Kanban tools create/read tasks including attempts; fallback check examines configured entries, optional live probe.
**Closest existing solution:** Native fallback/manual picker and user-authored scheduled prompt reusing [optional watchers](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/optional-skills/devops/watchers/SKILL.md); community [model drift catalog](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/plugin-catalog/model-drift-watch.yaml) addresses quality measurement, not evidenced first-party decision closure. No new detector or core.
**Relevant original Issues/PRs:** #5452 sunset warning OPEN (2026-04-06), #5437 capability preflight OPEN (2026-04-06) with #5443 triage reference; #26297 OPEN_PR head 5a77493a1975a193beed532fd906780c4bc5ac6b (reactive detection/redirect), #115486 OPEN_PR head aff55e7be7725b5253d004571dfeafbd127a5967 (opt-in policy at route resolution). #150930/#158207 discuss per-turn model switching/routing, not this Skill. Live body/state checked 2026-11-24; no full merged-equivalence or independent native execution claim. PR #139455 (temporary read-only watchdog and periodic refresh scope), #142953 (doctor catalog checks), #29277 (merged xAI-specific migration) provide additional overlap; #5452 full body re-read 2026-11-24, old (232 days), OPEN, zero comments. Not all related artifacts deeply revalidated today; see canonical receipt for blocked history and evidence limits. Historical evidence remains in receipt.
**On-top distinctness:** Explicit prospective source, versioned options, authorized decision and later observed feedback, not duplicate warning, catalog detector, per-turn hook or silent redirect.
**Source ambiguity / rights blockers:** Need exact provider/account model, official dates and permissions, actual profile and board toolset and correlation. CLI history/complete source overlap remains separate publication gate.

## 3. Minimal complete S4 first-party C construction

**Required property:** Developer can compose an autonomous prospective decision owner with lawful action options and attributable later operation feedback.
| Native seam | Existing behavior | Proposed composition and owner/effect/return |
| --- | --- | --- |
| [Cron](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/website/docs/user-guide/features/cron.md) and [skill example](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/skills/research/competitor-news-monitor/SKILL.md) | Configurable recurring agent job, isolated fresh session; tools explicit | Dedicated configured watcher Skill loads fresh official notices and profile-local state. Retain/prepare/hold. |
| [Model metadata](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/agent/models_dev.py) and [fallback check](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/website/docs/user-guide/features/fallback-providers.md) | Cached metadata and checks of configured entries | Dated external evidence and allowed options; no retirement inferred from absence, no probing unauthorized route. |
| [Kanban schemas](https://github.com/NousResearch/hermes-agent/blob/4c84e78629cf1cdfcb79bea3b39aa4a49003c829/tools/kanban_tools_schemas.py) | kanban_create with idempotency_key; kanban_show task state, attempts and comments | One source-linked decision card; lawful current owner accept/defer/reject and controls any next-session validation or change. Read actual later outcome into next watch tick. |

**Architectural C-sufficiency argument:** Native composition uses existing profile tools; a skill can specify the prospective loop without creating a new core API. If simple existing native prompt already gives equivalent reusable owned choice/feedback or the Skill cannot legitimately obtain later actual results, prefer reuse or stop. No deployed C proof.
**Explicit non-goals:** No new daemon, core route hook, automatic provider migration, credentials transfer, active-session edits, manual pin override, policy/identity transfer, or unrelated C targets.
**Implementation dependency graph:** Verify official source, profile/board authorization, exact options, idempotency, return correlation (P1) -> opt-in Skill and profile (P0) -> actual native validation.

## 4. Priorities, optional alternative and stopping rules

**P0 and P1:** As canonical roadmap receipt. Minimal proposed Skill plus configured existing runtime seams; verify opt-in, exact source, durable decision identity and authorized outcome.
**P2:** NONE.
**Alternative path:** Native fallback/manual picker + user-authored Cron; optional/Hub Skill if niche. Prefer if enough.
**Stop:** Equivalent native complete path, no distinct lawful actor, no supported feedback, violated parent/provider constraints, or unresolved indispensable source/authority. No forced publication.

## 5. Future source-native acceptance — derive tests, do not copy a matrix

**Native test commands and entry points:** NOT_RUN. Historical known entry points in [prior technical case](https://github.com/opensiro-contributions/hermes-agent/blob/36bf948e61e784787cc925adf080b0958070b629/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md) cover Cron isolation, Kanban tools, fallback; current repo contribution guide prescribes its actual test runner. Verify exact current test paths before implementation.
**Positive functional closure:** Synthetic dated model sunset, two permitted future alternatives; independent profile chooses, idempotent card is acted on, real authorized later validation result is correlated and alters next choice.
**Independent alternative (where applicable):** Same notice with different permitted constraint changes decision to retain or hold rather than hardcoded redirect.
**Negative authority and compatibility (where applicable):** Stale or unverified notice, disallowed provider, wrong profile, repeat tick, owner denies, current session pin, missing/failed outcome; no silent change or fictitious success.
**Matched native alternative:** Same inputs, warning/manual picker and native fallback check/user cron; compare observed choices, feedback and later task result, not just text.

## 6. Proposal verdict, falsification, evidence ownership and handoff

**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE
**Primary falsifier:** Shipped equivalent prospective actor with lawful downstream effect/feedback, simpler native workflow sufficient for actual user outcome, or no permissible feedback connection.
**Validation state:** NOT_RUN
**Ownership of truth:** Profile semantics, Skills classification, Index historical grade, original code/maintainer decision, canonical roadmap structured case; current source observation separate.
**Cost status:** NOT_MEASURED
**Next permitted action:** ROADMAP_NOT_READY_FOR_EXTERNAL_PROPOSAL. Restore bounded history (403/truncated PR search); consider native recipe or useful #5452 comment only after material overlap is reconciled. No owner-ready external draft; separate exact consent remains mandatory.
**Human backlink:** [issue.md](issue.md)
**case receipt:** [roadmap.md](roadmap.md)
**AI disclosure:** AI-assisted; no native tests or independent human validation, no external communication permission.

Historical detailed technical argument and previous test entry points remain at [prior pinned file](https://github.com/opensiro-contributions/hermes-agent/blob/36bf948e61e784787cc925adf080b0958070b629/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md); this template refresh does not claim a new independent research pass.
