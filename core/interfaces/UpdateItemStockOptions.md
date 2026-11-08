[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / UpdateItemStockOptions

# Interface: UpdateItemStockOptions

Defined in: [core/services/inventory.service.ts:162](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/services/inventory.service.ts#L162)

Options for `inventory.updateItemStock()`.

## Properties

### idempotencyKey?

> `optional` **idempotencyKey?**: `string`

Defined in: [core/services/inventory.service.ts:166](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/services/inventory.service.ts#L166)

Idempotency key (defaults to a generated UUID)

***

### quantity

> **quantity**: `number`

Defined in: [core/services/inventory.service.ts:164](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/services/inventory.service.ts#L164)

New stock count. Replaces the current quantity; it is not added to it.
