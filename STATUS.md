---
slug: llms-as-boundary-phenomena
kind: paper
title: 'LLMs as boundary phenomena: Bearers and cognitive attribution'
stage: complete
external: preprint
blocked_on: []
updated: 2026-08-15
source:
- STATUS.md
- PORTFOLIO.md
- main.tex
preprints:
- philpapers/REYLAB
next_action: 'Update PhilPapers/PhilArchive REYLAB with the completed standalone v5 PDF after Brett signs in; synchronize the changed title and abstract; then prepare the anonymous Philosophical Psychology submission package.'
notes: 'The posted PhilPapers preprint remains version 2. The standalone v5 revision is complete locally. Nefdt remains the principal case but his publication status is no longer a submission dependency.'
---

# STATUS.md -- LLMs as Boundary Phenomena
<!-- SUMMARY: Preprint live as version 2 (PhilPapers REYLAB); standalone v5 complete and awaiting upload; target venue Philosophical Psychology; no external submission blocker · updated: 2026-08-15 -->

**Last updated:** 2026-08-15
**Current phase:** Standalone v5 ready; PhilPapers update pending sign-in
**PhilPapers:** https://philpapers.org/rec/REYLAB
**Target venue:** *Philosophical Psychology*
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
- [x] Final polish (pre-submission check, Oxford spelling, page refs, punctuation)
- [x] Preprint uploaded to PhilPapers (2026-02-12)
- [x] Cluster-distinction revision (2026-02-18): "cognition" tracks distinct integration/capacity clusters
- [x] Von der Malsburg & Padó (2026) integration — agreement attraction as integration/capacity evidence
- [x] Venue selected (2026-08-15): *Philosophical Psychology*; eventual submission will be framed as an original article under the journal's current author guidelines
- [x] v3 recast (2026-08-15): projectibility-first reframe + Sripada & Lewis / Hu et al. / Ladyman & Nefdt / Nefdt & Ladyman / Futrell & Mahowald; built and visually checked
- [x] v4 revision (2026-08-15): Sol-led surgical revision after independent and external review; added full declaration schema, bounded Hu projection, failed von der Malsburg--Padó projection, source corrections, and prospective decision rule; built and visually checked
- [x] v5 standalone revision (2026-08-15): made bearer-relativity the first-order objection; added Dennett, Shanahan, construct-validity, and capacity-attribution positioning; added the Kosinski/Ullman repair; recast HPC as a prospective dissociation hypothesis; stated failure conditions; rebuilt and visually checked at eight pages
- [ ] Update PhilPapers/PhilArchive `REYLAB` with v5 and synchronize the changed title and abstract (PDF ready; requires PhilArchive sign-in)
- [ ] Consider Kısa et al. (2026) "Cognitive change without linguistic change" (*Cognition* 273, 106522) — Hai||om spatial cognition shifted geocentric→egocentric over ~20 years while language stayed geocentric. The language/cognition cluster dissociated under material-culture pressure. This is a human case of exactly the HPC point: the cluster's properties can come apart without the cluster dissolving. Strengthens the argument against Nefdt's binary (language tracks cognition) by showing it fails even within a single community undergoing cultural change, not just at the LLM boundary. Also relevant to mechanisms: language was assumed to be the homeostatic mechanism maintaining geocentric cognition, but material culture overrode it — multiple competing mechanisms, not a single determinant.
- [ ] Consider Arora et al. (2026) "Language model circuits are sparse in the neuron basis" (arXiv:2601.22594) — ~100 MLP neurons control agreement; sparse, causally manipulable circuits. Evidence that integration/capacity cluster distinction has internal structural correlates, not just behavioural ones. Also: Arora et al. (2025) "Mechanistic evaluation of Transformers and state space models" — architecturally different models use fundamentally different mechanisms for the same task. This is convergent function from divergent structure (Powell's framework), applied to AI architectures.
- [ ] Prepare the anonymous *Philosophical Psychology* submission package under the live author guidelines

### Literature: Groeger, Wen, and Brbic (2026)

Central note: `../../../literature/groeger_wen_brbic_2026_aristotelian_representation_hypothesis.notes.md`.

This paper is already in `main.tex` as the calibration correction to Huh et al.'s Platonic Representation Hypothesis. Next touch should preserve the exact use: raw global representational convergence is weakened by width/depth and layer-search confounds; calibrated local neighbourhood convergence survives. That supports task-driven constraint on representations without licensing a stronger "shared statistical model of reality" claim. When updating PhilPapers, make sure the revised PDF contains this qualification.

## Genesis

Arose from Brett's email exchange with Geoff Pullum about a pro-LLM Nature paper. Reading Nefdt's "What it's like to be an LLM" revealed that his 2x2 table (Language x Cognition) is a necessary-and-sufficient-conditions framework that HPC theory is designed to replace. The "tomato move" (is LLM reasoning linguistic or cognitive? depends on projection purpose) crystallized the argument.

## Session Log

### 2026-04-16
- Brett emailed Cameron Yetman (UofT) re his forthcoming *Ergo* paper on LLM representation, connecting to this project and the vector-grounding reply. Yetman replied same morning agreeing to read both. No deadline; informal comments expected. See `yetman-reply-2026-04-16.md`.

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

### 2026-02-12 (session 7, pre-submission and upload)
- **BibTeX audit:** All 20 entries verified against external sources. Three errors found: boyd1999 pages (141--185 → 141--186), khalidi2013 first name (Mohammad → Muhammad), Goodman1955 year/publisher (1955/Harvard → 1954/Athlone or 1983/Harvard 4th ed.). Brett declined fixes.
- **Pre-submission check:** Full build clean (8 pages). All Nefdt quotes verified against PDF. Found page reference error (p.10 → p.9 for "trained to execute" quote). Found three punctuation-outside-quotes violations. Found overfull hbox (5pt) in projection-mismatch paragraph.
- **Fixes applied:** Page ref corrected; punctuation moved outside \enquote{}; Oxford spelling (categorising → categorizing, reorganising → reorganizing); overfull resolved by rewording "stability across contexts" → "contextual stability" and dropping Oxford comma.
- **Uploaded to PhilPapers:** https://philpapers.org/rec/REYLAB
- Categories: Artificial Minds, Misc; Methodology of Linguistics, Misc; Philosophy of Cognitive Science, Misc

### 2026-02-18 (session 8, cluster-distinction revision)
- **Core new move:** "Cognition" tracks distinct property clusters (integration and capacity) that converge in humans, co-vary in non-human animals, and come apart for LLMs. Parallel to Brett's deitality/definiteness distinction.
- **New paragraph in Section 4:** Two clusters under "cognition"; convergence in humans; co-variation in animals masked the ambiguity; LLMs break the co-variation via different causal pathway. Terminological distinction flagged as available.
- **Revised Nefdt paragraph:** Table implicitly tracks the integration cluster — animals get +Cognition, LLMs get -Cognition, but under capacity cluster verdicts would differ.
- **Revised Section 4 closing:** Disputants track different clusters under shared label.
- **Section 5 bridge updated:** Scale shift from category level to vocabulary level made explicit.
- **Shanahan/Cappelen & Dever mapping:** One sentence making integration/capacity mapping explicit.
- **Abstract updated:** Now advertises cluster-distinction argument, not weaker tomato perspectivalism.
- **Conclusion sharpened:** "a question that presupposes the predicate is univocal."
- Chose Option B (flag) over Option A (coin): "cognitive integration" and "cognitive capacity" were drafted but Brett preferred flagging the move as available without committing to terms.
- All edits pass style checker. Builds clean, 8 pages.
- Updated PDF renamed for posting. PhilPapers preprint needs updating.

### 2026-03-18 (session 9, von der Malsburg & Padó integration)
- **New paragraph in Section 4:** Von der Malsburg & Padó (2026) as concrete evidence that integration/capacity clusters come apart within a single domain (morphosyntactic agreement). Transformers share grammatical capacity but replicate processing-channel effects only partially.
- **Connection to grammaticality/acceptability distinction:** Agreement attraction is a processing-channel phenomenon (feeling of ungrammaticality), not a grammatical one. This explains why the capacity transfers but the processing signature doesn't.
- **Email sent to von der Malsburg & Padó** offering the grammaticality/acceptability distinction as an explanation for their PP/ORC divergence. Pointed them to lingbuzz/009713 (the de-idealizing paper), not the PhilPapers preprint.
- Bib entry added to references-local.bib. Builds clean, 9 pages.

### Literature: Many Minds podcast (Frank & Lupyan, 2026-03-26)
- **Boundary framing:** The whole podcast wrestles with whether LLMs are "really" doing cognition — exactly your paper's territory. Lupyan rejects the stochastic-parrots / autocomplete dichotomy. Frank: "we can't be lulled into the fact that a conversational agent speaks in language that we understand to think that it has exactly the same representations."
- **Embodiment downgraded:** Lupyan: "LLMs have shifted my own personal view... downgrade the importance of sensory input." Frank: "many ways to ground" including code and math.
- **Multiple realizability / Quine's topiary** (Frank): Same external behavior, different internal branches. Adjacent to HPC clustering on observables.
- See `literature/many-minds-frank-lupyan-2026.md` for full notes + transcript.

### 2026-03-29 (session 10, Cavell/Techio integration)
- **New paragraph + footnote in Section 4:** Acknowledgment (Cavell 1969) as a third diagnostic pattern beyond projection mismatch and essentialism. Crosscuts both integration and capacity clusters. A system can have functional cognition and biological integration and still fail to acknowledge. Cites Techio (2026) essay on Cowen's GOAT and the "fiction layer," and Techio (2021) monograph on meaning as risky activity. Footnote references Cavell's "Avoidance of Love" on soul-blindness.
- **Source verification:** Characterisation of Techio (2021) confirmed against Severo (2022) review in Nordic Wittgenstein Review.
- **Bib entries added to central bib:** Cavell1979ClaimOfReason, Cavell1988InQuest, Cavell1969AvoidanceOfLove, Cavell1969KnowingAcknowledging, Techio2026ClaimTrainingData, Techio2021ThreatSolipsism. DOI corrected (was wrong De Gruyter ID).
- Builds clean, 9 pages.
