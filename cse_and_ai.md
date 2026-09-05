# CSE and AI

How Cognitive Systems Engineering (CSE) is relevant to the design and use of AI, drawing on the arguments in *Cognitive Systems Engineering: Connecting Situations and Awareness* (John M. Flach).

## AI as Enhancing Observability, Not Replacing Control

The book's most direct argument: most AI hype frames AI as an autonomous controller (an "autopilot") that will either replace humans or push them up into pure supervisory roles — with the hidden assumption that the AI has access to "the right map." Flach argues this is fine for simple/complicated domains, but wrong for complex or chaotic ones where no complete map exists. His alternative: AI's real value is to **enhance observability** — using computation to pull partial patterns out of data that humans couldn't otherwise perceive, in service of human orientation and sensemaking. In Boyd's OODA terms, AI enriches *Observation* in ways that shape human *Orientation* and framing of *Decisions* — it doesn't replace the loop, it feeds it.

## Joint Cognitive Systems, Not Human-vs-AI

CSE's founding move — treating the human+technology+domain as one unit of analysis with emergent properties, rather than separate components to optimize independently — is exactly the frame the book (via John Allspaw's quote in the Preface) says is missing from mainstream AI discourse, which tends to default to either "AI does everything autonomously" or "people just supervise AI." CSE offers a third option: designing the *joint* system's dynamics deliberately.

## The Automation-Surprise Problem Gets Sharper, Not Smaller

CSE emerged because Rasmussen recognized automated control systems would eventually face situations their designers hadn't anticipated, requiring humans to detect, diagnose, and improvise. That's arguably the central risk profile of modern AI systems too — and the book's answer isn't "make the AI good enough that this never happens," it's designing the human role and the interface so people can catch and recover from exactly those moments.

## EID Principles Apply Directly to AI Interfaces

Ecological Interface Design's core commitment — show both fine-grained data *and* higher-order relations (configural, not either/or), shape mental models rather than just match them, support adaptive improvisation rather than procedural compliance — is a ready-made design philosophy for AI explanation/output interfaces, as opposed to either a black-box answer or an undigested dump of model internals.

## Wicked Problems and the Ethics of "Taming"

Churchman's warning (quoted in Chapter 17) that tackling a wicked problem piecemeal and presenting it as solved is *morally wrong* because it deceives people into thinking something is safe when it isn't — this reads as a direct caution against deploying AI in complex domains (healthcare, security, policy) with more confidence than the underlying problem structure warrants.

## The Common Thread

CSE doesn't treat "how much should AI do vs. humans" as the question. It treats the coupling between them — what each can observe, what constraints propagate between them, how stability emerges from the pairing — as the actual design object.
