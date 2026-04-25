---
reviewer: bertin
work: 0046-minard-hannibal
weight: 0.20
rubric_version: v2.2
---

# Bertin Review — 0046 Hannibal Crossing the Alps

Systematic variable assessment.

Band width: encodes troop count. Size variable — quantitative, ordered. Correct match. Linear encoding declared in the legend.

Band position/path: encodes geographic route. Position — the most powerful spatial variable. Correct use. The geographic base is simplified, but simplification for legibility is a declared design choice in cartographic grammar, not an encoding error.

Band color: single color (brown/tan). No direction variable needed — Hannibal did not return. The single-color band is correct for a one-direction march. Compare to the Napoleon map: two-color encoding (tan advance + black retreat) was necessary because the army moved in both directions. For Hannibal, one direction, one color. Correct.

Text labels: troop counts at inflection points. These are redundant encodings (the band width already encodes the count) that add precision. Correct in statistical-graphics grammar — redundant precision annotations are legitimate when they serve readers who need the exact number rather than the proportional estimate.

What is NOT encoded: the cause of the attrition. The band narrows at the Alpine crossing. The map shows the Alps as a symbol and label. But the terrain variable — elevation, route difficulty, climate — is not quantitatively encoded. Compare to the Napoleon map, where temperature is a quantitatively encoded second-register variable explaining attrition. The Hannibal map shows the effect (narrowing band) without encoding the cause. This is a lower-dimensional design.

Data quality note: the troop counts from Polybius and Livy carry uncertainty that is not represented in the band width. The band at the start shows approximately 90,000 men. Whether this is 80,000 or 100,000 cannot be known from ancient sources. The band width implies a precision that the data does not support.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 18/20 | Flow map grammar correctly applied; all variables correctly matched to visual variables |
| Integrity | 15/20 | Ancient source uncertainty not declared in work; troop counts from contested historical sources; −3 for undisclosed uncertainty, −2 for source quality |
| Legibility | 13/15 | Contemplative study; single register clear; route and attrition legible |
| Execution | 13/15 | Correct encoding; missing second register (cause variable) that Napoleon achieves; lower dimensional information |
| Resonance | 12/15 | Historical resonance; narrowing band carries weight; ancient campaign creates distance |
| Purpose | 13/15 | Historical documentation; form serves purpose |
| **TOTAL** | **84/100** | |
