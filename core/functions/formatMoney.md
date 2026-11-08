[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / formatMoney

# Function: formatMoney()

> **formatMoney**(`cents`, `currency?`, `locale?`): `string`

Defined in: [core/utils.ts:56](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/utils.ts#L56)

Format money for display.

## Parameters

### cents

`number`

Amount in cents

### currency?

[`CurrencyCode`](../type-aliases/CurrencyCode.md) = `'usd'`

Currency code (default: usd)

### locale?

`string` = `'en-US'`

Locale for formatting (default: en-US)

## Returns

`string`

Formatted currency string

## Example

```typescript
formatMoney(1050); // "$10.50"
```
