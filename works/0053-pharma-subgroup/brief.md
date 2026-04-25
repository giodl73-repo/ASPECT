---
work: 0053-pharma-subgroup
title: "Pharmaceutical Subgroup Analysis Forest Plot (Drug X / TRIAL-X)"
historical_author: Claude (original design — realistic type case)
period: contemporary
school: statistical-graphics (Type A)
cluster: X — advocacy-as-coercion
coercion_mechanism: analytical_frame_selection
rubric_version: v2.2
---

# Brief — 0053 Pharmaceutical Subgroup Analysis Forest Plot

## Design Origin

This is an original design of a realistic type case, not a specific real pharmaceutical trial. The design represents a class of visualization practice documented in the peer-reviewed literature on selective reporting in clinical trials (see: Rothwell 2005, NEJM; Pocock and Collier 2011, NEJM; Brookes et al. 2004, BMJ). The type case is realistic and the mechanism is well-documented.

## The Trial

**Drug X** was studied for **Condition Y** in a randomized controlled trial (TRIAL-X). The trial was pre-registered with a primary endpoint: reduction in major adverse cardiovascular events (MACE) at 12 months.

**Primary outcome result:**
- Hazard ratio: 0.94
- 95% CI: [0.85, 1.04]
- p-value: 0.23
- Conclusion: Not statistically significant. The trial did not demonstrate efficacy on its pre-registered primary endpoint.

**Post-hoc subgroup analysis:**
- Subgroup: patients aged >65
- Hazard ratio: 0.82
- 95% CI: [0.70, 0.97]
- p-value: 0.02
- Conclusion: Statistically significant in this subgroup.

## The Marketing Visualization

The marketing communication — presented to physicians at conferences and in journal supplements — shows a forest plot. A forest plot is a legitimate statistical graphic for displaying multiple effect estimates simultaneously, commonly used in meta-analyses and subgroup analyses.

The forest plot in this case:
- Shows 8–12 subgroup lines (age, sex, race, comorbidity status, baseline severity, etc.)
- Highlights the >65 age subgroup line in a distinct color or with an annotation marker
- Shows the overall trial result as one line among many in the forest plot, not as the primary finding
- Carries accompanying text: "Drug X demonstrated significant benefit in patients over 65 in the TRIAL-X study."

## The Analytical Frame Selection Mechanism

The coercion mechanism is analytical frame selection: choosing which analysis to foreground not based on the pre-registered primary outcome but based on which analysis favors the desired conclusion.

Key features:
- The primary endpoint IS shown — it is a line in the forest plot
- The subgroup finding IS real — the statistical test is legitimate
- No individual data point is falsified
- The coercion is entirely in which finding is foregrounded and how the display is framed
- Post-hoc subgroup analyses have ~1/20 probability of false positive at p<0.05 by chance alone if 20 subgroups are tested

This is the most sophisticated coercion mechanism in the cluster: the visualization is technically defensible at every point, yet it produces a systematically false impression of the trial's result.
