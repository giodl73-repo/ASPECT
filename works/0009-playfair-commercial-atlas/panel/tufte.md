---
work: 0009-playfair-commercial-atlas
stage: panel
reviewer: tufte
rubric_version: v1.4
created: 2026-04-23
---

# Tufte -- Panel Review

*School type: B (Founder). Statistical-graphics.*

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type B) | 19 | 20 |
| Data/Story Integrity | 17 | 20 |
| Legibility (political-presentation context) | 13 | 15 |
| Visual Economy | 13 | 15 |
| Resonance (Types II + IV) | 14 | 15 |
| Craft | 12 | 15 |
| **Total** | **88** | **100** |

## Review

William Playfair invented the bar chart in 1786 and explained it clearly in the same document. For this alone, the work deserves a score that acknowledges historical magnitude.

But historical magnitude is not a rubric. I will score what I can evaluate: does the chart work as a chart?

**On School Fidelity (Type B):**

The founding grammar of statistical graphics is recoverable from this chart and its preface. The rules: bar length proportional to quantity; axis as measurement scale; categories on the perpendicular axis; visual comparison available before numerical reading; two sub-series distinguished by fill pattern. These five rules have governed bar chart design for 240 years. Every bar chart made since Playfair has used at least three of them.

I withhold one point for a founding gap that subsequent practitioners have had to solve: the work does not specify how to handle baseline -- should bars always start at zero? Playfair's chart starts at zero, which is correct, but he does not state this as a rule. A practitioner who derived their bar chart grammar from Playfair alone would not know that non-zero baselines are a form of distortion. This is a significant gap in the founding grammar, because the truncated-axis problem has plagued statistical graphics ever since.

Score 19.

**On Data/Story Integrity:**

The explicit encoding declaration puts this in a different category from most works we have reviewed. Playfair tells us exactly what the chart encodes and what it is for. He does not claim more precision than the chart provides. He does not claim causation. He declares the framework.

The source data issue (Customs records with known evasion and recording gaps) docks one point. This is not a failure -- it is the irreducible uncertainty in 18th-century commercial statistics. The chart does not imply false precision. Score 17.

**On Visual Economy:**

The hatched fill pattern (diagonal lines to distinguish imports vs. exports) is the right choice given the available technology (hand engraving, black ink). No color was possible. The hatching is functional, not decorative. Score: high.

The decorative cartouche title in the corner is the most significant non-data element. The typography overall is hand-lettered, which was the only available technique, and it introduces slight irregularities. These are production constraints, not design choices. I do not penalize for them. Score 13.

**On Craft:**

The hand-engraved copper plate shows its limitations at the typographic level. The trading-partner names are slightly cramped and the letterforms are inconsistent. This is what hand-engraving produces; it would be unfair to penalize as if mechanical typography were available. However, even accounting for period constraints, the label placement is not optimal: the labels crowd some bars and leave awkward space near others. Score 12.

**On whether the first bar chart is a good bar chart:**

By contemporary standards, it is a good bar chart with known flaws that have been corrected by 240 years of practice. The sort order is approximate rather than strict, which reduces the ranking-comparison clarity. The label typography is cramped. The fill pattern works in black and white but is less clear than color would be. All of these are solvable within the bar chart grammar that Playfair founded. The grammar is sound; the first instance has the imperfections of all first instances.

## Innovations Flagged

1. **Baseline declaration as founding grammar requirement** -- a founding statistical chart grammar should specify the baseline rule (bars start at zero) as explicitly as it specifies the encoding rule (bar length = quantity). Playfair's failure to specify the baseline rule is a founding gap that has produced persistent errors in subsequent practice. The rubric's School Fidelity Type B anchors should ask: does the founding grammar address the most common subsequent distortions of the form? *Rubric anchor: School Fidelity (Type B).*

2. **Period-constraint vs. design-choice distinction in Craft** -- when a work's craft limitations are production-technology constraints of the period (hand-engraving vs. mechanical typography) rather than design choices, they should be assessed differently from discretionary craft failures. The Craft dimension should distinguish between what the designer could control and what the technology permitted. *Rubric anchor: Craft.*
