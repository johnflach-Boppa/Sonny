# Lextant Talk (11 Nov) — Critique and Suggestions

**Question:** Can you critique and make suggestions for improvements to the Lextant\*.pptx slides?

Review of `Lexant Talk 11 Nov.pptx` (31 slides). PowerPoint's PDF export couldn't be scripted, so the deck was never fully rendered. This review is based on the embedded images and on each slide's layout data (positions, sizes, font sizes). Slides 19–21 hold EMF figures that couldn't be rendered and are not reviewed.

The filename is spelled **"Lexant"**, missing the second "t". It's worth fixing before the deck goes to Lextant.

## Overall

**What works.** The argument is strong and well paced:

- The "hats" opening sets up a personal story.
- "What's new (different)?" comes back four times as a signpost (slides 7, 10, 14, 23). Each time it adds a new overlay to the same table: Miller & Simon, then Rasmussen and productive thinking. That's an effective recurring device.
- The talk moves from the triad to the abstraction hierarchy to design challenges and then to AI.
- The cartoons on slides 15 and 22 ("Holy crap – I don't even know the acronyms", "There goes 40 years of work domain analysis out the door") are the most memorable slides in the deck.

**1. The audience link is mostly implicit.** Lextant does design research and UX. Slide 4's design-space figure is the only slide that names UX, and it shows UX as a separate box from CSE. I'd add one slide near the start and one near the end that answer "what changes in *your* practice?" For example, work analysis versus user personas, or "shape mental models, don't just match them." Slide 26 already includes a consumer-health example (the cardiovascular risk calculator), and that's the bridge to their work. Give it a title and talk it through.

**2. Several slides have no takeaway headline.** Slides 5, 6, 8, 9, 11, 12, 13, 25, 26, 29 and 31 have no title. In a live talk you can narrate them. But if you share the deck afterward, these slides won't make sense without you. Short headlines that state the claim would help, such as "Same plant, two eras of interface" or "Symmetry makes the fault visible."

**3. Diagram text is too small for a room.** Slides 8–9 (information processing vs. closed loop) and slide 13 (nested control loops, about 45 shapes) use 10pt labels. Those won't be readable past the first few rows. Two options:

- Build them up across 2–3 slides, the way you already did with slides 24 → 27 → 28.
- Enlarge the labels to at least 14pt and drop the "e.g." lines.

**4. Low-resolution images are stretched large and will look blurry on a projector:**

- **Slide 6:** the background control-room photo is 480 px wide, stretched to full screen.
- **Slides 7/10/14/23:** the Information vs. Meaning Processing table is a 720 px screenshot at 11". This is the most-repeated slide, so it's the most important to fix. Rebuild it as real text, with each later addition revealed as an overlay.
- **Slide 25:** the polar-graphic display is 281 px stretched to 6.6" tall.
- **Slide 26:** the four EID examples are a single 720 px image at full width, so their labels are unreadable.
- **Slide 17:** the aircraft abstraction hierarchy is dense, and its caption ("Figure 1. Abstraction Hierarchy of ownship") is cut off at the bottom.

**5. The ending is unclear.** Slide 30 repeats the title slide, and then slide 31 (the semiotic-triad puzzle) comes after it. Either move 31 before 30 as the closing synthesis, or hide it as a backup slide. The closing slide would also work better as three takeaways plus contact details than as a copy of the title slide.

## Errors to Fix

| Slide | Problem | Fix |
|---|---|---|
| 9 | "C.S. **Pierce**" | Peirce |
| 14 | "Karl **Dunker**", "Otto **Seltz**", "Adrian De Groot" | Duncker, Selz, Adriaan de Groot |
| 2–3 | The quote "I just kept inventing fields, so that I had a home" sits above the Hollnagel & Woods (1982) citation, which makes it look like the quote comes from that paper | Name the speaker beside the quote and keep the citation for the CSE claim. The journal version is *IJMMS*, 1983 |
| 16–18 | The level names change from slide to slide: "General Function" (16), "Generalized Function" (17, AD space), "Physical Form" vs. "Physical **Anatomy**" (18) | Pick one set of names. Five consecutive slides on the abstraction hierarchy will make the audience notice the differences |
| 1 / 16 (AD-space figure) | "Rational for why" and "physical means for accomplish" | "Rationale for why" and "physical means for accomplishing" |
| 11 | The scanned decision ladder has "INTERPTRE" baked in from the original figure | Redraw it, or acknowledge the original. It's projected large |
| 27 | The *Abduction and Induction* cover (eds. **Peter** A. Flach & Kakas) appears without a label | If AI = Abduction + Induction is the joke, say so on the slide. Otherwise people will think it's your book |
| 17, 22–26 | Several borrowed figures (the aircraft AH, the NuScale photo, the EID examples) have no source | Add small source lines |
| 26 | A stray line shape is 21" wide and runs off the right edge of a 13.3" slide | Delete it |
| 4 | The title box (to 4.61") overlaps the left edge of the figure (from 4.01"), where the "Agency Constraints" label sits | Narrow the title box or move the figure right |

## Smaller Suggestions

- **Slide 12** (skill/rule/knowledge-based nested arrows): this is the clearest bridge to slide 13. Say "same structure, now an organization" out loud, or put the two slides side by side.
- **Slides 24 → 27 → 28:** a good build. On slide 28, though, six labels float around the triad with no connectors. Tie each label to a vertex: Transparency to the representation, Trust to the belief, Utilization to the ecology. Then the AI challenges map onto the triad the whole talk has built.
- **Slide 29** (RAG pipeline) is the only concrete "here's what we're building" slide. It deserves a title and a sentence on why CSE curators make the pipeline better than plain RAG.
- **Fonts:** the theme uses Aptos, which isn't installed on older Office versions. If presenting from Lextant's machine, test the deck there, or embed fonts.
- **Speaker notes:** none of the 31 slides has any. Since so much of the meaning is in the narration, a line or two per slide would help if the deck is shared afterward.
