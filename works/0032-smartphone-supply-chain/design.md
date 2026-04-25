---
work: 0032-smartphone-supply-chain
title: Global Smartphone Supply Chain
school: schematic-cartography
type: A (School Member)
rubric_version: v1.11
created: 2026-04-23
---

# Design Specification — 0032 Global Smartphone Supply Chain

## Canvas

Landscape orientation, 90 x 55cm. Five stage columns reading left-to-right:

**EXTRACTION | PROCESSING | COMPONENTS | ASSEMBLY | MARKET**

Each column is approximately 15cm wide; gaps between columns are 3cm. Nodes are placed within columns; lines connect nodes across columns following the Beck grammar (horizontal, vertical, and 45-degree angles only).

## Stage Anchors (Geographic Anchor Problem Solution)

The five stage column headers are the primary organizational axis. They are not geographic — they are industrial. Nodes within each stage column are identified by country/region name as a label, but their position within the column is determined by which material line(s) flow through them, not by geographic position.

This is the explicit solution to work 0013's geographic anchor problem: there is no geographic reference at all. Position encodes stage and material flow; geography is a node label only.

## Six Material Lines

Each material is a horizontal flow line, color-coded:

| Material | Color |
|----------|-------|
| Lithium | Cyan (#00BCD4) |
| Cobalt | Orange (#FF7043) |
| Rare Earth Elements | Purple (#9C27B0) |
| Silicon | Yellow-green (#8BC34A) |
| Aluminum | Blue (#1565C0) |
| Copper | Brown (#795548) |

Lines run horizontally across the five stage columns. Where a single node handles multiple materials (e.g., China's rare earth processing handles both REE mining and processing; an assembly plant handles all materials), lines converge at that node, branch, and continue.

## Node Design

Nodes are circles (15mm diameter). Color: white fill with the circle border colored by the stage:
- Extraction: dark gray border
- Processing: blue border  
- Components: green border
- Assembly: orange border
- Market: light gray border

Node label: country/region name, 8pt, centered below the circle. A small number inside the circle indicates how many material lines flow through this node (1-6).

**Critical node identification:** Nodes through which 4+ material lines converge are marked with a red fill (chokepoint nodes). These are the supply chain vulnerability points. The red fill makes chokepoints immediately visible as a gestalt pattern.

## Key Topology

**Extraction nodes** (left column): Chile (lithium, copper), DRC (cobalt), Inner Mongolia/China (REE), Saudi Arabia/global (silicon), Jamaica/Australia/Guinea (aluminum), Peru/Zambia (copper).

**Processing nodes**: China handles REE processing for nearly all global rare earth output; lithium processing is split between China and Chile; cobalt processing is primarily Belgium and China; silicon processing (polysilicon) is primarily China (60%+ share).

**Component nodes**: Taiwan (semiconductors — dominant for advanced chips), South Korea (memory chips, display), Japan (camera modules, sensors), China (PCBs, batteries).

**Assembly nodes**: China/Vietnam/India (majority of smartphone assembly, all requiring most materials).

**Market nodes**: USA, EU, China-domestic, India, rest-of-world.

## The Convergence Pattern (Gestalt Argument)

The visual structure reveals immediately: all six material lines converge at China's processing/component nodes. The assembly column shows near-total convergence at China/Vietnam/India. The supply chain's topology shows extreme geographic concentration at the middle stages — this concentration is the vulnerability argument, made visible as a network topology.

The chokepoint nodes (red fill) cluster in the Processing and Components columns. This is the argument without text: the supply chain's most vulnerable stages are the invisible middle stages, not the visible end stages (mining or retail).

## Beck Grammar Compliance

- Lines run at 0, 45, and 90 degrees only — no arbitrary angles
- Stage columns are the "line" identity anchors (analogous to Beck's underground lines)
- Material colors are the primary navigation variable (analogous to Beck's line colors)
- Nodes (stations) are consistently marked with circles and labeled
- Interchange markers: nodes where multiple material lines converge are visually marked (border weight increases, material count shown inside circle)
- The diagram represents topology (supply chain stage relationships and material flows), not geography

## The Geographic Anchor Problem Solved

Work 0013's problem: one geographic anchor created confusion about whether other positions were geographic or topological. This work's solution: zero geographic anchors. Stage headers are the only positional reference. Country names appear as node labels but position does not encode geography. Declaration in the subtitle: "Positions indicate supply chain stage, not geographic location. Country names are node labels only."

This declaration makes explicit what Beck's original Underground map left implicit: the grammar operates on topological, not geographic, position.

## Source Declaration

Supply chain data: Benchmark Mineral Intelligence (battery materials), USGS Mineral Commodity Summaries 2023, Semiconductor Industry Association 2023 Factbook, IEA Critical Minerals 2023.
