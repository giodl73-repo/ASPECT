---
work: 0014-maternal-mortality-race
stage: design
school: advocacy-visualization
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
sources:
  - "CDC WONDER 2016-2022"
  - "OECD Health Statistics 2022"
---

# Design — 0014 Maternal Mortality Race

## Design Approach: Du Bois's Precision-as-Defiance

The design chooses Du Bois's position: show the full honest context, including the OECD comparison that is unflattering to the US system at every level. The argument: precision-as-defiance here means refusing to let any part of the US healthcare system off the hook. White American women die at rates that exceed the UK. The racial gap runs above that already-elevated baseline. Showing only the racial gap without the international context would allow a policy audience to conclude that the problem is race alone — missing that the US healthcare system's structural failures create elevated risk for all women, with racial inequities on top.

**This is a declared design choice, surfaced in the panel review.**

## Visual Structure

A diptych: two linked panels sharing the same y-axis scale (maternal mortality per 100,000 live births) and the same x-dimension.

**Panel 1 — The Racial Gap Over Time (primary)**: A time-series line chart. Three lines: Black American women (bold red, Du Bois red — #c0392b), White American women (blue-gray — #5b7fa6), Hispanic American women (green-gray — #6d9b6e). Years 2016–2022 on x-axis. Rates on y-axis, 0–80. COVID years (2020–2021) shaded with a very light yellow band, labeled "COVID-19 period."

**Panel 2 — International Context (secondary, same scale)**: A horizontal bar chart on the same y-axis. Countries ranked by 2020 maternal mortality rate. Bars: Norway, Netherlands, Germany, Canada, UK, US overall, US (Black), US (White). US (Black) and US (White) use the same colors as Panel 1. The "US overall" bar is a mid-gray; European countries are light gray. A bold horizontal line connects the y-axis at the US (White) value — showing that even the lower-mortality US racial group exceeds the UK.

The two panels are placed side by side with a shared y-axis title ("Maternal mortality per 100,000 live births") bridging them. The diptych format is the Du Bois advocacy device: the comparison lives in the relationship between panels.

## Encoding Decisions

| Visual Variable | What it encodes | Justification |
|----------------|-----------------|---------------|
| Line color (red) | Black American women | Du Bois convention: persistent color marks the subject of the series |
| Line color (blue-gray) | White American women | Lower-urgency color; the comparison baseline |
| Line color (green-gray) | Hispanic American women | Third group; visible but not primary |
| Line weight | Bold (Black), regular (White, Hispanic) | Emphasis on the primary finding; declared |
| Yellow band | COVID-19 period | Structural-attentional; explains rate spike |
| Bar color (red/blue-gray) | US racial groups in Panel 2 | Consistent with Panel 1 colors |
| Bar color (light gray) | Other countries | Not the primary subject; de-emphasized |
| Horizontal reference line | US White rate in international context | Draws the eye to the key comparison: white US > UK |
| Diptych structure | Temporal change + international context | Advocacy argument lives in the relationship between panels |

## Color System

| Color | Hex | Role |
|-------|-----|------|
| Du Bois red | #c0392b | Black American women (subject line) |
| Blue-gray | #5b7fa6 | White American women |
| Green-gray | #6d9b6e | Hispanic American women |
| Mid-gray | #8c8c8c | US overall (Panel 2 bar) |
| Light gray | #c8c8c8 | European country bars |
| COVID yellow-band | #fff9c4 | Structural-attentional; COVID period |
| Near-black | #1c1c1c | Text, labels |
| White | #ffffff | Background |

## Title as Argument (Advocacy School Convention)

**Primary title**: "Black American Women Die in Childbirth at Three Times the Rate of White Women"

**Subtitle**: "And both rates exceed most wealthy nations — United States maternal mortality, 2016–2022"

The subtitle carries the Du Bois position: the international comparison is not a distraction but a second layer of the argument.

## School Elements (Advocacy Visualization Checklist)

| Rule | Satisfied? | Notes |
|------|-----------|-------|
| Audience identification before form selection | Yes | US policy researchers; line+bar diptych is standard in policy reports |
| Form chosen for audience impact | Yes | Time-series (trend) + international bars (context): standard policy form, not experimental |
| Argument embedded in structure | Yes | The racial gap is visible before reading labels; the diptych embeds the OECD comparison |
| Deliberate accuracy tradeoff | Declared | No tradeoff: Du Bois position explicitly chooses full context |
| Comparison selection is the argument | Yes | Eight countries + three US racial groups = declared comparison selection |
| Evidence must be honest | Yes | CDC data sourced; ICD coding change declared in notes |

## Typography

- **Primary title**: 16pt bold, near-black
- **Subtitle**: 12pt regular, near-black
- **Axis labels**: 10pt; y-axis shared between panels
- **Data labels**: selective; Black line labeled at 2022 endpoint; White line labeled at 2022 endpoint
- **COVID band label**: 9pt, #6e6e6e
- **ICD note**: 9pt footnote; "Note: CDC revised ICD-10 coding for maternal mortality in 2018; rates pre- and post-2018 may not be fully comparable. Data shown as published."

## Rendering Notes

- Format: landscape A3 (420×297mm), suitable for policy report and conference projection
- Panel 1 width: 55% of total; Panel 2 width: 40%; 5% shared axis
- Line chart: y-axis 0–80; x-axis 2016–2022; year labels at every year
- Bar chart: same y-axis scale 0–80; horizontal bars; country labels left of bars
- The shared y-axis scale is the critical connection; both panels must use exactly the same scale
