# AGENTS

> Purpose: Be the model-neutral entry point for coding agents working in this repository.
> When to update: When agent workflow, required reads, validation rules, or canonical docs change.
> Owner: {{OWNER_NAME}}.

## Start Here

- Read `README.md` first for the human-facing project overview.
- Read `docs/INDEX.md` second for the document map.
- Read `TODO.md` before substantial work and help replace scaffold placeholders with project-specific facts.
- If you are Claude Code, read `CLAUDE.md` for Claude-specific workflow guidance.

## Entry Points

- `README.md`: human entry point
- `AGENTS.md`: model-neutral agent entry point
- `CLAUDE.md`: Claude Code guidance
- `TODO.md`: setup items that must be resolved after this template is copied
- `docs/INDEX.md`: canonical document map; the full list of owning docs lives there and only there

## Working Rules

- Use `docs/INDEX.md` to find the document that owns the question you are answering.
- Do not invent commands, checks, deployment steps, security contacts, or ownership. If the copied project has not defined them yet, update `TODO.md` or the owning doc.
- Keep changes focused and update durable docs when behavior, structure, or process changes.
- Prefer `spec -> plan -> tasks` before large changes; the templates live in `docs/specs/`.
- Capture validation evidence (the commands run and their outcomes) in the pull request description or task summary, per `docs/TESTING.md`.
