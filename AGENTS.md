# AGENTS.md

This repository is a phase-driven, local-only computer vision project for business visiting cards. Future AI sessions must follow these rules.

## Core Rules

- Work in strict phase order.
- Do not implement future-phase functionality early.
- Do not create placeholder implementations, mock pipelines, or fake integrations for later phases.
- Keep changes production-oriented and maintainable.
- Prefer correctness and reliability over speed.
- Keep everything local and offline.
- Avoid cloud services, remote APIs, and internet dependencies.

## Architecture Rules

- Use modular architecture.
- Keep components small, focused, and reusable.
- Separate computer vision, OCR, storage, workflow, and GUI responsibilities.
- Use dependency injection where it improves testability.
- Prefer explicit types, docstrings, and clear naming.
- Avoid God classes and long functions.
- Do not hardcode configuration values when they can be defined centrally.
- Add logging and meaningful error handling for recoverable failures.

## Phase Discipline

- Phase 0 is limited to environment setup, repository structure, configuration, and basic testing support.
- Phase 1 is limited to visiting card detection.
- Later phases must not be partially introduced inside earlier phases.
- Every phase must be completed and stable before moving to the next.
- Preserve backward compatibility with completed phases.

## Testing Rules

- Every meaningful function should be testable in isolation.
- Add or update tests alongside functional changes.
- Validate the touched slice before broadening scope.
- Do not skip tests for critical logic.

## Implementation Boundaries

- Do not add GUI code until the GUI phase.
- Do not add OCR code until the OCR phase.
- Do not add storage logic until the storage phase.
- Do not add duplicate detection logic until the duplicate phase.
- Do not add workflow automation beyond the declared phase scope.

## Documentation Rules

- Keep the roadmap, phase docs, and architecture docs current.
- Record important project constraints when they affect future work.
- Use the repository structure as the source of truth for phase boundaries.
