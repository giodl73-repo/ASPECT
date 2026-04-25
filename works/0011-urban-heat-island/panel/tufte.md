---
work: 0011-urban-heat-island
stage: panel
reviewer: tufte
rubric_version: v1.6
created: 2026-04-23
---

# Tufte — Panel Review

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type A) | 16 | 20 |
| Data/Story Integrity | 16 | 20 |
| Legibility | 13 | 15 |
| Visual Economy | 11 | 15 |
| Resonance | 11 | 15 |
| Craft | 12 | 15 |
| **Total** | **79** | **100** |

## Review

The chart is competent. It is not yet good.

**On School Fidelity:**

The grammar is applied correctly. Zero baseline, sorted bars, direct labeling, explicit encoding declaration — these are all correct. The error bars are present and appropriate. The color is the problem, as Playfair has already identified. I will add a specific critique: the color palette chosen (blue, purple, orange, green, pink) has five hues. Five hues is at the edge of reliable discrimination for adjacent comparison. When bars of similar colors are separated by many positions in the sort order (as they inevitably are, since we are sorting by UHI, not by region), the viewer must scan the legend repeatedly. Every legend lookup is a cognitive cost. The region encoding could be replaced with a direct regional label on the first bar of each regional group — or removed entirely.

The title makes a claim the data does not fully support. This is a school fidelity issue because the statistical-graphics school requires honesty between title and data. Score 16.

**On Data/Story Integrity:**

The error bars are correct. The sorting is honest. The zero baseline is present. The title overreach is the primary integrity concern.

Additionally: the uncertainty of ±0.3°C means that the chart's top ten cities cannot be reliably distinguished in rank — Phoenix (4.8) and Beijing (4.4) differ by 0.4°C, barely above the uncertainty. The designer should note this directly: "Rankings in the top tier should be interpreted cautiously given measurement uncertainty." The error bars are present but the interpretive note is not. Score 16.

**On Visual Economy:**

Eleven. The region color is the main excess. Remove it and the chart is leaner and more honest. What else: the gridlines at integer values are present in the design spec; if they are light they are acceptable; if they are heavy they compete with the bars. The label density (30 city names at 6mm spacing) is tight — some names may require 8pt type at the specified dimensions, which is at the edge of comfortable reading.

**On Resonance:**

The core message — Phoenix worse than Mumbai — is genuinely surprising. That is good resonance for a quantitative chart. But the design does not amplify this surprise. There is no annotation at Phoenix explaining why it is first, no annotation at Johannesburg explaining why it is last. The viewer who wants to understand, not just see, needs the accompanying text. The chart is correct and informative but does not guide the viewer toward the most important conclusions. Score 11.

**The fundamental question the brief raised and the design did not answer:**

Is this the right form? The brief's open question was: "Is a single sorted bar chart the right form, or does the story require grouping by region, by income, or by scatter?" The design chose the sorted bar chart and passed the question to the panel. My answer: no, this is not the right form. The story is about the relationship between two variables — UHI and income (or climate zone). A scatter plot of UHI vs. per-capita energy consumption, with city names labeled, would tell a more honest and more revealing story. The bar chart shows ranking; the scatter would show causation. This is a school choice error, not a school execution error.

## Innovations Flagged

1. **School-story mismatch as a design failure category** — the bar chart school correctly handles ranked single-variable comparison, but this story is fundamentally a two-variable relationship story. Choosing the single-variable form because it is familiar and clean is a school choice error: the grammar is applied correctly, but the wrong grammar was chosen for the story. *Rubric anchor: School Fidelity. Implication: the rubric should ask not only "is the chosen school correctly applied?" (Type A fidelity) but also "is the chosen school appropriate for this story?" School-story mismatch should be a named School Fidelity failure mode.*

2. **Rank uncertainty in sorted charts** — when data has measurement uncertainty, items ranked close together may not be reliably distinguishable. A sorted bar chart implies a definitive ranking; overlapping error bars challenge that implication. The designer should declare where ranking is reliable and where it is within the noise. *Rubric anchor: Data/Story Integrity. Implication: for sorted bar charts with error bars, add a note to Step A (source quality) requiring declaration of whether adjacent rankings are statistically distinguishable.*
