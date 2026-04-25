---
work: 0035-covid-counterfactual
stage: panel
rubric_version: v2.0
created: 2026-04-23
gate: PASS
---

# Panel SUMMARY — 0035 COVID-19 Deaths and the Masking Counterfactual

## Score Table

| Dimension | Nightingale (30%) | Du Bois (25%) | Rosling (20%) | Statistician (15%) | Tufte (10%) | Weighted |
|-----------|------------------|--------------|--------------|-------------------|------------|---------|
| School Fidelity /20 | 18 | 17 | 17 | 16 | 17 | 17.2 |
| Integrity /20 | 17 | 17 | 16 | 16 | 17 | 16.7 |
| Legibility /15 | 14 | 14 | 13 | 13 | 14 | 13.7 |
| Execution /15 | 13 | 13 | 13 | 13 | 13 | 13.0 |
| Resonance /15 | 14 | 14 | 13 | 12 | 13 | 13.4 |
| Purpose /15 | 14 | 14 | 13 | 13 | 14 | 13.7 |
| **Total /100** | **90** | **89** | **85** | **83** | **88** | **87.7** |

**Weighted aggregate: 87.7 / 100**
**Gate: PASS**

---

## Weighted Calculation

- Nightingale (30%): 90 × 0.30 = 27.00
- Du Bois (25%): 89 × 0.25 = 22.25
- Rosling (20%): 85 × 0.20 = 17.00
- Statistician (15%): 83 × 0.15 = 12.45
- Tufte (10%): 88 × 0.10 = 8.80
- **Total: 87.50 / 100**

---

## Key Agreements

**The counterfactual area fill structure works.** All five reviewers accept the temporal area fill as the correct generalization of the counterfactual gap technique from work 0029. The structural argument (one line is what happened; the other is what could have happened at achievable intervention; the gap is the cost of inaction) is chart-form independent. The temporal version achieves something the static bar cannot: it shows the gap accumulating over time through specific policy moments.

**The uncertainty range is the key integrity decision.** All reviewers affirm the range (130,000–180,000) and uncertainty band as the right way to communicate modeling uncertainty without false precision. The Statistician and Rosling press for additional disclosures (Delta variant assumptions; smoothing method declaration).

**The Purpose dimension scores high across all reviewers.** An advocacy work on 800,000 deaths, using a form proportionate to those stakes, with honest uncertainty acknowledgment. Purpose is fully served.

---

## Key Tensions

**Rosling vs. Nightingale on temporal granularity:** Rosling wants finer granularity (monthly data points explicitly visible; Delta variant modeling declared) and a companion empirical comparison (high-compliance countries). Nightingale accepts the current structure as sufficient for the advocacy context. Resolution: Rosling's concerns are legitimate revision targets; the current design meets the advocacy threshold.

**Statistician vs. Nightingale on the "achievable" framing:** Statistician flags "achievable" as an unsupported claim (85% compliance was not achieved); Nightingale implicitly accepts the advocacy framing. Resolution: replace "achievable" with "modeled at 85% compliance" in all design language — the revision resolves the tension without weakening the argument.

---

## Innovations Flagged (5 total)

| # | Name | Reviewer | Rubric Anchor | Cluster | Status |
|---|------|----------|---------------|---------|--------|
| 234 | Counterfactual area fill as temporal advocacy structure | Nightingale | School Fidelity / Resonance | **T** | **CONFIRMS** |
| 235 | Counterfactual gap as accumulating moral argument | Du Bois | Purpose / Resonance | **T** | **CONFIRMS** |
| 236 | Empirical counterfactual as revision target | Rosling | Integrity | T adjacent | New |
| 237 | Counterfactual integrity checklist for advocacy visualization | Statistician | Integrity | **T** | **CONFIRMS** |
| 238 | Counterfactual gap independence from chart form | Tufte | School Fidelity / Integrity | **T** | **CONFIRMS** |

---

## CLUSTER T — CONFIRMED ACROSS WORKS 0029 + 0035

**Cluster T: Counterfactual visualization integrity** is confirmed across two works from four reviewers in this work.

- **Work 0029** (#215 Nightingale, #218 Tufte): the counterfactual gap technique was first identified in the child mortality split bar chart — one bar is what is; the other is what could be at achievable intervention; the gap is the argument.
- **Work 0035** (#234 Nightingale, #235 Du Bois, #237 Statistician, #238 Tufte): the same technique is confirmed in a temporal area fill for COVID-19 deaths, a completely different data type, chart form, and subject matter.

**The confirmed generalization:** The counterfactual gap technique is a **structural visual argument type**, not a specific chart form. It applies wherever:
1. One encoding represents an empirical reality (what happened)
2. A second encoding represents a modeled counterfactual (what would have happened at a named intervention)
3. The gap between the two encodings is the primary argument (the cost of inaction, the benefit of action)

This structure operates in static bar charts (work 0029), temporal area fills (work 0035), and potentially in geographic maps (spatial counterfactuals) or network diagrams. The structural logic is chart-form independent.

**Integrity requirements confirmed across both works:**
1. The counterfactual scenario must be labeled as modeled (not empirical)
2. The modeling assumptions must be declared (compliance rate, period, pre/post-variant if applicable)
3. The uncertainty must be shown (range or band, not point estimate)
4. The causal chain must be supported by evidence
5. Confounders must be acknowledged (if not modeled, note that other factors are held constant)

**Amendment recommendation:** Add to Integrity dimension, Question 2 (Argument integrity):

> *For works using counterfactual encodings:* a counterfactual comparison (one encoding = empirical reality; second encoding = modeled scenario; gap = cost/benefit of intervention) satisfies argument integrity when: (a) the counterfactual is labeled as modeled; (b) modeling assumptions are declared; (c) uncertainty is shown as range or band; (d) the causal chain is evidenced; and (e) confounders not modeled are acknowledged. Works that meet all five conditions make an argument the data can support. Works that suppress any of these five conditions may overstate the counterfactual claim.

**Status: CLUSTER T CONFIRMED — two works, six reviewer instances (two in 0029, four in 0035), rubric amendment identified.**

---

## Design Revision Priorities

1. **Replace "achievable" with "modeled at 85% compliance"** throughout — the compliance threshold should be named as a modeling parameter, not claimed as achievable
2. **Declare Delta variant assumption**: add a figure note — "Counterfactual models use pre-Delta mask efficacy estimates; post-July 2021 counterfactual carries higher uncertainty"
3. **Show uncertainty band along full counterfactual line**, not only at terminus — the band should narrow near the beginning (less model drift) and widen toward the end
4. **Declare smoothing method**: if the lines are smoothed (e.g., 14-day rolling average), state the smoothing method in the data note
