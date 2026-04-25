---
work: 0031-soil-health-degradation
reviewer: bertin
weight: 0.25
rubric_version: v1.11
---

# Bertin — 0031 Soil Health Degradation

## School Fidelity /20 → 17

Variable audit:
- Position (vertical): depth — ordered/quantitative. Downward direction declared. Correct.
- Position (horizontal): region (column identity) — nominal. Shape/position separation is correct.
- Position (within column, sub-column): variable identity (pH / OM / kPa / MDI) — nominal. Correct.
- Color intensity (sequential): variable values within each zone — ordered/quantitative. Sequential palettes (pale to dark) are correctly matched to ordered data.
- Color direction (diverging for pH): diverging palette (acid/alkaline from neutral) — ordered from a midpoint. Correctly matched to a diverging variable.
- Band height (vertical extent of each zone): depth range — quantitative. Proportional band heights correctly encode the depth range of each zone.

All variables correctly matched. The diverging pH palette is the most sophisticated choice and requires the most careful legend. The four sequential palettes must be perceptually distinguishable — if green, red, and blue happen to produce similar intensity gradients at the same data value, the viewer may confuse variables. Each palette must be independently calibrated.

The sub-column structure (4 sub-columns per zone per profile) is a grammar choice I find defensible: it allows four variables to coexist in a single zone band without requiring a small multiples expansion. The information cost is that the zone bands become narrow (approximately 2.5cm per sub-column at 10cm column width). At this narrow width, color intensity is readable but color detail is not.

## Data/Story Integrity /20 → 16

The 4-variable selection (pH, OM, compaction, microbial diversity) is the standard soil health assessment framework. No cherry-picking. The depth zone boundaries (0-10, 10-30, 30-60, 60-100, 100+) follow the standard pedological A/B/C horizon classification. Correct.

Data quality varies by region (noted in Minard's review). The West Africa data is sparse by comparison with US Midwest data. A data quality indicator by region (e.g., filled circle = dense data; half-filled = moderate; outline = sparse) would satisfy Step A without cluttering the main composition.

The right-margin environmental gradient panel is correctly treated as contextual reference rather than additional data encoding — it explains the pattern without claiming to measure it. Good integrity practice.

## Legibility /15 → 12

The two reading directions (horizontal comparison scan, vertical profile scan) are both supported by the layout. The horizontal scan is the more natural first reading; the vertical scan requires intentional attention to one column. This is appropriate for an expert scientific audience.

The 6pt variable labels (pH / OM% / kPa / MDI) at the top of each column are the minimum legible size for this subject matter. Larger labels would dominate the composition; smaller labels would be unreadable. The trade-off is correctly calibrated for the audience.

## Visual Economy /15 → 13

Intrinsic complexity (Cluster H): 160 data cells is intrinsic to the subject. The subject matter (soil health across multiple regions, depths, variables) genuinely requires this many data points to make the argument. The visual mark count is not additive complexity — it is the data itself.

The environmental gradient panel adds approximately 15% more visual area but provides the causal context that makes the data interpretable without prior ecological knowledge. Economy-positive: it reduces the cognitive load of interpreting the pattern by providing the explanatory framework.

## Resonance /15 → 13

The gestalt is correct. The A-horizon bands (topsoil) pattern is visible across all 8 columns as a horizontal strip of varying color intensity. The degradation pattern (more dark red, less dark green in the affected regions) is visible as a horizontal comparison before any label is read. This is Type IV gestalt resonance.

Type V (domain-gated) is also active: the pedologist will immediately recognize the profile structure and read it as a soil scientist reads a borehole log.

## Craft /15 → 13

High craft demands from color calibration across four palettes. Any inconsistency in palette rendering will undermine the comparison. High-resolution output required.

## My Total: 84/100

A rigorous ecological visualization with excellent variable matching and an important grammar innovation (depth-axis inversion). The data quality variation across regions is the primary integrity gap. The sub-column narrowness is the primary legibility risk.

## Innovation Flagged (confirms Minard #221)

The depth-axis inversion is a grammar requirement documented by Minard as #221. I confirm: the ecological visualization school's grammar should specify that the gradient axis direction is determined by the natural direction of the gradient — not by convention. Upward for altitude; downward for depth; inward for marine depth profiles. The confirmation of #221 makes this a two-reviewer cluster candidate.
