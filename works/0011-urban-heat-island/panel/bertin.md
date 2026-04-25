---
work: 0011-urban-heat-island
stage: panel
reviewer: bertin
rubric_version: v1.6
created: 2026-04-23
---

# Bertin — Panel Review

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type A) | 16 | 20 |
| Data/Story Integrity | 16 | 20 |
| Legibility | 13 | 15 |
| Visual Economy | 12 | 15 |
| Resonance | 11 | 15 |
| Craft | 13 | 15 |
| **Total** | **81** | **100** |

## Review

**Visual variable audit:**

*UHI differential → bar length (size/position):* Quantitative data encoded in length. Length is ordered and quantitative — the correct assignment. The horizontal orientation places the primary quantitative variable on the horizontal axis, which is the standard convention for the school. Correct.

*City identity → y-axis position with label:* Nominal categorical data encoded in position with direct text label. Position is the highest-fidelity retinal variable; using it for the categorical axis is correct. Direct labeling eliminates the need for a legend for city identity. Correct.

*Sort order → y-axis position:* The quantitative variable (UHI differential) is used to determine the categorical axis order. This is a second use of the position variable — the y-axis encodes both city identity and ranking simultaneously. This is a valid and efficient double-encoding; it does not violate the grammar because the two encodings are consistent (rank is derived from the quantitative variable being displayed).

*World region → color hue:* Nominal categorical data encoded in hue. Hue is selective — the viewer can group bars by color. This is the correct variable for nominal data. The problem: the sort order fragments the color groups. Selective does not mean the viewer will easily perceive the groups when they are physically scattered throughout the sorted list. The encoding is grammatically correct (hue for nominal) but functionally weak (the sort order defeats the grouping utility).

**The two-variable problem:**

This chart is encoding two variables on the y-axis (city identity + rank) and one variable by color (region). The total encoding density is three variables on two visual dimensions. This is achievable; Minard encoded six. But the conflict between sort-by-UHI and color-by-region means neither the rank structure nor the regional grouping is fully visible. The designer should choose: sort by region (color fully legible, rank obscured) or sort by UHI (rank fully legible, color fragmented). The current design attempts both and achieves a partial compromise.

**Tufte's suggestion (scatter plot) — my assessment:**

Tufte recommends a scatter plot of UHI vs. income or energy consumption. I agree the story is a two-variable relationship, but I note that a scatter plot introduces two new problems: (1) the city names at 30 points will be severely overplotted at typical chart dimensions, and (2) the viewer loses the immediate ranking that the sorted bar chart provides. A small-multiples design — one sorted bar chart per region — might serve both arguments simultaneously.

**Step D assessment:**

The analytical framework (sorted bar chart = ranked comparison) is standard statistical-graphics grammar. Declared in the encoding key. Step D Level 1 (in-work): dock 0-1. No novel framework. Score unaffected.

## Innovations Flagged

1. **Double-encoding conflict in sorted categorical charts** — using y-axis position to encode both category identity and rank (a valid double-encoding) creates a conflict when a second encoding (color) is added to produce groupings that cut across the sort order. The result: three simultaneous organizational logics (y-position = city, y-position = rank, color = region) that produce visual interference rather than visual density. *Rubric anchor: Visual Economy / School Fidelity. Implication: when adding a grouping variable (color) to a sorted chart, the rubric should ask whether the grouping variable's structure is consistent with or contradicts the sort order. Contradictory groupings create visual fragmentation that reduces economy below what either encoding alone would achieve.*
