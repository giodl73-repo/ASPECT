# Skill: degas-school

**Pipeline position:** Reference — invoked before design when a school needs documentation  
**Produces:** `schools/<slug>.md`

---

## Purpose

Document a visualization school's grammar: its visual vocabulary, principles, constraints, historical exemplars, and key decisions. A school document is the reference a designer consults before working in that school's vernacular, and what reviewers invoke when assessing school fidelity.

## Preconditions

- School name or subject identified (from brief or research)
- School does not yet exist in `schools/` or needs expansion

## Procedure

1. **Identify the school slug.** Kebab-case, short. Check `schools/` for conflicts.

2. **Research the school's foundations:**
   - Historical origin: who founded or formalized it? when?
   - Core claim: what does this school believe visualization is for?
   - Primary exemplars: 3-5 canonical works that define the school

3. **Document the visual grammar:**
   - Visual primitives: what marks does this school use? (bars, lines, pictograms, abstract forms, contour lines...)
   - Compositional rules: how are marks arranged? what relationships are privileged?
   - Encoding conventions: what visual variables carry what types of information?
   - Forbidden moves: what does this school explicitly prohibit or consider failure?

4. **Identify the school's personas:** which of the DEGAS founding personas work in this school? who is the primary voice?

5. **Note adjacent schools:** what schools is this frequently confused with? where does it borrow from? where does it diverge?

6. **Save to `schools/<slug>.md`** with frontmatter.

## Output Format

```markdown
---
slug: school-slug
name: Full School Name
primary_personas: [persona-slug, ...]
adjacent_schools: [school-slug, ...]
created: YYYY-MM-DD
updated: YYYY-MM-DD
---

# [School Name]

## Origin and Claim
...

## Visual Grammar

### Primitives
...

### Compositional Rules
...

### Encoding Conventions
...

### Forbidden Moves
...

## Canonical Exemplars
...

## Adjacent Schools
...
```

## Example Invocation

`/degas-school statistical-graphics` — documents the statistical graphics school in full.  
`/degas-school isotype` — documents the ISOTYPE school.
