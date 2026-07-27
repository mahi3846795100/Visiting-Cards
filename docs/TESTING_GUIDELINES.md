# Testing Guidelines

## Baseline

- Every completed phase must have tests that cover its success criteria.
- Prefer unit tests for isolated logic and targeted integration tests only where necessary.
- Keep tests deterministic and local.

## Expectations

- Test behavior, not implementation details.
- Keep test setup small and readable.
- Add regression coverage whenever a bug is fixed.
- Do not rely on external services or internet access.

## Validation Strategy

- Start with the smallest test scope that can falsify the change.
- Expand to broader validation only after the focused check passes.
- Keep completed phase tests green before moving forward.
