# Development Guidelines

## Working Model

- Develop one phase at a time.
- Keep implementation focused on the current phase scope.
- Avoid speculative abstractions that are not needed yet.
- Prefer incremental, reviewable changes.

## Code Organization

- Use the `src/` layout.
- Separate domain logic from UI concerns.
- Keep vision, processing, workflow, storage, and utility code isolated.
- Favor small modules with clear responsibilities.

## Quality Expectations

- Write code that is testable without the GUI.
- Use logging for operational visibility.
- Handle errors gracefully and return useful diagnostics.
- Avoid duplication and implicit behavior.

## Phase Control

- Do not add future-phase imports, dependencies, or placeholders.
- Do not implement stubs that pretend to be complete features.
- When a phase is finished, document the exact outcome and remaining boundaries.
