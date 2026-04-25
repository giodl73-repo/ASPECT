---
work: 0023-nyt-512-paths
stage: panel
rubric_version: v1.9
created: 2026-04-23
gate: PASS
cluster_o: CONFIRMED_AND_EXTENDED
---

# Panel SUMMARY — 0023 NYT "512 Paths to the White House"

## Score Table

| Dimension | Rosling (30%) | Tufte (25%) | Bertin (20%) | Audience (15%) | Nightingale (10%) | Weighted |
|-----------|--------------|------------|-------------|----------------|------------------|---------|
| School Fidelity /20 | 17 | 16 | 16 | — | 16 | 16.3 |
| Data/Story Integrity /20 | 17 | 16 | 16 | — | 16 | 16.3 |
| Legibility /15 | 13 | 12 | 12 | 12 | 12 | 12.3 |
| Visual Economy /15 | 13 | 13 | 13 | 12 | 13 | 12.9 |
| Resonance /15 | 14 | 13 | 13 | 13 | 13 | 13.3 |
| Craft /15 | 14 | 14 | 14 | — | 14 | 14.0 |
| **Total /100** | **88** | **84** | **84** | — | **84** | **85.1** |

*Audience lens scores Legibility, Visual Economy, Resonance only.*

**Weighted aggregate: 85.1 / 100**
**Gate: PASS**

---

## Key Agreements

**Interaction-as-variable is a genuine extension of the dynamic grammar.** All five reviewers agree that the 512 Paths graphic is in the same school family as Gapminder (work 0021) and that the grammar generalizes. Rosling (Innovation #184) names the distinction: pre-computed dynamics (Gapminder) vs. viewer-authored dynamics (512 Paths). Bertin (Innovation #187) names the visual variable extension: dynamic state (opacity/weight encoding path-consistency with viewer assignments) as a new visual variable type not in the static framework.

**Interaction outperforms small multiples for navigational questions.** Tufte explicitly revises his general preference for small multiples (Innovation #186): small multiples are optimal for comparison; interaction is optimal for viewer-personalized navigation. The electoral math question is navigational. This is a significant concession from Tufte.

**The possibility-vs.-probability gap is the main integrity issue.** Tufte (Amendment L: state ordering undeclared), Bertin (Amendment L: state ordering), and Nightingale (Innovation #189: possibility-space vs. probability-space undeclared) all identify the same family of variable-selection issues: the tree shows paths without showing their relative probability. This is the one consistently flagged integrity gap.

---

## Key Tensions

**Rosling vs. Tufte on the initial-state density:**
Rosling accepts the initial full-tree density as the price of the viewer-authored dynamic grammar — the viewer must see the full space before they begin pruning it. Tufte finds the initial state marginally overwhelming. The panel does not resolve this; the trade-off between comprehension of the full space and initial display density is a real design tension in viewer-authored dynamic visualizations.

**Audience on affordance discovery:**
The Audience lens flags (Innovation #188) that interaction affordance is a legibility prerequisite — the viewer must discover that the tree is clickable before they can use it. This is a legibility sub-criterion the rubric does not currently include. The panel agrees this is a real gap and flags it for the Cluster O amendment.

---

## Innovations Flagged (#184–#190)

| # | Work:Reviewer | Technique Name | Rubric Anchor | Status |
|---|--------------|----------------|---------------|--------|
| 184 | 0023:rosling | Viewer-authored vs. pre-computed dynamic visualization | School Fidelity / Legibility | Cluster O confirmation and extension |
| 185 | 0023:tufte | Gestalt legibility of combinatorial spaces | Legibility | New |
| 186 | 0023:tufte | Interaction vs. small multiples boundary condition | School Fidelity / Legibility | Cluster O confirmation |
| 187 | 0023:bertin | Dynamic state as visual variable | School Fidelity / Visual Economy | Cluster O confirmation |
| 188 | 0023:audience | Interaction affordance as legibility prerequisite | Legibility (Step 0) | New |
| 189 | 0023:nightingale | Possibility-space vs. probability-space in electoral visualization | Data/Story Integrity (Step A) | New |
| 190 | 0023:rosling | Dynamic variable as generalized grammar category | School Fidelity (Type B extension) | Cluster O extension — amendment trigger |

---

## CLUSTER O — CONFIRMED AND EXTENDED

**Previous status:** Forming — one work (0021 Gapminder), proposing "time-as-animation" as the key dynamic variable

**Current status after work 0023:** CONFIRMED AND EXTENDED

The cluster generalizes: the dynamic-statistical-graphics grammar extends beyond time-as-animation to encompass **dynamic variable** as a broader grammar category. Both time (Gapminder) and viewer interaction (512 Paths) are dynamic variables — dimensions of the data that change as the viewer engages.

**Proposed Cluster O amendment (to be added to Legibility and School Fidelity in v1.11):**

> **Dynamic variable recognition (Cluster O amendment):**
> Some works encode a primary variable that changes dynamically as the viewer engages — either through animation (time-as-variable) or through interaction (viewer-choice-as-variable). For these works:
> - Identify the dynamic variable and its mode (time-driven / interaction-driven)
> - In Legibility: add `[static: X/15]` notation parallel to `[contemporary: X/15]` — the legibility score with the dynamic variable removed; for interaction-driven works, also add affordance clarity as a sub-criterion
> - In School Fidelity: assess whether the dynamic variable is the right encoding mode for the argument (pre-computed for comparative arguments; viewer-authored for navigational arguments)

**The Cluster O amendment threshold is met: 2 works, multiple reviewer confirmations, coherent cluster.**

---

## What This Work Reveals

**Interaction-as-dynamic-variable is not a special case of animation.** Rosling's Innovation #184 distinguishes them clearly: pre-computed dynamics and viewer-authored dynamics have different legibility standards, different resonance modes, and different school requirements. The rubric should treat them as related but distinct sub-types within the dynamic visualization grammar.

**The navigational use case is underserved by static visualization.** Tufte's concession (Innovation #186) is significant: small multiples — the gold standard for showing comparison across scenarios — cannot personalize to the viewer's scenario. For questions with a navigational structure (given my prior, what follows?), interaction is the appropriate grammar.

**The "wonder" resonance type extends to civic engagement.** Rosling defined wonder as "the experience of having a false assumption shaken by data." In 512 Paths, the wonder is different: "the experience of understanding a complex system by acting on it." This is wonder-through-agency rather than wonder-through-correction. Both produce the viewer-leaving-knowing-something-true result Rosling considers the test of resonance.
