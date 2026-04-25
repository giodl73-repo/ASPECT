---
work: 0009-playfair-commercial-atlas
stage: panel
reviewer: statistician
rubric_version: v1.4
created: 2026-04-23
---

# Statistician Lens -- Panel Review

*School type: B (Founder). Statistical-graphics.*

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type B) | 18 | 20 |
| Data/Story Integrity | 17 | 20 |
| Legibility (political-presentation context) | 12 | 15 |
| Visual Economy | 13 | 15 |
| Resonance (Types II + IV) | 12 | 15 |
| Craft | 11 | 15 |
| **Total** | **83** | **100** |

## Review

This is a work of genuine statistical communication, and I will score it on those terms.

**On Data/Story Integrity -- my primary assessment:**

Step A: The Scottish trade data (Christmas 1780 to Christmas 1781) comes from Customs records, which Playfair cites. The Customs system in 18th-century Britain was imperfect: significant smuggling, recording inconsistencies across ports, delays in reconciliation. Playfair does not declare these limitations. A contemporary reader would not know whether the displayed values are official totals, adjusted figures, or estimates. Dock -1 for undeclared source limitations (Step A).

Step B: No accuracy tradeoff is present -- bar length is the most accurate available encoding for the data type. No dock.

Step C: No causal claims. The chart is purely comparative. No dock.

Step D: Playfair's explicit preface declaration is exceptional. He states the encoding rule, the intended use, and the limitations of the method. He does not claim more precision than the method provides. Dock 0. This is the only work in the project with a Step D dock of zero, and it earns it.

Net from steps: -1. Base anchor with high integrity and explicit declaration: 18. Final: 17.

**On what the chart would have needed to achieve full statistical integrity:**

1. Error bars or uncertainty ranges. The customs data has significant measurement error; displaying point estimates with no uncertainty indication implies false precision. This was not a convention in 1786 and I will not penalize heavily, but it should be named.

2. Comparative context. The chart shows Scotland's trade in one year. A reader cannot tell whether 1780-1781 was a typical year, an exceptional year, or a carefully selected year to support a particular argument. Without multi-year comparison, the single-year chart is vulnerable to cherry-picking (whether or not Playfair intended it).

3. Normalization. The chart shows monetary value in absolute pounds sterling. For comparisons across trading partners of different economic sizes, a per-capita or GDP-relative figure would be more informative. However, in 1786, neither GDP measurement nor reliable population data was available for most of these trading partners. This is an anachronistic critique and I will not apply it as a dock.

**On the explicit declaration as statistical virtue:**

The preface declaration is unusual in statistical graphics history. Most founders of graphical forms have not explained their encoding rules -- they have assumed that the form speaks for itself. Playfair's decision to explain is both practically necessary (the form was new) and statistically virtuous (declaring your data model is good practice). The combination of explicit declaration + appropriate modesty about precision is a model that subsequent statistical graphics have frequently failed to follow.

## Innovations Flagged

1. **Uncertainty suppression as period-standard vs. design choice** -- in 1786, uncertainty quantification was not a convention of statistical presentation. Playfair's failure to show error ranges is a period-standard practice, not a deliberate choice to suppress uncertainty. The rubric's Step A should distinguish between: (a) uncertainty suppression as a current design choice (penalize), (b) uncertainty non-representation as a period-standard practice (note but do not penalize at the same rate), (c) uncertainty non-representation as deliberate concealment (penalize heavily). *Rubric anchor: Data/Story Integrity (Step A).*

2. **Single-year vulnerability** -- a comparative chart showing a single time period is vulnerable to the objection that the period was selected to support a predetermined conclusion, even if it was not. Multi-period comparison is the statistical defense against this vulnerability. The rubric should note, for works showing a single cross-section, whether the selection of the time period is declared and justified. *Rubric anchor: Data/Story Integrity (Step A/C).*
