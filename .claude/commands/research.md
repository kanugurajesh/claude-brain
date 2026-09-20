---
description: Build a cited market, competitor, segment or account brief from public sources
argument-hint: <company | market | segment>
---

Run **Research** as defined in CLAUDE.md §7. Subject: `$ARGUMENTS` (if empty, ask what to research and why).

Check the wiki first and update an existing brief rather than duplicating it. Use web search and fetch primary sources. Save a raw snapshot (URLs, access date, key excerpts) under `raw/processed/YYYY-MM/`, create its source page, then write the brief from `_templates/research.md`. Public information only; no personal contact data. Cite every claim, mark guesses with `[!inference]`, mark missing data with `[!gap]`, set `as_of` to today. Update `index.md` and `log.md` in the same turn. Finish with the "so what" in 3 bullets and offer up to 3 experiment ideas.
