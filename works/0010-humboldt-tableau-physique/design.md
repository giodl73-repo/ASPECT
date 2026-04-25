---
work: 0010-humboldt-tableau-physique
stage: design
school: ecological-visualization
review_type: canonical-import
historical_author: Alexander von Humboldt
author: claude
rubric_version: v1.4
created: 2026-04-23
---

# Design Description: Humboldt's Tableau Physique des Andes

## Visual Structure

A large plate (approximately 60 × 50 cm). The central image: a cross-section of Mount Chimborazo (6,268 m) and its neighboring mountains, rendered in profile from sea level to summit. The mountain profile is detailed but schematic — not a topographic survey but a naturalistic silhouette.

Flanking the central mountain profile: dense columns of text and data on both sides, organized by altitude bands. Left columns: plant geography, animal communities. Right columns: meteorological measurements (temperature, atmospheric pressure, humidity, cyanometry, gravity, oxygen content).

**The structure is a matrix with an irregular axis**: altitude is the primary axis (vertical), running from sea level to summit; the columns of data run parallel to the altitude axis, each column encoding a different variable measured or observed at each altitude zone.

## Encoding Decisions

| Variable | Encoding | Notes |
|----------|---------|-------|
| Altitude | Vertical position on mountain profile | Primary axis; geographic |
| Temperature | Column of numeric values by altitude | Adjacent to the profile |
| Atmospheric pressure | Column of numeric values | Barometric readings, altitude-matched |
| Humidity | Column of values | |
| Oxygen content | Column of values | Cyanometric index |
| Gravity | Column of values | Pendulum observations |
| Plant communities | Named bands on mountain profile + flanking text | Species names at altitude zones where Humboldt observed them |
| Animal communities | Named in text columns | |
| Geological features | Rendered on mountain profile | Rock type visible in cross-section |
| Human settlements | Named on profile | Villages, monasteries at altitude |

**The data model (Step D):** Humboldt's founding insight — that altitude organizes ecological communities in the same way latitude does; that the climb up Chimborazo replicates a journey from tropics to poles — is the analytical framework of the diagram. This framework is not declared explicitly on the plate; it is argued in the accompanying essay text. The plate presents the data; the essay makes the interpretive framework explicit.

This is a more complex Step D case than Beck or Snow: Humboldt's framework IS partially declared (in the adjacent essay, not the plate itself). Dock is smaller than Snow's.

## The Ecological-Visualization School Grammar

1. Primary ecological axis (altitude, latitude, temperature gradient) organizes the spatial structure
2. Multiple environmental variables measured against this axis simultaneously
3. Species distributions overlaid on the environmental matrix
4. The visualization argues for a system — the ecological zone concept — rather than reporting isolated measurements
5. Natural beauty of the central image (the mountain) is not decorative; it establishes the geographic reality that contextualizes the data columns

## Color / Rendering

The Tableau Physique was originally published in color: the mountain cross-section renders different geological strata and vegetation zones in naturalistic colors. The flanking data columns are in black text on pale background. The combination of naturalistic image + tabular data on the same plate is the visual innovation.

## Rendering Notes

- Large-format folded plate in the folio edition of the Essai
- Designed for extended study — this is not a glance-readable work
- Humboldt supervised the production closely; the plate is among the most ambitious scientific visualizations of the early 19th century
- Scale: the project spans Humboldt's Chimborazo ascent (1802) to the 1807 publication — 5 years of compilation
