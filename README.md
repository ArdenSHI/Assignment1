# The Part Only You Can Hold

*Independent thinking across three stages of making a work*

I make things — tools, art projects, installations — and this year enrolled in a programming course for designers and artists. In 2026, a system can write working code from a sentence of English and gets better every six months. The polite answers to *why are you here?* do not satisfy me. I am not looking to defend the course; I want to describe what I think will survive.

To make something genuinely worth making, you need an understanding that only forms when programming experience and design experience meet in the same person and produce their own thing. Most of the projects I make with AI follow the same three stages: finding inspiration, refining inspiration into a structure, producing the finished product. Each stage calls for different sub-skills, but they all belong to the same category: independent thinking. I will walk through the three stages using concrete projects, then close on how I think this ability is built.

## Finding inspiration

For finding inspiration, the most important ability is to use AI for ideas without being pulled off course by its first suggestions, and without letting it agree with whatever you say to keep the conversation going. Both failures end with you losing your judgement.

I learned this on a VR game I was prototyping. I had a long brainstorm with an AI; my real contribution was asking one broad question. The AI gave me a long list, I picked one that was *fine* — and not mine. As soon as I asked it to extend that one, the other ideas dropped away and the direction kept narrowing.

I closed the AI and wrote my own outline from what I already knew about 3D games. I stripped the labels and gave both outlines — the AI version and mine — to my teacher and several classmates, asking only which they would rather play. They picked mine. A few pieces in the final version did come from the earlier AI conversation, but the combination is mine. That combination, not the fragments, is what they preferred.

The lesson is that the AI's first answers are dangerous not because they are bad but because they are plausible, and the model agrees with you too easily. When it stops offering alternatives, you have already lost something.

## Refining inspiration into a structure

The second stage is turning the core idea into a plan. Most modern AIs have a planning function; given a clear goal, they can break the task into subtasks and execute on their own. The core steps are usually right — scaffolding an HTML page, setting up an asset library. What a plan tends to miss, however, are the small things: features that are not critical for v1 but quietly shape the result.

This is where project management comes in. You need to notice what the planner missed, decide which gap belongs in which version, and lay out the overall timeline — what is left for v2, what makes v1 acceptable, what proves each step worked. Across every non-trivial project I have run — the VR game, a museum installation, several e-commerce builds — the core trajectory was mine. The AI gave a first draft of the plan; the testing methods, rollout steps, and success metrics at each stage were the plan I built.

## Producing the finished product

Production is where AI helps most, because the blueprint is set and execution is the most controllable part. The result just needs to match what the blueprint requires and run reliably. The most important ability here is the simplest in words: you need to read what the AI wrote well enough to know whether it does what it claims.

I worked with an AI on a tool for managing complex SKUs for a phone-case e-commerce business. Its job was to take inconsistent product names and rename them into a tidy internal format. I gave it my test cases and the output was fully correct, so I trusted it. When I ran it on a real export, the output was a mess — and worse, the tool had no backup step and overwrote my original file. I had to ask a colleague for a fresh copy.

Going back, the bug was easy to see. The renaming logic only handled the common naming formats. A few rare formats I had left out of the test set produced identical outputs, so different products collided and the whole sheet fell apart. There was no backup step either. Neither would have shown up in any test I could have written, because I do not know enough about that part of the stack to imagine them. The lesson was not better tests; it was that without the ability to read the code, no test I design catches what I cannot imagine.

## How to build this ability

Walking back through the three stages, the skill that runs underneath them — the one that decides whether you ignore AI's first idea, whether you catch the gap in its plan, and whether its *it works* is actually *it works* — is independent thinking. It is the same skill wearing different clothes in each stage.

How is it built? That is the reason I am here. I am not here to learn a syntax that will be obsolete by forty. I am here to learn the fundamentals — technical, design, creative — and keep adding to them every day, so that my thinking grows the branches it needs to drive the machine rather than be carried by it. As Don Ihde argues, technologies are never neutral: they shape what their users perceive as possible [1]. A tool you cannot read is a tool that decides for you.

The only durable answer, for someone who wants to keep making things worth making, is to keep getting more capable in the parts the machine cannot hand you.

---

## References

[1] D. Ihde. 1990. *Technology and the Lifeworld: From Garden to Earth*. Indiana University Press, Bloomington, IN.

[2] L. Manovich. 2001. *The Language of New Media*. MIT Press, Cambridge, MA.

[3] A. A. Lovelace. 1842. Notes by the Translator upon L. F. Menabrea's "Sketch of the Analytical Engine Invented by Charles Babbage". *Scientific Memoirs*, 3. https://www.fourmilab.ch/babbage/sketch.html

[4] D. Beattie. 2019. *The Art of Code*. YouTube. https://www.youtube.com/watch?v=6avJHaC3C2U
