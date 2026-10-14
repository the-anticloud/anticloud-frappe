# Students — FRAPPE

**Project:** FRAPPE  
**Category:** ENGINEERING_CONSTRUCTION  
**Upstream:** https://github.com/frappe/frappe  
**Pinned commit:** `ada0e11941afb860fa865131f939d80143353d63`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7d693ab4f6a4335ff509c19c2841aaedb2a3d5711816ddd12c53f6b552b74205`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ada0e11941afb860fa865131f939d80143353d63`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `7d693ab4f6a4335ff509c19c2841aaedb2a3d5711816ddd12c53f6b552b74205`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
