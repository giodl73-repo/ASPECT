---
work: 0041-beat-92-vaccines
stage: design
school: statistical-graphics
review_type: original
rubric_version: v2.2
created: 2026-04-23
---

# Design Description: Beat-92 — Vaccines and Child Mortality

## Visual Structure

**Layout:** Two-panel horizontal composition on a single page. Left panel (40% width): "Under-5 Mortality Rate, 2000." Right panel (40% width): "Under-5 Mortality Rate, 2023." Center spine (20% width): country name labels, aligned to both panels.

**Country list:** 30 countries with highest 2023 under-5 mortality rates, sorted descending (Nigeria at top, Morocco at bottom). Sort key is 2023 rate, which creates the primary visual argument: "look how much shorter the right bars are."

**Bar encoding:**
- Bar length: mortality rate (deaths per 1,000 live births), linear scale
- Bar fill: functional gradient encoding vaccination coverage
  - Left sub-bar: DTP3 coverage (%) — blue gradient, light = low coverage, saturated = 90%+
  - Right sub-bar: MCV2 coverage (%) — teal gradient, same saturation logic
  - The two sub-bars are stacked within each bar to show dual-indicator coverage
- 2000 bars: left panel, extending leftward from center spine
- 2023 bars: right panel, extending rightward from center spine

**Scale:** Linear, 0–200 per 1,000 (x-axis). Both panels share the same scale, making the reduction immediately comparable.

**Typography:**
- Title: large serif, centered above full composition
- Country labels: small, aligned center spine, right-aligned to left panel and left-aligned to right panel
- Axis labels: small sans-serif below each panel
- Data values labeled at bar endpoints for top 10 and bottom 5 countries
- Source note: small serif, bottom of page

## Encoding Decisions

| Data Variable | Visual Variable | Scale |
|--------------|----------------|-------|
| Under-5 mortality rate | Bar length | Linear, 0–200 |
| Country | Position (y-axis, sorted) | Ordinal by 2023 rate |
| Year (2000 vs 2023) | Panel position (left vs right) | Categorical |
| DTP3 coverage | Fill saturation, left sub-bar | Linear, 0–100% |
| MCV2 coverage | Fill saturation, right sub-bar | Linear, 0–100% |

## Color System

- **Blue gradient** (DTP3): light blue (#d4e8f5) at 0% coverage → saturated blue (#1565c0) at 90%+
- **Teal gradient** (MCV2): light teal (#d4f5ec) at 0% coverage → saturated teal (#00695c) at 90%+
- **Background:** white; no fill behind bars
- **Spine:** thin vertical rule in mid-gray (#888888)
- No color is decorative. Every color element encodes vaccination coverage data.

## Functional Justification of Gradient Fill

The gradient fill is not decoration. It encodes a third and fourth data variable (DTP3 and MCV2 coverage) within the same bar that encodes mortality. This is multi-variable encoding, not chartjunk. The functional case:
1. High-coverage countries (full saturation) show lower 2023 mortality — the correlation is visible in the bar itself
2. Low-coverage countries (pale fill) show higher 2023 mortality — the remaining gap is visible and explained
3. The gradient carries the mechanism argument: vaccines → survival

## Disclosure Panel

Positioned bottom-right, small serif:
- Source: WHO Global Health Observatory immunization coverage, 2024 release
- Source: UN Inter-agency Group for Child Mortality Estimation (UN IGME), 2024
- Coverage indicators: DTP3 (3rd dose diphtheria-tetanus-pertussis) and MCV2 (2nd dose measles-containing vaccine)
- Note: Coverage figures are government-reported to WHO; estimates carry ±3–8% uncertainty
- Note: Mortality estimates include 95% confidence intervals; point estimates used for display
- Methodology: countries ranked by 2023 under-5 mortality; top 30 shown

## School-Specific Elements

**Statistical-graphics:**
- Bar chart for comparison — exactly what bar charts do; school-story match is perfect
- Linear scale, zero-baseline
- Sorted by quantitative variable (2023 rate)
- Multi-variable encoding through gradient fill (functional, not decorative)
- Direct value annotation at endpoints
- Source and methodology declared

**No imports from other schools.** This is a pure statistical-graphics execution. The advocacy dimension is carried by the title and the visual argument (shorter bars = fewer deaths), not by any non-statistical graphic element.

## Intrinsic Complexity Assessment

This is a simple chart with a modest multi-variable encoding. The intrinsic complexity is low: two bar panels plus two sub-bar fill gradients. No decorative marks. Economy of means is high.

The gradient fill is the only element that could be questioned on economy grounds — it is justified as functional encoding of a third and fourth variable.
