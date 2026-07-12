# Testing Strategy

> Purpose: Define how this project proves correctness and what validation is required before changes ship.
> When to update: When test layers, required checks, tooling, or reliability rules change.
> Owner: {{OWNER_NAME}}.

## Quality Gates

- Required automated checks: `TODO`
- Required manual checks: `TODO`

## Validation Evidence

- Evidence means the exact commands or checks run and their outcomes.
- Record evidence in the pull request description or the task summary for the change.
- Do not report a check as passing without running it. If a required check is still `TODO`, say so in the evidence.

## Test Layers

- Unit tests: what belongs here
- Integration tests: what belongs here
- End-to-end tests: what belongs here

## Fixtures And Data

Document approved fixtures, seeded data, and test environment setup.

## Mocking Policy

Define what is acceptable to mock and what should be tested through real integrations.

## Reliability Rules

- How to handle flaky tests
- How to document missing coverage
- What must run before merge
