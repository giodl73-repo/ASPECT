---
slug: cartography
name: Cartography (Thematic / Statistical)
primary_personas: [minard, bertin]
adjacent_schools: [statistical-graphics, epidemiological-mapping, schematic-cartography, ecological-visualization]
founded: ~1600s (thematic); 1844 (Minard's figurative maps)
founder: Multiple; Minard for quantitative flow cartography
canonical_works: [0001-napoleon-march]
---

# Cartography (Thematic / Statistical)

## Origin and Claim

Geographic maps encode position faithfully; thematic maps add a data layer on top of the geographic base. Statistical cartography — specifically the encoding of quantitative variables in geographic space — reaches its apex with Minard's figurative maps (1844–1869). The school's claim: some data is inherently spatial, and geographic position is the most powerful retinal variable. Placing data where it occurred makes the spatial argument available before the viewer has read a label.

## Visual Grammar

### Primitives
- **Geographic base map**: rivers, coastlines, borders — the spatial scaffold; simplified to what the data layer needs
- **Point symbol**: event or quantity at a location (proportional circle, dot, symbol)
- **Line symbol**: route, connection, boundary, flow
- **Flow band**: Minard's innovation — width encodes quantity; path encodes route; color encodes category or direction
- **Choropleth**: geographic region filled with a value-encoded color
- **Isoline**: contour of equal value across continuous space

### Compositional Rules
1. Geographic position encodes real-world location; accuracy is the primary commitment
2. The data layer must not obscure the geographic information needed to read it
3. The base map carries only what the data layer needs — excess geography is noise
4. Where geographic accuracy must be sacrificed for legibility, declare the distortion
5. Color hue on choropleths: use for nominal categories only; use color value (lightness) for quantitative sequences

### Encoding Conventions
- **Position**: geographic coordinates (primary, non-negotiable)
- **Size**: proportional to quantity at that location (circles, band widths)
- **Color hue**: categorical — line identity, direction, event type
- **Color value**: ordered/quantitative — density, rate, temperature gradient
- **Orientation**: flow direction

### Forbidden Moves
- Geographic distortion without declaration
- Choropleth with non-normalized data (showing absolute counts in regions of unequal area)
- Proportional circles sized by radius rather than area (overestimates large values)
- Mixing categorical and quantitative color on the same map

## Canonical Exemplars (DEGAS project)
- 0001 Minard (83.5): the Napoleon march — six-variable flow map; multi-school synthesis

## Adjacent Schools
- **Statistical-graphics**: same data; removes geographic base; trades spatial argument for precision
- **Epidemiological-mapping**: specialized cartography where spatial clustering IS the causal argument
- **Schematic-cartography**: distorts geography to represent network topology
- **Ecological-visualization**: geographic cross-section with multiple scientific data layers
