# CLAUDE.md — AI Assistant Guide for AITF

## Project Overview

AITF (AI Test Framework) is a new project repository. This file serves as the canonical reference for AI assistants working in this codebase.

## Repository Structure

```
AITF/
├── CLAUDE.md          # This file — AI assistant guide and project conventions
└── (project files)    # To be added as the project develops
```

> **Note:** This repository is in its initial state. Update this section as the project structure evolves.

## Development Workflow

### Branch Conventions

- Feature branches should follow the pattern: `claude/<description>-<session-id>`
- Always push with: `git push -u origin <branch-name>`
- Never force-push to `main` or `master`

### Commit Messages

- Use clear, descriptive commit messages
- Focus on the "why" rather than the "what"
- Keep the first line under 72 characters
- Use imperative mood (e.g., "Add feature" not "Added feature")

### Pull Requests

- Keep PR titles short (under 70 characters)
- Include a summary section with bullet points
- Include a test plan when applicable

## Build & Test

> **TODO:** Document build commands, test commands, and lint commands as they are established.

## Code Conventions

### General Principles

- Keep solutions simple and focused — avoid over-engineering
- Only add error handling at system boundaries (user input, external APIs)
- Don't create abstractions for one-time operations
- Prefer editing existing files over creating new ones
- Remove unused code entirely — no compatibility shims or `// removed` comments

### Security

- Never commit secrets, credentials, or `.env` files
- Validate user input and external API data at system boundaries
- Follow OWASP top 10 guidelines

## Key Files

| File | Purpose |
|------|---------|
| `CLAUDE.md` | AI assistant guide and project conventions |

> Update this table as key files are added to the project.

## Common Tasks

> **TODO:** Document common development tasks, debugging tips, and troubleshooting steps as they are established.

## Architecture Decisions

> Record significant architectural decisions here as the project develops, using the format:
>
> **Decision:** [What was decided]
> **Context:** [Why it was needed]
> **Consequences:** [Trade-offs and implications]
