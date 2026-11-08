[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / CloverHost

# Type Alias: CloverHost

> **CloverHost** = `"ecommerce"` \| `"platform"`

Defined in: [core/types/index.ts:22](https://github.com/Bates-Solutions/clover/blob/40568e0a95019adb2af4cb858720aefc035388af/src/core/types/index.ts#L22)

Which Clover host an operation targets.

- `ecommerce` — the Stripe-shaped `/v1/...` API (charges, refunds, tokens) on
  `scl(-sandbox).dev.clover.com`.
- `platform` — the `/v3/merchants/{mId}/...` REST API (customers, orders,
  inventory) on `api(sandbox).dev.clover.com`.
