# DEGAS — Visualization Design Lab

## Mission

DEGAS is a studio for studying and designing visualizations across the full spectrum from quantitative statistical graphics to pure artistic expression. We learn how visualization schools work by working in them — designing in their vernacular, critiquing through their principles, and evolving our understanding through practice.

The name honors the project's dual nature: Edgar Degas, who studied movement and light obsessively from within a tradition while quietly breaking it.

## Core Vocabulary

- **School** — a visualization tradition with its own visual grammar, principles, and exemplars (statistical graphics, isotype, cartography, abstract art, etc.)
- **Work** — a single visualization design belonging to a school, produced in response to a brief
- **Brief** — the assignment: what is being shown, who is the audience, which school applies
- **Persona** — a named visualizer (historical or synthetic) who embodies a school and voices reviews
- **Lens** — a review perspective (statistician, designer, audience, historian, artist)
- **Panel** — a multi-persona/multi-lens review of a work
- **Innovation** — a structural technique that advances the rubric; logged during panel sessions
- **Amendment** — a rubric revision ratified from clustered innovations
- **ASPECT** — the rubric framework (v3.0): **A**im, **S**chool, **P**recision, **E**ffect, **C**larity, **T**ruth. Six dimensions, 100 points total. Every visualization has aspects; ASPECT checks all of them.

## Visual Schools (living list)

- `statistical-graphics` — charts, graphs, quantitative comparison (Playfair, Tufte, Nightingale)
- `cartography` — spatial, geographic, topological maps (Minard, Beck)
- `isotype` — standardized pictographic systems (Neurath, Arntz)
- `scientific-illustration` — anatomical, botanical, natural history (Haeckel, Thompson)
- `abstract-art` — non-representational, formal visual language (Kandinsky, Albers)
- `information-architecture` — systems, flows, diagrams (contemporary)
- `data-art` — artistic treatment of data, aesthetic-first
- `narrative-visualization` — story-driven, editorial, journalistic

Schools are defined in `schools/`. New schools are added when a work requires a vocabulary not yet documented.

## Personas (named visualizers)

Eight founding personas live in `personas/`. Each embodies a school, has signature techniques, and voices panel reviews from their own intellectual stance. Personas disagree by design.

| Slug | Name | School(s) | Signature |
|------|------|-----------|-----------|
| `minard` | Charles Joseph Minard | cartography, statistical | Flow maps, dimensional layering |
| `tufte` | Edward Tufte | statistical graphics | Data-ink ratio, chartjunk critique |
| `nightingale` | Florence Nightingale | statistical graphics | Polar diagrams, advocacy framing |
| `playfair` | William Playfair | statistical graphics | Bar/line/pie invention, commercial clarity |
| `bertin` | Jacques Bertin | semiotics, cartography | Visual variables, retinal efficiency |
| `neurath` | Otto Neurath | isotype | Pictographic democracy, repetition-not-scaling |
| `beck` | Harry Beck | cartography, schematic | Topological reduction, 45°/90° geometry |
| `kandinsky` | Wassily Kandinsky | abstract art | Point-line-plane, synesthetic resonance |

## Review Lenses

Five cross-cutting perspectives in `personas/lenses/`:

- `statistician` — data accuracy, encoding integrity
- `designer` — visual craft, technical execution
- `audience` — legibility, accessibility, comprehension
- `historian` — school fidelity, historical authenticity
- `artist` — resonance, originality, visual surprise

A standard panel invokes 3 personas (chosen by school alignment) + 2 lenses.

## File Naming Conventions

- Works: `works/NNNN-<slug>/` — numbered, kebab-case slug
- Schools: `schools/<slug>.md`
- Personas: `personas/<slug>.md`
- Lenses: `personas/lenses/<slug>.md`
- Skills: `.claude/skills/degas-<name>/SKILL.md`
- Handoffs: `docs/handoff/YYYY-MM-DD-<slug>.md`

## Frontmatter Contract

Every generated file opens with YAML frontmatter:

```yaml
---
work: NNNN-slug          # for work artifacts; omit for non-work files
stage: brief|design|panel|handoff
school: school-slug
author: persona-slug (or 'human')
rubric_version: v1.0
created: YYYY-MM-DD
updated: YYYY-MM-DD
sources: []
---
```

## Session Resume Protocol

1. Read latest `docs/handoff/YYYY-MM-DD-<slug>.md`
2. Confirm rubric version via `scoring/RUBRIC.md` header
3. Report in one sentence: rubric version + most recent work + top 1-3 priorities
4. Do NOT re-read full CLAUDE.md or TRACKER unless instructed

## Editorial Rules

1. **School first** — every design decision should be traceable to school principles; don't mix school grammars without naming the tension
2. **No hierarchy of schools** — statistical is not more rigorous than abstract; isotype is not simpler than cartography; each school has its own demands
3. **Personas disagree** — Tufte and Kandinsky will rarely agree on a work; that friction is the point
4. **Innovation over repetition** — a panel that finds no new structural technique has not looked hard enough
5. **Forward-only rubric** — rubric amendments apply to works created after ratification; never retroactively re-score
