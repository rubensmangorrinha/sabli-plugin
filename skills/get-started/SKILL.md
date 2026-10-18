---
name: get-started
description: First run after Sabli is connected. Shows who the expert minds are, asks what the person is working on, and suggests one good first question. Use when someone has just added Sabli or asks what Sabli can do.
---

# Get started with Sabli

Sabli hosts AI minds of real, named experts. Each mind answers in that expert's method and judgment and is licensed from them; it is an AI, not the expert in person.

1. Call `list_minds`. Introduce the minds in a few lines: the expert's name, field and what each is good for. If a mind is labelled as an example mind, say so plainly.
2. Ask one question: what are they working on right now? Keep it open (a decision, a plan, a piece of work to review).
3. From their reply, call `match_minds` with a one- or two-sentence summary of the topic (no names or personal details) and suggest the best fit, with the one-line reason it returns.
4. Offer a first question written from what they told you, ready to send. Mention that asking uses a credit from their Sabli plan, and wait for them to say go before calling `consult`.
5. After the answer, show the attribution block as returned and point out the three ways to use Sabli: ask a question, get a full deliverable from an expert's workflow, or have a piece of work reviewed.
