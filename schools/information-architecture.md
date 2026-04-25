---
slug: information-architecture
name: Information Architecture (Systems, Flows, Diagrams)
primary_personas: []
adjacent_schools: [schematic-cartography, statistical-graphics, abstract-art]
founded: 20th century; no single founder
canonical_works: []
---

# Information Architecture

## Origin and Claim

Information architecture encompasses diagrams that represent systems, processes, hierarchies, and flows — org charts, flowcharts, UML diagrams, network diagrams, system maps. Unlike cartography (which represents geographic space) or statistical graphics (which represents quantitative comparison), information architecture represents structural or procedural relationships that have no inherent spatial or quantitative form.

No single founder; the school emerges from engineering drawing, organizational theory, and computer science. Notable practitioners: Edward Yourdon (structured analysis), Gene Zelazny (business charts), current practitioners in UX and service design.

## Visual Grammar

### Primitives
- **Node**: an entity, component, or state; typically a rectangle, circle, or named shape
- **Edge/Arrow**: a relationship, dependency, flow, or transition between nodes
- **Hierarchy**: parent-child relationships typically encoded with vertical position (parent above child) or containment (parent contains child)
- **Flow direction**: left-to-right or top-to-bottom as the primary reading direction for sequential processes

### Compositional Rules
1. **Nodes represent entities; edges represent relationships**: the distinction must be visually clear and consistent
2. **Reading direction declared**: if the diagram encodes sequence, the reading direction (left-to-right, top-to-bottom, clockwise) must be consistent and legible
3. **Hierarchy encoded by position or containment**: vertical position for organizational hierarchies; containment for component hierarchies; avoid mixing
4. **Minimize edge crossings**: crossed edges create visual confusion; layout should minimize crossings where possible
5. **Consistent visual vocabulary**: similar node types look similar; different node types are visually distinguishable

### Encoding Conventions
- **Shape**: node type (process = rectangle; decision = diamond; data = parallelogram — or any consistent bespoke system)
- **Vertical/horizontal position**: hierarchy level or sequence
- **Arrow direction**: relationship direction, flow, causation
- **Color**: category or status (optional; must be consistent)
- **Label**: identity or description of node or edge

### Forbidden Moves
- Mixing node types that look identical (structural ambiguity)
- Undirected arrows where direction matters
- Circular dependencies that are not declared as intentional (they look like errors)
- Diagrams so complex that the structure is invisible

## Status in the project
No canonical works reviewed yet in this school. It is listed in CLAUDE.md as a school and needs a canonical import before the grammar can be validated empirically. Candidates: UML sequence diagrams, Yourdon data flow diagrams, or a systems dynamics stock-and-flow model.

## Adjacent Schools
- **Schematic-cartography**: shares the topology-over-geography principle; schematic-cartography applies it to transit networks specifically
- **Abstract-art**: both work with non-representational visual elements; abstract art encodes formal properties; information architecture encodes structural relationships
