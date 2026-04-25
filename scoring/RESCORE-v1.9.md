---
rubric_version: v1.9
created: 2026-04-23
trigger: Cluster K (school-story mismatch) + Cluster L (variable selection disclosure)
works_affected: 0011–0016
---

# RESCORE-v1.9: Original Design Works 0011–0016

This document records the v1.9 adjustments to original design works 0011–0016. Rubric v1.9 is forward-only; these rescores are applied because the amendment directly addresses failure modes the panels already identified in these works. The rescore is a formal acknowledgment of what the panels found, now expressed in rubric language.

---

## Amendment Summary

**Amendment K (Step 0c — School-story match):**
Dock 0–4 from School Fidelity depending on how badly the school's grammar mismatches the story. Confirmed across works 0011, 0012, 0013, 0015.

**Amendment L (Step A — Variable selection disclosure):**
Dock −1 to −3 from Data/Story Integrity when key variables are excluded without declaration, especially when the exclusion creates a framing effect or actively misleads. Confirmed across works 0011, 0012, 0013, 0014.

---

## Work 0011 — Urban Heat Island

**v1.6 score: 80.8**

**Amendment K — School-story match:**
The bar chart school shows ranked quantities. The story's claim is about a two-variable relationship (UHI × income). Tufte's panel review (Innovation #103) explicitly named this: the bar chart is a partial mismatch — it can tell the story but a scatter plot or similar relational form would tell it more honestly. The school correctly applied but incorrectly chosen for the story's core argument.
- Assessment: **Partial mismatch**
- Dock: **−2 from School Fidelity**
- School Fidelity revised: 16.1 → 14.1

**Amendment L — Variable selection disclosure:**
The title claims "high-income temperate cities" but income is not encoded. The exclusion actively misleads: a viewer reads the title and expects income encoding; the chart delivers only UHI without it. Playfair (Innovation #102) and Du Bois (Innovation #105) both flagged this.
- Assessment: **Exclusion actively misleads** (title creates income expectation, income absent)
- Dock: **−2 from Data/Story Integrity**
- Data/Story Integrity revised: 15.9 → 13.9

**v1.9 weighted score:**

| Dimension | v1.6 Weighted | v1.9 Adjustment | v1.9 Weighted |
|-----------|--------------|-----------------|--------------|
| School Fidelity /20 | 16.1 | −2.0 | 14.1 |
| Data/Story Integrity /20 | 15.9 | −2.0 | 13.9 |
| Legibility /15 | 13.2 | — | 13.2 |
| Visual Economy /15 | 12.2 | — | 12.2 |
| Resonance /15 | 11.2 | — | 11.2 |
| Craft /15 | 12.2 | — | 12.2 |
| **Total /100** | **80.8** | **−4.0** | **76.8** |

**v1.9 score: 76.8 / 100. Gate: PASS**

---

## Work 0012 — ISOTYPE Plastic Pollution

**v1.6 score: 79.4**

**Amendment K — School-story match:**
Nightingale (panel review, Cluster K confirmation) raised whether ISOTYPE is the right school for this story. The argument the design wants to make is a per-capita normalization story — the school's absolute-count grammar actively resists this argument. Per-capita comparison requires a different kind of encoding (ratio, proportion) than ISOTYPE's repeated-icon grammar naturally delivers. However, the mismatch is partial rather than significant: paired ISOTYPE charts can tell this story; the designer chose an incomplete version of the school's own prescription (one chart instead of two).
- Assessment: **Partial mismatch** (the school can tell the story; the designer chose the wrong version of the school's grammar for a per-capita claim)
- Dock: **−1 from School Fidelity**
- School Fidelity revised: 16.5 → 15.5

**Amendment L — Variable selection disclosure:**
The chart encodes absolute ocean plastic inputs without per-capita context. The title does not declare this limitation. The Statistician (Innovation #115) called it "present-but-inaccessible context as Step B failure." Under v1.9 variable-selection disclosure: key variable excluded without declaration, creating a framing effect (viewers read absolute tonnage as proportional responsibility).
- Assessment: **Key variable excluded without declaration; exclusion creates framing effect**
- Dock: **−1 from Data/Story Integrity**
- Data/Story Integrity revised: 14.4 → 13.4

**v1.9 weighted score:**

| Dimension | v1.6 Weighted | v1.9 Adjustment | v1.9 Weighted |
|-----------|--------------|-----------------|--------------|
| School Fidelity /20 | 16.5 | −1.0 | 15.5 |
| Data/Story Integrity /20 | 14.4 | −1.0 | 13.4 |
| Legibility /15 | 12.5 | — | 12.5 |
| Visual Economy /15 | 12.9 | — | 12.9 |
| Resonance /15 | 11.1 | — | 11.1 |
| Craft /15 | 12.0 | — | 12.0 |
| **Total /100** | **79.4** | **−2.0** | **77.4** |

**v1.9 score: 77.4 / 100. Gate: PASS**

---

## Work 0013 — Schematic Science Network

**v1.6 score: 76.4**

**Amendment K — School-story match:**
The panel already identified this as the clearest school-story mismatch in the original design set. Beck's schematic-cartography grammar was designed for transit navigation with a geographic anchor and a single navigational variable (line + color for route). Applied to a science co-authorship network with five domain-colors, no natural geographic anchor (ghost continent is a workaround), and two simultaneous navigational variables (color + weight), the grammar is significantly strained. The Historian (Innovation #121) named the geographic anchor substitution problem. Tufte (Innovation #119) prescribed importing a solution from statistical-graphics (small multiples) because Beck's own grammar could not solve the multi-domain legibility problem within its constraints. This is significant mismatch territory.
- Assessment: **Significant mismatch** (Beck grammar cannot fully solve the five-domain, no-anchor problem without importing tools from another school)
- Dock: **−3 from School Fidelity**
- School Fidelity revised: 14.5 → 11.5

**Amendment L — Variable selection disclosure:**
Data/Story Integrity panel scores were already in the 14–15 range (moderate), reflecting concerns about the ghost continent and line-weight ambiguity. No active variable-exclusion misleading identified — the network shows what it claims to show (co-authorship connections), and the story's variables are all encoded. No dock applied.
- Assessment: **Well-disclosed** — no L adjustment

**v1.9 weighted score:**

| Dimension | v1.6 Weighted | v1.9 Adjustment | v1.9 Weighted |
|-----------|--------------|-----------------|--------------|
| School Fidelity /20 | 14.5 | −3.0 | 11.5 |
| Data/Story Integrity /20 | 14.9 | — | 14.9 |
| Legibility /15 | 11.4 | — | 11.4 |
| Visual Economy /15 | 11.1 | — | 11.1 |
| Resonance /15 | 11.6 | — | 11.6 |
| Craft /15 | 12.9 | — | 12.9 |
| **Total /100** | **76.4** | **−3.0** | **73.4** |

**v1.9 score: 73.4 / 100. Gate: PASS**

---

## Work 0014 — Maternal Mortality Race

**v1.6 score: 82.9**

**Amendment K — School-story match:**
The advocacy-visualization school is precisely the right school for this story (racial health disparity requiring legislative action). The diptych form for a two-level argument (racial gap within US + US/international comparison) is a correctly-chosen advocacy structure. School Fidelity panel scores were 15–17. No K adjustment.
- Assessment: **Well-matched**
- Dock: **None**

**Amendment L — Variable selection disclosure:**
The panel praised the variable selection. Data sources are fully declared (CDC WONDER + OECD). ICD coding change declared. COVID period flagged. All relevant variables encoded. The Statistician gave the strongest data praise of any work in the project. The one gap (OECD comparability on postpartum windows) was identified but is a minor Step A issue already reflected in the v1.6 score.
- Assessment: **Well-declared**
- Dock: **None** (existing Step A score already accounts for the OECD comparability gap)

**v1.9 score: 82.9 / 100 (unchanged). Gate: PASS**

---

## Work 0015 — Kandinsky Waiting

**v1.6 score: 83.5**

**Amendment K — School-story match:**
The abstract-art / Kandinsky grammar is the appropriate school for encoding psychological states. However, Bertin and Tufte both raised a version of school-story mismatch that operates in reverse: not "wrong school for this story" but "this school's accuracy standard is insufficient for this story." The formal grammar can encode anticipatory tension; it cannot uniquely determine "waiting" vs. adjacent psychological states (longing, chronic grief). This is a partial mismatch in the reverse direction — the school is partially insufficient for the precision of the claim.
- Assessment: **Partial mismatch** (school is the appropriate school for psychological states; the story's claim is more specific than the school's grammar can demonstrate uniquely)
- Dock: **−1 from School Fidelity**
- School Fidelity revised: 17.2 → 16.2

**Amendment L — Variable selection disclosure:**
Abstract compositional work. The "variables" are formal properties (point tension, line velocity, color temperature), not external data. Variable selection disclosure as a Data/Story Integrity step applies to reportive works encoding external data; demonstrative encoding works are assessed under Step E. No L adjustment applicable.
- Assessment: **Step E pathway applies** (demonstrative encoding)
- Dock: **None**

**v1.9 weighted score:**

| Dimension | v1.6 Weighted | v1.9 Adjustment | v1.9 Weighted |
|-----------|--------------|-----------------|--------------|
| School Fidelity /20 | 17.2 | −1.0 | 16.2 |
| Data/Story Integrity /20 | 13.9 | — | 13.9 |
| Legibility /15 | 12.2 | — | 12.2 |
| Visual Economy /15 | 13.8 | — | 13.8 |
| Resonance /15 | 12.9 | — | 12.9 |
| Craft /15 | 13.5 | — | 13.5 |
| **Total /100** | **83.5** | **−1.0** | **82.5** |

**v1.9 score: 82.5 / 100. Gate: PASS**

---

## Work 0016 — Haeckel Coccolithophores

**v1.6 score: 86.0**

**Amendment K — School-story match:**
The scientific-illustration school is precisely the right school for this story (morphological taxonomy of five coccolithophore species). The school's grammar — species-level morphological comparison at consistent scale — is the most efficient and honest encoding for this argument. No K adjustment.
- Assessment: **Well-matched**
- Dock: **None**

**Amendment L — Variable selection disclosure:**
The work encodes the morphological variables it claims to encode. The one gap (absence of size-comparison inset showing true relative scale) is a Design Revision Recommendation, not a variable-selection misleading — the schematic equalization convention is documented in the school's grammar, and the plate does not claim to show true relative scale. No L adjustment.
- Assessment: **Well-matched to school conventions**
- Dock: **None**

**v1.9 score: 86.0 / 100 (unchanged). Gate: PASS**

---

## Summary Table

| Work | v1.6 Score | K dock | L dock | v1.9 Score | Change |
|------|------------|--------|--------|------------|--------|
| 0011 Urban Heat Island | 80.8 | −2 | −2 | 76.8 | −4.0 |
| 0012 ISOTYPE Plastic | 79.4 | −1 | −1 | 77.4 | −2.0 |
| 0013 Science Network | 76.4 | −3 | 0 | 73.4 | −3.0 |
| 0014 Maternal Mortality | 82.9 | 0 | 0 | 82.9 | 0 |
| 0015 Kandinsky Waiting | 83.5 | −1 | 0 | 82.5 | −1.0 |
| 0016 Coccolithophores | 86.0 | 0 | 0 | 86.0 | 0 |

**Key finding:** The K and L amendments provide formal vocabulary for failure modes the panels already identified qualitatively. Works 0011–0013 were already the weakest of the original designs; v1.9 confirms that their weaknesses are structural (wrong school for the story; variable selection misleads). Works 0014–0016 are essentially unchanged: well-matched school, well-declared variables.

**The school-story match assessment (Amendment K) is the more consequential amendment.** It docks 1–3 points depending on mismatch severity; its implications for work 0013 (−3) are the most significant. The variable selection disclosure (Amendment L) largely codifies what Step A already implied; its main effect is making the title-data gap in 0011 formally punishable.
