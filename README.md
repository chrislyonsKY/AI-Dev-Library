# Agents — Reusable AI Agent Configurations

> Each agent is a specialized persona for a specific development task.
> Fork into your project's `ai-dev/agents/` and customize with project context.

## Inventory

| Agent | File | Primary Use |
|---|---|---|
| Solutions Architect | `architect.md` | System design, module interfaces, structural review |
| Python Expert | `python-expert.md` | Business logic, ArcPy, data pipelines, idiomatic Python |
| C# / .NET Expert | `csharp-expert.md` | ArcGIS Pro SDK, WPF/MVVM, .NET patterns |
| TypeScript Expert | `typescript-expert.md` | React/Next.js, Three.js, Vite, web apps |
| Data & Database Expert | `data-expert.md` | SQL, ETL, geodatabases, data modeling |
| QA Reviewer | `qa-reviewer.md` | Testing, edge cases, code review findings |
| DevOps Expert | `devops-expert.md` | Deployment, CI/CD, logging, scheduling |
| Technical Writer | `technical-writer.md` | Docs, SOPs, README, runbooks, metadata |
| Frontend & UI Expert | `frontend-expert.md` | React UI, CSS, accessibility, data viz |
| Security Reviewer | `security-reviewer.md` | Threat modeling, credential audits, input validation |
| GIS Domain Expert | `gis-expert.md` | Enterprise GIS, spatial analysis, geodatabase design |
| Refactor Coach | `refactor-coach.md` | Legacy modernization, code smells, migration strategy |

## Usage

Reference from CLAUDE.md:
```
Read ai-dev/agents/architect.md for your role definition.
```

Or in a Claude Code / chat prompt:
```
Read ai-dev/agents/python-expert.md, then implement the data sync module.
```

## Customization Checklist

When forking an agent into a project:
- [ ] Replace `[PROJECT_NAME]` with actual project name
- [ ] Add project-specific patterns to the Patterns section
- [ ] Add project-specific anti-patterns
- [ ] Update the review checklist with project conventions
- [ ] Cross-reference with `ai-dev/guardrails/` in the preamble
