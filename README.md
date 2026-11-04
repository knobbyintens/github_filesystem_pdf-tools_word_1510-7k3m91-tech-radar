# Northwind Labs - AI Research Tech Radar

This repository is the system of record for paper-to-implementation adoption reviews.

## Layout
- `radar/registry.json` - review registry. Preserve every existing entry and append new reviews.
- `intake/archive/` - archived intake manuscripts (reference material only).
- One GitHub issue per intake item holds the review narrative.

## Issue conventions
- `[ADOPT] <owner>/<repo>` - implementation adopted; tier recorded in the body.
- `[WATCH] <owner>/<repo>` - runnable implementation that does not yet meet adoption criteria.
- `[HOLD] <intake_id>` - no runnable implementation repository found.

## Review expectations
Each issue body states the intake id, paper title, decision, tier (when applicable),
the repository URL (when applicable), and a short rationale.
