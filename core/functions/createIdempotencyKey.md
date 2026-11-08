[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / createIdempotencyKey

# Function: createIdempotencyKey()

> **createIdempotencyKey**(): `string`

Defined in: [core/utils.ts:76](https://github.com/Bates-Solutions/clover/blob/40568e0a95019adb2af4cb858720aefc035388af/src/core/utils.ts#L76)

Create a unique idempotency key for Clover requests.

Uses WebCrypto `randomUUID`, so it runs on any modern runtime (Node 22+,
Deno, Bun, Cloudflare Workers).

## Returns

`string`

UUID string
