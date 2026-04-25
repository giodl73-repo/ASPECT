---
work: 0024-descartes-geometry
stage: design
---

# Design Description — La Géométrie Diagrams (1637)

## Physical Description

The diagrams in *La Géométrie* are engraved figures accompanying the mathematical text, printed on the same pages as the algebraic notation. Each diagram is relatively small (typically 30-80mm in its largest dimension), without decorative borders or frames. The diagrams are embedded in the flow of mathematical argument: Descartes refers to specific lettered points (A, B, C, ...) in the text and the figures.

The figures are executed in the standard convention of 17th-century mathematical engraving: thin black lines on white paper, labeled with uppercase letters, no shading, no color, no decorative elements. The conventions of Euclidean geometric figures apply throughout.

## Types of Diagrams in La Géométrie

**Type 1 — Unit construction diagrams:**
These show how to establish a unit length (an arbitrary segment designated as 1) and then construct other segments whose lengths correspond to algebraic products, quotients, and roots. The key diagram shows a right triangle with the hypotenuse as the unit, and a perpendicular from the right angle to the hypotenuse — a classical Euclidean construction now given the interpretation: if the two segments of the hypotenuse are a and b, and the altitude to the hypotenuse is c, then c^2 = a × b (the geometric mean is the algebraic product).

**Type 2 — Equation solution diagrams:**
These show how to construct the solutions to algebraic equations using Euclidean tools (ruler and compass). For a quadratic equation, Descartes shows a semicircle construction that geometrically locates the roots. For higher-degree equations, different construction methods are shown.

**Type 3 — Curve-equation correspondence diagrams:**
These are the most radical: they show a curve (e.g., a parabola, a conic section) alongside the algebraic equation that defines the relationship between a point on the curve and a reference line. This is the closest Descartes comes to what we now call a coordinate axis — a reference line from which distances are measured and assigned algebraic values.

## Visual Variable Inventory (Bertin analysis)

| Visual variable | Use | Data type |
|----------------|-----|-----------|
| Position | Geometric relationships — the relative positions of points define the construction | Relational (geometric) |
| Size (segment length) | Algebraic quantity — a longer segment represents a larger algebraic value | Quantitative (relative to unit) |
| Shape (point, line, curve, circle) | Geometric element type | Nominal |
| Orientation | Direction of lines and curves | Nominal/relational |
| Labels (A, B, C, ...) | Element identity — connects diagram to text argument | Nominal |

As in Euclid (work 0018), these variables operate under the demonstrative encoding contract: position is relational (geometric relationship), not geographic; size is relative (geometric proportion), not absolute. Standard visual variables are reassigned for the demonstrative context.

## The New Primitive: The Unit Segment

Euclid's diagrams are purely geometric: lengths are equal, greater, or less, but they are not assigned numerical values. Descartes introduces the unit segment — an arbitrary segment designated as "1" — which allows lengths to be assigned numerical values and algebraic operations to correspond to geometric constructions.

This is a genuine extension to the school's grammar: a new primitive that Euclid does not have, introduced by Descartes and declared in-work (Book I of *La Géométrie* opens with the unit segment construction). The declaration satisfies Step E1 (logical foundation): the new primitive is stated before it is used.

## Encoding Mode: Demonstrative

Like Euclid, Descartes's diagrams are demonstrative: the diagram IS the argument; the viewer verifies by following the construction. Algebraic equations and geometric constructions are both demonstrations — neither requires external data correspondence.

However, Descartes makes a claim that Euclid does not: that algebraic operations and geometric constructions are equivalent. This is not a purely geometric claim; it is a correspondence claim. The diagram must demonstrate that the geometric construction produces the same result as the algebraic operation. This is Step E3 (logical validity): does the construction actually demonstrate what it claims to demonstrate?

In Euclid, the correspondence is between a construction and a geometric property (e.g., the triangle is equilateral). In Descartes, the correspondence is between a construction and an algebraic value (e.g., this segment has length equal to the product a × b). The algebraic dimension adds a layer of verification that Euclid's purely geometric demonstrations do not require.

## Comparison to Euclid (Work 0018)

| Property | Euclid | Descartes |
|----------|--------|-----------|
| School type | Type B (founding) | Type A (school member, extending) |
| Epistemic mode | Demonstrative | Demonstrative (with algebraic correspondence claim) |
| Primary primitive | Point, line, circle | Point, line, circle + unit segment |
| Correspondence claim | Geometric property | Geometric-algebraic equivalence |
| Step E1 (premises) | Established by prior propositions and postulates | Unit segment declared in-work; algebraic rules assumed known |
| Step E2 (completeness) | High (most steps shown) | Moderate (algebraic steps assumed from algebra; not re-demonstrated) |
| Step E3 (validity) | High for classical propositions | High for geometric constructions; moderate for algebraic correspondence |
| Grammar declaration | Traditional, undeclared | New primitive declared; correspondence claim demonstrated |

The key difference: Descartes assumes algebraic rules (commutative, associative, distributive laws, etc.) without demonstrating them geometrically. He bridges algebra and geometry but does not derive algebra from geometry. A viewer who does not know algebra cannot follow all of Descartes's arguments even with the diagrams. This is a Step E2 gap: some argument steps are left for the viewer to supply (from prior algebraic knowledge).
