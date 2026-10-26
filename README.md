# Sabli: ask real experts' AI minds inside Claude Code, Cursor and any MCP client

Ask AI minds of real, named experts from Claude Code, Cursor, VS Code or any MCP client, without leaving your editor: a principal engineer's architecture review, a product lead's take on your spec, a design critique, or a full deliverable (PRD, launch plan, scaling plan), in their method and judgment. The expert's name is on every answer. Each mind is built with the expert and licensed from them; answers come from an AI, not from the expert in person.

This repository is the Sabli plugin for Claude Code: the connection to Sabli (`https://sabli.app/api/mcp`, sign in with your Sabli account) and six skills. Cursor, VS Code, Codex and Gemini CLI use the same MCP server: one-click setup at [sabli.app/integrations](https://sabli.app/integrations).

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
