---
work: 0041-beat-92-vaccines
rubric_version: v2.2
gate: PASS
---

# SUMMARY — 0041 Beat-92 Vaccines and Child Mortality

## Score

| Dimension | Playfair (×0.30) | Nightingale (×0.25) | Du Bois (×0.20) | Rosling (×0.15) | Statistician (×0.10) | Weighted |
|-----------|-----------------|---------------------|-----------------|-----------------|----------------------|---------|
| School Fidelity /20 | 19 | 19 | 19 | 19 | 19 | **19.0** |
| Integrity /20 | 18 | 18 | 17 | 18 | 17 | **17.8** |
| Legibility /15 | 14 | 14 | 14 | 14 | 13 | **13.85** |
| Execution /15 | 14 | 14 | 14 | 14 | 14 | **14.0** |
| Resonance /15 | 14 | 14 | 14 | 15 | 13 | **14.0** |
| Purpose /15 | 14 | 14 | 14 | 14 | 14 | **14.0** |
| **Total** | **93** | **93** | **92** | **94** | **90** | **92.65** |

**Final Score: 92.7 — PASS — Beat-92 target achieved.**

## Gate Status

PASS. Score 92.7 exceeds the Beat-92 target. New project high, surpassing 0040 (antibiotic resistance, 90.6). Panel unanimous on gate; spread 90–94.

## Dimension Analysis

**School Fidelity (19.0/20):** Perfect bar chart grammar. School-story match is ideal — comparison is exactly what bar charts do. Gradient fill is functional, encoding vaccination coverage as a third variable within the bar. One point deducted for the dual sub-bar requiring a legend reading step.

**Integrity (17.8/20):** Gold-standard data; causal title claim defensible given mechanistic evidence and correlation strength. Primary integrity gap: confidence intervals on mortality estimates suppressed from bar display. UN IGME carries ±15–25% uncertainty at country level; improvement is large enough to survive CI display but the suppression is real.

**Legibility (13.85/15):** Policymaker in contemplative study well served. Gradient encoding requires one legend-reading step, costing one point across most reviewers.

**Execution (14.0/15):** No decorative marks. Gradient fill formally justified as functional encoding. Dual sub-bar creates one small navigation burden.

**Resonance (14.0/15):** Advocacy resonance fully achieved. Gestalt available immediately: all right bars shorter, most dramatically where gradient fill is saturated. Rosling gave 15/15.

**Purpose (14.0/15):** Advocacy for clear public health goal; stakes genuine and proportionate. Honest about remaining gaps. One point deducted for suppressed confidence intervals.

## Top 3 Design Recommendations

1. Add 95% CI whiskers to bar endpoints (top 10 + bottom 5 countries) — improvement large enough to survive uncertainty display; would raise Integrity to ~18.5 and push total score to 93+.
2. Elevate sort-order disclosure to subtitle — "Countries ranked by 2023 under-5 mortality rate (top 30)" is a framing choice with advocacy implications; policymakers should see it immediately.
3. Larger gradient legend as side panel — dual sub-bar is the design's most innovative element; it deserves legend treatment equal to axis labels, not a footnote.

## Innovations Logged

- **#271 — Functional gradient fill as multi-variable bar encoding:** Gradient fill encoding a third variable that explains the primary variable's variation is a legitimate statistical-graphics technique, not chartjunk. Key criterion: the gradient must encode data causally related to the bar-length variable.
- **#272 — Dual sub-bar within sorted bar chart:** Stacking two mechanism indicators as sub-bars keeps all variables in a single visual space where co-variation is visible. Cost: one legend-reading step. Benefit: mechanism visible without a separate chart.

## Cluster Implications

No new cluster triggered. #271 is adjacent to counterfactual-as-structural-element (T) but operates in the opposite direction (showing mechanism of what did happen, not what did not). Both innovations stand alone.

## Comparative Note

New project high: 92.7. Previous high: 0040 at 90.6. The two-point gap to a theoretical ceiling (94–95) is explained by suppressed confidence intervals (Integrity) and dual sub-bar requiring legend (Legibility, Execution). Both are fixable in version 2.
