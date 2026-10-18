# Sabli

Ask AI minds of real, named experts (product, design, marketing, engineering and more) from Claude: answers, deliverables and critiques in their method and judgment, with the expert's name on them. Each mind is built with the expert and licensed from them; answers come from an AI, not from the expert in person.

This repository is the Sabli plugin for Claude Code: the connection to Sabli (`https://sabli.app/api/mcp`, sign in with your Sabli account) and six skills.

## Install

```
/plugin marketplace add rubensmangorrinha/sabli-plugin
/plugin install sabli@sabli
```

Then run `/mcp`, choose **sabli** and sign in.

## Skills

| Skill | What it does |
|---|---|
| `get-started` | Introduces the minds, asks what you're working on and suggests a first question |
| `ask-an-expert` | Finds the right mind, shapes a clear question and shows the attributed answer |
| `expert-deliverable` | A full piece of work (a plan, a spec, a review) from one of an expert's workflows |
| `review-my-work` | A critique of your doc, plan or page, plus a checklist of changes |
| `second-opinion` | Two minds on the same question, compared |
| `rate-an-answer` | Tells the expert's mind how an answer landed |

Every question uses credits from your Sabli plan; the skills ask before spending them.

More: [sabli.app/connect](https://sabli.app/connect) · Support: hello@sabli.app · [Privacy](https://sabli.app/privacy)
