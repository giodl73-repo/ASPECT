---
work: 0028-rubric-system-map
reviewer: bertin
weight: 0.30
rubric_version: v1.11
---

# Bertin — 0028 The DEGAS Rubric as a System Map

## School Fidelity /20 → 17

I will conduct my visual variable audit of all three layers.

**Layer 1 (six dimensions):**
- Position (horizontal): dimension identity — nominal. Shape is a better nominal variable; position is wasted here on a nominal distinction that has no inherent order. However, I accept it because the horizontal position in Layer 1 is correlated with the connection density to Layer 2 below — dimensions that amended more clusters are implicitly positioned near where their cluster nodes cluster in Layer 2. This is a subtle and defensible use of position.
- Node shape: rectangle — consistent across all six. Shape encodes node type correctly (dimension nodes all look alike; they are distinguishable from cluster circles and work small-circles by shape). Correct.
- Color: dimension identity — nominal. Correct; hue is selective and associative, appropriate for nominal categories. The palette is well-chosen: high contrast, distinguishable, accessible.
- Line thickness (correlation): ordered quantitative. Correct — thickness is an ordered variable appropriate for encoding ordered data.
- Line type (solid/dashed/dotted): ordered — strong/moderate/weak. Correct.

**Layer 2 (clusters):**
- Position (horizontal): chronological order — ordered. Correct — horizontal position encodes ordered data.
- Node shape: circle — consistent across all 16. Correct.
- Color: dimension amended — nominal. Matches Layer 1 palette. Correct. The color-coding is the primary connection between layers; it does the critical work of linking cluster to dimension without requiring the viewer to follow an upward arrow.
- Arrow direction: causal direction (cluster amends dimension). Arrows are the correct representation of directed relationships. Upward arrows from cluster to dimension correctly encode the causal direction (bottom-up, as declared).

**Layer 3 (works):**
- Position (horizontal): work number / chronological — ordered. Correct.
- Node shape: small circle — consistent across all 25. Correct.
- Color: work type (canonical/original) — nominal, 2 values. Correct, though light gray vs. warm ochre is a slight color-value confound (ochre is both a different hue AND lighter value than gray). Better: distinguish by saturation only to avoid conflating hue with value.
- Upward line density: innovation productivity — quantitative (approximate). This is the most interesting encoding in the diagram: density of lines from a node is used to encode quantity. This works only because all lines originate from the same vertical position (the work node) and the density is directly countable if the viewer chooses. Innovative — and correct.

**Grammar verdict:** No grammatical errors. All variables correctly matched. The color-continuity between layers (dimension color appears in both Layer 1 nodes and Layer 2 cluster nodes and upward lines from Layer 3) is the diagram's most efficient device — it allows the viewer to trace vertical connections without following individual lines.

Minor dock: the Layer 3 work node color (canonical gray vs. original ochre) should use a cleaner variable distinction — saturation rather than hue-plus-value simultaneously.

## Data/Story Integrity /20 → 16

The diagram represents a real system — the DEGAS rubric's self-improvement loop. The cluster-to-dimension arrows encode real amendments documented in the rubric's amendment history. The work-to-cluster connections encode real innovations logged in the project. The dimension correlation lines (Layer 1) encode patterns observed across 25 works of panel scoring.

One integrity concern: the dimension correlation lines claim to encode observed cross-dimension correlations, but the specification does not declare how these correlations were measured. Are they based on panel score data (do reviewers tend to give similar scores on both dimensions simultaneously)? Or are they based on the designer's qualitative impression? The difference matters — the visual encoding (line thickness as correlation strength) implies quantitative measurement, but the basis may be qualitative.

Step D applies: the correlation claim uses a non-standard analytical framework (observed co-movement of panel scores as evidence of dimension dependency). This should be declared.

## Legibility /15 → 12

Context: contemplative study (academic or practitioner audience). The reading direction is declared (bottom-up arrow). The three-layer structure is visible at reading distance. The color-continuity mechanism (Layer 2 and Layer 3 lines match Layer 1 dimension colors) allows vertical tracing.

The challenge: 25 work nodes in Layer 3, with multiple upward lines from each node to multiple cluster nodes in Layer 2, to multiple dimension nodes in Layer 1. The total number of lines in the diagram is large. Even with color-coding, a viewer who wants to trace a specific work's full innovation path (e.g., "which dimensions did work 0001 contribute to?") must follow multiple colored lines through a potentially crowded middle layer.

This is intrinsic complexity — the system has 25 works and 16 clusters, and their connections are genuinely dense. The design cannot make this simpler without losing real information. The legibility score reflects achievable legibility under intrinsic complexity, not a design failure.

## Visual Economy /15 → 13

The feedback loop annotation (right margin text stack) is the most important economy element: it gives the viewer the meta-reading key without cluttering the main diagram. It is correctly separated. The reading direction arrow is minimal and necessary.

The correlation lines in Layer 1 are the main economy risk — four lines connecting six nodes, with thickness and type encoding strength and character. This is a lot of visual information in a small area (the top band). Reducing to the two strongest correlations (solid thick lines only) and dropping the medium and thin lines might improve economy at modest cost to completeness.

## Resonance /15 → 14

The diagram's primary resonance type is Type I (Aesthetic-Intentional): the viewer who knows the DEGAS project sees their system made visible. Type V (Domain-Gated) is also active: a viewer without DEGAS context will find the diagram interesting as a system diagram but will not experience the recognition that a DEGAS participant experiences.

The three-layer reading (works → clusters → dimensions) produces a genuine "aha" moment for the initiated viewer: the rubric's development is not a linear progression but a bottom-up emergence from the experiences of specific works. That is the system's most important property, and the diagram shows it correctly.

## Craft /15 → 13

The specification demands precision: consistent node sizes, smooth bezier arcs, controlled palette, dense small-type labeling at multiple scales. The small type (6-7pt for work titles and cluster names) is a real execution risk — at these sizes, label legibility depends on high-resolution output or screen display above 100 DPI.

## My Total: 85/100

A strong information architecture work with one correctable visual variable error (Layer 3 color encoding) and one integrity note (correlation basis undeclared). The three-layer structure is well-conceived; the variable matching is sound; the color-continuity mechanism is the design's most important innovation.

## Innovation Flagged

**#211 — Color as inter-layer connection device in multi-layer system maps**: in a diagram with multiple layers representing different system levels, using the same color palette across layers (so that a dimension's color appears in its cluster nodes and in the lines connecting works to clusters) allows the viewer to trace vertical connections without following individual lines. This is a visual grammar technique for multi-level system maps that the rubric's information architecture school documentation does not name. The rubric's Bertin visual variable framework covers in-layer color but not cross-layer color continuity as a navigation device.
