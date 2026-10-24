# brands/ routing and index

Written 24 Oct 2026. One folder per brand. Sizes are bytes.

| Task | Read | Skip | Use |
|---|---|---|---|
| Add a brand from a URL | `_template/profile.md`, `TOKENS-SCHEMA.md` | every other brand folder | `../scripts/ingest-url.py` |
| Run the intake interview | `INTAKE-SCHEMA.md` | `databrill-core/` moodboard assets | `/intake` skill, `../.claude/skills/intake/SKILL.md` |
| Lock a brand's fields | `<slug>/tokens.json`, `LOCKS-SCHEMA.md` | other brands | `/lock` skill, `../.claude/skills/lock/SKILL.md` |
| Check where a brand is | `INVENTORY.md` | everything else | none |

Every row: a brand folder is the source of truth for that brand. Nothing downstream edits a locked field.

| Entry | Files | Bytes | Last changed | Holds |
|---|---|---|---|---|
| `_template/` | 2 | 2,296 | 2026-04-27 | profile and tokens templates; copy to start a brand |
| `retechuk/` | 6 | 2,740,029 | 2026-04-27 | Re Tech UK, full set incl. locks and intake |
| `databrill-core/` | 320 | 38,914,365 | 2026-04-27 | Databrill Core, profile and tokens plus moodboard and logo assets |
| `databrill-core-extracted/` | 5 | 483,291 | 2026-04-27 | the same brand as the cascade read it |
| `databrill/` | 2 | 8,473 | 2026-04-27 | parent Databrill brand |
| `claude-ui-workflow/` | 3 | 1,816 | 2026-04-27 | this repo's own brand |
| `INVENTORY.md` | 1 | 4,883 | 2026-04-27 | status per brand |
| `TOKENS-SCHEMA.md` | 1 | 6,069 | 2026-04-27 | what tokens.json must contain |
| `LOCKS-SCHEMA.md` | 1 | 11,117 | 2026-04-27 | what locks.json must contain |
| `INTAKE-SCHEMA.md` | 1 | 6,520 | 2026-04-27 | what intake.json must contain |
| `REF-IMAGE-REPORT-SCHEMA.md` | 1 | 5,911 | 2026-04-27 | reference image report shape |
