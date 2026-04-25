---
work: 0046-minard-hannibal
stage: design
school: cartography, statistical-graphics
review_type: canonical-import
historical_author: Charles Joseph Minard
historical_date: 1866
rubric_version: v2.2
created: 2026-04-23
---

# Design Description: Minard's Hannibal Map (1866)

## Visual Structure

Single-register flow map (unlike the Napoleon map's two registers).

**Geographic base:** Southern France, Mediterranean coast, Alps, and northern Italy. Coastlines, major rivers (Rhone, Po), and mountain ranges (Alps) shown schematically. City and region labels in French. The geographic base is simplified — the Alps are shown as a mountain symbol rather than topographic contours.

**Band:**
- Single color (brown/tan) flow band, width proportional to troop count
- Left to right: from the Rhone junction eastward and then southward into Italy
- Key labeled points: Rhone junction (~90,000), Cartagena departure (implied), various Alpine crossings, arrival in Italy (~26,000)
- The band narrows steadily with major drops at key engagements and the Alpine crossing itself

**Text elements:**
- Title block describing the campaign and encoded variables
- Troop counts labeled at key inflection points
- Place names at geographic positions
- Scale of band width (e.g., "une ligne = X hommes")

**Key structural difference from the Napoleon map:**
The Hannibal map has only ONE register. The Napoleon map has two registers (march map + temperature chart below), with a shared horizontal axis linking them. The Hannibal map does not include a corresponding variable (temperature, terrain elevation) in a second register. This is a simpler composition.

**Key data quality difference:**
Hannibal's troop counts come from Polybius and Livy — ancient historians writing generations after the campaign. The numbers are contested: modern historians estimate between 20,000 and 50,000 soldiers arrived in Italy. Minard used the higher figures from his sources. The uncertainty is substantial; the Napoleon map uses contemporary military records with much lower uncertainty.

## School-Specific Elements

**Cartographic:**
- Geographic base map with city labels, river systems, mountain symbols
- Route encoded as a geographic path

**Statistical-graphics:**
- Band width = troop count (quantitative, linear encoding)
- Troop counts labeled at key points
- Single-variable flow encoding

## Comparison with Napoleon Map (0001)

| Feature | Napoleon (0001) | Hannibal (0046) |
|---------|----------------|----------------|
| Registers | 2 (march + temperature) | 1 (march only) |
| Data quality | Contemporary records | Ancient sources (Polybius, Livy) |
| Geographic scope | Russia campaign, ~2000km | Alps crossing, ~500km |
| Emotional weight for Minard | Personal/national memory | Historical study |
| Variables encoded | 6 (size, direction, geography, route, temperature, time) | 4 (size, direction, geography, route) |
| Year | 1869 | 1866 |
