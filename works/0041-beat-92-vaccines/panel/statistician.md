---
reviewer: statistician
work: 0041-beat-92-vaccines
weight: 0.10
rubric_version: v2.2
---

# Statistician Review — 0041 Beat-92 Vaccines

Data quality assessment first. WHO Global Health Observatory immunization coverage: government-reported, verified against survey data where available, standardized across reporting periods. UN IGME child mortality estimates: multi-model ensemble using civil registration, surveys, and demographic surveillance; peer-reviewed methodology. This is the gold standard for global health data. No GLASS ceiling problem. The data is complete, comparable, and well-documented. That is rare and should be stated clearly.

The encoding decisions are statistically appropriate. Bar length for mortality rate: correct — ratio data, linear scale, zero baseline. Gradient saturation for coverage percentage: appropriate — the saturation ordering matches the ordinal-to-quantitative nature of coverage percentages. Sorting by 2023 rate: correct choice for advocacy; transparently declared in methodology note.

The title "children are surviving because vaccines are working" makes a causal claim. I will examine it carefully. The correlation between DTP3/MCV2 coverage and under-5 mortality reduction is large (r ≈ 0.7 across countries), robust across income levels, and supported by strong mechanistic evidence (vaccines prevent specific diseases with known mortality contributions — measles, pertussis, diphtheria, tetanus). The causal claim is not merely an implied correlation; it is a claim with mechanistic support. I would note that it remains an observational claim — countries that scaled vaccines also improved sanitation, nutrition, and healthcare access — but the magnitude and specificity of vaccine-attributable mortality reduction is documented in the Lancet (Murray et al.) and NEJM literature. The "because" in the title is defensible.

Two honest concerns: (1) Confidence intervals on mortality estimates are suppressed. The UN IGME estimates carry ±15–25% uncertainty at country level. For countries with smaller populations, the uncertainty band is wide enough to overlap between 2000 and 2023 point estimates. This should be disclosed more prominently. (2) The gradient encoding combines two coverage indicators (DTP3 and MCV2) as sub-bars. Viewers may conflate overall coverage from these two indicators when actual coverage programs include a broader basket. This scope limitation should be noted.

Both concerns are minor relative to the work's overall integrity. The data is real, the methodology is sound, and the limitations are acknowledged.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 19/20 | Standard bar chart grammar applied correctly throughout |
| Integrity | 17/20 | Gold-standard data; causation claim defensible with caveats; CI suppression and indicator scope limitation are genuine undisclosed items, −1 each |
| Legibility | 13/15 | Technically readable; dual sub-bar with gradient requires legend attention; −2 |
| Execution | 14/15 | High economy; gradient justified as functional encoding |
| Resonance | 13/15 | Advocacy resonance strong; slight statistical restraint — some advocacy panels may want more explicit uncertainty framing |
| Purpose | 14/15 | Form-purpose alignment correct; stakes honest |
| **TOTAL** | **90/100** | |
