# AI Dev Library — Reusable Project Infrastructure

![Agents](https://img.shields.io/badge/Agents-12-blue?style=flat-square&logo=robot&logoColor=white)
![Skills](https://img.shields.io/badge/Skills-8-green?style=flat-square&logo=bookopen&logoColor=white)
![Guardrails](https://img.shields.io/badge/Guardrails-6-red?style=flat-square&logo=shield&logoColor=white)
![Specs](https://img.shields.io/badge/Specs-5-orange?style=flat-square&logo=clipboard&logoColor=white)
![Decisions](https://img.shields.io/badge/Decisions-3-purple?style=flat-square&logo=gitbranch&logoColor=white)
![Prompts](https://img.shields.io/badge/Prompts-6-teal?style=flat-square&logo=terminal&logoColor=white)

![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Claude_Code_%7C_Claude_Chat_%7C_ChatGPT_%7C_Copilot_%7C_Cursor-lightgrey?style=flat-square)
![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen?style=flat-square)
![Files](https://img.shields.io/badge/Files-47-informational?style=flat-square)

> A curated library of agents, skills, guardrails, specs, decisions, and prompt templates
> designed to be forked into any new project's `ai-dev/` directory.

**Philosophy:** Documentation and architecture first, code second. AI is the accelerant — you're the engine.

## How to Use This Library

1. **Starting a new project?** Copy the relevant files into your project's `ai-dev/` folder
2. **Customize** — Replace `[PLACEHOLDERS]` with project-specific values
3. **Reference from CLAUDE.md** — Wire up the files so AI tools discover them automatically

## Library Contents

### `agents/` — 12 Reusable Agent Configurations
### `skills/` — 8 Domain Knowledge & Pattern Libraries
### `guardrails/` — 6 Non-Negotiable Constraint Sets
### `specs/` — 5 Specification Templates
### `decisions/` — 3 Decision Record Templates
### `prompt-templates/` — 6 Reusable AI Prompts

See each directory's README.md for inventory and usage guidance.

## Agent Combination Matrix

| Phase | Primary Agent | Supporting Agents |
|---|---|---|
| **Architecture** | Architect | Data Expert, GIS Expert |
| **Implementation** | Language Expert (Py/C#/TS) | Data Expert, GIS Expert |
| **Testing** | QA Reviewer | Language Expert |
| **Code Review** | QA Reviewer + Architect | Security Reviewer |
| **Refactoring** | Refactor Coach | Architect, Language Expert |
| **Deployment** | DevOps Expert | Technical Writer |
| **Documentation** | Technical Writer | All (for review) |

## Forking Workflow

```bash
# 1. Copy what you need into your project
cp ai-dev-library/agents/architect.md my-project/ai-dev/agents/
cp ai-dev-library/guardrails/*.md my-project/ai-dev/guardrails/

# 2. Customize the [PLACEHOLDERS] with project-specific values

# 3. Wire into CLAUDE.md — reference files so AI tools find them
```
