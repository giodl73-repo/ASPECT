# Skill: degas-handoff

**Pipeline position:** End of session — always  
**Produces:** `docs/handoff/YYYY-MM-DD-<slug>.md`

---

## Purpose

Create a resume point before context clears. The handoff contains everything needed to continue work in the next session without re-reading the full project. The next session begins by reading the latest handoff, not CLAUDE.md or TRACKER.

## Preconditions

- End of a substantive working session
- At least one work has been touched or a significant design decision has been made

## Procedure

1. **Identify the active or most recently touched work** (slug + number).

2. **Snapshot the session:**
   - What was accomplished this session?
   - What stage did the active work reach? (brief / design / panel / complete)
   - What rubric version is current?
   - Were any innovations logged? Any amendments ratified?

3. **State open items:**
   - What remains to be done on the active work?
   - Any open questions in the brief or design that need resolution?
   - Any cluster candidates in INNOVATIONS.md that haven't been acted on?

4. **Rank next priorities** (top 3):
   - Ordered by urgency and dependency

5. **Write the handoff file** to `docs/handoff/YYYY-MM-DD-<work-slug>.md`.

6. **Update TRACKER.md** with current rubric version and works status.

## Output Format

```markdown
---
handoff_date: YYYY-MM-DD
active_work: NNNN-slug
rubric_version: v1.X
---

# Handoff: YYYY-MM-DD — [Work Title]

## Session Summary
[2-3 sentences: what was accomplished]

## Active Work Status
- Work: NNNN-slug
- Stage reached: [brief | design | panel | complete]
- Gate status: [PASS / ADVISORY / FAIL / not yet paneled]

## Open Items
- [ ] [specific thing to do next on this work]
- [ ] [open question needing resolution]
- [ ] [cluster candidate, if any]

## Top 3 Priorities for Next Session
1. [most urgent / blocked thing]
2. [next most important]
3. [longer-horizon item]

## Pool State
- Rubric version: v1.X
- Works completed: N
- Innovations logged: N
- Schools documented: N
```

## Session Resume Protocol

Next session: read the latest `docs/handoff/` file. Report in one sentence: rubric version + active work + top priority. Do not re-read CLAUDE.md, TRACKER.md, or school/persona files unless specifically needed.

## Example Invocation

`/degas-handoff` — produces handoff for the current session, names the most recent active work.
