[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / OrderExpand

# Type Alias: OrderExpand

> **OrderExpand** = `"lineItems"` \| `"lineItems.discounts"` \| `"lineItems.modifications"` \| `"payments"` \| `"payment.tender"` \| `"payment.cardTransaction"` \| `"refunds"` \| `"credits"` \| `"voids"` \| `"employee"` \| `"customers"` \| `"discounts"` \| `"serviceCharge"` \| `"orderType"` \| `string` & `object`

Defined in: [core/services/orders.service.ts:11](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/services/orders.service.ts#L11)

Related data Clover can embed in an order response (`expand`).

Any other string is also accepted so new Clover expansions work without a
library update.
