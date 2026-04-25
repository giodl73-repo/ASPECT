---
work: 0004-dubois-paris-charts
stage: panel
rubric_version: v1.3
created: 2026-04-23
gate: PASS
---

# Panel SUMMARY — 0004 Du Bois Paris Charts

## Score Table

| Dimension | Nightingale (30%) | Tufte (25%) | Neurath (20%) | Audience (15%) | Artist (10%) | Weighted |
|-----------|------------------|------------|--------------|---------------|-------------|---------|
| School Fidelity /20 | 17 | 15 | 16 | — | — | 16.1 |
| Data/Story Integrity /20 | 16 | 15 | 17 | — | — | 16.0 |
| Legibility /15 | 13 | 12 | 14 | 13 | — | 13.1 |
| Visual Economy /15 | 11 | 8 | 12 | — | — | 10.4 |
| Resonance /15 | 15 | 14 | 15 | 15 | 15 | 14.8 |
| Craft /15 | 13 | 13 | 14 | — | 14 | 13.4 |
| **Total /100** | **85** | **77** | **88** | — | — | **83.8** |

**Weighted aggregate: 83.8 / 100**  
**Gate status: PASS**

---

## The Scoreboard (all four works, v1.3)

| Work | School | v1.3 Score |
|------|--------|-----------|
| 0001 — Minard Napoleon March | Type C synthesis | 83.5 |
| 0002 — Nightingale Coxcomb | Type B founder | 81.2 |
| **0004 — Du Bois Paris Charts** | **Type C synthesis** | **83.8** |
| 0003 — Beck Underground | Type B founder | 91.0 |

Du Bois almost ties Minard. The gap is in Visual Economy — Du Bois's decorative complexity is the only significant drag on an otherwise high-performing work. Everything else (data integrity, legibility, resonance, craft) scores at or above Minard.

---

## Key Agreements

**Resonance is the strongest dimension, and it is unanimous.** Every reviewer gives 14 or 15. The work achieved its advocacy goal (gold medal, international record, 120-year survival). Tufte gives 14 rather than 15 because he applies the harder standard (ideological change, not record-entry). Everyone else gives 15. This is the highest-agreement score on Resonance in the project — even Beck, with his purely functional map, had more spread on this dimension.

**Data integrity is high despite the formal invention.** Nightingale, Tufte, and Neurath all score 15–17. The key agreement: Du Bois's honest treatment of unflattering data (the illiteracy chart, the low income levels) is the single most important integrity move in the series. He could have suppressed the difficult numbers; he showed them and contextualized them. That is a form of integrity all three reviewers recognize and credit.

---

## Key Tensions

**Visual Economy: the 8 vs. the 12.**  
Tufte scores 8; Neurath scores 12; Nightingale scores 11. The gap (4 points) is the largest sustained disagreement on a single dimension in this project. All three reviewers are correct in their own frameworks. Tufte is measuring decoration against data: the spirals are decorative relative to what a bar chart would achieve. Neurath is measuring accessibility: the spirals expand the receiving audience and are therefore economical in a different sense. Nightingale is holding a middle position: she understands the exhibition logic but still sees visual excess.

This tension is not resolvable by the current rubric. The three reviewers are applying three different definitions of "economy" — data economy, audience economy, and display economy — to the same marks. The rubric should distinguish them.

**What is the resonance type?**  
Nightingale says Type III (advocacy efficacy). Neurath agrees. Tufte says Type III, partially. The Artist says none of the current types — she proposes "testimonial resonance," a form rooted in the conditions of the making act itself. The Audience lens adds a second new concept: delayed record-entry resonance (contemporaneous vs. long-arc efficacy). The panel has produced *two* new Resonance type candidates from a single work, both distinct from the four existing types AND from each other.

---

## Innovations Flagged (12 total)

| # | Name | Reviewer | Rubric Anchor | Status |
|---|------|----------|---------------|--------|
| 33 | Precision as defiance | Nightingale | Data Integrity / Resonance (III) | New |
| 34 | Comparative selection as argument | Nightingale | Data/Story Integrity | New |
| 35 | Decoration as exhibition strategy | Tufte | Visual Economy | New |
| 36 | Political stakes as resonance amplifier | Tufte | Resonance (III) | New |
| 37 | Two-speed legibility | Neurath | Legibility | New |
| 38 | Accessibility as visual economy | Neurath | Visual Economy | **Cluster G candidate** |
| 39 | Hostile audience legibility | Audience | Legibility | New |
| 40 | Resonance that accumulates (delayed) | Audience | Resonance (III) | **Cluster E candidate** |
| 41 | Color as subject declaration | Artist | School Fidelity (C) / Resonance | New |
| 42 | Testimonial resonance | Artist | Resonance | **Cluster E candidate** |

---

## Cluster Updates

### Cluster E — Resonance Type V: **STRONG CANDIDATE, near threshold**
**Works: 0003 + 0004. Innovations: #25 (domain-gated gestalt), #31 (functional resonance), #40 (delayed/accumulated resonance), #42 (testimonial resonance)**

Four innovations across two works — but they are pointing at *multiple* new Resonance types, not a single one:
- #25 and #31 from work 0003 = domain-gated and functional
- #40 and #42 from work 0004 = delayed record-entry and testimonial

These may need to split into two sub-clusters (E1 and E2). The panel has found that "Resonance Type V" is actually hiding multiple distinct concepts. *Consider splitting before amending.*

### Cluster F — Data model declaration: **STILL FORMING**
**Work: 0003. Innovations: #22, #24.** Work 0004 did not generate further Data model innovations. One more work needed.

### New Cluster G — Visual Economy: context-dependent definition: **FORMING**
**Work: 0004. Innovations: #35 (decoration as exhibition strategy), #38 (accessibility as visual economy)**  
Both point at the same gap: Visual Economy currently asks "does each mark represent data?" It should ask "what is this complexity for, and does it serve a legitimate communicative purpose in this context?" A third definition of economy emerges alongside data economy (Tufte) and audience economy (Neurath): *display economy* — is the visual complexity appropriate to the competitive display environment? Watch for work 0005.

---

## Design Recommendations

1. **Split Cluster E before amending.** Four innovations, two works, but pointing at three or four different new Resonance types. Amending as "Type V" would be premature — it would name a single type for what may be three distinct phenomena (domain-gated, functional, testimonial, delayed). *Separate analysis needed.*

2. **Amend Visual Economy** after one more confirmation of the context-dependent definition gap. Cluster G is strong from a single work; one more confirmation would be decisive.

3. **Add `advocacy_type`** to frontmatter as recommended by work 0002 SUMMARY. Du Bois = directed + suite + public-display.

4. **Document the advocacy-visualization school** formally in `schools/`. It now has three founding works in the project (Nightingale 0002, Du Bois 0004, and implicitly Minard 0001's narrative function). The school grammar can now be written.
