---
work: 0032-smartphone-supply-chain
title: Global Smartphone Supply Chain
school: schematic-cartography
type: A (School Member)
rubric_version: v1.11
created: 2026-04-23
---

# Brief — 0032 Global Smartphone Supply Chain

## The Story

A smartphone contains lithium from Chile, cobalt from the DRC, rare earth elements from China, silicon from polysilicon plants in multiple countries, aluminum from bauxite mines globally, and copper from Chile, Peru, and Zambia. These materials flow through processors, component manufacturers, assembly plants, and logistics networks before reaching consumers. The topology of this supply chain — who depends on whom, where the chokepoints are, which nodes are irreplaceable — is the real data.

## Design Approach

Beck grammar applied to a supply chain network. No geographic base — the topology is the argument, not the geography. Six "lines" (each a material: lithium, cobalt, rare earths, silicon, aluminum, copper), flowing from source nodes (mines by country) through processing nodes to component nodes to assembly and then to market nodes.

## The Geographic Anchor Problem

Work 0013 (schematic-science-network) was penalized for the "one geographic anchor" problem: a schematic diagram that provided one geographic reference point created confusion about whether other positions were geographic or topological. This work must solve that problem explicitly: either provide no geographic anchor, or provide an industry/stage anchor instead.

## Solution

Replace geographic anchors entirely with stage anchors. Each column of the diagram represents a supply chain stage: EXTRACTION | PROCESSING | COMPONENTS | ASSEMBLY | MARKET. Geographic information (country names) appears as node labels within these stage columns, but position within a stage column is not geographic — nodes within a column are arranged by material flow (top to bottom by material line).

## Panel Configuration

- Beck (30%) — schematic grammar, topological representation, stage anchor solution
- Bertin (25%) — visual variable audit
- Tufte (20%) — data economy
- Nightingale (15%) — argument about supply chain vulnerability
- Audience (10%) — comprehension for policy audience
