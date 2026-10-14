# Students — VISERON

**Project:** VISERON  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** see BENCH.json  
**Pinned commit:** `4b63f8edf2ac1664ad41ebb0f5920f9b861a34f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `35d623c2b886466d96095fe9ec48fee3ceae511a88be1d38920ab5ecab1372cd`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4b63f8edf2ac1664ad41ebb0f5920f9b861a34f0`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `35d623c2b886466d96095fe9ec48fee3ceae511a88be1d38920ab5ecab1372cd`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
