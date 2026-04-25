---
work: 0012-isotype-plastic-pollution
stage: design
school: isotype
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
sources:
  - "Jambeck et al. (2015)"
  - "OECD Global Plastics Outlook (2022)"
---

# Design — 0012 ISOTYPE Plastic Pollution

## Visual Structure

A comparative ISOTYPE array: eight horizontal rows, one per world region, sorted descending by symbol count (most plastic to ocean at top). Each row contains region label (left), array of ocean-plastic symbols (center), and rounded count label (right-margin, outside image proper). A unit declaration appears below the title. A separate annotation panel (physically adjacent but visually distinct) addresses per-capita context and waste export.

## Layout Specification

```
[TITLE ZONE]
PLASTIC TO THE OCEAN BY REGION  (2023 estimates)
Each symbol = 1 million tonnes per year

[ARRAY ZONE — 8 rows, left-to-right]
East Asia & Pacific       ████████  (8)
South Asia                ███  (3)
Sub-Saharan Africa        ██  (2)
Latin America & Caribbean  ██  (2)
Middle East & N. Africa   █  (1)
Europe                    ▪  (< 1)
North America             ▪  (< 1)
Central Asia              ·  (< 1)

[SOURCE ZONE]
Source: OECD Global Plastics Outlook 2022; Jambeck et al. 2015 (updated estimates)
Rounding: fractional values < 0.5 shown as partial symbol ▪; < 0.1 shown as trace ·

[ANNOTATION PANEL — physically adjacent, different background tint]
What these numbers do not show:
Europe and North America consume more plastic per person than any region above.
Much of their waste is exported to nations in Asia and Africa, where processing
infrastructure cannot handle the volume. The symbols above count where plastic
enters the ocean — not who produced the consumer goods that became that plastic.
```

## Encoding Decisions

| Visual Variable | What it encodes | Justification |
|----------------|-----------------|---------------|
| Symbol count (repetition) | Annual ocean plastic input (Mt/year) | Core ISOTYPE rule: quantity by repetition, never scaling |
| Symbol type | Referent: ocean-bound plastic (ocean-wave + bottle silhouette) | One symbol type; standardized library extension |
| Symbol color | Fixed: deep teal (#1a6b7a) | Single thematic color; not categorical (all rows same referent) |
| Row position | Region identity | Ordered top-to-bottom by quantity; highest at top |
| Row label (text) | Region name | Left-aligned; horizontal; no visual encoding |
| Partial symbol variants | Sub-unit fractions | ▪ = 0.1–0.5 Mt; · = trace (< 0.1 Mt); declared in source zone |
| Annotation panel background | "This is explanation, not data" | Separate visual zone; light warm gray vs. white image zone |

## Symbol Design

**Primary symbol**: Ocean plastic — a silhouette of a wave crest with a plastic bottle embedded in it. Flat color, no shading, no gradient. Legible as a 12mm square at arm's length. Designed as a single closed path, reproducible as a stamp or screen-printed form.

**Partial symbol ▪**: A filled square at 50% the primary symbol width — conveys "less than one full unit" without scaling the primary symbol. Not part of the original Arntz library but a consistent extension declared in source notes.

**Trace marker ·**: A filled circle at 25% primary symbol width — conveys "present but less than half a partial unit." Also declared.

**Rationale for partial symbol convention**: The original ISOTYPE system frequently used partial figures (a half-person, a partial ship) to represent sub-unit values. This extension follows that practice consistently across all three sub-unit values, rather than rounding to zero and losing the data.

## Color System

| Color | Hex | Role |
|-------|-----|------|
| Ocean teal | #1a6b7a | Primary symbol fill; all arrays |
| Near-black | #1c1c1c | Text; labels; title |
| White | #ffffff | Image background |
| Warm gray | #f0ece6 | Annotation panel background |
| Light gray | #d4d0ca | Source zone separator line |

Color is NOT used to distinguish regions (that would be a Bertin grammar error — using hue as a quantitative or comparative variable when position already does that work). All symbols are the same teal. Region distinction is by row label only.

## Typography

- **Title**: 18pt bold, near-black, sans-serif (Neurath's preferred sans-serif aesthetic)
- **Unit declaration**: 11pt regular, near-black; immediately below title; box-framed or line-separated
- **Row labels**: 11pt regular, near-black; left-aligned; right-margin of label zone
- **Source/rounding notes**: 9pt, gray (#6e6e6e)
- **Annotation panel**: 10pt italic, #3a3a3a; set in a narrower measure than image proper

## School Elements (ISOTYPE checklist)

| Rule | Satisfied? | Notes |
|------|-----------|-------|
| Repeat, never scale | Yes | All symbols same size; partial variants declared |
| Flat color, no decoration | Yes | No gradients, shadows, or textures |
| Standardized symbol library | Partial | Ocean-plastic symbol is bespoke extension; declared |
| Unit declaration required | Yes | "Each symbol = 1 million tonnes per year" |
| No numbers in the image | Yes | Counts appear in margin outside image proper |
| Array composition | Yes | Horizontal rows; eye counts naturally left-to-right |
| Normalization declaration | Yes | Absolute totals declared; per-capita context in annotation panel |

## Rendering Notes

- Format: portrait A2 (420×594mm) for museum-wall display; array zone upper three-quarters; annotation panel lower quarter with tinted background
- Minimum symbol size: 12mm × 12mm to maintain legibility at 2m viewing distance
- Symbol spacing: 3mm gap between symbols within a row; 8mm between rows
- Label zone width: 140mm; array zone width: 240mm; right-margin count zone: 20mm
- Annotation panel: 420mm wide × ~110mm tall; 16mm internal margin

## Deliberate Limitations

This design cannot encode the per-capita story or the waste-export story in ISOTYPE symbols without violating the school's grammar. The choice to use a separate annotation panel (rather than a second ISOTYPE chart showing per-capita figures) is a design decision that a reviewer might challenge. A second per-capita chart would be the more ISOTYPE-faithful solution: show two charts — one absolute, one per-capita — and let the comparison do the work. This design chooses text annotation instead, prioritizing production simplicity and brevity over school purity. The panel should evaluate this choice.
