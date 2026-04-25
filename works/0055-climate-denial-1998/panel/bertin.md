---
reviewer: bertin
work: 0055-climate-denial-1998
weight: 0.10
rubric_version: v2.2
---

# Bertin Review — 0055 "No Warming Since 1998" Temperature Chart

The time-series line chart uses a small, well-defined set of visual variables:

**Position (x-axis):** Time, encoded as years 1998 to present. The x-axis is the temporal scope selection. Encoding is correct; the scale is linear and honest.

**Position (y-axis):** Temperature anomaly in degrees Celsius. The y-axis origin and scale are honest — no truncation, no distortion.

**Shape (line):** Connects sequential data points. Conventional and correct for continuous temporal data.

**Shape (trend line):** A regression line fitted to the data in the window. Mathematically correct for the selected window.

The encoding passes my audit. Every visual variable is correctly matched to its data type. Position encodes both temporal and magnitude data correctly. The trend line correctly represents the mathematical trend within the selected window.

The coercion is in the x-axis scope — the choice of where the time axis begins. In my visual variable framework, scope selection is a design decision at the data preparation stage, prior to encoding. The encoding faithfully represents the scope that was selected. The grammar cannot show "this scope was selected to produce this result" because scope is an input to the visualization, not a variable encoded within it.

Let me be precise about what this means: the time-series grammar, applied correctly, will produce different visual arguments depending on the temporal scope of the data provided. The same temperature data, starting in 1970, produces a clearly rising trend. Starting in 1998, it produces a flat trend. The grammar is neutral between these inputs — it encodes faithfully whatever scope it is given. The designer's control over the scope is the designer's control over the argument.

**Implication for v2.3:** The Integrity questions should explicitly address temporal scope selection as a Q2 variable — not just whether accuracy tradeoffs are declared, but whether the temporal scope was chosen to produce a desired result. "Time window selection should be disclosed and justified when the choice of window materially changes the apparent trend."

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 14/20 | Statistical-graphics grammar correctly applied throughout |
| Integrity | 5/20 | Encoding is correct; temporal scope selected for desired result; El Niño anomaly not disclosed; Q2 and Q3 failures |
| Legibility | 12/15 | Fully legible in the primary reading context |
| Execution | 12/15 | Standard execution; competent line chart production |
| Resonance | 9/15 | Effective in denial communications context |
| Purpose | 4/15 | Purpose is manufactured scientific ambiguity; delays climate policy action |
| **TOTAL** | **56/100** | |
