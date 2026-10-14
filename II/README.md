# Independent Insurance — FRAPPE

**Project:** FRAPPE  
**Category:** ENGINEERING_CONSTRUCTION  
**Upstream:** https://github.com/frappe/frappe  
**Pinned commit:** `ada0e11941afb860fa865131f939d80143353d63`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7d693ab4f6a4335ff509c19c2841aaedb2a3d5711816ddd12c53f6b552b74205`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | FRAPPE with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `7d693ab4f6a4335ff509c19c2841aaedb2a3d5711816ddd12c53f6b552b74205`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
