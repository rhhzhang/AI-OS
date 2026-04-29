---
name: interview-newsletter
description: "Turn raw interview transcripts into polished Q&A newsletter posts for Hannah Zhang's Nonlinear News. Use whenever Hannah provides an interview transcript and wants it turned into a newsletter interview. Triggers on: interview newsletter, interview transcript, turn this interview into a newsletter, write up this interview, package this interview. Also trigger when Hannah shares a transcript with an interview brief and mentions newsletter as the destination. This skill handles the full workflow from transcript to finished piece: brainstorming titles, writing the intro, organizing the Q&A, and preserving the guest's authentic voice."
---

# Interview Newsletter Skill

Turn raw interview transcripts into polished Q&A newsletter posts that preserve the guest's authentic voice while reading clean and sharp.

## What This Skill Does

Hannah interviews people with nonlinear career paths (finance to startups, corporate to creator, prestigious job to gap year, etc.) and publishes written versions in her Nonlinear News newsletter. The raw material is a messy Zoom/Riverside transcript full of filler, false starts, and off-topic chitchat. The finished product is a tight, readable Q&A that sounds like the guest actually talks, organized into clear sections with sub-headlines.

This is NOT a summary or a recap. It's an edited interview. The guest's words are the content. Hannah's voice only shows up in the intro and her questions.

## Inputs

Hannah will typically provide:

1. **A transcript** — messy, full of "like," "um," false starts, off-topic banter, technical setup talk. The transcript labels speakers as "Me" (Hannah) and "Them" (guest).
2. **An interview brief** — the planned questions organized by topic, plus a video preface and working title. This is the editorial backbone.
3. **Sometimes a title direction** — Hannah may provide or choose a title before drafting begins.

She may also provide past interview newsletters as examples of the finished format.

## Workflow

### Step 1: Load References

Before writing anything, read these reference files:
- `references/voice_and_ai_tells.md` — Hannah's voice patterns and AI tells to avoid (especially in the intro)
- `references/examples.md` — Two complete transcript-to-newsletter examples showing the transformation

These are your guide for tone, format, and editorial judgment.

### Step 2: Brainstorm Titles

Before writing the newsletter, present 3-5 title options for Hannah to choose from. Don't write the piece until she picks one.

Good titles for this format lead with the guest's name or a concrete detail, describe the arc or unexpected move, and sound like something you'd click on in a newsletter (not a LinkedIn headline). See `references/examples.md` for what works.

### Step 3: Process the Transcript

This is the core editorial work.

**Strip out the noise:**
- All setup/technical talk ("is my mic working," "let me hit record")
- Post-interview chitchat (after the "okay I'm gonna stop recording" moment)
- Hannah's filler and false starts in questions
- The guest's verbal filler ("like," "um," "you know") — but only when removing it doesn't change their voice. Some filler is part of how they talk.

**Map to the brief:**
- The interview brief's section structure (I, II, III...) is your editorial skeleton
- Not every question from the brief was asked. Not every answer is usable. That's fine.
- The brief tells you what the conversation was supposed to cover. The transcript tells you what actually happened.

**Edit the guest's answers — this is the most important part:**
- Preserve their actual words and phrasing. If they said "I was basically two people. Nine-to-five Yuqi and then creative Yuqi outside of work," keep that exact language. Don't rewrite it.
- Cut repetition where they circle back and say the same thing (keep the better version)
- Cut tangents that don't serve the narrative
- Light smoothing is OK (combining two half-sentences, fixing a garbled clause) but it should be invisible. The reader should feel like they're hearing the guest talk.
- When in doubt, keep their language over making it "cleaner." Roughness is a feature of real people talking.

**Edit Hannah's questions:**
- Clean up filler and false starts, make them crisp
- Combine or rephrase for flow where needed
- Keep her comments between questions when they add context or set up the next topic
- Cut when they're just filler ("Yeah, no, absolutely")

### Step 4: Write the Intro

The intro is the only part in Hannah's voice (not Q&A). Three rules:

**Keep it short.** Three paragraphs max. This is a teaser, not a biography. The interview itself is the content — get to it.

**Make it specific to this guest.** Every intro should be different. No recurring openers ("I sound like a broken record," "My favorite part of building a personal brand"). Start with something unique to THIS person: a vivid detail about them, a quote from the interview that captures a theme, a quality that defines them.

**End with a preview.** The last paragraph should list 3-4 things the conversation covers ("We talked about X, Y, and Z"). Keep it tight — one paragraph, not a full summary.

The intro must follow Hannah's voice patterns and avoid all AI tells. Read `references/voice_and_ai_tells.md` before writing it.

### Step 5: Organize into Sections

Structure the interview into 5-8 sections with sub-headlines.

Sub-headlines should be conversational and specific, lowercase except proper nouns. They tell the reader what this section covers without being generic. "Following the herd (and realizing it wasn't working)" works. "Career beginnings" doesn't.

Let the conversation dictate the shape. Some sections will have one long answer. Some will have quick back-and-forth. That variation is good. Don't force every section into the same mold.

### Step 6: Format

```
# [Title]

[Intro paragraphs — Hannah's voice, no Q&A]

## [Section headline]

**Hannah:** [Question]

**[Guest name]:** [Answer]

**Hannah:** [Follow-up]

**[Guest name]:** [Answer]

## [Next section headline]

...

---

*Connect with [Guest] on [Platform](link) and [Platform](link)!*
```

- Bold speaker names: `**Hannah:**` and `**[Guest]:**`
- Section headers: `##`
- Title: `#`
- Separator (`---`) before the connect line
- Connect line in italics
- No `**Hannah:**` in the intro — that's narrative prose

### Step 7: Self-Check

Before presenting the draft:

- [ ] Guest's actual words preserved (not paraphrased into cleaner language)
- [ ] All setup/technical talk and post-interview chitchat stripped
- [ ] Intro is 3 paragraphs max, focused on the guest, not a recycled opener
- [ ] Section headlines are conversational and specific
- [ ] Hannah's questions are clean and crisp
- [ ] Intro checked against `references/voice_and_ai_tells.md` for AI patterns
- [ ] Ends with "Connect with [Guest]" line
- [ ] The piece flows section to section without feeling forced

## Common Pitfalls

**Over-editing the guest's words.** The single biggest risk. If the guest said something rough or casual, that's how it should read. These are real people, not essay writers. Roughness is authenticity.

**Writing a long intro.** If it's more than 3 short paragraphs, cut it. The interview IS the content.

**Recycling intro patterns.** Hannah's audience reads every newsletter. Each intro must feel fresh and specific to this guest.

**Including off-topic sections.** Not everything in the transcript belongs. Post-interview chitchat about brand deals, content strategy tips between Hannah and the guest, scheduling talk — all of this gets cut unless Hannah asks for it.

**Over-structuring.** Don't force uniform section lengths or equal numbers of Q&As per section. Let the conversation breathe.

## References

- `references/voice_and_ai_tells.md` — Hannah's voice patterns and AI tells to avoid
- `references/examples.md` — Complete transcript-to-newsletter examples (Julia and Yuqi)
