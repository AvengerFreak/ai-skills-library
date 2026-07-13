# Codex Skills Library

A curated list of official OpenAI Codex skills for full-stack application development, workflows, and data. Store skills as folders with `SKILL.md` files and optional supporting assets.

## Repository Layout

```text
codex-skills-library/
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

Codex uses a skill catalog and installs curated skills with the built-in skill installer. Skills in the `.system` directory are automatically available, and curated or experimental skills can be installed by name or by GitHub directory URL. [web:215]

## Frontend

- **frontend-design**  
  Official skill for designing and building frontend experiences with Codex.  
  Install: `$skill-installer frontend-design`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **javascript-typescript**  
  Official or curated JavaScript and TypeScript development skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer javascript-typescript`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **react-nextjs**  
  Official or curated React and Next.js frontend skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer react-nextjs`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

## Backend

- **api-design**  
  Official skill for API design, validation, and backend service structure when present in the OpenAI catalog.  
  Install: `$skill-installer api-design`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **python**  
  Official or curated Python skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer python`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **java**  
  Official or curated Java skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer java`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **test-driven-development**  
  Official skill for TDD workflows and implementation discipline.  
  Install: `$skill-installer test-driven-development`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **systematic-debugging**  
  Official skill for structured debugging and root-cause analysis.  
  Install: `$skill-installer systematic-debugging`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

## DevOps

- **docker**  
  Official or curated Docker/container skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer docker`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **kubernetes**  
  Official or curated Kubernetes deployment skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer kubernetes`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **aws**  
  Official or curated AWS deployment skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer aws`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **azure**  
  Official or curated Azure deployment skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer azure`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **gcp**  
  Official or curated GCP deployment skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer gcp`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **ci-cd**  
  Official skill for CI/CD workflow planning and release automation when present in the OpenAI catalog.  
  Install: `$skill-installer ci-cd`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

## Data

- **sql**  
  Official or curated SQL skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer sql`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **data-analysis**  
  Official or curated data analysis skill, when present in the OpenAI skills catalog.  
  Install: `$skill-installer data-analysis`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

## Workflows

- **create-plan**  
  Official skill for planning and implementation breakdowns.  
  Install: `$skill-installer create-plan`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **specification-writing**  
  Official or curated skill for writing specifications, when present in the OpenAI catalog.  
  Install: `$skill-installer specification-writing`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **context-collection**  
  Official or curated skill for gathering relevant code context, when present in the OpenAI catalog.  
  Install: `$skill-installer context-collection`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

## Architecture and Quality

- **folder-structure**  
  Official or curated skill for standard repository layouts, when present in the OpenAI catalog.  
  Install: `$skill-installer folder-structure`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **architecture-design**  
  Official or curated skill for system design and architecture decisions, when present in the OpenAI catalog.  
  Install: `$skill-installer architecture-design`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **doublecheck**  
  Official or curated verification skill for review and consistency checks, when present in the OpenAI catalog.  
  Install: `$skill-installer doublecheck`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **linting-quality-gate**  
  Official or curated code-quality skill for linting and formatting standards, when present in the OpenAI catalog.  
  Install: `$skill-installer linting-quality-gate`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

## Security

- **secret-safety**  
  Official or curated skill for secrets handling and least-privilege guidance, when present in the OpenAI catalog.  
  Install: `$skill-installer secret-safety`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

- **secure-code-review**  
  Official or curated security review skill, when present in the OpenAI catalog.  
  Install: `$skill-installer secure-code-review`  
  Documentation: [OpenAI Codex Skills](https://developers.openai.com/codex/skills) [web:212][web:215]

## Skill Format

Each skill should live in its own folder and include a `SKILL.md` file.

```text
.codex/skills/backend/python/
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

Codex skills are discovered from the skills catalog and installed with the built-in installer. The catalog is the safest source for verifying whether a skill is official and installable. [web:215][web:212]
