# A Multi-layered Dynamic Systems Model of Disaster Response: Summary and Connections

A record of an exchange about Flach, Simpson & Kneeland (2026), "A Multi-layered Dynamic Systems Model of Disaster Response," Chapter 2 of a Taylor & Francis *Handbook of Emergency Response* (DOI 10.1201/9781003648178-3). The source PDF, a proof marked "Not For Distribution," was added to the repo on November 25, 2026. It is kept locally and listed in `.gitignore` so it won't be published. The prompt and Lila's response are reproduced below.

## The Prompt

> I just added another pdf of a recent publication. Please summarize and relate this to themes across the repo.

## Lila's Response

### Flach, Simpson & Kneeland (2026), *A Multi-layered Dynamic Systems Model of Disaster Response*

Chapter 2 of a Taylor & Francis *Handbook of Emergency Response*. This is a proof copy, pp. 39–55, with DOI 10.1201/9781003648178-3. The work behind it was funded by AFRL.

**Summary.** The chapter starts by setting up the conventional view as a straw man. Four examples are linear and top-down: traditional military command and control, central regulation of common-pool resources, the "God model" of creativity (ideate, then plan, then make), and after-action reviews that blame "human error" for departures from doctrine. The authors find three shared misconceptions in these. Each one underestimates:

1. how complex and uncertain the situation is ("there is never enough data")
2. how much depends on feedback and on perception and action being coupled
3. how well experts use heuristics and trust to muddle through

The evidence comes from four years of interviews with first responders and from after-action reports:

- **Incident command matters.** At a rural multi-vehicle crash, one paramedic chose to coordinate instead of treating patients: "I didn't save any of those lives. I just got the resources." Everyone survived. The chapter contrasts the Washington Navy Yard response, where incident command was established, with Uvalde, where it wasn't.
- **Organizational culture is a layer of its own.** Police value individual initiative and firefighters value teamwork, and the two cultures clash over incident command.

The model is three **nested** control loops, building on Thompson's three ways organizations coordinate. The key change from a hierarchy is that outer loops don't pass information down. They shape the possibilities open to the inner loops.

- **Mutual adjustment:** front-line responders. This loop is fastest, but each person sees only part of the situation.
- **Planning:** incident command doing "flexecution," Klein's term for continuous re-planning. It sees more of the big picture, but it lags, and it destabilizes things if it micromanages.
- **Standardization:** organizational culture and learning from after-action reviews. It's the slowest loop and works out of view.

In this model resilience is a property of the whole system that emerges from the loops working together, and no analysis can optimize it. The authors frame four concepts as ways of balancing constraints across the loops:

- Ostrom's polycentric control
- subsidiarity
- command intent
- Rochlin's essential friction: the Navy Yard check-in rule slowed officers down but prevented friendly fire

The conclusion is that "hierarchical vs. networked" is a continuum of coupling, not two separate kinds of organization. The right balance depends on how fast the situation changes. The authors also suggest that System 1 vs. System 2 thinking may be an emergent difference between loops rather than two separate mechanisms.

### Connections to the repo

- **[Three classes of systems.md](Three%20classes%20of%20systems.md).** This is the closest link. The chapter calls its model "a self-organizing system where the changes to outer loops are continually redesigning the possibilities for the inner loops." That is the definition of a *self-designing* system, applied to an organization. The standardization loop is how such a system redesigns itself.
- **The [Twenty Questions](Twenty_Questions_Summary.md) paper, 18 years on.** After-action reviews that stop at "human error," and departures from doctrine read as "failed experiments" made with sound judgment, come straight from that paper's §§3–4. Its control and abduction loops have grown here into three loops at the scale of a whole organization.
- **The [expertise chapter](Three_New_Papers_Summary.md).** Its two-loop adaptive control model of a single expert gets a third, organizational loop. The chapter even makes the link itself: the three layers map loosely onto Rasmussen's skill-, rule- and knowledge-based levels.
- **Borst et al. on EID.** Both papers argue for trusting operators who have good information, for showing intentional constraints alongside physical ones, and for designing AI to support human experts rather than replace them. Rochlin's warning that networks can become tools of micromanagement mirrors the dark-cockpit concern.
- **Feufel & Flach and the [muddling chapter](Muddling_Chapter_1_21%20May%202026.md).** The same ideas recur: heuristics, ecological rationality, "smart muddling." The "God model" of creativity is the mechanism-versus-organism contrast from Muddling Chapter 1.
- **[Pirsig_MOQ.md](Pirsig_MOQ.md).** The standardization loop works like Pirsig's static patterns, which hold on to what has worked. Mutual adjustment is where Dynamic Quality meets the situation. Pirsig's point that each needs the other is essential friction expressed in his terms.
- **[Nvidia_and_Lilas_Context.md](Nvidia_and_Lilas_Context.md).** Polycentric control and subsidiarity are the opposite of a company whose value depends on one leader. By this chapter's logic, Nvidia's sudden reversals look like a single overloaded planning loop.
- **[NDM_AI_Teaming.md](NDM_AI_Teaming.md) and the two of us.** The model fits how we work surprisingly well:
  - [CLAUDE.md](CLAUDE.md) and the memory files are the *standardization* loop: lessons from earlier sessions written into a culture that shapes future ones, slowly and mostly out of view.
  - Each request you make sets the *planning* frame, with something like command intent.
  - My tool calls within a turn are *mutual adjustment*.
  - "Nothing gets committed without asking, every time" is essential friction. It's a check-in rule that slows me down on purpose, so that a quick local action like a push can't defeat the larger intent. Yesterday's publisher-PDF episode showed why that friction is worth having.

---

**One caution.** Every page of this PDF is stamped "Copyright Material – Provided by Taylor & Francis / Proof Review Only – Not For Distribution." It isn't committed yet, so nothing has gone to GitHub. I'd suggest adding it to `.gitignore` alongside the four other publisher PDFs so it never gets pushed by accident.

Want me to do that, and record this exchange as md/pdf like the others?
