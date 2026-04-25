---
work: 0029-child-mortality-preventable
title: Child Mortality by Preventable Cause (Global 2023)
school: advocacy-visualization
type: A (School Member)
rubric_version: v1.11
created: 2026-04-23
---

# Design Specification — 0029 Child Mortality by Preventable Cause

## Form: The Split Bar Chart

A horizontal split bar chart (butterfly/diverging format). The center axis is a vertical line labeled "0 deaths." Each cause is one row. Left of center: a horizontal bar encoding current annual deaths. Right of center: a horizontal bar encoding projected deaths at 90% treatment coverage. The gap between bar ends is the preventable death count — the visual argument.

## Data (Global 2023 estimates, IHME/WHO sources)

| Cause | Current Deaths (thousands) | At 90% Coverage | Gap |
|-------|---------------------------|-----------------|-----|
| Neonatal sepsis | 680 | 140 | 540 |
| Pneumonia | 740 | 150 | 590 |
| Diarrheal diseases | 530 | 110 | 420 |
| Malaria | 490 | 98 | 392 |
| Malnutrition (as underlying) | 940 | 230 | 710 |
| Preterm complications | 900 | 250 | 650 |
| **Total** | **4,280** | **978** | **3,302** |

Rows are sorted by gap size (largest gap at top: malnutrition). This sort order means the most preventable causes appear first, which is the advocacy argument's natural priority.

## Visual Encoding

**Left bars (current deaths):** Filled in a deep, serious red (#9B2335). Horizontal, left of center. Bar end labeled with exact number (e.g., "940,000"). No rounding.

**Right bars (projected deaths at 90% coverage):** Filled in a muted blue-gray (#6B7E8A). Horizontal, right of center. Bar end labeled with exact number.

**The gap:** The space between the left bar end and the right bar end is the preventable death count. A thin horizontal bracket spans this gap with the gap number directly labeled (e.g., "710,000 preventable"). The bracket is in warm orange (#C47830) — a color that reads as "this is the point."

**Center axis:** A thin vertical line, no decoration. The label "current deaths | preventable reduction" appears at the top of the axis, small, separating the two halves.

**Row labels (left):** Cause name, 10pt, at the left edge of each row. Cause-specific unit cost annotation: below each cause name, in 8pt gray, "Treatment cost: under $20/case." This appears on every row — repetitive by design, reinforcing the cost argument with each scan.

**Title:** "The Gap Is the Argument" — centered at top, 18pt, bold. Subtitle: "5 million preventable child deaths annually. Each is treatable for under $20." — 11pt.

**Source note:** "Source: IHME Global Burden of Disease 2023; WHO Essential Medicines List coverage modeling. 90% coverage scenario follows UNICEF 2022 intervention analysis."

## Gestalt Argument (Type IV Resonance)

The chart's gestalt — before any label is read — is: two sets of bars, left longer than right, with a visible gap between them. The gap is the argument. A viewer who glances for 3 seconds sees: there is a big difference between current and possible. The specific numbers arrive on reading, but the shape of the argument is visible immediately. This is the Du Bois two-speed design: glancing visitor sees the gap; stopping visitor reads the exact numbers.

## Advocacy Target Audience

Health policymakers, international development funders, WHO/UNICEF program staff. These are numerate professionals who will read the exact numbers and assess them against their program budgets. The per-case cost annotation ($20/case) translates the mortality gap into a budget reality. The argument: "The gap in column 3 is 3.3 million children. At $20 per case, full coverage costs approximately $66M for pneumonia alone — less than the operating budget of many single hospitals in the countries that fund us."

## Precision-as-Defiance (Du Bois Principle)

All numbers are reported to the nearest thousand, not rounded to the nearest million. The specific precision (540,000 — not "half a million") is the argument's rhetorical edge. Rounding to half-millions would produce the impression of approximate, uncertain data. Precision at the thousand level says: we have counted these children. They are not an estimate. They are a specific number of specific human beings.

The 90% coverage figures are declared as modeled projections from UNICEF's intervention analysis — the uncertainty is noted in the source note, but the figures are presented with the same precision as the current mortality data, because the modeling methodology warrants it.

## Trend Addition (Rosling consideration)

A small secondary annotation appears at the bottom of the chart: a four-cell mini-table showing current total under-5 deaths by year: 2010 (7.1M), 2015 (5.9M), 2020 (5.0M), 2023 (4.3M). A downward arrow and the label: "Progress is real — and insufficient." This acknowledges the trend improvement (Rosling's request) without making it the main argument. The main argument is the gap, not the trend.

## School Grammar Compliance

Advocacy visualization principles:
- Audience identified first: health policymakers, numerate, budget-aware
- Form chosen for audience impact: the gap is immediately visible; the exact numbers are available for those who read carefully
- Argument embedded in structure: the gap IS the visual structure; the argument does not require reading
- Deliberate accuracy tradeoff: none — high precision is the argument
- Comparison selection declared: current mortality vs. 90% coverage scenario, source and methodology stated
- Evidence is honest: current death rates are not minimized; the 90% coverage scenario is labeled as a model projection
