# Skill: degas-brief

**Pipeline position:** Stage 1 — before design  
**Produces:** `works/NNNN-slug/brief.md`

---

## Purpose

Define a visualization problem clearly enough that design can begin. A brief names the data or story to be shown, the intended audience, the school to work in, and the constraints on the work. A well-formed brief is the contract between intent and execution.

## Preconditions

- User has a visualization problem or topic in mind
- A school has been identified or will be selected during briefing

## Procedure

1. **Assign a work number and slug.** Count existing `works/` directories; next number is N+1. Slug is 2-4 words from the subject, kebab-case. Create `works/NNNN-slug/`.

2. **Draft the brief** with these sections:

   ### Subject
   What is being shown? State the data source or narrative subject precisely. If data: what variables, what time range, what population? If narrative: what event, what argument, what story?

   ### Audience
   Who will see this? What is their background and visual literacy? In what context will they encounter the visualization (print, screen, exhibition, report)?

   ### School
   Which visualization school applies? If multiple schools are candidates, name them and state which is primary. Consult `schools/` for documented school grammars. If the school is new, note that a school definition will be needed before design.

   ### Core Message
   State the single most important thing the visualization should communicate. A viewer who sees only the first impression of the work should carry this away.

   ### Constraints
   - Format: dimensions, medium, color availability
   - Complexity ceiling: how much can the intended audience process?
   - What must be included? What is explicitly out of scope?

   ### Open Questions
   List anything that needs resolution before design can proceed.

3. **Write frontmatter** and save to `works/NNNN-slug/brief.md`.

## Output Format

```markdown
---
work: NNNN-slug
stage: brief
school: school-slug
author: human (or persona-slug if AI-generated)
rubric_version: v1.0
created: YYYY-MM-DD
updated: YYYY-MM-DD
sources: []
---

# Brief: [Title]

## Subject
...

## Audience
...

## School
...

## Core Message
...

## Constraints
...

## Open Questions
...
```

## Example Invocation

`/degas-brief` — prompts for subject, audience, school; produces brief.md in the next numbered work directory.
