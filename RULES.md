# RULES

## Spec-First Workflow
- Every feature must be documented before implementation.
- Either:
  - Create a new feature spec in `SPECS/`, or
  - Extend the Acceptance Criteria in an existing spec.
- No code changes without a matching spec update.

## Enforcement
- I will always check for the relevant spec before making changes.
- If a spec is missing, I will add it first.
- If the feature fits an existing spec, I will update its Acceptance Criteria before coding.
- When updating or creating a feature, I will also update or create its spec in the same change set.

## TODO Hygiene
- When a TODO is implemented, it must be removed from `TODO.md`.
