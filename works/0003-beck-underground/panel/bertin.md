---
work: 0003-beck-underground
stage: panel
reviewer: bertin
rubric_version: v1.2
created: 2026-04-23
---

# Bertin — Panel Review

*School type: B (Founder). Scored on founding grammar coherence.*

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| School Fidelity (Type B) | 17 | 20 |
| Data/Story Integrity | 17 | 20 |
| Legibility | 14 | 15 |
| Visual Economy | 14 | 15 |
| Resonance | 12 | 15 |
| Craft | 14 | 15 |
| **Total** | **88** | **100** |

## Review

I will conduct my standard visual variable audit, but I need to note at the outset that this map presents a genuine challenge to my grammar. Beck is using my variables correctly — and in doing so, he reveals a limitation in the grammar itself.

**Visual variable audit:**

*Line identity → color hue:* Hue is selective and associative; it groups marks into categories and allows the viewer to perceive category membership immediately. Line identity is a nominal categorical variable: lines have names, not ranks or quantities. Hue for nominal data is the correct pairing by my grammar. The execution is excellent: each line has one color; the colors are mutually distinct; saturation is high enough for small-scale legibility. This is the most correct variable pairing in the map.

*Station existence → position + tick mark:* Position is the most powerful retinal variable — the eye reads it first and most reliably. Assigning station position to a topological rather than geographic coordinate system does not violate my grammar; my grammar specifies what the variable *can* encode, not what coordinate system it must use. The tick mark is shape — a selective variable appropriate for marking category membership (is this location a station? yes/no). Correct.

*Transfer possibility → shape (ring vs. tick):* Interchange stations receive a distinct shape — the ring or diamond — that differs from the simple tick mark of non-interchange stations. Shape is selective: the viewer can immediately identify all interchange stations without reading labels. Correct usage. Highly effective.

*Station name → text label:* Text is not one of my seven variables. It is a symbolic encoding requiring literacy and language. The map uses text for station names — which is necessary, since there is no visual variable that could encode 100 distinct proper names. Text where necessary; visual variables where possible. This is correct design discipline.

**The problem with the grammar:**

Here is what the audit reveals: Beck uses color (hue) as the *primary navigation variable*, not as a *secondary classification variable*. In my grammar and in most statistical graphics, position is primary and color is secondary. The viewer finds the data by position and then reads additional information by color.

In Beck's map, position has been deliberately degraded — it encodes topological relationship, not geographic location, and the topology is not intuitive to someone who has not memorized the map. So the viewer *cannot* navigate by position alone; they navigate by *color*. They follow the red line; they follow the blue line. They are not reading a position; they are tracking a color through the network.

This is a usage of color that my grammar did not anticipate. In my framework, hue is selective — the viewer can group by it — but it is not ordered and not quantitative. I did not consider the case where hue becomes *directional* — where the viewer follows a specific hue through the diagram as a path, not just uses it to group marks. This is a new use of the hue variable that the grammar does not name.

**On School Fidelity (Type B):**

The founding grammar is internally coherent and learnable from the 1933 edition. Score 17 rather than 18 or 19 for the Thames: the Thames is a geographic encoding embedded in a topological diagram. This creates a visual grammar inconsistency that the grammar does not resolve. The rule "topology over geography" has one exception that is not derived from the rule. Score 17.

**On Data/Story Integrity:**

Step A: all network connections are correctly represented. No false connections; no suppressed connections. Step B: the variable-scale encoding (central expansion) is an undeclared accuracy tradeoff, as Tufte notes. I agree; dock one point. Step C: the map does not imply causal relationships. No adjustment.

Score 17 — the network data is correct; the undeclared variable scale is a mild Step B concern.

**On Legibility:**

Fourteen. The color-as-navigation-primary works extremely well for the informed user following a known line. It is somewhat fragile for the novice: the novice must first identify which line they need (by name, then by color) before they can navigate. The map offers no help for this first step beyond the key. Once the user knows their line color, navigation is fast. The initial "find your line" step is a legibility cost for novices.

**On Visual Economy:**

Fourteen rather than fifteen. My one concern: the interchange ring mark is not visually distinct enough from the terminal station marks in all cases. A viewer looking at Hammersmith (where District and Piccadilly lines terminate and interchange) may not immediately resolve whether the mark indicates interchange, terminus, or both. The grammar of marks is almost complete; it frays at edge cases.

**On Resonance:**

I agree with Tufte: the primary resonance type is domain-gated — the network's shape is immediate and satisfying to someone who knows it; opaque to someone who does not. I am less interested in resonance than my colleagues. Score 12 — the work achieves something, but it is a functional satisfaction rather than an aesthetic or advocacy effect.

**On Craft:**

The King's Cross cluster is the one craft failure. The angle discipline is maintained throughout — I verified: no non-constrained angles. The color discrimination is sufficient for the scale. Score 14.

## Innovations Flagged

1. **Hue as navigational path variable** — using color hue not as a grouping variable (identify all marks belonging to category X) but as a tracking variable (follow this hue through a network, ignoring all other hues). My grammar identifies hue as selective and associative but does not account for the directed-tracking use. This is a new visual variable behavior: the viewer does not just perceive that marks share a color, they *move through the diagram by following a color*. *Rubric anchor: School Fidelity (Type B) / Data/Story Integrity. Implication: the visual variables grammar in the rubric should recognize directed-tracking as a use of hue distinct from grouping, and evaluate whether the design supports the tracking behavior (sufficient saturation, no hue collisions, consistent stroke width).*

2. **Variable density as a structural property** — the central expansion creates a map with non-uniform density: more visual information per unit area in the center than the periphery. This is not chartjunk (the extra density is data); it is not economy failure (the periphery is not empty). It is a structural property of the encoding design that my grammar does not have a name for. Some map forms are inherently variable-density; the design choice to use such a form carries implications for cross-region legibility comparisons that the rubric does not assess. *Rubric anchor: Visual Economy. Implication: Visual Economy should distinguish uniform-density designs from variable-density designs and score the variable-density form on whether its density distribution is appropriate to its data distribution — not simply whether marks are "earning their place."*
