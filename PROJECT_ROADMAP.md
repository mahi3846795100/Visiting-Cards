# Project Roadmap

## Mission

Build a reliable local Windows application that can continuously scan large volumes of business visiting cards with minimal user interaction, while keeping accuracy, stability, and maintainability as first-class requirements.

## Delivery Model

The project is intentionally phase-based. Each phase must be production-ready before the next phase begins. Future functionality must not leak into earlier phases.

## Phases

### Phase 0 - Environment Setup

Goal: establish the repository foundation, Python 3.12 packaging baseline, configuration system, and basic testing support.

### Phase 1 - Visiting Card Detection Engine

Goal: determine whether exactly one valid visiting card is present in front of the camera.

### Phase 2 - Card Processing Engine

Goal: perform automatic cropping, perspective correction, deskew, enhancement, and quality validation.

### Phase 3 - OCR Engine

Goal: integrate PaddleOCR for raw text extraction and confidence scoring.

### Phase 4 - Business Information Extraction

Goal: extract company name, person name, designation, phone, email, website, address, and LinkedIn information.

### Phase 5 - Duplicate Detection

Goal: identify duplicate cards using image hashing and similarity matching.

### Phase 6 - Storage Engine

Goal: create folders, apply naming conventions, and save images locally.

### Phase 7 - Front and Back Capture Workflow

Goal: automate capture of the front and back of a card with flip detection.

### Phase 8 - Continuous Scanning Engine

Goal: enable high-speed continuous processing and readiness for the next card.

### Phase 9 - Desktop GUI

Goal: provide settings, scanner screen, statistics, and developer mode.

### Phase 10 - Integration Testing

Goal: validate the full stack under stress and large dataset conditions.

### Phase 11 - Windows EXE

Goal: package and distribute the application as a Windows executable and installer.

### Phase 12 - Business Contact Intelligence System

Goal: expand the system into searchable contact intelligence with CRM, analytics, AI, and relationship management features.

## Phase Gates

A phase may close only when:

- Scope is complete.
- Tests pass for the touched surface.
- The implementation remains backward compatible.
- Documentation is updated to reflect the phase state.
- No future-phase code has been introduced prematurely.
