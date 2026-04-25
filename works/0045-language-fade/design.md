---
work: 0045-language-fade
stage: design
school: data-art
review_type: original
rubric_version: v2.2
created: 2026-04-23
---

# Design Description: Language Endangerment as Visual Fade

## Visual Structure

**Overall composition:** A large field (recommended: 80cm x 100cm for wall display; or full-browser web display). Background: deep black or near-black (#0a0a0a).

**Marks:** 7,168 small circles, each representing one living language in the UNESCO dataset. Arranged by geographic region using approximate geographic coordinates (not a strict map projection, but a spatially-ordered field that preserves continental adjacency).

**Encoding system:**

| UNESCO Status | Mark Opacity | Mark Radius | Color |
|--------------|-------------|-------------|-------|
| Safe | 100% | 3px | #e8d5b7 (warm cream) |
| Vulnerable | 70% | 2.5px | #c4a882 |
| Definitely endangered | 45% | 2px | #9a7b5a |
| Severely endangered | 20% | 1.5px | #6b5030 |
| Critically endangered | 8% | 1px | #3d2a15 |
| Extinct (reference traces) | 3% | 0.75px | #1a0f05 |

**Typographic elements:**
- Title: "7,168 languages. 3,000 will not survive this century." (Large, centered, white text — reversal on dark ground)
- Regional labels: faint white text at approximate continent centers
- UNESCO source note: small, bottom-right

**The visual effect:**
At arm's length, the viewer sees a field of marks, densest in Asia-Pacific and Sub-Saharan Africa (where language density is highest), sparse in North America and Europe. Large blank spaces and near-invisible clusters mark regions of high endangerment — the Caucasus, Northern Australia, the Pacific Northwest, parts of Central America.

The extinction traces — the lowest opacity marks — are ghosts. They are positioned at where languages were spoken but are now silent. The viewer who looks closely enough finds marks that are nearly invisible. The marks are still present; the data is not suppressed. But the visual effect is of absence.

## The Absence-as-Encoding Question

This is the central design decision that the panel must evaluate. Opacity encoding endangerment means that the most critical data (critically endangered languages) is displayed with the least visual prominence. This is the inverse of normal statistical-graphics convention (important data should be visually prominent).

The defense: the fade IS the argument. A language being critically endangered means it is nearly gone — nearly invisible in the world. Encoding that near-invisibility as visual near-invisibility is not the suppression of data; it is the faithful representation of the real-world condition. The encoding is honest: the mark is still present; its faded state represents the language's faded state.

The challenge: Tufte's criterion — are these faded marks data or chartjunk? They are data marks that have been made harder to see. In standard statistical-graphics, making data marks harder to see is a Legibility failure. In data-art, it can be an argument.

## Narration Mode

Standalone. The work must explain itself without accompaniment. The title carries the number and the forecast. The opacity gradient must be accompanied by a legend. The legend distinguishes this from pure aesthetic fading.
