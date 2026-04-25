---
reviewer: bertin
work: 0045-language-fade
weight: 0.20
rubric_version: v2.2
---

# Bertin Review — 0045 Language Endangerment as Visual Fade

Let me identify the visual variables in use.

Position: geographic region of language family/origin. Correct use of position for geographic data — position is the most powerful spatial variable.

Size: radius of mark, decreasing with endangerment. Size is a quantitative, ordered variable — correct for encoding an ordered variable (safe > vulnerable > endangered > extinct). The size reduction is in the right direction: smaller = more endangered.

Value (lightness/opacity): decreasing with endangerment. Value is an ordered variable — correct for ordered data. The opacity reduction is in the right direction: less opaque = more endangered.

Color hue: warm cream to near-black. Using hue as an ordered variable is typically a grammar error in my framework. However, in this case, the hue shift is from light warm to near-black, which is effectively a lightness change (value variable) rather than a pure hue change. The shift is from yellow-brown to near-black, which is a warm → neutral color temperature change that accompanies the value reduction. This is not a pure hue encoding; it is a combined value/hue encoding. The grammar is defensible because the ordering is unambiguous: lighter = safer.

The redundancy of size + opacity/value encoding: deliberate and correct. Redundant encoding strengthens the communication when the primary variable (opacity) might be missed. A viewer who does not notice the opacity difference will notice the size difference. Both encode the same thing.

The density-endangerment confound is my primary concern. Position encodes geographic location; but geographic language density varies enormously — Papua New Guinea has ~850 languages in a small area, while Iceland has 1. The spatial distribution of marks therefore encodes both geographic density (confound) and endangerment (argument). A viewer cannot distinguish "few marks here because few languages ever existed here" from "few marks here because the marks are nearly invisible due to high endangerment." This is a genuine encoding ambiguity that the legend must resolve explicitly.

My recommendation: a companion map showing total language count by region (regardless of endangerment status) would allow the viewer to subtract the density baseline from the opacity field, making the endangerment argument visible as the residual.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 17/20 | Data-art Type A; opacity encoding is valid; redundant encoding justified |
| Integrity | 14/20 | UNESCO data honest; but density-endangerment confound is a genuine framing issue — the visual structure implies blank spaces = extinction when some blank spaces = natural sparseness; −4 |
| Legibility | 11/15 | Public display; standalone; density confound requires legend; legend as described is insufficient; −2 for confound ambiguity, −2 for legend insufficiency |
| Execution | 13/15 | Economy high for data-art; opacity and size both functional; no decorative marks |
| Resonance | 13/15 | Advocacy + experiential resonance; the fade is affecting; confound slightly undermines advocacy claim |
| Purpose | 13/15 | Language preservation advocacy; stakes high; confound is a purpose-fidelity gap |
| **TOTAL** | **81/100** | |
