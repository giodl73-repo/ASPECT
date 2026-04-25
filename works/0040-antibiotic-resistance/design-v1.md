---
work: 0040-antibiotic-resistance
title: Global Antibiotic Resistance Rates — Cycle 1
school: statistical-graphics
type: A (School Member)
version: v1
rubric_version: v2.1
created: 2026-04-23
---

# Design Specification — 0040 Antibiotic Resistance (Cycle 1)

## Core Form: Heat Matrix

A 30 × 5 heat matrix. Rows: 30 countries. Columns: 5 bacterial species. Each cell: resistance rate encoded in color intensity (light = low resistance; dark = high resistance).

## Canvas

Landscape orientation, 60cm × 45cm. Matrix occupies the central 40cm × 35cm. Left margin (10cm): country names with income tier indicators. Top margin: bacteria column headers with brief clinical note. Color scale bar at bottom right.

## Country Order (Cycle 1)

Countries listed in alphabetical order within no explicit grouping. 30 countries:

Norway, Sweden, Denmark, Netherlands, Germany, Canada, Japan, Australia, New Zealand, South Korea, USA, France, Italy, Spain, Greece, Brazil, China, Turkey, South Africa, Mexico, Thailand, India, Pakistan, Vietnam, Nigeria, Kenya, Bangladesh, Ethiopia, DR Congo, (South Korea listed once).

## Bacteria Columns (left to right)

1. *E. coli* — fluoroquinolone resistance (%)
2. *K. pneumoniae* — carbapenem resistance (%)
3. *S. aureus* — methicillin resistance / MRSA (%)
4. *S. pneumoniae* — penicillin resistance (%)
5. *N. gonorrhoeae* — ceftriaxone resistance (%)

## Color Encoding

Sequential single-hue palette: white (0% resistance) to dark red (100% resistance). Color value (lightness) is the primary encoding variable — Bertin's ordered retinal variable, appropriate for ordered quantitative data.

Cells with missing data (primarily sub-Saharan Africa, some low-income countries where WHO GLASS surveillance is incomplete): cross-hatched pattern, labeled "Data insufficient."

## Numeric Labels

Resistance percentage printed inside each cell (2 decimal places rounded to integer: "73%"). Cell size large enough to hold 3-character label at 9pt.

## Color Scale

Bottom right: continuous scale bar, 0% to 100%, labeled at 0, 25, 50, 75, 100. Title: "Resistance rate (% of isolates)."

## Legend / Income Tier Notation

Left margin country labels include a small dot: filled black = high income; grey = upper-middle income; outline = lower-middle income; x = low income. Brief legend at bottom left.

## Title and Subtitle

- **Title**: "Antibiotic Resistance Rates, 30 Countries (2023)"
- **Subtitle**: "Percentage of isolates resistant to first-line antibiotics. Source: WHO GLASS 2023 database; ECDC Surveillance Report 2023."

## Schema Declaration

Brief explanatory note at top right of matrix: "Darker cells indicate higher resistance. Countries in alphabetical order. Missing data cross-hatched."

## Known Cycle 1 Limitations

This is a base design — standard form, standard ordering. The panel will identify the primary structural improvements. Expected gaps:
- Alphabetical country order obscures the income-tier resistance pattern (Bertin's matrix reordering observation)
- Missing counterfactual reference (what rate is achievable with good stewardship?)
- Color palette may not adequately distinguish the low-resistance clustering in Nordic countries from moderate-resistance countries
- Bacteria columns not sorted by clinical priority or resistance severity
- No regional grouping visible despite large regional variation
