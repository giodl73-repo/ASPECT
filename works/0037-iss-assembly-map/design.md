---
work: 0037-iss-assembly-map
stage: design
rubric_version: v2.0
created: 2026-04-23
---

# Design Notes — 0037 ISS Assembly Map

## Visual Grammar

Node-connection diagram with four encoded variables:

| Variable | Encoding | Data type |
|----------|----------|-----------|
| Module identity | Node label (module name) | Nominal |
| Construction sequence | X-position (left = earlier) | Ordered |
| Launch year | Y-position (top = 1998, bottom = 2024) | Ordered-quantitative |
| Module mass | Node size (area proportional to mass) | Quantitative |
| Country of origin | Node fill color | Nominal |
| Docking sequence | Connection line | Ordered (arrow direction) |

## Node Design

Each node is a rounded rectangle. Width scales with module mass (minimum width = smallest module; maximum width = largest module — Zarya, 19,323 kg). Height is fixed. Text label is the module's common name (e.g., "Zarya," "Destiny," "Kibo").

The five country colors:
- United States: #1E3A8A (deep blue)
- Russia: #8B0000 (deep red)
- Japan: #166534 (deep green)
- ESA: #854D0E (amber/gold)
- Canada: #B45309 (orange)

## Connection Logic

Connections represent docking sequence: an arrow from Module A to Module B means Module B was docked to Module A (or to a module already connected to Module A) in the assembly sequence. The arrow direction is the docking order; the connection is not a physical adjacency (the ISS's physical layout is different from its construction sequence).

## Meta-Visualization Structure

The ISS assembly was planned using node-connection diagrams: mission planning tools use network diagrams to show docking sequences, dependency chains, and assembly constraints. The visualization uses the same grammar — nodes as units, connections as docking relationships — that the ISS's own mission planners used.

This creates a self-referential structure: a node-connection diagram about the assembly of a system that was designed using node-connection diagrams. The informed viewer (an aerospace engineer, ISS mission planner, or space history scholar) will recognize this recursion. The general viewer will not — they will read the node-connection diagram as a node-connection diagram, which is still the correct primary reading.

## Legibility Decisions

The diagram is laid out so that the ISS's major phases are visually distinct: the initial Russian core (Zarya, Zvezda — leftmost, 1998-2000); the US truss and lab additions (Destiny, Unity — center-left, 2001-2006); the international science modules (Columbus, Kibo, Poisk — center, 2007-2010); the final extensions (Nauka, Prichal — rightmost, 2021-2024). This phase structure is emergent from the encoding (chronological X-position + country color), not separately declared — but it is visually clear.
