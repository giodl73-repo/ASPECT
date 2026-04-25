---
work: 0011-urban-heat-island
stage: panel
reviewer: statistician
lens: true
rubric_version: v1.6
created: 2026-04-23
---

# Statistician Lens — Panel Review

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| Data/Story Integrity | 14 | 20 |
| Legibility | 12 | 15 |
| **Weighted contribution** | *see SUMMARY* | — |

## Review

**On Data/Story Integrity:**

The error bars (±0.3°C) are present and appropriate. This is a significant improvement over the historical works reviewed in this project — Minard had no uncertainty indicators; Nightingale had none. The designer deserves credit for including them.

Three concerns:

First: the ±0.3°C uncertainty is described as a "mid-range estimate" but not sourced. The brief cites Manoli et al. (2019) and ECDC Urban Climate Monitor (2022); I would need to verify that ±0.3°C is consistent with the cited sources' reported confidence intervals. For the purposes of this review, I accept it provisionally.

Second: UHI measurement methodology varies significantly. Some studies measure UHI as daytime surface temperature differential; others measure near-surface air temperature; others use nighttime satellite thermal readings. The chart presents a single figure per city as if these methodologies are commensurable. They are not always. Phoenix's 4.8°C may be measured differently from Johannesburg's 0.5°C. This is a Step A concern (source quality) that the chart does not address.

Third: the chart presents 2018–2022 averaged data, which smooths inter-annual variation. UHI intensity varies significantly by season and year; a multi-year average hides whether the effect is growing or shrinking. For Phoenix, which has been implementing urban greening programs, the trend may be as informative as the current value. The static chart suppresses all of this.

Score 14: better than most historical canonical imports on uncertainty disclosure; weaker on methodological comparability and trend suppression.

**On Legibility:**

The chart is legible for the stated audience. City names at 9pt in a 6mm row will be readable at normal screen resolution. The horizontal bars with explicit quantitative axis labels are the clearest possible form for this data type. The color legend adds one lookup per regional grouping — minor friction. Score 12.

## Innovations Flagged

1. **Methodological comparability as Step A criterion** — when data from multiple sources or methodologies is presented in a single visualization as if commensurable, the comparability assumption should be declared. "These measurements use consistent methodology" or "these measurements use varying methodologies: see data notes" are both acceptable; silence is not. *Rubric anchor: Data/Story Integrity (Step A). Implication: Step A should explicitly ask whether data from multiple sources is methodologically comparable, and whether the comparability is declared.*

2. **Trend suppression in point-in-time charts** — a chart of current values that does not declare whether those values are improving, worsening, or stable has suppressed potentially critical context. For policy-relevant data (climate, public health, economics), the trend direction is often as important as the current value. *Rubric anchor: Data/Story Integrity (Step A/C). Implication: for policy-relevant original designs, the panel should ask whether trend direction is known and whether its absence from the chart is declared or actively noted.*
