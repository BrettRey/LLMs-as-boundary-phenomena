# Source hook: Hu et al. (2026), the LLM conflict-task study
<!-- SUMMARY: mechanistic in-weight vs in-context competition evidence (Stroop-style) from the Sripada-Lewis lab; new integration-side evidence for the capacity/integration distinction · status: filed 2026-08-14, uncited · updated: 2026-08-14 -->

**Source:** Hu, X., Angstadt, M., Storks, S., Huang, Z., Taxali, A., Weigard, A., Lewis, R. L.,
& Sripada, C. 2026. Conflict and congruency effects in large language models: In-weight and
in-context competition in a verbal conflict task. arXiv:2608.11510 (posted ~2026-08-10).
On disk: `literature/hu-etal-2026-llm-conflict-congruency-stroop.pdf` + `.md`.

**Why this project cares.** The empirical companion to the Sripada & Lewis convergence paper
(their ref 54; see [[sripada-lewis-2026-cognitive-convergence]] hook). A verbal-only conflict
task where an in-weight default (same-color completion) competes with an in-context rule:
Gemma-2-2B and six Pythia models (410M–12B) show congruency effects, and causal attribution
plus attention ablations separate a short-range pathway carrying the automatic response from a
long-range pathway carrying the rule. This is mechanism-level, intervention-backed evidence on
the *integration* side of the paper's capacity/integration distinction ~-- the side
main.tex:90 currently supports only with von der Malsburg & Padó's partial-divergence finding.
It cuts the other way: processing-level convergence, not just capacity-level.

**Use with care.** One task family, small open models, no frontier models; and reproducing a
congruency effect shows shared functional organization at one grain, not shared implementation.
The projection-purpose analysis should say which projection this evidence feeds (functional/
mechanistic-organization) rather than treating it as settling the cluster question.

**Before citing.** Preprint, v1; no venue yet. Suggested key `hu2026ConflictCongruency`; not in
any bib.
