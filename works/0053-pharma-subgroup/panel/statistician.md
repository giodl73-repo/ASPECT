---
reviewer: statistician
work: 0053-pharma-subgroup
weight: 0.15
rubric_version: v2.2
---

# Statistician Review — 0053 Pharmaceutical Subgroup Forest Plot

I will audit this work as a statistician, because this case is the most statistically interesting in the cluster.

**The multiple comparisons problem.** If a trial tests 20 subgroups at p<0.05, we expect approximately 1 false positive by chance alone — even if the drug has zero effect. The >65 age group analysis is one subgroup from an unstated number of post-hoc analyses. Without Bonferroni correction or pre-registration, the reported p-value of 0.02 carries no interpretable weight as evidence of true effect.

**The primary endpoint hierarchy.** In clinical trial design, the primary endpoint is pre-specified precisely because it has priority in interpretation. It is the analysis with a priori statistical power (the trial was sized for it) and protected Type I error. The subgroup analysis is post-hoc, not powered, not controlling multiple comparisons, and not pre-specified. The primary endpoint (HR 0.94, p=0.23) is the correct answer to "does this drug work?" The subgroup finding is, at best, a hypothesis for a future study.

**What the forest plot should show:** A responsible forest plot of TRIAL-X would show the primary endpoint prominently, labeled as primary, with the subgroup analyses shown in standard weight and labeled "exploratory" or "post-hoc, uncorrected for multiple comparisons." The CI for the overall finding crosses the null; that is the finding.

**What this forest plot shows:** The subgroup finding is highlighted; the primary endpoint is one line among many; the accompanying text presents the subgroup as the result. A physician who reads the text and notes the highlighted row without carefully reading all lines would conclude: "this drug works in patients over 65."

**The Integrity score.** I give this work more Integrity credit than 0051 or 0052 because the primary endpoint IS shown and the data is real. But the analytical frame selection produces a false impression that is functionally equivalent to false reporting, for the ordinary reader. The rubric should name this.

| Dimension | Score | Notes |
|-----------|-------|-------|
| School Fidelity | 15/20 | Forest plot grammar correctly applied; the subgroup analysis is a real statistical form |
| Integrity | 8/20 | Primary endpoint shown (credit); post-hoc status undisclosed; primary/secondary hierarchy inverted; multiple comparisons not corrected; Q2 (accuracy tradeoff undeclared) and Q3 (analytical framework undeclared) both fail |
| Legibility | 13/15 | Highly legible; the highlighted finding reads as the primary result |
| Execution | 14/15 | Clean execution; professional production |
| Resonance | 11/15 | Effective; achieves clinical impression |
| Purpose | 5/15 | The statistical presentation prevents physicians from correctly weighting the evidence |
| **TOTAL** | **66/100** | |
