---
title: Bringing a Character to Life with Firefly Boards
date: 2026-02-02
tags:
  - animation
  - tutorial
  - "#toolstack"
  - firefly
slug: making-a-looping-gif-with-fresco-firefly-and-express
description: No budget, no studio, no problem — how I take a character from rough sketch to finished animation with Firefly Boards.
draft: false
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/0rl6V5HxOFk?si=J1-9az3qzf_cgY3g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### "But would it still be your cartoon?"

That's the question I get a lot. If AI is doing the heavy lifting, is it really mine?

Short answer: yes. Long answer: this whole video.

---

## The quick version

- **Fresco** — rough out a character illustration. This is my reference, not a throwaway.
- **Firefly Boards + Image 5** — bring the illustration in, prompt with real design language (cinematic lighting, texture, the stuff you already know), generate variations.
- **Photoshop** — color correct and tighten up the pick I like. Faster to just do it myself than keep re-prompting.
- **Boards + Gemini 3** — reference the corrected image, add "character turnaround" to the prompt, get a character sheet for consistency.
- **Boards, again** — prompt out props and scene work around the character.
- **First and last frame** — generate a start and end state so the video model has something to hold onto.
- **Ray 3** — the model that actually kept the character consistent across the generation, after testing it against Gemini, Firefly, and Sora.
- **Premiere Pro** — sound design, color, final touches.

---

## Design principles still apply

Just because it's Gen AI doesn't mean the fundamentals go out the window.

> Just because it's Gen AI doesn't mean you can abandon the design principles you spent years mastering.

Prompting well is still art directing. If you know what "cinematic lighting" actually looks like, you'll get better results than someone just typing keywords and hoping.

---

## Grounding the video with first and last frame

Generative video has a habit of drifting from your character the longer it runs, especially off a single reference frame. My workaround: generate a first frame and a last frame, and let the model fill in the middle.

For this one, that meant a character asleep on a porch in winter for frame one, and the same character awake, coffee in hand, snow melting, for frame two. Small narrative built right into the technical constraint.

---

## Picking a model

I ran the same generation across Gemini, Firefly, and Sora before landing on **Ray 3**, which held onto character consistency the best of the bunch. Worth testing your options — the "best" model changes depending on what you're making.

---

Full walkthrough is in the video above. If you've got a character or a cartoon idea you've been sitting on, I want to hear about it — drop it in the comments.