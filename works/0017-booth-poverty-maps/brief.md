---
work: 0017-booth-poverty-maps
stage: brief
school: cartography
type: C  # deliberate synthesis: demographic + geographic
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
sources:
  - "Booth, Charles. Life and Labour of the People in London. 17 vols. London: Macmillan, 1889–1903."
  - "Booth, Charles. Descriptive Map of London Poverty, 1889. Four sheets."
  - "British Library: Maps CC.5.a.441"
---

# Brief — 0017: Charles Booth's Poverty Maps of London (1889)

## Work Identity

**Title:** Descriptive Map of London Poverty  
**Author:** Charles Booth (1840–1916)  
**Date:** 1889 (first edition; revised 1898–1899)  
**Form:** Hand-colored large-format map of London's street network, 4 sheets  
**School:** cartography (Type C synthesis: demographic + geographic)  
**Publication context:** Part of *Life and Labour of the People in London*, 17 volumes (1889–1903)

## What It Shows

A street-by-street map of London — primarily the East End — in which every street is colored according to the social class and poverty level of its inhabitants. The coloring scheme uses seven categories:

| Color | Category Label |
|-------|---------------|
| Black | Lowest class, vicious, semi-criminal |
| Dark blue | Very poor, casual, chronic want |
| Light blue | Poor, 18s to 21s a week for a moderate family |
| Purple | Mixed, some comfortable, others poor |
| Pink (rose) | Fairly comfortable, good ordinary earnings |
| Red | Middle class, well-to-do |
| Yellow/gold | Upper-middle and upper classes, wealthy |

The street network is drawn to accurate geographic scale on the base map. Color is applied street by street, not block by block, reflecting Booth's methodology: systematic door-to-door interviews with School Board visitors, police inspectors, and local informants, conducted between 1886 and 1889.

## Historical Context

Booth was a Liverpool-born shipping magnate and social reformer. He undertook the London survey after skepticism about socialist claims that one-quarter of Londoners lived in poverty. His survey found the actual figure was closer to one-third. The maps were produced to accompany the statistical volumes and to make the spatial distribution of poverty legible to reform-minded readers who might not read tables.

The maps were described at the time as the most systematic street-level survey of a major city ever conducted. They preceded and influenced the development of social geography as a discipline.

## What Makes This Work Difficult to Score

### 1. The categorical labeling problem

The seven category labels carry explicit moral and social value judgments. "Lowest class, vicious, semi-criminal" is not a neutral economic description — it is a characterization of character and behavior, not just income. The label conflates poverty with criminality in a way that was conventional in Victorian social thought but is now understood as a category error and a form of structural discrimination.

The rubric must decide: does categorical labeling that is accurate to the designer's analytical framework but morally contested score under Data/Story Integrity (the categories may accurately describe Booth's data model while being analytically wrong), School Fidelity (is this the grammar of cartography or of Victorian moralizing?), or Resonance (the labeling now reads differently than it did in 1889)?

### 2. The data model question

Is Booth's subject geography or social hierarchy? The map treats the street as the unit of analysis. But the underlying data is the household — the street color is an aggregation across many households with potentially wide internal variation. Streets with mixed populations are colored purple ("mixed"), but the visual form implies that the entire street is uniformly of that character.

The analytical data model (street = social unit) is convenient but not fully declared. Step D of Data/Story Integrity applies.

### 3. Color as social value judgment vs. neutral category

The color scale from black to gold is not merely categorical — it is thermally and culturally loaded. Gold is wealth and worth; black is darkness, threat, and moral danger. This is not an accident of the color spectrum — it is the Victorian moral geography made visible. Whether this constitutes an honest encoding of a socially-constructed category (Step A: source quality declared) or a form of confidence suppression (the categories present contested moral judgments as factual classifications) is the central integrity question.

## Panel Assignment

| Reviewer | Weight | Rationale |
|----------|--------|-----------|
| minard | 30% | Primary cartographic witness; spatial encoding of social data is his domain |
| bertin | 25% | Visual variables grammar: color as ordinal vs. nominal; choropleth analysis |
| tufte | 20% | Data density; categorical labeling as potential chartjunk vs. necessary legend |
| dubois | 15% | Advocate for populations encoded by others; understands the moral stakes of demographic mapping |
| historian | 10% | Victorian social science context; cartography school traditions |

## Key Questions for the Panel

1. How does the rubric handle categorical labeling that encodes social value judgment as objective classification?
2. What is the data model — is the street a legitimate aggregation unit, and is that declared?
3. Does the color scale's cultural loading (black = worst, gold = best) constitute connotative variable layer (Innovation #5) or is it a neutral ordinal encoding in Victorian context?
4. Does Booth's map qualify as Type C synthesis (cartography + sociology/demography), and if so, does the synthesis earn the +2 bonus?
5. How does the 1889 primary context (contemplative study by reform-minded readers) compare to the contemporary context (heritage display, scholarly study)?
