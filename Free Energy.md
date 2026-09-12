# Free Energy

An explanation of Karl Friston's Free Energy Principle (FEP) — already name-checked in the *Cognitive Systems Engineering* book sitting in this repo (Chapter 30, tied to Piaget's assimilation/accommodation and Boyd's OODA loop).

## The Problem It's Trying to Solve

Any self-organizing system that persists over time — a cell, an organism, a brain — has to occupy a limited, low-entropy set of states (the right temperature, hydration, blood glucose, etc.) against the universe's general pull toward disorder. Persisting means resisting dissipation. FEP asks: what must such a system be doing, computationally, to pull this off?

## The Core Move

The most direct answer would be "minimize surprise" — avoid sensory states that are improbable given your model of the world (formally, surprisal = −log P(sensory input | model)). But computing true surprise exactly is intractable — it would require marginalizing over every possible hidden cause of your sensory input. So instead, Friston proposes the system minimizes a computable upper bound on surprise called **variational free energy**. This isn't the same "free energy" from thermodynamics (Gibbs/Helmholtz) — it's a borrowed term from variational Bayesian statistics (the same math underlies things like variational autoencoders in ML).

Free energy can be decomposed two useful ways:

- **Complexity − Accuracy**: a Bayesian-Occam's-razor tradeoff between how far your beliefs deviate from a simple prior and how well those beliefs predict the data.
- **Surprise + KL divergence** (between your approximate internal model and the true posterior): since KL divergence is always ≥ 0, free energy is always ≥ surprise. Minimize the bound, and you drag down the actual surprise too — and as your internal model gets more accurate, the bound tightens toward the true value.

## Two Ways to Minimize It — the Key Unifying Move

1. **Perceptual inference**: update your internal beliefs to better explain the sensory data you're getting (classic Bayesian updating / predictive coding — perception as hypothesis-revision).
2. **Active inference**: instead of updating your beliefs, act on the world to change the sensory data so it matches your existing predictions.

That's the theory's most distinctive claim: perception and action aren't two separate systems bolted together — they're the *same* optimization (minimizing free energy) run in two directions. You can resolve a mismatch between model and world either by changing the model or by changing the world.

## Hierarchical Structure

The brain is modeled as a multi-level generative model constantly issuing top-down predictions; prediction errors flow upward and get absorbed either by updating beliefs or by triggering action, at every level simultaneously, each level operating over a different timescale.

## The Connection Back to This Repo

Chapter 30 of the CSE book explicitly lines up FEP with Piaget's assimilation (acting on the world to make it fit your schema — active inference) and accommodation (updating the schema to fit surprising feedback — perceptual inference), and with Boyd's creation/destruction dynamic in the OODA loop. It's the same move as Rasmussen's Abstraction-Decomposition hierarchy, too — higher levels provide context that filters what's salient at lower levels, exactly FEP's hierarchical top-down/bottom-up structure. And it's a formal, mechanistic answer to the question the "Three classes of systems" note raises about self-organizing vs. self-designing systems: FEP is Friston's attempt to give a rigorous account of *how* a self-designing system (one with "internal agency") actually manages the trick of persisting against entropy by acting on top of just dissipating energy efficiently.

## A Caveat Worth Knowing

FEP is contested. Critics argue it's so general it risks being unfalsifiable — that it can be retrofitted to explain almost any behavior after the fact — and that it's substantially a reformulation of older ideas (Helmholtz's "unconscious inference," the Bayesian brain hypothesis, homeostasis/allostasis, classical cybernetics) in new mathematical clothing rather than a novel empirical discovery. That doesn't make it wrong, but it's not settled, universally-accepted science the way the label "principle" might suggest.
