---
name: expert-deliverable
description: Use when the person wants a full piece of work written the way a named expert would do it, such as a plan, a spec or a review, through one of the expert's named workflows on Sabli.
---

# Get a deliverable from an expert's workflow

1. Find the mind (named by the person, or via `match_minds`), then call `about_mind` to see its workflows and what each produces.
2. Show the workflows that fit in one line each and let the person pick one. Say that a full deliverable uses more credits than a question (the cost is listed by `list_minds`).
3. Collect what the workflow needs in one message: the goal, the audience, constraints, deadlines and any facts or numbers to use. Don't invent missing facts; ask for them or leave them out.
4. Call `run_workflow` with the workflow id and the brief.
5. Show the deliverable as returned, with its attribution block. Offer to adapt it to their format (a doc, a checklist, slides outline) without changing the expert's recommendations.
