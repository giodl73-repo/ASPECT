---
work: 0002-nightingale-coxcomb
stage: design
school: statistical-graphics
review_type: canonical-import
historical_author: Florence Nightingale
author: claude
rubric_version: v1.1
created: 2026-04-23
updated: 2026-04-23
sources:
  - Nightingale 1858
  - Cohen 1984
  - Brasseur 2005
---

# Design Description: Nightingale's Diagram of Causes of Mortality

---

## Visual Structure

**The work is a diptych: two polar area diagrams side by side on a single plate.**

**Left diagram — April 1854 to March 1855 (Year 1 of the war):**  
Twelve wedge-shaped sectors, one per month, arranged clockwise beginning at the 12 o'clock position with April 1854. Each wedge radiates outward from the center; its area (not its radius) represents the total mortality rate for that month. The wedge is subdivided into three concentric colored zones:
- **Blue outermost zone**: deaths from preventable zymotic diseases (the dominant zone in most months of Year 1)
- **Red middle zone**: deaths from battle wounds (usually smaller; occasionally near-absent)
- **Black innermost zone**: deaths from all other causes

In Year 1, the blue zone is enormous — particularly in January 1855 and February 1855, where the wedge extends dramatically outward, making those months' preventable disease deaths visually overwhelming. The red zone (battle wounds) is dwarfed throughout most of Year 1. The shape of the Year 1 diagram is asymmetric, bloated in the winter months, contracting in summer.

**Right diagram — April 1855 to March 1856 (Year 2):**  
Same format. But the April 1855 sector is dramatically smaller than March 1855. The cause: the Sanitary Commission dispatched to Scutari in March 1855, which began cleaning sewers, ventilating wards, and removing decomposing material. The blue zone collapses almost immediately. By summer 1855, the blue zones are small. The diagram is visually quiet compared to Year 1.

**Placement and relationship:**  
The two diagrams are placed side by side. Year 1 is on the right in Nightingale's original layout (the reader encounters the explosion first, then turns to the collapse). Some reproductions reverse the order. In either arrangement, the pairing is the argument: the reader moves from catastrophe to recovery.

**Title and annotation:**  
The title is explicit about the argument: "Diagram of the Causes of Mortality in the Army in the East." A legend identifies the three colors. The word "Preventable" is present in the legend label — it is not just a category name, it is an accusation.

---

## Encoding Decisions

| Data Variable | Visual Variable | Notes |
|--------------|----------------|-------|
| Month | Angular position (sector) | 12 sectors × 30°; clockwise from 12 o'clock |
| Total monthly deaths (by cause) | Sector area | Area, not radius — the critical encoding choice |
| Cause of death | Color (hue) | Blue = preventable; Red = wounds; Black = other |
| Temporal sequence | Reading direction (clockwise) | Follows conventional clock-reading |
| Before/after intervention | Diagram pairing | Left/right placement encodes the causal argument |

**The area-not-radius choice is deliberate and consequential.** If Nightingale had used radius to encode quantity, the visual differences would be even more dramatic (radius scales as square root of area, so large values look far larger if encoded in radius). By using area, she is being statistically conservative. The choice is not naïve — she understood the difference. Using area is the more honest encoding; using radius would have been more rhetorically extreme but less defensible.

**This is not Bertin's preferred grammar.** Bertin identifies area as a variable with ordered and quantitative properties, but it is harder for the eye to estimate than bar height (linear position). A bar chart of the same data would be more precisely readable. Nightingale chose the polar form over the bar chart. The reasons are debated; likely: the polar form is visually unusual and arresting; it does not look like the tables that decision-makers had already ignored; it reads as a dramatic shape before it reads as a set of numbers.

---

## School-Specific Elements

**Advocacy visualization (founding grammar):**
- The audience is explicitly identified as decision-makers who hold power and are not statisticians
- The encoding is chosen for rhetorical impact over statistical precision
- The title carries the argument ("Preventable")
- The data is selected and framed to foreground the policy implication
- The pairing of diagrams creates a before/after causal structure that the reader can grasp without instruction

**Statistical graphics:**
- Quantitative data (mortality counts) encoded in a visual variable (area)
- Color used categorically (cause of death)
- A time axis (months) arranged spatially (angular position)
- Explicit legend

**What the work does NOT do:**
- Does not present confidence intervals or uncertainty
- Does not show competing interpretations of the data
- Does not distinguish between deaths Nightingale's specific reforms could have prevented vs. those that other factors addressed
- Does not acknowledge that the decline in Year 2 correlates with (not necessarily caused by) the Sanitary Commission

---

## Color System

- **Blue/grey-blue**: the dominant color visually and politically. In Year 1, it fills most of the plate. This is the color of preventable death.
- **Red/pink**: battle wounds. Visually subordinate in almost every month. This is the detail that subverts the public assumption that soldiers die in war from fighting.
- **Black**: other causes. A residual that the reader deprioritizes visually.

The color logic is advocacy logic: the "most important" cause (preventable disease) gets the most visually prominent, expansive color. There is no pretense of neutral categorical color assignment.

---

## Typography and Labels

- Title block states the argument
- Legend identifies three colors by cause category — the label "Preventable or Mitigable Zymotic Diseases" is unusually long for a legend entry; it is doing argumentative work
- Month labels at each sector's outer edge
- Year and "Cause of Death" labels
- The diagrams have a directional note in Nightingale's reports indicating how to read the sectors

---

## Rendering Notes

- Original: printed lithograph, hand-colored or early color printing
- Plate size: approximately A3 (42cm × 30cm) for the diptych
- Color is essential — the encoding collapses without it
- Designed for private distribution, not for exhibition; the scale is reading scale, not display scale
- The work exists in several slightly variant printings; the 1858 version is the canonical one
