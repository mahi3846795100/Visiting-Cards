# Architecture

## System View

Business Contact Scanner is intended to evolve into a modular desktop application with a camera input layer, a vision and processing layer, OCR, extraction, duplicate detection, storage, workflow automation, and a GUI.

## Structural Rules

- Keep each subsystem isolated behind clear interfaces.
- Do not couple UI code to core vision logic.
- Keep storage and file-system behavior separate from analysis logic.
- Prefer composition over monolithic classes.

## Current Foundation

The repository currently contains only the project scaffold. No runtime pipeline is implemented yet. Phase 0 should add only the minimal structure required to support later phases safely.
