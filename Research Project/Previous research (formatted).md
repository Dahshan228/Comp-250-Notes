# Previous Research

Ali Eldahshan and Mazen Malas

Earlier work on AI and the speed of hacking can be sorted into four groups. The first group tracks how long attackers take to exploit a flaw once it is public. Mandiant found that this time dropped from an average of 32 days in 2021–2022 to 5 days in 2023 (Charrier and Weiner 2024). By the third quarter of 2026, Rapid7 put the average at 3 days, and it saw AI used in 8 percent of the threats it tracked (Rapid7 Intelligence 2026). We use these numbers as our starting point, since they show how little time organizations already have to patch. They do not tell us how much of the drop is due to AI, though, and that is one of the things we want to find out. The second group is lab tests of what AI can actually do. Fang et al. (2024) found that GPT-4 could exploit 87 percent of fifteen real vulnerabilities when it was given a description of each one, but only 7 percent without the description. That result matters to us because a description is exactly what gets published when a flaw goes public, so an AI attack can start as soon as the flaw is announced. Google’s Big Sleep team tested the defensive side by using an AI agent to find a flaw in SQLite that normal testing had missed, and the flaw was fixed before it ever reached users (Big Sleep Team 2024). Between them, these two studies cover both halves of our question. Still, the Big Sleep team calls its own results experimental, and lab tests cannot show which side comes out ahead in practice. The third group looks at AI in real attacks. Anthropic reported that a state-sponsored group used Claude Code, Anthropic’s own tool, to do 80 to 90 percent of the work in an espionage campaign, at a speed that “would have been, for human hackers, simply impossible to match” (Anthropic 2025). The UK’s National Cyber Security Centre expects AI to “almost certainly” shorten the gap between disclosure and exploitation even more, but it also says AI will help defenders (National Cyber Security Centre 2025). These reports tell us that attackers are already using AI, but not whether defenders can keep up. The last group is news coverage of PHP2Shell, which is our case study. Gatlan (2026) covers the two flaws and the emergency patches released on October 21, 2026, and Washenko (2026) reports that governments in Europe and Canada shut down websites as a precaution. Ntsele (2026) adds that researchers used AI to find the flaws, which had sat in PHP for over a decade, and that researchers at Wiz used AI to build working exploits “in hours.” This one event shows AI helping both defenders and attackers. The articles report what happened, but they do not ask what it means for how fast organizations now have to respond, and that is where our project comes in.

## References

Anthropic. 2025. “Disrupting the First Reported AI-Orchestrated Cyber Espionage Campaign.” *Anthropic News*, November 13. <https://www.anthropic.com/news/disrupting-AI-espionage>.

Big Sleep Team. 2024. “From Naptime to Big Sleep: Using Large Language Models to Catch Vulnerabilities in Real-World Code.” *Project Zero*, November 1. <https://projectzero.google/2024/10/from-naptime-to-big-sleep.html>.

Charrier, Casey, and Robert Weiner. 2024. “How Low Can You Go? An Analysis of 2023 Time-to-Exploit Trends.” *Google Cloud Blog*, October 15. <https://cloud.google.com/blog/topics/threat-intelligence/time-to-exploit-trends-2023>.

Fang, Richard, Rohan Bindu, Akul Gupta, and Daniel Kang. 2024. “LLM Agents Can Autonomously Exploit One-Day Vulnerabilities.” arXiv:2404.08144. Preprint, arXiv, April 11. <https://doi.org/10.48550/arXiv.2404.08144>.

Gatlan, Sergiu. 2026. “PHP Ships Emergency Patches for Critical PHP2Shell Flaws.” *BleepingComputer*, October 21. <https://www.bleepingcomputer.com/news/security/php-ships-emergency-patches-for-critical-php2shell-flaws/>.

National Cyber Security Centre. 2025. *Impact of AI on Cyber Threat from Now to 2027*. <https://www.ncsc.gov.uk/report/impact-ai-cyber-threat-now-2027>.

Ntsele, Gugu. 2026. “PHP Flaws Found by AI Force Governments and Major Sites Offline.” *Paubox*, October 22. <https://www.paubox.com/blog/php-flaws-found-by-ai-force-governments-and-major-sites-offline>.

Rapid7 Intelligence. 2026. “Q3 2026 Threat Update: Attackers Are Exploiting Vulnerabilities Within 3 Days.” *Rapid7 Blog*, October 21. <https://www.rapid7.com/blog/post/tr-q3-2026-threat-update-attackers-exploiting-vulnerabilities-within-3-days/>.

Washenko, Anna. 2026. “Government Websites in the EU and Canada Taken Offline over PHP Vulnerability.” *Engadget*, October 21. <https://www.engadget.com/2293625/government-websites-in-the-eu-and-canada-taken-offline-over-php-vulnerability/>.
