---
reviewer: playfair
work: 0040-antibiotic-resistance
cycle: 1
rubric_version: v2.1
weight: 0.30
---

# Playfair Review — 0040 Antibiotic Resistance (Cycle 1)

## School Fidelity (20)

Type A, statistical-graphics school. The heat matrix is a legitimate grammar descendant of the Bertinian matrix tradition — quantitative data encoded in a retinal variable (color value/lightness) organized in rows and columns for comparison. This is the right form for a 30 × 5 quantitative comparison. I invented the bar chart and the line graph because proportion needs to be immediate. The heat matrix makes resistance rates immediately comparative — you see the dark cluster at the bottom of the matrix before you read a single country name.

What the current design lacks is what I always insist on: **sort by the argument.** Alphabetical order is no order at all — it is the order of language, not of data. The countries should be sorted by resistance burden, or by income tier, or by stewardship classification — any order that makes the argument visible. Alphabetical order hides the pattern. The matrix's power is precisely that reordering reveals structure. An unsorted matrix is a chart that refuses to state its argument.

The bacteria columns should similarly be sorted — by clinical priority, by resistance severity, or by stewardship sensitivity. Random column order is a missed opportunity.

Score: **15/20** (correct form; sorting failure is a significant grammar violation for a school whose entire purpose is comparative clarity)

## Integrity (20)

The source declarations are present and appropriate: WHO GLASS 2023 and ECDC Surveillance Report 2023 are the correct authoritative sources for this data. The missing data cross-hatching is the right treatment for incomplete surveillance coverage. Do not suppress missing data — mark it.

One Integrity concern: the resistance rates for *N. gonorrhoeae* present a special case. Ceftriaxone resistance in gonorrhea is measured differently across surveillance systems (some report MIC levels; some report phenotypic resistance at different breakpoints). The figure note should acknowledge that gonorrhea resistance data uses the EUCAST/CLSI breakpoint for ceftriaxone, and that comparability across surveillance systems varies.

The income tier dots in the margin are a good disclosure move — they expose the structural variable (income/stewardship tier) that the panel will want to analyze against the resistance data.

Score: **16/20** (strong; gonorrhea resistance methodology caveat needed)

## Legibility (15)

Context: policy report, contemplative study, policymakers with high statistical literacy. The matrix form is immediately legible to this audience — they read data tables and charts regularly. The income tier dots are legible at reading distance.

The alphabetical ordering is the primary legibility failure. A policymaker reading this matrix cannot immediately extract the pattern without sorting it mentally — which defeats the purpose of visual encoding. If the matrix were sorted by income tier (high income at top, low income at bottom), the dark-cell cluster would appear at the bottom right of the matrix, and the argument ("lower income + poor stewardship = highest resistance") would be visible in 5 seconds. As currently designed, the viewer must work to find the pattern.

Score: **11/15** (legible form, critically under-serving the argument through poor ordering)

## Execution (15)

Economy: the color encoding is clean. The income tier dots add information without cluttering the matrix. The missing data crosshatch is correctly implemented. The numeric labels inside cells are appropriate — they serve the reader who wants precision, not just comparison.

Craft: the single-hue sequential palette (white to dark red) is correctly chosen for ordered quantitative data. Bertin would approve: color value (lightness) is the appropriate ordered retinal variable.

One craft concern: the transition from "low resistance" (light) to "moderate resistance" (medium red) may be perceptually compressed. A diverging palette anchored at a "good stewardship" reference point (e.g., WHO-target rate in blue; higher rates in red) would make the deviation from good stewardship immediately visible. This is the most important craft recommendation for Cycle 2.

Score: **12/15** (good economy; palette choice is technically correct but misses an opportunity to make the argument through color structure)

## Resonance (15)

Advocacy resonance — this is data for decision-makers. The matrix, as currently designed, achieves partial advocacy resonance: the scale of the problem (dark cells across the matrix) is visible. But the argument — that stewardship is the key variable, that high-income countries with good stewardship maintain low rates despite equivalent use — is not visible in the current sort order.

The work needs a structural change to achieve advocacy resonance: sort the countries by income tier and stewardship classification so that the pattern emerges from the matrix's organization, not from the viewer's mental effort.

Score: **10/15** (partial advocacy resonance; the form can do more work)

## Purpose (15)

Advocacy — persuade policymakers to prioritize stewardship over use-reduction alone. The form is the right form. The data is the right data. But the argument is not visible in the current design. A policy report that presents the data without making the structural argument is informational, not advocacy. This work is designed for advocacy but currently functioning as information display.

Score: **11/15**

---

## Score Summary

| Dimension | Score |
|-----------|-------|
| School Fidelity /20 | 15 |
| Integrity /20 | 16 |
| Legibility /15 | 11 |
| Execution /15 | 12 |
| Resonance /15 | 10 |
| Purpose /15 | 11 |
| **Total /100** | **75** |

## Top Recommendations for Cycle 2

1. **Sort countries by income tier then stewardship classification** — this single change will improve School Fidelity, Legibility, Resonance, and Purpose simultaneously. The argument becomes visible.
2. **Add WHO-standard stewardship counterfactual** — either as a reference column showing what resistance rates should be achievable with good stewardship, or as a diverging color palette anchored at the stewardship target.
3. **Sort bacteria columns by clinical priority / stewardship sensitivity** — *K. pneumoniae* carbapenem resistance is the most severe clinical threat and should anchor the matrix.
