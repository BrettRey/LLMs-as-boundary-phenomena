# STATUS.md -- LLMs as Boundary Phenomena

**Last updated:** 2026-02-06
**Current phase:** Revised draft (post simulated review)
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
