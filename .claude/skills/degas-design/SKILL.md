# Skill: degas-design

**Pipeline position:** Stage 2 — after brief, before panel  
**Produces:** `works/NNNN-slug/design.md` (and optionally `rendering.txt` or `rendering.svg`)

---

## Purpose

Generate a complete visualization design specification in the school's vernacular. The design document describes the visualization with enough precision that it could be rendered by a skilled practitioner in the school's medium, and reviewed by the panel against the rubric.

## Preconditions

- `works/NNNN-slug/brief.md` exists and is complete
- School is documented in `schools/` (or document it now via `degas-school`)
- No open questions remain in the brief

## Procedure

1. **Read the brief.** Identify the school, the subject, the audience, the core message, and the constraints.

2. **Read the school document** in `schools/<slug>.md`. Note the visual grammar: primitives, compositional rules, encoding conventions, forbidden moves.

3. **Design in the school's vernacular:**

   ### Visual Structure
   Describe the overall form: what is the viewer's first impression? What is the organizing principle of the layout? What is the figure and what is the ground?

   ### Encoding Decisions
   For each data variable or narrative element: what visual variable encodes it, and why is that variable appropriate (per Bertin's grammar)? State encodings as rules: "circle area = population," "color hue = continent," "horizontal position = year."

   ### School-Specific Elements
   What specific techniques from this school are deployed? Name them by their school vocabulary (e.g., "flow band width encodes troop strength" for Minard-style cartography; "symbol repetition, not scaling, encodes quantity" for isotype).

   ### Typography and Labels
   Where do labels appear? What typeface conventions does the school use? How are legends handled — inline or separate?

   ### Color System
   What colors are in use? For each color: what does it encode and why? Is the palette school-appropriate?

   ### Rendering Notes
   What medium does this belong to? Paper? Screen? What dimensions? Any rendering constraints the practitioner should know?

4. **Produce an optional rendering** for simpler visualizations:
   - ASCII art for schematic/diagrammatic work
   - SVG description for geometric work
   - Annotated layout sketch in markdown for complex work

5. **Write frontmatter** and save to `works/NNNN-slug/design.md`.

## Output Format

```markdown
---
work: NNNN-slug
stage: design
school: school-slug
author: persona-slug (or human)
rubric_version: v1.0
created: YYYY-MM-DD
updated: YYYY-MM-DD
sources: []
---

# Design: [Title]

## Visual Structure
...

## Encoding Decisions
...

## School-Specific Elements
...

## Typography and Labels
...

## Color System
...

## Rendering Notes
...

## Rendering (optional)
```[ascii/svg/annotated]
...
```
```

## Example Invocation

`/degas-design 0001-napoleon-losses` — designs the visualization for brief 0001.
