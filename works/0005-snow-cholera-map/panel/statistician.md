---
work: 0005-snow-cholera-map
stage: panel
reviewer: statistician
lens: true
rubric_version: v1.3
created: 2026-04-23
---

# Statistician Lens — Panel Review

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| Data/Story Integrity | 14 | 20 |
| Legibility | 12 | 15 |
| **Weighted contribution** | *see SUMMARY* | — |

## Review

I have to work carefully here, because I am genuinely uncertain whether to praise this map or critique it, and that uncertainty is itself informative.

**On Data/Story Integrity:**

Step A (source quality): Snow collected death data first-hand, house by house, cross-referencing with the official death registry. For its time, this is exceptional source quality — better than Minard's estimated troop counts, better than Nightingale's classification-dependent mortality figures. No significant dock for Step A.

Step B (accuracy tradeoff): The one-mark-per-death encoding is as accurate as point event data can be. No tradeoff.

Step C (causation): This is where I must be honest about something methodologically important.

The spatial clustering of deaths around the Broad Street pump is a real pattern. The negative evidence (brewery, workhouse, and the traveling woman who preferred Broad Street water) significantly strengthens the case. Snow's inference — pump as source — is correct. We know this now because germ theory was established after his death and the waterborne transmission of cholera was confirmed.

But Snow did not know this. He did not know the mechanism. He was inferring causation from spatial correlation plus negative controls. In 1854, the dominant theory was miasma — that cholera spread through "bad air" — and the Broad Street neighborhood certainly had bad air (it was a densely poor area with poor sanitation broadly). Snow's spatial argument against miasma is strong but not decisive from first principles. The pump cluster could theoretically have reflected a local miasma source rather than a waterborne one.

What saves Snow's argument is the combination of: positive cluster + negative brewery + negative workhouse + outlier explanation. The joint probability of all these patterns arising from a miasma source is very low. Snow doesn't calculate this; he describes it in prose. The map shows the positive evidence; the text carries the rest.

I dock 3 points for Step C: the causal claim exceeds what the map alone can prove (the map shows clustering, not mechanism); the joint argument across positive and negative evidence is strong but not presented as a unified statistical argument; and Snow acknowledges no uncertainty in the causal claim even though mechanism was unknown.

Score 14 — excellent source data, correct encoding, significant causal gap.

**On Legibility:**

*Context: contemplative study, medical/scientific reader.*

For the primary context: the spatial pattern is visible. A physician reading this map in the context of Snow's book — which provides the negative evidence and the outlier explanation — can follow the full argument. The map alone, without the text, makes the weaker case (positive clustering only).

The legibility cost for the primary audience: the causal argument requires the analytical model (clustering = causal evidence) which was not established in 1854. A physician skeptical of Snow's approach would not know what to do with the spatial pattern because the framework for interpreting it was what Snow was proposing, not what they already held. For the sympathetic medical reader, legibility is 14/15; for the skeptical one, significantly lower.

I score 12 because I must account for the intended scientific audience's full range, including the skeptics who were Snow's primary target for persuasion.

## Innovations Flagged

1. **Causal claim without mechanism** — making a causal spatial argument (this source caused these events) without knowing or demonstrating the physical mechanism of causation. Snow was right; he was right by observation and spatial logic alone, without mechanistic knowledge. This is a specific form of Step C issue: the causal claim is not implied or overstated — it is explicitly stated — but it relies on a novel analytical framework (spatial clustering = causal evidence) that was not established at the time of publication. The rubric's Step C (causation claim integrity) handles overclaiming from established frameworks but not the distinct case of a correct causal claim made without the framework to prove it. *Rubric anchor: Data/Story Integrity (Step C). Implication: Step C should distinguish: (a) causal claim implied by correlation from established frameworks, (b) causal claim correctly stated using novel analytical framework not yet validated, (c) causal claim contradicted by data. These are epistemically different and should be scored differently.*

2. **The map as partial argument** — some works make only part of their argument visually, leaving the rest to accompanying text. Snow's map shows the positive evidence; his text provides the negative evidence (brewery, workhouse) and the outlier explanation. The full argument is map + text; the map alone is incomplete. The rubric currently assesses the work as a visual artifact, not as a text+image unit. For works where the visual and textual components are designed as a joint argument, scoring the image alone produces an artificially weak Data/Story Integrity score. *Rubric anchor: Data/Story Integrity / Legibility. Implication: for works designed as text+image units (scientific papers, books, reports), the rubric should specify whether it is scoring the visual alone or the joint text+image argument — and prefer the latter for works explicitly designed that way.*
