# Compliance — REACT_NATIVE

**Project:** REACT_NATIVE  
**Category:** MOBILE  
**Upstream:** https://github.com/facebook/react-native  
**Pinned commit:** `e82a8e4e5710be97bf2f98ad4e5b2e1019df059c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d405584b0a2085de54f38f6a9ec8f7580d65b5e2f0413eaebfcf42e49e70efad`  
**Date:** October 2026

## Position

REACT_NATIVE is mapped against eleven frameworks in `BENCH.json`:
OWASP LLM Top 10, OWASP Top 10 (2021), SOC 2 Type II readiness, NIST AI RMF,
NIST SP 800-53 Rev. 5, NIST CSF 2.0, FedRAMP Rev. 5, PCI DSS v4.0.1,
ISO/IEC 27001:2022, MITRE ATT&CK v16, and ML TRL.

**Current result: 16/16 checks passing.**

## What the mapping asserts

For each framework, every in-scope control is bound to a named evidence source
in this project, and that source exists and is re-runnable. The control counts
and evidence counts are recorded per framework in `BENCH.json`.

## What is not claimed

No audit opinion, SOC report, FedRAMP authorisation, PCI attestation or ISO
certificate is held. Those are issued by an independent assessor against a
defined period of operation; no project can self-issue one. See
`OFFICIAL_BENCHMARKS/` for the per-framework scope statement.

## Verification

Open `ISOLATED_LAB_RESULTS/03_Result_Register.md`, read a row, recompute the
SHA3-256 of its evidence file in `04_Evidence/`, compare.
