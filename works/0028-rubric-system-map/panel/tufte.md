---
work: 0028-rubric-system-map
reviewer: tufte
weight: 0.25
rubric_version: v1.11
---

# Tufte — 0028 The DEGAS Rubric as a System Map

## School Fidelity /20 → 16

Information architecture is a legitimate school and this work applies its grammar correctly. Nodes for entities, edges for relationships, reading direction declared, node types visually distinguished. The three-layer structure is the appropriate form for representing a three-level hierarchical-causal system.

My fidelity concern: the work claims to show a system, and it does. But system maps of self-referential systems (a rubric that evaluates visualizations, mapped as a visualization) have a peculiar grammar problem: the diagram is subject to its own evaluation criteria. The work asserts, without demonstrating, that the dimension correlations shown in Layer 1 are real. If I apply the information architecture school's own criterion (are the relationships encoded by edges real and verifiable?), the correlation lines need their empirical basis declared.

## Data/Story Integrity /20 → 15

The cluster-to-dimension arrows are factual: the amendment history documents which clusters amended which dimensions. The work-to-cluster lines are factual: the innovations log documents which works triggered which clusters. These elements of the diagram are verifiable.

The Layer 1 dimension correlation lines are the integrity risk. The specification states that line thickness encodes "strength of correlation" based on "observed cross-dimension interactions from the panel data." This is a claim about the panel scoring data — specifically, that dimension scores co-move in ways that imply underlying dependency. This claim:

1. Requires a specific analytical method (panel data regression, or at minimum correlation calculation)
2. Is presented as a visual encoding (thickness) implying quantitative precision
3. Is not declared or sourced in the design specification

Step D: analytical framework undeclared. The correlation claim depends on a non-standard analytical framework (co-movement of panel scores as evidence of dimension dependency). Without declaration, the viewer cannot verify or challenge it. Dock -2.

## Legibility /15 → 12

Context: contemplative study, academic/practitioner audience. The reading direction is declared clearly. The three-layer structure is visible and the layer functions are labeled. A patient reader can trace any specific connection path.

The complexity of 25 work nodes with multiple upward lines is intrinsic — the system has this many connections. The color-coding mechanism (Layer 2 and Layer 3 lines colored by dimension) is the most important legibility device. Without it, the diagram would require line-following across dense crossing paths.

My efficiency concern: the small type (6-7pt for work titles and cluster names) is at the edge of comfortable reading. For a printed diagram, this requires close approach. For a screen diagram, zoom is available. The primary context should be specified.

## Visual Economy /15 → 13

This is a complex diagram of a complex system. The first economy question: is the complexity intrinsic or additive? It is largely intrinsic — the system has 25 works, 16 clusters, and 6 dimensions, and their connections are real. The correlation lines in Layer 1 add some economy risk (4 lines with thickness and type encoding) but they encode real claimed relationships.

The feedback loop annotation in the right margin is excellent economy practice: it provides the meta-reading key without cluttering the main diagram. This is the kind of structural annotation I endorse — it reduces cognitive load without encoding data.

The one decorative element I note: the smooth bezier arcs for correlation lines in Layer 1 are aesthetically pleasant but slightly more complex to render and read than straight lines would be. The smoothness adds visual comfort at small economy cost.

## Resonance /15 → 13

The diagram produces genuine insight for the DEGAS-familiar viewer: the rubric's development is visible as a bottom-up emergence from work experiences. This is not obvious from reading the amendment history — it requires seeing all the connections simultaneously. The system map delivers this holistic view.

The system map also shows something I did not previously see clearly: the uneven distribution of innovation productivity across works. The line density from early canonical imports (0001-0010) vs. later works is visible as a compositional weight difference. This is Type II resonance (emergent-data) alongside the primary Type I (aesthetic-intentional).

## Craft /15 → 13

The specification is precise and the palette is well-designed. The main execution risks are: small-type legibility at 6-7pt, bezier arc smoothness for 16-cluster upward arrows, and the color-continuity mechanism across all three layers. These are achievable with careful execution.

## My Total: 82/100

A well-designed system map with one significant integrity gap (correlation basis undeclared) and solid execution across all other dimensions. The three-layer structure is the right form; the visual variable matching is sound (Bertin will verify this more thoroughly); the color-continuity mechanism is elegant.

## Innovation Flagged

**#212 — Self-referential diagram: the diagram is assessed by the same rubric it maps**: when a visualization represents the system that evaluates visualizations, the diagram is subject to evaluation by the criteria it depicts. This creates a logical recursion that is not accounted for by any current rubric dimension. The Data/Story Integrity dimension would need to assess whether the diagram is internally consistent with the rubric it claims to represent — a different kind of integrity check than correspondence to external data.
