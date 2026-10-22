## Part 1: Topic, Question, and Problem

We are studying how artificial intelligence is speeding up hacking, both in finding security flaws and in carrying out attacks.
We chose this topic because of a recent example, "php2shell," a pair of flaws in the PHP programming language that became public in October 2026.
These flaws had been hidden in PHP's code for more than ten years before researchers used AI tools to find them.
When the PHP Foundation released emergency fixes on October 21, 2026, governments in Europe and elsewhere took websites offline to install the fixes.
We want to find out whether AI helps defenders, who find and fix flaws, more than it helps attackers, who exploit them.
We also want to know how AI changes the time that organizations have to notice an attack or install a fix.
This question matters because security experts usually assume that website owners have days or weeks to patch a flaw after it becomes public.
If AI lets attackers build a working attack within hours of a fix, that assumption no longer holds.
We want to help organizations of every size, from governments to small businesses, understand how quickly they must now respond when a security flaw becomes public.

## Part 2: Process

So far, my partner and I have chosen our topic and narrowed its scope.
We started by bouncing different topics and ideas off each other, and I jotted some of them down on paper before typing them up.
I do my writing in Visual Studio Code, using Markdown with one sentence per line so that Git can track changes to each sentence.
We keep our work in a shared GitHub repository, where I created the folder and file for this proposal and my partner committed our first draft.
I then used Claude Code, an AI assistant, to fix grammar errors in the draft and to revise it using the clarity principles in *The Craft of Research*.
My partner and I communicate by texting and meeting in person, and we use GitHub to share drafts and see each other's changes.
As the project continues, I plan to collect and cite our sources with Zotero and use Pandoc to turn our final Markdown file into a formatted Word or PDF document.

## Sources

### PHP2Shell

Gatlan, S. (2026, October 21). *PHP ships emergency patches for critical PHP2Shell flaws*. BleepingComputer. https://www.bleepingcomputer.com/news/security/php-ships-emergency-patches-for-critical-php2shell-flaws/

Ntsele, G. (2026, October 22). *PHP flaws found by AI force governments and major sites offline*. Paubox. https://www.paubox.com/blog/php-flaws-found-by-ai-force-governments-and-major-sites-offline

Washenko, A. (2026, October 21). *Government websites in the EU and Canada taken offline over PHP vulnerability*. Engadget. https://www.engadget.com/2293625/government-websites-in-the-eu-and-canada-taken-offline-over-php-vulnerability/

### AI and the Speed of Hacking

Anthropic. (2025, November 13). *Disrupting the first reported AI-orchestrated cyber espionage campaign*. https://www.anthropic.com/news/disrupting-AI-espionage

Big Sleep Team. (2024, November 1). *From Naptime to Big Sleep: Using large language models to catch vulnerabilities in real-world code*. Project Zero. https://projectzero.google/2024/10/from-naptime-to-big-sleep.html

Charrier, C., & Weiner, R. (2024, October 15). *How low can you go? An analysis of 2023 time-to-exploit trends*. Google Cloud Blog. https://cloud.google.com/blog/topics/threat-intelligence/time-to-exploit-trends-2023

Fang, R., Bindu, R., Gupta, A., & Kang, D. (2024). *LLM agents can autonomously exploit one-day vulnerabilities* (arXiv:2404.08144). arXiv. https://doi.org/10.48550/arXiv.2404.08144

National Cyber Security Centre. (2025, May 7). *Impact of AI on cyber threat from now to 2027*. https://www.ncsc.gov.uk/report/impact-ai-cyber-threat-now-2027

Rapid7 Intelligence. (2026, October 21). *Q3 2026 threat update: Attackers are exploiting vulnerabilities within 3 days*. Rapid7. https://www.rapid7.com/blog/post/tr-q3-2026-threat-update-attackers-exploiting-vulnerabilities-within-3-days/
