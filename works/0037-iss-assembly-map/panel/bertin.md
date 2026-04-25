---
work: 0037-iss-assembly-map
reviewer: bertin
weight: 0.30
rubric_version: v2.0
---

# Bertin — 0037 ISS Assembly Map

## School Fidelity /20 → 17

I will audit the visual variables. The design uses: X-position, Y-position, node size, node fill color, and connection line (with arrow direction). Let me assess each.

**X-position encoding construction sequence**: position is ordered and quantitative. Construction sequence is ordered. Correct pairing. The most retinally efficient encoding in the diagram — position is read automatically.

**Y-position encoding launch year**: position is ordered and quantitative. Launch year is ordered-quantitative. Correct pairing. X and Y are both positional — using both for two ordered variables creates potential confusion when a module was launched in a different year than its docking sequence implies. Declare any concordance/discordance in the encoding note.

**Node size encoding module mass**: size is quantitative in area. Module mass is quantitative. Correct pairing. The proportionality (area proportional to mass) must be precise — size is a notoriously difficult quantitative variable to read precisely. Consider adding mass labels on the largest nodes.

**Node fill color encoding country of origin**: color hue is selective and associative. Country of origin is nominal. Correct pairing. Five colors for five categories is at the upper limit of discriminable hues but achievable.

**Connection line encoding docking sequence**: ordered connection with arrow direction. Correct pairing.

Overall: four of five variables correctly matched. The X/Y concordance issue for chronological vs. spatial sequence is the one gap.

## Integrity /20 → 17

Reportive: represents historical data (ISS assembly sequence, module masses, launch years, country contributions) — all public record. No integrity issues with data claims.

The critical integrity question: the connections encode docking sequence, not physical adjacency. Without declaration, a reader may assume connections represent physical adjacency (as in most system maps), which they do not. Declare in the figure note: "Connections show docking sequence (chronological order of attachment), not physical adjacency."

## Legibility /15 → 12

For the informed general reader, legibility is good. Country colors are immediately readable; size variation is visible; chronological reading direction follows convention. The meta-level — self-referential grammar — is not legible to a general reader and should not be. The general reader reads the node-connection diagram as a node-connection diagram: the correct primary reading.

Main legibility risk: with 42 missions and 16+ pressurized modules, label legibility at reading distance is the binding constraint. Small module names on small nodes may be illegible without close examination.

## Execution /15 → 13

Five visual variables, all correctly matched, with clean connections and consistent conventions. No decorative elements. The meta-level does not add visual complexity — the diagram looks exactly as it would without the self-referential layer, which is correct.

Economy: every node is a module, every connection is a docking event, every size difference is a mass difference, every color is a country. Maximum economy.

## Resonance /15 → 12

Domain resonance for aerospace engineers and ISS historians is high — they will recognize both the factual content and the self-referential grammar. The meta-level creates a resonance bonus for this audience. For the general viewer, resonance is informational — the diagram tells the ISS's political and engineering history in compact form.

## Purpose /15 → 13

Informational purpose fully served. Country-color encoding makes political structure immediately visible; mass-size shows relative contributions; chronological X-axis shows assembly sequence.

## My Total: 84/100

Strong information-architecture work. The self-referential grammar question confirms Cluster S.

## Innovation Flagged

**#248 — Self-referential grammar as domain resonance bonus**: using the same visual grammar as the subject (an assembly-sequence diagram to document an assembly sequence) creates a domain resonance bonus for viewers who recognize the recursion. The bonus is real and significant for domain experts; absent for general viewers. Cluster S confirmation: the self-referential grammar question from work 0028 applies here with the same structure.
