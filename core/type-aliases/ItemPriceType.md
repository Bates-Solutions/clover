[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / ItemPriceType

# Type Alias: ItemPriceType

> **ItemPriceType** = `"FIXED"` \| `"VARIABLE"` \| `"PER_UNIT"`

Defined in: [core/services/inventory.service.ts:10](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/services/inventory.service.ts#L10)

How an item is priced. `PER_UNIT` items are sold by weight or measure
(`unitName`), `VARIABLE` items get their price at the register.
