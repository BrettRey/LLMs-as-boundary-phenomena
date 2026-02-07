# STATUS.md -- LLMs as Boundary Phenomena

**Last updated:** 2026-02-07
**Current phase:** Third revision complete; ready for final read-through
**Target venue:** TBD (philosophy of AI journal, or commentary on Nefdt)
**Collaborators:** None (sole author)

## Progress

- [x] Core argument identified (conversation with Claude, 2026-02-06)
- [x] Primary source read (Nefdt 2026, "What it's like to be an LLM")
- [x] Project folder created
- [x] Outline drafted
- [x] Key sources located and read (Boyd, Cappelen & Dever, Casto et al.)
- [x] First draft
- [x] Simulated review (8 reviewers)
- [x] Revision (post-review, ~185 words added)
- [ ] Final polish
- [ ] Submission

## Genesis

Arose from Brett's email exchange with Geoff Pullum about a pro-LLM Nature paper. Reading Nefdt's "What it's like to be an LLM" revealed that his 2x2 table (Language x Cognition) is a necessary-and-sufficient-conditions framework that HPC theory is designed to replace. The "tomato move" (is LLM reasoning linguistic or cognitive? depends on projection purpose) crystallized the argument.

## Session Log

### 2026-02-06
- Read Nefdt (2026) in full
- Identified core argument: Nefdt's Table 1 is a binary framework; HPC + projection-purpose analysis handles LLMs better
- Three projections identified: neuroscience (linguistic), functional (cognitive), phenomenological (undecidable)
- Connection to Powell's convergence/contingency framework noted
- Project folder created from template

### 2026-02-06 (session 2)
- Symlinked references.bib to centralized .house-style/references.bib
- Added 7 bib entries to centralized file: nefdt2026, cappelen2025, bender2020, casto2025, mahowald2024, nagel1974, powell2020
- Wrote outline in main.tex with 5 sections: Introduction, The binary and its discontents, HPC reframing, The tomato move, Why this matters
- Each section has detailed argumentative notes in comments with word budgets and citation plans
- Fixed Makefile template title
- Added \newpage before \printbibliography (house style)

### 2026-02-06 (session 3)
- Drafted full paper (~1,900 words body text, 5 pages)
- All quotes from Nefdt (2026) verified against PDF with page references
- All 8 citation keys resolve: nefdt2026, boyd1991, boyd1999, bender2020, cappelen2025, casto2025, mahowald2024, nagel1974, powell2020
- House style checker: no violations
- Added PhilPapers URL to nefdt2026 bib entry
- Builds clean with `make`

### 2026-02-06 (session 4, revision)
- Implemented 8 targeted revisions responding to simulated reviews from Boyd, Godfrey-Smith, Heath, McCloskey, Zimmer, Harris, Nefdt, Millikan
- Pre-empted "table as heuristic" objection (Section 2): even heuristic binaries constrain conceptual space
- Acknowledged HPC is contested, citing Magnus (2014)
- Added stakes after tomato analogy: *Nix v. Hedden* (1893), regulation/liability consequences
- Distinguished epistemic hedging from ontological continuity (Section 2)
- Added concession: binary table forces commitment; HPC's flexibility is a risk; claim is narrower
- Softened neuroscience-projection attribution to Nefdt
- Glossed "projection purpose" for readers unfamiliar with Goodman
- Acknowledged etiological gap: natural vs. engineered clustering (Section 3)
- Fixed Section 2 transition ("Consider the evidence" replaces redundant "But")
- Net addition: ~185 words. Still within note scope.
- Builds clean, no style violations

### 2026-02-06 (session 5, Section 5 deep revision)
- Complete rewrite of Section 5's two diagnostic paragraphs
- **Projection-mismatch paragraph:** Reframed as predicate overloading — cognitive predicates serve multiple purposes (predictive accuracy vs. productive engagement) that converge for humans, diverge at LLM boundary. Shanahan foregrounds accuracy (predicates overshoot); Cappelen & Dever foreground engagement (predicates necessary for productive interaction). Section 4's three projections framed as analytical-level instances; Section 5 shows vocabulary-level divergence.
- **Essentialism paragraph:** Replaced Cappelen & Dever with Piantadosi & Hill (2022, "Meaning without Reference in LLMs") for property-selection pairing. B&K and P&H both ask about meaning but essentialize differently (grounding vs. conceptual role). HPC theory diagnoses this as treating a cluster kind as having necessary conditions.
- Framing changed from "obvious/subtler" to "persistence/resolution": first pattern explains why debate persists; second, why disagreements resist resolution
- Key insight (Brett-led): cognitive predicates are overloaded like "noun" for syntacticians vs. semanticists — multiple purposes converge in core cases, diverge at boundaries
- Added piantadosi2022 bib entry (arXiv:2208.02957)
- Added \label{sec:tomato} for cross-reference from Section 5
- Multiple rounds of iteration on Shanahan characterization: from mechanistic deflationism → metalinguistic caution → vocabulary management → predicate overloading
- Lesson: I (Claude) kept describing patterns when I should have been diagnosing them using the paper's own framework. Brett had to lead me to both the predicate-overloading insight and the essentialism diagnosis.
- Builds clean, no style violations, 6 pages

### 2026-02-07 (session 6, third revision)
- **Homeostatic mechanisms paragraph:** Replaced etiological disclaimer with substantive argument. Training as candidate homeostatic mechanism; Huh et al. (2024) on representational convergence as evidence clustering is constrained not stipulated; Khalidi (2013) on etiological kinds. Boyd comparison normalizes incomplete mechanistic story.
- **Category drift paragraph:** HPC kinds aren't static; LLMs reshaping cognitive categories in real time. New selection pressure on cognition cluster. Brett's insight — the entity is reshaping the kinds, not just occupying them.
- **Channeling sentence:** Cluster kinds afford motivated property selection — structural framing, not attribution of bad faith.
- **Source verification:** Downloaded and read B&K 2020 ("Climbing towards NLU") and Bender et al. 2021 ("Stochastic Parrots"). Confirmed B&K 2020 characterization is fair (meaning = form-intent relation, p. 5187). Stochastic Parrots is a different paper not cited in this note.
- **Structural edits:** Cut §5 throat-clearing paragraph; sharpened §5 transition; added subtitle "A comment on Nefdt (2026)"; updated abstract with drift; intro tricolon previewing §5's three moves.
- **Rhetorical polish:** Two humor lines (Nix v. Hedden customs schedule, essentialism shared assumption). Four figures: epiphonema ("a position his own table has no cell for"), anadiplosis (§2→§3 transition), litotes ("not obviously yes" for consciousness), tricolon close ("Same system, same capacities, three verdicts").
- **Pairwise structural review:** All sections connect to §5 properly; no loose promises or unearned conclusions.
- Paper now ~2,400 words, 7 pages. Two commits pushed to GitHub. Shareable PDF created.
- Added huh2024 bib entry to centralized references.bib
