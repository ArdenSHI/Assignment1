# Nobody's Screensaver

*On the skill between describing and specifying*

Anyone can ask for "a generative poster that feels unsettling." The question I want to answer is what it takes to actually get one — whether that skill is programming, design, or something new.

My answer: it's something new, but something made out of the other two. It is the ability to hold programming experience and design experience in the same head and let them correct each other — an independent understanding that neither discipline produces on its own. I couldn't have written that sentence a year ago. I learned it from watching how my own work actually gets made.

## Three stages, one gap

Almost everything I make with AI — small practical products, art pieces — decomposes the same way: finding inspiration, refining it, producing the finished thing. Inspiration is taste doing its quiet work: references, half-images, a pull toward something not yet nameable. Production is patience: packaging, edge cases, shipping. Neither stage is where a programming course lives.

The interesting stage is refinement, and it is exactly the gap between describing and specifying.

Earlier this year I built a generative piece with an AI assistant: shapes drifting across a browser canvas. My prompt asked for something "organic and unsettling." What came back was a lava lamp — smooth blobs, a purple gradient, a screensaver. It wasn't wrong. It was nobody's: the average of every "unsettling" ever requested.

The turn came when I could say *why* it was nobody's. The motion was too smooth, because nothing organic moves at constant velocity. The palette was pleasant, when I wanted it slightly sick. The shapes had only group behaviour, no individual life. Those are design judgements — I could not have made them without a trained eye. But each one only became *fixable* through programming knowledge: the smoothness was an easing function; "slightly sick" meant shifting a hue rotation by a specific amount; individual life meant giving each shape its own noise seed instead of a shared one. The request that finally produced something I wanted was not a sentence a designer alone, or a programmer alone, could have written. It took both, at once, in real time.

That is the skill. Not writing code, and not having taste — running the loop between them: see the output, judge it aesthetically, specify the fix mechanically, repeat.

## What each side contributes

Programming gives you the material. Don Ihde's argument that technologies are never neutral — that they shape what their users perceive as possible (Ihde, 1990) — has a sharp edge here: a generative system's possibility space is enormous, but a prompt can only navigate it if you know its coordinates. If you don't know that seeds, easing functions, and hue rotation exist, you can't ask for them, and the defaults become invisible walls that look like the whole world.

Design gives you the target. You cannot specify what you cannot discriminate. The lava lamp looked fine until I could see exactly how it failed — and that seeing is trained, not given.

Lev Manovich argues that the twentieth-century avant-garde didn't die; it became software, its experiments compiled into the default settings of our tools (Manovich, 2001). If that's true, the defaults literally encode design history, and escaping them takes someone who can both read what is encoded and imagine what isn't. Ada Lovelace saw past the Analytical Engine's stated purpose to what it could become (Lovelace, 1842); Dylan Beattie's delight in code as a *human* language — written to be read, punned in, played with (Beattie, 2019) — points the same way: code is a medium for thought, not just a means of production. The new skill is thinking in that medium without letting it do your thinking for you.

## So why I'm here

I watch my friends split cleanly. The designers who won't touch code keep receiving defaults, executed professionally. The programmers who don't make things keep shipping technically correct mediocrity. Both are competent; both are replaceable by exactly the systems this course teaches us to use.

The syntax I learn this semester will probably be obsolete by the middle of my career, and I'm at peace with that. What I'm actually here to build is the refinement loop — the judgement plus the mechanism, held together. The machine will write the program. It will not notice that the motion is too smooth, or that the green is slightly sick. Noticing that, and knowing what to ask for next, is still a job.

---

## References

Beattie, D. (2019). *The art of code* [Video]. YouTube. https://www.youtube.com/watch?v=6avJHaC3C2U

Ihde, D. (1990). *Technology and the lifeworld: From garden to earth*. Indiana University Press.

Lovelace, A. A. (1842). Notes by the translator upon L. F. Menabrea's "Sketch of the Analytical Engine invented by Charles Babbage". *Scientific Memoirs, 3*. https://www.fourmilab.ch/babbage/sketch.html

Manovich, L. (2001). *The language of new media*. MIT Press.
