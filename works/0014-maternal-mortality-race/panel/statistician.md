---
work: 0014-maternal-mortality-race
stage: panel
school: advocacy-visualization
author: statistician
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
---

# Panel Review — Statistician Lens

## Score Table

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity /20 | — | Not scored |
| Data/Story Integrity /20 | 16 | Step A: CDC WONDER cited; ICD coding change declared — good. Step B: no accuracy tradeoff; full context shown. Step C: no causal overclaim. Step D: standard aggregation model. One gap: COVID comorbidity effect on rates not quantified. |
| Legibility /15 | 13 | Expert audience; the shared y-axis is the critical connection and it is clear |
| Visual Economy /15 | — | Not scored |
| Resonance /15 | — | Not scored |
| Craft /15 | — | Not scored |
| **Total /100** | — | |

## Voiced Review

The data sourcing is the best I have seen in an original design under this rubric. CDC WONDER is the authoritative source. OECD Health Statistics is the authoritative international source. Both are cited. The ICD-10 coding change in 2018 is declared — this is the most common data integrity failure in maternal mortality trend analyses, and the designer has addressed it. I am impressed.

My one quantitative concern: the COVID comorbidity effect. The 2020–2021 spike in all racial groups is acknowledged through the shading band, but the design does not declare the magnitude of COVID's effect on the trend. Research suggests that approximately 40-50% of the excess maternal mortality in 2020–2021 can be attributed to COVID-19 as a contributing cause (Thoma et al., 2022). Without this declaration, a viewer might conclude that the 2016–2019 trend is more severe than it appears, when in fact the 2020–2021 peak is partially a COVID artifact. The racial gap persists throughout — but its pre-COVID trajectory and post-COVID trajectory should be treated as more analytically reliable than the peak years.

A small but important distinction: the design shows "maternal mortality rates" which CDC defines as deaths per 100,000 live births among women up to 42 days postpartum. This definition excludes late maternal deaths (43 days–1 year). Different countries use different cut-off points, which affects international comparisons. OECD attempts to harmonize these, but the harmonization is imperfect. A single sentence noting this comparability limitation would satisfy the Step A standard.

Overall: this is honest, carefully sourced, and correctly executed. The ICD note is the most important thing and it is present.

## Innovations Flagged

**Innovation #127 — COVID artifact declaration in maternal mortality trend designs**: Maternal mortality rate charts spanning 2020–2022 must declare whether the peak reflects COVID-19 as a contributing cause and, if possible, quantify the contribution. Failure to declare creates a Step A risk: the viewer may read the COVID peak as part of the secular trend rather than a temporary COVID-mediated elevation. The design should note estimated COVID contribution to peak-year excess mortality (citing available research) alongside the shading band. Rubric anchor: Data/Story Integrity (Step A — source quality and uncertainty declaration).
