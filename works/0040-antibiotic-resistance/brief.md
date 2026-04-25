---
work: 0040-antibiotic-resistance
title: Global Antibiotic Resistance Rates (2023)
school: statistical-graphics
type: A (School Member)
rubric_version: v2.1
created: 2026-04-23
score_target: 92+
cycle: 3-cycle revision experiment
---

# Brief — 0040 Global Antibiotic Resistance Rates (2023)

## Subject

Percentage of key bacterial infections resistant to first-line antibiotics, across 30 countries, for five bacterial species. Data year: 2023.

## Five Bacterial Species

| Bacterium | First-line antibiotic | Clinical significance |
|-----------|----------------------|----------------------|
| *Escherichia coli* | Ampicillin / fluoroquinolones | Urinary tract infections, sepsis |
| *Klebsiella pneumoniae* | Carbapenems / cephalosporins | Hospital-acquired pneumonia, sepsis |
| *Staphylococcus aureus* | Methicillin (MRSA) | Skin infections, endocarditis, sepsis |
| *Streptococcus pneumoniae* | Penicillin | Pneumonia, meningitis, ear infections |
| *Neisseria gonorrhoeae* | Ceftriaxone / azithromycin | Gonorrhea — resistance now widespread |

## Thirty Countries

Drawn from all income tiers (World Bank classification):
- **High-income, good stewardship**: Norway, Sweden, Denmark, Netherlands, Germany, Canada, Japan, Australia, New Zealand, South Korea
- **High-income, weaker stewardship**: USA, France, Italy, Spain, Greece, South Korea (dual-listed for comparison)
- **Upper-middle income**: Brazil, China, Turkey, South Africa, Mexico, Thailand
- **Lower-middle income**: India, Pakistan, Vietnam, Nigeria, Kenya, Bangladesh
- **Low income**: Ethiopia, Democratic Republic of Congo

## Core Message

Resistance is not uniformly distributed. Lower-income countries with high antibiotic use but poor stewardship have the worst resistance rates. High-income countries with good stewardship have maintained lower rates despite equivalent or higher total antibiotic use. The distribution reveals that stewardship — not income or use volume alone — is the critical variable.

## Audience and Context

- **Primary audience**: infectious disease policymakers, WHO health ministers, global health researchers
- **Statistical literacy**: high
- **Reading context**: contemplative study (policy report, extended solo reading)
- **Narration mode**: standalone

## School Attribution

**Statistical graphics (Type A)** — Playfair's grammar is the highest-scoring school for comparative quantitative data across many categories. A 30-country × 5-bacteria matrix is exactly the kind of multi-variable comparison the school was built for. The Bertin matrix-reordering technique (sorting rows and columns by similarity to reveal structure) is directly applicable.

## Revision Cycle Plan

| Cycle | Design | Key question |
|-------|--------|-------------|
| 1 | Heat matrix (countries × bacteria), resistance in color intensity | Does the base grammar work? What are the primary gaps? |
| 2 | Revised heat matrix: sorted by income tier, added WHO-standard counterfactual, improved color palette | Do the top Cycle 1 recommendations improve the score significantly? |
| 3 | Final design: implement remaining recommendations | Can 90+ be achieved? Can 92+ be achieved? |

## Data Notes

Resistance rates (illustrative, based on published ECDC, WHO GLASS, and CDC surveillance 2023 estimates):
- Nordic countries: E. coli resistance ~10–20%; K. pneumoniae carbapenem resistance <5%
- India, Pakistan: E. coli resistance 70–85%; K. pneumoniae carbapenem resistance 40–60%
- USA: MRSA prevalence ~30%; declining due to stewardship
- Greece, Turkey: K. pneumoniae carbapenem resistance 30–50%
- Sub-Saharan Africa: variable; surveillance data sparse

These figures inform the design; actual visualization uses cited GLASS 2023 database figures.
