---
work: 0005-snow-cholera-map
stage: design
school: epidemiological-mapping
review_type: canonical-import
historical_author: John Snow
author: claude
rubric_version: v1.3
created: 2026-04-23
updated: 2026-04-23
sources:
  - Snow 1855, 2nd edition
  - Tufte 1997 pp. 27-37
  - Koch 2004
---

# Design Description: Snow's Broad Street Cholera Map

---

## Visual Structure

A single map, black ink on white, approximately 12 × 14 cm in the printed book. The geographic base shows a grid of named streets in the Soho district of London. No terrain, no shading, no visual hierarchy beyond the streets themselves.

**Three layers of content, in order of visual prominence:**

**Layer 1 — The death data (dominant):**  
At every address where one or more cholera deaths occurred, Snow places stacked black bars perpendicular to the street, one bar per death, extending outward from the building line. The effect from a distance: thick black hedges along certain streets, thin or absent along others. The density is immediately visible as a spatial pattern before the viewer has read a single label.

**Layer 2 — The pump locations (secondary):**  
Eleven water pumps marked with a distinct symbol — a small circle or cross — at their geographic location on the street. The symbols are smaller and less visually prominent than the death bars. The viewer's eye finds the pumps after finding the death pattern, not before.

**Layer 3 — The street grid and names (ground):**  
A standard street map of the Soho district: named streets, block outlines, no terrain, no buildings individually shown. The grid is the scaffold for the data layers, not a subject itself.

**The argument in the layout:**  
The Broad Street pump is approximately at the center of the densest death cluster. This is not labeled. There is no arrow pointing from the cluster to the pump. The viewer is expected to see the pump at the center of the density and make the connection. The map trusts the spatial evidence.

**The negative space argument (not on the map):**  
Snow describes in his text the two notable absences: the Lion Brewery (to the west; workers drank beer and had almost no deaths) and the Poland Street Workhouse (to the east; had its own well and had far fewer deaths than its population would predict). These are spatial arguments that the map supports but does not show explicitly — you can look at the map and find the brewery's location and see the absence of bars there, but you need Snow's text to know it is significant.

---

## Encoding Decisions

| Data Variable | Visual Variable | Assessment |
|--------------|----------------|-----------|
| Death at an address | Mark (bar) | Binary: dead or not. The presence of a mark encodes a death. |
| Death count at an address | Height/count of stacked bars | Quantitative by counting; approximately quantitative by height. The bars are thin and stacked closely — readable at count, not at glance. |
| Address location | Geographic position | Faithful to ground truth: the bar appears at the street address where the death occurred. |
| Bar orientation | Perpendicular to street | Follows the street direction; bars point outward from the building. Not a random choice — it means the bar is "at" the building, pointing into the open space where the viewer looks. |
| Pump location | Shape (circle/cross symbol) | Categorical: pump or not-pump. No encoding of pump size, usage rate, or water source type. |
| Disease cluster | Emergent spatial pattern | Not explicitly encoded. The viewer reads the density pattern from the aggregate of individual death marks. The cluster is not drawn; it emerges. |

**The emergent-cluster encoding:**  
This is the founding innovation. Snow does not draw the cluster. He plots the individual deaths and lets the cluster emerge from the aggregate. The reader's visual system performs the synthesis — seeing "density here, not there" — without being told to. This is different from every other work in this project: Minard draws a band that represents the aggregate directly; Nightingale draws sectors that represent the aggregate; Beck draws lines that represent the network. Snow plots individual events and lets the aggregate argument emerge from the viewer's perception.

---

## The Epidemiological Mapping School: Founding Grammar

**1. One mark per event, at event location.** Do not aggregate before plotting. The individual events carry their own spatial argument when plotted together; aggregation would suppress the clustering pattern that is the evidence.

**2. Geographic position IS the argument.** In epidemiological mapping, geography is not a background for data — it IS the data. The spatial distribution of events is the evidence. Geographic accuracy is not cartographic convention; it is methodological necessity.

**3. Show the negative space.** The absence of events in a region is as evidentially important as their presence. The map should make both visible (by showing the map area where events could have occurred but did not).

**4. The causal source is not labeled; it is seen.** The viewer is meant to perceive the source from the spatial pattern. The map does not say "the pump caused the outbreak"; it shows the spatial clustering around the pump and trusts the viewer to make the inference.

**5. Triangulate with negative evidence.** The strongest causal argument combines: presence of events near the source + absence near areas with alternative sources + explanation of outliers. All three are in Snow's work, though principles 3-5 are mostly in his text, not the map alone.

---

## Color System

Black on white. No color. Every mark is the same visual weight. The only differentiation is between the stacked bars (deaths) and the pump symbols (location markers). This is the most visually spare work in the project to date.

---

## Typography and Labels

Street names in small serif type, placed along or beside streets. Pump symbols unlabeled (in the map; labeled "Pump" in the book text). No legend on the map itself — the legend is in Snow's accompanying text.

---

## Rendering Notes

- Published in a scientific/medical book; designed for close reading by experts
- Engraved from Snow's original drawing for the 1855 publication
- Small scale (book page): approximately 12 × 14 cm
- Not designed for display; designed for evidence
- The original hand-drawn map (pre-engraving) does not survive; the 1855 engraving is the canonical version
