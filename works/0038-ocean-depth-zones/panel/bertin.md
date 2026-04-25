---
work: 0038-ocean-depth-zones
reviewer: bertin
weight: 0.25
rubric_version: v2.0
---

# Bertin — 0038 Ocean Depth Zones

## School Fidelity /20 → 17

I audit the visual variables: primary axis (Y-position encoding depth), and five flanking encodings.

**Y-position encoding depth**: position is ordered and quantitative. Depth is ordered-quantitative. Correct pairing. The axis runs downward — 0m at top, 11,000m at bottom. This is the axis inversion I identified in work 0031 (#221: axis inversion as ecological grammar requirement). The ocean context confirms the principle: the gravitational hierarchy demands that depth increase downward. I find this natural, not counterintuitive. Surface is where you are; depth is where you go; the eye follows the same direction as descent.

**Light intensity (left panel, horizontal bar)**: size (bar length) is ordered and quantitative. Light intensity is quantitative. Correct pairing. The logarithmic scale is essential — light decreases exponentially with depth; a linear scale would make the entire meaningful variation occur in the top 10% of the diagram. The log scale must be declared.

**Temperature (right side, horizontal line)**: position (horizontal displacement) encoding temperature is quantitative. Temperature is quantitative. Correct pairing. The thermocline signature (sharp gradient in the 200-1000m range) should be visually distinct — this is the most ecologically significant temperature feature.

**Pressure (numeric annotation)**: text annotation at zone boundaries. Acceptable for a variable with such a large range (1-1100 atm) that a proportional bar encoding would compress all below-10-atm values to invisibility.

**Oxygen (far right, horizontal bar)**: size encoding oxygen concentration. The OMZ dip at 200-1000m must be legible — this is the diagram's most counterintuitive feature and its most important ecological insight. The bar should be labeled "Oxygen (ml/L)" with the OMZ dip explicitly annotated.

**Species density (illustrated silhouettes)**: this is not a Bertin visual variable in the strict sense — it is a density-of-marks encoding rather than a continuous variable encoding. But for species diversity, which is a complex multivariate quantity not reducible to a single scale, density-of-marks is the appropriate semi-quantitative encoding. Acceptable.

Five encodings: four correctly matched, one (species density) appropriately non-standard. School fidelity is high.

## Integrity /20 → 17

The ecological data is accurate (OMZ, thermocline, photic zone boundary, pressure values). The logarithmic scale for light is declared (or should be). The zone boundaries are shown as fuzzy gradients rather than crisp lines — ecologically honest, since zones are defined by conditions that vary by location.

One integrity note: the temperature profile (30C at surface to 1-2C at depth) is representative of tropical and temperate oceans. Polar oceans have a very different profile — the thermocline is weaker or absent, and surface temperatures are close to 0C. The diagram should declare its geographic scope: "Representative profile for tropical-temperate open ocean; polar ocean profiles differ significantly."

## Legibility /15 → 13

The five-panel array flanking a central depth axis is the correct structural form for this subject — it is how oceanographic profiles are standardized in the scientific literature. The scientific audience will recognize the structure immediately. The general reader will need the legend and zone labels.

The OMZ dip (oxygen concentration dip in the mesopelagic zone) is the most important legibility challenge: it is counterintuitive (one expects oxygen to decrease monotonically with depth), and its correct reading depends on the viewer understanding that the dip is real and important, not a data error. An explicit annotation — "Oxygen Minimum Zone — caused by bacterial decomposition of sinking organic matter" — is essential for the general reader.

## Execution /15 → 14

Intrinsic complexity (Cluster H) applies. Five variables across 11,000m of depth is intrinsically necessary for the ecological argument. No decorative elements. Economy is high.

The craft decision I would flag: the zone boundary transitions should be consistently drawn as fuzzy gradients (not crisp lines) across all five variable panels — if the light panel shows crisp zone boundaries and the temperature panel shows gradients, there is inconsistency. All panels should use the same zone boundary convention.

## Resonance /15 → 13

Domain resonance for oceanographers and ecologists is high — the Humboldt grammar, the OMZ, the thermocline, the species density distribution are all immediately recognizable and correctly presented. The diagram functions as a reference visualization for ocean ecology, which is the highest domain resonance standard.

Experiential resonance for general readers: the scale of the depth axis (0 to 11,000m — from sea surface to the deepest point on Earth) creates genuine awe when the reader understands what the numbers mean. The diagram should anchor two or three depth reference points: 40m (recreational diving limit), 332m (deepest SCUBA dive), 200m (edge of photic zone), 1000m (deep-sea submarine range), 11,000m (Mariana Trench).

## Purpose /15 → 14

Informational purpose: making ocean vertical ecology legible. The gravitational hierarchy (axis runs downward) makes the diagram immediately physically intuitive. Purpose is well served.

## My Total: 88/100

Strong ecological visualization. The axis inversion is confirmed as natural and correct for ocean ecology. Cluster U confirmed.

## Innovation Flagged

**#254 — Gravitational hierarchy in ocean vs. soil ecology**: the downward depth axis in ocean ecology (0m surface at top, 11,000m trench at bottom) uses the same gravitational hierarchy principle as the downward soil axis in work 0031 (0cm surface at top, 150cm at bottom). In both cases, the axis follows the direction of depth increase under gravity. The principle generalizes: any ecological visualization with a depth or altitude gradient should orient its primary axis to follow the gravitational hierarchy. Top = surface/zero-depth/sea-level; bottom = maximum depth; up = altitude above sea level. This is a simple, universally applicable rule that the rubric should codify as part of the Ecological Visualization school's grammar.
