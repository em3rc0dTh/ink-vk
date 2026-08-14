# Dayos — Raw ZIP Ingest Status

**Date:** 2026-08-14  
**Status:** RAW BYTES VERIFIED LOCALLY / GITHUB BINARY INGEST BLOCKED BY CURRENT CONNECTOR

## What is complete

- All 11 user-supplied ZIP archives were opened and reviewed.
- All 66 PNG captures were recovered.
- Exact source filenames, byte sizes and SHA-256 values are recorded in `DAYOS_VISUAL_SOURCE_MANIFEST_v1.0.md`.
- The two reduced-zoom archives are explicitly marked so they cannot be misused as exact scale evidence.

## What is not complete

The current connected GitHub write surface exposes UTF-8 file creation and Git blob construction from caller-provided text/base64, but it does not expose a mounted-file/binary upload action. The original ZIPs are binary files up to several megabytes. Re-encoding or reconstructing them through chat-sized text payloads would weaken the guarantee that repository bytes are the untouched user source.

Therefore the original ZIP bytes are **not represented as uploaded in this branch**.

Ink-VK source governance prefers an explicit incomplete ingest over silently changing a raw source artifact.

## Verification contract

Any later raw-byte ingest is valid only if the repository ZIP hashes match the manifest exactly.

Expected archives:

- `dayos-home-view.zip`
- `dayos-navbar-view.zip`
- `dayos-hero-answers-view.zip`
- `dayos-hero-actions-view.zip`
- `dayos-hero-experts-view.zip`
- `dayos-solutions-itmanagement-view-reduced.zip`
- `dayos-use-cases-view-reduced.zip`
- `dayos-plans-view.zip`
- `dayos-partnership-view.zip`
- `dayos-company-view.zip`
- `dayos-schedule-demo-view.zip`

See `DAYOS_VISUAL_SOURCE_MANIFEST_v1.0.md` for exact SHA-256 values.
