# Skill: degas-amendment

**Pipeline position:** Post-cluster (2+ innovations across 2+ works)  
**Produces:** new version of `scoring/RUBRIC.md`; entry in amendment history table

---

## Purpose

Ratify a rubric amendment from a cluster of innovations. A cluster is 2+ innovations that point at the same rubric gap across 2+ different works. The amendment tightens the rubric text so future works are scored more accurately on this dimension.

## Preconditions

- `scoring/INNOVATIONS.md` contains a cluster (2+ entries with matching technique/anchor across 2+ works)
- The cluster has been identified — either by `degas-innovation` reporting a match, or by manual review

## Procedure

1. **Read the cluster** in `scoring/INNOVATIONS.md`. Name the technique the cluster represents and the rubric dimension it affects.

2. **Assess the amendment:**
   - What does the current rubric text say about this dimension?
   - What does the cluster say the rubric should say?
   - Is the change an expansion (adding a new case the rubric didn't cover), a tightening (specifying an existing case more precisely), or a correction (fixing an anchor that is wrong)?

3. **Draft the amendment:**
   - Revise the affected dimension's anchor table
   - If a new anchor level is needed, add it
   - Write the changelog entry: "v1.X: [one-sentence description of change]; triggered by cluster [technique name] from works [NNNN, MMMM]"

4. **Bump the rubric version:** increment the minor version (v1.0 → v1.1). Major version changes (v1.X → v2.0) only for structural changes that alter scoring weights or dimensions.

5. **Update `scoring/RUBRIC.md`:**
   - Update the version header
   - Revise the affected dimension
   - Add the amendment to the amendment history table

6. **Update `TRACKER.md`:** note the new rubric version and date.

## Amendment History Format

```
| v1.X | YYYY-MM-DD | [technique-name] cluster (works NNNN, MMMM) | [one-sentence description] |
```

## Example Invocation

`/degas-amendment` — reads INNOVATIONS.md, identifies available clusters, proposes amendment text, awaits confirmation, then updates RUBRIC.md.
