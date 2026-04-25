---
work: 0017-booth-poverty-maps
stage: design
school: cartography
type: C  # deliberate synthesis: demographic + geographic
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
---

# Design Analysis — 0017: Charles Booth's Poverty Maps of London (1889)

*For canonical imports, the design document is an analytical description of the work's visual grammar, not a design specification. It serves as the artifact record for the panel to reference.*

---

## Visual Grammar

### Base structure

The map uses a conventional cartographic base: London's street network at approximately 1:10,560 scale (6 inches to 1 mile) across four sheets covering inner London. Streets are drawn as fine black lines; the street names are printed in small type. Geographic landmarks (the Thames, major parks, railway lines) are present but subordinated to the social-data layer.

The base map is accurate to the ordnance survey of the period. Geographic position is preserved; no topological distortion is introduced. This is straightforwardly cartographic.

### The primary encoding: color as social category

Every named street is colored from a seven-class palette. Color is applied as a band along the street centerline — essentially, the street itself is the colored mark, not the block or parcel.

Visual variable analysis (Bertin framework):

| Variable | Data mapped | Assessment |
|----------|-------------|-----------|
| Color (hue + value combined) | Social class category | Ordinal (implied); hue ranges from black to gold through blue, purple, pink, red |
| Position | Geographic location | Quantitative spatial |
| Length of colored segment | Street length only — not data | Structural |

The seven-class system uses hue and value simultaneously, creating a compound visual variable. Black carries the lowest value (darkest) and most threatening hue. Gold carries the highest value (lightest, most saturated warm) and most culturally positive association. Intermediate steps traverse blue (cold, poor), purple (mixed, ambiguous), pink (comfortable, warm), red (well-to-do, robust).

This is not a standard cartographic choropleth. Standard choropleths color areas (blocks, districts, parishes). Booth colors individual street segments — a finer grain that requires the underlying data to be street-level, not area-level.

### The legend

A printed legend accompanies the map sheets, giving the seven category labels in full. The legend is a separate artifact — it is not embedded in the map image. Viewers consulting the map without the legend would recognize that the colors mean something ordered (the progression is visually apparent) but would not know the specific category labels.

### Typography and cartographic elements

Street labels are in a single serif typeface at uniform size. No variation in label weight corresponds to social class — the street name appears in the same type regardless of the street's color. This is a deliberate choice: the color is the data; the label is the identifier.

Major landmarks and institutional buildings (churches, hospitals, markets) are shown but not specially emphasized. The social data layer is dominant.

### Scale and coverage

The four-sheet map covers central London from Hammersmith to Stepney (east-west) and from Hampstead to Brixton (north-south). The East End — the area of most intense poverty investigation — receives the greatest geographic attention. This is not a distortion but a selection: the map covers where Booth's survey was most dense.

---

## Analytical Framework Assessment

**Step D (Data/Story Integrity) pre-assessment:**

Booth's data model is: *the street is the social unit.* This means:

1. The street's color represents an aggregated judgment across all households on that street
2. Where a street had mixed inhabitants, it was colored purple ("mixed")
3. Where a street had a dominant character, it was colored accordingly

This aggregation is a methodological choice, not a natural property of streets. A street is not inherently a social unit — a single street might contain households ranging from destitution to comfort. The methodological decision to treat it as a unit is undeclared in the map itself; it is described in the accompanying volumes.

**Category construction:**

The seven categories are not income bands with precise thresholds. They are qualitative assessments made by Booth's informants (School Board visitors, police constables, clergy) using descriptive criteria. The categories blend:
- Economic descriptors ("18s to 21s a week")
- Moral descriptors ("vicious, semi-criminal")
- Stability descriptors ("casual," "chronic")
- Aspirational descriptors ("comfortable," "well-to-do")

This mixing of economic fact with moral judgment is a property of the categories themselves, not of the cartographic encoding. The map faithfully encodes the categories — but the categories are contested.

---

## What the Work Achieves

At the level of cartographic execution, the Booth maps achieve something genuinely novel for 1889: a complete, systematic, street-level social survey of a major world city rendered spatially. The spatial distribution of poverty — concentrated in the East End, scattered in inner districts, thinning toward the suburbs — is immediately visible as a spatial pattern that no table could convey.

The maps are the first systematic demonstration that poverty is not randomly distributed but spatially clustered — a pattern that implies structural causes rather than individual moral failure. This is an argument the maps make through their visual grammar regardless of whether the category labels support it.

At the level of categorical construction, the maps embed Victorian moral taxonomy in a spatial form that presents it as objective classification. The label "Lowest class, vicious, semi-criminal" does not describe income; it describes a population as criminal in character. This is not what the map's color encodes (the color encodes the aggregated social classification) — but it is what the legend declares the color to mean.

---

## School Classification

**Type C — Deliberate Synthesis:** cartography + Victorian social science/demography

- Cartographic dimension: street-network base, geographic scale, position-as-location
- Demographic dimension: household survey data, social classification, category system

The synthesis is partially declared: Booth describes the methodology in the accompanying volumes, and the map is explicitly presented as a cartographic representation of social data. The cross-school tension (geographic precision vs. social-category imprecision) is not explicitly resolved; it is simply executed at the level of the street-as-unit aggregation.

**Synthesis bonus eligibility:** Partial. The synthesis is declared in the publication (adjacent documentation) but not in the map itself. The cross-school tensions (geographic vs. social data models; ordinal color vs. morally-loaded categories) are not resolved — they are present as latent contradictions.

---

## Version Note

`version_reviewed`: The 1889 first edition, as reproduced in facsimile by the London School of Economics (LSE) Charles Booth Online Archive.

`institutional_divergence`: Low. The maps have not been modified since publication. The LSE archive presents them as produced. The categories and coloring are original.

`context_decay`: High. The 1889 primary context (urban reform readers, Parliamentary advocates, social investigators) is essentially gone. Contemporary viewers encounter these maps as heritage objects, data history artifacts, or scholarly subjects — not as live reform instruments.
