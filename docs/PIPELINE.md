# DEGAS Pipeline

```
BRIEF → [SCHOOL] → DESIGN → PANEL → [INNOVATION] → [AMENDMENT] → HANDOFF
  ↑                                      |
  └──── revise brief or design ──────────┘
        (if gate FAIL or ADVISORY)
```

## Stages

| Stage | Skill | Output | Gate |
|-------|-------|--------|------|
| 1. Brief | `degas-brief` | `works/NNNN-slug/brief.md` | Open questions resolved? |
| 1b. School | `degas-school` | `schools/<slug>.md` | School grammar documented? |
| 2. Design | `degas-design` | `works/NNNN-slug/design.md` | Design matches brief? |
| 3. Panel | `degas-panel` | `works/NNNN-slug/panel/` | Score ≥ 60? |
| 3b. Innovation | `degas-innovation` | entries in `scoring/INNOVATIONS.md` | Cluster formed? |
| 3c. Amendment | `degas-amendment` | updated `scoring/RUBRIC.md` | 2+ works, 2+ innovations? |
| 4. Handoff | `degas-handoff` | `docs/handoff/YYYY-MM-DD-*.md` | Always |

## Gate Thresholds

- **PASS**: aggregate score ≥ 60 — work is complete
- **ADVISORY**: 50-59 — work is provisionally complete with identified weaknesses; designer may proceed or revise
- **FAIL**: < 50 — work requires revision before archiving

## Revision Loop

If gate ADVISORY or FAIL:
1. Read panel SUMMARY for specific recommendations
2. Revise `design.md` (or `brief.md` if the problem is upstream)
3. Run panel again (increment review round: R1, R2, ...)
4. Gate applies to revised design
