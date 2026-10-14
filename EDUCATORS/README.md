# Educators — FRAPPE

**Project:** FRAPPE  
**Category:** ENGINEERING_CONSTRUCTION  
**Upstream:** https://github.com/frappe/frappe  
**Pinned commit:** `ada0e11941afb860fa865131f939d80143353d63`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7d693ab4f6a4335ff509c19c2841aaedb2a3d5711816ddd12c53f6b552b74205`  
**Date:** October 2026

## Teaching with FRAPPE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `7d693ab4f6a4335ff509c19c2841aaedb2a3d5711816ddd12c53f6b552b74205` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
