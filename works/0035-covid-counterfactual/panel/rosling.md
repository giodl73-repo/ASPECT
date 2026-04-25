---
work: 0035-covid-counterfactual
reviewer: rosling
weight: 0.20
rubric_version: v2.0
---

# Rosling — 0035 COVID-19 Deaths and the Masking Counterfactual

## School Fidelity /20 → 17

Time is data. This work puts time on the X-axis and lets the divergence between two trajectories tell the story, which is exactly what a temporal data visualization should do. The static bar chart in work 0029 told you the gap existed; this work shows you the gap growing. The growth IS the argument. The form is more natural for temporally-structured data than the static comparison — I would have designed work 0029 this way if I had been involved.

The synthesis of statistical-graphics and advocacy-visualization is correct and declared. The annotation layer provides the causal narrative that pure statistical-graphics would omit, and it does so without overwhelming the visual structure. This is the right balance: statistical rigor as the scaffold, advocacy narrative as the layer above it.

## Integrity /20 → 16

I will say what I always say: show me the path. The design shows the cumulative trajectory from March 2020 to December 2021, which is good. But I want to know more about the slope changes. The annotated policy events help — I can see where the actual deaths line accelerated (Delta surge, annotation 5) and where it would have decelerated differently under 85% masking. But the monthly data granularity should be visible. Are there biweekly data points, or is the line smoothed? If smoothed, declare the smoothing method.

The counterfactual modeling uncertainty is honestly declared (range, uncertainty band, three named models). The 85% compliance assumption is named. I find no overreach on the causal claim — the work is careful to frame masking as the modeled intervention, not the guaranteed solution.

One question I would press: what is the counterfactual's Delta variant assumption? The Delta surge (July 2021 onward) dramatically changed transmission dynamics. Does the counterfactual model incorporate Delta's higher transmissibility? If masking at 85% compliance was modeled using pre-Delta assumptions, the counterfactual gap from July 2021 onward may be overstated. This should be declared.

## Legibility /15 → 13

The temporal structure is legible to the intended audience — policymakers, public health advocates, educated general readers. The two-line area fill is a familiar form; it does not require statistical training to grasp. The annotation layer provides the causal narrative at precisely the moments when the viewer will want explanation.

My one legibility note: the uncertainty band on the counterfactual line may be visually confusing for viewers unfamiliar with confidence intervals. Some will read it as "the actual deaths could have been in this range" rather than "the model's estimate of the counterfactual is in this range." A small note — "uncertainty reflects ensemble model spread, not actual deaths range" — would resolve this.

## Execution /15 → 13

The design is economical. Two lines, gap fill, uncertainty band, five annotations, terminal bracket. No decorative elements. The color choices are well-judged. The translucent gap fill creates visual weight without obscuring the line data.

One economy note: the annotation text should be kept to four or five words per event ("CDC mask guidance" not "CDC issues first guidance on mask use in public settings"). The temporal structure is already doing narrative work; the annotations should be labels, not sentences.

## Resonance /15 → 13

The temporal growth of the counterfactual gap is the strongest resonance mechanism in the work. The gap does not appear at once — it accumulates month by month, through the Delta surge, through the vaccination rollout that came too late for too many. A viewer who follows the two lines from March 2020 to December 2021 experiences the temporal accumulation of preventable loss. That is the work's most powerful argument, and the form achieves it.

My secondary resonance note: the work could achieve more wonder if it included a brief comparison panel showing what the trajectory looked like in countries that achieved 85%+ mask compliance (South Korea, Taiwan, Japan). This would make the counterfactual empirical rather than purely modeled — "not a model; this is what actually happened elsewhere." I would add a small inset for a future version.

## Purpose /15 → 13

Advocacy purpose with 800,000 deaths as subject. The form is proportionate to the stakes. The gap structure names the cost of inaction at a scale that decision-makers can absorb and advocates can deploy. Purpose is well served.

## My Total: 85/100

The counterfactual area fill is the right form for temporally-structured data. The main revisions are the Delta variant assumption disclosure and the monthly granularity declaration. The Cluster T confirmation is solid.

## Innovation Flagged

**#236 — Empirical counterfactual as revision target**: the modeled counterfactual in this work (85% compliance projection) could be partially validated by reference to countries that achieved high mask compliance. A companion panel showing South Korea, Taiwan, or Japan's COVID-19 death trajectories alongside the US actual trajectory would transform part of the counterfactual from modeled to empirical — "this is what actually happened when a similar population adopted high-compliance masking." This is a design innovation: using empirical international comparison to partially validate a domestic counterfactual model. The technique is not in the rubric's counterfactual vocabulary.
