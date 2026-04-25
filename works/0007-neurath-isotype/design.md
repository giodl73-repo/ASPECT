---
work: 0007-neurath-isotype
stage: design
school: isotype
review_type: canonical-import
historical_author: Otto Neurath, Gerd Arntz
author: claude
rubric_version: v1.4
created: 2026-04-23
---

# Design Description: Neurath's ISOTYPE Charts

## Reviewing Three Representative Charts

**Chart A — "Workers in Manufacturing Industries" (comparative, Germany vs. USA, 1930)**  
Two rows of identical male-worker pictograms (Arntz design): 10 figures per row. Each figure = 1 million workers. Germany: 10 figures. USA: 34 figures (3 full rows + 4 extra). No numbers visible in the image. Unit declared in a small legend below: "Each figure = 1,000,000 workers." Reading the chart: Germany has 10 million manufacturing workers; the USA has 34 million.

**Chart B — "Housing Conditions in Vienna" (change over time, 1900–1927)**  
House pictograms in rows by year. Dark house = overcrowded. Light house = adequate. The proportion of dark to light changes across the years. No numbers. The trend is visible as the proportion of dark houses shrinks.

**Chart C — "Infant Mortality Rates" (comparative, 10 nations)**  
Baby-cradle pictograms in columns, one column per nation, sorted descending by count. Each cradle = 10 deaths per 1000 births. The tallest column is Romania; the shortest is the Netherlands.

## Encoding Decisions

| Data Variable | Visual Variable | ISOTYPE Rule |
|--------------|----------------|-------------|
| Quantity | Count of identical symbols | Repeat, never scale |
| Category | Symbol type (worker, house, baby) | Standardized library symbol per referent |
| Comparison | Array height/length | More symbols = more quantity; reader counts |
| Change over time | Row-by-row across years | Same symbol type, arranged chronologically |
| Subcategory | Symbol fill/color variant | Dark vs. light, colored vs. uncolored |

**The key grammar rule: repetition, not scaling.** A symbol twice as tall does not mean twice as much — it means a distorted symbol. Quantity is always and only shown by repeating the standard-size symbol. This makes quantities countable rather than estimable. The reader counts; they do not judge height or area.

## The ISOTYPE School Grammar

1. Repeat the unit symbol; never scale it. Quantity = count of instances.
2. Symbols from a standardized library; one symbol type per referent.
3. Flat color; no shading, no shadow, no gradient.
4. No numbers in the image; the picture replaces the number.
5. Unit declaration required: "1 symbol = X [referent]."
6. Comparison by array adjacency; the eye counts and compares without calculation.

## Color System

Flat color; typically 1–3 colors per chart. Arntz's symbols designed to read in silhouette — color is supplementary, not primary. The system works in black-and-white; color adds categorical distinction.

## Rendering Notes

- Large-format display charts for museum wall installation; approximately 80 × 60 cm
- Designed for visitors who will glance while walking; must be readable at 2–3 meters
- Lettering: bold, sans-serif, large; must be legible at display distance
- The public-display context is essential to understanding all design choices
