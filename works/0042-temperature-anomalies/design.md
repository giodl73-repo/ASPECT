---
work: 0042-temperature-anomalies
stage: design
school: dynamic-statistical-graphics
review_type: original
rubric_version: v2.2
created: 2026-04-23
---

# Design Description: Animated Temperature Anomalies 1880–2024

## Visual Structure

**Static frame anatomy:**
- Single vertical bar centered on a zero-line (the 1951–1980 baseline)
- Bar extends upward (positive anomaly) or downward (negative anomaly)
- Bar color: continuous gradient keyed to anomaly magnitude — deep blue at −0.5°C, neutral gray at 0°C, deep red at +1.5°C
- Year printed large (72pt, upper-right corner) — the primary temporal label
- Anomaly value printed at bar tip (small, 14pt)
- Y-axis: −0.6°C to +1.6°C, labeled at every 0.2°C
- Baseline labeled: "1951–1980 average"
- Title: "Global Surface Temperature Anomaly, 1880–2024" (static, fixed across all frames)

**Animation:**
- 144 frames, one per year, 1880–2024
- Transition: bar height and color update simultaneously each frame
- A trailing line (thin, 40% opacity) shows the last 10 years' anomaly path — provides temporal context without overwhelming current-year bar
- No wipe or fade; each frame replaces the previous instantaneously
- Optional: loop with pause at 2024 frame for 5 seconds before restarting

## Encoding Decisions

| Data Variable | Visual Variable | Notes |
|--------------|----------------|-------|
| Temperature anomaly magnitude | Bar height | Linear; zero-baseline |
| Anomaly sign (above/below) | Bar direction | Up = above baseline |
| Anomaly magnitude | Bar color | Continuous gradient; blue–gray–red |
| Current year | Large year label | Primary temporal marker |
| Current anomaly value | Bar-tip annotation | Precision label |
| Recent trend | Trailing 10-year line | Context without clutter |

## Animation Variable Justification

Time as animation is the correct choice: the argument IS the temporal change. A static version showing 144 years of bars as small multiples or a strip chart would make the trend visible but would eliminate the experiential weight of watching the red grow year by year. The viewer who watches the animation from 1880 to 2024 has a different experience than the viewer who sees the end state. The change is the argument. The animation is not decoration; it is the primary encoding.

## Color Choice Note

Blue-to-red is connotative (cold/warm = danger scale). Tufte will flag this: the color is not purely retinal/quantitative — it carries cultural coding of danger. The defense: (1) the thermal association (blue = cold, red = hot) is non-arbitrary for temperature data; (2) the cultural coding of red as danger reinforces rather than contradicts the data; (3) the gradient is continuous and monotone from blue through neutral to red, which is a valid ordinal encoding. This is a contested design choice that sits at the boundary between connotative and denotative encoding.

## Narration Mode

Accompanied. The presenter says "Watch the red grow" at the start, then narrates inflection points — 1940s warm period, 1950s–1970s cooling, 1980s acceleration, 1998 El Niño, 2016 El Niño, 2023–2024 acceleration. Standalone legibility [static: 11/15].

## Source

NASA GISS Surface Temperature Analysis (GISTEMP v4). Public domain.
