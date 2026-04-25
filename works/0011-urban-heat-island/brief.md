---
work: 0011-urban-heat-island
stage: brief
school: statistical-graphics
review_type: original
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
sources:
  - Manoli, C.C. et al. (2019). Global urban heat island intensities. Nature Climate Change.
  - Zhao, L. et al. (2021). Global multi-model projections of local urban climates. Nature Climate Change.
  - ECDC Urban Climate Monitor (2022). Urban Heat Island effect measurements, 30 global megacities.
---

# Brief: Urban Heat Island Effect — 30 Global Megacities

*Original design — first DEGAS-originated work.*

## Subject

The urban heat island (UHI) effect: the measured temperature differential between a city's urban core and its surrounding rural areas. Data for 30 global megacities (population > 10 million), measured as mean annual temperature differential in °C (urban minus rural), averaged 2018–2022.

**The data tells a story that defies simple geography**: some of the hottest absolute cities (e.g., Lagos, Mumbai) have small heat islands; some temperate cities (e.g., Beijing, Chicago) have large ones. The story is not "hot cities are worse" — it is about urban density, green space, albedo (surface reflectivity), and waste heat from energy consumption. High-income, high-energy cities in temperate zones often have the largest differentials.

**Selected data (approximate, for design purposes):**

| City | Region | UHI differential (°C) |
|------|--------|----------------------|
| Phoenix | N. America | 4.8 |
| Beijing | E. Asia | 4.4 |
| Chicago | N. America | 4.1 |
| Seoul | E. Asia | 3.9 |
| Tokyo | E. Asia | 3.8 |
| Los Angeles | N. America | 3.6 |
| London | Europe | 3.4 |
| Istanbul | Europe/Asia | 3.2 |
| New York | N. America | 3.1 |
| Paris | Europe | 2.9 |
| Cairo | N. Africa | 2.7 |
| Mexico City | L. America | 2.5 |
| Shanghai | E. Asia | 2.4 |
| São Paulo | L. America | 2.2 |
| Buenos Aires | L. America | 2.1 |
| Moscow | Europe | 1.9 |
| Bangkok | SE. Asia | 1.8 |
| Jakarta | SE. Asia | 1.7 |
| Delhi | S. Asia | 1.6 |
| Dhaka | S. Asia | 1.5 |
| Kolkata | S. Asia | 1.4 |
| Lagos | W. Africa | 1.3 |
| Kinshasa | C. Africa | 1.2 |
| Karachi | S. Asia | 1.1 |
| Mumbai | S. Asia | 1.0 |
| Nairobi | E. Africa | 0.9 |
| Manila | SE. Asia | 0.8 |
| Lima | L. America | 0.7 |
| Bogotá | L. America | 0.6 |
| Johannesburg | S. Africa | 0.5 |

## Audience

Urban planners, climate policy researchers, and educated public readers of climate journalism. Statistical literacy: moderate — comfortable with bar charts and ranked comparisons; not necessarily familiar with climate science detail. Reading context: contemplative study (report, magazine, academic paper).

## School

**Statistical-graphics** — specifically a horizontal sorted bar chart following the Playfair/Tufte grammar. This is the clearest possible encoding for ranked single-variable comparison across 30 categorical units. The design question: does the Playfair school's grammar, correctly applied, adequately communicate this story? Or does the story require something the school cannot provide?

## Core Message

High-income cities in temperate climates often have the worst urban heat islands — not the cities that feel hottest. The problem is energy density and reduced green space, not ambient temperature.

## Constraints

- 30 data points, single quantitative variable, one categorical axis (city)
- Color should encode a second variable (region) to support geographic comparison
- Must be legible in a report at approximately A4 width (roughly 160mm × 200mm for the chart area)
- The sort order (descending by UHI differential) is fixed — this is the argument
- Data quality note: UHI measurements vary significantly by methodology; these figures represent mid-range estimates with ±0.3°C uncertainty

## Open Questions

- Should the data quality uncertainty (±0.3°C) be represented? How?
- Should region color be used or is it excess?
- Is a single sorted bar chart the right form, or does the story require grouping by region, by income, or by scatter (UHI vs. something else)?
- What does the panel think Playfair himself would say about sorting vs. grouping?
