# Claim and Storyboard

Ali Eldahshan and Mazen Malas

## Claim Paragraph

On October 21, 2026, the PHP Foundation released emergency fixes for PHP2Shell, two serious flaws in the PHP programming language [@gatlanPHPShipsEmergency2026].
Researchers had used AI to find the flaws, which had sat in PHP for more than ten years, and researchers at Wiz then used AI to build working attacks "in hours" [@ntselePHPFlawsFound2026].
Governments in Europe and Canada took websites offline as a precaution [@washenkoGovernmentWebsitesEU2026].
Security teams usually plan as if they have days or weeks to install a fix after a flaw becomes public, but that window was shrinking even before AI, from 32 days in 2021–2022 to 5 days in 2023 [@charrierHowLowCan2024].
Experts expect AI to shrink it further [@nationalcybersecuritycentreImpactAICyber2025], but it is not clear whom AI helps more: some studies show it finding flaws for defenders [@bigsleepteamNaptimeBigSleep2024], while others show it attacking for hackers [@fangLLMAgentsCan2024; @anthropicDisruptingFirstReported2025].
No one has yet worked out what this means for how fast an ordinary organization must act once a flaw becomes public.
If organizations keep planning around days when attackers need only hours, they will be exposed in the gap.
We argue that AI helps both sides, but at different times: before a flaw is public, it helps defenders find it, but once the flaw is announced, it helps attackers more, because it can turn the published description into a working attack faster than most organizations can install a fix.
As a result, organizations can no longer count on days to respond to a critical flaw; they need to be ready to act within hours.

## Storyboard

**Claim:** AI helps defenders find flaws before they are public, but it helps attackers more after a flaw is announced, so organizations must be ready to respond within hours, not days.

**Key terms in the claim:**

- *Disclosure:* the moment a flaw becomes public, usually with a description and a fix.
- *Patch window:* the time between disclosure and the first attack, which is the time an organization has to install the fix.
- *Defenders* and *attackers:* the people who find and fix flaws, and the people who exploit them.

**Order:** The body follows the life of a security flaw, from before it is public, to its disclosure, to the race to fix it.
This also runs from the least to the most debatable point, so our most debatable reason, that patching cannot keep up, comes last.
PHP2Shell serves as a running example throughout.

### 1. First, the Patch Window Was Already Shrinking

- **Reason:** First, even before AI, the patch window was shrinking, as the time-to-exploit fell from weeks to days.
- **Evidence:**
  - Mandiant found that the average time-to-exploit fell from 32 days in 2021–2022 to 5 days in 2023 [@charrierHowLowCan2024].
  - Rapid7 put it at 3 days in the third quarter of 2026 and saw AI used in 8 percent of the threats it tracked [@rapid7intelligenceQ32026Threat2026].
- **Key terms:** *time-to-exploit* (the number of days from disclosure to the first known attack), *shrinking patch window*.
- **Acknowledgment and response:** These numbers do not show how much of the drop is due to AI, since it began before AI tools were common.
  We do not claim AI caused the whole drop, only that it pushes the window from days down to hours.

### 2. Before a Flaw Is Public, AI Helps Defenders

- **Reason:** Before a flaw is public, AI helps defenders discover hidden flaws that years of human testing missed.
- **Evidence:**
  - Google's Big Sleep agent found a flaw in SQLite that normal testing had missed, and it was fixed before it reached users [@bigsleepteamNaptimeBigSleep2024].
  - Researchers used AI to find the PHP2Shell flaws after they had sat in PHP for more than ten years [@ntselePHPFlawsFound2026].
  - The UK's National Cyber Security Centre expects AI to help defenders as well as attackers [@nationalcybersecuritycentreImpactAICyber2025].
- **Key terms:** *hidden flaws* (flaws that sit unnoticed in code for years), *human testing* (the usual ways people check code for flaws), *discover*.
- **Acknowledgment and response:** The Big Sleep team calls its own results experimental, and attackers can use the same tools to find flaws first.
  We agree, which is why our claim gives defenders the advantage only before disclosure, and only if they look first.

### 3. Once a Flaw Is Announced, AI Builds the Attack in Hours

- **Reason:** Once a flaw is announced, its public description gives AI what it needs to build a working exploit in hours.
- **Evidence:**
  - GPT-4 exploited 87 percent of fifteen real flaws when given a description of each, but only 7 percent without one [@fangLLMAgentsCan2024].
  - Researchers at Wiz used AI to build working PHP2Shell attacks "in hours" [@ntselePHPFlawsFound2026].
- **Key terms:** *public description* (the details about a flaw published at disclosure), *working exploit* (code that uses a flaw to break into a system).
- **Acknowledgment and response:** Fang's team tested only fifteen flaws with a 2024 model, and Wiz's researchers were defenders, not criminals.
  But AI models have grown stronger since 2024, and anything researchers can do in hours, attackers with the same tools can do too.

### 4. Worse, AI Carries Out the Attack Itself

- **Reason:** Worse, AI does not just build the exploit; it carries out most of the attack, at a speed and scale no human team can match.
- **Evidence:**
  - A state-sponsored group used Claude Code to do 80 to 90 percent of the work in an espionage campaign, at a speed that "would have been, for human hackers, simply impossible to match" [@anthropicDisruptingFirstReported2025].
  - The National Cyber Security Centre expects AI to "almost certainly" shorten the gap between disclosure and exploitation [@nationalcybersecuritycentreImpactAICyber2025].
- **Key terms:** *AI-orchestrated attack* (an attack in which AI, not a person, carries out most of the steps), *speed and scale*.
- **Acknowledgment and response:** Anthropic's report covers only one campaign.
  But the National Cyber Security Centre and Rapid7 independently report the same trend.

### 5. Finally, Installing a Patch Still Moves at Human Speed

- **Reason:** Finally, installing a patch still moves at human speed, so organizations often have to fall back on mitigation, such as taking sites offline.
- **Evidence:**
  - Governments in Europe and Canada took websites offline instead of waiting to install the PHP2Shell fixes [@washenkoGovernmentWebsitesEU2026].
  - The PHP Foundation had to release the fixes as an emergency, outside its normal schedule [@gatlanPHPShipsEmergency2026].
  - In 2025, organizations took a median of 43 days to fully patch flaws that attackers were already known to be exploiting, up from 32 days the year before, and they fully patched only 26 percent of them [@verizon2026DataBreach2026].
  - The PHP Foundation itself first found signs of one PHP2Shell flaw in 2024, but work on a fix "stall[ed] and restart[ed] repeatedly over months," a delay it called "a structural failure, caused by both the security team's decision process and its lack of resources" [@ngPHPFoundationAdmits2026].
- **Key terms:** *installing a patch* (the step each organization must take itself after the software maker releases a fix), *human speed* (the pace of people testing, scheduling, and restarting systems), *mitigation* (a temporary step, such as taking a site offline, that blocks an attack until the patch is in).
- **Acknowledgment and response:** AI may soon help defenders install patches faster too.
  If it does, the gap could close, but we have not yet found evidence that this is happening at scale, and we will keep looking.

# References
