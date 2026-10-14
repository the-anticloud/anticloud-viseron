# Ethics — VISERON

**Project:** VISERON  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** see BENCH.json  
**Pinned commit:** `4b63f8edf2ac1664ad41ebb0f5920f9b861a34f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `35d623c2b886466d96095fe9ec48fee3ceae511a88be1d38920ab5ecab1372cd`  
**Date:** October 2026

## Position

VISERON is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
