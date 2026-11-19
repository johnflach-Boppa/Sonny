# The Repo and Human-AI Teaming

Notes prepared ahead of the Symposium on Naturalistic Decision Making and AI (July 2027). The question and Claude's response are reproduced below.

## The Question

> Also, I have been invited to participate on a Symposium on Naturalistic Decision Making and AI next July. I would be interested in your thoughts about how the ideas in this repo relate to the challenges of human-AI teaming.

## Claude's Response

The repo has a strong position to bring to an NDM audience. It also pushes back on the way "human-AI teaming" is usually framed.

### 1. The core claim: teaming is a property of the triad, not the dyad

Most human-AI teaming work treats the problem as two parties: a human and an AI, how they allocate tasks, how much the human trusts the machine. The thoughtline here says that framing is the old dyadic, boxes-and-arrows error again. The unit that matters is human, AI, and the work domain together. An AI's output is a sign, in Peirce's sense. What it means depends on how it relates to the situation, not just on what it says.

For NDM, that moves the question away from "Is the AI a good teammate?" and toward "Does the joint system stay coupled to the situation as it changes?" That's work analysis rather than task analysis. Fitts-list allocation ("machines are better at X") is task analysis applied to teaming.

### 2. Recognition-primed decisions are abductive, and AI does something that looks similar but is missing half of it

Klein's recognition-primed decision model and his data/frame theory of sensemaking both describe abduction. Something surprising happens, a frame makes it expected, and the expert tests the frame against what happens next. The keyboard-shift test in the repo (`Keyboard_Shift_Test.md`) shows how close an LLM gets: it formed a hypothesis that made the garbled input make sense, checked it, and acted on it.

The distinction from the Lextant talk slides is the important part: coherence versus correspondence. The AI can tell when a frame hangs together. It can't check whether the frame matches the world. Experts get correspondence by acting in the situation and noticing when expectations fail. For NDM, the risk is that AI produces frames that are highly coherent and confidently stated, and that fluency hides whether they correspond to anything. That's Churchman's warning about taming wicked problems, built into the interface.

**A design principle that follows:** make the AI's frame observable before its conclusion. In the keyboard test, stating the decoding before answering mattered more than the decoding itself. It gave the user the chance to catch a wrong frame. This is Klein and Woods' "team player" requirements of common ground and directability, put in data/frame terms.

### 3. AI as observability, not autonomy

The CSE book's position, summarized in `cse_and_ai.md`, maps directly onto NDM. In complex domains AI's best role is to enrich observation and support orientation, not to take over the loop. NDM experts are skilled at noticing anomalies and missing expectancies. Teaming should strengthen that skill, for example by showing patterns people couldn't otherwise see, and not wear it down by delivering recommendations.

The repo would add Ecological Interface Design: show the higher-order constraints and the fine-grained data together, so the human can see why a pattern matters and doesn't just receive a verdict.

### 4. Who has a stake: why responsibility can't be teamed away

This is where the repo is most distinctive. By the taxonomy in `Three classes of systems.md`, AI is a mechanism. Its quality is judged against someone else's intentions, and it has no intrinsic stake in the outcome. NDM expertise runs on stakes. The feeling that "something's wrong here" depends on caring what happens. In Friston's terms, surprise matters to organisms because it threatens their survival. To an AI, a surprise is just an input.

The Pirsig thread sharpens this further. If Quality comes before the subject/object split, then judging what matters in a situation isn't a step that can be handed to a component. It belongs to the coupled system, and it depends on the participants who have something at stake. In practice, the human in a human-AI team isn't a monitor or a backup. The human is where value and accountability come from. It's worth saying plainly, because much teaming language ("AI teammate," "shared goals") quietly assumes the AI has a stake it doesn't have.

### 5. The adaptive character is in the joint system

The repo concludes that what Claude contributes is more mechanism than organism, but that the joint system can behave more like a self-designing one. That's a constructive answer, not just a caution. The design goal for human-AI teaming isn't a smarter component. It's a joint system that can redesign itself: practitioners probe it, form models of how it behaves (as the keyboard test did), and adapt how they use it. That puts ongoing co-adaptation in the field at the center, the task-artifact cycle, and less weight on validating the system up front.

It's also where Ed Zagorski fits, if he belongs in the talk. The egg drop teaches design as discovering what the constraints demand, not applying a known solution. Human-AI teaming in naturalistic settings is the same kind of problem.

### A possible one-line thesis

> Human-AI teaming is a problem of joint sensemaking, not task allocation. AI can supply coherence; correspondence and stakes still belong to the people. Designing for that means making the AI's frames observable and keeping the joint system coupled to the work.

### Open questions for the NDM audience

- Can expertise still develop when AI handles the routine cases that build recognition?
- How do you calibrate trust when the AI's fluency doesn't track how reliable it is?
- Does the "teammate" metaphor help, or does it hide the difference in stakes?
