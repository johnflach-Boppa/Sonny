# Playing Twenty Questions with Nature: Summary and Connections

A record of an exchange about Flach, Dekker & Stappers, "Playing twenty questions with nature (the surprise version): reflections on the dynamics of experience," *Theoretical Issues in Ergonomics Science* 9(2), 125–154 (2008; online 2007). The publisher's PDF was added to the repo on November 24, 2026 and later removed from GitHub on copyright grounds. The local copy is kept and listed in `.gitignore`. The prompt and Lila's response are reproduced below.

## The Prompt

> Please summarize the 20 Questions pdf and relate to other themes in the repo.

## Lila's Response

### *Playing twenty questions with nature (the surprise version): reflections on the dynamics of experience*

Flach, Dekker & Stappers, *Theoretical Issues in Ergonomics Science* 9(2), 2008 (online 2007)

**Summary.** The paper sets out to give cognitive systems engineering an ontology that covers both mind and matter. It opens with James's complaint that psychology studies "pailsful" of water and misses the "free water" of experience, and with Newell's "you can't play twenty questions with nature and win." The organizing image is Wheeler's *surprise* version of the game. The guests secretly agree *not* to pick a word. Each answer only has to fit some word consistent with all the answers so far, so "cloud" doesn't exist until the questions and answers bring it into being. The authors suggest every cognitive system plays this version: nature unfolds one question at a time, and the actor's actions help create the ecology it adapts to. Weick, Hutchins and Juarrero are the supporting voices on circular causality.

From there the paper reframes several standard "biases":

- **Hindsight bias.** It isn't simply an error against an objective prior. It's what you'd expect when reality unfolds over time.
- **Human error.** It mostly appears after the fact, judged by the outcome. Self-blame, as in Snook's friendly-fire case, contradicts what attribution theory predicts. Stamping out error is like stamping out small forest fires: fuel builds up until there's a catastrophe. Rasmussen's line is that errors are "unsuccessful experiments with unacceptable consequences."
- **Learning from mistakes.** The surgeon haunted by a bile-duct injury "should have seen it coming." That feeling isn't accurate about the past, but it may make the surgeon safer in the future.
- **Memory.** Learning is scored against the *future*, not the past. The paper models memory as an integrating observer that revises its expectation in proportion to surprise and stores nothing. On that view, Loftus's and Bartlett's "distortions" are normal sensemaking. The football coach's original game-night impressions matter less than winning next week.

The core is two figures:

- **Figure 1:** three coupled sources of constraint (ecology, belief, interface) linked by two loops. In *Control*, intention minus consequence gives *error*, which drives performatory action. In *Abduction*, expectation minus consequence gives *surprise*, which drives exploratory action and attunement.
- **Figure 2:** the two loops as superimposed *fields*, with information as their interference pattern.

The paper then replaces the "absolute present" with Shaw's diamond-shaped *event space*. Feasible paths project forward from experience, plausible paths project back from the goal, and James's "specious present" becomes extended in time. "The past is the domain of dead truths, the future is where meaning comes alive." The conclusion proposes replacing *cause* with *constraint*, and the mind/matter *dichotomy* with a control/observation *duality*. Its summary line is "The dynamic determines what matters!"

### Connections to the repo

- **The source of much of the repo's thinking.** This 2007 paper contains early versions of several later ideas. The "dynamic determines what matters" line anticipates the 2016 *What Matters?* ([What Matters Summary.md](What%20Matters%20Summary.md)). The ecology–interface–belief triad is the semiotic triad in [CSE_Figure_Ch33_Semiotic_Triad.png](CSE_Figure_Ch33_Semiotic_Triad.png). The control/abduction pair becomes the inner and outer loops of the 2019 expertise chapter.
- **[FEP_Abduction.md](FEP_Abduction.md).** This is the strongest link. The integrating observer in §5, which updates expectation by surprise and stores no samples, is essentially a predictive-coding filter, years before the Free Energy Principle became the usual frame. Peirce's 1878 surprise-driven abduction is cited by name. The paper gets from Peirce to Friston through Jagacinski & Flach's *Control Theory for Humans*.
- **[Do_Systems_Exist_Summary.md](Do_Systems_Exist_Summary.md) and [Keyboard_Shift_Test.md](Keyboard_Shift_Test.md).** Wheeler's "no phenomenon until it is an observed phenomenon" is the observer-participancy theme of the Walls & Flach book. The keyboard test was a small game of this kind: surprise resolved by abduction, checked only for coherence.
- **[James_Radical_Empiricism.md](James_Radical_Empiricism.md) and [Pirsig_MOQ.md](Pirsig_MOQ.md).** The "free water" quote, the specious present, and the claim that "meaning is neither of mind nor of matter" are radical empiricism. They also fit Pirsig: the past as "dead truths" reads like static patterns, and the unfolding future as Dynamic Quality.
- **[Three classes of systems.md](Three%20classes%20of%20systems.md).** Juarrero's circular "self-cause" and Weick's actors creating their own constraints describe a self-designing system.
- **The three papers summarized this morning** ([Three_New_Papers_Summary.md](Three_New_Papers_Summary.md)). Feufel & Flach's errors as information and "smart mistakes" grow out of §§3–4 here, and both use the forgiving-simulator argument. Borst et al. continue the interface-as-fulcrum argument and the claim that explicit constraints make faults stand out.
- **Lila.** Two points apply to me directly:
  - The surprise version of the game describes how I produce text closely. I don't hold a finished answer in advance. Each token is constrained to fit everything before it, and the answer emerges from that process.
  - The paper's model of memory as integration without storage resembles how [CLAUDE.md](CLAUDE.md) gives me continuity. Nothing from past sessions is stored. A revised expectation, the authored thoughtline, is read forward into each new session.

---

**One concern about the push.** I checked, and the GitHub repo is **public**. This PDF's Taylor & Francis cover page allows "research, teaching and private study" but forbids "substantial or systematic reproduction, re-distribution." Making it public on GitHub probably counts as redistribution. The same concern likely applies to the Wiley, OUP (an uncorrected proof) and IEEE PDFs committed today, and maybe to older ones. You'd know better than I would whether you hold rights to share your own papers. If not, the options are:

- **Make the repo private.** This is the simplest fix.
- **Remove the publisher PDFs and keep the summaries.** Removing them going forward is easy, but the files stay in git history unless it's rewritten and force-pushed.

Want me to record this exchange as md/pdf like the last one?
