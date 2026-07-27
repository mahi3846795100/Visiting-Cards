# Business Contact Scanner

Business Contact Scanner is a local-only Windows desktop application for high-reliability scanning of business visiting cards at scale. The project is designed to continuously process large volumes of cards with minimal user interaction while prioritizing accuracy, stability, and maintainability.

This repository is currently in the foundation phase. No production scanning logic is implemented yet. The initial goal is to establish a professional project structure, documentation system, phase roadmap, and Python 3.12 packaging baseline before any computer vision or OCR work begins.

## Project Vision

The long-term goal is a business contact intelligence system that can reliably detect cards, process front and back images, extract business information, prevent duplicates, and store organized contact assets locally.

The software is intentionally phase-driven:

- Phase 0 establishes the environment, structure, configuration, and test baseline.
- Phase 1 introduces visiting card detection only.
- Later phases add processing, OCR, extraction, duplicate handling, storage, workflow automation, GUI, testing, packaging, and intelligence features.

## Current Status

- Repository foundation initialized
- Documentation scaffolded
- Phase roadmap defined
- Package layout created
- Application logic intentionally deferred

## Principles

- Local execution only
- No cloud dependency
- No internet dependency
- Accuracy over speed
- Reject uncertain detections
- Modular architecture
- Small testable components
- Strict phase separation

## Repository Layout

- docs/ contains development, testing, coding, and architecture guidance
- phases/ defines the scope of each development phase
- src/ is reserved for application packages
- tests/ contains the initial test baseline
- assets/, temp/, and logs/ are workspace directories for runtime use

## Next Milestone

The next stage of work is Phase 0 implementation, which will cover environment setup, configuration, camera initialization scaffolding, and basic testing support without adding future-phase functionality.