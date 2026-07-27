# Phase 1 - Visiting Card Detection Engine

## Objective

Determine whether exactly one valid visiting card is present in front of the camera.

## Scope

- Card presence detection
- Single-card validation
- Rejection of uncertain detections
- Detection result reporting

## Exclusions

- Card cropping
- Perspective correction
- Deskewing
- Image enhancement
- OCR
- Data extraction
- Duplicate detection
- Storage
- GUI work

## Deliverables

- Detection engine
- Validation rules for a valid card presence
- Unit tests for detection behavior

## Success Criteria

- The system can distinguish valid single-card presence from invalid or ambiguous scenes.
- False positives are minimized by rejecting uncertain inputs.
- The phase remains isolated from later processing stages.
