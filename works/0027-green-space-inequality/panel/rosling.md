---
work: 0027-green-space-inequality
reviewer: rosling
weight: 0.25
rubric_version: v1.11
---

# Rosling — 0027 Green Space Inequality in 10 US Cities

## School Fidelity /20 → 16

The narrative structure is real and the progression is sound. I appreciate a work that commits to showing the viewer something they did not know — and this work does that. Most people know abstractly that wealthier neighborhoods have more green space; few have seen the specific percentage numbers across 10 cities and 4 income quartiles simultaneously. Section 2's bar chart does that work efficiently. The scroll-driven revelation is the right mechanism for this story.

My concern with school fidelity is Section 4 — the timeline. This is the section where I would expect the temporal dimension to fully come alive, and it is static. Six data points across 50 years for three neighborhoods. I understand this is a scroll-driven essay, not an animated Gapminder chart, but the timeline as specified (connected line chart with six points) is the most static possible way to show 50 years of canopy change. The path between the points — what happened year by year in the 1980s and 1990s — is invisible. The viewer sees "it went down" but not "how fast" or "whether it recovered briefly."

For a narrative visualization, the timeline's treatment of temporal change is undersized relative to the importance of the causal argument it is asked to carry.

## Data/Story Integrity /20 → 16

The income-canopy correlation is real and the data is sourced correctly. My question is about the comparison selection in Section 2. Ten cities were chosen — but which ten? The specification names Chicago, Houston, Phoenix, Atlanta, Detroit, Seattle, Baltimore, Denver, Memphis, New Orleans. These are not the 10 largest cities; they are a selection that includes several notorious cases of racial segregation and disinvestment (Chicago, Baltimore, Detroit, Memphis). Is this selection declared?

I am not saying the selection is dishonest — I believe the correlation between income quartile and canopy holds across virtually all US cities. But the choice to include Detroit and Memphis (large Black-plurality cities with documented disinvestment histories) and exclude cities like Minneapolis, Portland, or San Jose (which might show different patterns in their lowest quartiles) is an argumentative choice. Step A of the rubric asks whether variable selection is disclosed. Selection of which cities is the same kind of choice.

This does not undermine the work's argument — the correlation is real — but declaring the selection criterion would strengthen the work's integrity.

## Legibility /15 → 13

Section 2 is immediately legible: the bars are short for Q1, tall for Q4, in every city cluster. No instruction needed. Section 1 (satellite + heat overlay) is powerful but its encoding is only partially legible without the accompanying text — the viewer knows "orange = hot" but may not know this is a real temperature measurement. The text establishes this clearly.

The timeline in Section 4 is legible but shallow. Six points across 50 years, three lines, directly labeled — yes, this is readable. But the "aha" moment the specification promises — connecting the redlining annotations to the canopy decline — requires the viewer to read three different elements simultaneously (the line trend, the axis annotation, the text above the chart). This is achievable in contemplative study but requires sustained effort.

## Visual Economy /15 → 13

Section 5's prescription checklist is the best-designed element in the work. Large numbers, direct text, split bars showing Q1 vs. Q4 compliance — it is economical and actionable simultaneously. The illustration icons add some weight but also add warmth. Acceptable trade.

Section 3's dual-variable heat map is the most complex element. Two overlaid visual variables (value gradient + dot density) with three callout annotations is demanding. It earns its complexity because the spatial pattern is genuinely two-variable — you cannot show canopy and temperature independently and achieve the same argument. But the execution must be careful to avoid the two layers fighting each other visually.

## Resonance /15 → 13

The work produces wonder — or rather, it produces the specific kind of wonder I care about, which is "I knew this was bad, but I did not know it was this bad, and I did not know specifically how it happened." The sequence from Section 1 (emotional) to Section 4 (historical explanation) is well-constructed.

My mild dissatisfaction: the temporal dimension is underused. A work about how canopy declined over 50 years should make the viewer feel 50 years of change, not just see 6 data points on a line. The most powerful version of Section 4 would show the canopy trajectory with density and granularity — not a 6-point line, but an annual or decadal animation (even a simple animated scroll-triggered line that draws from left to right as the viewer scrolls).

I do not dock harshly for this because I understand the format constraints. But I note it.

## Craft /15 → 13

Five sections, five visualization forms, and the challenge of maintaining visual continuity across all of them. The specification's use of sequential green for income quartiles (across Sections 2 and 5) and the heat orange across Sections 1 and 3 is the right continuity device. The annotation style (callout lines with neighborhood labels) must be consistent between Sections 3 and later references.

## My Total: 84/100

A strong narrative visualization with the temporal dimension underserved in Section 4. The work knows what it wants to argue and argues it clearly. The prescription is specific. The historical cause is named. The main recommendation: give the timeline in Section 4 more granularity, more years, more path-visibility. The argument lives in the change, not just the endpoints.

## Innovation Flagged

**#208 — Temporal granularity as a narrative visualization quality criterion**: in a narrative visualization whose argument depends on historical change, the granularity of the temporal encoding (how many points, what resolution, whether the path is shown) is a quality criterion distinct from legibility. A 6-point line is legible; a 50-point line (or annual data) is more honest about the historical trajectory. The rubric's Data/Story Integrity dimension does not currently assess temporal resolution as a variable selection consideration.
