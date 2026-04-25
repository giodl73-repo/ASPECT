---
work: 0012-isotype-plastic-pollution
stage: panel
school: isotype
author: statistician
rubric_version: v1.6
created: 2026-04-23
updated: 2026-04-23
---

# Panel Review — Statistician Lens

## Score Table

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity /20 | — | Not scored by statistician lens |
| Data/Story Integrity /20 | 14 | Step A: source declared; Step B: absolute-only framing is an undeclared accuracy tradeoff of moderate severity; Step C: no causal overclaim; Step D: standard additive model |
| Legibility /15 | 12 | The counting mechanism is clear; rounding convention declared; annotation text legibility failure at scale is a real problem |
| Visual Economy /15 | — | Not scored by statistician lens |
| Resonance /15 | — | Not scored by statistician lens |
| Craft /15 | — | Not scored by statistician lens |
| **Total /100** | — | (Statistician scores Data/Story Integrity and Legibility only) |

## Voiced Review

The data sourcing is adequate: OECD Global Plastics Outlook is a credible source; Jambeck et al. is the foundational academic work; both are declared. The estimates are exactly that — estimates, with uncertainty that is not shown. Ocean plastic input is not a directly measured quantity; it is modeled from waste generation, mismanagement rates, and hydrological inputs. The uncertainty bands on these estimates span ±30-40% in some regional cases. This uncertainty is not visible anywhere in the design.

The rounding convention is the right one. Showing a trace marker (·) for Central Asia rather than zero preserves the information that the value is non-zero; rounding to zero and showing nothing would be a small but real integrity failure. The partial symbol system (▪ for 0.1–0.5, · for trace) is declared and consistent. I am satisfied.

The Step B issue is serious. The design shows absolute ocean plastic inputs. It does not show per-capita plastic production. It does not show plastic waste exports. It does not show waste infrastructure investment. Any one of these additional variables would materially change the moral framing the data supports. The design is aware of this — that is what the annotation panel is for — but the annotation panel cannot be read at the design's intended display scale.

My specific objection: the design presents numbers as if they tell a complete story about regional responsibility, while suppressing (in a technically present but practically invisible annotation) the context that radically changes what responsibility means. Under Step B, this is an accuracy tradeoff that is present but placed where it cannot function. I score it more harshly than if the per-capita context were simply absent — present but inaccessible is worse than absent and declared.

Recommendation: either bring the per-capita comparison into the visual encoding (a second chart), or declare the limitation in the title zone where it is legible at display scale.

## Innovations Flagged

**Innovation #115 — Present-but-inaccessible context as Step B failure**: When a design includes corrective context that materially changes the moral interpretation of the primary visual argument, but places that context in a zone that is physically present but illegible in the design's primary reading context, the Step B accuracy tradeoff is not mitigated — it is performed. The correction is there to satisfy scrutiny without actually reaching the viewer. This is a distinct sub-category of undeclared accuracy tradeoff. Rubric anchor: Data/Story Integrity (Step B).
