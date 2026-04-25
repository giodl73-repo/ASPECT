# DEGAS Design Specification v1.0

**Date:** 2026-04-23  
**Status:** Active — first specification

---

## 1. Mission

DEGAS is a studio for studying and designing visualizations across the full spectrum from quantitative statistical graphics to pure artistic expression. The method is practice: we learn how visualization schools work by working in them — designing in their vernacular, critiquing through their principles, and evolving our understanding through production.

## 2. Core Architecture

DEGAS follows the governance patterns established in the sister repos (marathon, tigris, chronicle, artisan):

- **Frontmatter contracts** on all generated files
- **Forward-only versioned rubric** with cluster-driven amendment
- **Named personas** who disagree by design
- **Innovation logging** → cluster analysis → amendment
- **Session handoff** discipline

## 3. Schools

Visualization schools are the intellectual territory DEGAS explores. A school is a tradition with its own visual grammar — a set of primitives, compositional rules, encoding conventions, and principles. Schools are documented in `schools/` and populated as works require them.

**Founding schools** (to be documented during first works):
- `statistical-graphics` — quantitative data, charts and graphs
- `cartography` — spatial, geographic, network
- `isotype` — pictographic, democratic
- `scientific-illustration` — natural history, anatomical
- `abstract-art` — non-representational formal composition
- `information-architecture` — systems, flows, diagrams

New schools are added when a work requires a grammar not yet documented.

## 4. Personas

Eight founding personas, each a historically grounded visualizer who embodies one or more schools. They voice panel reviews from genuine intellectual stances and disagree by design.

See `personas/` for full definitions.

## 5. Review System

The panel system runs 3 personas + 2 lenses per work. Selection is guided by school alignment:
- Primary persona: most identified with the work's school
- Secondary: adjacent or contrasting school (productive friction)
- Tertiary: addresses a dimension the first two may neglect

Lenses are cross-cutting perspectives (statistician, designer, audience, historian, artist) that do not belong to a school.

## 6. Rubric

Six dimensions, 100 points total. Advisory threshold 60. See `scoring/RUBRIC.md` for current version.

## 7. Works

Works live in `works/NNNN-slug/`. A completed work has:
- `brief.md` — the visualization problem
- `design.md` — the visualization specification
- `panel/` — persona and lens reviews + SUMMARY
- Optionally: `rendering.txt`, `rendering.svg`

## 8. Pipeline

`BRIEF → [SCHOOL] → DESIGN → PANEL → [INNOVATION] → [AMENDMENT] → HANDOFF`

See `docs/PIPELINE.md` for stage details and gate thresholds.

## 9. Scope and Direction

DEGAS is deliberately open-ended at founding. The journey through visualization strategies — from statistical symbols to artworks — will define the project's shape through production. We expect:
- Early works to explore foundational schools (statistical graphics, cartography)
- Middle works to push into expressive territory (isotype, abstract, data art)
- Later works to synthesize and hybridize schools
- The rubric to evolve as production surfaces what the founding dimensions miss

The personas set the critical vocabulary. The works test it. The amendments refine it.
