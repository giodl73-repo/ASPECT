---
work: 0037-iss-assembly-map
title: International Space Station Assembly Map (1998–2024)
school: information-architecture
type: A (School Member) — with meta-visualization layer
rubric_version: v2.0
created: 2026-04-23
---

# Brief — 0037 ISS Assembly Map

## The Argument

The International Space Station was assembled in orbit between 1998 and 2024 in 42 missions, adding 16 pressurized modules and supporting structures contributed by the United States, Russia, Japan, Europe, and Canada. The assembly was not planned as a single design but as a sequence of decisions made over 26 years, each constrained by the previous. The visualization makes the ISS's design history visible as an information-architecture system map.

The meta-level argument: the visualization is itself a node-connection diagram — the same visual grammar used by the ISS's own assembly plans, docking diagrams, and mission planning tools. A visualization of an assembly sequence that uses the grammar of assembly sequence documentation is self-referential. This is Cluster S territory.

## Design Approach

Information-architecture system map. Each ISS module is a node. Connections show docking order (chronological, not spatial). Node size encodes module mass (kg). Color encodes country of origin (US: blue; Russia: red; Japan: green; ESA: yellow; Canada: orange). Reading direction: left to right encodes chronological construction sequence; vertical position encodes launch year (top: 1998; bottom: 2024).

Key design decisions:
- Docking connections (not physical adjacency): the diagram shows the order in which modules were attached, which is the ISS's assembly logic — not the ISS's physical layout (which would be a different diagram)
- Mass as size: the largest modules (Zvezda, Destiny, Columbus) are visually prominent; the smallest (PMA adapters, short truss segments) are appropriately small
- Country color: the ISS's international political structure is immediately legible from the color map
- Year as vertical position: the 26-year construction timeline is encoded in the Y-axis without requiring any animation

The meta-visualization question: does using an assembly-sequence diagram grammar to document an assembly sequence create a Resonance bonus (the informed viewer recognizes the recursion) or a Legibility cost (the recursion confuses the primary reading)?

## Panel Configuration

- Bertin (30%) — visual variable grammar, encoding audit
- Tufte (25%) — economy, data density, information architecture
- Kandinsky (20%) — composition, internal consistency, meta-level
- Historian (15%) — school fidelity, precedent, ISS history accuracy
- Audience (10%) — comprehension, first-time encounter

## Score Target

80-86. Self-referential grammar creates Resonance bonus for domain viewers; some Legibility cost from the meta-level for general audience. Strong School Fidelity and Execution.

## Innovation Target

Confirm Cluster S by testing whether the self-referential grammar question (work 0028: the DEGAS rubric visualized as a system map) applies in a different domain (ISS assembly).
