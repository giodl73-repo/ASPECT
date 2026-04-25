---
slug: mathematical-proof-visualization
name: Mathematical Proof Visualization
primary_personas: [bertin, kandinsky]
adjacent_schools: [abstract-art, scientific-illustration, information-architecture]
founded: ~300 BCE
founder: Euclid of Alexandria (canonical formalization); Descartes extended to analytic geometry (1637)
canonical_works: [0018-euclid-elements]
---

# Mathematical Proof Visualization

## Origin and Claim

Euclid's *Elements* (~300 BCE) establishes the template: geometric diagrams that prove mathematical claims by construction. The school's founding claim: some truths can be shown rather than stated. A diagram that constructs an equilateral triangle on a given line segment does not represent a triangle — it IS the proof that such a triangle exists and can be constructed. The viewer verifies the claim by following the construction, not by checking correspondence to external measurement.

This is the deepest founding act in the project: a school whose grammar encodes logical necessity, not empirical description.

## Visual Grammar

### Primitives
- **Point**: a location with no dimension; labeled with a capital letter (A, B, C)
- **Line segment**: the connection between two points; finite; labeled by its endpoints (AB)
- **Circle**: all points equidistant from a center; defined by center and radius
- **Angle**: the figure formed by two rays from a common point
- **Construction arc**: the trace of a compass operation; a visible construction aid, not part of the proved figure

### Compositional Rules
1. **Construction precedes proof**: every element that appears in the diagram is placed by a valid construction step; nothing appears without construction justification
2. **Construction aids vs. proved figure**: marks used during construction (arcs, construction lines) are visually distinguished from the proved figure; the reader must be able to identify what has been proved
3. **Diagrammatic convention declaration**: the rules under which the diagram operates (which moves are permitted: ruler and compass only; no measurement; no approximation) are established by the school's conventions and should be noted for readers unfamiliar with the tradition
4. **Generality through particularity**: the diagram shows one specific instance (one particular triangle) but proves a general claim (all triangles of this type); the reader must understand the instance as representative
5. **Necessary sufficiency**: every mark in the diagram must be necessary for the proof; marks that are not used in any step of the argument are diagrammatic excess

### Encoding Conventions
- **Position**: absolute within the diagram; not quantitative (the proof does not depend on specific measurements)
- **Label**: capital letters identify points; labels are part of the formal argument
- **Construction arc**: typically drawn lighter or in a different style from the proved figure
- **Shading**: used occasionally to indicate the proved region (e.g., the proved triangle)

### What "Data Integrity" means here (Rubric Step E — Demonstrative)
For demonstrative works, Steps A–D do not apply. Apply Steps E1–E4:
- **E1 (foundation)**: are the premises clearly established? (prior propositions, postulates)
- **E2 (completeness)**: does the diagram show all construction steps?
- **E3 (validity)**: does the construction actually prove what it claims? (logical gap check)
- **E4 (convention declaration)**: are the diagrammatic rules (ruler and compass only) stated or well-established by context?

### Forbidden Moves
- Measurement-dependent arguments (a proof that depends on specific numerical dimensions is not a geometric proof)
- Marks that appear without construction justification
- Construction aids indistinguishable from proved figure
- Assuming what is to be proved (circular construction)

## Canonical Exemplars (DEGAS project)
- 0018 Euclid (86.8): Elements Propositions I.1–I.5; highest Precision score in the project (15/15 unanimous); Cluster I confirmed

## Grammar Declaration
The Euclidean grammar was not declared on the diagrams themselves — it is transmitted through the surrounding text (the propositions, the construction steps, the QED). The grammar is in the tradition, not in the image. Under rubric J modifier: adjacent-documentation declaration (the text declares the proof steps).

## Successor works
- Descartes's Geometry (1637): extends the grammar to analytic geometry — algebraic operations given geometric interpretation
- Newton's Principia diagrams (1687): classical mechanics proved geometrically
- Contemporary mathematical figures: proof-by-picture (valid for some combinatorial arguments), commutative diagrams (category theory)

## Adjacent Schools
- **Abstract art**: both use marks with formal meanings independent of external reference; abstract art encodes compositional properties; mathematical-proof encodes logical relationships
- **Information architecture**: both represent structural relationships; mathematical-proof uses construction logic; information architecture uses system relationships
- **Scientific illustration**: both render with precision; scientific illustration renders empirical forms; mathematical-proof constructs logical forms
