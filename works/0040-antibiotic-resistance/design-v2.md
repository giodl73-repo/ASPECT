---
work: 0040-antibiotic-resistance
title: Global Antibiotic Resistance Rates — Cycle 2
school: statistical-graphics
type: A (School Member)
version: v2
rubric_version: v2.1
created: 2026-04-23
changes_from_v1:
  - Country rows sorted by income tier then stewardship index
  - Diverging color palette anchored at WHO stewardship target rates
  - Surveillance comparability note added
  - Country name background shaded by income tier
  - Bacteria columns sorted by WHO Priority classification
  - Uncertainty indicators added for low-surveillance cells
---

# Design Specification — 0040 Antibiotic Resistance (Cycle 2)

## Changes Implemented from Cycle 1 Recommendations

### Change 1: Country Row Ordering (implements Playfair, Tufte, Bertin, Du Bois recommendation #1)

Countries now sorted by: (1) World Bank income tier (High → Upper-middle → Lower-middle → Low), then (2) antimicrobial stewardship composite index (WHO AWARE Index + OECD stewardship indicator), ranked highest-stewardship to lowest within each tier.

**New order (top to bottom):**

*High income — good stewardship* (Norway, Sweden, Denmark, Netherlands, Germany, Canada, Japan, Australia, New Zealand, South Korea)
*High income — variable stewardship* (USA, France, Germany duplicate removed, Italy, Spain, Greece)
*Upper-middle income* (Brazil, China, Turkey, South Africa, Mexico, Thailand)
*Lower-middle income* (India, Pakistan, Vietnam, Nigeria, Kenya, Bangladesh)
*Low income* (Ethiopia, Democratic Republic of Congo)

**Visual separator**: thin horizontal rule between income tiers; tier label in left margin.

### Change 2: Diverging Color Palette (implements Playfair, Tufte, Bertin recommendation #2)

**New palette structure**: diverging, per-pathogen, anchored at WHO stewardship target:

Each pathogen column has its own reference target rate (based on WHO AWARE and published stewardship intervention evidence):

| Pathogen | WHO Target Rate | Rationale |
|----------|----------------|-----------|
| *E. coli* fluoroquinolone | ≤20% | Achievable with good stewardship; Nordic countries currently at 10-15% |
| *K. pneumoniae* carbapenem | ≤5% | Critical priority; <5% is achievable; any higher is severe stewardship failure |
| *S. aureus* MRSA | ≤15% | Achievable; Denmark at 1.5%; USA at 30% demonstrating stewardship impact |
| *S. pneumoniae* penicillin | ≤25% | Moderate; natural variation higher than other pathogens |
| *N. gonorrhoeae* ceftriaxone | ≤5% | WHO Gonorrhea Action Plan target for first-line treatment failure |

**Color encoding**: 
- Cells at or below target: blue gradient (pale = at target; saturated blue = well below target)
- Cells above target: red gradient (pale pink = slightly above; saturated dark red = severely above)
- White = exactly at target rate
- This makes the argument visible: blue = achieving stewardship goal; red = failing; darkness = degree of success/failure

### Change 3: Income Tier Country Name Shading (implements Du Bois recommendation)

Country name row backgrounds:
- High income: pale blue background
- Upper-middle income: pale yellow background
- Lower-middle income: pale orange background
- Low income: pale red background

This eliminates the information bottleneck of the small dot notation. The income tier is now visible at reading distance without close inspection.

### Change 4: Bacteria Column Ordering (implements Bertin recommendation)

Columns now ordered by WHO Priority Classification, highest priority first:

1. *K. pneumoniae* carbapenem (WHO Priority 1 Critical)
2. *E. coli* fluoroquinolone (WHO Priority 1 Critical — combination with ESBL)
3. *S. aureus* MRSA (WHO Priority 2 High)
4. *N. gonorrhoeae* ceftriaxone (WHO Priority 2 High)
5. *S. pneumoniae* penicillin (WHO Priority 3 Medium)

Column header now includes WHO priority designation: "Priority 1 CRITICAL / Priority 2 HIGH / Priority 3 MEDIUM."

### Change 5: Surveillance Comparability Disclosure (implements Statistician recommendation)

Added prominent yellow-background text box at top of figure:

> "Surveillance note: Countries participating in WHO GLASS (marked *) use standardized methodology. Non-GLASS countries use national surveillance; cross-country comparability varies. Gonorrhea resistance figures use EUCAST ceftriaxone breakpoints; some national systems use different thresholds. Use comparative rankings with caution for non-GLASS countries."

GLASS-participating countries marked with asterisk (*) beside country name.

### Change 6: Uncertainty Indicators (implements Statistician recommendation)

Cells where resistance estimate is based on <50 isolates or where surveillance methodology is flagged as non-comparable: numeric label italicized and followed by "~" symbol (e.g., "~73%"). Brief legend: "~ = estimate from limited surveillance data."

---

## Elements Retained from Cycle 1

- Sequential heat encoding logic (now replaced with diverging, but cell-based structure retained)
- Numeric labels inside all cells with adequate surveillance
- Missing data cross-hatch for cells with no data
- WHO GLASS / ECDC source citations
- Title and subtitle structure

---

## Additional Cycle 2 Element: Reference Column

**New rightmost column**: "Achievable target" — showing the WHO stewardship target rate for each pathogen as a colored reference strip (solid blue, at the target rate position). This makes the counterfactual visible as part of the matrix structure.

This is a contained application of the counterfactual visualization grammar (Cluster T): the counterfactual (achievable good-stewardship rate) is clearly labeled as a modeled target, not a measured rate. Modeling assumptions are the WHO intervention evidence base. This passes the counterfactual integrity checklist at 3/4 items; uncertainty in the target rate should be shown (gap: the target is shown as a single number, not a range).

---

## Expected Cycle 2 Score Projection

Based on the five changes implemented:

| Dimension | Cycle 1 | Expected Cycle 2 | Driver |
|-----------|---------|-----------------|--------|
| School Fidelity | 14.7 | 17.5 | Sort order, column priority order |
| Integrity | 15.6 | 16.5 | Surveillance note, uncertainty indicators |
| Legibility | 10.9 | 13.5 | Income tier background, sort structure |
| Execution | 12.0 | 13.5 | Diverging palette craft |
| Resonance | 10.6 | 13.0 | Argument now visible in structure |
| Purpose | 10.8 | 13.0 | Form now serves advocacy argument |
| **Total** | **74.6** | **87.0** | |
