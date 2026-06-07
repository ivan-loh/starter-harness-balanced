# Documentation Index

> Purpose: Map the docs, explain what each document is for, and show where the main answers live.
> When to update: When files are added, removed, renamed, or reassigned.
> Owner: {{OWNER_NAME}}.

## Main Rules

- `docs/INDEX.md` is the file map for the docs.
- `README.md` is the main file for humans.
- `AGENTS.md` is the model-neutral entry point for coding agents.
- `CLAUDE.md` is the Claude Code-specific instruction file.
- `TODO.md` tracks setup items that cannot be known before the template is copied.
- `docs/PRD.md` owns product scope and requirements.
- `docs/ARCHITECTURE.md` owns system structure.
- `docs/TESTING.md` owns testing rules.

## Reading Order

- Humans: `README.md` -> `docs/INDEX.md` -> `docs/DEVELOPMENT.md` -> `docs/PRD.md` -> task-specific docs
- LLMs: `AGENTS.md` -> `README.md` -> `docs/INDEX.md` -> `TODO.md` -> task-specific docs
- Claude Code: `AGENTS.md` -> `README.md` -> `docs/INDEX.md` -> `TODO.md` -> `CLAUDE.md` -> task-specific docs

## Root Files

- `README.md`: start here if you are a person
- `AGENTS.md`: start here if you are a coding agent
- `CLAUDE.md`: Claude Code-specific guidance
- `TODO.md`: setup work for the copied project
- `CONTRIBUTING.md`: change and review process
- `SECURITY.md`: public security reporting
- `CHANGELOG.md`: notable changes over time
- `CODEOWNERS`: review ownership by path

## Core Docs

- `docs/HARNESS_GUIDE.md`: how this doc set is meant to work
- `docs/DEVELOPMENT.md`: local setup, commands, and working rules
- `docs/PRD.md`: goals, scope, and requirements
- `docs/ARCHITECTURE.md`: system shape and key boundaries
- `docs/SECURITY.md`: internal security model and controls
- `docs/TESTING.md`: testing layers and required checks
- `docs/ROADMAP.md`: planned next work
- `docs/RISKS.md`: current risks and assumptions
- `docs/DECISIONS.md`: ADR rules and index

## Where To Look

- What is this project and why does it exist? `README.md`, `docs/PRD.md`
- How do I run it locally? `docs/DEVELOPMENT.md`
- How is it structured? `docs/ARCHITECTURE.md`
- How do we handle internal security? `docs/SECURITY.md`
- How do people report vulnerabilities? `SECURITY.md`
- How do we test it? `docs/TESTING.md`
- How do reviews and contributions work? `CONTRIBUTING.md`, `CODEOWNERS`, `.github/*`
- What setup work remains? `TODO.md`
- What should I read next? `docs/INDEX.md`, `AGENTS.md`, `CLAUDE.md`

## Governance And Workflow

- `CONTRIBUTING.md`: contribution rules
- `SECURITY.md`: public reporting policy
- `CHANGELOG.md`: release history
- `CODEOWNERS`: review routing
- `.github/PULL_REQUEST_TEMPLATE.md`: PR checklist
- `.github/ISSUE_TEMPLATE/*`: issue templates

## Feature Workflow

- `docs/specs/FEATURE_SPEC_TEMPLATE.md`: feature problem and outcome
- `docs/specs/IMPLEMENTATION_PLAN_TEMPLATE.md`: technical plan for an approved spec
- `docs/specs/TASK_BREAKDOWN_TEMPLATE.md`: small reviewable tasks
