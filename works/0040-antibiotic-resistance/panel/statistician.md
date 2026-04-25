---
reviewer: statistician
work: 0040-antibiotic-resistance
cycle: 1
rubric_version: v2.1
weight: 0.10
---

# Statistician Review — 0040 Antibiotic Resistance (Cycle 1)

## School Fidelity (20)

Type A, statistical-graphics. The heat matrix encodes resistance rates in color value — ordered retinal variable for ordered quantitative data. Correct.

My concern is with the equivalence assumptions embedded in the comparison. The 30 countries use different surveillance systems (GLASS-participating countries have standardized methodology; non-GLASS countries use national systems with varying definitions and sampling frames). The resistance rate for *K. pneumoniae* carbapenem resistance in Norway and in Nigeria may not be strictly comparable because the patient populations being sampled differ (hospital isolates vs. community isolates; severity-stratified vs. unstratified samples). The design should acknowledge this comparability limitation prominently, not bury it in fine-print citations.

Score: **14/20**

## Integrity (20)

Two issues:

First, the *N. gonorrhoeae* ceftriaxone resistance data is not comparable across systems for the reasons I outlined — the WHO GLASS gonorrhea surveillance uses different sampling frames and breakpoints than CDC/ECDC reporting. A specific note for the gonorrhea column is required.

Second, the "resistance rate" metric aggregates across patient severity, infection site, and sample collection method. A hospital-acquired urinary tract infection caused by resistant *E. coli* is clinically different from a community-acquired case, and the resistance rates in these populations differ substantially. The design presents a single number per country-pathogen cell, but that number conceals substantial within-country variation. A range bar (min-max of subgroup estimates) or a small error bar would be more honest.

Score: **14/20** (comparability limitations not adequately disclosed)

## Legibility (15)

High-literacy audience, contemplative study. The form is legible. The statistical limitations I've identified are legibility concerns for expert readers — they will question the comparability and may reject the data if the limitations are not acknowledged.

Score: **12/15**

## Execution (15)

Clean economy. The cross-hatch for missing data is correctly implemented. The numeric labels are appropriate.

One suggestion: for pathogens where uncertainty in the resistance estimate is high (primarily Sub-Saharan Africa), the numeric label could be italicized or marked with an asterisk to indicate lower confidence. This would communicate data quality variation without eliminating the estimate.

Score: **12/15**

## Resonance (15)

Domain resonance for infectious disease specialists is present. The scale of resistance in India and Pakistan for *E. coli* and *K. pneumoniae* will be recognizable to clinicians. The gonorrhea resistance numbers will alarm anyone working in STI medicine.

Advocacy resonance is limited — the form is not making the structural argument.

Score: **11/15**

## Purpose (15)

The statistical limitations should not prevent the work from achieving its advocacy purpose, but they must be visible. A work that reaches WHO health ministers with incompletely disclosed statistical limitations could produce policy decisions based on imprecise comparisons. The purpose requires the disclosure.

Score: **11/15**

---

## Score Summary

| Dimension | Score |
|-----------|-------|
| School Fidelity /20 | 14 |
| Integrity /20 | 14 |
| Legibility /15 | 12 |
| Execution /15 | 12 |
| Resonance /15 | 11 |
| Purpose /15 | 11 |
| **Total /100** | **74** |

## Top Recommendations for Cycle 2

1. **Add surveillance comparability note** — acknowledge GLASS vs. non-GLASS methodology differences prominently.
2. **Add uncertainty indicators for low-data cells** — asterisk or italics for estimates with high methodological uncertainty.
3. **Gonorrhea column caveat** — specific note on measurement breakpoint differences for the *N. gonorrhoeae* column.
