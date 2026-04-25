---
reviewer: bertin
work: 0050-degas-scoreboard
weight: 0.20
rubric_version: v2.2
---

# Bertin Review — 0050 DEGAS Scoreboard

Variable assessment.

Bar length: score value (0-100). Size variable — quantitative, ordered. Correct match. Linear scale.

Vertical position: rank (sorted by score). Position — ordered variable, correct for ranking. Sorting is the most important design decision: it makes the comparative ranking immediately available without requiring the viewer to search.

Bar color: school category. Hue — selective, associative, but not ordered. Correct match for nominal categorical data (schools are not ordered). My concern: 14 categories pushes beyond the limit of reliable hue discrimination. Above 7-8 categories, viewers cannot reliably associate hue with category without consulting the legend. The color encoding becomes a lookup task rather than a preattentive grouping.

Text labels: work slugs (left) and score values (right). These are annotations, not encodings — they add precision. Correct use.

Reference lines at 60, 80, 90: value lines — they encode three threshold points on the quantitative scale. Correct use; they add reference without adding data noise.

The matrix reordering principle applies here: the bars are already sorted by the primary variable (score), which is the correct sort key for the comparative argument. If the designer wanted to also reveal school clustering, sorting by school (secondarily) would reveal whether any school consistently clusters at a performance level. This would be an alternative design, not a correction.

My recommendation for the color problem: use 7 school groupings (families) with clear hue differences within each family via light/dark variants. Statistical-graphics family (statistical, dynamic, advocacy): blue tones. Cartographic family (cartography, schematic, epidemiological): brown/orange tones. Ecological/scientific family: green tones. Art family (data-art, abstract, isotype): purple/magenta tones. Architectural family (information-architecture): teal. Mathematical family (proof-visualization): slate. This reduces required discriminations from 14 to 7 while preserving the school information.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 19/20 | Bar chart grammar correctly applied; sorted by quantitative variable; color for categorical correct; 14-color limit concern |
| Integrity | 19/20 | Complete DEGAS data; no uncertainty; self-referential recursion declared; truncated axis must be declared |
| Legibility | 13/15 | 50 bars require attention; 14-color legend requires lookup; work slugs are 8pt -- limit of legibility at arm's length |
| Execution | 13/15 | Economy high; reference lines functional; 14-color palette exceeds preattentive discrimination limit |
| Resonance | 13/15 | Domain resonance for DEGAS practitioners; Cluster S recursion: +1; informational satisfaction for others |
| Purpose | 14/15 | Informational + self-reflexive; form perfectly matched to comparative ranking argument |
| **TOTAL** | **91/100** | |
