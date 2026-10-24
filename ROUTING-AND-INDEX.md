# Routing and index, read first

Written 24 Oct 2026 by the Jake folder system. Pointers only, no instructions. Three workspaces produce work; everything else is reference. Index regenerated 2026-10-24. Sizes are bytes; FLAG marks a file over 12,000, so open the named section, not the whole file.

## Which workspace for which work

| Work | Go to | Then read |
|---|---|---|
| Add, ingest or lock a brand | `brands/` | `brands/ROUTING-AND-INDEX.md` |
| Run a cycle, audit a page, write a retro, pick up the last session | `dogfood/` | `dogfood/ROUTING-AND-INDEX.md` |
| Fix or extend a script, add a design rule | `scripts/` | `scripts/ROUTING-AND-INDEX.md` |
| Refresh the README | root | `README.md`, with danny-readme-builder |
| Anything about the private companion folder | `../Claude-UI-Workflow_private/` | parked by the operator, 24 Oct 2026; nothing routed there yet |

## Folders

| Folder | Kind | Files | Bytes | Open when |
|---|---|---|---|---|
| `brands/` | Workspace | 343 | 42,184,770 | adding, ingesting or locking a brand |
| `dogfood/` | Workspace | 52 | 15,049,895 | running a cycle, auditing a page, writing a retro |
| `scripts/` | Workspace | 8 | 127,209 | fixing or extending a script |
| `design-db/` | Reference | 15 | 61,216 | adding or changing one rule; open one CSV |
| `design-system-sections/` | Reference | 8 | 61,760 | the reasoning behind a design decision |
| `examples/` | Reference | 10 | 1,444,222 | judging raw Stitch output |
| `records/` | Reference | 2 | 8,671 | the two inspiration transcripts |
| `reference/` | Reference | 3 | 34,908 | Stitch and Claude Design source notes |
| `deploy/` | Reference, read only | 12 | 84,372 | the three shipped Netlify pages |
| `_ui-mockup/` | Reference | 7 | 105,664 | the six-page local HUD mockup, open index.html |
| `assets/` | Reference | 4 | 31,560 | README logos and poster |
| `_captures/` | Local only | 33 | 4,868,465 | browser captures, ignored by git |
| `_archive/` | Local only | 27 | 6,454,487 | retired files, ignored by git; never pushed |
| `.claude/skills/` | Reference | 2 | 18,786 | the /intake and /lock skill manifests |

## Root documents

| File | Bytes | Last changed | Open when |
|---|---|---|---|
| `PRD.md` | 9,074 | 2026-04-27 | the goal; read first on any new piece of work |
| `RUNBOOK.md` | 5,489 | 2026-04-27 | what runs today; second |
| `PRE-CHECK-CHECKLISTS.md` | 16,912 FLAG | 2026-04-27 | per-stage checks; open the one stage's section |
| `STITCH-MODEL-RULES.md` | 9,464 | 2026-04-27 | before any Stitch generation |
| `DESIGN-PIPELINE-VISUAL.md` | 22,231 FLAG | 2026-04-27 | when changing the architecture |
| `MASTER-LOG.md` | 169,270 FLAG | 2026-10-24 | kickoff prompt and latest session only |
| `OUTSTANDING-WORK.md` | 14,567 FLAG | 2026-10-24 | before starting a branch of work; April list, see its note |
| `README.md` | 42,564 FLAG | 2026-10-24 | the public front page; refresh with danny-readme-builder |
| `STAGE-CMD.md` | 1,159 | 2026-05-09 | on-stage cue card, May 2026 event |
| `Design System Workflow Ideas.md` | 9,918 | 2026-04-27 | idea note, read only |
| `Google Stitch-10 ideas for amazon sellers.md` | 18,852 FLAG | 2026-04-27 | idea note, read only |

## Naming rules

- `brands/<slug>/`: lower case, hyphens, no spaces. Fixed filenames inside: `profile.md`, `tokens.json`, `locks.json`, `intake.json`, `ingestion-confidence.md`.
- `dogfood/YYYY-MM-DD-<slug>/`: one folder per cycle run, dated on the day it started.
- `_captures/<feature>/`: every screenshot or browser capture. Never at the root.
- `design-system-sections/NN-slug.md` and `records/YYYY-MM-DD-slug.md`.
- Page snapshots and scratch notes do not live at the root. Finished with: `_archive/<group>-YYYY-MM-DD/`.
