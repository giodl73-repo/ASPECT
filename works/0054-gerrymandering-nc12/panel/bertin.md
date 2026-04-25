---
reviewer: bertin
work: 0054-gerrymandering-nc12
weight: 0.10
rubric_version: v2.2
---

# Bertin Review — 0054 North Carolina Congressional District Map

The visual variable analysis of the district map is brief, because the encoding is simple and correct.

**Position:** Geographic. Encodes real-world location. Correct.

**Shape:** District boundary. Encodes the boundaries of each jurisdiction. The shape is irregular — particularly for NC-12 in its 1993 form — but the shape correctly represents the actual district boundary. The irregular shape is not a visual encoding error; it is honest representation of an irregular boundary.

**Color (hue):** District identity. Each district receives a distinct hue. Hue is a selective, nominal variable; district identity is nominal data. This pairing is correct.

The encoding is complete and correct. Every variable is well-matched to its data type. The grammar is sound.

Now let me say what the grammar cannot represent.

The visual variable system can encode: position, size, shape, value, hue, orientation, texture. It cannot encode: "this shape was drawn to optimize partisan seat allocation." There is no visual variable for process provenance. A district drawn by an impartial commission and a district drawn to maximize partisan advantage look identical in the choropleth grammar. The grammar cannot distinguish them.

This is not a failure of the grammar; it is an appropriate boundary of what the grammar was designed to do. The choropleth encodes "what is here" (geographic identity, area membership). It does not encode "why is it here" or "what produced this arrangement." For civic cartography, the "why" question is often the most important one, and the grammar cannot answer it.

The implication for v2.3 is that civic cartography — maps of politically-produced geographic structures — may require a disclosure modifier analogous to the counterfactual checklist in the Integrity section: when the subject of the map was produced by a political process, the process should be disclosed.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 18/20 | Cartography Type A; grammar is precisely applied; the irregular district boundaries are correct representations |
| Integrity | 11/20 | Visualization encoding is fully honest; the process that produced the subject is invisible in the grammar and undisclosed; civic cartography requires process disclosure that standard choropleth cannot provide |
| Legibility | 13/15 | Fully legible in standard civic use context |
| Execution | 14/15 | Clean cartographic execution; appropriate scale and detail |
| Resonance | 8/15 | Geographic naturalization is the resonance effect |
| Purpose | 7/15 | Legitimate reference use partially served; civic deliberation purpose not served |
| **TOTAL** | **71/100** | |
