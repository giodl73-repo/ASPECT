---
slug: statistical-graphics
name: Statistical Graphics
primary_personas: [playfair, tufte, nightingale, bertin]
adjacent_schools: [cartography, advocacy-visualization, isotype, epidemiological-mapping]
founded: 1786
founder: William Playfair
canonical_works: [0009-playfair-commercial-atlas, 0002-nightingale-coxcomb]
---

# Statistical Graphics

## Origin and Claim

Founded by William Playfair in 1786 (*The Commercial and Political Atlas*) with the invention of the bar chart and line graph; the pie chart followed in 1801. The school's founding claim: proportional visual encoding of quantitative data allows the eye to perceive comparison before the mind processes numbers. A chart makes proportion immediate; a table requires sequential reading and mental arithmetic.

The school was theorized by Bertin (*Sémiologie Graphique*, 1967) and refined by Tufte (*The Visual Display of Quantitative Information*, 1983). Nightingale extended it into advocacy (1858). Du Bois extended it into political testimony (1900).

## Visual Grammar

### Primitives
- **Bar** (rectangle): height or length encodes a quantitative value; width is categorical
- **Line** (connected series): connects values across a continuous axis, typically time; slope encodes rate of change
- **Point** (scatter): position in two-dimensional quantitative space
- **Area** (filled region): cumulative or proportional quantity
- **Sector** (polar area or pie): proportion of a whole at a single moment

### Compositional Rules
1. Every quantitative axis must start at zero unless explicitly justified and declared
2. Proportional encoding: visual magnitude must be proportional to numerical magnitude
3. Comparison is primary: charts are designed for comparison, not for precise reading of individual values
4. Direct labeling preferred over legends where space allows
5. Grid lines serve the data; remove them if the comparison is legible without them

### Encoding Conventions
- **Position** (Bertin's most powerful retinal variable): used for the primary quantitative axis
- **Length/Height**: bars; ordered, quantitative
- **Area**: use only when the data is proportional (pie) or when the subject demands it (polar area)
- **Color hue**: categorical only; not quantitative; maximum 6-7 distinguishable hues
- **Color value** (lightness): ordered sequence; appropriate for sequential data

### Forbidden Moves
- Non-zero baseline without declaration (implied false magnitude)
- 3D effects on 2D data (distorts apparent proportion)
- Dual axes without clear declaration of the two scales (implies spurious correlation)
- Scaled symbols to represent quantity (use repetition or length instead)
- Decoration that competes with data marks

## Canonical Exemplars (DEGAS project)
- 0009 Playfair (89.4): the founding bar chart; simplest possible grammar, explicitly declared
- 0002 Nightingale (81.8): polar area form extending the grammar for advocacy impact

## Adjacent Schools
- **Advocacy-visualization**: same data, argument-first design logic; audience is power-holders
- **Isotype**: replaces abstract bar with pictographic repetition; trades precision for accessibility
- **Epidemiological-mapping**: applies statistical point-encoding to geographic space
- **Cartography**: adds geographic position as a primary variable
