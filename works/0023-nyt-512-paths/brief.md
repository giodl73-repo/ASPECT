---
work: 0023-nyt-512-paths
slug: nyt-512-paths
type: canonical-import
school: dynamic-statistical-graphics + narrative-visualization (Type C synthesis)
created: 2026-04-23
rubric_version: v1.9
---

# Brief — "512 Paths to the White House" (New York Times, November 2012)

## Work Description

Published by the New York Times on November 5, 2012 (Election Day), created by Mike Bostock and Shan Carter. The interactive graphic presents all 512 possible electoral combinations arising from 9 contested swing states (Florida, Ohio, Virginia, Colorado, Iowa, Nevada, New Hampshire, North Carolina, Wisconsin) in the 2012 presidential election. Each combination maps to one of two outcomes: Obama wins or Romney wins the electoral vote count needed for the presidency (270+).

The visualization takes the form of a binary decision tree. Each node in the tree represents a swing state. Left branches = Democrat win; right branches = Republican win. The path from root to leaf traces one complete scenario. At the right edge, a bar chart shows the resulting Electoral College total for each path. A color band at each terminal node shows the winner (blue = Obama; red = Romney).

The viewer interacts by clicking individual swing state nodes to "assign" them to a candidate. As the viewer assigns states, the tree prunes: paths that are now impossible (given the assigned states) fade or collapse; paths that remain possible stay highlighted. A counter at the top shows the remaining possible paths and the current Obama/Romney electoral vote projections given the current assignments.

## The Dynamic Variable: Interaction

This work extends the dynamic-statistical-graphics school's grammar. Work 0021 (Rosling Gapminder) established time-as-animation as the primary dynamic variable: the chart changes on its own, driven by a time parameter, and the viewer watches. Work 0023 introduces a different dynamic mode: interaction-as-dynamic-variable. The viewer drives the change by clicking; the visualization responds to viewer choice rather than running on its own clock.

This is a Cluster O test case. Does the dynamic-statistical-graphics grammar (time as an explicit encoding variable) generalize to interaction as an equivalent dynamic variable? Or is interaction a fundamentally different cognitive mode that requires a different school classification?

## Panel Composition

| Reviewer | Weight | Rationale |
|----------|--------|-----------|
| Rosling | 30% | Does the interaction-as-variable grammar generalize from his time-as-animation founding act? |
| Tufte | 25% | Are 512 paths legible or overwhelming? Small multiples vs. interaction as alternative to animation |
| Bertin | 20% | Visual variable audit of an interactive diagram |
| Audience | 15% | Can a newspaper reader use this in real time on Election Day? |
| Nightingale | 10% | Does the tool serve the audience — voters trying to understand electoral math? |

## Key Questions

1. Does interaction-as-dynamic-variable generalize the Gapminder grammar? If yes, Cluster O expands from "time-as-animation" to "interaction-as-dynamic-variable" and encompasses both works. If no, Cluster O remains Rosling-specific and this work belongs to a different school.
2. Are 512 simultaneous paths legible, or does the decision tree exceed retinal capacity even with pruning?
3. What is the work's legibility context? A newspaper reader on Election Night is under time pressure but also has extended engagement — something between wayfinding and contemplative study.
4. Does the viewer feel like they understand the electoral math, or like they are operating a system they do not fully comprehend?
