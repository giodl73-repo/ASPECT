---
work: 0017-booth-poverty-maps
stage: panel
school: cartography
author: bertin
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
weight: 0.25
---

# Panel Review — Bertin on 0017: Booth Poverty Maps

## Opening

I will analyze this work variable by variable, as I always do. A map is a graphic system. Every mark has properties. The question is whether those properties are matched to the data they carry.

The Booth maps use a single primary visual variable — color — applied to a geographic base. The color carries the social classification. Let me examine whether this variable is correctly matched to what the data actually is.

---

## Variable Analysis

### Position

Position encodes geographic location. This is the natural and correct use of position in a cartographic work. The encoding is faithful: streets are where they are. Position does not encode social data — this is the right decision. If position had been distorted to reflect poverty levels, we would have a catastrophic grammar failure. Booth kept geography in position and put social data in color. Correct.

### Color (hue + value compound)

This is the central variable and the central question.

The seven-class system uses both hue and value (lightness/darkness) simultaneously. Black, dark blue, light blue, purple, pink, red, yellow-gold. This is an ordinal variable used to encode an ordinal classification. Is this correct?

Bertin's grammar says: color (hue) is **selective** and **associative** but NOT inherently **ordered**. Hue alone cannot encode rank — the viewer cannot reliably perceive that red is "more" than blue. Value (lightness/darkness) IS ordered — darker is consistently perceived as "more" of something.

The Booth palette is clever: it uses value primarily (black is darkest; gold is lightest and most saturated warm) with hue providing additional selective differentiation. The ordered direction of the palette is recoverable from value alone, even if hue varies non-monotonically. A viewer who does not see in color can still perceive the rough ordering from dark to light.

However: the compound variable (hue + value combined) is not a standard Bertin variable. It requires the viewer to integrate two properties simultaneously to achieve category identification. This creates cognitive load — not severe, but real.

**Grammar assessment:** The color encoding is not perfectly matched (pure value would be more ordinal-appropriate) but it is the best available compound solution for a seven-class ordinal system where categories must also be **selective** (individually identifiable). Pure value at seven steps is barely distinguishable. The hue addition allows selectivity at the cost of some ordinal ambiguity. This is a reasonable engineering tradeoff.

### The category label problem — from a grammar perspective

I must address this because it is not just an ethical or political question — it is a grammar problem.

A visual variable encodes a property of a data object. For the encoding to be faithful, the visual property must map to a real property of the subject. Position maps to geographic location — real, measurable. What does black (the compound of darkest value + most threatening hue) map to?

If it maps to "income at or below subsistence level," that is an economic fact, imprecise but real.  
If it maps to "vicious, semi-criminal character," that is a moral judgment, not a data property.

The two are not the same. The map presents them as if they are the same category — as if the visual variable is encoding a coherent data property. It is not. It is encoding two simultaneously: one factual (poverty), one contested (moral character). The visual variable cannot carry two semantically distinct properties without confusion.

This is what I would call a **variable overloading** error: the same visual element carries two non-equivalent properties, and the viewer cannot distinguish which property is being asserted.

---

## 1. School Fidelity /20 — Score: 15

The cartographic grammar is sound. Geographic position is maintained. Color is applied as an ordinal variable in a way that is functional if imperfect. The street-as-unit grain is innovative and appropriate to the data resolution.

The synthesis with social demography is executed at a functional level: the cartographic layer and the social data layer do not compete. The color variable is dedicated to social data; the position variable is dedicated to geography. This is a correct grammar for a Type C synthesis.

Deductions: the compound color variable creates some ambiguity; the category labels create a variable overloading problem that the grammar cannot resolve without explicit declaration.

**Score: 15/20**

---

## 2. Data/Story Integrity /20 — Score: 12

The variable overloading problem is the dominant integrity issue. The categories mix economic facts with moral judgments. The visual form presents both as equivalent properties of the subject. This is a Level 4 Step D issue (analytical framework undeclared and non-obvious): the viewer must supply the premise that "vicious, semi-criminal" is a legitimate social-scientific classification — a premise they are unlikely to hold without Victorian social context.

Additionally, the street-as-unit aggregation (Level 2 Step D — declared in adjacent documentation) creates imprecision that is not visible in the map.

**Score: 12/20** — Variable overloading between factual and moral categories is an analytical framework problem. Street-as-unit aggregation undeclared in map.

---

## 3. Legibility /15 — Score: 12

For the primary contemplative-study audience, legibility is good. The ordinal direction of the color scale is inferable even without the legend. The spatial pattern is clear. The fine grain of the street-level encoding rewards extended reading.

The primary legibility problem is the legend separation and the cognitive load of the seven-class compound color system. Seven distinguishable colors is near the limit of categorical differentiation in standard cartographic practice. Bertin's own research suggests five classes as the practical maximum for reliable differentiation; seven pushes this.

**Score: 12/15**

---

## 4. Visual Economy /15 — Score: 14

The work is economical at the mark level. Every colored street segment is a data mark. The geographic base is necessary for orientation. There is no decorative excess.

**Score: 14/15**

---

## 5. Resonance /15 — Score: 12

The gestalt is strong: the dark east and the warm west are a visual argument before any label is read. The advocacy resonance is historically demonstrated. I assess the same range as Minard.

**Score: 12/15**

---

## 6. Craft /15 — Score: 13

Consistent color application, accurate base map, professional execution for the period.

**Score: 13/15**

---

## Total: 78/100

| Dimension | Score |
|-----------|-------|
| School Fidelity /20 | 15 |
| Data/Story Integrity /20 | 12 |
| Legibility /15 | 12 |
| Visual Economy /15 | 14 |
| Resonance /15 | 12 |
| Craft /15 | 13 |
| **Total** | **78** |

---

## Innovation Flagged

**Innovation: Variable overloading — factual and moral categories sharing a visual channel** — Rubric anchor: Data/Story Integrity (Step D). When a visualization's category system mixes empirical measurements with moral judgments, and both are encoded through the same visual variable, the variable is overloaded: it appears to assert a single property of the subject but in fact asserts two non-equivalent properties. This is distinct from imprecise measurement (Step A) and from a contested data model (Step D standard): it is a category composition problem where the categories themselves mix incommensurable ontological types. The rubric should recognize this as a special form of analytical framework failure.
