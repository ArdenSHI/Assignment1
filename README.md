# The Part Only You Can Hold

*On independent thinking across three stages of making a work.*

The question, bluntly: I make things — products, art pieces, installations — and I have enrolled in a programming course in 2026, when systems write working code from a sentence of English and get better every six months. The polite answers feel thin. I don't want to defend the course; I want to describe what survives.

For me, the thread worth pulling on is this: to make something genuinely worth making, you need the understanding that only forms when programming experience and design experience meet in the same person and produce their own thing. Almost everything I make with AI follows three stages — finding inspiration, refining it into a structure, producing the finished thing — and underneath each, it is the same: independent thinking, the part the machine cannot do for you.

## Finding inspiration: don't let the first answer win

The first stage looks like the easiest, and the trick is that AI's *first* answer is the most dangerous one — not because it is bad, but because it is too plausible. You ask a vague question, it gives you a confident cluster of options, and you pick the one you like best. By the time you do, you have stopped thinking.

I learned this at the start of a VR game I was prototyping. I asked an AI to brainstorm; it produced a long list. I picked one that was *fine* — and not my own. When I asked it to push that idea deeper, the other ideas vanished. I closed the AI and wrote a draft outline by hand, from what I already knew about 3D games. I gave both outlines — labels stripped — to my teacher and several classmates, asking only which they would rather play. They picked mine. A few pieces in the final version came out of that earlier conversation, but the *combination* was mine — and that combination, not the fragments, is what they preferred.

The danger is not the AI's ideas but how naturally it agrees with you. Watch for the moment it stops offering alternatives — you have probably already lost something.

## Refining into structure: the project is the gaps

Once the core idea is firm, the next stage is structural. Modern AI tools are good at this — give them a clear goal and they will plan their own task lists. The *core* steps are usually right (scaffolding an HTML site, setting up a game asset library); the rest is usually missing.

What the plan misses, in my experience, are the *small* things: lower-priority features whose absence won't kill v1 but quietly shapes the final experience. Manovich's argument that the twentieth-century avant-garde became software, that previous decades of design now live as our tools' defaults (Manovich, 2001), is why these gaps matter: the defaults encode assumptions about what a project is for, and you cannot see what you cannot name.

The skill you need is project management — noticing what the planner missed, deciding which gap goes in which version, and how the timeline folds together. For every non-trivial project I have shipped — the VR game, a museum installation, a few e-commerce builds — the core trajectory was mine. The AI gave me a first draft of the plan; the rest — what each version optimises, what each milestone produces, what proves each step worked — is the work I did.

## Producing: the trap called "it passed the test"

Production should be the safest stage. The blueprint is set, the AI executes against it, and you check the result. The most important capability is also the simplest in words: you have to be able to *read what the AI wrote* well enough to know whether it does what it claims.

I once built, with an AI, a tool for renaming messy product names into a tidy format for a phone-case e-commerce business. I gave it my test cases; it worked perfectly, so I trusted it. The first time I pointed it at a real export, it produced total chaos — and worse, had written back over my original file with no backup. I had to ask a colleague for a fresh copy.

The bug was obvious in retrospect. The renaming logic only handled the common name formats; several rare formats I had left out of the test set produced identical output names, so different products collided. There was no backup branch either. Neither problem would have shown up in any test I would have written, because I do not know enough about that part of the stack to imagine them. The lesson was not to write better tests — it was that, without the ability to read the code, no test I design will catch what I cannot imagine.

## How to build it

So the skill running through all three stages — the one that tells you when to ignore AI's first idea, when its plan is missing something, and when its "it works" is not actually "it works" — is independent thinking. The same skill in different clothes.

How is it built? That is what I think this course is for. I am not here to learn an obsolete syntax. I am here to learn the fundamentals — technical, design, creative — and keep adding to them every day, so that the tree of my thinking grows enough branches to drive the machine rather than be carried by it. Don Ihde's observation that technologies are never neutral (Ihde, 1990) has a practical edge here: a tool you cannot read is a tool that decides for you.

The machine gets more capable every six months. The only durable answer, for someone who wants to make things worth making, is to keep getting more capable yourself, in the parts the machine cannot hand you. That is the part only you can hold.

---

## References

Beattie, D. (2019). *The art of code* [Video]. YouTube. https://www.youtube.com/watch?v=6avJHaC3C2U

Ihde, D. (1990). *Technology and the lifeworld: From garden to earth*. Indiana University Press.

Lovelace, A. A. (1842). Notes by the translator upon L. F. Menabrea's "Sketch of the Analytical Engine invented by Charles Babbage". *Scientific Memoirs, 3*. https://www.fourmilab.ch/babbage/sketch.html

Manovich, L. (2001). *The language of new media*. MIT Press.
