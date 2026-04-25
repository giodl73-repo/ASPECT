---
work: 0009-playfair-commercial-atlas
stage: design
school: statistical-graphics
review_type: canonical-import
historical_author: William Playfair
author: claude
rubric_version: v1.4
created: 2026-04-23
---

# Design Description: Playfair's Scottish Trade Bar Chart (1786/1801)

## Visual Structure

A single chart, approximately 25 × 20 cm on the page. Seventeen horizontal bars, one per trading partner of Scotland. Each bar divided into two segments: left segment = imports to Scotland, right segment = exports from Scotland. The bars are sorted approximately by trade volume (largest at top). The horizontal axis represents monetary value (in £1,000s). The vertical axis lists trading partner names.

The chart is hand-engraved, with bar fills using diagonal line hatching to distinguish imports from exports.

## Encoding Decisions

| Data Variable | Visual Variable | Playfair's explicit declaration |
|--------------|----------------|-------------------------------|
| Trade value (imports) | Bar length (left segment) | "the length of the bar shows the amount" |
| Trade value (exports) | Bar length (right segment) | Stated in accompanying explanation |
| Trade partner identity | Position (vertical axis, labeled) | Named directly |
| Import vs. Export | Fill pattern (hatching direction) | Key provided |
| Trade balance | Relative bar segment lengths | Readable as comparison |

**Playfair's explicit declaration (Step D):** Unlike every other founder in this project, Playfair explicitly explains his encoding in the preface. He writes: "The advantage proposed by this method is not that of giving a more accurate statement than by figures, but it is to give a more simple and permanent idea of the gradual progress and comparative amounts, at different periods, by presenting to the eye a figure, the proportions of which correspond with the amount of the sums intended to be expressed." He declares the data model, the encoding logic, and its limitations.

This makes Playfair unique in the project: Step D dock = 0.

## The Statistical-Graphics School: Founding Grammar

Playfair's founding principles, extractable from this chart and its explanation:
1. Proportional encoding: bar length is proportional to quantity
2. Axis as measurement scale: horizontal axis provides a reference for reading bar lengths
3. Categorical vertical axis: each category (trading partner) gets one bar
4. Visual comparison: the reader sees relative magnitudes before reading numbers
5. Multi-variable in one figure: two sub-series (imports/exports) share the same axis
6. Explicit legend: encoding rules are stated

This is the grammar every subsequent bar chart follows. It is the clearest, most complete founding grammar of any school in this project.

## Color / Fill System

Black ink on white paper; hatching distinguishes the two data series (imports vs. exports). No color available in the period. The hatching is functional, not decorative.

## Typography

Hand-lettered trading partner names on the vertical axis; monetary values on the horizontal axis; a title and a short key. Somewhat crowded at the names; Playfair was working at the limit of what hand-engraving could produce at this scale.

## Rendering Notes

- Hand-engraved copper plate; printed on book pages
- Designed for reading in a commercial/political context (the Atlas was addressed to politicians and merchants)
- The chart is approximately 240 years old; the form it invented is still the most used chart type in the world
