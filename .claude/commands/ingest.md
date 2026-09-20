---
description: Ingest a raw source (default: oldest file in raw/inbox/) into the wiki
argument-hint: [path-to-source | "batch"]
---

Run **Ingest** exactly as defined in CLAUDE.md §7. Source: `$ARGUMENTS` (if empty, use the oldest file in `raw/inbox/`; if `batch`, process everything in the inbox with minimal discussion).

Reminders: supervised by default (takeaways → plan → wait for my go-ahead); never modify raw content; new SOPs start as `draft`; use `[!gap]` and `[!conflict]` instead of guessing; update `index.md` and `log.md` in the same turn; move the raw file to `raw/processed/YYYY-MM/`; finish with a short report of pages touched, open gaps/conflicts and suggested next steps.
