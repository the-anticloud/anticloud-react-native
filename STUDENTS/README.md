# Students — REACT_NATIVE

**Project:** REACT_NATIVE  
**Category:** MOBILE  
**Upstream:** https://github.com/facebook/react-native  
**Pinned commit:** `e82a8e4e5710be97bf2f98ad4e5b2e1019df059c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d405584b0a2085de54f38f6a9ec8f7580d65b5e2f0413eaebfcf42e49e70efad`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e82a8e4e5710be97bf2f98ad4e5b2e1019df059c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `d405584b0a2085de54f38f6a9ec8f7580d65b5e2f0413eaebfcf42e49e70efad`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
