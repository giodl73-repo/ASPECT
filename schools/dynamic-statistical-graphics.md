---
slug: dynamic-statistical-graphics
name: Dynamic Statistical Graphics (Animated / Interactive Visualization)
primary_personas: [rosling, tufte, bertin]
adjacent_schools: [statistical-graphics, narrative-visualization, information-architecture]
founded: 2006 (Rosling's TED presentation as canonical founding moment)
founder: Hans Rosling (animated presentation); concurrent with Ben Flocken (Trendalyzer software)
canonical_works: [0021-rosling-gapminder]
---

# Dynamic Statistical Graphics

## Origin and Claim

Founded by Hans Rosling's 2006 TED presentation using the Gapminder animated bubble chart. The school's founding claim: for data with a temporal dimension, animation (time as explicit encoding variable) reveals patterns that any static representation necessarily suppresses. A chart of income vs. life expectancy for 2006 shows a correlation; the same chart animated from 1800 to 2006 shows that the correlation has been changing, that convergence is real, that the "developing world" is not a fixed category — it is countries on a path. The motion is not a presentation aid; it is an encoding of the most important variable in the data.

This is the first school in the project where the primary encoding variable (time-as-motion) is inaccessible in static reproduction.

## Visual Grammar

### Primitives
- **Bubble**: a country, organization, or entity; position encodes two quantitative variables simultaneously; size encodes a third (typically population or absolute magnitude)
- **Motion path**: the trail a bubble traces through the space as time advances; reveals trajectory, not just current position
- **Animation frame**: one moment in time; a static chart shows one frame; dynamic visualization shows the sequence
- **Narrative annotation**: text or audio that accompanies specific frames, guiding attention to notable patterns, events, or transitions
- **Logarithmic axis**: Rosling's contribution — income distributed log-normally; log scale reveals true distribution; linear scale creates false "two-world" impression

### Compositional Rules
1. **Time as primary variable**: the animation variable (time) encodes the most important dimension of the data; if time is not the most important variable, animation is not justified — use small multiples instead
2. **Narrative accompanies animation**: animation alone is insufficient; a presenter or audio narration guides attention to what matters in each frame; the narration IS part of the encoding
3. **Clarity at each frame**: every individual frame must be legible as a static chart; the animation connects intelligible frames, not blurs them
4. **Logarithmic income axis**: for economic development data where income spans orders of magnitude, the log axis is a founding principle — it reveals the continuous distribution rather than the false poor/rich binary
5. **Motion path as history**: show where bubbles have been, not just where they are; the trail encodes the story of change
6. **Country identity across time**: a bubble must be consistently identifiable across frames; the viewer must be able to follow specific entities through the animation

### Encoding Conventions
- **Horizontal position**: one quantitative variable (Rosling: income/capita, log scale)
- **Vertical position**: second quantitative variable (Rosling: life expectancy)
- **Bubble size**: third quantitative variable (Rosling: population)
- **Bubble color**: nominal categorical (world region)
- **Time**: animation variable; one year per frame or continuous
- **Narration**: guides attention; highlights specific bubbles; contextualizes transitions

### Static Reproduction Problem
A dynamic visualization captured as a single frame loses its primary encoding variable (time). Static reproduction scores approximately 20–30 points lower than the live animated presentation. The rubric must score the work in its native context (animated presentation) and note the static-reproduction degradation in brackets.

### Forbidden Moves
- Animation of data where time is not the important variable (use small multiples instead)
- Frames that are too dense to read individually (the animation cannot rescue illegible frames)
- Narration that tells the viewer what to think rather than what to look at (presenter-as-conclusion vs. presenter-as-guide)
- Linear income axis for data spanning multiple orders of magnitude

## Canonical Exemplars (DEGAS project)
- 0021 Rosling Gapminder (84.5): the founding presentation; static reproduction estimated 65-70; Cluster O formed

## Grammar Declaration
Rosling declared the dynamic-statistical-graphics grammar in his TED presentations and in *Factfulness* (2018). The founding principles (time as variable, log income axis, narrative accompaniment) are explicitly stated. Under rubric J modifier: adjacent-documentation declaration (stated in accompanying publications and the presentation itself — a high-declaration case).

## Adjacent Schools
- **Statistical graphics**: static version of the same encoding; loses time but gains reproducibility and precision
- **Narrative visualization**: both use sequence to structure the viewer's experience; dynamic-statistical-graphics uses time animation; narrative visualization can use scroll, click, or narrator-pacing
- **Information architecture**: both represent change; information architecture represents system states; dynamic-statistical-graphics represents empirical change over time
