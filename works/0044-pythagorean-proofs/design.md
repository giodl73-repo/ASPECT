---
work: 0044-pythagorean-proofs
stage: design
school: mathematical-proof-visualization
review_type: canonical-import
historical_author: Euclid; Chinese Chu-pei tradition
historical_date: c.300 BCE (Euclid); c.200 CE (Chu-pei)
rubric_version: v2.2
created: 2026-04-23
---

# Design Description: Two Pythagorean Proofs

This design document covers both proofs for comparative scoring.

## Proof A: Euclid (Elements I.47, "Bride's Chair")

**Visual structure:** A right triangle ABC with the right angle at C. Squares constructed externally on each of the three sides: ABDE (hypotenuse), BCFG (one leg), ACKH (other leg). From C, a line parallel to BD meets AB at L, creating two rectangles within ABDE. The key argument: the area of rectangle ABLM equals the area of square BCFG (proved through triangle congruence AEB = ABC, then rectangle-triangle area relationship). Similarly for the other half.

**Construction steps required:** ~10 steps minimum (construct three squares; draw the altitude line; establish two sets of triangle congruences; apply twice-rectangle = area-of-square lemma; sum).

**E1 (Foundation):** Requires Euclid's prior work — specifically propositions I.35 (parallelograms on equal bases), I.38 (triangles on equal bases), SAS congruence. These are stated in Elements but must be imported.

**E2 (Completeness):** All steps are present in the diagram; the proof is complete by Euclid's own account. Ten construction steps visible.

**E3 (Validity):** The proof is valid. 2,300 years of checking confirm this.

**E4 (Convention):** Euclidean geometry conventions are well established; the operating rules are stated in Elements Book I.

## Proof B: Chinese Chu-pei Rearrangement

**Visual structure:** A square of side (a+b). Inside it, four identical right triangles with legs a and b are placed in the corners, leaving a central square of side c. The central square's area is c squared. Now rearrange the same four triangles: they can be repositioned to leave two squares of side a and side b respectively. The same total area minus the same four triangles equals a squared + b squared = c squared.

**Construction steps required:** 2 visual moves — the initial placement, the rearrangement.

**E1 (Foundation):** Requires only that the viewer accepts: (1) area is preserved under rearrangement; (2) the four triangles have the labeled dimensions. Both are visually verifiable.

**E2 (Completeness):** Two steps, both fully visible. The proof is complete after the second diagram.

**E3 (Validity):** Fully valid. The rearrangement argument is airtight.

**E4 (Convention):** The operating rules are visual and geometric; they require less stated convention than Euclid because the argument relies on rearrangement (verifiable) rather than area-equality lemmas (requires prior propositions).

## The Comparative Question

Does Proof B (simpler, fewer steps, smaller foundation) score higher than Proof A? The E-pathway suggests:
- E1: Proof B requires less foundation — fewer prior propositions
- E2: Both proofs are complete — but Proof A has more steps to verify
- E3: Both valid
- E4: Proof B relies on visually evident conventions; Proof A requires stated Euclidean conventions

Elegance argument: Proof B achieves the same logical conclusion with dramatically less machinery. It is more immediately convincing because the viewer can verify both moves without any prior geometric knowledge beyond area conservation. This makes it more accessible but raises the question of whether "elegance" (fewer steps) is a legitimate scoring criterion or just an aesthetic preference.
