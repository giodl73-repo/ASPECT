---
work: 0005-snow-cholera-map
stage: panel
reviewer: bertin
rubric_version: v1.3
created: 2026-04-23
---

# Bertin — Panel Review

*School type: B (Founder).*

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type B) | 18 | 20 |
| Data/Story Integrity | 17 | 20 |
| Legibility (contemplative-study context) | 13 | 15 |
| Visual Economy | 15 | 15 |
| Resonance | 12 | 15 |
| Craft | 13 | 15 |
| **Total** | **88** | **100** |

## Review

**Visual variable audit:**

*Death count at address → stacked marks (size/count):* One mark per death, stacked perpendicular to the street. Size/count is ordered and quantitative-capable at low densities; at high densities (where deaths are so numerous that bars merge), counting becomes unreliable. The encoding is correct in principle; it fails at peak density. This is a variable-capacity failure — the chosen variable (count of discrete marks) saturates before the data range is exhausted.

*Address location → geographic position:* Correct. Position is the highest-fidelity variable for spatial data. Geographic position for geographic data is the right assignment.

*Bar orientation → perpendicular to street:* This is an encoding I want to examine. The bars are not vertical; they are perpendicular to whatever direction the street runs. This means the bars on a north-south street point east-west, and the bars on an east-west street point north-south. The visual result: the bars radiate from the streets in the direction a pedestrian would walk away from the building. The orientation is not encoding data — death direction is not a variable. The orientation is following the street geometry for visual coherence. This is what I would call a structural encoding: a visual variable choice driven by the structure of the display surface rather than by a data variable. Not incorrect, but worth naming.

*Pump location → shape (circle/cross):* Shape is selective — the viewer can group all pump marks without reading labels. Correct for a categorical binary (pump/not-pump). The failure: all pump symbols are identical, making source/control discrimination require label-reading rather than visual variable differentiation. If Snow had used two shape variants (one for the suspected source, one for controls), the causal argument would be available at the retinal level rather than requiring the viewer to identify Broad Street by label.

**On this work and Cluster F:**

This map is a direct test of the Cluster F question (data model declaration). Snow's data model is: *spatial clustering of events around a candidate source is evidence for that source's causal role.* This is not geography-for-its-own-sake. It is a specific analytical claim about what spatial distribution proves.

The rubric currently asks: is the encoding faithful to the data? For Snow, the data IS spatial location of deaths. Geographic position for geographic data is the correct encoding. But the ARGUMENT — that clustering around the pump indicates the pump as source — requires a data model beyond "deaths have locations." It requires: "spatial clustering of events implies a nearby common cause."

This data model is not declared on the map. The viewer sees deaths plotted at their locations. The viewer must supply the analytical model (clustering = causal evidence) to complete the argument. In 1854, this model was not established — Snow was proposing it, not invoking it. The map presents spatial data with an undeclared analytical framework that constitutes the causal claim. This confirms Cluster F: the data model must be declared, not assumed. Score for School Fidelity reflects this gap.

**On School Fidelity (Type B):**

The founding grammar is recoverable and strong. Score 18 rather than 19 because the pump-shape undifferentiation (discussed above) is a grammar gap that subsequent practitioners have often missed or had to solve separately.

**On Data/Story Integrity:**

Step A: strong — Snow's data collection was careful and first-hand. Step B: no accuracy tradeoff — individual death marks are the most accurate available encoding for point event data. Step C: the clustering-as-causation argument is implied, not proven. The negative evidence (brewery, workhouse) significantly strengthens it. Dock −2 for the causal claim's strength relative to the evidence available in 1854 (no mechanism known). Score 17.

**On Legibility:**

*Context: contemplative study, medical/scientific reader.*

[Contemporary context: 11/15 — the spatial pattern is visible; the analytical framework (clustering = causal evidence) requires instruction to supply]

For the primary context: a physician in 1855 can follow the spatial argument if they accept the causal framework. The visual saturation at the Broad Street cluster makes individual counting unreliable. The pump-symbol uniformity requires label-reading to identify Broad Street. Score 13.

**On Visual Economy:**

Fifteen. There is nothing here that is not data or scaffold. The street grid is the coordinate system without which the point data has no position — equivalent to Minard's geographic base. Every bar is a death. Every symbol is a pump. The black-and-white constraint (no color available) means no additional variable can be encoded; Snow makes correct use of what he has. Score 15.

**On Resonance:**

E1 (domain-gated): strongly present. An epidemiologist sees the founding method immediately. A general viewer sees a historical curiosity. The domain gap is large — epidemiology is a technical field, and its founding logic (clustering as causal evidence) is not intuitive to non-practitioners.

E2 (delayed): present, of the epistemic variety. The delay was a consequence of germ theory's timeline, not political suppression. Distinct from Du Bois.

No testimonial resonance. Score 12.

**On Craft:**

The engraving is correct but the scale creates the mark-saturation problem at peak-density addresses. Score 13.

## Innovations Flagged

1. **Variable-capacity saturation** — a visual variable that works correctly at moderate data density but fails at peak density because the variable cannot represent the full range of values. The stacked-bar encoding works at addresses with 1–5 deaths; at addresses with 10–15 deaths the bars merge and the count becomes visual mass rather than countable marks. This is not the designer's error in choosing the variable; it is a property of all discrete-mark encodings that there is a density ceiling above which the encoding saturates. *Rubric anchor: Data/Story Integrity / Craft. Implication: the rubric should assess whether a discrete-mark encoding has sufficient resolution across the data range — and note when peak-density values exceed the variable's readable capacity.*

2. **Analytical data model as undeclared assumption** — some works present data faithfully while relying on an undeclared analytical framework to complete the argument. Snow plots deaths correctly; the causal argument requires the additional premise that spatial clustering implies a nearby common cause. This premise was not established in 1854; Snow was proposing it. The map presents data and leaves the analytical model implicit. *This directly confirms Cluster F.* The data model must be declared, not assumed — especially when the model itself is the scientific innovation. *Rubric anchor: Data/Story Integrity. Implication: add a Step D to Data/Story Integrity: analytical framework declaration. Works that rely on an analytical framework to complete their argument (beyond encoding faithfulness) should state the framework, especially when the framework is novel.*
