---
work: 0011-urban-heat-island
stage: design-v2
school: statistical-graphics
review_type: original-revision
author: human
rubric_version: v1.9
created: 2026-04-23
panel_recommendations_implemented:
  - Remove region color (sort-color conflict fix)
  - Add trend indicator (UHI increase/decrease past decade)
  - Qualify the title (remove title-data gap)
  - Add methodological note (MODIS satellite methodology declaration)
---

# Design v2: Urban Heat Island Effect — 30 Global Megacities (Revised)

## Revision Summary

Four changes implement the v1 panel's top four recommendations. This document describes the revised design; the rescore panel (RESCORE-v2-v1.9.md) evaluates it against rubric v1.9.

---

## Change 1: Remove Region Color

**What changed:** The region fill color has been removed entirely. All bars are now a uniform dark blue (#2c5f8a). The region legend is removed.

**Why:** The v1 panel reached unanimous agreement that the region color created an organizational conflict with the sort order. The chart sorts cities by UHI differential (highest to lowest). The color fills group cities by region. These two organizational logics compete: the viewer's eye follows the color groups while the chart's structure is the quantitative ranking. As Playfair, Tufte, and Bertin all independently noted, choosing one logic forces the designer to commit to one story. This chart's story is the ranking; the ranking now owns the visual space.

**Design note:** If a designer wanted to preserve region information, the correct move (per Bertin) would be to sort by region and label each region group, abandoning the UHI-sorted ranking. That is a different chart telling a different story. This revision commits to the ranking story and removes the region encoding rather than resolving it incorrectly.

---

## Change 2: Add a Trend Indicator Column

**What changed:** A narrow column of trend indicators is added immediately to the right of each city name label, before the bar begins. Each indicator is one of:
- ↑ (black, upward triangle) — UHI differential has increased ≥ 0.1°C over the past decade (2012–2022 vs. 2018–2022)
- ↓ (gray, downward triangle) — UHI differential has decreased ≥ 0.1°C over the past decade
- = (medium gray, dash) — trend is stable (change < 0.1°C over the past decade)

The indicators are set at 8pt, right-aligned in the trend column. A small legend below the chart: "↑ increasing trend (past decade) ↓ decreasing trend (past decade) = stable."

**Why:** The v1 panel's third recommendation identified "trend suppression in point-in-time charts" (Statistician, Innovation #109) as a real data gap. The current chart shows the UHI differential for 2018–2022 only. A city currently at 3.2°C but declining rapidly tells a different story than a city at 3.2°C and increasing. The trend indicator adds critical longitudinal context with minimal visual cost: three symbols, one column, one small legend.

**Data note:** Trend data derived from MODIS Land Surface Temperature records for the same cities over the preceding ten years (2012–2022 vs. 2018–2022 comparison). Source: NASA MODIS MOD11A2 product, processed by the same methodology as the primary data.

---

## Change 3: Qualify the Title

**What changed:** Title revised from:

> "High-income temperate cities have the worst urban heat islands"

To:

> "High-income temperate cities tend to have the worst urban heat islands"

**Why:** The v1 panel flagged the title-data gap (Innovations #102, #105) as a real integrity problem under Amendment L: the original title asserts "high-income" as a fact the chart encodes, but income is not encoded in the chart. The revised title uses "tend to" — which (1) accurately describes the pattern (it is a tendency, not an absolute rule), and (2) reduces the implied claim to what the chart can actually demonstrate. The chart shows UHI ranking; it does not show income. The qualifying word acknowledges the gap while preserving the argument.

**Note:** This is the minimum fix. A stronger fix (adding income annotation per Recommendation 2 of the v1 panel) would require adding a second variable — a deeper design revision that changes the chart's school category toward relational analysis. This revision takes the minimal path: qualify the title rather than redesign the form.

---

## Change 4: Add a Methodological Note

**What changed:** A methodological note is added in the chart's footer, set at 7pt:

> "Measurements use consistent satellite thermal methodology (MODIS Land Surface Temperature, 2018–2022 mean; MOD11A2 product). All cities measured using identical processing pipeline. Note: inter-city comparability is generally high but subject to land cover classification differences at city boundary definitions. See data notes for full methodology."

**Why:** The v1 panel's Statistician (Innovation #108, "Methodological comparability as Step A") identified that UHI measurements across cities potentially use different methodologies, producing comparability concerns. The note declares: (1) the specific measurement technology (MODIS satellite thermal), (2) the time window (2018–2022), (3) a caveat on inter-city comparability (boundary definition differences), and (4) a pointer to fuller documentation. This satisfies Step A's source quality declaration requirement without requiring a different chart.

---

## Full Revised Encoding Specification

| Data Variable | Visual Variable | Status |
|--------------|----------------|--------|
| UHI differential (°C) | Bar length (horizontal) | Unchanged |
| City identity | Position (y-axis, labeled) | Unchanged |
| Sort order | y-axis position (descending by UHI) | Unchanged |
| World region | ~~Bar fill color~~ | **Removed** |
| Uncertainty (±0.3°C) | Error bar | Unchanged |
| Decade trend (↑/↓/=) | Symbol column (trend indicator) | **Added** |

---

## Title and Labeling

- **Title:** "High-income temperate cities tend to have the worst urban heat islands"
- **Subtitle:** "Mean urban heat island differential, °C (2018–2022), 30 selected megacities"
- **Trend legend:** Small, below chart: "↑ increasing  ↓ decreasing  = stable (past decade)"
- **Methodological note:** Footer, 7pt (full text above)
- **Error bar note:** Retained in subtitle or legend: "Error bars = ±0.3°C measurement uncertainty"

---

## Color System (Revised)

Single color: all bars uniform dark blue (#2c5f8a). Error bars in a darker variant of the same hue or black. Trend symbols: ↑ in black, ↓ in medium gray, = in light gray. Background: white. Gridlines: light gray at 1°C intervals.

This is a simpler, more economical palette. The chart no longer requires a region legend; the trend column has its own three-symbol legend.

---

## Comparison to v1

| Aspect | v1 Design | v2 Design |
|--------|-----------|-----------|
| Region encoding | Present (fill color, 5 hues) | Removed |
| Trend data | Absent | Present (↑/↓/= per city) |
| Title | "High-income temperate cities have the worst urban heat islands" | "High-income temperate cities tend to have the worst urban heat islands" |
| Methodological note | Absent | Present (MODIS satellite, comparability caveat) |
| Color complexity | 5 region hues + error bars | 1 hue (+ trend symbols) + error bars |
| Visual variables active | 4 (length, position, color, error) | 4 (length, position, symbol, error) |

The revision does not change the chart's school (statistical-graphics / ranked bar chart). It removes the school-story mismatch in color (the sort-color conflict), adds a new time-dimension variable (trend), repairs the Amendment L gap (title-data gap), and declares the methodology.
