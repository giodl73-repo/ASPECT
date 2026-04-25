# DEGAS Rubric Audit — Persona Panel

**Date:** 2026-04-23  
**Rubric version audited:** v1.12  
**Purpose:** Identify redundancy, restore elegance, preserve rigor  
**Reviewers:** Tufte (30%), Bertin (25%), Nightingale (20%), Playfair (15%), Kandinsky (10%)

---

## Tufte — What to Cut

I am going to be direct. The Data/Story Integrity dimension has become the visualization equivalent of a chart with six legends, three axes, and a watermark. It has six sub-steps and a main anchor table. That is chartjunk in rubric form. I will tell you what each step is actually doing, and then I will tell you how many steps you need.

**Step A** (source quality) and the **variable selection disclosure** embedded in Step A are the same question: *Is the visualization honest about what data it claims to represent?* They are phrased differently, but a reviewer asking "was the uncertainty declared?" and "was the variable selection disclosed?" is asking the same underlying question — disclosure honesty. One step.

**Steps B and C** (accuracy tradeoff and causation) are both asking *Is the visualization honest about its arguments?* One uses form; the other uses inference. The mechanism differs; the ethical question does not. These can be consolidated as "argument integrity."

**Steps D and F** (framework declaration and ontological categories) are both asking *Is the framing honest?* Does the work's conceptual structure — its data model, its categories — honestly represent the reality it claims to represent? Two faces of the same question. Merge them.

**Step E** (demonstrative encoding pathway) is not a sub-step at all. It is a routing instruction: *before you score anything, determine whether this work reports data or demonstrates a claim.* It should live above the dimension, not inside it.

**The three questions I actually need answered for Data/Story Integrity:**
1. Is the data what the work claims it is? (disclosure honesty)
2. Does the argument make only what the data can support? (argument integrity)  
3. Is the conceptual framing — the categories, the framework, the model — honestly presented? (framing integrity)

Three sub-questions. One step each. Then the main anchors.

**For Resonance:** Types I (aesthetic-intentional), II (emergent-data), and IV (gestalt) all ask the same underlying question — does the work create an experience in the viewer? The mechanism differs but the criterion does not. I have scored works under all three and found myself applying the same anchors. Collapse to one type: **Experiential**. Keep III (Advocacy) and V (Domain-gated) as genuinely distinct — they answer different questions (did it move someone to act? is it only available to the initiated?). Make Type VI a timing note, not a type.

**For School Fidelity:** The J modifier (+0 to +1 for declared grammar) adds at most 1 point and requires a separate classification table. Absorb it into the Type B anchor text: "Declared grammars reach the upper end of this band; derivable-but-undeclared grammars reach the middle." Remove the step.

---

## Bertin — The Variable Audit

I will do what I always do: audit what each element is actually encoding, and ask whether two elements encode the same thing.

**The six dimensions: are they orthogonal?**

School Fidelity encodes: *does the work speak the grammar of a visual tradition?*  
Data/Story Integrity encodes: *does the work honestly represent what it claims?*  
Legibility encodes: *can the intended audience read it in context?*  
Visual Economy encodes: *does every mark earn its place?*  
Resonance encodes: *does the work create the intended effect?*  
Craft encodes: *is the execution precise and consistent?*

These are not orthogonal. Visual Economy and Craft are closely coupled. A mark that is imprecisely rendered (Craft failure) is also a mark that is not earning its place (Visual Economy failure). A chart with ragged alignment (Craft) is also a chart where the alignment is adding visual noise rather than communicating (Economy). The two dimensions are measuring the same thing at different resolution.

**Proposal:** Merge Visual Economy and Craft into a single **Execution** dimension (15 pts). Two anchors within it: (a) *Economy of means* — is complexity additive or intrinsic? does every mark earn its place? (b) *Quality of execution* — are the marks precise, consistent, and polished? One dimension, two lenses. This is how a trained designer looks at execution anyway.

**Within Data/Story Integrity:** The six sub-steps are not independent. They share a common structure: *does the work declare what it is claiming?* Whether the claim is about source data (A), variable selection (L embedded in A), argument structure (B, C), analytical framework (D), or category construction (F) — the underlying question is the same. I count three genuinely distinct questions, as Tufte also identifies. Three steps, not six.

**For School Fidelity:** The four separate anchor tables (one per Type A/B/C/D) produce calibration divergence. A work scoring 16 on Type A anchors is not obviously comparable to a work scoring 16 on Type B anchors, because the anchors describe different things. Propose: one unified anchor table (0-20) with Type-specific notes beneath each band. "For Type B founders: within this band, declared grammars score at the upper end." This is how Bertin's visual variable tables work — one property, multiple applications.

---

## Nightingale — The Usability Audit

My question is not whether the rubric is technically correct. It is whether a reviewer who did not write it can apply it and arrive at approximately the same score as a reviewer who did.

The answer, currently, is uncertain. The chained docking tables in Data/Story Integrity produce high inter-reviewer variance. Consider: Step A says dock −2 to −4 for confidence suppression. Step B says dock −3 to −4 for undeclared disproportionate tradeoff. Step C says dock −3 to −4 for significantly overstated causal claim. Step F says dock −5 to −8 for ontologically contaminated categories. A reviewer applying maximum docks to all sub-steps can reach −22 before the main anchors. A reviewer applying minimum docks reaches −4. The resulting scores can diverge by 18 points on the same work.

This is not a rubric. This is a framework for producing the appearance of precision while concealing judgment.

**Proposal:** Replace chained docking tables with a simpler protocol. Each sub-question produces a qualitative answer: PASS / NOTE / DOCK. PASS: no adjustment. NOTE: flag for the SUMMARY but do not dock. DOCK: move one anchor band down. The reviewer exercises judgment at one point (the PASS/NOTE/DOCK decision) rather than at twelve (which dock severity from which range for which sub-step).

**For Legibility:** This dimension has the most successful structure in the rubric. It works because the structure is: *specify context → apply anchors → note divergence in brackets.* This is clear, reproducible, and produces low inter-reviewer variance. The pattern should propagate to every other dimension. Every dimension should have the same shape.

**For Resonance Type VI** (the mechanism matrix): I have applied this in approximately six reviews and have never felt it produced a score that justified its complexity. The matrix (speed × agency) requires knowing the history of the work's reception and classifying it into a 2×4 grid to produce a bonus of +0 to +1. I would note the timing of recognition in the SUMMARY and let the reviewer exercise judgment about its significance. Remove the matrix.

---

## Playfair — The Communicability Audit

I invented the bar chart because proportional comparison should be immediate. The rubric, at present, is not immediate. It is a wall of text that requires sustained reading before the structure becomes visible.

The problem is inconsistency. Each dimension has a different internal structure:
- School Fidelity: Step 0 → Step 0b (only for Type B) → Step 0c → four anchor tables
- Data/Story Integrity: six sub-steps → main anchors  
- Legibility: Step 0 → context sub-types → anchors → narration mode note
- Visual Economy: Step 0a → Step 0b → mark categories → anchors
- Resonance: six types + mechanism matrix + dynamic variable note → anchors
- Craft: anchors (nothing else)

A reviewer cannot develop intuition for the rubric's structure because the structure changes every dimension. The strongest reform would be: **every dimension has the same three-layer structure.**

Layer 1: **Classification** — what type or context is this work, for this dimension? (5-10 seconds to determine)  
Layer 2: **Anchors** — apply the appropriate anchor for this classification. (The scoring decision)  
Layer 3: **Modifiers** — any special circumstances? (Only invoked when relevant)

This is a bar chart logic: the structure is visible immediately, the data fills it, and the viewer knows what they are looking at from the first moment. Write the rubric as you would write a chart: clear structure, then content.

---

## Kandinsky — The Compositional Balance Audit

The rubric has lost its compositional balance. I can demonstrate this with approximate word counts:

| Dimension | Approx. words in rubric | Weight |
|-----------|------------------------|--------|
| School Fidelity | ~550 | 20 pts |
| Data/Story Integrity | ~900 | 20 pts |
| Legibility | ~380 | 15 pts |
| Visual Economy | ~450 | 15 pts |
| Resonance | ~650 | 15 pts |
| Craft | ~80 | 15 pts |

The composition is asymmetric. Data/Story Integrity has ten times the rubric text of Craft, for the same maximum score. Craft is a cold spot — a dimension that has received no amendments despite generating real reviewer disagreements (the Haeckel mark saturation, the Berezina registration failure, the HOLC chromolithography quality). Craft deserves more structure, or it should be merged with a dimension that already has it.

The visual economy of the rubric itself is poor. A well-composed rubric would have consistent weight across its dimensions, with complexity proportional to the genuine complexity of the underlying question. Data/Story Integrity is genuinely more complex than Craft — but ten times more complex? I do not believe this.

**The coherent composition I would propose:**
- Two 20-point dimensions: School Fidelity, Integrity (the merged Data/Story question)
- Four 15-point dimensions: Legibility, Execution (merged Visual Economy + Craft), Resonance, one new dimension

**The new dimension:** What is currently missing from the rubric is a dimension for *stakes and purpose* — does the work take its subject seriously? Does the form serve the function? Is the design for something, or is it merely correct? This connects to the moral weight criterion and to the school-story match question. Currently these float between School Fidelity and Resonance without a clear home. Give them a home: **Purpose** (15 pts).

---

## Convergence — The Five Cuts

All five reviewers converge on the following:

1. **Consolidate Data/Story Integrity** from 6 sub-steps to 3 questions: (a) disclosure honesty, (b) argument integrity, (c) framing integrity. Step E (demonstrative pathway) moves above the dimension as a routing instruction.

2. **Merge Visual Economy and Craft** into a single **Execution** dimension (15 pts), with two lenses: economy of means + quality of execution.

3. **Simplify Resonance** from 6 types to 3: **Experiential** (I+II+IV collapsed), **Advocacy** (III), **Domain** (V). Type VI becomes a timing note in the SUMMARY, not a rubric type.

4. **Standardize the dimension structure**: Classification → Anchors → Modifiers. Every dimension.

5. **Absorb the J modifier** (Type B declared grammar bonus) into the Type B anchor text. Remove as a separate step.

**What to preserve without simplification:**
- School Fidelity Types A/B/C/D — genuinely distinct, well-calibrated
- School-story match (K) — productively differentiated from school execution
- Legibility context specification — the best-structured dimension; model for the rest
- Visual Economy intrinsic complexity (H) — essential; saves Haeckel and Humboldt
- Data/Story Integrity Step F (ontological categories) — cannot be removed; the HOLC maps showed this
- Data/Story Integrity Step E (demonstrative pathway) — move, not remove
- Dynamic variable note (O) — keep as a Legibility + Resonance note

**Proposed new structure:**

| Dimension | Points | Core question |
|-----------|--------|--------------|
| School Fidelity | 20 | Does the work speak the grammar of its claimed school? |
| Integrity | 20 | Does the work honestly represent what it claims to show? |
| Legibility | 15 | Can the intended audience, in the intended context, read it? |
| Execution | 15 | Does every mark earn its place, and is it executed with precision? |
| Resonance | 15 | Does the work create the intended effect? |
| Purpose | 15 | Does the form serve the function? Does the work take its subject seriously? |

Total: 100 pts. Six dimensions. Clean.
