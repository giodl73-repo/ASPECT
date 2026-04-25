---
work: 0037-iss-assembly-map
stage: panel
rubric_version: v2.0
created: 2026-04-23
gate: PASS
---

# Panel SUMMARY — 0037 ISS Assembly Map (1998-2024)

## Score Table

| Dimension | Bertin (30%) | Tufte (25%) | Kandinsky (20%) | Historian (15%) | Audience (10%) | Weighted |
|-----------|-------------|------------|----------------|----------------|---------------|---------|
| School Fidelity /20 | 17 | 17 | 16 | 17 | 14 | 16.5 |
| Integrity /20 | 17 | 17 | 17 | 17 | 16 | 16.9 |
| Legibility /15 | 12 | 12 | 11 | 13 | 11 | 11.9 |
| Execution /15 | 13 | 13 | 13 | 13 | 12 | 12.9 |
| Resonance /15 | 12 | 13 | 13 | 13 | 12 | 12.6 |
| Purpose /15 | 13 | 13 | 13 | 13 | 13 | 13.0 |
| **Total /100** | **84** | **85** | **83** | **86** | **78** | **83.8** |

**Weighted aggregate: 83.8 / 100**
**Gate: PASS**

---

## Weighted Calculation

- Bertin (30%): 84 × 0.30 = 25.20
- Tufte (25%): 85 × 0.25 = 21.25
- Kandinsky (20%): 83 × 0.20 = 16.60
- Historian (15%): 86 × 0.15 = 12.90
- Audience (10%): 78 × 0.10 = 7.80
- **Total: 83.75 / 100**

---

## Key Agreements

**The self-referential grammar creates a domain Resonance bonus without general audience Legibility cost.** This is the central Cluster S finding. All five reviewers confirm: the informed viewer (aerospace engineer, space historian, information-architecture practitioner) who recognizes that this diagram uses the same grammar as ISS mission planning tools receives a resonance bonus. The general viewer (Audience lens) reads the diagram as a node-connection diagram because it is one — the meta-level is completely invisible to them. The self-referential grammar is invisible to those who do not recognize it and rewarding to those who do.

**The docking sequence vs. physical adjacency declaration is required.** All reviewers flag this: the diagram must declare that connections represent docking sequence (chronological order of attachment), not physical adjacency. Without this declaration, the diagram will be misread by a significant fraction of viewers.

**Five variables are correctly encoded.** Bertin confirms: all five variable-to-encoding pairings are grammatically correct. The one concern is the X/Y concordance issue when launch year and construction sequence order differ for the same module.

---

## Key Tensions

**Bertin on X/Y concordance**: when a module was launched before an earlier-docked predecessor, X-position (construction sequence) and Y-position (launch year) are discordant. This creates potential visual confusion. Resolution: declare the discordance in the encoding note; annotate discordant modules.

**Kandinsky on composition vs. grid**: using both X and Y for ordered variables risks a mechanical grid arrangement rather than a dynamic composition. Resolution: test the layout at full density; use connection routing (bezier arcs, not straight lines) to prevent grid-lock.

**Audience on the meta-level**: the Audience reviewer has no access to the self-referential dimension and scores Resonance lower as a result. This is the correct outcome — the meta-level's domain-specificity means its Resonance is domain-gated. The panel accepts this asymmetry: domain resonance is high; general resonance is moderate.

---

## Innovations Flagged (5 total)

| # | Name | Reviewer | Rubric Anchor | Cluster | Status |
|---|------|----------|---------------|---------|--------|
| 248 | Self-referential grammar as domain resonance bonus | Bertin | Resonance | **S** | **CONFIRMS** |
| 249 | Self-referential grammar: Resonance bonus without visual cost | Tufte | Resonance / Execution | **S** | **CONFIRMS** |
| 250 | Emergent composition from political encoding | Kandinsky | Resonance | S adjacent | New |
| 251 | Shared grammar as historical authenticity | Historian | School Fidelity | **S** | **CONFIRMS** |
| 252 | Meta-level invisibility as criterion for self-referential grammar success | Audience | Legibility / Resonance | **S** | **CONFIRMS** |

---

## CLUSTER S — CONFIRMED ACROSS WORKS 0028 + 0037

**Cluster S: Meta-visualization and self-referential diagrams** is confirmed across two works.

- **Work 0028** (#212 Tufte: self-referential diagram and recursive integrity; #214 Historian: meta-visualization as school fidelity category): the DEGAS rubric system map used information-architecture grammar to document an information-architecture system, raising the question of whether a diagram that uses the grammar of its subject creates integrity or resonance effects.
- **Work 0037** (#248 Bertin, #249 Tufte, #251 Historian, #252 Audience): the ISS assembly map confirms the Cluster S finding in a different domain (aerospace engineering vs. rubric documentation) with a clear answer to the question work 0028 raised.

**The confirmed finding:**

Self-referential grammar — using the same visual grammar as the subject being documented — produces:
1. **Resonance bonus for domain experts** (confirmed by Bertin, Tufte, Historian): viewers who recognize the recursion receive a moment of pleasurable recognition that amplifies the primary informational effect
2. **Legibility neutral for general audiences** (confirmed by Audience lens): viewers who do not recognize the recursion read the primary diagram correctly without interference from the meta-level
3. **Historical authenticity** (Historian innovation #251): using the subject community's own visual grammar is a form of historical fidelity, not merely a compositional flourish
4. **No additional visual complexity** (Tufte #249): the meta-level is invisible in the diagram's visual structure — it adds no marks, no additional encoding, no complexity

**The failure mode** (from work 0028's self-referential integrity question, #212): a self-referential diagram that fails to apply its own grammar correctly is a deeper integrity violation than an ordinary diagram that fails its grammar — the self-reference creates a higher standard of grammar compliance. In work 0037, this integrity standard is met: the docking-sequence grammar that documents the ISS's assembly is correctly applied.

**Amendment recommendation:** Add to Resonance dimension, under Domain type:

> *Self-referential grammar (meta-visualization):* a work that uses the same visual grammar as the system or subject it documents achieves domain resonance through the recursive recognition available to initiated viewers. Score this as Domain resonance (available to initiated viewers; partial or absent to others). The meta-level should not add visual complexity to the primary reading — it should be invisible to non-initiated viewers and rewarding to initiated ones. A self-referential diagram that fails to apply its own grammar correctly is held to a higher integrity standard than an ordinary diagram.

**Status: CLUSTER S CONFIRMED — two works, six reviewer instances across 0028 and 0037, rubric amendment identified.**

---

## Design Revision Priorities

1. **Declare docking sequence vs. physical adjacency** in figure note — required for integrity
2. **Add mass labels to largest nodes** (Zarya, Zvezda, Destiny, Kibo) — improves quantitative legibility without adding visual noise
3. **Solve connection routing at full density** — use bezier arc routing to minimize line crossings; test at 42-mission density before finalizing
4. **Address X/Y concordance** — annotate any module where launch year and construction sequence order are discordant
5. **Consider bicolor nodes for jointly funded modules** — Zarya (Russia-built, US-funded) as a historical nuance worth capturing
