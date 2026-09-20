---
description: Create, plan, launch, update or conclude a GTM experiment
argument-hint: [EXP-id | new idea]
---

Run **Experiment** as defined in CLAUDE.md §7. Target: `$ARGUMENTS` (if empty, ask whether to create a new experiment or update an existing one and list current ones from `index.md`).

New: ask one question at a time (hypothesis, audience, channel, metric, success and kill thresholds, time box, effort), then draft from `_templates/experiment.md`. Never set `running` without my explicit go-ahead. When concluding, ask me for the real numbers; never estimate. Propose a decision (`scale | iterate | kill`) and wait for my confirmation. Update `index.md` (Experiments table) and `log.md` in the same turn.
