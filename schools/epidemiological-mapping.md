---
slug: epidemiological-mapping
name: Epidemiological Mapping (Geographic Source-Tracing)
primary_personas: [minard, nightingale, bertin]
adjacent_schools: [cartography, statistical-graphics]
founded: 1854 (Snow's Broad Street work); published 1855
founder: John Snow
canonical_works: [0005-snow-cholera-map]
---

# Epidemiological Mapping

## Origin and Claim

Founded by John Snow's Broad Street cholera map (1855). The school's founding claim: when events cluster spatially around a candidate source, the spatial pattern constitutes evidence for that source's causal role. Geographic position is not merely context — it IS the argument. This is distinct from cartography (which shows where things are) and from statistical graphics (which compares quantities): epidemiological mapping uses the distribution of events to prove something about causes.

The founding analytical framework — spatial clustering as causal evidence — was Snow's scientific innovation. It was not declared on the map itself; it was argued in the accompanying text of *On the Mode of Communication of Cholera* (1855). Under rubric v1.5 Step D: Level 2 declaration (adjacent documentation).

## Visual Grammar

### Primitives
- **Event mark**: one mark per event (death, case, incident) at its exact geographic location; never aggregated before plotting
- **Source candidate marker**: a distinct symbol at each candidate source location (pump, factory, well)
- **Geographic base**: street grid or terrain necessary for reading the clustering pattern; nothing else
- **Negative space**: the absence of event marks in regions where events would be expected is active evidence; the base map must extend to include evidentially significant absences

### Compositional Rules
1. **One mark per event**: plot individual events; let the cluster emerge from the aggregate; never pre-aggregate
2. **Geographic fidelity**: position must be accurate — the clustering argument depends on where marks actually are
3. **Include negative evidence**: the map must show areas where events did NOT occur, especially areas with alternative candidate sources
4. **Source-control differentiation**: visually distinguish the candidate source from the control candidates (other potential sources that did not produce the cluster)
5. **Sufficient density**: enough events must be plotted that the clustering pattern emerges visually; if event count is too low, the pattern does not emerge

### Encoding Conventions
- **Position**: geographic (primary; the argument depends on it)
- **Mark presence**: binary (event / no event); stacking encodes count at a single location
- **Mark count (stacked)**: quantitative by counting; saturates at high densities (variable-capacity saturation, innovation #47)
- **Source symbol shape**: categorical (pump / well / factory; source-type)

### Forbidden Moves
- Pre-aggregating events before mapping (suppresses local clustering patterns)
- Omitting the geographic area where events are absent but would be expected
- Mapping all candidate sources identically (hides the source-control contrast)
- Claiming causal proof from spatial correlation alone (the map shows correlation; the causal argument requires the full triangulation with negative evidence and outlier explanation)

## Canonical Exemplars (DEGAS project)
- 0005 Snow (85.9): Broad Street cholera map; domain-gated resonance; undeclared analytical framework (Step D Level 4)

## Data Model Declaration note
The analytical framework (spatial clustering = causal evidence) was Snow's founding innovation, not an established method in 1854. The map presents data faithfully but the causal interpretation requires the viewer to supply the analytical premise — which most viewers in 1854 did not hold. Step D Level 4 dock applied. Subsequent epidemiological maps operating in an established field score better on Step D.

## Adjacent Schools
- **Cartography**: geographic base; epidemiological mapping adds event-distribution-as-argument
- **Statistical-graphics**: quantitative comparison; epidemiological mapping uses spatial pattern rather than abstract proportion
