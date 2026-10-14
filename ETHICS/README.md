# Ethics — FLUENTUI

**Project:** FLUENTUI  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/microsoft/fluentui  
**Pinned commit:** `cdb17d0b39aae1c544ddcce0f5140c3dfc9f6aad`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c6976929d2ff0e052f009fca77be4835819abe728e6ca1b764a227e27afa08a9`  
**Date:** October 2026

## Position

FLUENTUI is packaged for offline deployment with a verifiable audit trail. The
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
