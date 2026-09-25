# Anton Ochniev

**Game systems · AI-assisted prototyping · Automation**

I build game prototypes and AI-assisted tools. I am interested in mechanics, progression, simulation and the way separate rules work together. I also write LitRPG, exploring worlds, abilities and the consequences of their rules.

Based in **Poznań, Poland**. Open to **junior game / systems design, AI prototyping and AI automation** opportunities.

[Email](mailto:77ant77@gmail.com) · [LinkedIn](https://www.linkedin.com/in/anton-ochniev/) · [Read Ring of God](https://www.royalroad.com/fiction/153199/ring-of-god)

## Game design & worldbuilding

### [RINGS — Telegram RPG](https://github.com/Anton-Ognev-AI/rings-telegram-rpg)

A text RPG set in a magical academy. The player works through a ten-stage expedition, chooses how to approach encounters and develops their stats, equipment and magic ring.

My work covers the rules, progression, encounter choices, onboarding and AI-assisted implementation. The project includes deterministic outcome resolution and a script for comparing starter builds. Game outcomes are calculated by code, not a runtime LLM.

**Status:** personal MVP in development, with public source and local verification tooling.

[Game design specification](https://github.com/Anton-Ognev-AI/rings-telegram-rpg/blob/main/docs/specs/2026-07-12-game-design-v1.1.md) · [Balance simulation](https://github.com/Anton-Ognev-AI/rings-telegram-rpg/blob/main/scripts/simulate-starter-builds.ts) · [Architecture](https://github.com/Anton-Ognev-AI/rings-telegram-rpg/blob/main/ARCHITECTURE.md)

### InsectWorld

My mobile game project, focused on an insect world and its interacting systems. I work on unit behavior, resources, progression and balance, using the prototype to test and revise the rules.

**Status:** personal project in development. Its source and a playable build are not included in this public portfolio.

### [Ring of God — LitRPG](https://www.royalroad.com/fiction/153199/ring-of-god)

I write under the name **Anton Ognev**. My fiction work includes worldbuilding, ability systems, progression and the consequences of those rules for the characters. The Royal Road edition is a public writing sample alongside my game projects.

## AI products & creative tools

### [Zadum — writing service](https://zadum-web-production.up.railway.app/)

A Ukrainian-language AI writing service I am building for fiction authors. The goal is to help an author move from a brief through planning, drafting and revision while keeping the story consistent.

**Status:** in development. The Book Factory repository below is a separate public engineering excerpt, not Zadum's production source.

### [Book Factory Pipeline](https://github.com/Anton-Ognev-AI/book-factory-pipeline)

A TypeScript project for structured long-form writing: planning, scene context, drafting, review and author approval. It combines specialized agents, n8n orchestration, Supabase and a React workspace.

**Public evidence:** source, architecture and a dashboard demo using synthetic data. Manuscripts, private book data and production credentials are excluded.

[View the workspace demo](https://github.com/Anton-Ognev-AI/book-factory-pipeline#demo--the-writer-workspace)

## Automation & engineering

### [Cortex](https://github.com/Anton-Ognev-AI/cortex)

A TypeScript task-orchestration hub controlled through Telegram. It turns messages into tracked tasks, records state in an append-only journal and hands execution to a separate companion project, Right Hand. The repository includes tests and documentation of the orchestration boundaries.

### [Karaoke Article Pipeline](https://github.com/Anton-Ognev-AI/karaoke-article-pipeline)

A client MVP connecting music data, verified YouTube embeds and AI-assisted writing to a WordPress draft. The workflow checks the output and sends it to Telegram for human review before publication.

### More projects

| Project | Focus |
| --- | --- |
| [n8n workflows as code](https://github.com/Anton-Ognev-AI/n8n-workflows-as-code) | Versioned workflow definitions, repeatable deployment and checks. |
| [Social automation toolkit](https://github.com/Anton-Ognev-AI/n8n-social-automation-toolkit) | Content workflows, secret scanning and explicit deployment approval. |
| [Reels growth loop](https://github.com/Anton-Ognev-AI/reels-growth-loop) | Collecting content metrics to inform the next iteration. |
| [LLM translation pipeline](https://github.com/Anton-Ognev-AI/llm-translation-pipeline) | Literary translation workflow, terminology checks and review roles. |
| [AI agent evaluation playbook](https://github.com/Anton-Ognev-AI/ai-agent-eval-playbook) | An agent evaluation, sandboxing approach and lessons learned. |

## How I work

I start with the intended behavior, build a small version and check the result. I use AI coding tools for implementation, research and iteration, while defining the requirements and reviewing what is produced. I keep design documents and tests alongside the code where they help make decisions easier to inspect.

**Tools used across my projects:** TypeScript · Python · Godot · n8n · PostgreSQL / Supabase · React · Telegram Bot API · LLM APIs · REST / webhooks.

My game-development work is currently personal-project experience. I am looking for a team where I can contribute that practical work and develop it further.
