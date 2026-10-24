# dogfood/ routing and index

Written 24 Oct 2026. One folder per cycle run. Sizes are bytes.

| Task | Read | Skip | Use |
|---|---|---|---|
| Run a cycle on a brand | `../PRE-CHECK-CHECKLISTS.md`, the one stage's section; `../STITCH-MODEL-RULES.md` | older runs, `../deploy/` | `../scripts/audit-copy.py` at Stage 8 |
| Audit a rendered page | the run's `locks.json` and `source-truth.json` | the HTML; the script reads it | `../scripts/audit-copy.py` |
| Write the retro | the previous run's retro | `_captures/` | none |
| Pick up the last session | `../MASTER-LOG.md`, kickoff prompt and latest session only | the rest of the log | none |

Every row: a new run gets its own dated folder; nothing from the previous brand is copied in.

| Run | Files | Bytes | Last changed | Holds |
|---|---|---|---|---|
| `2026-04-25-retechuk/` | 19 | 11,261,677 | 2026-04-27 | cycle 1, friction log, 29 findings |
| `2026-04-26-databrill-core/` | 15 | 1,736,683 | 2026-04-27 | cycles 2 and 3, friction log, lock note |
| `2026-04-27-pushpullagency/` | 18 | 2,051,535 | 2026-04-27 | cycle 4, time log, retro, locked 28/30; the Test protocol sample |
