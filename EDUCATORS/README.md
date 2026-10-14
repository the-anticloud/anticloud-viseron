# Educators — VISERON

**Project:** VISERON  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** see BENCH.json  
**Pinned commit:** `4b63f8edf2ac1664ad41ebb0f5920f9b861a34f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `35d623c2b886466d96095fe9ec48fee3ceae511a88be1d38920ab5ecab1372cd`  
**Date:** October 2026

## Teaching with VISERON

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `35d623c2b886466d96095fe9ec48fee3ceae511a88be1d38920ab5ecab1372cd` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
