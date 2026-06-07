# CLAUDE

> Purpose: Be the Claude Code-specific instruction file for this repository.
> When to update: When project workflow, required reads, validation rules, or documentation ownership changes.
> Owner: {{OWNER_NAME}}.

## Canonical Rule

- Treat `AGENTS.md` as the model-neutral agent entry point.
- Treat this file as the Claude Code-specific instruction file for the repo.
- Keep this file short, stable, and specific.
- Treat `docs/INDEX.md` as the canonical document map.
- Do not create a second file index in another document.

## Start Here

- If you arrived here first, read `AGENTS.md` before continuing.
- Always read `README.md` and `docs/INDEX.md` before significant work.
- Read `TODO.md` before substantial work and help replace scaffold placeholders with project-specific facts.
- Use `docs/INDEX.md` to decide which document owns the question you are working on.

## Task Routing

- Scope, goals, non-goals, and requirements: `docs/PRD.md`
- Local commands, environment rules, and developer workflow: `docs/DEVELOPMENT.md`
- First setup tasks and unresolved scaffold decisions: `TODO.md`
- System shape, boundaries, and invariants: `docs/ARCHITECTURE.md`
- Internal security controls: `docs/SECURITY.md`
- Public vulnerability reporting policy: `SECURITY.md`
- Validation strategy and required checks: `docs/TESTING.md`
- Contribution and review workflow: `CONTRIBUTING.md`, `CODEOWNERS`, `.github/*`
- Document set rules and ownership: `docs/HARNESS_GUIDE.md`, `docs/INDEX.md`
- Feature delivery packets: `docs/specs/*`

## Required Reads By Change Type

- Read `docs/PRD.md` before changing product behavior or scope.
- Read `docs/ARCHITECTURE.md` before structural or integration changes.
- Read `docs/SECURITY.md` before changing auth, secrets, trust boundaries, or sensitive data flows.
- Read `docs/TESTING.md` before changing validation strategy or test coverage.
- Read `docs/DEVELOPMENT.md` before changing local commands, tooling, or environment expectations.
- Read `CONTRIBUTING.md` before changing contribution, branch, or review workflow.

## Working Rules

- Prefer `spec -> plan -> tasks` before large changes.
- Keep diffs focused and easy to review.
- Update the relevant docs in the same change when behavior or process changes.
- Update `docs/INDEX.md` if files are added, removed, renamed, or reassigned.
- State assumptions and unresolved risks explicitly.

## Definition Of Done

- Changed behavior is reflected in docs.
- Document structure changes are reflected in `docs/INDEX.md`.
- Validation evidence is captured.
- Remaining risks or follow-ups are recorded.
