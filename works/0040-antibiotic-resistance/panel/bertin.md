---
reviewer: bertin
work: 0040-antibiotic-resistance
cycle: 1
rubric_version: v2.1
weight: 0.20
---

# Bertin Review — 0040 Antibiotic Resistance (Cycle 1)

## School Fidelity (20)

Type A, statistical-graphics school. I will say this precisely: the heat matrix is the correct form for a 30 × 5 quantitative comparison, and color value (lightness) is the correct visual variable for ordered quantitative data. These decisions are correct.

But a matrix is only as powerful as its ordering. The matrix is my invention as much as anyone's — *Sémiologie Graphique* Chapter 4 makes clear that reordering rows and columns by similarity of profile is not an optional decoration. It is the mechanism by which structure emerges from pattern. An unsorted matrix conceals what a sorted matrix reveals.

The current design has alphabetical row order. This is the worst possible order: it is neither data-derived nor argument-derived. It is a linguistic convention imposed on a quantitative display. Every resistance pattern that exists in the data is invisible in alphabetical order.

This is a serious School Fidelity failure because the reordering matrix technique is not peripheral to the statistical-graphics school — it is central to the Bertinian tradition from which the heat matrix form derives.

Score: **14/20** (correct form and encoding variables; sorting failure is a core grammar violation)

## Integrity (20)

The data sources are authoritative. Missing data is correctly handled. The income tier indicators are an honest disclosure of the structural covariate.

One concern: the bacteria columns should be ordered to reflect clinical or stewardship logic, not arbitrary presentation. *K. pneumoniae* carbapenem resistance is the WHO Priority 1 Critical pathogen — it belongs in the first column or the last column (either anchor position), not embedded between other pathogens. The ordering of columns is an editorial argument about clinical priority, and the current design makes no such argument.

Score: **16/20**

## Legibility (15)

Context: policy report, high statistical literacy, contemplative study. The matrix form is legible to this audience.

My specific concern is that the argument is not legible — only the data is. For the matrix to serve its purpose, the pattern must emerge from the structure. Currently, a policymaker must scan the entire matrix mentally, group countries by income tier in their head, and then notice that the grouped pattern matches the stewardship hypothesis. The matrix should do this grouping work. Sorted by income tier, the pattern becomes visible in 5 seconds without any mental effort from the reader.

Score: **10/15** (legible form; argument-illegible through missing sort structure)

## Execution (15)

Economy: clean. No unnecessary elements.

Craft: the sequential red palette is technically correct but limited. I recommend the following palette structure for Cycle 2: use a diverging palette from blue (at or below WHO stewardship target rate for that pathogen) through white (at target) to dark red (severely above target). This encodes not just the magnitude but the deviation from achievable good-stewardship rates, which is the argument's core variable.

The numeric labels inside cells are correct and should be preserved.

Score: **12/15**

## Resonance (15)

Domain resonance for specialists is present — the magnitude of resistance in high-burden countries is immediately visible. Advocacy resonance is minimal because the argument structure is not visible in the form.

Score: **10/15**

## Purpose (15)

The purpose (advocacy for stewardship policy) is not served by the current design. The data is displayed; the argument is not made. Revision must move the work from information display to advocacy structure.

Score: **10/15**

---

## Score Summary

| Dimension | Score |
|-----------|-------|
| School Fidelity /20 | 14 |
| Integrity /20 | 16 |
| Legibility /15 | 10 |
| Execution /15 | 12 |
| Resonance /15 | 10 |
| Purpose /15 | 10 |
| **Total /100** | **72** |

## Top Recommendations for Cycle 2

1. **Sort rows by income tier then by average resistance burden within tier** — primary and most urgent change.
2. **Diverging color palette anchored at WHO stewardship targets per pathogen** — argument becomes visible in color.
3. **Sort bacteria columns by clinical priority (WHO Critical / High / Medium)** — makes column ordering an argument about relative urgency.
