---
work: 0022-holc-redlining
reviewer: bertin
weight: 0.20
rubric_version: v1.9
---

# Bertin Review — HOLC Residential Security Maps

## Opening

I assess visual grammars. The grammar of this map is correct. The contamination is in the category construction, not the visual variable selection, and I want to be precise about where the grammar ends and the category construction begins — because conflating them produces a different error than the one this map makes.

## Visual Variable Audit

**Hue (green/blue/yellow/red) → Grade categories (A/B/C/D):**

Hue is a selective and associative variable. It groups marks: all red areas belong to the same category; all green areas belong to another. Hue is not ordered in the strict retinal sense — the eye does not automatically read a color sequence as a rank. However, the specific hue sequence chosen (green → blue → yellow → red) exploits cultural convention to imply order: green is go; red is stop. This is a connotative layer (Innovation #5, work 0001) used to impose evaluative order on a nominally ordered categorical variable.

The hue choice is appropriate for four ordered categories. The grammar is correct. The colors are culturally legible and retinally distinct. A colorblind viewer might confuse the green and red (the most common form of color vision deficiency), which is a craft issue for secondary audiences; the primary lending audience would not have had this problem in 1940.

**Position → Geographic location:**

Standard geographic encoding. Correct use of position for spatial data.

**Shape → Zone boundaries:**

Irregular polygons following neighborhood boundaries. Structurally appropriate.

Innovation #177: **Connotative order imposition** — using a culturally ordered hue sequence (green-yellow-red traffic-light convention) to impose evaluative rank on a categorical variable. Distinct from ordered variables (which have intrinsic rank) and from arbitrary hue assignment (which has no implied order). Connotative order works retinally but is not a property of the variable itself; it derives from cultural convention and can be exploited to make a categorical judgment appear to be an objective measurement.

## The Grammar-Category Boundary

The visual grammar ends where the categories begin. Bertin's framework asks: does the visual variable match the data type? For four ordered risk grades, an ordered hue sequence is an appropriate match. The grammar question is satisfied.

The category question — what does "Grade D" actually measure? — is not a grammar question. Grammar describes the mapping from data to marks. If the data is contaminated (Grade D = racial designation presented as risk measurement), the grammar can faithfully encode the contaminated data without error. The encoding is valid even when the argument is false.

This distinction is important for the rubric. Grammar failures produce wrong encodings of correct data. Category contamination produces correct encodings of wrong categories. These require different diagnoses.

Innovation #178: **Encoding validity vs. argument validity** — a visualization can be grammatically correct (visual variable matches data type; encoding is consistent and legible) and argumentatively false (the encoded categories do not represent what they claim to represent). The rubric's School Fidelity and Data/Story Integrity dimensions assess grammar and accuracy, respectively. Neither directly assesses category construction validity. Cluster N confirms this gap.

## Scoring

**School Fidelity (Type C): 15/20**

The cartographic grammar is correctly applied. The choropleth form is the appropriate encoding for categorical geographic data. The hue selection is appropriate for ordered categorical data. The synthesis of advocacy and cartography is coherent in form, if not in honesty. I cannot dock for grammar errors that do not exist. I dock for the undeclared advocacy character (a school-synthesis resolution failure) and for the connotative order exploitation.

**Data/Story Integrity: 9/20**

I apply Steps A–D. The source quality problem is severe: the categories were constructed from appraisers' racial attitudes, not default-rate measurements. Step A dock at maximum (−4): the implied precision (a four-grade measurement system) bears no relationship to the actual measurement basis (appraiser racial judgment). The causation problem (Step C) is circular: the designation causes the risk. Dock −3. The variable selection problem (Amendment L): race is the operative variable, undeclared. Dock −2. Starting from a notional 18/20, these docks bring the score to approximately 9.

**Legibility: 11/15**

The map is highly legible for its primary audience and purpose. The grade system is simple and immediately actionable.

**Visual Economy: 13/15**

Efficient four-category encoding. No decorative excess. The map is economical in marks.

**Resonance: 11/15**

Type III (advocacy efficacy): the map achieved its policy goal with high fidelity over several decades.

**Craft: 13/15**

Consistent, professional cartographic execution.

## Concluding Observation

I have spent my career arguing that visualization works when the visual grammar is matched to the data type. This map satisfies that criterion and should not be scored. I score it because the rubric requires me to, and because the category contamination — which is outside the grammar's scope — is something the rubric needs to address formally.

The grammar is innocent. The use is not.

## Summary

Bertin total: **72/100**
