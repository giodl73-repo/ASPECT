---
work: 0020-dubois-staircase
stage: design
school: advocacy-visualization
type: B  # School Founder
author: human
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
---

# Design Analysis — 0020: Du Bois Staircase-Spiral Chart (1900)

*For canonical imports, the design document is an analytical description of the work's visual grammar.*

---

## Form Description

The staircase-spiral is a hand-drawn chart on cream paper, approximately 28 x 22 cm, in red and black with gold lettering. The form is:

- A spiral path that proceeds from the center-left outward to the right and upward
- The spiral is "staired" — it does not curve continuously but proceeds in discrete horizontal and vertical segments
- Each horizontal segment (tread) represents a five-year period
- Each vertical segment (riser) represents the increase in property value from the previous period
- The width of each tread represents the cumulative total property value at the end of that period
- The numbers are printed directly on each step

The spiral direction is counterclockwise when viewed from inside (the earliest period is innermost; the latest period is outermost). The visual argument is growth: each step is wider and the overall form expands outward, embodying accumulation.

---

## Variable Analysis

| Visual element | Variable type | Data encoded | Assessment |
|---------------|--------------|-------------|-----------|
| Tread width | Size (length) | Cumulative property value | Quantitative; proportional to value |
| Riser height | Size (height) | Period-over-period increase | Quantitative; proportional to increase |
| Tread sequence (left→right, inward→outward) | Position (ordinal) | Time sequence (1875→1899) | Ordered; temporal direction clear |
| Color (red) | Hue | The subject (Black Georgian property) | Nominal; consistent with Du Bois's suite convention |
| Numbers on steps | Label | Exact property values | Quantitative; direct labeling |

**Dimensional layering assessment:**

The form encodes three variables simultaneously:
1. Time (step sequence)
2. Cumulative value (tread width)
3. Growth rate (riser height)

This is ambitious dimensional layering. The question is whether the three encodings are simultaneously readable or whether they interfere with each other.

**Interference analysis:**
- Tread width and riser height are both size variables applied to the same geometric element (the step). A viewer looking at a single step must integrate two size dimensions to extract two different data points. This creates cognitive load that would not exist if the variables were encoded in different visual properties.
- The spiraling direction adds positional complexity: the outer steps are physically larger (the spiral expands), which correctly encodes the growth in cumulative value, but the viewer must distinguish between "this step is larger because it is outer" (a structural property of the spiral) and "this step is larger because cumulative value grew" (the data encoding). These are not always distinguishable without the numeric labels.

**Conclusion:** The dimensional layering is ambitious and partially successful. The temporal sequence is clear; the growth direction is unmistakable. The precise discrimination between cumulative value and growth rate requires the numeric labels.

---

## Legibility Analysis

**Without numeric labels:** A viewer sees a spiral that grows outward and upward, with a clear directional flow from small (inner) to large (outer). The argument "property ownership grew" is available from the visual gestalt before any number is read. This is successful gestalt encoding.

**With numeric labels:** The precise values are directly stated on each step. A patient viewer can extract exact numbers and compute growth rates. The form achieves both gestalt (the growth argument) and precision (the specific amounts).

**The legibility problem:** The staircase-spiral is a novel form. In 1900, no viewer at the Paris Exposition had seen it before. Novel forms require more cognitive effort than familiar forms — the viewer must infer the encoding rules from the visual grammar before extracting the data. Without familiarity with the form, the viewer must figure out:
- What does the width of each step mean?
- What does the height of each step mean?
- Why does the form spiral?

The numeric labels and the title help. But the form's novelty is a genuine legibility cost that conventional forms do not pay.

**Comparison to conventional alternatives:**
A simple bar chart showing total property value by five-year period would be immediately readable: bar height = total value, and the bars would grow consistently. The viewer extracts the argument in five seconds without inference. The staircase-spiral requires more inference but achieves richer dimensional encoding.

Du Bois's choice of the staircase-spiral over a bar chart is the advocacy-visualization trade: formal invention for rhetorical distinctiveness. The form is memorable in a way that a bar chart is not. At the Paris Exposition, 60 charts on the wall, the staircase-spiral would have arrested attention. The legibility cost is the price of attention.

---

## Comparison to Other Spiral Forms in the Suite

Work 0004 (the full Paris suite) includes other spiral forms — most notably the famous "proportion of freemen and slaves" spiral. How does the staircase-spiral compare in legibility?

**Staircase advantages over pure spiral:**
- The discrete steps make temporal sequence unambiguous: each step = one period
- The step structure prevents the eye from treating the form as a continuous variable
- The riser heights are individually readable as growth indicators

**Staircase disadvantages vs. pure spiral:**
- The staircase encoding is more complex (two size variables) than a single continuous spiral (one variable)
- The spiral direction creates some ambiguity about which step comes "next" (reading direction is counterintuitive for some viewers)

**Verdict:** The staircase form carries temporal information more clearly than a pure spiral, at the cost of encoding one additional variable (riser height as growth rate) that pure spirals do not attempt.

---

## Version Note

`version_reviewed`: The chart as reproduced in Whitney Battle-Baptiste and Britt Rusert (eds.), *W.E.B. Du Bois's Data Portraits: Visualizing Black America* (2018), which is based on the Library of Congress archival holdings. The original is hand-drawn; the reproduction faithfully captures the form.

`institutional_divergence`: Low. The chart has not been modified since 1900. The Library of Congress holds the original.

`context_decay`: Very High. The 1900 primary context — a viewer at the Paris Exposition Universelle, encountering the chart in the "American Negro" exhibit as part of a political and cultural argument about Black American achievement — is completely gone. Contemporary viewers encounter the chart as design history or advocacy visualization scholarship.
