---
slug: schematic-cartography
name: Schematic Cartography (Topological Mapping)
primary_personas: [beck]
adjacent_schools: [cartography, information-architecture]
founded: 1933
founder: Harry Beck
canonical_works: [0003-beck-underground]
---

# Schematic Cartography

## Origin and Claim

Founded by Harry Beck's London Underground map (1933). The school's founding claim: when the data IS a network, topological representation (preserving connections, distorting distances) is the faithful encoding — not geographic representation. The traveler underground needs network adjacency, not geographic position. Schematic cartography answers the traveler's actual question.

The school derives from engineering drawing conventions (electrical circuit diagrams) applied to public navigation at city scale.

## Visual Grammar

### Primitives
- **Colored line**: represents a transit route or network path; continuous, no geographic curves
- **Tick mark**: station on a line; perpendicular to the line direction
- **Interchange ring/diamond**: transfer station — visually distinct from non-interchange stations; highest visual priority after the lines
- **Line terminus marker**: end of a route; arrow or terminal station label
- **Geographic anchor**: one retained geographic feature (river, coastline) for orientation

### Compositional Rules
1. **Topology over geography**: preserve connections exactly; distort distances as needed for legibility
2. **Angular discipline**: all lines run at 0°, 45°, or 90° only — no arbitrary angles
3. **Central expansion**: dense central area drawn at larger scale than periphery; station legibility maintained throughout
4. **Color as line identity**: each line has exactly one unique saturated color; color IS the line
5. **Interchange priority**: transfer stations receive the highest visual emphasis after line colors
6. **Horizontal labeling**: station names horizontal wherever possible
7. **One geographic anchor**: retain the single most orientation-useful geographic feature; distort everything else

### Encoding Conventions
- **Color hue**: nominal categorical (line identity) — primary navigation variable; viewer follows the color, not the position
- **Position**: topological (network adjacency), NOT geographic
- **Shape**: tick = non-interchange; ring/diamond = interchange — binary categorical
- **Orientation**: line direction — constrained to 0°/45°/90°

### Forbidden Moves
- Geographic curves in line paths (introduces arbitrary angles)
- Color used for anything other than line identity
- Station spacing proportional to geographic distance (would create illegible density at the center)
- Omitting the interchange mark at transfer stations

## Canonical Exemplars (DEGAS project)
- 0003 Beck (91.1): the 1933 London Underground map — highest-scoring work in the project

## Grammar Declaration
Beck's grammar was NOT declared in the 1933 map itself; it is derivable from the map. Declaration came through his design documents and the subsequent global adoption. Under rubric J modifier: derivable-not-declared = current standard (no bonus, no penalty).

## Adjacent Schools
- **Cartography**: uses geographic position; schematic-cartography deliberately abandons it
- **Information-architecture**: shares the network/flow representation; schematic-cartography is constrained to transit navigation
