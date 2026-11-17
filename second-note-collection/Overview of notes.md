# Overview

## Organizing Questions

My partner Mazen Malas and I are researching whether AI helps the people who find and fix security flaws more than the people who exploit them.
We also want to know how AI changes the amount of time organizations have to install a fix once a flaw goes public.
Our case study is PHP2Shell, two flaws in PHP that AI tools found after they had been there for more than ten years, which led governments to take websites offline in October 2026 (Ntsele 2026).

## Sources

Our project uses eleven sources, but for this collection I picked the four that actually test or forecast what AI can do, because they deal most directly with which side AI helps.
Each one comes from a different place.
Fang et al. is a university lab testing attacks, Big Sleep is a Google team testing defense, Anthropic is an AI company reporting a real attack, and the NCSC is a government agency forecasting both.
I only cite Ntsele (2026) in the commentary, to connect the notes back to PHP2Shell.

## How My Focus Changed

The notes go from lab results to a real attack to a forecast.
When I started, I was mostly looking at how fast AI can attack, but Fang’s cost section (note 3) and the Anthropic campaign (note 6) made me think the bigger change is scale, since one attacker can now go after thousands of targets at once.
The NCSC report changed my focus again, from thinking of “defenders” as one group to seeing a divide between strong and weak defenders (note 10).

## Subject Terms

This time I reused subject terms on purpose.
“Patch window,” meaning the time between disclosure and a patch actually being installed, shows up in eight notes because it’s the main idea of our claim.
“Offense–defense balance” shows up in six and marks the notes that help answer which side AI favors.
Terms that only appear once, like “fuzzing” and “digital divide,” mark places where one source added something new.

## Connections and Takeaways

The biggest connection across the notes is that finding a flaw is harder than exploiting one that’s already known (notes 2, 4, 5, and 9).
That explains why the evidence for defense is more cautious than the evidence for attacks, and it backs up our claim that AI helps the two sides at different times.
I also ended up disagreeing with my sources more than I expected, especially Fang’s “Fortunately” (note 2) and Anthropic’s advice for defenders (note 8).

## Process

Based on the feedback from my first collection, I changed three things.
I picked passages I could argue with instead of ones I could only summarize, I added context in brackets whenever a quote used words like “we” or “it,” and I tried to make each commentary take a position instead of restating the quote.

## Next Steps

The biggest gap in my research right now is evidence that AI helps organizations install patches faster, not just find flaws (note 8).
I also need newer results on AI finding flaws than Big Sleep’s 2024 post (note 5), and I plan to read the follow-up report the NCSC published in November 2026.
Mazen and I share the project’s sources and storyboard, but we each wrote our own note collection.

## AI Disclosure

I used Claude Code (Anthropic) to prepare this collection.
It checked every quotation word for word against the full text of each source, helped me come up with arguments and to veryfiy they made sense, suggested the subject titles, formatted the Chicago citations, and revised the wording, spelling, and grammer etc.
I used it to fix the three problems from my first collection: quotes without context, commentary that only summarized, and too little keyword overlap.
