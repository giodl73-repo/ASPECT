---
work: 0004-dubois-paris-charts
stage: design
school: statistical-graphics, advocacy-visualization
review_type: canonical-import
historical_author: W.E.B. Du Bois
author: claude
rubric_version: v1.3
created: 2026-04-23
updated: 2026-04-23
sources:
  - Battle-Baptiste & Rusert 2018
  - Du Bois 1900 originals (Library of Congress)
---

# Design Description: Du Bois's Paris Charts

*Ten representative charts from the ~60-chart series, organized by formal strategy.*

---

## The Suite as a Whole

Before describing individual charts: the series has a visual identity. Every chart uses:
- A consistent limited palette: **red**, **black**, **tan/buff**, **green**, **gold/yellow**
- A consistent typography: hand-lettered, all-caps, confident — not tentative draftsmanship but a deliberate graphic voice
- A consistent rhetorical stance: every chart moves from "here is the number" to "here is what the number means for a people"
- Consistent physical scale (28 × 22 inches each) suggesting authority, not casualness

The suite answers a question before the viewer asks it: *Who are these people, really?*

---

## Selected Charts by Formal Strategy

### Chart 1 — City and Rural Population (Geographic bar chart)
A Georgia county map with superimposed bars showing Black population. Standard enough form — statistical-geographic hybrid familiar to the tradition. But: the bars are crimson, bold, impossible to ignore against the muted county geography. The color is not neutral categorical assignment; it is declaration.

**Encoding:** position = county, bar height = population, color = a uniform affirmation rather than a category

### Chart 2 — Increase of the Negro Population in the United States (Spiral timeline)
Population growth from 1790 to 1900, not shown as a line chart but as a spiral expanding outward from a center. Each decade is a segment of the spiral; the width of the segment encodes population. The spiral grows as it turns — visually, the population has been turning and expanding for a century.

This is formally invented. There is no prior visualization of a time series as an expanding spiral. The form implies: *this growth is centrifugal, accumulating, alive*. A line chart would show the same numbers with less rhetorical weight.

**Encoding:** angular position = decade, radial distance = population, form = centrifugal growth (non-standard)

### Chart 3 — Conjugal Condition (Comparative bar chart)
A horizontal bar chart comparing marital status (single, married, widowed, divorced) across: African Americans, Germany, France, Austria, Italy, and Russia. The comparison is designed to shock: Black American marriage rates compare favorably to European nations. The implicit argument is legible before reading a label: *we have families; we have institutions; we are not what you assumed*.

**Encoding:** horizontal bar length = proportion, color blocks = marital status categories, vertical axis = populations compared. Standard form; the comparison selection IS the argument.

### Chart 4 — Proportion of Freemen and Slaves Among American Negroes (Flowing timeline)
The most formally radical chart in the series. Shows the proportion of free versus enslaved Black Americans from 1790 to 1870, then the proportion of the formerly enslaved who achieved freedom, year by year. The form is neither a bar chart nor a line chart — it is a flowing ribbon that narrows and widens as the proportions shift. The emancipation year (1863–1865) produces a dramatic visual rupture: the "enslaved" band collapses and the "free" band floods the space.

**Encoding:** horizontal axis = time, band width = proportion free/enslaved, form = continuous flow with rupture event

This is the closest Du Bois comes to Minard's flow band — but where Minard's band encodes loss through attrition, Du Bois's band encodes liberation through rupture. The form choice is the argument.

### Chart 5 — Land Owned by Negroes in Georgia (Incremental area chart)
Shows acreage of land owned by Black Georgians across decades. Not shown as bars — shown as nested or stacked rectangles, each representing a decade's cumulative total. The rectangles grow. The visual effect: a person entering this area of the exhibit sees a stack of property, not a row of numbers.

**Encoding:** rectangle area = total acreage, stacking = temporal accumulation, color = deep red

### Chart 6 — Income and Expenditure of 150 Negro Families in Atlanta, Ga. (Comparative segmented bar)
A stacked horizontal bar chart showing how 150 families allocate income across categories (food, clothing, rent, taxes, church, education, other). The bars are segmented and colored by category. This is the most conventional chart in the series — and deliberately so. It makes the case with no formal invention: here is exactly how these families spend money. The ordinariness of the pattern is the argument.

**Encoding:** bar length = total income, segments = expenditure categories, color = category. Standard Playfair grammar; the data does the work.

### Chart 7 — Illiteracy (Comparative bar chart, international)
Compares illiteracy rates: African Americans vs. Romania, Russia, Italy, Spain, France, Germany, UK, the United States. The bars are sorted from highest to lowest illiteracy rate. Black American illiteracy (approximately 44% in 1900, down from near-100% in 1860) is high — but Romania, Russia, and Italy are higher. The chart does not suppress the Black illiteracy rate; it contextualizes it. The argument is precision, not flattery.

**Encoding:** bar length = illiteracy rate (%), vertical axis = nations, sorted descending. The sort order IS the argument.

### Chart 8 — Valuation of Town and City Property Owned by Georgia Negroes (Spiral area)
Similar to Chart 2 in form — a spiral showing decade-by-decade growth of property ownership. The spiral form here is even more dramatic: the outermost ring (1900) is many times wider than the innermost (1870). The visual reading: *explosive growth from almost nothing to meaningful wealth in 30 years*.

**Encoding:** spiral segment width = property value, angular position = decade, radial expansion = temporal sequence + growth

### Chart 9 — Occupations of Georgia Negroes (Multi-segment bar chart)
Occupation categories for Black Georgians across decades. Multiple bars per decade, each segment a different occupation. The chart is dense but legible at close reading. What stands out: the "Agriculture" bar shrinks relative to "Business, Manufacturing, and Mechanical" as the decades advance. The trend is visible before reading numbers.

**Encoding:** bar height = proportion, color = occupation category, horizontal grouping = decade

### Chart 10 — A Series of Statistical Charts: The Comparative Distribution of Negro and White Wealth
The final chart in our selection — and the most formally confrontational. A circle divided into sectors representing the distribution of wealth in Georgia between Black and white populations. The Black sector is small. The white sector is enormous. The form is pie-chart adjacent but the segment is drawn in deep red and outlined heavily. This is not a neutral presentation; it is an indictment drawn in ink.

**Encoding:** sector area = proportion of wealth, color = racial category (red = Black, neutral = white), form = circular comparison

---

## Consistent Design Logic Across the Suite

**Color as declaration**: Red is the Du Bois color. It is not assigned randomly or categorically — it marks the subjects of the charts as a positive presence, not a deficit. Red in Du Bois is assertion, not warning.

**Form as rhetoric**: When a standard form (bar chart, line chart) would serve the data but fail the argument, Du Bois invents or adapts a form. The spiral conveys centrifugal growth that a line chart cannot. The flowing ribbon conveys liberation as a rupture event that a stacked bar cannot.

**Comparison as the argument**: The suite's most powerful rhetorical move is comparative framing. Literacy rates vs. European nations. Marriage rates vs. European nations. Property ownership growth vs. nothing (there was nothing before). Every comparison is chosen to make the data say: *judged by the standards of civilization you claim to honor, this community has met them*.

**Precision as defiance**: the charts do not flatter. The illiteracy rate is accurately high; the income levels are accurately low. The precision is the argument — *we do not need to hide our numbers; look at what we have built from nothing, under what conditions*.
