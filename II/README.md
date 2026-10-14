# Independent Insurance — VISERON

**Project:** VISERON  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** see BENCH.json  
**Pinned commit:** `4b63f8edf2ac1664ad41ebb0f5920f9b861a34f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `35d623c2b886466d96095fe9ec48fee3ceae511a88be1d38920ab5ecab1372cd`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | VISERON with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `35d623c2b886466d96095fe9ec48fee3ceae511a88be1d38920ab5ecab1372cd`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
