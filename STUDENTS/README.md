# Students — FLUENTUI

**Project:** FLUENTUI  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/microsoft/fluentui  
**Pinned commit:** `cdb17d0b39aae1c544ddcce0f5140c3dfc9f6aad`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c6976929d2ff0e052f009fca77be4835819abe728e6ca1b764a227e27afa08a9`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `cdb17d0b39aae1c544ddcce0f5140c3dfc9f6aad`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `c6976929d2ff0e052f009fca77be4835819abe728e6ca1b764a227e27afa08a9`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
