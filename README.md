# Brain — GTM & Ops Wiki

A self-maintaining knowledge base for **how an early-stage team finds and wins customers, and how it runs day to day**: market and competitor research, ICP hypotheses, GTM experiments and their results, operating procedures, tools and message templates. You feed it messy sources and questions; a Claude Code agent researches, integrates and keeps a clean, cross-linked, cited wiki.

> Not a document dump you search through. Every new source or research run is *integrated* into existing pages. Guesses are labelled, gaps are flagged, and nothing is invented.

## How it works

```
 raw/inbox/ or the web ──►  Claude researches & integrates  ──►  knowledge/
 (notes, transcripts,          (/research, /ingest, /capture)      research · experiments · SOPs
  public sources)                                                  tools · templates · concepts
                                                                        ▲
                       /experiment, /weekly-brief, /ask, /review, /lint ┘
```

| Layer | What it is | Who touches it |
|---|---|---|
| `raw/` | Original material and saved web snapshots | You drop files in; never edited |
| `knowledge/` | Clean pages written and maintained by the AI | AI writes, you read & approve |
| `CLAUDE.md` | The rulebook the AI follows | You and the AI evolve it together |

## Quick start

1. Install [Claude Code](https://claude.com/claude-code) and open a terminal **in this folder**: `cd Brain && claude`
2. (Optional) Open the folder as a vault in [Obsidian](https://obsidian.md) for backlinks and graph view.
3. Run `/setup` for a short interview that fills in `knowledge/company.md`.
4. Run `/research <company or market>` to get a cited brief with proposed experiments.
5. Run `/experiment` to turn an idea into a tracked experiment with a hypothesis, metric and kill threshold.
6. Run `/weekly-brief` on Fridays for a one-page update.

## Commands

| Command | Use it when… |
|---|---|
| `/setup` | First time only. Describe the company, ICP, channels and tools. |
| `/research <target>` | You need a market, competitor, segment or account brief from public sources. |
| `/experiment [id or idea]` | Create, launch, update or conclude a GTM experiment. |
| `/weekly-brief` | You need a one-page status update from what changed this week. |
| `/ingest [file]` | You have notes, a transcript or a doc to add. |
| `/capture [topic]` | A process only exists in someone's head; Claude interviews you and drafts the SOP. |
| `/ask <question>` | "What have we tried?", "What do we know about X?", "How do we…?" Answers cite pages. |
| `/review` | Approve drafts, close experiments, refresh stale research. **Weekly.** |
| `/lint` | Health check: broken links, stale pages, contradictions. **Monthly.** |

## Trust rules

- **No invented facts.** Missing information is marked `[!gap]`; disagreements are `[!conflict]`; guesses are `[!inference]`.
- **Every claim cites a source**, and web research is saved as a raw snapshot first.
- **Only a human** promotes an SOP to `active` or launches an experiment.
- **Experiment results are real numbers only.** Sample content is always labelled `sample`.
- **Public information only** for company research. No personal contact data, secrets or keys in the wiki.

## Folder guide

```
CLAUDE.md   index.md   log.md   README.md
_templates/     page skeletons (SOP, experiment, research, source, entity)
raw/inbox/      drop new sources here
raw/processed/  ingested sources and web snapshots (filed by month)
knowledge/           company.md · research/ · experiments/ · sops/ · tools/ · templates/ · concepts/ · syntheses/ · sources/
```

Start at [`index.md`](index.md). See what changed lately in [`log.md`](log.md).
