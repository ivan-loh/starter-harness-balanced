# Template Setup TODO

> Purpose: Track project-specific setup items that cannot be known before this template is copied.
> When to update: During first setup and whenever commands, checks, ownership, deployment, security, or validation expectations change.
> Owner: {{OWNER_NAME}}.

Delete or replace items as they become real project documentation. Do not leave completed setup facts only in this file if another document owns them.

## First Setup

- [ ] Delete the template banner at the top of `README.md`.
- [ ] Replace all `{{...}}` placeholders across the repository (find them with `grep -rn '{{' .`).
- [ ] Confirm the license type and copyright holder in `LICENSE`.
- [ ] Replace scaffold examples, `TODO` markers, `@org/team`, `security@replace-me.example`, and `replace-with-private-channel` with project-specific facts.
- [ ] Add project owners, maintainers, and review ownership.
- [ ] Add a `.gitignore` for the project language, tools, secrets, local env files, build outputs, and caches.
- [ ] Confirm the default branch is `{{DEFAULT_BRANCH}}` or update every reference.

## Commands And Local Environment

- [ ] Fill in install, run, test, lint, format, build, and verify commands in `docs/DEVELOPMENT.md`.
- [ ] Document required language/runtime versions.
- [ ] Document required environment variables and local services.
- [ ] Document any commands agents may safely run without extra context.

## Quality Gates And CI

- [ ] Define required automated checks in `docs/TESTING.md`.
- [ ] Define required manual checks in `docs/TESTING.md`.
- [ ] Decide what must pass before commit, pull request, merge, and release.
- [ ] Add CI once the real stack is known.
- [ ] Add docs checks, placeholder checks, secret scanning, dependency review, and branch protection when they apply.

## Product, Architecture, And Risk

- [ ] Fill in product scope, goals, non-goals, and users in `docs/PRD.md`.
- [ ] Fill in system boundaries, major components, data flow, invariants, and failure posture in `docs/ARCHITECTURE.md`.
- [ ] Fill in roadmap, risks, assumptions, and decision records.
- [ ] Define when an ADR is required.

## Security And Governance

- [ ] Replace public security contacts and response SLAs in `SECURITY.md`.
- [ ] Fill in internal security model, trust boundaries, sensitive data, and control expectations in `docs/SECURITY.md`.
- [ ] Replace `CODEOWNERS` with real users or teams.
- [ ] Review and customize the `.github` issue and pull request templates, including the security contact link in `.github/ISSUE_TEMPLATE/config.yml`.
- [ ] Configure repository settings, branch protection, and required reviewers.

## AI And Review Workflow

- [ ] Decide whether `AGENTS.md`, `CLAUDE.md`, or both need project-specific instructions.
- [ ] Add acceptance-criteria evidence expectations to the spec templates if the project needs stricter review packets.
- [ ] Define what validation evidence must appear in pull requests or task summaries.

## Release Readiness

- [ ] Choose a versioning scheme and start recording notable changes in `CHANGELOG.md`.
- [ ] Document packaging and deployment in a new Deployment section of `docs/DEVELOPMENT.md`.
- [ ] Document rollback and recovery steps under Failure Posture in `docs/ARCHITECTURE.md` before production use.
- [ ] Document support ownership and the escalation path in `docs/DEVELOPMENT.md` or `README.md` before production use.
- [ ] Consider moving to the `full` variant when deployment, operations, and release work needs owning docs.
