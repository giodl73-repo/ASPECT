---
work: 0011-urban-heat-island
stage: panel
reviewer: playfair
rubric_version: v1.6
created: 2026-04-23
---

# Playfair — Panel Review

*School type: A (Member — statistical-graphics). Original design, first in the project.*

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type A) | 17 | 20 |
| Data/Story Integrity | 17 | 20 |
| Legibility | 13 | 15 |
| Visual Economy | 13 | 15 |
| Resonance | 12 | 15 |
| Craft | 12 | 15 |
| **Total** | **84** | **100** |

## Review

This is exactly the form I would have used. Thirty items, one quantitative variable, sorted descending — the horizontal bar chart is correct in every particular. The designer has applied the grammar properly.

**On School Fidelity:**

The zero baseline is present. The sort order is descending, which is correct for a "who has the worst problem" argument. The city names are direct-labeled. The encoding declaration in the subtitle is admirable — this is what I did in my preface, and I am pleased to see it carried forward. The form speaks the grammar. I dock three points for one genuine weakness: the region color.

Color introduces a second categorical variable — world region — into a chart that is arguing about ranking. The sorting and the coloring are fighting each other. The chart is sorted by UHI differential; the colors create visual groupings by region that cut across the sort order. When the viewer's eye follows the orange bars (E. Asia) down the chart, they find them distributed across positions 2, 4, 5, 10, 13 — not adjacent. The color creates a visual pattern that the layout immediately contradicts. Either sort by region (and lose the differential ranking) or drop the color (and lose the regional information). The design is trying to do both and succeeding at neither with full conviction.

**On Data/Story Integrity:**

The error bars are exactly right. Showing ±0.3°C uncertainty does not weaken the chart — it strengthens it, because the viewer can see that the ranking at the top (Phoenix vs. Beijing: 4.8 vs. 4.4) is within the uncertainty range, while the gap between the top and bottom (Phoenix vs. Johannesburg: 4.8 vs. 0.5) is robust. The designer has not hidden the data quality limitation.

The title is a rhetorical title in my tradition — it states the argument: "High-income temperate cities have the worst urban heat islands." But the chart does not show income. The title makes a claim that the chart supports circumstantially (the high-UHI cities are generally known to be high-income) but does not demonstrate directly. For the title to be honest, it should be qualified: "High-income temperate cities tend to have..." or the chart should add a second axis for income.

I dock 1 for the overstated title claim, 1 for the region color that creates misleading cross-cuts. Score 17.

**On Resonance:**

I find the chart interesting. Phoenix at 4.8°C — I would not have guessed Phoenix was worse than Beijing. That is a genuine surprise that the chart delivers. The 10× range from Phoenix to Johannesburg is also surprising. The chart produces the wonder that a good chart should produce. But the visual form is conventional — a bar chart — and the emotional register is informational rather than affecting. Score 12.

## Innovations Flagged

1. **Sort-color conflict** — when a chart is sorted by one variable and colored by a second, the two organizational logics compete. The viewer cannot simultaneously read the sort order (descending) and the color groupings (regional) without visual confusion. This is a specific visual economy failure unique to multi-variable bar charts: adding a second encoding variable to a sorted chart creates a visual conflict that neither grouping nor sorting alone would create. *Rubric anchor: Visual Economy / School Fidelity. Implication: when adding a second categorical variable to a sorted bar chart, the designer must choose between sorting by the second variable (losing the primary ranking) or accepting visual fragmentation of the second variable's groups.*

2. **Title-data gap in advocacy framing** — a rhetorical title that makes a claim not fully demonstrated by the chart (the title claims "high-income cities"; the chart shows city names without income data). The viewer must supply knowledge of each city's income level to verify the title. This is a legitimate advocacy-visualization technique (Nightingale's titles also made moral claims) but it creates a Data/Story Integrity gap when the claim could be verified by adding a second data variable. *Rubric anchor: Data/Story Integrity. Implication: for original designs, the title-data gap should be scored — does the title claim something the chart can show, or something the viewer must supply from prior knowledge?*
