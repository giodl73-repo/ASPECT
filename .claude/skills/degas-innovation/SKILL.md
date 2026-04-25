# Skill: degas-innovation

**Pipeline position:** Post-panel, or during review  
**Produces:** entries in `scoring/INNOVATIONS.md`

---

## Purpose

Log structural innovations surfaced during panel reviews. An innovation is a technique the work deploys — or a critical failure that reveals a rubric gap — that the current rubric does not adequately name or score. Logged innovations cluster into amendment proposals.

## Preconditions

- A panel review has been completed (`works/NNNN-slug/panel/SUMMARY.md` exists)
- One or more reviewers flagged innovations or rubric gaps

## Procedure

1. **Read the panel SUMMARY** for the current work. Note all innovations flagged by reviewers.

2. **For each innovation, assess:**
   - Is this genuinely structural — a technique that could recur in future works — or is it incidental to this specific work?
   - Which rubric dimension does it most affect? Does it stretch or reveal a gap in that dimension?
   - Is it a positive technique (something the rubric should reward) or a failure mode (something the rubric should penalize)?

3. **Write the innovation entry:**

   ```
   WORK:MOMENT — TECHNIQUE NAME — RUBRIC ANCHOR — IMPLICATION
   ```

   - `WORK`: the work slug (e.g., `0001-napoleon-losses`)
   - `MOMENT`: which review surfaced this (e.g., `minard-review`, `tufte-review`, `statistician-lens`)
   - `TECHNIQUE NAME`: a short memorable name for the technique
   - `RUBRIC ANCHOR`: which ASPECT dimension this touches (e.g., `School`, `Precision`, `Truth`)
   - `IMPLICATION`: one sentence on what the rubric should say about this, if amended

4. **Append to `scoring/INNOVATIONS.md`** under the current date.

5. **Check for clusters:** if this innovation is similar to one logged in a prior work, note the match. Two matching innovations across two works = cluster. Report the cluster to the user.

## Example Entry

```
0003-cholera-map:neurath-review — Democratic Failure Mode — Clarity — When isotype symbols are used at scales too small to count (< 5mm), the repetition principle breaks down; the rubric should penalize sub-threshold symbol sizing explicitly.
```

## Example Invocation

`/degas-innovation 0001-napoleon-losses` — reviews the panel SUMMARY for work 0001 and logs all innovations to INNOVATIONS.md.
