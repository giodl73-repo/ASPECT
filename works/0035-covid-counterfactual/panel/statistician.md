---
work: 0035-covid-counterfactual
reviewer: statistician
weight: 0.15
rubric_version: v2.0
---

# Statistician — 0035 COVID-19 Deaths and the Masking Counterfactual

## School Fidelity /20 → 16

The synthesis of statistical-graphics and advocacy-visualization creates a particular integrity challenge that I want to name clearly: when a statistical chart is deployed for advocacy, there is pressure to present the counterfactual as more certain than the modeling supports. This design resists that pressure correctly — the uncertainty band is shown, the range is declared, the modeling basis is named. The synthesis is disciplined.

The form choice (temporal area fill vs. static bar) is appropriate for the data type. Time-series cumulative data should be shown as a time series, not collapsed to a single comparison point. This is a statistical graphics decision made correctly.

## Integrity /20 → 16

I will examine the counterfactual modeling claims precisely.

**The 85% compliance assumption**: the three named models (Stutt et al. 2020, Howard et al. 2021, CDC ensemble) all use different compliance modeling assumptions. The design uses these as an ensemble and shows the range, which is appropriate. But I note: Stutt et al. was published in June 2020, before Delta; Howard et al. was a meta-analysis of pre-Delta effectiveness studies. The CDC ensemble estimates (if the 2021 internal estimates are the ones referenced) may or may not incorporate Delta's higher transmissibility. This should be declared: "Counterfactual models use pre-Delta mask efficacy assumptions; Delta-period estimates carry higher uncertainty."

**The "achievable" framing**: the brief notes that 85% compliance was not achieved nationally. The design should not use the word "achievable" — it should say "modeled at 85% compliance," which is what the models do. This is a framing integrity issue.

**The causal claim**: the design implies masking adoption = deaths prevented, at the modeled ratio. The causal chain (masking → reduced transmission → reduced deaths) is well-supported in peer review. The confounders (behavioral spillovers, economic effects, vaccination timing interactions) are not modeled. The design should note this: "Counterfactual holds all other factors constant." This is standard epidemiological disclaimer language and should appear in the figure note.

Despite these notes, the overall integrity is good — the range and uncertainty band signal honest uncertainty, and the modeling basis is named.

## Legibility /15 → 13

For the intended audience (policymakers, public health researchers, informed general public), the temporal area fill is legible. The uncertainty band could be confusing to general audiences unfamiliar with confidence intervals — a label would help. The terminal range bracket (130,000–180,000) correctly communicates modeling uncertainty to non-statisticians.

## Execution /15 → 13

The design is economical. My only Execution note is that the uncertainty band should be consistently visible throughout the chart, not just at the terminus. If the uncertainty band is only shown at the end (as a terminal bracket), it underrepresents the full uncertainty in the counterfactual trajectory. Show the band along the entire counterfactual line.

## Resonance /15 → 12

For the statistician audience, the design is credible and well-structured. The range and uncertainty band are the right signals. For a general audience, the temporal accumulation of the gap creates genuine resonance — the growing red space communicates something that a single number cannot.

I would not claim this work achieves domain resonance at the highest level — a statistician looking at this would want to see the full model specifications, not just the ensemble range. But for an advocacy work targeting decision-makers rather than statisticians, the level of statistical disclosure is appropriate and honest.

## Purpose /15 → 13

Advocacy work on a subject with 800,000 deaths. The statistical disclosures are proportionate to the stakes and the context. The design is honest enough to be credible; it is accessible enough to reach its audience. Purpose is well served.

## My Total: 83/100

Strong work with three precision revisions needed: Delta variant assumption declaration, "achievable" framing correction to "modeled at 85%," and all-factors-constant disclaimer. The counterfactual gap technique is statistically defensible and the generalization from work 0029 is structurally sound.

## Innovation Flagged

**#237 — Counterfactual integrity checklist for advocacy visualization**: the work surfaces a specific set of integrity questions that apply to any counterfactual visualization. These questions are not fully captured by the v2.0 Integrity dimension's three sub-questions (Disclosure, Argument, Framing). A counterfactual-specific integrity checklist would include: (1) Is the counterfactual scenario labeled as modeled vs. empirical? (2) Are the modeling assumptions (compliance rate, period, pre/post-variant) declared? (3) Is the causal chain (intervention → outcome) supported by evidence, and are confounders acknowledged? (4) Is the uncertainty range from ensemble or single-model? These are the four questions the Statistician would apply to any advocacy work using counterfactual modeling.
