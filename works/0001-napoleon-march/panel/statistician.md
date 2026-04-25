---
work: 0001-napoleon-march
stage: panel
reviewer: statistician
lens: true
rubric_version: v1.0
created: 2026-04-23
---

# Statistician Lens — Panel Review

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity | — | 20 |
| Data/Story Integrity | 13 | 20 |
| Legibility | 11 | 15 |
| Visual Economy | — | 15 |
| Resonance | — | 15 |
| Craft | — | 15 |
| **Weighted contribution** | *see SUMMARY* | — |

*Lens reviews score only the dimensions within their focus. The statistician scores Data/Story Integrity and Legibility.*

## Review

I have several data quality concerns with this work. I will present them in order of severity.

**Source data quality — troop counts:**

The 422,000 figure is a construction. It aggregates French and allied forces from multiple corps that departed at different times and from different crossing points. The 422,000 represents the peak combined strength in the theater, not a count taken at a single moment at the Niemen. Subsequent figures (327,000 at Wilna, etc.) come from fragmentary corps-level records, many destroyed in the retreat itself or afterward during the political chaos of post-Napoleonic France. Some figures appear to have been interpolated by Minard from the best available evidence.

This is not fabrication — Minard was scrupulous by the standards of his era. But the band width implies a precision that the data does not have. There is no uncertainty envelope on the band. The figures labeled along the band are presented as exact; they are at best approximate.

**Source data quality — temperature:**

The temperature readings attributed to the retreat come primarily from the memoirs of Armand de Caulaincourt, Napoleon's master of horse, written years after the fact from his journals. Caulaincourt recorded temperatures, but not in a systematic meteorological sense — they are personal observations, not instrument readings. Corroborating records exist (Russian sources, other French memoirs) and broadly agree, but the precision of the plotted line is greater than the underlying data supports.

The Réaumur scale is also a barrier: the modern reader must convert mentally (or look it up) to understand that −30°R ≈ −37.5°C ≈ −35°F. The visualization provides no conversion.

**Implied causal claim:**

The juxtaposition of the retreat band and the temperature chart implies causation: cold weather killed soldiers. This is partially true — cold was a major cause of death. But the principal causes of the Grande Armée's losses during the retreat were, in roughly descending order: disease (typhus, dysentery), starvation, combat losses, desertions, and cold. The visualization, by pairing band width with temperature, implies a causal relationship that is real but overstated. The data supports "cold correlates with elevated losses during the retreat." The visualization implies "cold caused the retreat's losses." These are not the same claim.

**Comparability problem:**

The advance band (422,000) and the retreat band (beginning where the advance ends, at Moscow) do not represent the same population. Some soldiers who participated in the advance never went to Moscow — they garrisoned supply lines, fought at Smolensk, or deserted. The 100,000 who returned from Moscow to begin the retreat are not the same 100,000 who started the advance from the Niemen. The band implies continuity of population; the reality is that the population being counted shifted throughout the campaign.

**What the work does correctly:**

The direction of the argument — this army was catastrophically destroyed — is accurate. The order of magnitude of the losses is correct. The timing of the worst losses (Berezina crossing) corresponds to documented events. The visualization does not lie about the historical story; it simplifies and clarifies it. My concerns are about the precision implied by the form, not about the truth of the underlying narrative.

## Innovations Flagged

1. **Implied causation from juxtaposition** — placing two data series in spatial proximity implies a causal relationship between them. The work does not assert that cold caused the losses; it places cold next to losses and allows the reader to conclude causation. This is a form of visual argumentation that the rubric does not currently assess under Data/Story Integrity. *Implication: the rubric should explicitly score whether causal implications from spatial juxtaposition are warranted by the underlying data.*

2. **Population continuity assumption** — flow visualizations that show a continuous band imply that the same population is being tracked throughout. When the tracked population changes (through garrisoning, detachment, desertion), the implied continuity is false. The rubric should score whether flow encodings correctly declare population changes. *Implication: add a population-tracking criterion to Data/Story Integrity for flow visualizations.*
