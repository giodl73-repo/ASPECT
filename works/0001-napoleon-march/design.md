---
work: 0001-napoleon-march
stage: design
school: cartography, statistical-graphics
review_type: canonical-import
historical_author: Charles Joseph Minard
author: human
rubric_version: v1.0
created: 2026-04-23
updated: 2026-04-23
sources:
  - Minard 1869 lithograph
  - Tufte 1983 pp. 40-41, 176-177
  - Robinson 1967 (Imago Mundi)
---

# Design Description: Minard's Carte figurative (Napoleon's March)

*This document describes the actual historical work for panel review. In canonical import mode, this replaces the DEGAS-generated design specification.*

---

## Visual Structure

The work divides into two registers:

**Upper register — the March map:**
A simplified geographic base showing Eastern Europe from the Niemen River (Poland/Russia border, left edge) to Moscow (right). The base is light gray on cream; rivers (Niemen, Berezina, Dniepr, Dvina) are shown as light blue lines; city names (Kowno, Wilna, Smorgoni, Molodetchno, Minsk, Studianka, Witebsk, Smolensk, Dorogobouje, Gjatz, Wiazma, Czeraeia, Mojaisk, Moscow, and others) are printed in small serif text.

Overlaid on this base: two interlocking flow bands.
- **Tan band** (advance, left to right): begins at full width at the Niemen, narrows with each engagement or attrition event, reaches Moscow as a drastically reduced remnant
- **Black band** (retreat, right to left): begins narrow at Moscow and continues to narrow; several auxiliary black branches represent detachments sent in different directions

Specific troop counts are labeled at key points along both bands in small text: 422,000 at the Niemen; 400,000 after first losses; 327,000 at Wilna (advance); and so on through 10,000 at the final crossing.

**Lower register — the temperature chart:**
Below a thin horizontal rule, a line chart shows the temperature during the retreat, in degrees Réaumur, with dates along the horizontal axis. The horizontal axis is aligned to the same geographic positions as the retreat band above — so at any city during the retreat, the temperature below it (on the same vertical line) is the temperature during the retreat through that city.

The two registers share horizontal position as a linking variable: geographic longitude (upper) and retreat date/position (lower) are mapped to the same horizontal axis, allowing the reader to connect cold temperatures with a specific point on the retreat band.

---

## Encoding Decisions

| Data Variable | Visual Variable | Scale |
|--------------|----------------|-------|
| Army size | Band width | Linear: 1mm ≈ ~10,000 men |
| Direction (advance vs. retreat) | Color hue | Categorical: tan = advance, black = retreat |
| Geographic position | X,Y position on map | Approximate geographic coordinates |
| Route/sequence | Band path (connected flow) | Temporal/spatial sequence |
| Temperature during retreat | Y-position in lower register | Linear, Réaumur scale |
| Key date/position | Shared horizontal alignment | Linked across registers |
| Named locations | Text label at geographic position | Direct annotation |

**Critical encoding choice:** Band width (size variable) encodes a quantitative value. Per Bertin's grammar, size is an ordered, quantitative-capable variable — the correct choice for troop counts. This is not an obvious choice in 1869; most contemporaries used tables or point symbols. Minard invents or popularizes the use of band width as a continuous quantitative encoding.

**Critical structural choice:** The two-register layout, with shared horizontal position linking geography to temperature, creates what we might call a **temporal-spatial bridge**: a single axis serves two purposes simultaneously. The upper register uses horizontal position for geographic longitude; the lower register uses horizontal position for temporal position (dates of the retreat). They coincide because the army moved geographically as time passed — the bridge holds as long as the army keeps moving in one direction.

---

## School-Specific Elements

**Cartographic:**
- Geographic base map (simplified, not to scale)
- Named cities at geographic coordinates
- River systems as blue vector features
- Scale suppressed in favor of readability

**Statistical-graphics:**
- Band width = quantitative variable (linear scale)
- Temperature line chart with labeled axis
- Numerical labels at key inflection points
- Multi-variable encoding in a single figure

**Narrative-visualization (unnamed school):**
- The work tells a story: enormous army goes, disaster returns
- The reader's eye follows the band left-to-right, then tracks the black retreat right-to-left
- The sequence is not abstract; it is causally ordered
- The final number (10,000) lands as a conclusion

---

## Color System

- **Tan/buff**: advance band; warm, neutral, suggestive of sunlight or ordinary movement
- **Black**: retreat band; absence of color = death, cold, failure
- **Light blue**: rivers; cartographic convention
- **Cream/off-white**: background; low visual noise
- **Gray**: geographic base features (terrain suggestion)

No color is decorative. The tan/black binary is the primary narrative variable. A viewer who grasps only this encoding grasps the work.

---

## Typography and Labels

- Serif typeface throughout; French text
- Title block in upper left: full description of the six encoded variables (a legend embedded in prose)
- Numerical labels (troop counts) placed along the bands at key events
- Place names positioned at geographic coordinates
- Temperature axis labeled in Réaumur; dates labeled below the chart line

---

## Rendering Notes

- Original: lithograph, approximately 62cm × 30cm
- Paper: cream stock; light printing on gray base
- The work was designed for detailed study, not for glancing; it rewards slow reading
- It functions at two reading distances: at arm's length (overall shape, emotional impact) and at close reading (specific numbers, dates, place names)
