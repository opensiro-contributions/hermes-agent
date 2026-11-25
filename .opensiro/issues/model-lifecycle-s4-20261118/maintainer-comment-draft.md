The proposed sunset warning could also serve as an input to an optional lifecycle workflow for long-running Hermes profiles, without introducing another model-deprecation detector.

A possible recipe using the existing [watchers skill](https://github.com/NousResearch/hermes-agent/blob/873e50b59c7abb34ea9b91ee55c56edd44fe4898/optional-skills/devops/watchers/SKILL.md), [Cron profile API](https://github.com/NousResearch/hermes-agent/blob/873e50b59c7abb34ea9b91ee55c56edd44fe4898/cron/plugin_api.py) and [Kanban tools](https://github.com/NousResearch/hermes-agent/blob/873e50b59c7abb34ea9b91ee55c56edd44fe4898/tools/kanban_tools_schemas.py):

- A separately configured watch profile checks dated provider notices for the exact provider/auth route and model. An absent or stale catalog entry alone is not evidence of retirement.
- Before the cutover, the profile compares three options: retain the current model, prepare a permitted alternative, or hold the decision for more evidence. It creates one deduplicated Kanban review card with the source, rationale and candidate options.
- The authorized operator or management profile decides whether to act. The watch profile reads the decision and the actual later validation result on its next run, and revises its recommendation accordingly. No automatic provider/model switch, credential change or paid upgrade.

This would complement the warning in this issue rather than compete with #5443, #26297, #139455 or #142953. It is a design hypothesis, not an implemented or benchmarked feature; existing native composition may already be sufficient.

Would documenting an opt-in recipe along these lines be useful, or would you prefer this to remain a user-authored skill/Skills Hub workflow? No core change is being requested at this stage.

*Context: OpenSiro VSM-informed architecture review; AI-assisted proposal draft.*
