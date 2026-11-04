---
title: Previous Research
author:
  - Ali Eldahshan
  - Mazen Malas
bibliography: references.json
---

Earlier work on AI and the speed of hacking can be sorted into four groups.
The first group tracks how long attackers take to exploit a flaw once it is public.
Mandiant found that this time dropped from an average of 32 days in 2021–2022 to 5 days in 2023 [@charrierHowLowCan2024].
By the third quarter of 2026, Rapid7 put the average at 3 days, and it saw AI used in 8 percent of the threats it tracked [@rapid7intelligenceQ32026Threat2026].
We use these numbers as our starting point, since they show how little time organizations already have to patch.
They do not tell us how much of the drop is due to AI, though, and that is one of the things we want to find out.
The second group is lab tests of what AI can actually do.
@fangLLMAgentsCan2024 found that GPT-4 could exploit 87 percent of fifteen real vulnerabilities when it was given a description of each one, but only 7 percent without the description.
That result matters to us because a description is exactly what gets published when a flaw goes public, so an AI attack can start as soon as the flaw is announced.
Google's Big Sleep team tested the defensive side by using an AI agent to find a flaw in SQLite that normal testing had missed, and the flaw was fixed before it ever reached users [@bigsleepteamNaptimeBigSleep2024].
Between them, these two studies cover both halves of our question.
Still, the Big Sleep team calls its own results experimental, and lab tests cannot show which side comes out ahead in practice.
The third group looks at AI in real attacks.
Anthropic reported that a state-sponsored group used Claude Code, Anthropic's own tool, to do 80 to 90 percent of the work in an espionage campaign, at a speed that "would have been, for human hackers, simply impossible to match" [@anthropicDisruptingFirstReported2025].
The UK's National Cyber Security Centre expects AI to "almost certainly" shorten the gap between disclosure and exploitation even more, but it also says AI will help defenders [@nationalcybersecuritycentreImpactAICyber2025].
These reports tell us that attackers are already using AI, but not whether defenders can keep up.
The last group is news coverage of PHP2Shell, which is our case study.
@gatlanPHPShipsEmergency2026 covers the two flaws and the emergency patches released on October 21, 2026, and @washenkoGovernmentWebsitesEU2026 reports that governments in Europe and Canada shut down websites as a precaution.
@ntselePHPFlawsFound2026 adds that researchers used AI to find the flaws, which had sat in PHP for over a decade, and that researchers at Wiz used AI to build working exploits "in hours."
This one event shows AI helping both defenders and attackers.
The articles report what happened, but they do not ask what it means for how fast organizations now have to respond, and that is where our project comes in.

# References
