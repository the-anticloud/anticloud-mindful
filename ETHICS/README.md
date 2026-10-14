# Ethics — MINDFUL

**Project:** MINDFUL  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/akaMrNagar/Mindful  
**Pinned commit:** `b6eb68d500463c54e1127b6cc7ad540f02ae0c8e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5995d345c708f14163d38efb514495491a30bd373b7ae3fe37113af5ab35fdbd`  
**Date:** October 2026

## Position

MINDFUL is packaged for offline deployment with a verifiable audit trail. The
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
