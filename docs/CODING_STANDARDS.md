# Coding Standards

## Language Baseline

- Target Python 3.12.
- Use type hints for public interfaces and non-trivial internal functions.
- Prefer standard library features where practical.

## Style

- Use meaningful names.
- Keep functions small and single-purpose.
- Avoid long files and deeply nested control flow.
- Add docstrings to public modules, classes, and functions when helpful.

## Design

- Apply single responsibility rigorously.
- Use dependency injection where it improves testability.
- Keep configuration centralized.
- Separate pure logic from side effects.

## Reliability

- Reject uncertain results instead of guessing.
- Surface clear exceptions or error messages for recoverable failures.
- Write code that can run continuously without leaking resources.
