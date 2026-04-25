---
work: 0028-rubric-system-map
stage: panel
rubric_version: v1.11
created: 2026-04-23
gate: PASS
---

# Panel SUMMARY — 0028 The DEGAS Rubric as a System Map

## Score Table

| Dimension | Bertin (30%) | Tufte (25%) | Kandinsky (20%) | Historian (15%) | Audience (10%) | Weighted |
|-----------|-------------|------------|----------------|----------------|---------------|---------|
| School Fidelity /20 | 17 | 16 | 16 | 16 | 14 | 16.1 |
| Data/Story Integrity /20 | 16 | 15 | 16 | 16 | 15 | 15.7 |
| Legibility /15 | 12 | 12 | 12 | 12 | 10 | 11.8 |
| Visual Economy /15 | 13 | 13 | 13 | 13 | 12 | 12.9 |
| Resonance /15 | 14 | 13 | 13 | 13 | 12 | 13.2 |
| Craft /15 | 13 | 13 | 13 | 13 | 12 | 12.9 |
| **Total /100** | **85** | **82** | **83** | **83** | **75** | **82.6** |

**Weighted aggregate: 82.6 / 100**
**Gate: PASS**

---

## Weighted Calculation

- Bertin (30%): 85 × 0.30 = 25.50
- Tufte (25%): 82 × 0.25 = 20.50
- Kandinsky (20%): 83 × 0.20 = 16.60
- Historian (15%): 83 × 0.15 = 12.45
- Audience (10%): 75 × 0.10 = 7.50
- **Total: 82.55 / 100**

---

## Key Agreements

**The three-layer structure is the right form.** All reviewers accept that a three-level hierarchical-causal system (works-clusters-dimensions) maps correctly to a three-layer diagram with bottom-up reading direction. No reviewer recommends an alternate form.

**The color-continuity mechanism is the strongest design element.** Bertin identifies it as the diagram's most efficient device; Kandinsky notes it as compositionally coherent; Audience notes it as the mechanism that makes tracing possible. Bertin flags it as Innovation #211 — a named technique not yet in the information architecture grammar.

**The correlation basis undeclared is the main integrity gap.** Bertin, Tufte, and Historian all flag the Layer 1 correlation line thicknesses as claiming quantitative precision without declaring the analytical basis. This is a Step D issue (analytical framework declaration) and the most important revision target.

---

## Key Tensions

**Kandinsky vs. Bertin on the feedback loop:**

Kandinsky finds the two-voice composition (static map + dynamic annotation) compositionally interesting and productive. Bertin accepts the annotation but notes that the feedback loop is absent from the main diagram's structure. Historian references systems dynamics practice (Forrester, 1968) as the precedent for showing closed loops in system maps. Audience directly says the loop's absence from the main diagram limits resonance.

This tension resolves toward the same recommendation from both angles: close the feedback loop in the main diagram. Bertin and the Historian want it for structural completeness; Kandinsky and Audience want it for resonance.

**Bertin vs. Audience on small type:**

Bertin accepts small type as appropriate for contemplative study with close-reading; Audience finds it a barrier. The resolution: maintain small type but add a separate index panel (work number index, cluster name index) that can be consulted alongside the main diagram.

---

## Innovations Flagged (4 total)

| # | Name | Reviewer | Rubric Anchor | Status |
|---|------|----------|---------------|--------|
| 211 | Color as inter-layer connection device in system maps | Bertin | Visual Economy / Legibility | New |
| 212 | Self-referential diagram and recursive integrity | Tufte | Data/Story Integrity | New |
| 213 | Two-voice composition in static system maps | Kandinsky | Resonance / School Fidelity | New |
| 214 | Meta-visualization as school fidelity category | Historian | School Fidelity | New |

**Cluster watch:** #212 and #214 are both about meta-visualization and self-referential diagrams — same concern from two reviewers. Candidate for Cluster S.

---

## Design Revision Priorities

1. **Declare the correlation basis**: add a footnote or legend note explaining how the Layer 1 correlation line thicknesses were determined (e.g., "based on panel score co-variance across 25 works")
2. **Close the feedback loop visually**: add a curved arrow from the Layer 1 dimension region back down to the Layer 3 work region, closing the self-improvement loop in the main diagram
3. **Add a work/cluster index panel**: a separate panel listing work numbers with one-line titles, and cluster letters with full names — allows close reading without requiring 6pt label legibility at viewing distance
4. **Declare the bezier arc convention**: add a legend note that curved lines in Layer 1 indicate correlation (not causation); straight arrows indicate causal direction
