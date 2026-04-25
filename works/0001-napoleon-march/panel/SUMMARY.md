---
work: 0001-napoleon-march
stage: panel
rubric_version: v1.0
created: 2026-04-23
gate: PASS
---

# Panel SUMMARY — 0001 Napoleon March

## Score Table

| Dimension | Minard (30%) | Tufte (25%) | Bertin (20%) | Statistician (15%) | Artist (10%) | Weighted |
|-----------|-------------|------------|-------------|-------------------|--------------|---------|
| School Fidelity /20 | 17 | 15 | 14 | — | — | 15.5 |
| Data/Story Integrity /20 | 18 | 17 | 18 | 13 | — | 17.0 |
| Legibility /15 | 13 | 12 | 11 | 11 | — | 12.0 |
| Visual Economy /15 | 14 | 15 | 14 | — | — | 14.3 |
| Resonance /15 | 15 | 14 | 13 | — | 15 | 14.2 |
| Craft /15 | 14 | 12 | 13 | — | 13 | 13.1 |
| **Total /100** | **91** | **85** | **83** | — | — | **86.1** |

*Lens reviewers (Statistician, Artist) score only their focal dimensions; their scores replace persona scores in those dimensions for weighting purposes.*

**Weighted aggregate: 86.1 / 100**  
**Gate status: PASS**

---

## Key Agreements

**Visual economy is exceptional.** All three personas agree: there is nothing to remove. Tufte gives perfect marks; Minard and Bertin deduct only for the terrain shading. This is the work's strongest dimension by consensus.

**Data integrity is strong but uncertified.** All reviewers acknowledge that the troop counts and temperature readings are probably substantially correct but cannot be verified to the precision implied by the visual form. There is no uncertainty declaration anywhere in the work. The integrity failure is one of form (implied precision > actual precision), not of substance (the direction of the argument is correct).

**Legibility costs the work.** The dual-axis horizontal bridge — geographic longitude above, temporal position below — is not self-evident. Readers must discover it. This is the primary legibility failure and all reviewers flag it.

---

## Key Tensions

**Does School Fidelity apply to a school-founding work?**  
Minard argues the work cannot be scored on school fidelity because no school existed to be faithful to in 1869. Tufte accepts the penalty reluctantly, noting it distorts the score. Bertin scores it on fidelity to the principles of both schools the work participates in, independently. The panel has three incompatible positions on this dimension for this type of work. *This is a rubric problem, not a reviewer disagreement.*

**Resonance: designed or emergent?**  
Minard claims the resonance is emergent from the data — he designed the encoding to be accurate; the tragedy is what the data does, not what he chose. The Artist disagrees, arguing that the choice to use a form (the band) that reads as organic mass was deliberate, even if the emotional effect exceeded the intention. Tufte holds a middle position: the work achieves resonance through encoding fidelity, but the temperature chart's emotional weight requires active effort from the reader to connect to the band — the link is provided but not resolved. These are not positions that can be reconciled. They reveal that the Resonance dimension is currently unable to distinguish between types of resonance.

**Causation from juxtaposition.**  
The Statistician identifies implied causation (cold → deaths) from spatial proximity. None of the personas address this. The Artist finds it appropriate — the juxtaposition is the work's most powerful compositional choice. Tufte would likely agree the data does not fully support the causal reading but would accept the juxtaposition as the reader's responsibility to interpret. This tension is productive: the work uses compositional argument (spatial proximity as implied causation) in a way the rubric does not score.

---

## Innovations Flagged (8 total)

| # | Name | Reviewer | Rubric Anchor | Status |
|---|------|----------|---------------|--------|
| 1 | Multi-school synthesis as founding act | Minard | School Fidelity | New |
| 2 | Spatial mourning (emergent-data resonance) | Minard | Resonance | New |
| 3 | Dual-axis horizontal bridge | Tufte | Visual Economy / School Fidelity | New |
| 4 | Confidence suppression | Tufte | Data/Story Integrity | New |
| 5 | Connotative variable layer | Bertin | School Fidelity / Data Integrity | New |
| 6 | Geographic-temporal compression via monotonic path | Bertin | Data/Story Integrity | New |
| 7 | Implied causation from juxtaposition | Statistician | Data/Story Integrity | New |
| 8 | Data anthropomorphism | Artist | Resonance | New |
| 9 | Punctuation failure at rupture events | Artist | Craft / Resonance | New |

*9 innovations from a single canonical review. This is a strong signal that the rubric was written with insufficient prior work.*

---

## Cluster Analysis (immediate)

**Cluster A — Resonance needs sub-types (innovations 2, 8):**  
Both Minard and the Artist flag that the Resonance dimension cannot distinguish between:
- **Aesthetic-intentional resonance** (designer chose to make something beautiful/affecting)
- **Emergent-data resonance** (the encoding's fidelity to the data produces affect as a side effect)
- **Data anthropomorphism** (encoding human quantities through visual mass, producing witnessing rather than reading)

Two innovations across different reviewers in the same work. Not yet across 2+ works — amendment threshold not met. *Watch for this cluster in work 0002.*

**Cluster B — Data Integrity needs uncertainty scoring (innovations 4, 7):**  
Tufte's confidence suppression and the Statistician's implied-causation-from-juxtaposition both address the same gap: the Data/Story Integrity dimension does not assess the relationship between implied precision/causation and actual data quality. Two innovations from different reviewers in the same work. *Watch for work 0002.*

**Cluster C — School Fidelity cannot handle synthesis (innovations 1, 3, 5):**  
Minard, Tufte, and Bertin all reach a version of the same conclusion: School Fidelity, as currently written, cannot score multi-school synthesis or school-founding works. Three innovations pointing at the same gap from three different reviewers. *This cluster is strong. Consider amendment after work 0002 confirms.*

---

## Design Recommendations

*(Not applicable for canonical imports. The work is historical and complete. Recommendations are for the rubric and pipeline, not for revision of Minard's work.)*

1. **Amend School Fidelity** to distinguish: (a) school-member works, (b) school-founding works, (c) deliberate multi-school synthesis, (d) accidental school mixing. Scoring logic differs for each.

2. **Amend Resonance** to recognize three sub-types: aesthetic-intentional, emergent-data, and data-anthropomorphic. Current anchors cannot distinguish them.

3. **Add a `degas-review` skill** for canonical imports. The current pipeline (`degas-brief` → `degas-design` → `degas-panel`) fits invented works; imported canonical works need a slightly different entry path where the design document is a description rather than a specification.

4. **Add uncertainty declaration as a criterion** to Data/Story Integrity anchors — does the work declare the precision limits of its source data?

5. **Watch work 0002** for Cluster A and B confirmation before amending.
