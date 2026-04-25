---
reviewer: tufte
work: 0050-degas-scoreboard
weight: 0.25
rubric_version: v2.2
---

# Tufte Review — 0050 DEGAS Scoreboard

A sorted bar chart of 50 values. Let me count what is in this design: 50 bars, 50 slug labels, 50 score values, 1 color legend, 1 title, 1 subtitle, 1 x-axis with tick labels, 3 reference lines, 14 color values. That is a reasonable mark count for 50 data points with two encoded variables (score, school).

Data-ink ratio: high. Each bar encodes a score; the color encodes a school; the label encodes the identity; the tick marks encode scale reference points. The reference lines (60 advisory, 80 above-average, 90 high range) are functional — they help the viewer locate works within the score distribution without counting tick marks.

My concern: the 14-color palette. Bertin established that categorical color discrimination degrades rapidly above 7-8 categories. With 14 school colors, the viewer must look up each bar in the legend to know which school it belongs to. The color is no longer a preattentive encoding — it is a lookup task. I would prefer smaller multiples by school (one bar chart per school, faceted) to a 14-color single chart. But faceting loses the cross-school ranking, which is the primary argument.

Compromise: 6-7 school families (statistical + advocacy, cartography + flow, ecological + scientific, information-architecture + schematic, art + data-art, other). Within each family, slight tonal variation. The viewer reads families preattentively; specific school identification requires the legend. This is the correct trade-off.

The truncated x-axis (50-100 rather than 0-100): I note this as a potential issue. The difference between 57.1 (propaganda) and 92.7 (vaccines) appears as 100% of bar length rather than 35.6% of bar length. The visual exaggeration is real. But since the argument is comparative ranking rather than absolute magnitude, the truncation is defensible if declared. Use the zig-zag break symbol at x=50 to make the truncation visible.

The self-referential element: work 0050 is in the chart. I find this a form of honest recursion. The chart is not pretending to be an external judgment of itself; it is the project's own score for this chart, declared as such. It is the equivalent of a bibliography that includes the book containing the bibliography.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 19/20 | Perfect bar chart grammar; sorted correctly; color for categorical is correct; 14-color limit concern |
| Integrity | 18/20 | Complete data; self-referential recursion declared; truncated axis needs zig-zag break symbol |
| Legibility | 13/15 | 50 bars require reading; 14-color legend requires lookup; small type for slugs necessary |
| Execution | 13/15 | High economy; reference lines functional; 14-color palette exceeds preattentive limit; −2 |
| Resonance | 13/15 | Domain resonance (Cluster S, +1); DEGAS practitioners see project history in bars; general viewers: informational satisfaction |
| Purpose | 13/15 | Informational + self-reflexive; project documentation; form well matched |
| **TOTAL** | **89/100** | |
