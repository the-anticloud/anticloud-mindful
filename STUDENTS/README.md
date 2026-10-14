# Students — MINDFUL

**Project:** MINDFUL  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/akaMrNagar/Mindful  
**Pinned commit:** `b6eb68d500463c54e1127b6cc7ad540f02ae0c8e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5995d345c708f14163d38efb514495491a30bd373b7ae3fe37113af5ab35fdbd`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `b6eb68d500463c54e1127b6cc7ad540f02ae0c8e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5995d345c708f14163d38efb514495491a30bd373b7ae3fe37113af5ab35fdbd`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
