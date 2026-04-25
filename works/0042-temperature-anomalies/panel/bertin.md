---
reviewer: bertin
work: 0042-temperature-anomalies
weight: 0.20
rubric_version: v2.2
---

# Bertin Review — 0042 Temperature Anomalies

Let me name the visual variables in use and assess whether each is correctly matched to its data.

Bar height: encodes temperature anomaly magnitude. This is a ratio variable (signed, with a meaningful zero). Bar height is a size variable — quantitative, ordered. Correct match.

Bar direction: encodes anomaly sign (above/below baseline). Binary categorical variable. Direction (up/down) is a selective, ordered variable. Correct match.

Color (gradient): encodes temperature anomaly magnitude redundantly. A continuous gradient from blue through neutral to red is an ordered variable correctly matched to ordered data. The blue-to-red gradient uses hue as an ordering device. For temperature data, the thermal association (cold = blue, hot = red) provides the ordering cue through subject-color isomorphism. This works precisely because temperature and thermal color perception are the same domain.

Time as animation variable: time is a sequence variable — ordinal, with natural direction. Animation encodes sequence by sequencing frames in time. The viewer's perception of time passing corresponds to actual time passing in the data. Perceptually matched. I find this elegant.

Trailing 10-year line: a secondary encoding providing short-term trend context. 40% opacity correctly subordinates it to the main bar. Good figure/ground handling.

Grammar errors: none. Every visual variable is correctly matched to its data type.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 18/20 | Correct grammar throughout; time-as-animation perceptually matched; color works for thermal data specifically |
| Integrity | 18/20 | NASA GISS declared; anomaly against declared baseline; no encoding errors |
| Legibility | 13/15 | Animation-as-primary context well served; [static: 11/15] |
| Execution | 14/15 | Per-frame economy excellent; trailing line adds without clutter |
| Resonance | 13/15 | Temporal accumulation produces genuine experiential resonance |
| Purpose | 13/15 | Climate visualization; stakes clear; experience is the advocacy |
| **TOTAL** | **89/100** | |
