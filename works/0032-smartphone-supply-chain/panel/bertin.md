---
work: 0032-smartphone-supply-chain
reviewer: bertin
weight: 0.25
rubric_version: v1.11
---

# Bertin — 0032 Global Smartphone Supply Chain

## School Fidelity /20 → 17

Variable audit:
- Position (horizontal): supply chain stage — ordered (EXTRACTION → MARKET). Correct — ordered variable for ordered data.
- Position (vertical within column): material flow routing — layout-determined, not data-encoded. This is the most important grammar decision in the design: vertical position within a stage column is NOT an encoding — it is a layout optimization (minimize line crossings). The design correctly treats this as layout, not data.
- Color (hue of lines): material type — nominal. Correct. 6 colors for 6 materials is within the perceptual limit for hue distinction.
- Shape (circle): node type — consistent. Correct.
- Border color: stage identity — nominal. Correct.
- Fill color (red): chokepoint status — binary nominal. Correct — a binary distinction is the appropriate use of a fill color change.
- Number (inside node): material line count — quantitative. Small number inside a circle is a compact, effective encoding for a small integer.

The grammar decisions are sound. The explicit declaration that vertical position within stage columns is NOT geographic is the critical declaration — it distinguishes this work from 0013's ambiguous case. Position encodes stage (horizontal) and nothing else (vertical is layout). This is correct schematic cartography grammar.

One potential grammar issue: the stage-colored node borders (dark gray for EXTRACTION, blue for PROCESSING, etc.) add a border color encoding to the white-fill node. The node fill color (red for chokepoints, white otherwise) encodes chokepoint status. Two color encodings on the same element (border + fill) risk confusion. The design correctly uses different visual subregions of the circle (border vs. fill area) for the two encodings, which preserves separability.

## Data/Story Integrity /20 → 17

Supply chain topology is accurate. The chokepoint identification threshold (4+ of 6 material lines) should be declared as an analytical choice (see Beck's review). Source declarations are appropriate.

The representation of China's dominance in processing/components is accurate but should note the degree: the diagram shows China as the node through which most processing lines flow, but the specific market share numbers (90% of REE processing, 60% of silicon polysilicon) are available in the cited sources and should be accessible via annotation or supplementary note for the policy reader who needs the specific number.

## Legibility /15 → 13

For a policy audience in political presentation or contemplative study context: legible with the stage column structure established. The convergence pattern at China's processing nodes is the most complex area — multiple colored lines entering and leaving the same node. Color tracking (following a specific material through the network) is achievable by color.

The potential color confusion concern: six line colors is at the upper limit of reliable hue distinction. At small diagram sizes or poor display quality, some colors (especially cyan vs. blue-green, or purple vs. orange at low saturation) may become confused. Test the color palette under various rendering conditions.

## Visual Economy /15 → 13

The diagram is economical. The node number (material count inside circle) is a particularly efficient encoding — one small integer encodes the same information as counting the entering/exiting lines. The stage-colored borders add moderate visual weight at significant informational value. Chokepoint red fill is binary and clear.

## Resonance /15 → 14

The convergence pattern at the middle stages is a genuine Type IV gestalt moment — the supply chain vulnerability is visible as a topological shape before any node is labeled. The red chokepoints cluster visually in the center-left of the diagram (Processing and Components columns), creating a visual cluster that draws the eye before the mind decodes the labels.

## Craft /15 → 13

Six material lines with 0-45-90 degree discipline across five columns, managing crossings with bridge conventions, consistent node styling — demanding but achievable craft.

## My Total: 87/100

A well-designed supply chain schematic that correctly solves the geographic anchor problem through the stage-anchor innovation. The variable matching is sound; the topology is accurate; the convergence pattern is the gestalt argument correctly encoded.
