---
work: 0023-nyt-512-paths
reviewer: nightingale
weight: 0.10
rubric_version: v1.9
---

# Nightingale Review — "512 Paths to the White House"

## Opening

I am always interested in the question of who a visualization is actually for and what it wants them to do. The 512 Paths graphic is for voters trying to understand electoral math. What it wants them to do is — what, exactly? It does not tell them who to vote for. It does not tell them which states are most likely to swing. It tells them what the space of possibilities looks like. This is a different kind of advocacy than I am used to.

## Does the Tool Serve the Audience?

The audience is voters trying to understand the 2012 US presidential election on Election Day. Two questions a voter might bring to this tool:

1. What are the possible paths to victory for each candidate?
2. Is my candidate likely to win?

The tool answers question 1 very well. It maps the complete possibility space. The interaction mechanism (assign states, watch paths narrow) is the right grammar for navigating a combinatorial space. A voter who wants to understand "what happens if Obama loses Florida?" gets a clear, immediate answer.

The tool does not answer question 2. The tree shows all paths as equally possible; it does not show which paths are more or less probable given the polling data. For a voter who wants to know whether their candidate is likely to win, the tool is informative but not decisive.

Innovation #189: **Possibility-space vs. probability-space in electoral visualization** — showing all possible outcomes is different from showing likely outcomes. Possibility-space visualizations (this is 512 Paths) answer "what could happen?" Probability-space visualizations (polling aggregation models like Nate Silver's FiveThirtyEight model, also active in 2012) answer "what is likely to happen?" Neither is wrong; they serve different audience needs. A visualization that presents itself in the context of an election should declare which it is doing.

## Advocacy Assessment (Type III Resonance)

Is this an advocacy visualization? It presents no explicit argument; it makes no recommendation. But it is published on Election Day by a major newspaper to help voters understand the election. In advocacy-visualization terms, the goal is civic comprehension, not action toward a specific outcome.

I score this as Type II (emergent-data) resonance rather than Type III (advocacy-efficacy): the resonance comes from the viewer's experience of the data (the narrowing tree, the electoral math becoming concrete) rather than from a directed argument for a specific action. The tool is in service of civic comprehension; the resonance is the experience of understanding.

## Narration Mode

Context specification: `narration_mode: standalone`. The graphic runs in a browser with no accompanying narrator. The text header and state labels are all the instruction provided. This is consistent with the standalone mode in v1.8: legibility is scored against what the viewer can understand without accompanying narration. The interactive tutorial (discover the interaction, assign states, read the tree) is the user's own experience.

A narrated version — someone explaining the tool in a video while demonstrating interaction — would score higher for initial legibility. The standalone mode imposes the affordance-discovery burden on the viewer.

## Scoring

**School Fidelity (Type C): 16/20**

The synthesis is coherent: statistical display + narrative navigation. Well-executed.

**Data/Story Integrity: 16/20**

Correct electoral math. The possibility-vs.-probability distinction is the main gap (undeclared simplification: all paths shown as equally possible when they are not equally probable). Dock −2 under Amendment L (key variable excluded without declaration: probability weights for each state outcome).

**Legibility: 12/15**

Context: news-engagement (Election Day, general public). Legible once interaction begins; moderate at first encounter. Narration mode: standalone; the affordance discovery burden reduces initial legibility.

**Visual Economy: 13/15**

Efficient dynamic encoding. Initial density is the one visible excess.

**Resonance: 13/15**

Civic comprehension resonance: the viewer leaves having genuinely understood the electoral math better than before. This is a service to democratic participation — the kind of advocacy I can endorse.

**Craft: 14/15**

Excellent execution.

## Summary

Nightingale total: **84/100**

The tool serves the voter's civic comprehension need well. It should declare whether it is showing possibility-space or probability-space. The interaction grammar is appropriate and elegant.
