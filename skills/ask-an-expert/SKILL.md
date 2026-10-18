---
name: ask-an-expert
description: Use when the person asks Sabli, or one of its expert minds, for advice on a decision in product, design, marketing, engineering or a similar field. Finds the right mind, shapes a clear question, asks it and shows the attributed answer.
---

# Ask an expert's mind

1. **Pick the mind.** If they named an expert, use that mind. Otherwise call `match_minds` with a one- or two-sentence summary of the topic (no names or personal details) and let them choose from the 1-3 suggestions. Don't ask a mind they haven't agreed to: each question uses a credit.
2. **Shape the question, briefly.** A good question has the situation, the goal, the constraints and what was already tried. If one of these is clearly missing and matters, ask for it in one short question; otherwise go ahead. Send the question with the details it needs, in their words; put background such as company, stage or audience in `context`.
3. **Leave out what isn't theirs to share:** other people's names, private data and anything confidential they haven't chosen to send.
4. **Ask** with `consult`.
5. **Show the answer as returned,** with its attribution block (mind, version, expert, run reference, disclosure). Never present it as the expert's personal words.
6. **Follow-ups** go to the same mind: send the new question with a one-line summary of the earlier answer in `context`.

If a tool says the plan has no credits left or the daily limit is reached, relay that message as it is and stop.

If a tool asks the person to sign in, tell them to run `/mcp` and choose Sabli.
