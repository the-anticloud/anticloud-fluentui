# Educators — FLUENTUI

**Project:** FLUENTUI  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/microsoft/fluentui  
**Pinned commit:** `cdb17d0b39aae1c544ddcce0f5140c3dfc9f6aad`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c6976929d2ff0e052f009fca77be4835819abe728e6ca1b764a227e27afa08a9`  
**Date:** October 2026

## Teaching with FLUENTUI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c6976929d2ff0e052f009fca77be4835819abe728e6ca1b764a227e27afa08a9` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
