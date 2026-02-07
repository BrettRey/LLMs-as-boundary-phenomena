# CLAUDE.md -- LLMs as Boundary Phenomena

## Role: Editor/Researcher

Deep editorial and research work welcome here. This is not a PM session.

## Project Overview

Short paper arguing that the debate over LLM cognition (are they "really" cognitive? merely linguistic?) is a category-boundary problem best handled by HPC theory and projection-purpose analysis, not by binary frameworks like Nefdt's (2026) 2x2 table.

### Core Argument

1. **Nefdt's Table 1 problem.** His Language/Cognition binary (humans: both; animals: cognition only; LLMs: language only) presupposes necessary-and-sufficient-condition categories. But the properties don't cleanly cluster into two groups: inferential reasoning, pragmatic implicature, analogical mapping, planning, and knowledge retrieval sit on a continuum between "clearly linguistic" and "clearly cognitive."

2. **HPC reframing.** Language and cognition are homeostatic property clusters, not binary features. LLMs instantiate a novel combination of properties from the cluster: some typically associated with cognition (reasoning, analogy, perspective-taking), others absent (embodied experience, persistent memory, emotional states). They're a boundary case, not a clean new cell.

3. **The tomato move.** The same LLM capacities get categorized as "linguistic" or "cognitive" depending on the projection purpose:
   - Neuroscience projection (implementation): linguistic
   - Functional projection (input-output behavior): cognitive
   - Phenomenological projection (consciousness): undecidable
   This is the tomato problem: fruit or vegetable depends on whether you're doing botany or cooking.

4. **Why this matters.** The LLM case is a vivid, publicly accessible illustration of projection-purpose effects on categorization. Everyone has intuitions about whether ChatGPT "really thinks," making this a better pedagogical vehicle for the HPC point than grammatical boundary cases (which require technical background).

### Key Sources (READ BEFORE WRITING)

| Source | Role | Location |
|--------|------|----------|
| Nefdt (2026) "What it's like to be an LLM" | Primary interlocutor | `../../literature/Nefdt_2026_What_its_like_to_be_an_LLM.pdf` |
| Boyd (1991, 1999) | HPC theory originals | Need to locate |
| Cappelen & Dever (2025) | Pro-LLM-cognition position | Referenced in Nefdt |
| Bender & Koller (2020) | Eliminativist position | Referenced in Nefdt |
| Casto et al. (2025) | Linguistic vs. deep understanding | Referenced in Nefdt |
| Mahowald et al. (2024) | Language/thought dissociation in LLMs | Referenced in Nefdt |
| Powell (2020) *Contingency and Convergence* | Convergence/contingency framework | Brett's library |

### Connections to Brett's Research Programme

- **HPC theory in linguistics:** This extends the HPC framework to philosophy of AI
- **Boundary phenomena:** LLMs as the paradigmatic boundary case for cognitive categories
- **Grammaticality:** The "zone of maximum systematicity" concept applies here too
- **Projection purposes:** The tomato analysis generalizes from grammatical categories to cognitive ones
- **Predicate overloading / noun analogy:** Cognitive predicates like "believes" are overloaded exactly like "noun" for syntacticians vs. semanticists — multiple purposes converge in core cases and diverge at boundaries. This is a structural parallel to Brett's core research on grammatical categories.

### Non-Negotiables

- Don't strawman Nefdt. His paper is good; the criticism is that binary frameworks undersell his own insights.
- The HPC framework should illuminate, not just relabel.
- **Diagnose, don't describe.** When the paper has a theoretical framework, the conclusion must show it doing work on specific cases — not just illustrate patterns. "Property selection" describes what happens; "essentialism about cluster kinds" diagnoses it using HPC theory. Always push toward diagnosis.
- Keep it short. This is a comment/reply piece, not a monograph.
- Source grounding LAW applies: verify all claims against Nefdt's actual text.

## Build System

XeLaTeX (not pdfLaTeX). `make` or:
```bash
xelatex main.tex && biber main && xelatex main.tex && xelatex main.tex
```

## House Style

See `.house-style/style-rules.yaml`. Key rules:
- `\term{}` for concepts, `\mention{}` for forms, `\enquote{}` for quotes
- En-dash with spaces (`~-- `), never em-dashes
- Contractions preferred, ~60 word paragraphs
- `\textcite{}` narrative, `\citep{}` parenthetical
