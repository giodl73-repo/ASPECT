---
work: 0013-schematic-science-network
stage: design
school: schematic-cartography
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
sources:
  - "Web of Science co-authorship data 2022"
---

# Design — 0013 Schematic Science Network

## Visual Structure

A topological network diagram in Beck's schematic style: colored lines representing research domains connect "station" nodes representing cities. The composition is organized around a conceptual center-of-gravity anchor (see Geographic Anchor section). Lines run at 0°, 45°, and 90° only. Node size is uniform (Beck's model: stations are equivalent regardless of passenger volume). Line weight encodes co-authorship frequency (three classes). A legend panel identifies line colors and line-weight classes.

## Layout Specification

Orientation: landscape A1 (841×594mm). The composition places the London–Boston–New York corridor in the upper-center, with European cities radiating to the left, East Asian cities radiating to the right, and Oceania/Singapore below right. This disposition roughly matches intuitive geographic orientation (West left, East right, South below) without using actual geographic coordinates.

```
[UPPER LEFT]          [UPPER CENTER]         [UPPER RIGHT]
Paris                 Boston                  Beijing
Amsterdam             New York ===London===   Shanghai
Berlin                Cambridge(UK)           Seoul
Vienna

[LOWER LEFT]          [CENTER]               [LOWER RIGHT]
                      Chicago                Singapore
Toronto               Los Angeles            Tokyo
                                             Sydney
                      [LEGEND ZONE]
                      Bangalore
```

Actual composition is more complex — intersections managed with standard Beck interchange conventions. All lines enter/exit nodes at 0°, 45°, or 90°.

## Geographic Anchor Solution

**The Thames Problem.** Beck's grammar requires one retained geographic feature for orientation. In the London Underground map, the Thames serves this function: it is a feature every Londoner knows and can use to orient the schematic network to their mental map. In a global science network, there is no equivalent. Three candidate solutions were evaluated:

1. **Ghost continent silhouette** (very light gray, #e8e8e8, no fill): Draws continent outlines as non-data structure at near-invisible weight. Cities sit roughly where their countries are. Provides orientation without claiming to represent geographic position.

2. **Conceptual gravity center** (a single bold dot at the weighted centroid of co-authorship volume, labeled "Global centroid 2022"): an invented datum rather than a geographic feature.

3. **No anchor** (accept that the schematic collapses all geographic reference).

**Design decision**: Option 1 — ghost continent silhouettes. This is declared as structural-attentional marks (not data), colored at #e8e8e8 (near-invisible at standard viewing distance), and noted in the legend: "Faint outlines are orientation aids only — they encode no data." This preserves the Beck grammar's requirement for one geographic anchor while honestly declaring that the anchor is structural, not topological.

## Encoding Decisions

| Visual Variable | What it encodes | Beck grammar status |
|----------------|-----------------|---------------------|
| Line color (hue) | Research domain (5 categories) | Standard — Beck uses hue for line identity |
| Line weight (3 classes) | Co-authorship frequency | Extension — Beck does not use weight for frequency; declared |
| Node shape: tick | Non-interchange city (appears on 1 domain-line) | Standard Beck |
| Node shape: ring | Interchange city (appears on 2+ domain-lines) | Standard Beck |
| Node size | Uniform | Standard Beck (station equivalence) |
| Position | Topological — preserves connections, not distances | Core Beck rule |
| Ghost outline | Continental orientation aid | Structural-attentional; declared non-data |
| Label orientation | Horizontal where possible; 45° where space requires | Beck preference; declared exceptions |

## Line Weight Classes

| Class | Stroke weight | Co-authorship volume | Visual |
|-------|--------------|---------------------|--------|
| Heavy | 4pt | > 5,000 joint papers/year | Dominant corridors |
| Medium | 2pt | 1,000–5,000 joint papers/year | Secondary links |
| Light | 1pt | < 1,000 joint papers/year | Emerging or specialist links |

**Grammar declaration**: line weight as frequency encoding is not in Beck's original grammar — it is an extension. A legend note states: "Line weight = co-authorship volume (three classes). This is not a standard Beck convention — see note."

## Color System

| Domain | Color | Hex |
|--------|-------|-----|
| Life sciences/medicine | Red | #d62728 |
| Physical sciences/engineering | Blue | #1f77b4 |
| Social sciences | Green | #2ca02c |
| Mathematics/computer science | Orange | #ff7f0e |
| Earth/environmental | Teal | #17becf |
| Ghost continent outlines | Near-white gray | #e8e8e8 |
| Labels and text | Near-black | #1c1c1c |
| Background | White | #ffffff |

Colors selected for maximum colorblind-accessible discrimination (Okabe-Ito palette adapted). London node uses a ring marker in each of the domain colors it appears on — it is the highest-interchange node in the network.

## Typography

- **City labels**: 10pt, horizontal where possible; near-black
- **Legend**: 9pt regular
- **Title**: "Global Scientific Collaboration — 20 Leading Research Cities (2022)"
- **Subtitle**: "Co-authorship links from Web of Science. Lines = research domains. Weight = volume."
- **Grammar note**: footnote, 8pt, bottom margin

## School Elements (Beck checklist)

| Rule | Satisfied? | Notes |
|------|-----------|-------|
| Topology over geography | Yes | Connections preserved; distances distorted for legibility |
| Angular discipline | Yes | All lines at 0°, 45°, or 90° |
| Central expansion | Yes | London/Boston/NY corridor expanded; distant cities compressed |
| Color as line identity | Yes | 5 domain-colors; consistent throughout |
| Interchange priority | Yes | Multi-domain cities get ring markers |
| Horizontal labeling | Mostly | Exceptions at 45° declared |
| One geographic anchor | Partial | Ghost continent outlines declared as structural-attentional, not geographic |

## Rendering Notes

- Format: landscape A1 (841×594mm), suitable for conference-room display
- Node spacing: minimum 25mm between adjacent nodes at final scale
- Line crossings: managed with standard Beck convention (lines cross over/under, not merging)
- The London node should be visually dominant through its interchange complexity (multiple rings), not through larger node size — Beck's grammar disallows non-uniform node sizes
