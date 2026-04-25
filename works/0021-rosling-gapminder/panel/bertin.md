---
work: 0021-rosling-gapminder
stage: panel
school: dynamic-statistical-graphics
author: bertin
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
weight: 0.10
---

# Panel Review — Bertin on 0021: Rosling Gapminder

## Variable Analysis

Six variables; five encoding channels; the animation is the sixth.

| Variable | Channel | Assessment |
|----------|---------|-----------|
| Income | X-position, log scale | Correct: position is the most precise quantitative encoding; log scale is the honest encoding for log-normal distribution |
| Life expectancy | Y-position, linear scale | Correct: linear scale appropriate for a variable with approximately normal distribution |
| Population | Bubble size (area) | Correct: size encodes quantitative data; area requires some translation (the eye perceives radius first, not area) but is the best available size encoding |
| World region | Hue | Correct: nominal data → selective, associative variable; hue is the standard nominal encoding |
| Year | Animation | Novel: time as animation is a non-Bertin variable; I have no pre-existing grammar for it |
| Narrative | Spoken word | Not a visual variable; external to my grammar |

**On the log scale for income:** This is the correct choice from a variable-matching perspective. Income across nations is distributed log-normally. Displaying log-normally distributed data on a linear scale misrepresents the data's structure: it visually compresses the majority of observations and expands the extreme values. The log scale correctly encodes the variable's actual distribution. This is not a designer's preference; it is a data-type matching requirement.

**On time as animation:** I must acknowledge that my grammar has no vocabulary for time-as-animation. The visual variable "time" in my framework is a static position variable — it occupies an axis (as in a line chart) or encodes temporal sequence in some spatial arrangement. Animation as a time-encoding is genuinely outside my grammar.

My assessment: animation is effective as a time-encoding for the specific case where the argument is about motion through a space. It fails the retinal efficiency criterion — the viewer must watch the animation in real time, cannot simultaneously see past and present, and must hold memory across time. But retinal efficiency is not the only criterion: for experiential arguments (Tufte's concession above), animation outperforms static encodings.

---

## Dimension Scores

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity /20 | 16 | Grammar coherent; animation as encoding is outside Bertin framework but coherent within its own logic |
| Data/Story Integrity /20 | 15 | Pre-1900 confidence suppression; income-life expectancy correlation presented as implied causation |
| Legibility /15 | 12 | Six variables; some encodings (bubble size, log scale) require narration to decode; animation itself is clear |
| Visual Economy /15 | 13 | Intrinsic six-variable complexity; Cluster H applies; economy appropriate |
| Resonance /15 | 13 | Strong advocacy resonance; wonder is achieved |
| Craft /15 | 12 | Good animation; bubble overlap is unresolved |
| **Total** | **81** | |

---

## Innovation Flagged

**Innovation: Log scale as a data-type matching requirement, not a design choice** — Rubric anchor: Data/Story Integrity (Step D) / School Fidelity. For variables with known distributional properties (log-normal income distribution; power-law network degree distribution; exponential growth rates), the choice of scale is not an aesthetic preference but a data-type matching requirement. Using a linear scale for a log-normal variable is a grammar error (Bertin: mismatched variable to encoding). The rubric's Data/Story Integrity should assess whether the scale chosen for quantitative axes is appropriate to the variable's actual distribution, not just whether it is "honest" in the simpler sense of not truncating axes. A scale that is honest (starts at zero, no truncation) but mismatched to the distribution's shape can still misrepresent the data's structure.
