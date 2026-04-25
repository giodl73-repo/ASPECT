---
work: 0007-neurath-isotype
stage: panel
reviewer: statistician
rubric_version: v1.4
created: 2026-04-23
---

# Statistician Lens -- Panel Review

*School type: B (Founder). ISOTYPE.*

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type B) | 18 | 20 |
| Data/Story Integrity | 13 | 20 |
| Legibility (public-display context) | 13 | 15 |
| Visual Economy | 10 | 15 |
| Resonance (Types III + V) | 12 | 15 |
| Craft | 13 | 15 |
| **Total** | **79** | **100** |

## Review

I will score only on the dimensions where my lens applies; the others I note without scoring.

**On Data/Story Integrity -- the primary assessment:**

*Chart A (Workers in Manufacturing, Germany vs. USA):*

Step A -- source quality: The data appears to come from ILO labor statistics of the period, which were reasonably reliable for the countries covered. No provenance is declared in the chart; the source is only identifiable by knowing the museum's archival context. -1 for undeclared source.

Step B -- accuracy tradeoff: Two issues. First, the unit-rounding problem: 34.7 million shown as 34 figures means a 2% understatement that the viewer cannot detect. For social statistics at this scale, 2% may be acceptable; it is not declared. Second, and more significant: the chart shows absolute worker counts, not shares of workforce or per-capita rates. Germany had approximately 63 million people in 1930; the USA had approximately 123 million -- roughly twice the population. A chart of absolute manufacturing workers showing the USA at 3.4x Germany implies the USA has a proportionally larger manufacturing sector, which is not what the raw data shows. The manufacturing share of the workforce was comparable. -2 for undeclared normalization choice that materially changes the comparison.

Step C -- causation: No causal claim. The chart is comparative. No dock.

Step D -- analytical framework: The unit (1 figure = 1 million workers) is declared, which is the primary analytical framework. However, the choice to use absolute counts rather than normalized rates is undeclared and constitutes an implicit framework choice that changes the comparison. -1.

Total dock: -4. Base anchor: 17 (high integrity, minor issues). Final: 13.

*Chart B (Housing Conditions, Vienna 1900-1927):*

The dual-symbol encoding (dark house = overcrowded, light house = adequate) is clear and effective. The trend is honest -- overcrowding did fall in Vienna over this period due to municipal housing programs. The source data (city housing records) is credible and the direction is correct. Score this chart higher than Chart A: the normalization problem does not apply (this is a proportion, not an absolute count). But: no error bars, no declaration that the city's definition of "overcrowded" changed over the period (it did, slightly), and no account for population growth that would affect the denominator. Modest dock only for this chart.

*Chart C (Infant Mortality, 10 nations):*

Infant mortality rates (deaths per 1000 births) are rates, not absolute counts -- this avoids the normalization problem from Chart A. The country ordering (descending) is clear and honest. The choice of nations is not explained; why these ten? A viewer who wonders why their nation is not included cannot answer that question from the chart. Minor dock for incomplete universe declaration.

**Overall Data Integrity assessment:**

The system's most significant systematic weakness is the absolute-count default. ISOTYPE as a school tends to show "how many things" rather than "what proportion of relevant things." This matters most in cross-country comparisons where population denominators differ. Neurath was aware of this and sometimes normalized; the reviewed charts show the problem most acutely in Chart A.

## Innovations Flagged

1. **Unit-declaration completeness as a school-level requirement** -- the ISOTYPE school requires unit declaration (1 symbol = X units), but does not require declaration of the normalization choice (absolute count vs. rate vs. share). For the school to achieve full data integrity, both declarations are necessary. A school-level amendment to the founding grammar would improve all subsequent ISOTYPE practice. *Rubric anchor: Data/Story Integrity (Step A/D).*

2. **Absolute-vs.-rate implicit comparison** -- charts that compare absolute quantities across populations of different sizes imply a structural comparison (proportional difference) that the data does not support without normalization. This is a systematic encoding bias that the Data/Story Integrity Step C (causation claim) should explicitly address: implied structural comparison from unnormalized absolute counts. *Rubric anchor: Data/Story Integrity (Step C).*
