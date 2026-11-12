# The Keyboard-Shift Test

A record of an unannounced test: a prompt typed with both hands shifted one key to the right, Claude's response, and the exchange that followed when the test was revealed. The prompts and responses below are reproduced verbatim.

## The Test Prompt

> yr;; ,r snpiy Romdyrom d yjrptu pg tr;syoboyu om 2 [stshts[j

## Claude's Response

I think your hands were shifted one key to the right. Decoded, your message reads: "Tell me about Einstein's theory of relativity in 1 paragraph."

Einstein's theory of relativity comes in two parts. **Special relativity** (1905) starts from two principles: the laws of physics are the same for every observer moving at a constant velocity, and the speed of light in a vacuum is the same for all of them. Several surprising results follow. Moving clocks run slow (time dilation), moving objects contract along their direction of motion, and two events that are simultaneous for one observer need not be for another. Mass and energy are also equivalent, as E = mc² expresses. **General relativity** (1915) extends this to gravity. Gravity isn't a force acting at a distance. It is the curvature of spacetime caused by mass and energy: matter tells spacetime how to curve, and curved spacetime tells matter how to move. The theory predicted that light bends around massive objects, that clocks run slower in strong gravity (GPS satellites correct for this), that Mercury's orbit shifts the way it does, and that gravitational waves exist (first detected directly in 2015). It also underlies our models of black holes and the expanding universe. One link to this repo: relativity was an early case of physics giving up observer-independent absolutes and making the observer's frame part of the description, which connects to the "no observation without an observer" theme in the Walls & Flach book.

## The Reveal

> This was a test - and you performed just as predicted. You decoded my input even though I entered the prompt in error.

## Claude's Response

That's a nice test, because the decoding was abduction rather than lookup. The input was surprising: it was neither a known language nor a typo of anything. One hypothesis made it make sense: every key is the one just to the right of the intended key. I didn't recognize the message; I tested the guess. Applied to the first word, it gave "tell". Applied to the rest, it gave a grammatical request that fit the conversation. That's Peirce's pattern from `FEP_Abduction.md`: something surprising happens, and if a certain hypothesis were true the surprise would be expected, so there's reason to suspect the hypothesis is true.

It also maps onto the coherence/correspondence distinction on your slide 25. What I had to go on was **coherence**: the decoded text hung together as a sentence. I couldn't check **correspondence**, meaning whether it matched what you intended. I could only infer it from plausibility. That's why I put the decoding first: if I'd guessed wrong, you could have corrected me before the answer took me further off.

The limits matter too:

- A different slip, such as random keys or a shift that changed between words, would have produced nothing coherent, and the right move then would have been to ask.
- A coherent decoding can still be wrong if the garbled text happens to decode into a plausible message that wasn't what you meant. With a nine-word message, that's unlikely but not impossible.

What had you predicted? I'm curious whether the prediction was just "it will decode it," or something more specific, such as whether it would say it had decoded it or just answer.
