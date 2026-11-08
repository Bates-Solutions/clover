[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / RequestOptions

# Interface: RequestOptions

Defined in: [core/http.ts:38](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/http.ts#L38)

Options for a single request.

## Properties

### body?

> `optional` **body?**: `unknown`

Defined in: [core/http.ts:45](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/http.ts#L45)

JSON request body

***

### idempotencyKey?

> `optional` **idempotencyKey?**: `string`

Defined in: [core/http.ts:47](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/http.ts#L47)

Idempotency key, sent as the `idempotency-key` header

***

### query?

> `optional` **query?**: `Record`\<`string`, `string` \| `number` \| `string`[] \| `undefined`\>

Defined in: [core/http.ts:43](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/http.ts#L43)

Query-string parameters. An array repeats the key once per value, which is
how Clover takes several `filter` parameters.
