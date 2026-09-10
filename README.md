# The Part Only You Can Hold

*Independent thinking across three stages of making a work*

In 2026, I make things with AI — tools, art projects, installations — and enrolled in the programming course. A system writes working code from a sentence and gets better every six months. This essay is not a defence of the course; it is a description of what I think survives.

To make something worth making, you need an understanding that only forms when programming experience and design experience meet in the same person and produce their own thing. Most of my projects follow three stages: finding inspiration, refining inspiration into a structure, producing the finished product. Each stage calls for different sub-skills, but they all belong to independent thinking. I will walk through the three stages using projects I have actually run, then close on how this ability is built.

## Finding inspiration

For finding inspiration, the most important ability is to use AI for ideas without being pulled off course by its first suggestions, and without letting it agree with whatever you say to keep the conversation going. Both end with you losing your judgement.

I learned this on a VR game I was prototyping. I had a long brainstorm with an AI; the prompt I gave was broad and vague. The AI gave me a long list, I picked one that was *fine* — and not mine. As soon as I asked it to extend that one, every other direction was dropped and the idea kept narrowing.

So I closed the AI and wrote my own outline from scratch, drawing on what I already knew about 3D games. I stripped the labels and gave both outlines to my teacher and several classmates, asking only which they would rather play. They picked mine. A few pieces in the final version did come from the earlier AI conversation, but the combination is mine.

The lesson is that the AI's first answers are dangerous because they are plausible, and the model agrees with you too easily. When it stops offering alternatives, you have already lost something.

## Refining inspiration into a structure

The second stage is turning the core idea into a plan. Most modern AIs have a planning function; given a clear goal, they can break the task into subtasks and execute on their own. The core steps are usually right — scaffolding an HTML page, setting up an asset library. What a plan tends to miss are the small things: features that are not critical for v1 but quietly shape the result.

This is where project management comes in. You need to notice what the planner missed, decide which gap belongs in which version, and lay out the overall timeline — what is left for v2, what makes v1 acceptable, what proves each step worked. Across every non-trivial project I have run — the VR game, a museum installation, several e-commerce builds — the core trajectory was mine. The AI gave me a first draft of the plan; the testing methods, rollout steps, success metrics, were the plan I built. As Manovich argues (Manovich, 2001), previous decades of design now live as our tools' defaults, so they encode assumptions about what a project is for. You cannot see what you cannot name, and the planner cannot name it for you.

## Producing the finished product

Production is the stage where AI helps most, because the blueprint is set and execution is the most controllable part. The result only needs to match the blueprint and run reliably. The most important ability here is the simplest in words: you need to read what the AI wrote well enough to know whether it does what it claims.

I worked with an AI on a tool for managing complex SKUs for a phone-case e-commerce business. Its job was to rename inconsistent product names into a tidy internal format. I gave it my test cases and the output was fully correct, so I trusted it. When I pointed it at a real export, the output was a mess — and worse, the tool had no backup step and overwrote my original file. I had to ask a colleague for a fresh copy.

Going back, the bug was easy to see. The renaming logic only handled the common formats. A few rare formats I had left out of the test set produced identical outputs, so different products collided and the whole sheet fell apart. There was no backup step either. Neither would have shown up in any test I could have written, because I do not know enough about that part of the stack to imagine them. The lesson was not better tests; it was that without the ability to read the code, no test I design catches what I cannot imagine.

## How to build this ability

Walking back through the three stages, the skill that runs underneath — the one that decides whether you ignore AI's first idea, whether you catch the gap in its plan, and whether its *it works* is actually *it works* — is independent thinking. Same skill, in different clothes.

How is it built? That is the reason I am here. I am not here to learn a syntax that will be obsolete by forty. I am here to learn the fundamentals — technical, design, creative — and keep adding to them every day, so that my thinking grows the branches it needs to drive the machine rather than be carried by it. As Ada Lovelace saw before any code ran (Lovelace, 1842), seeing past a tool's stated purpose to what it could become is itself a skill; programming just made the tool very fast. Dylan Beattie frames code as an expressive medium (Beattie, 2019); the part that survives is the human who can describe what they want precisely enough to build it.

The only durable answer is to keep getting more capable in the parts the machine cannot hand you.

---

## References

Beattie, D. (2019). *The art of code* [Video]. YouTube. https://www.youtube.com/watch?v=6avJHaC3C2U

Ihde, D. (1990). *Technology and the lifeworld: From garden to earth*. Indiana University Press.

Lovelace, A. A. (1842). Notes by the translator upon L. F. Menabrea's "Sketch of the Analytical Engine invented by Charles Babbage". *Scientific Memoirs, 3*. https://www.fourmilab.ch/babbage/sketch.html

Manovich, L. (2001). *The language of new media*. MIT Press.
