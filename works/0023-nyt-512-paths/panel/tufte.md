---
work: 0023-nyt-512-paths
reviewer: tufte
weight: 0.25
rubric_version: v1.9
---

# Tufte Review — "512 Paths to the White House"

## Opening

I should have thought of this. I didn't. The small multiples instinct in me says: show all 512 scenarios at once, each as a small fixed panel, let the viewer compare. The 512 Paths design says: show all 512 simultaneously as a tree, let the viewer prune. Both are strategies for dealing with a large combinatorial space. The tree strategy is, in this case, better — and I say that reluctantly.

## Legibility of 512 Simultaneous Paths

The initial state of the visualization is visually dense. 512 branching paths, displayed simultaneously, create a mass of thin lines at the right edge of the display. A viewer encountering the tree before interaction may legitimately find it overwhelming. This is the primary legibility risk.

However, I want to distinguish two legibility modes here. The tree in its initial state is not legible in the sense that a viewer can trace individual paths — they cannot. But it IS legible in the sense that a viewer can immediately see the shape of the possibility space: most paths lead to one outcome; a few are critical junctures. The gestalt is legible even when the detail is not.

Innovation #185: **Gestalt legibility of combinatorial spaces** — in visualizations that display large numbers of paths or scenarios simultaneously, detail-level legibility (can the viewer trace any individual path?) and gestalt-level legibility (can the viewer see the shape of the overall possibility space?) are different and separable. Designs that achieve gestalt legibility at the expense of detail legibility may be appropriate when the argument is about the shape of the space (most paths go here), not about individual paths.

The 512 Paths tree achieves gestalt legibility before interaction and detail legibility after. This is a defensible design choice for the editorial context.

## The Interaction vs. Small Multiples Question

My usual preference is for small multiples over animation. I argued this explicitly in work 0021 (Gapminder). The same argument applies here: could a set of small multiples — perhaps 9 panels, each showing the tree for a different key-state assignment — replace the interaction?

The answer is no, for a specific reason that changes my view: the argument of 512 Paths is not comparative (A vs. B across scenarios) but navigational (given my current assignments, what remains possible?). Small multiples are optimal for comparison; interaction is optimal for navigation. The electoral college question is a navigation question — the viewer brings their own scenario (who will win Florida?) and wants to know what remains possible given their belief. Small multiples cannot personalize to the viewer's prior.

I revise the general rule: **small multiples are better than animation for comparative arguments; interaction is better than small multiples for navigational arguments where the viewer's own input defines the relevant scenario.**

Innovation #186: **Interaction vs. small multiples boundary condition** — extends the work 0021 finding (animation vs. small multiples boundary). Interaction outperforms small multiples when the argument requires viewer-personalized navigation through a scenario space. Small multiples outperform interaction when the argument is comparative across pre-defined scenarios.

## Variable Selection Disclosure (Amendment L)

The state ordering in the tree (Florida first, Wisconsin last) embeds an editorial judgment: Florida matters most; Wisconsin matters least. This ordering is not random — it reflects the designers' assessment of swing state importance. But it is not declared as an editorial judgment; it appears as the tree's natural structure.

A viewer who disagrees with this ordering (say, who believes Wisconsin is the critical state in 2012) will have a different experience of the tree: they will want to click Wisconsin first, but Wisconsin is near the terminal branches. The design mildly imposes the designers' scenario hierarchy on the viewer's exploration.

This is a Step A variable-selection issue: the variable "state importance ordering" is encoded without declaration. Dock −1 under Amendment L.

## Scoring

**School Fidelity (Type C): 16/20**

The synthesis of dynamic-statistical-graphics and narrative-visualization is well-executed. The tree is statistically correct; the narrative structure is clear. I dock for the undeclared state-ordering editorial judgment.

**Data/Story Integrity: 16/20**

Electoral math correct. All paths shown. The paths are equiprobable in the tree (Amendment L: the relative probability of each state outcome, per polls, is not shown). This simplification is defensible but undeclared. Dock −1.

**Legibility: 12/15**

Gestalt legibility: high. Detail legibility before interaction: low. Detail legibility after interaction: high. The interaction-dependence of legibility is unusual and the design does not fully resolve it — a viewer who does not click may leave confused. Dock for the cold-encounter legibility gap.

**Visual Economy: 13/15**

The initial full-tree state has more simultaneous paths than are useful before interaction. The pruning mechanism is elegant; the initial display is slightly overwhelming. The counter and bar chart at the right edge are well-integrated.

**Resonance: 13/15**

The interaction produces genuine engagement. A viewer who assigns all 9 states has authored the visualization's outcome. This is a form of resonance I did not anticipate — viewer-as-author resonance. The Gapminder viewer watches; the 512 Paths viewer builds. Different experience, comparable resonance quality.

**Craft: 14/15**

Excellent technical execution. Smooth interaction, clean layout, consistent color coding, accurate counter updates.

## Summary

Tufte total: **84/100**

Better than I expected. The interaction grammar solves a legibility problem I thought only small multiples could solve. I retain my preference for small multiples in comparative contexts; I concede the navigation context to interaction.
