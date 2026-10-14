# Ethics — FRAPPE

**Project:** FRAPPE  
**Category:** ENGINEERING_CONSTRUCTION  
**Upstream:** https://github.com/frappe/frappe  
**Pinned commit:** `ada0e11941afb860fa865131f939d80143353d63`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7d693ab4f6a4335ff509c19c2841aaedb2a3d5711816ddd12c53f6b552b74205`  
**Date:** October 2026

## Position

FRAPPE is packaged for offline deployment with a verifiable audit trail. The
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
