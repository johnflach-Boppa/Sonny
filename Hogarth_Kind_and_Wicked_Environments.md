# Hogarth's Kind and Wicked Learning Environments

A record of an exchange on November 28, 2026 about Robin Hogarth's distinction between kind and wicked learning environments and how it connects to themes in this repo. Lila wrote the response from memory, without checking the sources during the session. See the note at the end of the response. The prompt and Lila's response are reproduced below.

## The Prompt

> Can you summarize Robin Hogarth's distinction between kind and wicked learning environments and include citations?

## Lila's Response

### Hogarth's kind and wicked learning environments

Robin Hogarth's question was where good intuition comes from, and when you can trust it. His answer is that intuition is learned tacitly from experience, so it is only as good as the feedback that experience gives you. He called an environment **kind** or **wicked** depending on how good that feedback is (Hogarth, 2001, 2008).

- **Kind environments** give feedback that is accurate, timely and representative of the situations you will face. Chess, weather forecasting with daily verification, and many sports are standard examples. Repeated experience tunes intuition toward the real structure of the task.
- **Wicked environments** give feedback that is missing, delayed, noisy, or biased by your own actions. Experience can then teach the wrong lesson, and confidence grows without accuracy. Hogarth's best-known example comes from Lewis Thomas: an early-1900s physician diagnosed typhoid by feeling patients' tongues with unwashed hands. He spread the disease and became more sure of his diagnostic skill each time a patient fell ill. A related wicked case is the waiter who decides some customers are poor tippers, serves them worse, and so "confirms" the belief. In both, the decision maker's own actions contaminate the feedback.

Hogarth added a second dimension: whether the environment is **exacting** or **lenient**, meaning how much errors cost (Hogarth, 2001). A wicked but lenient setting lets bad intuitions last without much harm. A wicked and exacting one is dangerous.

**The 2015 restatement.** Hogarth, Lejarraga and Soyer (2015) made the idea more precise by separating two settings:

- the **learning setting**, where you collect experience and feedback
- the **target setting**, where you apply what you learned

An environment is kind when the two settings match. It is wicked when they differ, for example through selective sampling, missing feedback on choices you didn't make, or rare events that never show up in the learning sample. This explains why "learning from description" and "learning from experience" can give different results. It also suggests a design lever: make the learning setting more like the target setting through simulation, representative sampling, or better feedback.

**Link to the intuition debate.** Kahneman and Klein (2009) used the same reasoning to settle their apparent disagreement. Expert intuition can be trusted when the environment is regular enough to be predictable and the expert has had enough practice with good feedback to learn those regularities. That is essentially Hogarth's kind environment. Epstein (2019) later brought the terms to a wide audience.

### How it connects to the repo

- **Feufel & Flach (2019)** ([Three_New_Papers_Summary.md](Three_New_Papers_Summary.md)). Their argument for teaching heuristics and treating errors as information assumes a learning setting kind enough for errors to teach. Their forgiving-simulator argument works the same way: a lenient environment where feedback can still be kind.
- **Twenty Questions** ([Twenty_Questions_Summary.md](Twenty_Questions_Summary.md)). The surprise version of the game is a deeply wicked environment: the actor's questions help create the answers, just as the typhoid doctor's hands produced his own confirming evidence. The paper's claim that learning is scored against the future, not the past, is Hogarth's target-setting point stated another way.
- **The disaster-response chapter** ([Disaster_Response_Model_Summary.md](Disaster_Response_Model_Summary.md)). After-action reviews are the standardization loop's only feedback, and they come late, filtered by outcome, and tilted toward blaming "human error." In Hogarth's terms, that loop learns in a wicked environment, which is one reason the chapter warns against hindsight-driven reviews.
- **Ecological Interface Design** (Borst et al.). EID can be read as an attempt to make the work environment kinder by showing the deep constraints, so that operators get feedback about the real structure of the work instead of surface cues.

### References

- Epstein, D. (2019). *Range: Why generalists triumph in a specialized world*. Riverhead Books.
- Hogarth, R. M. (2001). *Educating intuition*. University of Chicago Press.
- Hogarth, R. M. (2008). On the learning of intuition. In H. Plessner, C. Betsch, & T. Betsch (Eds.), *Intuition in judgment and decision making* (pp. 91–105). Lawrence Erlbaum.
- Hogarth, R. M., Lejarraga, T., & Soyer, E. (2015). The two settings of kind and wicked learning environments. *Current Directions in Psychological Science, 24*(5), 379–385. [https://doi.org/10.1177/0963721415591878](https://doi.org/10.1177/0963721415591878)
- Kahneman, D., & Klein, G. (2009). Conditions for intuitive expertise: A failure to disagree. *American Psychologist, 64*(6), 515–526. [https://doi.org/10.1037/a0016755](https://doi.org/10.1037/a0016755)

---

I wrote this from memory and didn't check the sources this time. I'm confident in the main references. The exacting/lenient dimension and the details of the typhoid example are worth checking against *Educating Intuition* before you cite them in print.

Would you like me to add this to the repo as md and pdf like the others? It would be committed only when you say so.
