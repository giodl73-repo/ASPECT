---
work: 0011-urban-heat-island
stage: design
school: statistical-graphics
review_type: original
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
sources:
  - UHI data per brief.md
---

# Design: Urban Heat Island Effect — 30 Global Megacities

## Visual Structure

A horizontal bar chart. 30 bars, one per city, sorted descending by UHI differential (Phoenix at top, Johannesburg at bottom). The bars extend left-to-right from a zero baseline at the left edge. City names are labeled on the left of the baseline (y-axis labels). The quantitative axis runs along the top and/or bottom, labeled in °C.

**The visual argument is immediate**: the bars at the top are much longer than those at the bottom. The eye can see, before reading any city name, that there is a wide range — a 10× spread from Phoenix (4.8°C) to Johannesburg (0.5°C). The sort order makes the gradient visible.

**Two-variable design**: each bar is filled with a region color, so the viewer can read both ranking and geography simultaneously.

---

## Encoding Decisions

| Data Variable | Visual Variable | Rationale |
|--------------|----------------|-----------|
| UHI differential (°C) | Bar length (horizontal) | Quantitative; position/length is Bertin's highest-fidelity quantitative variable; directly comparable across bars |
| City identity | Position (y-axis, labeled) | Nominal; labeled directly; no legend needed |
| Sort order | y-axis position | Encodes ranking; the argument is "who has the worst problem" — descending sort makes this immediate |
| World region | Bar fill color (hue) | Nominal categorical; 5 regions (N. America, Europe, Asia, Africa, L. America); maximum 5 hues; selective variable correctly assigned to nominal data |
| Uncertainty (±0.3°C) | Error bar | Quantitative range; should appear as thin horizontal lines at bar ends |

**Encoding rules stated (Step D Level 1 — in-work declaration):**
The chart title or subtitle will state: "Bar length = mean annual urban-rural temperature differential, °C, 2018–2022. Color = world region. Error bars = ±0.3°C measurement uncertainty. Cities sorted highest to lowest differential."

---

## School-Specific Elements (Statistical-Graphics, Playfair grammar)

1. **Zero baseline**: all bars start at zero. No truncation of the axis. The proportional comparison is honest.
2. **Single quantitative axis**: the horizontal axis is the measurement scale. Labeled at 0, 1, 2, 3, 4, 5°C. Light gridlines at each integer.
3. **Sorted for comparison**: descending sort is the strongest Playfair move — the viewer grasps the top-to-bottom gradient before reading names.
4. **Direct city labeling**: city names on the y-axis; no separate legend for city identity.
5. **Region legend**: one small color key for the five region categories; placed in the lower right or upper left white space.
6. **Rhetorical title**: "High-income temperate cities have the worst urban heat islands" — states the argument in the title, per Playfair's commercial-atlas convention.
7. **Explicit uncertainty**: error bars shown to declare data quality per rubric Step A.

---

## Typography and Labels

- Sans-serif typeface throughout (Helvetica Neue or equivalent)
- City names: 9pt, right-aligned against baseline
- Axis labels: 8pt, centered under tick marks
- Title: 14pt bold
- Subtitle/legend: 8pt
- Chart width: approximately 160mm; full height for 30 bars at approximately 6mm per bar = 180mm total

---

## Color System

Five region colors, chosen to be distinguishable under colorblindness:
- **N. America**: blue (#2166ac)
- **Europe**: purple (#762a83)  
- **E. & SE. Asia**: orange (#d94801)
- **S. Asia & Africa**: green (#1a7837)
- **L. America**: pink (#e08090)

These are categorical — no implied order among regions. Palette checked for deuteranopia (red-green colorblindness) compatibility.

---

## Rendering Notes

This design does not physically render — it specifies a rendering. A practitioner with Datawrapper, R/ggplot2, or D3.js could reproduce this from the specification. The description is complete enough for reconstruction.

**One open question from the brief**: should region color be used or is it chartjunk? The panel's answer to this will determine whether the second variable adds comprehension or merely adds visual complexity. The design deploys it; the panel judges it.

**A second open question**: is this the right form for this story? The Playfair grammar handles ranked comparison well. But the core message ("high-income temperate cities are worse") is really a two-variable story (UHI vs. income, or UHI vs. climate zone) that a scatter plot might communicate better. The panel should weigh in on whether school and story are well matched.
