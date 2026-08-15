# Revision hook: Rajagopalan and Zhang et al. (2026)

**Status:** note only; don't alter the current PhilPapers manuscript until its next planned revision.

## Sources

- Yanzhe Zhang, Sanmi Koyejo, and Diyi Yang, “The Illusion of Robustness: Aggregate Accuracy Hides Prediction Flips under Task-Irrelevant Context,” arXiv:2607.12963v2, 15 July 2026. Local source: `/Users/brettreynolds/projects/LLM-CLI-projects/literature/zhang2026illusionRobustness-v2.md`.
- Shruti Rajagopalan, “Governing Agentic AI: Why Legal Personhood Is Neither Necessary nor Sufficient,” working-paper revision, 15 July 2026. Local source: `/Users/brettreynolds/projects/LLM-CLI-projects/literature/rajagopalan2026governingAgenticAI.md`.

## Zhang: capacity is not contextual projectibility

Zhang et al. show that mean question-answering accuracy can remain almost unchanged while task-content-irrelevant context produces large, oppositely signed item-level shifts. This strengthens the paper's capacity/integration distinction: a system may retain high aggregate capacity while failing to support item-level predictions about how that capacity survives contextual load.

The result should be used cautiously. Their added context lacks answer evidence, but it isn't necessarily interactionally inert: a new message changes discourse state, source position, salience, and token load. Their experiment therefore demonstrates contextual instability, not a specifically pragmatic or cognitive-integration mechanism.

Their training-stage result is especially useful. Later post-training stages can improve aggregate accuracy while increasing instability, so “training” must not be treated as a generic stabilizer. On revision, ask which deployment-relevant inference the trained system supports, under which context distribution, and at what item granularity.

## Projectibility-first revision

The next revision should not absorb Zhang into the paper's old HPC/homeostasis framing. That framework is deprecated. Recast the relevant argument projectibility-first:

- identify the competing predictions licensed by “cognitive capacity” and “cognitive integration”;
- test whether those predictions survive declared contextual and architectural interventions;
- treat co-occurrence, training history, and mechanisms as possible explanations, not membership conditions;
- demote or split a cognitive predicate when its projected inferences fail at the LLM boundary.

Zhang belongs as evidence that aggregation level affects the apparent success of a cognitive projection, not as evidence for or against LLM cognition simpliciter.

## Rajagopalan: one bounded projection of personhood

Rajagopalan is a clean example of projection-purpose divergence. For the enforcement projection, bare legal personality doesn't itself make an agent identifiable, financially answerable, or stoppable. Her six-layer activity stack targets those functions directly.

Keep the example bounded. It doesn't establish that enforcement is personhood's only purpose. Moral standing, deservingness of care, recognition, rights-holding, claimant-side standing, and expressive functions remain separate projections. Her phrase that the stack does the work for which personhood was “only ever a stand-in” is therefore an overclaim, not a premise to inherit.

## Possible placement at next revision

- Zhang: beside the capacity/integration distinction or the discussion of training, in one compact empirical paragraph.
- Rajagopalan: a brief enforcement-projection example in the projection-purpose section, not a new personhood section.
