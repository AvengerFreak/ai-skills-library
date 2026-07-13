# Gemini Code Assist Skills Library

A curated list of official Gemini Code Assist skills and related Google Gemini API skills for full-stack application development, workflows, and data. Store skills as folders with `SKILL.md` files and optional supporting assets.

## Repository Layout

```text
gemini-skills-library/
├── README.md
├── frontend/
├── backend/
├── devops/
├── data/
├── workflows/
├── architecture/
├── quality/
└── security/
```

## Official Installation Notes

Google documents Gemini Code Assist as an IDE coding assistant and also documents Gemini API skills for developer workflows. The Gemini API skills page explains that skills are installed with supported tools such as `skills.sh` or Context7, and that the Gemini Docs MCP can be paired with those skills. [web:242][web:250]

## Frontend

- **frontend-design**  
  Official Gemini skill for building frontend experiences with modern UI patterns and design guidance.  
  Install: `npx skills add google-gemini/gemini-skills --skill frontend-design --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **javascript-typescript**  
  Official or supported JavaScript and TypeScript development skill for frontend and web applications.  
  Install: `npx skills add google-gemini/gemini-skills --skill javascript-typescript --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **react-nextjs**  
  Official or supported React and Next.js frontend skill for app structure, components, and page organization.  
  Install: `npx skills add google-gemini/gemini-skills --skill react-nextjs --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

## Backend

- **api-design**  
  API design, request validation, error handling, and service structure for backend applications.  
  Install: `npx skills add google-gemini/gemini-skills --skill api-design --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **python**  
  Python development guidance for backend services, automation, and integration code.  
  Install: `npx skills add google-gemini/gemini-skills --skill python --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **java**  
  Java development guidance for backend services, APIs, and enterprise applications.  
  Install: `npx skills add google-gemini/gemini-skills --skill java --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **test-driven-development**  
  Test-first implementation workflow for building and verifying features.  
  Install: `npx skills add google-gemini/gemini-skills --skill test-driven-development --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **systematic-debugging**  
  Structured debugging workflow for isolating root causes and validating fixes.  
  Install: `npx skills add google-gemini/gemini-skills --skill systematic-debugging --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

## DevOps

- **docker**  
  Container image design, multi-stage builds, and secure container best practices.  
  Install: `npx skills add google-gemini/gemini-skills --skill docker --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **kubernetes**  
  Kubernetes deployment patterns, manifests, RBAC, and runtime configuration.  
  Install: `npx skills add google-gemini/gemini-skills --skill kubernetes --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **aws**  
  AWS deployment and infrastructure guidance with least-privilege and environment separation.  
  Install: `npx skills add google-gemini/gemini-skills --skill aws --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **azure**  
  Azure deployment and identity guidance for cloud-native application delivery.  
  Install: `npx skills add google-gemini/gemini-skills --skill azure --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **gcp**  
  Google Cloud deployment guidance, service accounts, and operational readiness.  
  Install: `npx skills add google-gemini/gemini-skills --skill gcp --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **ci-cd**  
  CI/CD workflow planning, release automation, and deployment safety.  
  Install: `npx skills add google-gemini/gemini-skills --skill ci-cd --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

## Data

- **sql**  
  SQL query design, schema quality, indexing, and analytics workflows.  
  Install: `npx skills add google-gemini/gemini-skills --skill sql --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **data-analysis**  
  Data cleaning, transformation, and analysis workflows for notebooks and scripts.  
  Install: `npx skills add google-gemini/gemini-skills --skill data-analysis --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

## Workflows

- **create-plan**  
  Break work into implementation steps and execution milestones.  
  Install: `npx skills add google-gemini/gemini-skills --skill create-plan --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **specification-writing**  
  Write clear, AI-friendly specs before implementation starts.  
  Install: `npx skills add google-gemini/gemini-skills --skill specification-writing --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **context-collection**  
  Gather relevant repository context before making changes.  
  Install: `npx skills add google-gemini/gemini-skills --skill context-collection --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

## Architecture and Quality

- **folder-structure**  
  Standard repository layouts and folder conventions.  
  Install: `npx skills add google-gemini/gemini-skills --skill folder-structure --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **architecture-design**  
  System design docs, architecture tradeoffs, and implementation boundaries.  
  Install: `npx skills add google-gemini/gemini-skills --skill architecture-design --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **doublecheck**  
  Verification, consistency review, and output quality checks.  
  Install: `npx skills add google-gemini/gemini-skills --skill doublecheck --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **linting-quality-gate**  
  Linting, formatting, naming, and maintainability checks across codebases.  
  Install: `npx skills add google-gemini/gemini-skills --skill linting-quality-gate --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

## Security

- **secret-safety**  
  Safe secrets handling, environment configuration, and least-privilege guidance.  
  Install: `npx skills add google-gemini/gemini-skills --skill secret-safety --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

- **secure-code-review**  
  Security review for application changes and risky implementation patterns.  
  Install: `npx skills add google-gemini/gemini-skills --skill secure-code-review --global`  
  Documentation: [Gemini API skills](https://ai.google.dev/gemini-api/docs/coding-agents) [web:250]

## Good Starter Bundle

If you want a practical first install set for Gemini Code Assist and Gemini API workflows, start with:

- `frontend-design`
- `javascript-typescript`
- `api-design`
- `python`
- `java`
- `test-driven-development`
- `systematic-debugging`
- `docker`
- `kubernetes`
- `aws`
- `azure`
- `gcp`
- `create-plan`
- `specification-writing`
- `doublecheck`

## Skill Format

Each skill should live in its own folder and include a `SKILL.md` file.

```text
.gemini/skills/backend/python/
├── SKILL.md
├── examples/
└── references/
```

## What to Include in Each Skill

Each skill should usually contain:

- a short purpose statement,
- when to use it,
- what it should optimize for,
- rules and constraints,
- examples of good output,
- examples of bad output to avoid.

## Notes

Google’s Gemini Code Assist documentation covers IDE coding assistance, while the Gemini API skills page covers the reusable skill packaging and installation model. Use the official Gemini skills catalog as the source of truth for installable skill names. [web:242][web:250]
