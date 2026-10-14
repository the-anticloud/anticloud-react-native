# Ethics — REACT_NATIVE

**Project:** REACT_NATIVE  
**Category:** MOBILE  
**Upstream:** https://github.com/facebook/react-native  
**Pinned commit:** `e82a8e4e5710be97bf2f98ad4e5b2e1019df059c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d405584b0a2085de54f38f6a9ec8f7580d65b5e2f0413eaebfcf42e49e70efad`  
**Date:** October 2026

## Position

REACT_NATIVE is packaged for offline deployment with a verifiable audit trail. The
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
