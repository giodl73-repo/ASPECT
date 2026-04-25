---
work: 0035-covid-counterfactual
stage: design
rubric_version: v2.0
created: 2026-04-23
---

# Design Notes — 0035 COVID-19 Deaths and the Masking Counterfactual

## Chart Structure

**Form**: Two-line area chart (temporal, accumulating).

**X-axis**: Time, March 2020 through December 2021. Monthly tick marks. Key policy events annotated with vertical reference lines.

**Y-axis**: Cumulative US COVID-19 deaths (thousands). Starts at 0. Does not truncate baseline.

**Primary line (actual deaths)**: Solid, dark red (#8B0000). Sourced from CDC COVID Data Tracker weekly surveillance data, aggregated to biweekly cumulative totals.

**Counterfactual line (modeled at 85% compliance)**: Dashed, muted amber (#B8860B). Ensemble mean of three peer-reviewed models:
- Stutt et al. (2020), Royal Society Open Science — baseline mask efficacy at population scale
- Howard et al. (2021), Lancet — community masking effectiveness synthesis
- CDC ensemble model estimates (internal, 2021)
Uncertainty band shown as translucent amber shading (±1 SD of ensemble spread).

**Gap fill**: Translucent red (#DC143C at 30% opacity) between the two lines. The gap grows as time passes and the two trajectories diverge.

**Terminal bracket**: A bracket at December 2021 with label "130,000–180,000 preventable deaths (modeled at 85% compliance, April 2020 onward)."

## Policy Event Annotations

Five vertical reference lines with small labels:
1. April 3, 2020 — CDC first mask guidance
2. May 2020 — widespread state reopenings begin
3. December 2020 — first vaccine authorizations
4. March 2021 — mask guidance relaxed in many states
5. July 2021 — Delta surge begins

Annotations are intentionally sparse — they provide context without crowding the visual argument.

## Integrity Decisions

The counterfactual gap is labeled with a range (not a point estimate) to represent modeling uncertainty. The ensemble modeling basis is declared in the figure note. The 85% compliance scenario is named as modeled — it is not presented as a proven outcome but as a well-supported projection. The range (130,000–180,000) is the conservative envelope of the three models.

## Comparison to Work 0029

Work 0029 used a split bar chart (static comparison of two scenarios). Work 0035 uses a temporal area fill (dynamic comparison of two trajectories). The structural argument is the same: one encoding is what is; the other is what could be at achievable intervention; the gap is the cost of inaction. The generalization from bar to area fill is the Cluster T confirmation target.
