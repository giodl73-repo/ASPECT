---
work: 0050-degas-scoreboard
stage: design
school: statistical-graphics
review_type: original
rubric_version: v2.2
created: 2026-04-23
---

# Design Description: DEGAS Scoreboard

## Visual Structure

**Format:** Horizontal bar chart on a single tall page (recommended: A3 or full-browser display, portrait orientation).

**Bars:**
- 50 horizontal bars, one per DEGAS work
- Bar length: v2.2 final score (0-100 scale)
- Sorted descending by score (highest at top)
- Left-aligned bar labels: work slug (e.g., "0041-beat-92-vaccines")
- Right-aligned bar labels: score value (e.g., "92.7")

**Color encoding:**
- Bar fill color encodes school category
- Color legend: bottom of chart
- School color assignments (consistent palette, colorblind-safe):
  - statistical-graphics: #1565c0 (blue)
  - cartography/flow: #5d4037 (brown)
  - scientific-illustration: #2e7d32 (forest green)
  - advocacy-visualization: #c62828 (red)
  - data-art: #6a1b9a (purple)
  - information-architecture: #00695c (teal)
  - schematic-cartography: #e65100 (orange)
  - dynamic-statistical-graphics: #0277bd (light blue)
  - isotype: #f57f17 (amber)
  - mathematical-proof-visualization: #37474f (slate)
  - ecological-visualization: #558b2f (light green)
  - abstract-art: #880e4f (magenta)
  - narrative-visualization: #004d40 (dark teal)
  - epidemiological-mapping: #bf360c (deep orange)

**Scale:** x-axis 50-100 (not zero-baseline; the truncation is declared)
Note: the truncation at 50 is declared explicitly because the minimum project score (57.1, propaganda poster) is still above 50. Starting at 50 compresses the visual comparison, but the range is declared. Alternative: start at 0 for honest baseline. Design recommendation: use 0 baseline with annotation "all works exceed 55."

**Typography:**
- Work slugs: 8pt monospace font (Courier or equivalent)
- Score values: 8pt sans-serif
- Axis ticks at 60, 70, 80, 90, 100
- Title: "DEGAS Works 0001-0050: v2.2 Scores" (sans-serif, 18pt)
- Subtitle: "Sorted by score descending; color = school; all 50 works"

**Reference lines:**
- Vertical line at 60 (advisory threshold)
- Vertical line at 80 (above-average zone)
- Vertical line at 90 (project high range)

## Encoding Decisions

| Data Variable | Visual Variable | Notes |
|--------------|----------------|-------|
| Score | Bar length | Quantitative, linear |
| Work identity | Bar label (slug) | Direct annotation |
| School | Bar fill color | Categorical, colorblind-safe palette |
| Rank | Vertical position (sorted) | Ordinal by score |

## School-Story Match Assessment

Bar chart for ranked comparison: perfect match. The question "which works score highest, and which schools cluster at which performance levels?" is exactly the question a sorted bar chart answers. The school color allows the viewer to see whether particular schools cluster at the top or bottom of the distribution.

## Self-Referential Note

This chart is DEGAS reviewing itself. The data for work 0050 (this chart) is its own score — the score assigned by this panel, which appears in the chart alongside the other 49 works. This creates a mild logical recursion: the chart includes its own score, which was determined by reviewing the chart that includes its own score. The recursion is declared; it is not hidden.

Practical resolution: work 0050's bar reflects the panel score assigned in this review. The chart displays 0050 alongside the other 49 works in the sorted order. This is honest.

## Data Source

All 50 scores from the DEGAS TRACKER.md, as determined by panel review under v2.2 rubric. Complete data. No missing values. No uncertainty in the scores (they are precise to one decimal place).
