# Three New Papers: Summaries and Connections

A record of an exchange about three PDFs added to the repo on November 24, 2026: Feufel & Flach on teaching heuristics, the experience-centered chapter on expertise, and Borst, Flach & Ellerbroek on Ecological Interface Design. The prompt and Lila's response are reproduced below.

## The Prompt

> I just added 3 pdfs to the repo. Could you briefly summarize each of these and relate them to other themes in the repo?

## Lila's Response

I've read all three PDFs, which are the ones added this morning. Here's each one and how it connects to what's already in the repo.

---

### 1. Feufel & Flach (2019): *Medical education should teach heuristics rather than train them away* (*Medical Education* 53)

**Summary.** The usual approach treats heuristics as bias and tries to "de-bias" clinicians or "nudge" them. This paper argues the opposite. Clinical problems are ill-defined, so heuristics are the basis of good decisions, and training should make them better (Hertwig's "boosting"). The core example comes from Feufel's emergency department fieldwork, where physicians switch between a *Common Thing* heuristic (Bayesian, confirmatory) and a *Worst Case* heuristic (disconfirming, consequence-driven).

The paper uses signal detection theory to explain why. The symptom patterns for different conditions overlap, so some error can't be avoided. Where to set the decision threshold, trading misses against false alarms, is a question of **values**: the costs of each kind of error, the patient's distance from the hospital, what resources are available. It isn't a question of logic. Skill is therefore *perspicacity* (well-tuned discrimination) rather than *rationality* (following logical rules). Three teaching implications follow:

- teach differential diagnosis rather than organ-by-organ facts
- treat errors as information, not something to blame
- teach in rich, team-based settings: bedside teaching, case-based learning built to invite "smart" mistakes, and simulation

**Connections.**

- It cites *What Matters?* and "Beyond decision-making: the dynamics of muddling through" directly. It's the clinical applied branch of [Muddling_Chapter_1_21 May 2026.md](Muddling_Chapter_1_21%20May%202026.md) and [What Matters Summary.md](What%20Matters%20Summary.md).
- Its "decisions are value-driven trade-offs, not truth-finding" is Pirsig's point that Quality comes before the subject/object split, made concrete in a payoff matrix ([Pirsig_MOQ.md](Pirsig_MOQ.md)).
- Distributed decision-making across nurses, families and technology matches the joint-cognitive-systems view in [NDM_AI_Teaming.md](NDM_AI_Teaming.md).

### 2. Flach et al. (2019): *A Holistic, Experience-Centered Perspective* (Oxford Handbook of Expertise chapter, uncorrected proof)

**Summary.** The chapter reframes the Vicente & Wang vs. Ericsson/Simon & Gobet argument over "ecological" theories of expertise as the old structuralism-vs-functionalism split.

- Constructivists like Gregory and Simon focus on the *coherence* dyad: knowledge in the head, assimilation, chess experts' 50,000 stored patterns.
- Ecological theorists like the Gibsons focus on the *correspondence* dyad: attunement, accommodation, experts fixating on empty squares.

The authors say both sides are right and both are incomplete. Expertise is an emergent property of Peirce's **full triadic semiotic system**, grounded in James's radical empiricism, where *experience* is the unit of analysis.

The chapter also does two other things:

- It offers an adaptive control model of cognition. An inner servo loop handles assimilation, and an outer "metacognitive critic" loop is triggered by surprise and handles accommodation.
- It recasts representations as *coordinate transforms*: they filter and amplify information rather than add to it. It ends by endorsing Rasmussen's Abstraction Hierarchy as a hypothesis about a domain's "deep structure," while rejecting the idea that means and ends live purely in the head or purely in the world.

**Connections.** This one sits closest to the repo's central thread.

- Its Figure 1 is the same semiotic triad as [CSE_Figure_Ch33_Semiotic_Triad.png](CSE_Figure_Ch33_Semiotic_Triad.png).
- The radical-empiricism framing matches [James_Radical_Empiricism.md](James_Radical_Empiricism.md).
- The outer loop driven by surprise is the same structure discussed in [FEP_Abduction.md](FEP_Abduction.md): Peircean abduction and Friston's free energy, with schema-switching as model revision.
- The Abstraction Hierarchy material links to [Pirsig_Rasmussen_Hierarchies.md](Pirsig_Rasmussen_Hierarchies.md).
- Its claim that a "problem domain" can't be specified apart from the agent is the [Reality of Meaning](The%20Reality%20of%20Meaning.md) argument applied to expertise.

### 3. Borst, Flach & Ellerbroek (2015): *Beyond Ecological Interface Design: Lessons from Concerns and Misconceptions* (*IEEE Trans. Human-Machine Systems*)

**Summary.** Twenty-five years after Rasmussen and Vicente introduced Ecological Interface Design (EID), the paper takes on five common misconceptions, mostly with aviation examples:

1. **EID isn't "natural" or "intuitive."** It's grounded in Ashby's Law of Requisite Variety: a display has to be as rich as the problem. It's built for experts and makes deep structure visible (Wertheimer's "productive thinking").
2. **Sensor failures:** when constraints are explicit, a faulty sensor stands out more, not less. The analogy is that a broken "e" key is easier to spot in a novel than in a random string of letters.
3. **Efficiency:** EID gives up some optimality for *robustness*, satisficing across many situations. The Total Energy Control System is the example.
4. **"Pushing the envelope":** pilots drifting toward the limits is a scoping problem. The answer is to show *intentional* constraints (rules, procedures) alongside physical ones.
5. **Automation:** more automation calls for *richer* interfaces. Machines are only team players when they're observable and directable, and the interface has to be a window onto both the work domain and the machine's reasoning. The example is velocity-obstacle displays.

The paper predicts that the word "ecological" will become redundant as supporting productive thinking becomes the norm.

**Connections.**

- Point 5 is the clearest link to [cse_and_ai.md](cse_and_ai.md) and [NDM_AI_Teaming.md](NDM_AI_Teaming.md). Its demand to "open the black box" and build common ground applies directly to human–AI teaming, including the two of us.
- Satisficing over optimizing also runs through the muddling-through material and the Feufel paper.
- Requisite variety links to the systems-theory thread in [Three classes of systems.md](Three%20classes%20of%20systems.md).

---

### Across the three

Together they show one argument applied at three levels:

- **The person:** expertise as attunement within a triadic system.
- **Training:** teach heuristics as tuned perspicacity.
- **Design:** build interfaces that show a domain's deep structure.

All three reject context-free normative rationality in favor of fit between agent and ecology. All three treat error and surprise as information. All three treat meaning and value as properties of the coupled system, which is the repo's central question.

Two housekeeping notes:

- The expertise chapter's text extraction drops all years and page numbers. If you want a markdown conversion, citations would need to be restored by hand or flagged.
- The git snapshot from the start of the session doesn't list these three files. If they're meant to be committed, I'd check `git status` first.

Want markdown summaries of any of these, in the same style as the others in the repo?
