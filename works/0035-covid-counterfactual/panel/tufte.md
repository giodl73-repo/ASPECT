---
work: 0035-covid-counterfactual
reviewer: tufte
weight: 0.10
rubric_version: v2.0
---

# Tufte — 0035 COVID-19 Deaths and the Masking Counterfactual

## School Fidelity /20 → 17

The synthesis of statistical-graphics and advocacy-visualization is declared and resolved. The temporal area fill is the statistically correct form for time-series cumulative data with a counterfactual comparison. I would have designed it approximately this way. The annotation layer is restrained — five events, not fifteen. The policy annotation is the advocacy layer; the line and gap are the statistical layer. They do not compete.

The form choice generalizes the counterfactual gap technique from work 0029. Work 0029 used a split bar chart (static comparison); this work uses a temporal area fill (dynamic comparison). The structural argument is identical — one encoding is what is; the other is what could be at achievable intervention; the gap is the cost of inaction. The generalization works because the structural logic is independent of the specific chart form.

## Integrity /20 → 17

The data is honestly presented. Actual deaths: CDC-sourced, unambiguous. Counterfactual: ensemble of three models, uncertainty band, range declared. The 85% compliance assumption is named. The modeling basis is in the figure note.

My integrity note: the uncertainty band should be shown along the full counterfactual line, not only at the terminus. An uncertainty band that appears only at the end implies that the earlier counterfactual estimates are certain, which they are not. The band should grow as time passes — earlier months have less modeling uncertainty than later months (less time for behavioral model drift), so the band can narrow near the beginning and widen toward the end. But it should be present throughout.

## Legibility /15 → 14

The form is immediately legible. Two lines, a gap, five annotations, a terminal bracket. The red gap fill communicates "this is the space we are discussing" before any label is read. The terminal bracket with range lands the quantitative argument. The annotation text is appropriately sparse.

The uncertainty band legibility concern (does the viewer correctly read it as model uncertainty, not actual deaths range?) is real but minor. A one-line note in the figure caption resolves it.

## Execution /15 → 13

The design is economical. Every element earns its place: actual deaths line (primary data), counterfactual line (the comparison), gap fill (the argument's pointer), uncertainty band (integrity marker), five annotations (causal context), terminal bracket (the argument's conclusion). The translucent gap fill is the cleverest Economy decision — it creates visual weight while allowing the line data to remain visible beneath it.

Color economy: dark red for actual, muted amber for counterfactual, translucent red for gap. The color choices are emotionally appropriate and non-manipulative. The amber counterfactual line reads as "unrealized" rather than "aspirational" — a subtle tonal choice that prevents the counterfactual from feeling like propaganda.

## Resonance /15 → 13

Experiential resonance is secondary but present — the temporal growth of the gap creates a visceral sense of accumulating loss that a static comparison cannot achieve. Advocacy resonance is primary and fires correctly for the intended audience (policymakers, public health advocates, legislators). The counterfactual gap structure provides actionable information: here is the intervention, here is the threshold, here is the cost of not reaching it.

## Purpose /15 → 14

800,000 deaths. The Purpose dimension asks whether the form is proportionate to the stakes. The temporal area fill is proportionate: it names the cost of inaction at the appropriate scale, without melodrama and without false precision. The range (130,000–180,000) is more honest than a single point estimate and still communicates the scale of preventable loss. Purpose is fully served.

## My Total: 88/100

This is the strongest advocacy work in the project after work 0029. The counterfactual gap technique generalizes correctly — the structural logic is not specific to child mortality data or split bar form. The form is different; the argument is the same. Cluster T is confirmed.

## Innovation Flagged

**#238 — Counterfactual gap independence from chart form**: the counterfactual gap technique (work 0029 #215, #218) was first instantiated as a split bar chart. This work instantiates it as a temporal area fill. The structural argument — one encoding is what is; the other is what could be at achievable intervention; the gap is the cost — is chart-form independent. It applies to bars (static cross-section), areas (temporal trajectory), and potentially to other forms (maps showing geographic counterfactuals, network diagrams showing counterfactual connectivity). The technique is a structural argument type, not a specific chart form. This is the Cluster T confirmation: the counterfactual gap is a generalized visual argument, confirmed across works 0029 and 0035 in two different chart forms.
