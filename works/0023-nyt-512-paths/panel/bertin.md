---
work: 0023-nyt-512-paths
reviewer: bertin
weight: 0.20
rubric_version: v1.9
---

# Bertin Review — "512 Paths to the White House"

## Opening

Interactive diagrams introduce a variable I have not formally addressed in my visual variables framework: time-of-interaction, or more precisely, viewer-state as a dynamic visual property. The seven static variables (position, size, shape, value, hue, orientation, texture) describe the properties of marks as they appear on a surface. Interactive diagrams add a new dimension: the mark's properties as a function of viewer action. This is a new encoding grammar that my framework does not fully cover.

Let me audit what I can audit and note the gap.

## Static Variable Audit (initial state)

**Position (horizontal) → Tree level = swing state:**
Correct use. Each level in the tree corresponds to a distinct state in the decision sequence. The horizontal position encodes ordinal sequence (which state is decided at this level).

**Position (vertical) → Path branching:**
This is a structural variable, not a data variable. The vertical position within a tree level encodes ancestry — which paths share a common ancestor — not an independent data property. This is a topology encoding, analogous to Beck's transit diagram: vertical position encodes relational structure, not geographic or quantitative data. Correct use.

**Color (hue) → Outcome at terminal nodes:**
Blue = Obama; Red = Romney. Correct use of hue for nominal categorical data (two outcomes). Cultural convention (political color coding) reinforces the encoding. The use is appropriate and redundant with position (which side of the tree the path terminates on) — productive redundancy.

**Opacity and line weight → Path status (active vs. pruned):**
These are the dynamic variables — the ones that change with interaction. In the static visual variables framework, opacity is related to value (lightness), and line weight is related to size. Both are used here not to encode data but to encode dynamic state: is this path currently possible given viewer assignments? This is a new use: the variable encodes the visualization's current interactive state, not a property of the underlying data.

Innovation #187: **Dynamic state as visual variable** — in interactive visualizations, marks have a new dimension of encoding: their current interactive state (active, suppressed, highlighted, etc.). This state changes with viewer input and is not a property of the underlying data. In the 512 Paths graphic, opacity and line weight encode "path currently consistent with viewer assignments" — a dynamic state variable that has no equivalent in static visual variables theory. This extends the visual variables grammar to interactive contexts.

## The Ordering Argument

The tree's root-to-leaf ordering (Florida first, Wisconsin last) encodes an editorial judgment about swing state importance. In Bertin's grammar, the ordering of a categorical variable is a design choice that should be matched to the analytical purpose: order by value for ranked comparison; order by similarity for clustering; order by time for temporal sequences.

Here, the ordering is by estimated electoral importance — a latent quantitative variable (expected electoral college impact) that is not shown in the visualization but governs the tree's structure. This is an undeclared encoding: the structure of the tree is determined by a variable (state importance) that is not visually represented.

**Amendment L applies:** Key variable (state importance ranking) encoded structurally without disclosure. Dock −1.

## Scoring

**School Fidelity (Type C): 16/20**

The statistical and narrative schools are both active and mutually reinforcing. The encoding grammar is applied correctly for the static variables. The dynamic state variable is used consistently (opacity/weight for active/pruned). Dock for the undeclared ordering variable.

**Data/Story Integrity: 16/20**

Electoral math correct. The tree is complete. Amendment L: state importance ordering undeclared (−1). Equal path probability implicit but undeclared (−1). Score: 16.

**Legibility: 12/15**

The initial state is dense. The interaction dramatically improves legibility. Context-dependent: high legibility for interactive users; moderate for passive readers. Appropriate for a newspaper digital format.

**Visual Economy: 13/15**

The dynamic pruning is an elegant economy mechanism: paths that become irrelevant are visually suppressed rather than removed, preserving the tree's structure while reducing its visual weight. This is high economy — the marks remain on the screen but do not compete with the active paths. Minor dock for the full-tree density in the initial state.

**Resonance: 13/15**

The interaction generates a distinctive resonance: viewer as active participant in the outcome's determination. The feeling of electoral paths narrowing as states are assigned is experientially compelling.

**Craft: 14/15**

Clean, consistent, smooth. A technically excellent implementation of a complex interactive system.

## Summary

Bertin total: **84/100**

The static variables are correctly deployed. The dynamic state variable (opacity/weight as path-status encoding) is a genuine extension of the visual variables grammar that my framework needs to address. Cluster O should expand to encompass this.
