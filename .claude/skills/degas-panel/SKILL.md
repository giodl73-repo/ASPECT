# Skill: degas-panel

**Pipeline position:** Stage 3 — after design  
**Rubric version:** v3.0 — ASPECT  
**Produces:** `works/NNNN-slug/panel/<persona>.md` and `works/NNNN-slug/panel/SUMMARY.md`

---

## Purpose

Run a multi-voice panel review of a completed visualization design. Three personas (chosen by school alignment) and two lenses each review the work against the rubric, disagreeing by design. The SUMMARY aggregates scores and surfaces the productive tensions for the designer.

## Preconditions

- `works/NNNN-slug/design.md` exists and is complete
- `scoring/RUBRIC.md` is the current rubric version
- Personas are defined in `personas/`

## Procedure

1. **Select reviewers.** Choose 3 personas from `personas/` based on school alignment:
   - Primary: the persona most identified with the work's school
   - Secondary: a persona from an adjacent or contrasting school (productive friction)
   - Tertiary: a third persona chosen for a dimension the first two may neglect

   Select 2 lenses from `personas/lenses/` based on the brief's concerns:
   - Default: `statistician` + `audience` for quantitative works; `historian` + `artist` for expressive works

2. **Run each persona review.** For each persona:
   - Read their definition in `personas/<slug>.md`, especially their preferred axes and voice
   - Apply ALL ASPECT dimension steps before scoring:
     - **School**: classify Type A/B/C/D; for Type B, declared grammars reach the upper anchors more readily
     - **Truth**: determine reportive vs. demonstrative; for reportive apply 3 questions (Disclosure, Argument integrity, Framing integrity); for demonstrative apply E1-E4
     - **Clarity**: specify primary context (wayfinding / political-presentation / contemplative-study / public-display); narration mode; note contemporary context decay in brackets
     - **Precision**: classify mark types (data / intrinsic complexity / ecology-as-composition / structural-attentional / cognitive-accessibility / decorative); assess craft quality
     - **Effect**: classify primary type (Experiential / Advocacy / Domain); note timing (delayed + mechanism); note dynamic variable [static: X/15]
   - Score the work on all 6 ASPECT dimensions (0 to max for each)
   - Write the review in the persona's voice: specific, grounded in the design document, referring to named elements
   - Identify 1-2 structural innovations — techniques the work deploys or problems the rubric doesn't yet name
   - Save to `works/NNNN-slug/panel/<persona>.md`

**Available personas (10 total):** minard, tufte, nightingale, playfair, bertin, neurath, beck, kandinsky, dubois, rosling

3. **Run each lens review.** Same procedure, voiced from the lens perspective. Save to `works/NNNN-slug/panel/<lens>.md`.

4. **Write the SUMMARY:**
   - Score table: each reviewer's scores by dimension + total
   - Weighted aggregate (primary persona: 30%, secondary: 25%, tertiary: 20%, lens 1: 15%, lens 2: 10%)
   - Key agreements: where do reviewers converge?
   - Key tensions: where do they most sharply disagree? what does that tension illuminate?
   - Innovations flagged: list any structural innovations named in reviews
   - Gate status: PASS (≥ 60), ADVISORY (50-59), FAIL (< 50)
   - Design recommendations: 3-5 specific actionable revisions

   Save to `works/NNNN-slug/panel/SUMMARY.md`.

## Persona Review Format

```markdown
---
work: NNNN-slug
stage: panel
reviewer: persona-slug
rubric_version: v3.0
created: YYYY-MM-DD
---

# [Persona Name] — Panel Review

## Scores

| Dimension | Score | Max |
|-----------|-------|-----|
| Aim | | 15 |
| School | | 20 |
| Precision | | 15 |
| Effect | | 15 |
| Clarity | | 15 |
| Truth | | 20 |
| **Total** | | **100** |

## Review

[Voiced review in persona's register, addressing specific design elements]

## Innovations Flagged

[Any structural techniques this work deploys that the rubric doesn't yet name]
```

## Example Invocation

`/degas-panel 0001-napoleon-losses` — runs full panel (3 personas + 2 lenses) on work 0001, produces panel/ directory and SUMMARY.
