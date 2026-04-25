---
work: 0031-soil-health-degradation
reviewer: tufte
weight: 0.20
rubric_version: v1.11
---

# Tufte — 0031 Soil Health Degradation

## School Fidelity /20 → 17

The ecological visualization school is correctly applied. 8 small multiples (profiles) sharing the same depth axis is the right structure for cross-regional comparison. The downward depth axis is a legitimate grammar extension of the Humboldt convention.

The four sub-columns per zone is the design choice I want to examine. An alternative would be four separate profile sets (one per variable), each showing all 8 regions — small multiples of small multiples. This would be more data-ink efficient for each individual variable comparison. But the design's choice (all four variables per zone in one profile) preserves the zone-as-unit reading — the viewer sees the full health profile of one depth zone at once, which is more ecologically meaningful than seeing one variable across all depths. The school-story match here favors the current choice: soil health is a holistic measure; zone-as-unit is the correct reading unit.

## Data/Story Integrity /20 → 15

The 4-variable selection is standard soil science. The depth zone boundaries are standard pedological classifications. Good source choices.

The data quality concern (sparse West Africa data vs. dense US Midwest data) is the main integrity gap. Presenting both with the same visual precision implies equivalent data quality, which is false. A data quality indicator is needed.

The pH diverging palette interpretation (both acid and alkaline are bad; neutral is optimal) requires a legend note that most viewers will not supply independently. Without this note, a viewer may read the acid-orange and alkaline-teal as categorical differences rather than as divergences from an optimal midpoint. Step D: undeclared analytical framework. Dock -1.

## Legibility /15 → 13

For an agricultural science audience in contemplative study: legible with effort. The two reading directions (horizontal comparison, vertical profile) are available. The sub-column labels (pH / OM% / kPa / MDI) at 6pt are the minimum legible size. The depth zone boundaries are clearly drawn.

## Visual Economy /15 → 13

160 data cells is intrinsic complexity (Cluster H). No additive decoration visible. The right-margin gradient panel is functional (contextual) rather than decorative. The economy is correct for the subject matter and audience.

The 6pt labels are an economy trade-off: larger labels would be more legible but would dominate the composition. The choice correctly prioritizes the data over the labeling. For a printed scientific visualization, this is standard practice.

## Resonance /15 → 13

The horizontal gestalt scan of the topsoil layer is the work's Type IV moment. The degradation pattern is visible as pattern before it is readable as numbers. For a soil scientist or agricultural policymaker, the Type V (domain-gated) resonance is also strong — they will recognize the borehole log format immediately.

## Craft /15 → 13

Color calibration across four palettes in 160 cells is high-stakes craft. Digital output is preferable to print for color precision. The four palette colors (green, red, blue, orange/teal) must be perceptually distinguishable at light intensities — the light-intensity cells (low data values) risk becoming visually indistinguishable. Test the rendering at minimum data values.

## My Total: 84/100

A well-conceived ecological visualization with good dimensional layering and correct intrinsic complexity. The data quality indicator and pH legend note are the primary additions needed.

## Innovation Flagged

**#222 — Zone-as-unit vs. variable-as-unit in multi-variable ecological profiles**: the choice between organizing a multi-variable ecological profile by zone (showing all variables per zone together) vs. by variable (showing one variable across all zones in small multiples) reflects a fundamental question about what the reading unit should be. Zone-as-unit reads holistically; variable-as-unit reads analytically. The rubric does not currently assess this organization choice as a School Fidelity or Data Integrity consideration. The ecological visualization school should name these two organizational modes and specify which subject-matter conditions favor which choice.
