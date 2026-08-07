# Dual-write

- Write path must handle partial failure policy (which store is source of truth)
- Idempotency keys required
- Lag metrics between stores
- Stop dual-write only after verification window
