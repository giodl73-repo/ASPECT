---
work: 0054-gerrymandering-nc12
---

# Design Description — 0054 North Carolina Congressional District Map

## Visual Format

A standard political district choropleth map of North Carolina, showing the state's congressional districts as color-coded geographic regions. This format is the standard form for representing legislative district structure — used by election administrators, media organizations, and the public as the authoritative representation of "who represents where."

## Layout Architecture

**Geographic base:** North Carolina outline at the state level; county lines shown in light gray as reference; district boundaries shown in heavier weight.

**District coloring:** Each of the 13 congressional districts is assigned a distinct color. The standard rendering uses a categorical palette — one hue per district — without value encoding (all districts shown at equal visual weight, regardless of competitiveness, voter density, or population).

**NC-12 appearance:** In both versions, the 12th district has an irregular shape following highway corridors or demographic concentrations. In the 1993 version, it is famously elongated — a thin line connecting urban minority communities. In the 2012 version, it is less obviously bizarre but still irregular.

**No annotation of design intent:** The standard district map carries no annotation about how boundaries were drawn, what criteria were applied, or what electoral outcomes the district configuration produces. The map is a neutral representation of a political outcome, not a visualization of a political process.

## The Cartographic Grammar

A choropleth district map uses:
- **Position:** Geographic location (encodes place)
- **Shape:** District boundary (encodes jurisdiction)
- **Color (hue):** District identity — a nominal, categorical variable correctly encoded with a nominal visual variable

The grammar is correct. The encoding is honest. The map could not look different and still be a correct district map. This is the defining feature of process coercion with truthful encoding: the manipulation is embedded in what is being shown, not in how it is shown.

## The Honest Map Problem

Consider what an alternative map showing "electoral manipulation" would look like. It would not be a different district map; it would be a different kind of visualization entirely — perhaps a comparison of partisan vote share vs. seat share, or a visualization of the district-drawing algorithm's inputs and outputs. The standard district map format has no visual grammar for encoding "these boundaries were engineered."

A journalist or voter encountering the standard district map cannot read the manipulation from the map. The map is the authoritative representation; the manipulation is in the process that produced what the map represents. This is different from all other Cluster X cases, where the manipulation is in the visualization itself.
