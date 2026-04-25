# Skill: degas-review

**Pipeline position:** Stages 1+2 combined — for canonical imports only  
**Produces:** `works/NNNN-slug/brief.md` + `works/NNNN-slug/design.md` in one pass

---

## Purpose

Entry point for reviewing an existing canonical visualization — a historical work or published piece — rather than designing a new one. Combines brief and design description into a single step, since there is no specification to write: only a work to describe.

This is the canonical-import analog to `degas-brief` + `degas-design`. After running this skill, the work proceeds to `degas-panel` as normal.

## When to Use

- Reviewing a historical masterwork (Minard, Nightingale, Playfair, Beck, Neurath, etc.)
- Reviewing a published contemporary visualization
- Studying a canonical work to surface innovations and test the rubric

Do NOT use for DEGAS-originated designs. Use `degas-brief` + `degas-design` for those.

## Preconditions

- The work to be reviewed has been identified
- Sufficient documentation exists to describe the work in detail (reproductions, scholarly analysis, the designer's own writing)
- The work number is the next available in `works/`

## Procedure

1. **Assign work number and slug.** Count existing `works/` directories; slug is 2-4 words, kebab-case. Create `works/NNNN-slug/`.

2. **Write `brief.md`** with these sections:

   - **Subject**: what is being shown; the variables or narrative; the original context
   - **Audience**: original audience + the review audience (always: DEGAS panel)
   - **School(s)**: which schools does this work participate in? Declare ambiguity honestly
   - **Core Question (Review Mode)**: what does this work do that our rubric cannot yet adequately name or score?
   - **Constraints**: what we do and don't have access to (original vs. reproduction, scholarly sources)
   - **Open Questions**: anything the panel should hold as contested

3. **Write `design.md`** — a reverse-engineering description of the actual work:

   - **Visual Structure**: overall form; first impression; figure/ground; the two or more registers if present
   - **Encoding Decisions**: table of data variables → visual variables → why each pairing is or isn't appropriate
   - **School-Specific Elements**: name the techniques from each school the work deploys, using school vocabulary
   - **Typography and Labels**: conventions in use
   - **Color System**: palette and what each color encodes
   - **Rendering Notes**: original medium, dimensions, context of production

4. **Set frontmatter** in both files with `review_type: canonical-import` and `historical_author`.

## Frontmatter Fields (canonical import)

```yaml
---
work: NNNN-slug
stage: brief          # or design
school: school-slug(s)
review_type: canonical-import
historical_author: Name
historical_date: YYYY or YYYY-MM-DD
version_reviewed: specific edition/version being assessed
institutional_divergence: how much the reviewed version differs from the contemporary institutional version (for living artifacts)
author: human         # or claude, for AI-assisted description
rubric_version: v1.6  # always use current rubric version
created: YYYY-MM-DD
updated: YYYY-MM-DD
sources: []
---
```

## Notes on Description Quality

- Write the design description as if you are explaining the work to a skilled practitioner who has not seen it
- State every encoding explicitly, even obvious ones — the panel will audit them
- Where the work's design logic is unclear or contested, say so; don't resolve ambiguities that the panel should surface
- Cite sources for data quality claims

## Example Invocation

`/degas-review 0002-nightingale-coxcomb` — sets up review of Nightingale's 1858 polar area diagram.  
`/degas-review 0003-beck-underground` — sets up review of Beck's 1933 London Underground map.
