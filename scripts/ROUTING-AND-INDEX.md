# scripts/ routing and index

Written 24 Oct 2026. Eight scripts. Sizes are bytes; FLAG marks over 12,000, so read one script at a time.

| Task | Read | Skip | Use |
|---|---|---|---|
| Fix or extend a script | that one script, `../RUNBOOK.md` | the other seven scripts | none |
| Add or change a design rule | the one CSV in `../design-db/` | the other fourteen CSVs | hand to `../design-db/`, reference folder |

Every row: `../package.json` maps six scripts to `npm run` names; `audit-copy.py` and `ref-image-check.py` run directly.

| File | Bytes | Last changed | Does |
|---|---|---|---|
| `audit-copy.py` | 9,635 | 2026-04-27 | Stage 8 hard-fail audit; standard library only |
| `ingest-url.py` | 25,647 FLAG | 2026-04-27 | Stage 2, URL to brand folder |
| `ingest-doc.py` | 21,111 FLAG | 2026-04-27 | Stage 2, style guide document to brand folder |
| `refine-from-screenshot.py` | 22,283 FLAG | 2026-04-27 | Stage 3, screenshot overrides |
| `extract-brand.mjs` | 24,132 FLAG | 2026-04-27 | Playwright extraction used by ingest-url |
| `emit-tokens.py` | 5,630 | 2026-04-27 | write tokens from a profile |
| `compare-tokens.py` | 4,347 | 2026-04-27 | diff two tokens.json |
| `ref-image-check.py` | 14,424 FLAG | 2026-04-27 | reference image report |
