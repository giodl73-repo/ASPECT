---
work: 0038-ocean-depth-zones
stage: design
rubric_version: v2.0
created: 2026-04-23
---

# Design Notes — 0038 Ocean Depth Zones

## Axis Grammar

**Primary axis (depth)**: vertical, running from 0m (top) to 11,000m (bottom). The gravitational hierarchy governs this choice: surface is different from depth in the same way that mountain peak is different from valley — gravity creates the ecological gradient, and the visualization should follow that gradient. The Humboldt grammar (altitude as primary axis, running upward) inverts to become the ocean grammar (depth as primary axis, running downward). The inversion follows gravity in both cases: up = mountain peak; down = ocean trench.

**Zone boundaries**: horizontal bands mark the five zones. Zone names label the band (Photic, Mesopelagic, Bathypelagic, Abyssal, Hadal). Zone transitions are not crisp (they depend on local conditions) but are shown as fuzzy gradient transitions rather than hard lines — ecologically honest.

## Five-Variable Encoding

The five variables are arranged as a panel array flanking the central depth axis:

| Position | Variable | Encoding | Notes |
|----------|----------|----------|-------|
| Far left | Light intensity | Horizontal bar, log scale | Warm white to black gradient |
| Left | Temperature | Horizontal line graph | Red (30C) to blue (1C) |
| Center | Depth axis | Primary organizing axis | With zone bands |
| Right | Oxygen concentration | Horizontal bar graph | Shows OMZ dip |
| Far right | Species density | Illustrated silhouettes | Density = diversity |

Center column: depth axis with zone bands and selected species silhouettes. The center column integrates all five variables — it is the anchor point from which the flanking variable panels are read.

## The Oxygen Minimum Zone

The oxygen concentration variable (right side) produces the most counterintuitive ecological feature: the oxygen minimum zone (OMZ) at approximately 200-1000m depth, where oxygen levels dip below both surface values (high, due to photosynthesis and atmospheric exchange) and deep values (moderate, due to cold temperatures that hold dissolved oxygen better). The OMZ is a critical ecological boundary — it limits the depth range of many species — and its counterintuitive location (not deepest = least oxygen) is one of the diagram's key insights.

## Intrinsic Complexity

Five environmental variables plus species diversity across 11,000m of depth is intrinsic ecological complexity. The Cluster H amendment applies: score only excess above intrinsic necessity. The species silhouettes in the central column are intrinsically necessary (they encode species density and diversity across zones) and should not be penalized as decorative marks.

## Axis Inversion — Cluster U Test

Work 0031 (soil health degradation) used a downward axis (0cm at top, 150cm at bottom) encoding soil layer depth. Reviewers confirmed this as an ecological grammar requirement — the gravitational hierarchy makes the downward axis natural. The current design applies the same principle to ocean depth (0m at top, 11,000m at bottom).

The key question: does the ocean context feel equally natural, or does the greater depth range (11,000m vs. 150cm) or the different ecological structure (five named zones vs. continuous soil gradients) create a different reading experience?
