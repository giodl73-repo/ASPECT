---
work: 0027-green-space-inequality
title: Green Space Inequality in 10 US Cities
school: narrative-visualization
type: A (School Member)
rubric_version: v1.11
created: 2026-04-23
---

# Design Specification — 0027 Green Space Inequality in 10 US Cities

## Format

Scroll-driven web essay. Mobile-first design, readable on desktop. Total scroll length: approximately 12 screens. Each section revealed progressively as the viewer scrolls. Text annotations advance the narrative between visualization reveals.

Primary reading context: contemplative study (web browser, solo, extended time available). Narration mode: standalone — the essay structure provides its own narration through text annotations.

## Section 1: The Opening (no chart)

Full-bleed satellite image: a 6-block area in the South Side of Chicago (63rd Street corridor). Heat overlay in infrared false color — surfaces above 40 degrees C in deep orange-red, below 25 degrees C in blue-green. The image is a 2021 July heat event composite. No trees visible in the target blocks. Adjacent wealthier neighborhood (Hyde Park) visible at the edge of the frame, noticeably cooler in color.

Headline (overlaid, white sans-serif): "On the hottest days, your neighborhood is either a greenhouse or a park. That choice was made for you decades ago."

Subtext: "In Chicago, a resident of Englewood is 8 degrees F hotter on a summer afternoon than a resident of Lincoln Park — same city, same day, different tree canopy. This is not weather. This is policy."

No data labels on the satellite image. The infrared colors carry the argument. The opening is designed to stop the scroll.

## Section 2: City Comparison (Statistical Graphics — Bar Chart)

Data: Tree canopy percentage by income quartile (Q1=lowest 25%, Q4=highest) for 10 US cities: Chicago, Houston, Phoenix, Atlanta, Detroit, Seattle, Baltimore, Denver, Memphis, New Orleans. Source: USDA Forest Service Urban FIA 2021 data.

Form: Grouped bar chart. 10 city clusters on the horizontal axis; 4 bars per city (Q1-Q4). Bars vertical; height = canopy %. Color: Q1 through Q4 encoded as a sequential palette from pale green to dark green. The income-canopy gradient is visible as a within-cluster color gradient.

Key annotation: A horizontal red dashed line at 30% marks the 3-30-300 standard canopy target. Only Q4 bars in Seattle and Denver cross it. No city Q1 bar reaches it.

Text above chart: "In every city measured, richer neighborhoods have more trees. The gap is not marginal — it is structural."

Tufte compliance: No background fill, no gridlines beyond the 30% reference line, direct labeling on selected bars.

## Section 3: Neighborhood Heat Map (Cartography)

Data: Chicago neighborhood-level (77 community areas) tree canopy % (USDA FIA 2021) overlaid with NOAA/NASA July mean afternoon temperature (LST, 2019-2021 average).

Form: Choropleth base layer showing tree canopy % as a value gradient (white = 0%, dark green = 40%+). Temperature deviation shown as a warm red-orange overlay layer using dot density. Two visual variables (hue/value for canopy; dot density for temperature) to avoid visual conflict.

Key annotation: Three neighborhoods labeled by callout: Englewood (2% canopy, +9F above city mean), Hyde Park (22% canopy, +1F), Lincoln Park (28% canopy, -2F).

Text above map: "Chicago's canopy gap follows the geography of historical disinvestment."

## Section 4: Historical Cause (Timeline)

Data: Tree canopy % estimated (aerial photo analysis and USDA records) for three Chicago neighborhoods (Englewood, Lakeview, Hyde Park) at 6 time points: 1970, 1980, 1990, 2000, 2010, 2021.

Form: Connected line chart. Three lines, directly labeled at right end. Horizontal axis: year. Vertical axis: canopy % (0-40%).

Key annotations on horizontal axis: "1973: Federal redlining maps abolished (HCDA)"; "1981: Reagan-era CDBG cuts." Englewood line shows sharp decline through the 1980s-90s; Lakeview and Hyde Park show modest increase over same period.

Text above chart: "The canopy gap widened as a direct consequence of urban renewal, redlining, and disinvestment. The trees lost were not replanted in the neighborhoods that lost them."

Du Bois compliance: This section explicitly names redlining and racial zoning as causes. The text uses these terms directly and does not soften the historical cause with purely neutral economic language.

## Section 5: Design Prescription (Information Architecture)

Form: Three-panel visual checklist. Each panel represents one element of the 3-30-300 rule. Each panel shows the rule element (large bold number), the standard (descriptive text), current status for the 10 cities as a Q1-vs-Q4 split bar showing % of residents meeting the standard, and a simple illustration icon.

Text above checklist: "The 3-30-300 standard is not aspirational — it is the minimum. It is achievable. No city currently meets it for all residents."

Closing text: "Planting trees in Englewood is not landscaping. It is public health infrastructure. It is climate resilience. It is the correction of a decades-long policy error. The measurement tool exists. The standard is set. The choice is political."

## Narrative Structure

Five sections follow a structured argument:
1. Establish emotional stakes (satellite heat image)
2. Show the quantitative pattern (bar chart, 10 cities)
3. Show the spatial pattern (Chicago heat map)
4. Name the historical cause (timeline + redlining annotation)
5. Provide actionable prescription (3-30-300 checklist)

The aha moment is designed for Section 4 — when the viewer connects the redlining annotations to the current canopy gap they have just seen in Sections 2-3.

## School Grammar Compliance

Narrative visualization constitutive principles fully applied: sequence, guided attention via text annotations, progressive disclosure, designed aha moment at Section 4, annotation as narration integral to the argument (not supplementary).
