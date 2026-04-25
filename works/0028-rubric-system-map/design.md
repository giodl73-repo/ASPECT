---
work: 0028-rubric-system-map
title: The DEGAS Rubric as a System Map
school: information-architecture
type: A (School Member)
rubric_version: v1.11
created: 2026-04-23
---

# Design Specification — 0028 The DEGAS Rubric as a System Map

## Canvas

Landscape orientation, 90cm wide x 60cm tall (or 1800 x 1200px digital). White ground. Three horizontal bands corresponding to the three layers. Each layer occupies approximately 30% of the vertical space, with 5% transition gaps between layers. Reading direction: bottom to top (declared by a vertical arrow in the left margin: "Read: bottom-up — works generate clusters; clusters amend dimensions").

## Layer 1: The Six Dimensions (top band)

Six nodes arranged horizontally, evenly spaced. Each node is a rectangle (40 x 20mm) with rounded corners. Node labels: the dimension name and its maximum point value. Color: dimension-specific (see palette below).

Connecting lines between nodes show documented correlations. Thickness of line encodes strength of correlation (observed cross-dimension interactions from the panel data):

- School Fidelity — Data Integrity: thick solid line (strongest correlation; these dimensions are scored jointly in complex works)
- Visual Economy — Legibility: thick solid line (economy failures almost always co-produce legibility problems)
- Resonance — Craft: medium dashed line (craft quality enables resonance but does not determine it)
- Resonance — School Fidelity: thin dotted line (school grammar shapes resonance type)

Lines run along the top of Layer 1 (above the dimension nodes), curving to avoid crossing. The connections are drawn as smooth bezier arcs, not angular lines — this distinguishes correlation links from causal arrows.

## Layer 2: The Sixteen Clusters (middle band)

16 cluster nodes, arranged in chronological order (left-to-right: Cluster A, B, C... P) within the layer. Each node is a circle (15mm diameter). Color: matches the dimension the cluster primarily amended (same palette as Layer 1 nodes).

Two types of arrows connect Layer 2 to Layer 1 and Layer 1 to Layer 2:
- **Upward arrows (cluster to dimension)**: solid black, arrowhead at top. Each cluster node sends one or more upward arrows to the dimension node(s) it amended. Where a cluster amended two dimensions, two arrows diverge from the cluster node.
- **Downward arrows (dimension to cluster)**: not drawn. The feedback from amended dimensions to future cluster formation is represented by the overall bottom-up reading direction, not by individual arrows.

Cluster node labels: cluster letter (A-P) and a 3-5 word name ("Resonance sub-types", "School Fidelity synthesis", etc.). At the node's scale, only the letter fits inside; the name appears as a small label below the node.

## Layer 3: The Twenty-Five Works (bottom band)

25 work nodes arranged chronologically (left-to-right: 0001 through 0025). Each node is a small circle (8mm diameter). Color: work type (canonical import = light gray; original design = warm ochre). Labels: work number (below node) and a 1-2 word title (above node, very small, 6pt).

From each work node, upward lines connect to the cluster(s) that work triggered. Line color: matches the cluster's dimension color. Where one work triggered multiple clusters (e.g., work 0001 helped trigger Clusters A, B, C), multiple colored lines rise from that work node into the cluster layer.

The density of upward lines from each work node visually encodes innovation productivity: works 0001 and 0006-0010 have many lines; later works have fewer. The line density IS the data — it encodes which works were most generative without requiring numerical labels.

## Visual Variables Used

| Variable | What it encodes | Data type |
|----------|----------------|-----------|
| Layer position (top/middle/bottom) | System level (dimension / cluster / work) | Nominal (ordered) |
| Horizontal position | Chronological sequence within layer | Ordered |
| Node shape (rectangle / large circle / small circle) | Node type (dimension / cluster / work) | Nominal |
| Color (hue) | Rubric dimension | Nominal |
| Line thickness (Layer 1 connections) | Strength of dimension correlation | Ordered |
| Line type (solid / dashed / dotted) | Type of relationship (strong / moderate / weak) | Ordered |
| Upward line density from work nodes | Innovation productivity per work | Quantitative (approximate) |
| Node size | Node type (larger = higher system level) | Ordered |

All visual variables are correctly matched to their data types. No ordered variable used for nominal data; no nominal variable used for ordered data.

## Feedback Loop Annotation

At the far right of the diagram, a separate annotation shows the closed feedback loop:

WORKS → [generates] → INNOVATIONS → [cluster into] → CLUSTERS → [amend] → DIMENSIONS → [shape scoring of] → WORKS

This is rendered as a vertical text stack with right-facing arrows between items. It is the diagram's key — it explains the bottom-up reading direction and the circular self-improvement logic. This annotation is enclosed in a thin-border box, visually separated from the main diagram but adjacent to it.

## Palette

- School Fidelity: deep blue (#1A4E82)
- Data/Story Integrity: forest green (#2A6B3C)
- Legibility: amber (#C9952A)
- Visual Economy: terracotta (#B54A2A)
- Resonance: purple (#6B3A8C)
- Craft: slate gray (#4A5A6B)

These are muted, professional colors — high-contrast against white, distinguishable by hue and value, accessible to common forms of color vision deficiency (checked against Coblis simulation).

## Typography

- Dimension names: 10pt, Futura Medium, all caps
- Cluster letters: 9pt, Futura Medium, centered in circle
- Cluster names (below node): 7pt, Futura Light
- Work numbers: 6pt, Futura Light, below node
- Work titles: 6pt, Futura Light, above node
- Feedback loop annotation: 9pt, Futura Light, italic
- Reading direction label: 8pt, Futura Light, with up-arrow glyph

## School Grammar Compliance

Information architecture constitutive principles:
- Nodes represent entities (dimensions, clusters, works); edges represent relationships (correlations, amendments, triggers)
- Reading direction declared (bottom-up arrow in left margin)
- Hierarchy encoded by layer position (top = higher system level)
- Consistent visual vocabulary: three node shapes for three node types; arrow direction consistent throughout
- Minimize edge crossings: cluster-to-dimension arrows are routed to minimize crossing; work-to-cluster lines are colored to allow visual tracking even when crossing

## What the Diagram Shows

The system map makes three claims visible:

1. **The six dimensions are not independent**: the correlation lines in Layer 1 show that dimension scores co-move. A work with School Fidelity problems tends to have Data Integrity problems; a work with Visual Economy problems tends to have Legibility problems. The rubric's six dimensions are six angles on a smaller number of underlying qualities.

2. **Innovation is concentrated in early works**: the density of upward lines from the left side of Layer 3 (works 0001-0010) vs. the right side (0011-0025) shows that the first canonical imports were the most generative rubric development period. This is expected: early works define the grammar; later works refine it.

3. **The feedback loop is real and visible**: the bottom-up reading direction, combined with the colors that link layers, allows the viewer to trace any dimension's history from the works that generated it, through the clusters that crystallized it, to the dimension node at the top. The rubric's self-improvement is not abstract — it is traceable.
