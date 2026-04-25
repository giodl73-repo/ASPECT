---
reviewer: bertin
work: 0053-pharma-subgroup
weight: 0.10
rubric_version: v2.2
---

# Bertin Review — 0053 Pharmaceutical Subgroup Forest Plot

The forest plot uses a limited, well-defined set of visual variables:

**Position (x-axis):** Encodes effect size (hazard ratio). Correct. The null reference line at HR=1.0 creates the visual binary: CI crossing = non-significant, CI not crossing = significant. This is a retinally efficient encoding — the eye can read significance without reading numbers.

**Size (CI bar length):** Encodes uncertainty width (confidence interval). Correct. Wider bar = more uncertainty; narrower bar = more precise estimate. The >65 subgroup bar (CI [0.70, 0.97]) does not cross the null. The overall result bar (CI [0.85, 1.04]) does cross the null.

**Color (hue):** The >65 row is encoded in a distinct hue from the other rows. Hue here encodes "this row is the emphasized finding." Hue is selective (the eye can group marks by hue) but not ordered (hue does not encode magnitude). The use of hue to encode "featured" status is grammatically correct — it is a selective variable being used for a selective purpose.

**Value (text weight):** The >65 row label is in heavier weight. Value/darkness encodes emphasis — an associative and ordered variable used for ordered emphasis. Grammatically acceptable.

The encoding is grammatically correct at every mark. The visual coercion operates not in any variable's misapplication, but in the selection of which row to encode with emphasis variables.

Here is the structural point: the forest plot grammar has no affordance for "this row should be de-emphasized because it is post-hoc." All rows are grammatically equivalent. The grammar assumes that the analyst has already selected which finding is primary. When the analyst selects the post-hoc finding as primary through emphasis variables, the grammar faithfully executes that selection. The coercion is at the selection level, invisible in the grammar.

This is the most technically sophisticated case in Cluster X: grammar-perfect coercion. The rubric's Execution and School Fidelity dimensions will give this work high marks. The Integrity failure is real but lives entirely outside the visual variable system.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 16/20 | Forest plot grammar precisely applied; all visual variables correctly matched; emphasis encoding is grammatically sound |
| Integrity | 8/20 | The grammar is correct; the analytical frame selection is the Integrity failure; Q3 dock (undeclared post-hoc analytical framework as primary) |
| Legibility | 13/15 | High legibility for trained readers; the emphasis variable reads immediately |
| Execution | 14/15 | Clean, professional; economical mark use |
| Resonance | 11/15 | Effective clinical impression |
| Purpose | 5/15 | Analytical frame serves commercial over clinical purpose |
| **TOTAL** | **67/100** | |
