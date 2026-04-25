---
work: 0031-soil-health-degradation
title: Soil Health Degradation (8 Agricultural Regions)
school: ecological-visualization
type: A (School Member)
rubric_version: v1.11
created: 2026-04-23
---

# Design Specification — 0031 Soil Health Degradation

## Canvas

Landscape orientation, 90 x 55cm. Eight profile columns side by side, each 10cm wide, separated by 1cm gaps. Each column is 45cm tall (representing 100cm+ depth). A separate right-margin panel (8cm wide) shows the environmental gradient legends.

## Depth Axis (Grammar Innovation)

The primary vertical axis runs downward: surface (0cm) at top, depth (100cm+) at bottom. This inverts the Humboldt ecological visualization convention (which uses altitude running upward). The inversion is declared by a vertical axis label reading "Depth (cm)" with a downward arrow. The axis marks appear on the left side of column 1: 0, 10, 30, 60, 100, 100+ cm.

This inversion is not decorative — it is a grammar requirement of the subject matter. Soil profiles are always drawn with surface at top in pedology. The viewer who knows soil science will recognize the convention; the viewer who does not will read the axis label and follow the downward reading direction.

## Profile Structure (per column)

Each of the 8 columns represents one agricultural region:
1. US Midwest (Corn Belt)
2. Brazilian Cerrado
3. European Wheat Belt (NW France/Germany)
4. North China Plain
5. Sub-Saharan Africa (West Africa savanna)
6. South Asian Indo-Gangetic Plain
7. Australian Wheatbelt
8. Argentine Pampas

Each column is divided into 5 depth zones: 0-10cm (A horizon, topsoil), 10-30cm (B horizon upper), 30-60cm (B horizon lower), 60-100cm (C horizon), 100cm+ (bedrock/parent material). Each depth zone is a horizontal band within the column. The band width (vertical extent) is proportional to the zone depth (10cm zone is narrower than 30cm zone).

## Variable Encoding (4 variables per zone per region)

Each depth zone band is split into 4 sub-columns, each encoding one soil health variable as a color intensity:

| Variable | Color | Direction |
|----------|-------|-----------|
| pH (0-14 scale, neutral=7 optimal) | Acid-alkali gradient: orange (acid) to teal (alkaline), white (neutral/optimal) | Diverging |
| Organic matter % | Green sequential: pale to dark green | Sequential |
| Compaction (kPa, lower=less) | Red sequential: pale to dark red | Sequential |
| Microbial diversity index | Blue sequential: pale to dark blue | Sequential |

Each variable's color intensity within a band represents the measured value for that region at that depth. The deepest zones are lighter for organic matter and microbial diversity (naturally low at depth) and paler for compaction (soil becomes looser at depth in most profiles). Degraded regions show more dark red (high compaction) and pale green (low organic matter) in the topsoil zones compared to healthy regions.

## Regional Comparison Logic

Reading horizontally across all 8 columns at the same depth level reveals inter-region comparison at that depth. Reading vertically within one column reveals the depth profile for that region. Both reading directions are simultaneously available — horizontal comparison and vertical profile.

## Key Finding Made Visible

The A horizon (0-10cm band) across all 8 profiles encodes the primary argument: the topsoil crisis. In degraded regions (North China Plain, Indo-Gangetic Plain, West Africa), the 0-10cm band shows: low organic matter (pale green), high compaction (dark red), low microbial diversity (pale blue). In healthier regions (US Midwest, Pampas), the 0-10cm band shows higher green, lighter red, deeper blue.

The comparison of A horizon quality across all 8 columns — visible in a single horizontal scan — is the chart's gestalt argument.

## Environmental Gradient Panel (right margin)

A separate 8cm panel at the right shows three reference gradients running from surface (top) to depth (bottom): light intensity (bright to dark), temperature (warm to cool), moisture (variable). These are not data — they are ecological context that explains why soil profiles naturally vary with depth. This panel uses the same downward depth axis as the main profiles. Small text labels explain each gradient.

## Typography

- Region names: 9pt, Futura Medium, above each column
- Depth axis labels: 8pt, Futura Light, left of column 1
- Variable sub-column labels: 6pt, at top of each column, above the 4 sub-columns: pH / OM% / Kpa / MDI
- Variable legend: 8pt with color swatches, at bottom of main composition
- Title: "Soil Under Pressure" — 16pt
- Subtitle: "Four measures of soil health at five depths across eight agricultural regions. Surface (0cm) is at top; depth increases downward." — 10pt

## School Grammar Compliance

Ecological visualization (Humboldt grammar adapted for depth):
- Primary axis: ecological gradient axis (depth instead of altitude; downward instead of upward)
- Multiple variables: 4 simultaneously per zone
- Regional comparison: 8 profiles side by side
- Environmental context: the right-margin gradient panel contextualizes the biological pattern against physical gradients
- The visual density is the data: high mark density (4 variables × 5 depths × 8 regions = 160 data cells) is intrinsic complexity, not additive complexity

The axis inversion is the grammar innovation: Humboldt's altitude axis assumes the viewer stands at ground level and looks up at the mountain. Soil visualization assumes the viewer stands at ground level and looks down into the earth. The subject determines the axis direction; the grammar adapts.
