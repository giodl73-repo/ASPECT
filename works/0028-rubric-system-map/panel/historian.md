---
work: 0028-rubric-system-map
reviewer: historian
weight: 0.15
rubric_version: v1.11
---

# Historian Lens — 0028 The DEGAS Rubric as a System Map

## School Fidelity /20 → 16

The information architecture school's grammar, as documented in the DEGAS schools file, requires: nodes for entities, edges for relationships, reading direction declared, hierarchy encoded by position or containment, consistent visual vocabulary, minimize edge crossings. This work satisfies all of these.

The school precedents most relevant here are: UML (Unified Modeling Language) sequence diagrams, which show entities at the top and interactions flowing downward — this work inverts that convention (reading bottom-up), which is the right choice for a bottom-up causal system. Yourdon data flow diagrams use circle nodes for processes and rectangle nodes for external entities — this work uses the same distinctions (rectangle for highest-system-level, circles for process-level nodes) consistently.

The most historically significant precedent I reach for: systems dynamics stock-and-flow diagrams (Forrester, 1968). In stock-and-flow diagrams, stocks are rectangles, flows are arrows with valve symbols, and the feedback loop is explicitly drawn as a closed loop. This work does not draw the feedback loop as a closed loop in the main diagram — it represents it only in the right-margin annotation. A true systems dynamics approach would draw the loop closing back from "dimension scoring" to "works." This is not a fidelity failure — it would make the diagram significantly more complex — but it is a design choice worth acknowledging.

## Data/Story Integrity /20 → 16

The diagram represents documented facts about the DEGAS project. I have access to the TRACKER.md and rubric files and can verify: the cluster-to-dimension amendments are accurate (checked against the amendment history); the work counts and cluster counts are accurate; the color-coding by dimension is consistent with the rubric.

The correlation lines in Layer 1 represent observed patterns across panel scoring data. I cannot independently verify the correlation strengths from the materials available, but I note that the correlations claimed (Visual Economy — Legibility; School Fidelity — Data Integrity; Resonance — Craft) are consistent with what I have observed in reading the panel reviews. The analytical basis should be stated more explicitly, but the claims are plausible.

## Legibility /15 → 12

Context: academic/practitioner audience, contemplative study. For this audience, the diagram is legible. The three layers are clearly bounded; the reading direction is declared; the visual vocabulary is consistent throughout. A practitioner familiar with information architecture conventions can read this diagram's structure within 30 seconds.

The density of Layer 3 (25 nodes with multiple upward lines) is the primary legibility challenge. The color-coding mechanism is the key mitigation. Without it, the diagram would require line-following through a dense web. With it, the viewer can track by color rather than by line — a significant improvement.

One historical note: information architects have traditionally dealt with diagrams of this complexity by adding interactive features (hover states that highlight selected paths, filtering by dimension). A static version of this diagram is a defensible choice but accepts a legibility limitation that an interactive version would not have.

## Visual Economy /15 → 13

The specification calls for a well-economized diagram. The feedback loop annotation is correctly separated. The small-type labels are demanding but necessary. The one element I question from a historical/school perspective: the bezier arc curves in Layer 1 correlation lines. Straight lines are the information architecture convention for correlation or association; curves are sometimes used to distinguish curved connections from straight-line flows. Here, curves are used to visually distinguish correlation from causation. This is a bespoke convention that works but should be declared in the legend.

## Resonance /15 → 13

For the DEGAS practitioner audience, the resonance is high. Seeing the system you work in represented as a system map produces the specific pleasure of recognition — "yes, this is the structure I have been working within." The three-layer structure makes visible a hierarchy that is implicit in the project's practices but has not been diagrammed before.

The meta-visualization aspect is also resonant: a visualization of the visualization evaluation system is a playful and serious move simultaneously. It demonstrates that the system is coherent enough to be mapped.

## Craft /15 → 13

The specification is precisely written and the palette is well-chosen. The historical information architecture tradition emphasizes drafting precision — consistent node sizes, clean line routing, controlled label spacing. The specification's attention to these details is appropriate to the school.

## My Total: 83/100

A well-executed information architecture work that correctly applies the school's grammar while making a genuine contribution: it makes visible the DEGAS system's three-level structure and the feedback loop that drives it. The main gap is the undeclared correlation basis for the Layer 1 dimension connections. The secondary gap is the failure to close the feedback loop in the main diagram.

## Innovation Flagged

**#214 — Meta-visualization as a school fidelity category**: a visualization that represents the evaluation system that will assess it is a specific form of meta-visualization without precedent in the information architecture school literature. The school's grammar tells us how to represent systems — but does not address what happens when the system being represented is the same one applying the grammar. This recursion creates a unique school fidelity consideration: the diagram must be internally consistent with the rubric it depicts.
